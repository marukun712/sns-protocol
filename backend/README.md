# Server

# Setup

ipfs をマシンにインストールします。

https://ipfs-book.decentralized-web.jp/install_ipfs/

ipfs を初期化します。

```
ipfs init
```

ipfs と orbitdb が通信するため、ポート`4001`と`4002`をを開放してください。

サーバーを起動します。自動的にサーバーに DB が replicate されます。

```
node index.ts
```
