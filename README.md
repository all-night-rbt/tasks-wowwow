## これはなに？

掃除や洗濯など生活の運営、ウェブサイト制作や動画編集などクリエイティブな活動、そして夏の楽しいアクティビティ、、、数々の種類のタスクを **淡々と確実にこなす人生** をサポートしてくれるツールです！

## 淡々とタスクをこなす人生、というパワーワード

この見出し見て、「えぇ…そんな人生やだ…社畜じゃん……」とか思ったか？  
それはちょっと早とちりだな。

#### 没頭することで、より鮮やかに、より身軽に

その日やる用事を列挙して、時間を見積もる。  
その時間の積み重ねが、きみの人生の1ページになる。  
未来のことはわからない。 `タスクの見積もり時間` なんて仮初めの数字だ。  

それでも、このまま突き進めば `思い描くゴール` にたどり着くんだ、という確信を持てていることは尊い。  
<br>

何時何分に全てのタスクが終了し満足げな表情で寝床へ帰ることになるのかが分かってるって、すごい良くない？  

<br><br><br>


思い通り進まないことだってあるだろう、生きてれば突発タスクは必ず起きる、 `ハッピーなタスク` も、 `アンラッキーな仕事` も。  

一寸先の未来が分からないからこそ、変化に耐えうる強靭な僕たちになろうぜ。  
<br><br><br><br><br><br>

突然差し込まれた横暴なタスクは  

![](https://raw.github.com/wiki/otr-zbnr/tasks-wowwow/images/howToCopy.mp4.gif)

1. <kbd><kbd>option</kbd>+<kbd>↓</kbd></kbd>で行追加、
2. そのまま<kbd>↑</kbd>で1つ上のセルへ移動、
3. <kbd><kbd>ctrl</kbd>+<kbd>←</kbd></kbd>からの<kbd><kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>→</kbd></kbd>で行全体をホールド！
4. そして、<kbd><kbd>ctrl</kbd>+<kbd>C</kbd></kbd>→<kbd><kbd>ctrl</kbd>+<kbd>V</kbd></kbd>で生まれたての真っ白な行を俺色に染めるだけだ!
5. あとは勝手にタスクの名前や見積もり時間を変えろ。


たったこれだけで、  
> さて、では今日は何を削って1日に納めようかな...

と戦略を練るフェーズに入る。そこからはキミの腕の見せ所だ。
<br><br><br><br>


そして一度タスクを開始したら、終了予定時間や明日のこと、過去の失敗や栄光は全て忘れて、その1行に没頭する。
<br><br><br>



その1行の中で生まれるドラマに身を浸し、喜び、悲しみ、生ききる。
<br><br><br>



それこそが最も生産的でアツい人生だと思わないか？
<br><br><br><br><br><br>


## ツールの概要
- 平たく言うとTODO管理(時間管理)用のツール
- Mac標準の表計算アプリ、Numbersのファイル
- ノリノリでウォウウォウしながらタスクをこなせる
- 完全オリジナル自作ツール、というわけではなく、「タスクシュート(TaskChute)」という既に世に出ているツールを元に、自分が使いやすいように勝手にごにょごにょいじったもの
  - ちなみに、「TaskChute」はこちら  
https://cyblog.biz/pro/taskchute2/index2.php

## 素直に本家本元の方(タスクシュート)使えば良さそうなのに、なんでわざわざ作ったか
1. Macで使いたかったから
    - タスクシュートには無料おためし版があるんだけど、それのファイル形式がExcelだった(Excel for Macを買う気は今の所ない)
2. それでもタスクシュート(的なもの)を使うことを諦めきれなかったのは、タスクシュートがまじで優秀なので
    - 当ツールは、下の機能についての説明を見れば分かるようにかなり機能減らしてしまったから、興味あればぜひ本家のやつを試してみてほしい
        - Macユーザーに救いの手はないんだろ...と思いきや、実はタスクシュートには[クラウド版](https://taskchute.cloud/users/top)があるから安心しろ


## 使い方、機能

- 使い方はノリでなんとかなると思うけど、どんな機能がついてるのか知ってるとより良く使えると思うので、タスクシュートのガイドを読むといい感じかもしれない
  - https://cyblog.biz/pro/taskchute2/index2.php
- 機能について、オリジナル版からの主な変更箇所は以下の通り

#### 機能カット、縮小(、妥協)
- ファイル保存時に動くスクリプトはなし(順番の入れ替え、repea機能、見積もり時間によってフォントサイズを変えるなど)
- 「見積M」列は削除(僕が分単位の見積もりをしない、かつ、「見H」「見積M」両列の連動が実現できないため)
- 並べ替えは手動(適宜表の並べ替えボタンを自分で押す)
- ショートカット(ctrl+W,ctrl+G,ctrl+T)はなし
- 現在時刻,現在日付の入力などのショートカット(Excel標準のもの)はNumbersには用意されていないので、[Wordservice](https:/apps.apple.com/jp/app/wordservice/id899972312?mt=12)などを使って自前で用意する
- プロジェクト名に応じた背景色設定は、対象行全体ではなく、プジェクトのセルのみ  
(numbersでは、セルの値に応じて別のセルのスタイルを変える機能は提供されていない、、)
- プロジェクト毎の背景色は、Projectシートではなく、メインの表の「条件付きハイライト」で設定(詳細はProjectシート参照)

#### 機能追加、拡充
- 現在時刻と併せて現在の節を表示
- タスク各行でも現在の節を赤字で表示
- 予実差を評価してくれる列を追加(見積もり時間より実績時間が多いと赤い字になります)

## ダウンロードはここから
- [tasks-wowwow.numbers](https://github.com/otr-zbnr/tasks-wowwow/raw/master/tasks-wowwow.numbers)

