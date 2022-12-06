## ja-maplibre-gl-js

日本語ドキュメンテーション用翻訳用のソースです。

Geolonia Javascript API ドキュメントの翻訳ソースとして使用しています。  
https://geolonia.github.io/ja-maplibre-gl-js-docs/api/


## 翻訳手順
翻訳する手順は、セクション毎に異なります。以下の手順に沿って翻訳して下さい。

### API リファレンス
https://geolonia.github.io/ja-maplibre-gl-js-docs/api/


#### 手順

1. 翻訳ファイルは、`src/` 以下にありますので、エディタで翻訳する文章を検索して下さい。  
2. 以下の様に英文を `//` でコメントアウトし、下に日本語を書きます。（`//`でコメントアウトした行は、アスタリスク`*`を削除して下さい）

```
 // @param {number} [options.maxZoom=22] The maximum zoom level of the map (0-24).
 * @param {number} [options.maxZoom=22] 地図の最大表示倍率（0〜24）。
```


### プラグイン

https://geolonia.github.io/ja-maplibre-gl-js-docs/plugins/

#### 手順

1. [ja-maplibre-gl-js-docsの pluguins.json](https://github.com/geolonia/ja-maplibre-gl-js-docs/blob/main/docs/data/plugins.json) を編集して下さい。（https://github.com/geolonia/ja-maplibre-gl-js-docs/blob/main/docs/data/plugins.json）
2. 以下の様に`description` 行をコピーし日本語に翻訳して下さい。英語の説明は、英文の列のキーを `_description` に変更して残していておいて下さい。

```
"mapbox-gl-accessibility": {
  "website": "https://github.com/mapbox/mapbox-gl-accessibility/",
  "_description": "Integrates with ARIA-compatible screen readers for users with visual impairments.",
  "description": "視覚障がい者向けARIA対応スクリーンリーダーとの連携。"
},
```
