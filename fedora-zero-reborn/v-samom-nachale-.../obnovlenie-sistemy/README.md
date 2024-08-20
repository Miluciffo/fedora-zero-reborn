---
description: Полное обновление системы Fedora Linux
---

# Обновление системы

Для полного обновления системы выполняем команду в терминале (CTRL+ALT+T):

```bash
sudo dnf upgrade --refresh
```

{% hint style="warning" %}
Тем не менее, команда Fedora Linux рекомендует обновляться штатным способом через магазин приложений Gnome Software.
{% endhint %}

<figure><img src="../../../.gitbook/assets/obraz (10).png" alt=""><figcaption><p>Gnome Software на Fedora Linux</p></figcaption></figure>

## Можно ли обновляться "через версию"? <a href="#mozhno-li-obnovlyatsya-cherez-versiyu" id="mozhno-li-obnovlyatsya-cherez-versiyu"></a>

{% hint style="info" %}
#### Можно ли обновляться "через верОфициально поддерживается лишь обновление с текущей на следующую версию. Если требуется выполнить обновление сразу через несколько релизов дистрибутива, то настоятельно рекомендуется делать это последовательно (например F27 -> F28 -> F29 -> F30 и т.д.). <a href="#mozhno-li-obnovlyatsya-cherez-versiyu" id="mozhno-li-obnovlyatsya-cherez-versiyu"></a>

В любом случае, можно обновляться через релиз, как показала практика нет никаких проблем с этим.
{% endhint %}

## При каждом релизе нужно ставить всё с нуля? <a href="#pri-kazhdom-relize-nuzhno-stavit-vsyo-s-nulya" id="pri-kazhdom-relize-nuzhno-stavit-vsyo-s-nulya"></a>

{% hint style="info" %}
Нет! Конечно-же нет! На момент официального релиза, в ваш магазин приложений, в раздел "Обновления" прилетит банер с предложением обновиться до самой новой версии Fedora. Обновляться сразу не обязательно!
{% endhint %}

<figure><img src="../../../.gitbook/assets/obraz (3).png" alt=""><figcaption><p>Gnome Software на Fedora Linux</p></figcaption></figure>

## Какой цикл обновлений у Fedora Linux? <a href="#kakoi-cikl-obnovlenii-u-fedora-linux" id="kakoi-cikl-obnovlenii-u-fedora-linux"></a>

{% hint style="info" %}
Цикл обновлений у Fedora Linux составляет от 6 до 8 месяцев, при этом как говорилось выше, необязательно обновляться с версию на версию, можно делать это поэтапно, либо через версию.

Даже если вы не обновитесь на самую актуальную версию, обновления безопасности и ваших приложений, будут приходить в штатном режиме.
{% endhint %}
