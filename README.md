# RubySymbol
シンボル

## 処理
ハッシュ（連想配列）をシンボルを使って出力する。

## コード
```
enemy1 = {"ザコ" => "スライム","中ボス" => "ドラゴン","ラスボス" => "魔王"}
p enemy1
p enemy1["ラスボス"]
puts ""

enemy2 = {:zako => "スライム",:boss => "ドラゴン",:king => "魔王"}
p enemy2
p enemy2[:king]
puts ""

enemy3 = {zako: "スライム",boss: "ドラゴン",king: "魔王"}
p enemy3
p enemy3[:king]
```

## 出力結果  
```
{"ザコ"=>"スライム", "中ボス"=>"ドラゴン", "ラスボス"=>"魔王"}
"魔王"

{:zako=>"スライム", :boss=>"ドラゴン", :king=>"魔王"}
"魔王"

{:zako=>"スライム", :boss=>"ドラゴン", :king=>"魔王"}
"魔王"
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
