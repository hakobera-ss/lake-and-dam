# lake-and-dam

## これはなに？

日本に分布する天然の湖沼をざっくり抽出してみた。

## データの出典と方法

1. 次のシェープファイルを取得
   - 国土数値情報（ダムデータ）（国土交通省）（https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W01.html ）平成26年度（2020年8月24日取得）
   - 国土数値情報（湖沼データ）（国土交通省）（https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W09-v2_2.html ）（2020年8月24日取得）

2. 湖沼のポリゴン辺縁から0.01度以内にダムの点データが存在する湖沼を削除した。

## 留意点

霞ヶ浦など、灌漑施設の存在によって削除された湖沼もあるので注意。

## 免責事項

このデータは、「国土数値情報（湖沼データ）」（国土交通省）（https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W09-v2_2.html ）を加工して作成した。

