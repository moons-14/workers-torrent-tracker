# Torrent Tracker HTTP Protocol
BitTorrentプロトコルはBEP([BitTorrent Enhancement Proposal](https://www.bittorrent.org/beps/bep_0001.html))として定義されています。トラッカーに関する仕様は[BEP 3](https://www.bittorrent.org/beps/bep_0003.html)で定義されています。

# トラッカーへのリクエスト
トラッカーへのリクエストはHTTP GETリクエストで行います。リクエストパラメータは以下の通りです。