# おでかけ手帖

行きたい旅行先・イベントをメモしておく自分用サイト。忘れずに行くため、3ヵ月以内に行ける時期なのに予定が入っていないものを一覧の上とポータルの「今日のまとめ」に出す。

- 公開: https://ykdtmnhnddsbba-jj.github.io/odekake-techo/
- データ: localStorage `odekakedb.v1` ＋ Google Drive `odekake-db.json`（共通ライブラリ `../portal/lib/techo-google.js` で同期）
- カレンダー: 「カレンダーに追加」で Googleカレンダーの登録画面を開き、手帖に予定ありの印を付ける（カレンダーAPIは使わない）
- 謎解きの公演は入れない（謎解き手帖が正本）
