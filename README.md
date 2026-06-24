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

### コマンド
| コマンド | 用途 |
|---|---|
| `file` | ファイルの種類を調べる |
| `chmod +x` | 実行権限を付与する |
| `ls` / `ls -l` | ファイル一覧を表示する |
| `mkdir -p` | ディレクトリを作成する |
| `mv` | ファイル・フォルダを移動/リネームする |

### ツール
| ツール | 用途 |
|---|---|
| Wireshark | pcapファイルの解析 |
| Exif確認くん | 画像のExif情報確認 |
| Python | 暗号解読の自動化 |

### 知識
| 分野 | 内容 |
|---|---|
| 古典暗号 | シーザー暗号の仕組み |
| ハッシュ | SHA1・レインボーテーブル |
| ファイル形式 | ELF・JPEG・pcap・doc |
| ネットワーク | パケット・pcapの基礎 |

## 解いた問題一覧
| カテゴリ | 問題名 | 使用ツール | 学び |
|---|---|---|---|
| Misc | Test Problem | なし | フラグフォーマットの確認 |
| Crypto | Caesar Cipher | アルファベット表, Python | シーザー暗号の仕組み |
| Reversing | exec_me | file, chmod | ELFバイナリの実行方法 |
| Misc | Can you open this file ? | file, Word | 拡張子がなくてもfileコマンドでファイル種類を特定できる |
| Forensics | River | Exif確認くん | JPEGにはExif情報として位置情報が含まれる |
| Network | pcap | Wireshark | パケットの生データにASCII文字列が含まれることがある |
| Crypto | HashHashHash! | Google検索 | SHA1は既知ハッシュをレインボーテーブルで逆引きできる |
