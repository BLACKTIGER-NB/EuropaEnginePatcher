# History

## 2016/02/20 Ver 0.54

- AoD1.10rc7に対応。
- AoDで自動命名時の語順変更をデフォルト有効に変更。
- 改行文字を含む複数行文字列の文字幅計算間違いを修正。
- _inmm.iniを入れ忘れた時にもそれなりの表示になるように初期フォント設定を変更。

## 2015/09/21 Ver 0.53

- 4GBパッチを当てる箇所を間違えていた不具合を修正。

## 2015/06/10 Ver 0.52

- 16bitカラー設定の自動処理を実装(Windows8以降のみ)
- 4GBパッチを実装。(64bitOSのみ)
- エラーメッセージを少し変更。

## 2015/03/11 Ver 0.51

- DH1.03以降のDH None/Lightで研究概要タブのモデル名打ち切り対応忘れを修正。
- 自動処理モードで英語版のファイルをリネームする前に上書き確認するように変更。
- エラーメッセージを少し変更。

## 2013/12/25 Ver 0.50

- 自動処理モードを実装。
- 英語版のファイルをリネームするモードを追加。
- 強制ウィンドウ化を実装。
- イントロスキップを実装。
- 時間制限解除を実装。
- _inmm.dllがVCランタイムに依存しないように改良。

## 2013/05/04 Ver 0.45

- チャットウィンドウの文字化け問題を一部修正。

## 2013/03/20 Ver 0.44

- 0.42の変更により発生したDDA1.2およびIC/DDAのパッチ当てに失敗する不具合を修正。

## 2012/10/06 Ver 0.43

- DH1.03RC1に対応。

## 2012/09/23 Ver 0.42

- DH/AoD/DDAで研究概要タブのモデル名が中途半端な位置で打ち切られる問題に対処。

## 2012/07/08 Ver 0.41

- AoD1.08にて技術の史実年度が技術名と重なって表示される問題を修正。

## 2012/07/01 Ver 0.40

- 巨大タワーにカーソルを合わせた時の反応改善。
- 実行ファイルはバージョン変更のみ。

## 2012/07/01 Ver 0.39

- 色指定後の分離禁則処理でバッファ計算処理に誤りがあったのを修正。
- 0.35よりVictoriaで自動改行処理が動作していなかったのを修正。

## 2012/06/23 Ver 0.38

- AoD1.08b6でのバイナリ変更に追従。
- 公式対応により河川ツールチップの日本語化を廃止。

## 2012/06/13 Ver 0.37

- AoD1.08b5の河川ツールチップを日本語化できるようにした。
- 0.36の変更により発生したEU2のメッセージ設定画面で落ちる不具合を修正。
- 微妙にログ出力内容修正。

## 2012/05/27 Ver 0.36

- AoD1.04/1.08b3に対応。
- 1.04/1.07/1.08の差異を自動認識するようにした。
- 共通化のため、微妙にパッチ内容変更。

## 2012/02/29 Ver 0.35

- EU2/FtGで折り返し処理を実装。
- HoIで語順変更/折り返し処理を実装。
- _inmm.dllの細かな効率化。
- 0.34の効率化により発生した不具合を修正。

## 2012/02/26 Ver 0.34

- _inmm.dllの効率化。
- これにより、巨大タワーにカーソルを合わせた時の反応を改善した。
- 実行ファイルはバージョン変更のみ。

```text
  2012/02/12 Ver 0.33   Victoriaで語順変更設定時に国家序列の表示が変になるので定義を分離。
                        和訳側の対応に伴い、DHで語順変更をデフォルト設定に変更。
                        微妙にインターフェース改良。
  2012/02/04 Ver 0.32   CKで折り返し処理を実装。
                        数字の分離禁則処理対象に小数点等の記号を含めるように修正。
                        色指定文字列の途中で極力改行しないようにロジック変更。
                        これに伴い、HoI2/AoD/DHの諜報画面/外交画面も折り返し処理を有効にした。
                        ゲーム自動判別時にオプションのデフォルト値を設定するよう変更。
  2012/01/30 Ver 0.31   メッセージログ画面の折り返し処理を実装。
                        Victoriaで語順変更/折り返し処理を実装。
                        微妙にインターフェース改良。
  2012/01/28 Ver 0.30   折り返し処理時に色指定コマンドの途中で分断される不具合修正。
                        メッセージ設定画面の折り返し処理を作成。
                        _inmm.dllに禁則文字判定処理を追加。
                        パッチを当てた実行ファイルの保存後に_inmm.dllをコピーする機能を追加。
                        _inmm.dllの細かな効率化。
                        HoI2でウィンドウ化した時に誤動作する問題が何故か発生しなくなった。
  2012/01/21 Ver 0.29   HoI2/AoD/DHでユニット自動命名時の語順変更に正式対応。
                        HoI2/AoD/DHで折り返し処理に対応。
                        _inmm.dllの細かなバグ修正/効率化。
  2012/01/15 Ver 0.21   DHのユニット自動命名時の語順入れ替え対応。
  2012/01/09 Ver 0.20   CK/EU2/FtG/Vic/HoIについてもクリッピング処理に対応。
                        _inmm.dllの細かなバグ修正/効率化。
                        FtG用コイン画像対応。
  2012/01/07 Ver 0.19   クリッピング処理対応。
                        _inmm.dllを自製化。
  2011/05/03 Ver 0.12   DHの研究概要画面で最大上陸規模の項目にゴミが表示される問題に暫定対応。
  2011/04/10 Ver 0.11   CK/EU2/FtG/Vic/HoIに対応。
  2011/04/08 Ver 0.10   DarkestHourに正式対応。
                        おまけでHoI2にも対応。
                        HoI2/AoD1.05以降/DarkestHourを自動認識する仕掛けを作成。
                        名称をEuropa Engine Patcherに変更。
  2011/04/06 Ver 0.06   DarkestHour対応暫定版を公開。
  2010/09/24 Ver 0.05   AoD1.05に対応。
  2010/05/19 Ver 0.04   強制大文字化回避のパッチ方法をHoI2英語版日本語化の方法に合わせた。
                        微妙にインターフェース改良(DnDに対応)
  2010/03/29 Ver 0.03   一部文字化けが残っていたのを修正
  2010/03/26 Ver 0.02   文字化けを修正/エラーチェックを(少し)実装
  2010/03/20 Ver 0.01   AoDJpPatcherとして初版公開
```
