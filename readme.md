## dotfiles
### Installation
```bash
git clone https://github.com/nickurt/dotfiles ~/.dotfiles
~/.dotfiles/bootstrap
```
### FAQ
#### Strange fonts in ZSH with Agnoster theme?
You need to install the patched font [Droid Sans Mono for Powerline](https://github.com/powerline/fonts/tree/master/DroidSansMono) to use this theme correctly.

#### Laravel Valet with a 502 Bad Gateway error
You need to install a DNS Proxy on Windows 10, e.g. [Acrylic DNS Proxy](http://mayakron.altervista.org/wikibase/show.php?id=AcrylicHome) to make it [working](http://mayakron.altervista.org/wikibase/show.php?id=AcrylicWindows10Configuration) (and don't forget to link *.dev sites to 127.0.0.1 in %windir%\system32\drivers\etc\hosts)