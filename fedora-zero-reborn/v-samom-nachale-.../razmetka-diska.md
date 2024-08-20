---
description: Ручная разметка в дистрибутиве Fedora Linux
---

# Разметка диска

{% hint style="info" %}
Всем пользователям, настоятельно рекомендуется использовать автоматическую разметку в установщике Fedorа Linux (Anaconda)
{% endhint %}

{% hint style="danger" %}
Будьте внимательны! Автоматическая установка полностью "затирает" диск куда будет устанавливаться система!
{% endhint %}

## Как установить Fedora в дуалбуте с Windows? <a href="#kak-ustanovit-fedora-v-dualbute-s-windows" id="kak-ustanovit-fedora-v-dualbute-s-windows"></a>

{% embed url="https://youtu.be/VaIgbTOvAd0" %}

## Ручная разметка Fedora Linux <a href="#ruchnaya-razmetka-fedora-linux" id="ruchnaya-razmetka-fedora-linux"></a>

{% embed url="https://youtu.be/DIp4yqIe8O4" %}

## Для того чтобы заработал Timeshift <a href="#dlya-togo-chtoby-zarabotal-timeshift" id="dlya-togo-chtoby-zarabotal-timeshift"></a>

{% hint style="info" %}
Чтобы всё заработало правильно, необходимо настроить правильно при ручной разметке в Blivet-GUI subvolumes для btrfs (порядок создания снизу-вверх!)
{% endhint %}



<figure><img src="../../.gitbook/assets/obraz (8).png" alt=""><figcaption></figcaption></figure>

```bash
@log /var/log
@home /home
@ /
```
