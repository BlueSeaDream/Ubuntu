# Ubuntu
- Install the Chinese language pack: System Settings--> Language Support--> Install/Remove Languages
- Install the ibus: sudo apt-get install ibus ibus-clutter ibus-gtk ibus-gtk3 ibus-qt4
- Choose im-config -s ibus
- Install ibus pinyin: sudo apt-get install ibus-pinyin
- Restart the IBus daemon: ibus restart
- Launch the iBus Preferences: ibus-setup
- Choose Chinese - pinyin in input method
- Retrieve the disappearance of the IBus Icon: ibus-daemon -drx
- Choose the Chinese input method in System Settings --> Text Entry
