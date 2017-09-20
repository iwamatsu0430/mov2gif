# mov2gif: Convert script .mov to .gif

If you want convert .mov movie to .gif animation. mov2gif can convert quickly!

## How to Use

### Setup

Firstly, you need install [Homebrew](https://brew.sh/) for Mac OS. and this script uses [ffmpeg](https://www.ffmpeg.org/) and [gifsicle](https://www.lcdf.org/gifsicle/).

```
brew install ffmpeg
brew install gifsicle
```

### Example

```
# gif scale = default (320)
mov2gif input.mov output.gif
```

```
# gif scale = 640
mov2gif input.mov output.gif 640
```

### Options

- input
  - .mov file
- output
  - .gif file
- scale
  - Optional
  - default = 320

## Thanks

https://qiita.com/macoshita/items/90222ab67440875a0a98
