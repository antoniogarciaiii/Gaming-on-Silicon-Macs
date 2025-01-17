# Gaming-on-Silicon-Macs
Personal list of PC games I've tested to work on Macs with a Silicon processor

Once I figure out how to make a basic webpage with a spreadsheet, I'll do that. In the meantime, here is what I've tested:

## Little Kitty, Big City
### Bulletpoints
* Using this installation of Little Kitty, Big City: https://fitgirl-repacks.site/little-kitty-big-city/
* Running on Whisky: https://getwhisky.app/
* Used an Xbox One S Controller connected via Bluetooth
### Notes
I got it to run by doing the following
* using a (VMWare) virtual machine running a 64-bit ARM version of windows, I was able to run the installer. I then copied the application folder fromm the virtual machine to the C: Drive in my Whisky "bottle," and ran it from there. I did not seem to need to use anny startup arguments.

### Problems
* although I am using a controller, it sometimes gives me odd inputs. For example if I move the camera, I'll get random input from a completelly different direction. Sometimes a reboot seems to fix the issue. I'd like to find a permanent fix. The controller itself seems to be fine. I sometimes play games using Dolphin, and had never had a problem with it.
  
### New Findings using  [Kegworks Winery](https://github.com/Kegworks-App)
After learning about the [sudden end to Whisky's development yesterday](https://www.reddit.com/r/macgaming/comments/1i311cr/whisky_is_not_dead_yet_but_needs_your_help/), I learned how to use Kegworks to install the game

* Installation went fine using similar methods to Whiskey. Kegworks was installed using MacPorts, as opposed to Homebrew
* Performance is good, with some slight tearing, even after enabling V-Sync
