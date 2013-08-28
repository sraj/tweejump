# Tweejump

Notes on integrating HelpshiftSDK
==================================

1. Open ***tweejump.xcodeproj*** in XCode, navigate to ***tweejump*** and click on AppDelegate.m

2. Initialize Helpshift library by calling the method

   ```
   	[Helpshift installForAppID:@"<YOUR_APP_ID>"  domainName:@"<YOUR_COMPANY>.helpshift.com" apiKey:@"<YOUR_API_KEY>"];
   ```
   inside ***application:didFinishLaunchingWithOptions:*** method (ideally at the top)
   for more information [refer doc](http://www.helpshift.com/docs/howto/ios/v2.x/#authentication)

3. Refer ***supportCallback:*** method in tweejump/Classes/Game.m to show support screen, for more information [refer doc](http://www.helpshift.com/docs/howto/ios/v2.x/#decomposition)

![Tweejump](http://iplayful.com/tweejump/tweejump.jpg)

Jump on platforms, collect coins on the way, and get highest score.

* [Tweejump on the App Store][11] (Free)
* [Tweejump video on YouTube][12]

Powered by [Cocos2D][13] framework.

[11]: http://itunes.apple.com/us/app/tweejump/id318903704?mt=8
[12]: http://www.youtube.com/watch?v=AtPiVIlCfMY
[13]: http://www.cocos2d-iphone.org/

## Contributors

* Yannick Loriot
  * cocos2d version updated to 1.0.1
  * code ported to cocos2d 2.0 ([gles20 branch][21])

[21]: https://github.com/haqu/tweejump/tree/gles20

## License

The code is released under the [MIT License][31].

All images are copyrighted by [Sergey Tikhonov][32]. Please use them only for learning purposes, and don't release with your own project.

[31]: http://opensource.org/licenses/mit-license.php
[32]: http://haqu.net/
