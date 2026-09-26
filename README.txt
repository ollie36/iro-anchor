いろアンカー FINAL v3.2 PWA

GitHubへ、このZIPを展開した「中身」をすべて上書きアップロードしてください。
追加ファイル:
- icon-192.png
- icon-512.png

PWA対応:
- Web App Manifestに専用アイコン、start_url、scope、standaloneを設定
- Service Workerを更新
- 古いキャッシュをactivate時に削除
- HTMLはネットワーク優先で更新
- インストール後はstandalone表示を想定

重要:
以前作ったChromeショートカットはいったん削除し、
GitHub Pagesへのv3.2反映を確認後にChromeから再インストールしてください。
IndexedDBの登録データ自体は、ショートカット削除だけならサイトデータを消さない限り維持されます。
