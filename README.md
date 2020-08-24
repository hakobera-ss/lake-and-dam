# lake-and-dam

## これはなに？

日本に分布する天然の湖沼をざっくり抽出してみた。

## 方法

1. 国土数値情報から次のデータを取得
   - 国土数値情報（ダムデータ）（国土交通省）（https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W01.html ）
   - 国土数値情報（湖沼データ）（国土交通省）（https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W09-v2_2.html ）

2. 辺縁から0.01度以内にダムデータが存在する湖沼を削除した。

## 留意点

霞ヶ浦など、灌漑施設の存在によって削除された湖沼もあるので注意。

