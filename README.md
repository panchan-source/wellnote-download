# wellnote-download
## Wellnote公式からのアナウンス
wellnoteから公式の一括ダウンロード機能のアナウンスがありました。  
https://wellnote.jp/information/?id=215  


# ツール説明
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

実行時にWindowsから警告がでる場合は詳細情報をクリックしたのち実行ボタンをクリックすると動作します。
<img src=https://user-images.githubusercontent.com/120144672/207176605-b0d5dd27-02b1-49c2-b482-d7e6f4851f60.jpg width=320px>
<img src=https://user-images.githubusercontent.com/120144672/207296234-0bd49d28-56e1-41d3-a804-f948fcb573d0.jpg width=320px>  

##  使用方法
ダウンロードしたdownload_pic_all.exeを実行すると以下の画面が表示されるので、emailとpasswordを入力してください。
exeと同じフォルダにcontentsフォルダが作成され、その配下にwellnoteのデータがダウンロードされます  
チェックボックスがONだとメディアの作成日時が撮影日になりますが、FFmgepを使用して更新するためが画質が劣化する可能性があります。  
![login3](https://user-images.githubusercontent.com/120144672/207177855-f7db3bcb-4ebe-4bf8-b3ab-b2fb833c47df.png)

contentsフォルダ配下に以下のファイルができることがあります。  
未対応メッセージ.txt : サポートしてないタイプの投稿がありました。DMにてご連絡ください。  
EXIF_Error.csv : ファイルタイプが不明でEXIFの付与、動画のメディアの作成日時の」付与に失敗しました。該当ファイルに手動で情報を付与してください。  



参考  
チェックあり  
![チェックあり](https://user-images.githubusercontent.com/120144672/206911449-29774769-4534-4779-97b5-aacb9ddaddfe.png)

チェックなし  
![チェックなし](https://user-images.githubusercontent.com/120144672/206911464-edd6feaa-f3c9-4756-a4d3-187102fd800e.png)


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
