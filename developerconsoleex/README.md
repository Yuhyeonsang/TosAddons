# developerconsole_ex
developerconsoleの私的改造版です。  
バージョンアップした結果すっかり変わってしまっております。

以下の改造を施しております
* 上下キーで過去履歴の参照ができます。  
* dev_history()を入力すると、履歴をすべてprintします(多いと重いかもです)
* addon用sysmenuにアイコンが登録されます。
* ALTキーを押しながら{}を入力すると、全角で｛｝が入力されます。そしてALTキーを押しながらENTERすると、{}に変換しなおされて実行されます。
* CTRL+SPACEでインテリセンスっぽいのが発動します。あまり期待しないでください。（事前に有効化する必要があります）
* 値をおおよそ常時確認できるインスペクタもあります(ウォッチ機能はまだです)  
インスペクタは関数も評価できますが、副作用に注意してください。
* あといろいろ

itosのdeveloperconsoleとは競合します。

# リリースノート
## v2.0.1
* インスペクタが表示されない時にLSHIFT押しながらToggleすることで強制位置調整する機能の追加
__現状使い勝手がいまいちなので、今後大幅な修正を予定__
## v2.0.0
* たくさんの機能強化
## v1.1.0
* 機能強化
## v1.0.0
初回