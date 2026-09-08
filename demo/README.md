# 営業用デモ（架空データ）

`node make-demo.mjs` で生成。実運用のHTMLを元に、架空データの投入・外部通信の遮断・デモ帯を差し込んだもの。

- index.html … 入口ページ(オーナー表示。/api はブラウザ内で偽装)
- {omiya,kawaguchi,ichihara}-reservation.html … キャンセル管理(架空データは「今日」を基準に生成)

架空データはブラウザの localStorage に入る。上の帯の「データを初期化」で作り直せる。
