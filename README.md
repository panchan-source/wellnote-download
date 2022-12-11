# wellnote-download
## 機能
・全家族写真/動画/アイコン  
・写真はアルバムの日時で撮影日時付与  
・チャット履歴(html)  
・チャット履歴(csv)  
・成長記録(csv)  
・自作スタンプ  
・RawData(json)  

## ダウンロード

[こちら](https://github.com/panchan-source/wellnote-download/releases/)
からdownload_pic_all.exeをダウンロードしてください。  
※Windowsのみ対象です

##  使用方法
ダウンロードしたdownload_pic_all.exeを実行すると以下の画面が表示されるので、emailとpasswordを入力してください。  
![login](https://user-images.githubusercontent.com/120144672/206593139-ba895c8a-3575-46b3-a310-fb6d8ef487d9.png)

ツールが動き始めると黒い画面にログが表示されます  
![実行画面](https://user-images.githubusercontent.com/120144672/206593495-01a5bae2-8375-47b2-8f96-f87334af682f.png)

ダウンロードが終わるとメッセージが表示されます  
![DONE](https://user-images.githubusercontent.com/120144672/206593987-ba56c960-f8cd-4134-9064-a3af0c0a894f.png)

## エラーが発生した場合
黒い画面に表示されているログとともにご連絡ください。  
可能な限り修正します  
![ERROR](https://user-images.githubusercontent.com/120144672/206594059-a499baf6-1301-4fb4-b409-47f68c06effe.png)

## 出力フォルダ/ファイル
./contents : すべてこのファイル配下に保存されます  
./contents/albums : 写真動画が保存されます  
./contents/index.html : チャットの記録がHTMLファイルのTOPPage  
./contents/defaultstamps : デフォルトスタンプが保存されます  
./contents/healthdata : 健康記録がcsv形式で保存されます  
./contents/icons : アイコンが保存されます  
./contents/originalstamps : 自作スタンプが保存されます  
./contents/pages : チャット毎のhtmlファイルが保存されます  
./contents/tweets : 家族毎のチャットがCSV形式で保存されます 
./contents/rawdata : 調査用の詳細なファイルが保存されます  
