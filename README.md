# Phaser Logo Particle Demo

Hello!\
Flash may be dead but I still love web games so I'm pretty excited to have discovered this framework!!!

There are plenty resources to read online but here are some tips and pitfalls I have found.

Setup:\
Phaser is a framework for web games so your setup should be pretty much exactly the same for normal web development. You can follow the [official setup guide](http://phaser.io/tutorials/getting-started-phaser3) on the Phaser site.
I use Visual Studio Code for a text editor because it's new and sexy.\
For a local server you could use the one that comes with the pre-installed Python 2 bundle on Mac. Start it with this command in Terminal: `python -m SimpleHTTPServer`\
I chose to use a local server in NodeJS, installed with NPM [http-server](https://www.npmjs.com/package/http-server)\
Tip: to update Node itself I use ["n"](https://www.npmjs.com/package/n)\
Tip: to add more commands to Terminal I use [Homebrew](https://brew.sh)

I also find these additional tools handy:\
[ImageMagick](http://www.imagemagick.org/Usage/crop/#crop_equal) is an image editor for commandline. Good for cropping sprite sheets in bulk\
Or use a 'proper' image editor. Here's an online one called [Pixlr](https://pixlr.com/web)\
[Spriter's Resource](https://www.spriters-resource.com/) for sprite sheets from games\
Phaser hosts [a ton of other assets](https://labs.phaser.io/assets/) themselves\
Aaand if you want to download all of those instead of clicking each link, try the Chrome extension [Image Downloader](https://chrome.google.com/webstore/detail/image-downloader/cnpniohnfphhjihaiiggeabnkjhpaldj)

The coke can particle demo seen here is a straight copy/paste from Phaser's [site](http://phaser.io/tutorials/getting-started-phaser3/part5) and [GitHub](https://github.com/photonstorm/phaser). The assets are hosted online. You are encouraged to fiddle to understand the features.

And now the [first game tutorial](http://phaser.io/tutorials/making-your-first-phaser-3-game)\
One thing the tutorial does not explain clearly is the demo code links the assets to local folders you probably dont have `src/games/firstgame/assets/space3.png`. So either\
a) create the right folders. Or\
b) edit the paths. Here you can select the text and hammer cmd+d to select the next occurences. Delete.
