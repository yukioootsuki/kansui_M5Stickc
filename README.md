# kansui_M5Stickc
自動灌水装置仕様
１．	土壌水分設定値　40％に固定。(設定機能無し)

２．	カレンダータイマー入力がON且つ、土壌水分が40％未満の条件で10分間灌水する。

（10分間自己保持する）

３．	ハウス２棟分とし、突入電流低減のためにハウス間でポンプの起動をずらしている。

４．	ポンプは水中ポンプとして定格電流は7A程度を想定している。

５．	水分センサーはＷＤ-3-Ｗ-5Ｙ(0-100％　/　0-1V)

※当初、直接M5Stackcのアナログ入力直接読み込んでいたがノイズが大きかったのでADCを追加した。(I2C)

