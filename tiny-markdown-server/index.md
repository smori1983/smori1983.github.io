---
layout: default
title: Tiny Markdown Server
---
# Tiny Markdown Server

![](/assets/tiny-markdown-server/ss.01.png)

My first electron application.

[Project page](https://github.com/smori1983/tiny-markdown-server)


## Download

### `v1.0.1`

- [Windows][release_win]
- [Mac][release_mac]

[release_win]: https://github.com/smori1983/smori1983.github.io/raw/tms_1.0.1/TinyMarkdownServer-1.0.1-win.zip
[release_mac]: https://github.com/smori1983/smori1983.github.io/raw/tms_1.0.1/TinyMarkdownServer-1.0.1-mac.zip


## Usage

- Select the directory where markdown files are saved (Like Apache's document root).
- Enter the port (80-65535).
- Click 'start'.
- Open in browser.


## Demo

Suppose you created `demo_folder` and you saved some markdown files.

```
demo_folder/
├── folder_01
│   └── sample_03.md
├── folder_02
│   ├── img
│   │   ├── image_01.png
│   │   └── image_02.png
│   └── sample_04.md
├── sample_01.md
└── sample_02.md
```

The top page will be:

![](/assets/tiny-markdown-server/demo.01.png)

- Only markdown files are listed.
- Only **.md** is considered as markdown file.

Of course you can use images in markdown.

```
# sample_04

## image

![](img/image_01.png)

## image

![](img/image_02.png)
```

This markdown will be:

![](/assets/tiny-markdown-server/demo.02.png)
