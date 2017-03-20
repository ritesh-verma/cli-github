
```
                                        CLI GitHub
                          A fancy GitHub client for command line.

                                    ..    ..::..    ..
                                  ..  ,,LLCCCCCCLL,,  ..
                                    ,,CCCCCCCCCCCCCC,,
                                    LLCC,,iiiiii,,CCLL
                                  ,,CCCC          CCCC,,
                                  ::CCLL  ......  ffCC::
                                  ,,CCCC    ..    CCCC,,
                                    CCCCLLii  ;;LLCCCC
                                    ;;CCffii  ttCCCC;;
                                  ..  ;;CC11  11CC;;  ..
                                    ..  ....  ....  ..







             :1ffftti,                .:::.    ,:::              :::,
           tCCCCCCCCCL  fCCf   .... . 1CCC1    LCCC,            ,CCCL .
          LCCCCLtttfL; .CCCC. ,CCCf . 1CCCt .. CCCC,            ,CCCL
         1CCCC.         ;ff;  ;CCCL,; 1CCC1    LCCC..;:;.  .;:;.,CCCL,i11;
         LCCC;  ;iiiii, CCCC.CCCCCCCC:iCCCCLLLLCCCC tCCCi  tCCCi.CCCCCCCCCC;
         LCCC:  CCCCCCf CCCC fLCCCCff.1CCCCCCCCCCCC tCCCi  tCCCi.CCCC1itCCCC
         LCCC;  tfLCCCt CCCC  ,CCCL . 1CCCf:;;:CCCC tCCCi  tCCCi.CCCL . LCCC:
         iCCCC.   iCCCt CCCC  :CCCL . 1CCC1    LCCC tCCCi  1CCCi.CCCL . LCCC:
          LCCCCLffLCCCf CCCC  .CCCCi1 1CCC1 .  CCCC tCCCLi1LCCCi.CCCC1itCCCC
           1CCCCCCCCCC1 CCCC   tCCCCC;iCCC1    LCCC..CCCCCCCCCCi.CCCCCCCCCC:
             .;1tt1i:   :;;:    ,i11i..;;;.    :;;;   :1t1i,.;;. ;;:.;111;
```

# `$ cli-github`

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Version](https://img.shields.io/npm/v/cli-github.svg)](https://www.npmjs.com/package/cli-github) [![Downloads](https://img.shields.io/npm/dt/cli-github.svg)](https://www.npmjs.com/package/cli-github)

> A fancy GitHub client for command line.

## Prerequisites

 - [NodeJS](http://nodejs.org/)
 - [GraphicsMagick](http://www.graphicsmagick.org/)

    ```sh
    # Ubuntu
    $ sudo apt-get install graphicsmagick
    # Fedora
    $ sudo dnf install GraphicsMagick
    # Mac OS X
    $ brew install graphicsmagick
    ```
## Installation
```
$ npm i -g cli-github
```
## Usage
```
$ github
```

Use the following key shortcuts to access different GitHub resources:

### News Feed

 - <kbd>SHIFT</kbd> + <kbd>C</kbd>: Create a new repository on GitHub.
 - <kbd>SHIFT</kbd> + <kbd>P</kbd>: Visit GitHub profiles (default: your GitHub profile).
 - <kbd>SHIFT</kbd> + <kbd>I</kbd>: View the open issues that are assigned to you.
 - <kbd>SHIFT</kbd> + <kbd>R</kbd>: View the open pull requests that created by you.
 - <kbd>SHIFT</kbd> + <kbd>←</kbd>: Go back in history
 - <kbd>SHIFT</kbd> + <kbd>→</kbd>: Go forth in history
### Profile

 - <kbd>SHIFT</kbd> + <kbd>R</kbd>: Fetch user's followers.
 - <kbd>SHIFT</kbd> + <kbd>N</kbd>: Fetch user's following.
 - <kbd>SHIFT</kbd> + <kbd>M</kbd>: Fetch the organization members.
### User List

 - <kbd>SHIFT</kbd> + <kbd>P</kbd>: Visit GitHub profiles (default: your GitHub profile).
## Screenshots
### Splashscreen
![](/screenshots/splashscreen.png)

### News Feed
![](/screenshots/news-feed.png)

### Create repository
![](/screenshots/create-repo.png)

### Profile
![](/screenshots/profile.png)

### Issues
![](/screenshots/issues.png)

### Pull Requests
![](/screenshots/pull-requests.png)


## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:



## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2014#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
