# rey-k-os001
test 001 for rey-k-os

[Japanese/Kanji]
- 目標
  - 既存の OS (Linux/Windows/MacOS/...) とは違った特徴を持つ OS を作ってみる。
- 特徴
  - 許可された権限のみ動作 (安全)
  - リソースを確保する際に (eg. malloc)、細かく制約をつけられる (安心)
  - アプリサンドボックス (POSIX, Android, Windows などのアプリを安全に動かす、専用スレッド込みで)
  - ドライバサンドボックス (Windows ドライバの一部を、安全に動かす)
- 使えそうなアイディア
  - Rust / Go くらいでサクッと書く
  - 協調型マルチタスク (いまさらではあるけれど、性能に全振りするならあり?)
