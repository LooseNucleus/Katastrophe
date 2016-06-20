# Katastrophe
**Python tool to download torrents from Kat.ph using the terminal or command promt.**

![ScreenShot](http://i.imgur.com/gVdTRPk.png)


## Installation

### Using [pip](https://pypi.python.org/pypi/pip/)

`$ pip install katastrophe`


### Get the latest build from the Source

* Clone the repo git clone https://github.com/alyakhtar/katastrophe
* Run python setup.py install


### Dependencies

* [BeautifulSoup4](https://pypi.python.org/pypi/beautifulsoup4/4.3.2)
* [tabulate](https://pypi.python.org/pypi/tabulate)
* [docopt](https://github.com/docopt/docopt)
* [requests](https://pypi.python.org/pypi/requests/)
* [lxml](https://pypi.python.org/pypi/lxml)


### Requires

* for Linux/Mac OS X
  - [Deluge](http://deluge-torrent.org)/[Transmission](http://transmissionbt.com)/[QBitTorrent](http://qbittorrent.sourceforge.net)/[Vuze](http://vuze.com)
* for Windows
  - [BitTorrent](https://www.bittorrent.com)/[μTorrent](https://utorrent.com)/[Deluge](http://deluge-torrent.org)



### Usage:
```sh
  katastrophe.py 
  katastrophe [-m | -t | -a | -s | -l | -g | -b]
  katastrophe -h | --help
  katastrophe --version

  Multi Download:
    i,j     From Serial No. i to Serial No. j
    ,i      From Serial No. 1 to Serial No. i 
    i,      From Serial No. i to serial no 25
```

### Options:
```sh
  -h, --help            Show this screen.
  --version             Show version.
  -m, --movies          Show latest Movie torrents
  -t, --tv              Show latest TV torrents
  -a, --anime           Show latest Anime torrents
  -s, --songs           Show latest Music torrents
  -l, --losslessmusic   Show latest Lossless Music torrents
  -g, --appsandgames    Show lates Application and Game Torrents
  -b, --books           Show latest Book Torrents
```

### Screenshots


#### Latest Movies


`$ katastrophe -m`


![ScreenShot](http://i.imgur.com/sMbc4Pb.png)


#### Latest TV Shows



`$ katastrophe -t`


![Screenshot](http://i.imgur.com/NJKtGWH.png)


#### Latest Games and Applications


`$ katastrophe -g`


![ScreenShot](http://i.imgur.com/YSQoOpS.png)


#### Latest Music 


`$ katastrophe -s`


![ScreenShot](http://i.imgur.com/PXcGIEO.png)


#### Latest Anime


`$ katastrophe -a`


![ScreenShot](http://i.imgur.com/IVnSAs1.png)


### Latest Books


`$ katastrophe -b`


![ScreenShot](http://i.imgur.com/DDwqrZF.png)


#### Latest Lossless Music


`$ katastrophe -l`


![ScreenShot](http://i.imgur.com/tknw3Zt.png)


#### Range for Multiple Downloads


`$ Starting and Ending Torrent`


![ScreenShot](http://i.imgur.com/wy78wMu.png)


`$ Starting Torrent`


![ScreenShot](http://i.imgur.com/hBzll6P.png)


`$ Ending Torrent`


![ScreenShot](http://i.imgur.com/ziLjt25.png)

### Contribute

Found a bug or want to suggest a new feature? Report it by opening an issue. Feel free to send a pull request for any improvements or feature requests ;)


### License

MIT © [Aly Akhtar](https://github.com/alyakhtar)
