# gtfs-preview

ウェブブラウザ上で直接 GTFS の zip ファイルを読み、 Leaflet の地図上で可視化するデモです。

![GTFS preview](https://repository-images.githubusercontent.com/183617102/b4730a80-6863-11e9-956a-ed43839ca03e)



# Usage

1. ブラウザで <https://frogcat.github.io/gtfs-preview/> を開きます
2. 初期はサンプルファイルがロードされます
3. 地図上に手持ちの GTFS の zip ファイルを直接ドラッグ＆ドロップすると、地図が更新されます

# Note

- サンプルファイル `sample/gtfs.1001.kanetsu_kotu.zip` は [群馬県内バス路線情報（標準的なバス情報フォーマット）](https://gma.jcld.jp/GMA_OPENDATA/) で公開されている、関越交通のファイルです。（取得日時2019年4月26日、ファイルサイズ 1,132kbytes）
- `csv.min.js` は <https://github.com/okfn/csv.js/blob/master/csv.min.js> をコピーしたものです。

