---
layout: doc
title: ウォーキングペーパー
permalink: /jp/beginner/walking-papers/
lang: jp
category: beginner
---

ウォーキングペーパー
==========

この章では、GPSを使わずに土地の情報を記録するための方法を紹介します。

今回はウォーキングペーパーと呼ばれるツールを使って、対象地域の地図を紙に印刷します。さらに、その紙の上に描いたメモや地物をJOSMに読み込ませることで、OpenStreetMapへデータを入力してみましょう。

ウォーキングペーパーの概要
-------------

ウォーキングペーパーについて詳細に説明する前に、動作原理を簡単に紹介します。

ステップ1:
地図を描く対象の地域をウォーキングペーパーのウェブサイトで特定し、地図を印刷します。印刷の際には、対象地域で既に書かれているOpenStreetMapの画像か、あるいは(もし提供されていれば)その地域の航空写真かのどちらかを選ぶことができます。

![]({{site.baseurl}}/images/jp_beg_ch5_image07.png)![]({{site.baseurl}}/images/jp_beg_ch5_image05.png)

ステップ2:
印刷された地図を使って、その地域を調査します。紙の地図の上に、より多くの事柄を追記してください。道路を示す線を引いたり、建物の形状を記載してもよいでしょう。対象についてのメモは、紙の地図の上に直接残します。あるいは他にメモ帳を用意しておき、対象についての詳細はメモ帳に別記して、地図の上には項番だけ記載しておくのも良い方法です。

![]({{site.baseurl}}/images/jp_beg_ch5_image00.png)

ステップ3:
紙の地図をコンピュータでスキャンします。スキャナが無い場合は、高解像度のカメラで紙の地図の写真を撮ることでも代用できます。ウォーキングペーパーのウェブサイトへ、作成した画像ファイルをアップロードします。

ステップ4:
JOSMを起動させ、ウォーキングペーパーを読み込みます。紙に描かれている情報を参考にして、OpenStreetMapの上へデジタル情報として記載を行います。

![]({{site.baseurl}}/images/jp_beg_ch5_image04.png)

ウォーキングペーパーの動作原理
---------------

ここまでに紹介した手順に従うことで、現地で使うツールが紙とペンだけであっても、正確な土地データを収集することができます。では、その裏側ではどのような処理が行われているのでしょうか。

![]({{site.baseurl}}/images/jp_beg_ch5_image01.png)

ウォーキングペーパーを印刷すると、紙の下側に四角いバーコードが一緒に印刷されます。ウォーキングペーパーはこのバーコードを読み込むことで、調査対象地域の正確な座標を割り出します。このため、調査が完了した後、紙の地図をJOSMで読み込む際に、紙に記載されたすべての対象の実際の位置が(少なくとも、私たちにとっては十分なくらいの精度で)表示されるのです。

それではここからは、ウォーキングペーパーを実際に印刷して、使ってみましょう。
 
対象の特定と印刷
--------

-  ブラウザを開きます。Firefox,Chrome,Opera,InternetExploerer、どのブラウザでもかまいません。ウィンドウ上部のアドレスバーに"[walking-papers.org](http://walking-papers.org)"と入力し、エンターキーを押してください。
-  以下の画像のような画面が表示されます。

  ![]({{site.baseurl}}/images/jp_beg_ch5_image07.png)

-  マウスのホイールを使うか、ブラウザの右端にあるスクロールバーを使って、ページを下へスクロールしてください。この図にあるような地図が表示されたところで、スクロールを止めてください。

  ![]({{site.baseurl}}/images/jp_beg_ch5_image02.png)

