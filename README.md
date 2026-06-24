# CPAWCTF 挑戦記録

## これは何
セキュリティを学ぶ目的でCPAWCTFに挑戦した記録です。
答え(フラグ)そのものより、考え方・詰まった点・学びを中心にまとめています。

## 取り組んだ分野
- Web
- Crypto
- Network
- Binary
- Misc

## 身につけたスキル・ツール
- `file` コマンド(ファイルの種類の調査)
- `chmod`(実行権限の付与)
- Python(暗号解読の自動化)
- 古典暗号の基礎知識(シーザー暗号)

## 解いた問題一覧
| カテゴリ | 問題名 | 使用ツール | 学び |
|---|---|---|---|
| Misc | Test Problem | なし | フラグフォーマットの確認 |
| Crypto | Caesar Cipher | アルファベット表, Python | シーザー暗号の仕組み |
| Reversing | exec_me | file, chmod | ELFバイナリの実行方法 |
| Misc | Can you open this file ? | file, Word | 拡張子がなくてもfileコマンドでファイル種類を特定できる |
| Forensics | River | Exif確認くん | JPEGにはExif情報として位置情報が含まれる |
