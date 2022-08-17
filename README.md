# My fonts

This is a repo of my patched fonts.

## License

These fonts are exclusively for personal use.

### SF Mono

Please note that it is forbidden to use the typeface SF Mono for any commercial project.

The typeface SF Mono is licensed to registered third-party developers for the design and development of applications for iOS, MacOS and WatchOS.

## How to generate new fonts

1. Get the `python-fontforge` package (e.g., on MacOS: `brew install fontforge`).
2. Download the [patcher script](https://github.com/ryanoasis/nerd-fonts/blob/master/font-patcher).
3. From the root of this repo, execute the command below for each of your fonts (e.g., regular, italic, bold, etc.); each of the generated fonts should be located on a new folder dedicated to the font family, which we specify using the `-out` flag.

```
path/to/font-patcher path/to/font.ttf -w -s -c -out <font-family-name>
```
