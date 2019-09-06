# Eat all the cookies on the tray!

Magic Cookies is our first commercial Haskell game. It's available for iOS on the [AppStore](https://itunes.apple.com/us/app/magic-cookies/id1244709871) and for Android on [Google Play](https://play.google.com/store/apps/details?id=uk.co.keera.games.magiccookies)!

<p align="center">
<img src="https://github.com/keera-studios/magic-cookies/raw/master/screencap.gif" alt="Screen capture of Magic Cookies on iOS" /> <br /> Screen capture of Magic Cookies on iOS
</p>

# Something doesn't work
Sorry to hear that. Please, open a new [issue](https://github.com/keera-studios/magic-cookies/issues/new) or send an email to [support@keera.co.uk](mailto:support@keera.co.uk). Please, be aware that issues reported using github are visible to everybody. If you are including confidential information, please send us an email.

# Follow us!
We often comment on our progress on [Facebook](http://facebook.com/keerastudios) and [Twitter](http://twitter.com/KeeraStudios). Please, follow us. Everything we publish has to do with multimedia and games in Haskell and other functional languages.

# FAQ
## What technology have you used?
The game is written in Haskell. For Android, there's a C and Java wrapper that merely invoke our Haskell main. For iOS, that part is done in objective C. It uses SDL2 for multimedia. The core uses the Functional Reactive Programming library [Yampa](http://github.com/ivanperez-keera/Yampa).

## Is your game open source?
Currently, **not**. We use this repo for issue tracking, so that github users have a quick and easy way to report issues, communicate with us and be notified when they are solved. Some of the (general purpose) code does make it into public and open source projects, though.

You may want to take a look at the Open Source game [Haskanoid](http://github.com/ivanperez-keera/haskanoid), which supports Wiimote & Kinect and is also written in Haskell using [Yampa](http://github.com/ivanperez-keera/Yampa).

We do not discard the possibility of making the game open source in the future.

## Isn't it a bit strange, to use github for a closed-source project?
Possibly, but Github doesn't have a problem with that (we spoke with them directly before doing it). They offer a great issue tracking system. This way users don't need to create new accounts elsewhere, or give us their email addresses.

We also publish [open](https://github.com/keera-studios/keera-hails) [source](https://github.com/keera-studios/keera-posture) [code](https://github.com/keera-studios/keera-callbacks) on Github.

# Thank you
We'd like to thank:
* The Haskell community, for creating such an awesome language and the right tools to build this. In particular, we'd like to thank the creators of the GHC Android and iOS backends.
* Github, for letting us host our repos here.
* The [Programming Haskell](https://www.facebook.com/groups/programming.haskell/) Facebook group for their constant praise and encouragement.
* Everyone who wrote to us with kind words of support :)
* Everyone who Flattred.
* Our beta testers, who put up with slow, heavy, boring versions until we got to a reasonably stable version. For privacy reasons we cannot publish their names, but we thank them for all their help.
* Those who buy the app. Please buy the app! We only get a very small fee for every customer, so we need to sell thousands to get enough money to pay the bills and publish the next game. We are already working on it!

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ivanperez-keera&url=https://github.com/keera-studios/magic-cookies&title=Magic%20Cookies&language=&tags=github&category=software)
