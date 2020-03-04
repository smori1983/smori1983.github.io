---
layout: page
title: Tiny Markdown Server
tms_version: 1.1.0
tms_md5sum_win: d2d54119e9d79c8df18ff021cc8f7476
tms_md5sum_mac: 360f99e0073153f633ad241a1a59f954
---
[github]: https://github.com/smori1983/tiny-markdown-server
[release_win]: https://tiny-markdown-server.smori.info/TinyMarkdownServer-{{ page.tms_version }}-win.zip
[release_mac]: https://tiny-markdown-server.smori.info/TinyMarkdownServer-{{ page.tms_version }}-mac.zip



![]({% link assets/tiny-markdown-server/ss.01.png %})

My first electron application.

[Project page][github]


## Download

version: `{{ page.tms_version }}`

|Platform|MD5 Sum|
|---|---|
|[Windows][release_win]|`{{ page.tms_md5sum_win }}`|
|[Mac][release_mac]    |`{{ page.tms_md5sum_mac }}`|


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

![]({% link assets/tiny-markdown-server/demo.01.png %})

- Only markdown files are listed.
- **.md** and **.markdown** are considered as markdown file.

Of course you can use images in markdown.

```
# sample_04

## image

![](img/image_01.png)

## image

![](img/image_02.png)
```

This markdown will be:

![]({% link assets/tiny-markdown-server/demo.02.png %})