-  この地図に表示された地域が、ウォーキングペーパーの対象地域として紙に印刷されます。この地図は、OpenStreetMapのウェブサイトと同じ方法で操作できます。マウスの左クリックを押しながらドラッグして地域の移動、マウスホイールを使って拡大、縮小が可能です。地図の拡大縮小は、画面左上端に表示されている＋とーボタンを左クリックすることでも可能です。
-  地図の上には、検索ボックスと"検索"ボタンが表示されています。目的の地点を検索することで、地図の表示領域を自動的に移動させることができます。検索ボックスへ市町村の名前を入力し、検索ボタンをクリックしてください。検索に適合する結果が存在すれば、地図の表示領域は自動的にその地点へ移動します。
-  地図の下には、追加でいくつかのオプションが表示されています。最初のオプションは"向き"の項目です。この項目を操作することで、地図の印刷サイズと、紙の向きが変更できます。"向き"と書かれた隣のボックスで、"縦(A4)"を選んでみてください。地図の表示領域が少し大きくなり、印刷時にA4サイズで印刷されるようになります。
-  ウィンドウの一番上に表示されている"地図供給者"という文字列の隣のボックスをクリックします。この部分を操作することで、地図の見た目を変更することができます。オプションの多くは、地図の表示方法の変更に関するものです。例えば、地図によって線の描画が細くなったり、彩色や文字表示が変更されたりします。"BingAerialImagery"をクリックすると、地図ではなく、マイクロソフト社から提供されたその地域の航空写真を表示させることができます。ただし、高解像度の写真でカバーされている地域は限られています。そのため、表示される画像がぼやけすぎて地図作成に有効とはいえないこともありますので注意してください。
-  表示形式を選択し、あなたが編集したい地域を地図に表示させてください。検索によって目標地点を表示させた後でも、より正確な位置へ地図の表示を移動させることが可能です。地図の拡大・縮小を行うときには、「ズームレベル」と呼ばれる数字が変化します。この数字の意味は単純で、どれだけ対象の地点を拡大しているか、ということを表しています。最も広い地域を含めて対象の地域を表示しようとした場合は、地球全体が表示され、ズームレベルは0となります。対象の地点を最も拡大して表示した場合、ズームレベルは18となります。現在指定されているズームレベルは、地図の上部に表示されます。ウォーキングペーパーで地図を印刷する際には、ズームレベル15,16,17がよく使われます。
-  さぁ、それでは地図を印刷してみましょう！マッピングしたい地域が決まり、オプションを選んで表示を整えたら、ウォーキングペーパーの準備は完了です。地図の下に表示されている"作成"ボタンをクリックしてください。
-  クリック後、新しいページが表示され、印刷時のイメージを作成する処理が実行されます。処理が完了すると、同じページ内に画像が表示されます。処理が完了するまでは、だいたい数分から20分ほど必要です。

  ![]({{site.baseurl}}/images/jp_beg_ch5_image08.png)

-  印刷の準備ができたら、"マップをダウンロード"を選択することで、PDFファイルのダウンロードが開始されます。ダウンロードが完了したらPDFファイルを開いてみましょう。
-  コンピュータとプリンタが接続されていることを確認して、PDFファイルを印刷します。以上の操作で、紙に印刷された地図の出来上がりです。

ウォーキングペーパーを使ったマッピング
-------------------

-  さぁ、ウォーキングペーパーを持って街へ出ましょう。ウォーキングペーパーの記述を手がかりにして、まだ地図に記されていない場所を記録してください。
-  道路を示す線を引いたり、建物の形状を記載してもよいでしょう。対象についてのメモは紙の地図の上に直接記載します。
-  もし他にメモ帳があるのであれば、対象についての詳細はメモ帳に別記して、地図の上には項番だけ記載しておくのも良い方法です。

  ![]({{site.baseurl}}/images/jp_beg_ch5_image00.png)

-  納得が行くまで紙の地図へ情報を書き込んだら、その情報をOpenStreetMapにも記入しましょう。

スキャンとアップロード
-----------

-  紙だけしか使わないマッピングとして、ウォーキングペーパーは非常に有効です。ただし残念ながら、ウォーキングペーパーは100％の魔法のツールではありません。OpenStreetMapに登録するためには、紙に記載した情報をJOSMに読み込み、内容をデジタル化する必要があります。
-  まずは、あなたのコンピュータへウォーキングペーパーをスキャンします。スキャナをコンピュータへ接続し、紙をスキャンして画像ファイルとして保存します。スキャナが無い場合は、写真を撮ることでも代用できます。ただし、写真の写りには注意してください。紙は平らに伸ばし、カメラに他のものが写り込まないように注意します。印刷されたバーコードが写真に収まるよう気をつけてください。バーコードが無いと、ウォーキングペーパーは正常に動作しません。以下は、スキャン/撮影した画像イメージの一例です。

  ![]({{site.baseurl}}/images/jp_beg_ch5_image03.png)

