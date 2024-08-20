---
description: Для обладателей твердотельных накопителей SSD.
---

# Fstab

## Что такое Fstab?

Fstab — один из конфигурационных файлов в [UNIX-подобных системах](https://ru.wikipedia.org/wiki/UNIX-%D0%BF%D0%BE%D0%B4%D0%BE%D0%B1%D0%BD%D0%B0%D1%8F\_%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F\_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0), который содержит информацию о различных файловых системах и устройствах хранения информации компьютера; описывает, как диск (раздел) будет использоваться или как будет интегрирован в систему.

## Настройка Fstab

{% hint style="warning" %}
Помимо стандартных параметров монтирования я через запятую добавляю ещё эти 3 после **`compress=zstd:1`**
{% endhint %}

**Открываем `fstab` командой в терминале (CTRL+ALT+T):**

```bash
sudo gnome-text-editor /etc/fstab
```

**и добавляем данные параметры после `compress=zstd:1`**

```bash
,defaults,noatime,discard=async
```

Для разделов: `/, /home, /var/log`

<figure><img src="../../.gitbook/assets/obraz (4).png" alt=""><figcaption><p>Редактирование Fstab в GNU/Linux</p></figcaption></figure>
