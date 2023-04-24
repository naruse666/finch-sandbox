# finch-sandbox

[finch](https://github.com/runfinch/finch)のキャッチアップ。

最小スペックは`2 CPU, 4 GB memory`となっているので注意。

# 簡単に
brewでインストール。
```brew install --cask finch```

初回のみ```finch vm init```を実行する必要がある。(1,2分くらいかかった)
  
`~/.finch/finch.yaml`が作られていて、これを元にvmが作られてそう。

コマンドは基本dockerと同じ。nerdctlでサポートされていることが前提みたい。

既存の`docker-compose.yaml`ファイルもそのまま実行できる。

以下のコマンドでfinchのvmに入れるらしい。
```LIMA_HOME=/Applications/Finch/lima/data /Applications/Finch/lima/bin/limactl shell finch```

動作はとても早くてDockerを使っている時のファンの音とさよならできそう？？
