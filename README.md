
# Cydia users

```diff
- ⚠️ Karen's repo is needed, as tweak relies on AppSync Unified to be able to allow app to play
- background audio for the speed limit alert feature.
```
[🚨 Before installing this tweak, tap on this link to add Appsync's repo repo](https://cydia.akemi.ai/add.php)

# OnewheelEnhancer

OnewheelEnhancer is an iOS tweak runnable on jailbroken devices. 
Upon installing, it'll patch FutureMotion's official app to support background audio mode to enable speed alerts.

# Features

  - Live cells voltage tracking
  - Helps spotting weaks cells (higher cells are displayed in green, cells weaker by 0.03V will be in green, weakers than 0.06V in red)
  - Battery percentage calculable using voltage instead of BMS value (Useful if using an XXR-mod for example)
  - Speed alert settable. You'll receive a push notification along with an alarm ringing from your phone if you exceed this max speed
  - Displays original cells type delivered with your BMS. If you replaced your battery pack with another cells type, a wrong information will be displayed.

### Installation

##### Download from cydia
Add my repo to Cydia by clicking [this link](https://thibauddavid.github.io/cydiarepo/) from your jailbroken iPhone and tap on link to install source, then install onewheelenhancer

##### Install from .deb file
Use `scp` to send .deb to your device, then install it using `dpkg -i /path/to/package.deb`

#### Building for source
This package is build using Theos. Follow [their instructions](https://github.com/theos/theos/wiki/Installation) to install it.
Once done, just `cd` to onewheelenhancer path then use `make package install`

### Todos

 - Plot cells status over time
 
**Ride on !**
