# potproject/lazyimages_without_scroll_events_japanese

## Detail

[GoogleChromeLabs/puppeteer-examples](https://github.com/GoogleChromeLabs/puppeteer-examples)に存在する

[lazyimages_without_scroll_events.js](./lazyimages_without_scroll_events.js)を使いやすくかつ日本語化したものです。

このスクリプトはPuppeteerを使用し、遅延読み込みされた画像がGoogle検索で正しく表示されるかどうかを判断します。

<img width="500" alt="screen shot 2018-10-09 at 12 15 10 pm" src="https://user-images.githubusercontent.com/238208/46697053-98aa5e80-cbc8-11e8-91c3-d5cf7937f3f7.png">

詳しくは[遅延読み込みコンテンツを Google が認識できるようにする#テスト](https://developers.google.com/search/docs/guides/lazy-loading#test)をご覧ください。

## Getting Starter
```sh
git clone https://github.com/potproject/lazyimages_without_scroll_events_japanese
cd lazyimages_without_scroll_events_japanese
npm i # or yarn
node lazyimages_without_scroll_events.js -h
```

### URL Test
```
node lazyimages_without_scroll_events.js -u https://blog.potproject.net
# results.htmlが生成される
```

## License

[Apache 2.0](./LICENSE) 2018 Google Inc.

[Apache 2.0](./LICENSE) 2019 potproject.
