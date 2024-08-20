---
icon: book
---

# Gnome

## Что такое Gnome?

GNOME  — [свободная](https://ru.wikipedia.org/wiki/%D0%A1%D0%B2%D0%BE%D0%B1%D0%BE%D0%B4%D0%BD%D0%BE%D0%B5\_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B5\_%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D0%B5) [среда рабочего стола](https://ru.wikipedia.org/wiki/%D0%A1%D1%80%D0%B5%D0%B4%D0%B0\_%D1%80%D0%B0%D0%B1%D0%BE%D1%87%D0%B5%D0%B3%D0%BE\_%D1%81%D1%82%D0%BE%D0%BB%D0%B0) для [UNIX-подобных операционных систем](https://ru.wikipedia.org/wiki/UNIX-%D0%BF%D0%BE%D0%B4%D0%BE%D0%B1%D0%BD%D0%B0%D1%8F\_%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F\_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0).

<figure><img src="../.gitbook/assets/obraz (15).png" alt=""><figcaption></figcaption></figure>

## Как скачать Gnome? <a href="#gde-skachat-fedora-linux" id="gde-skachat-fedora-linux"></a>

Сначала установим графический дисплейный менеджер и базовые пакеты. Список пакетов вы можете изменять в соответствии с вашим опытом предпочтениями и знаниями.

```bash
sudo dnf install gdm gnome-shell nautilus gnome-terminal gnome-system-monitor xdg-user-dirs-gtk fedora-workstation-backgrounds
```

Далее включим его, переключимся в графический режим, перезагрузимся:

```bash
sudo systemctl enable gdm
sudo systemctl set-default graphical.target
reboot
```

## Fedora Workstation

{% embed url="https://fedoraproject.org/workstation/" %}
