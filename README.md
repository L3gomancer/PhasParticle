# Phaser Logo Particle Demo

Hello, Collective!\
Flash may be dead but I still love web games so I'm pretty excited to have discovered this framework!!!

There are plenty resources kicking about but here are some tips and pitfalls as I found them.

Setup:\
As the [setup guide](http://phaser.io/tutorials/getting-started-phaser3) on the official Phaser site says, get set up for normal web development.\
I'm on a Mac so I use Unix commands in Terminal.\
I use Visual Studio Code because it's new and sexy.\
Macs come with Python2 and its local server so I used that.
`python -m SimpleHTTPServer`

I also find these additional tools handy:\
[ImageMagick](http://www.imagemagick.org/Usage/crop/#crop_equal) is a venerable commandline image editor, you can automate cropping sprite sheets\
Or use a 'proper' image editor. Here's an online one called [Pixlr](https://pixlr.com/web)
[Spriter's Resource](https://www.spriters-resource.com/) for sprite sheets from games\
Phaser hosts [a ton of other assets](https://labs.phaser.io/assets/) themselves\
Aaand if you want to download all of those instead of clicking each link, try the Chrome extension ['Image Downloader'](https://chrome.google.com/webstore/detail/image-downloader/cnpniohnfphhjihaiiggeabnkjhpaldj)

For the particle demo (on Phaser's [site](http://phaser.io/tutorials/getting-started-phaser3/part5) and [GitHub](https://github.com/photonstorm/phaser)) it's pretty much a copy/paste of the code and the assets are hosted online. You are encouraged to fiddle to understand the features.

And now the [first game tutorial](http://phaser.io/tutorials/making-your-first-phaser-3-game)\
One thing the tutorial does not explain clearly is the demo code links the assets to local folders you probably dont have `src/games/firstgame/assets/space3.png`. So either\
a) create the right folders. Or\
b) edit the paths. Here you can select the text and hammer cmd+d to select the next occurences. Delete.
