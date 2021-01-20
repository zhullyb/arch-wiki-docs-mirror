This is a mirror of ArchWiki

The python script comes from [https://github.com/lahwaacz/arch-wiki-docs](https://github.com/lahwaacz/arch-wiki-docs)

To use it, you should install ```git python python-simplemediawiki python-lxml python-cssselect``` first

If you are using Archlinux, you can use a command like this

```bash
sudo pacman -S git python python-simplemediawiki python-lxml python-cssselect --needed
```

Then, you can use a command like this

```
git clone https://github.com/zhullyb/arch-wiki-docs-mirror.git
cd arch-wiki-docs-mirror
python arch-wiki-docs.py --output-directory "Wiki_Mirror" --clean --safe-filenames
```

I'll update it .....emmm...monthly maybe ???