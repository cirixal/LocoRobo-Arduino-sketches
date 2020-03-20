# LocoRobo - Pololu Zumo 32u4

I got one of these robots on used, with no documentation, or other information.  
I did look on the locorobo website, but didn't find any thing that was helpful, if these were open source, I'm having a hard time finding the source code.  
Luckly the base plateform is a Pololu Zumo 32u4, it has the zumo push bar removed, doesn't have a line sensor, and didn't have the LCD. But at least I can make it work :-)  

This is a few things I learned, it's not a complete project, it may or may not be helpful for other people who have these little robots and not sure what to do with them.  

## Installation

To use this effectly follow the instructions on the Pololu website for the Arduino IDE.  
https://www.pololu.com/category/170/zumo-32u4-robot  
https://www.pololu.com/docs/0J63  

Most of the examples will work, with out making changes.  

The Ultrasonic is hooked up to A0, A3. The Neopixels are hooked to A2.  I couldn't get the bluetooth to work, not sure, it almost appears to be a pass thur, but everything I tried said no.  
The bluetooth dongle that came with mine, did help a little, in a terminal program I was able to get the BLE to response with the word "Alive" when zero was pushed. But other then that, I couldn't get it to do anything.  
And couldn't figure out how it was talking to the Leonardo board.  

That is about it. If you know anything else or have a sketch that will work with it, let me know.  

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Support Me

If you find this or any of my projects useful or enjoyable please support me.  
Anything I do get goes to buy more parts and make more/better projects.  
https://www.patreon.com/kd8bxp  
https://ko-fi.com/lfmiller  
https://www.paypal.me/KD8BXP  

## Other Projects

https://www.youtube.com/channel/UCP6Vh4hfyJF288MTaRAF36w  
https://kd8bxp.blogspot.com/  


## Credits

Copyright (c) 2020 LeRoy Miller

## License

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses>
