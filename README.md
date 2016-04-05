# BitBar [Battery health](http://github.com/tanrax/bitbar-batteryHealth) Plugin

## What does?

The best way to maintain a healthy battery is having it, aproximadamante, between 85% and 45%. This plugin will alert you whenever you leave these values. With a notification and a red circle. And it will show the percentage of battery.

![BitBar plugin battery Health](https://programadorwebvalencia.com/wp-content/uploads/2016/04/Screen-Shot-2016-04-05-at-12.47.25.jpg)
![BitBar plugin battery Health](https://programadorwebvalencia.com/wp-content/uploads/2016/04/Screen-Shot-2016-04-05-at-12.45.39.jpg)

## Installation

To install bitbar, run:
```
brew cask install bitbar
```

To install **Battery health**, run:
```
cd ~/your/plugin/path/
wget https://raw.githubusercontent.com/tanrax/bitbar-batteryHealth/master/battery_health.60s.sh
chmod +x battery_health.60s.sh
```

## Where's my plugin path?

If you do not know your plugin path, run:

```
open ~/Library/Preferences/com.matryer.BitBar.plist
```

and edit your `pluginsPath` key.

---

## License

MIT License, Copyright (c) 2016 Andros Fenollosa
