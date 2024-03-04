# YouTube Downloader CLI

## Description

This is a command-line tool to download YouTube videos from the `Terminal`, written under [Pytube](https://pytube.io/).

it is cross-platform (Windows, Mac, Linux) and can be used in any terminal.

> **Note:** This project is still in development.

## Inspiration

This project was inspired by [uTube](https://github.com/omer73364/uTube/) by [omer73364](https://github.com/omer73364) 🤩

## Features

- User-friendly CLI interface.
- Download a single YouTube video

## TODO

- [x] Publish on PyPI.
- [x] Support downloading sounds (mp3 format).
- [x] Supports all available video formats and qualities.
- [x] Support if there is no specified quality, download the close it one.
- [ ] Support shorts.
- [ ] Supports downloading playlists.
- [ ] Playlists organized into folders by their names.
- [ ] Adding numbers playlist videos to their names to make them organized.
- [ ] Add convert videos into mp3 format.
- [ ] GUI app.
- [ ] Any features that you/I can think of.

## Installation

### Method 1: Using Pip

```bash
pip install pyutube
```

### Method 2: Building the project from source

Clone the repository:

```bash
git clone https://github.com/Hetari/pyutube.git
```

Change to the directory:

```bash
cd pyutube
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Build the package:

```bash
python setup.py sdist bdist_wheel
```

Install the package via pip:

```bash
pip3 install dist/*
```

> **Warning:**
>
> In some cases, the package will not install. You may have to add the flag `-H` into the pip command. and if this case, you can use `pip3 install -H dist/uTube-1.0.tar.gz` instead of `pip3 install dist/uTube-1.0.tar.gz`
>
> and if this not working, and you are on `Linux` or `Mac`, try the command with `sudo`.

Then you can use it in your `Terminal`.

## Usage

uTube is very easy to use, just type `utube` on your **terminal** or **cmd** then you can use it.

Here examples of uses:

**- Download videos by `3` steps:**

1.  `utube https://www.youtube.com/watch?v=N3CALZudhkI [the_download_path]`.
2.  Choose video or audio format. (right now only video is supported)
3.  Choose the resolution if it a video you want to download.

`the_download_path` is an optional input, the default is the `terminal` path

| ![enter image description here](pyutube/images/image1.png) | ![enter image description here](pyutube/images/image2.png) |
| ---------------------------------------------------------- | ---------------------------------------------------------- |

<div style="text-align: center;">
    <img src="pyutube/images/image3.png" />
    <br />
    <br />
    <img src="pyutube/images/image3.png" />

</div>

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
please follow the [contributing guidelines](https://github.com/Hetari/pyutube/blob/main/CONTRIBUTING.md)

## License

This project is licensed under the [MIT License](https://github.com/Hetari/pyutube/blob/main/LICENSE.md).