-  ウォーキングペーパーをスキャンしてコンピュータへ保存したら、ウォーキングペーパーのウェブサイトを再度開いてください。
-  "アップロード"タブをクリックします。

  ![]({{site.baseurl}}/images/jp_beg_ch5_image09.png)

-  "参照"ボタンをクリックして、ウォーキングペーパーをスキャン/撮影した画像ファイルを選択して下さい。
-  選択が終わったら、"送信"ボタンをクリックします。
-  回線の速度にもよりますが、送信には数分程度必要です。アップロードが完了すると別のページが表示され、質問事項が2つ表示されます。

-  ![]({{site.baseurl}}/images/jp_beg_ch5_image10.png)
-  "この地図をご自身で編集する予定ですか？"という質問には"いいえ"を選択してください。この場合、ウォーキングペーパーは公開され、他のマッパーがスキャンした地図を参照できるようになります。

-  その下にある空白のボックスには、その地図で何をマッピングしたのかの概要を記入してください。マッピングした場所の名称と、追記した地点の種類を含めるとよいでしょう。"保存"をクリックすると、ウォーキングペーパーの処理が開始されます。この処理には20分以上必要となります。

JOSMでの読み込み
----------

-  地図の画像処理が完了すると、地図はJOSMで読み込める形式に変換されます。書き込んだ情報を元に、OpenStreetMapへ追加を行いましょう。前の手順で行ったのと同様、ブラウザへ[walking-papers.org](http://walking-papers.org)と入力して、ウォーキングペーパーのウェブサイトを表示してください。
-  "最近の取り込みの続き"をクリックしてください。
-  あなたが追加した地図を探して、クリックします。以下のような画面が表示されます。

  ![]({{site.baseurl}}/images/jp_beg_ch5_image06.png)

-  処理が完了した地図をJOSMに読み込むには、ウォーキングペーパー上の地図のID番号が必要となります。ブラウザのURLバーを選択し、キーボードのCtrl+Cを押してURLをコピーしてください。文字列は以下のような形式になっているはずです。:[http://walking-papers.org/scan.php?id=fmxcgdqd](http://walking-papers.org/scan.php?id=fmxcgdqd)
-  コピーが終わったら、JOSMを起動してください。このガイドの3章でインストールしたウォーキングペーパープラグインを利用して、スキャンされた地図の読み込みを行います。ウォーキングペーパープラグインをインストールしていない場合、ガイドの3.3章を参照してインストールを行なってください。
-  JOSMのトップメニューから"ウォーキングペーパー"→"ScannedMap"の順番でクリックしてください。
-  入力ボックスが表示されますので、Ctrl+Vを押して、ウォーキングペーパーのウェブサイトでコピーした文字列を貼りつけます。OKをクリックします。
-  以上の操作で、JOSMへのウォーキングペーパー読み込みは完了です。次の章では、地図に追加した地点をOpenStreetMapへ追加する方法について紹介します。

再調査！
----
-  地図上の変更点をOSMへ追加することにより、情報はOSMの地図上に保存されます。そこまで完了したら、その地図に対してさらなる改良を行いましょう。次の調査で印刷されるウォーキングペーパーは、あなたが追加した情報が書き込まれた地図となります。調査は何度も繰り返すことで、OSMの地図も、あなたの地図も、より詳しく、使いやすくなってゆきます。

まとめ
---

おつかれさまでした！

この章では、ウォーキングペーパーの使い方と、その動作原理を紹介しました。また、ウォーキングペーパーの印刷、マッピング、スキャン方法についても紹介しています。次の章では、私達がマッピングした地点をOpenStreetMapへ追加する方法、そして、地図の編集手順を紹介します。