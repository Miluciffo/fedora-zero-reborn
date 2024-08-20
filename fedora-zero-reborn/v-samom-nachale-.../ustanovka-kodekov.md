---
description: Мультимедийные кодеки для Fedora Linux
---

# Установка кодеков

Не воспроизводиться видео? Установи кодеки!

<figure><img src="../../.gitbook/assets/obraz (13).png" alt=""><figcaption></figcaption></figure>

```
sudo dnf install gstreamer1-plugins-{bad-\*,good-\*,base} gstreamer1-plugin-openh264 gstreamer1-libav --exclude=gstreamer1-plugins-bad-free-devel
```

```
sudo dnf install lame\* --exclude=lame-devel
```

```
sudo dnf group upgrade --with-optional Multimedia
```
