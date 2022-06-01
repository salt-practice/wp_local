## WordPress の ローカル開発環境構築

### 構築方法
適当なディレクトリ作成 ex. wordpress  
`themes` と `plugins` ディレクトリ作成 し並列に このリポジトリを clone
```
wordpress
  ├ themes
  ├ plugins
  └ wp_local
```
コンテナ起動
```bash
$ cd wp_local
# cp
$ cp .env.example .env
# 必要であれば編集
$ vim .env
# 起動
$ docker-compose up
```

### themes と plugins ディレクトリについて
ここでテーマとプラグインを開発  
テーマ、プラグインを1つずつ `git` 管理想定