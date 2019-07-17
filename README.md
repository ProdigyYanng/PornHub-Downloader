
# Pornhub-downloader

## Important Notice: This project is aim to study Node.js, so I will not update this project

![alt text](https://mondrian.mashable.com/uploads%252Fcard%252Fimage%252F890680%252Fbd195a74-b8e9-4c80-8c57-be52bda56739.jpg%252F950x534__filters%253Aquality%252880%2529.jpg?signature=Rmc-ahNHdlEgxylDA2z5-sEjWxg=&source=https%3A%2F%2Fblueprint-api-production.s3.amazonaws.com)

## No Need To Thank Me（Enjoy !! :smile:）

Download highest quality videos from [pornhub](https://pornhub.com).

**Version 2.x is coming now!**

## statement

**This repo is just for studying, not for other purpose.**

## Screenshots

![running](./imgs/running.png)

![files](./imgs/files.jpg)

## Features

* Support proxy setting.

* Always choose highest quality video to download(720P usually).

* Support keyword searching.

* Show progress bar and download speed.

* Skip repeat file.

* Download one by one until error occurs or fetch nothing.

* **Download with custom URLs or custom page.**

* **split big file to pieces, avoid downloading incomplete file**

## Requirement

* Node.js 7.6.0+.

* Your network can access to [pornhub.com](https://www.pornhub.com).

## Usage

* clone this repo.

* install node modules:

```shell
npm install
```

### default

* run

```shell
npm start
```

### custom

If you only want to download specific video(s), you can edit `src/feature/urls.js` like this:

```js
const urls = [
  'https://www.pornhub.com/view_video.php?viewkey=ph5844dbb3a1456'
];
```

> Add your URLs as array.

And then run:

```shell
npm run url
```

## Download speed

The speed depends on your local network or proxy.
