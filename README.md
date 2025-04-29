# kerberos-lab-config

## 概要
このリポジトリは、Kerberos認証環境の構築・検証用に作成した設定ファイルを保存しています。

- Kerberos Key Distribution Center (KDC) 用の設定ファイル (`krb5.conf`)
- 管理用アクセスコントロールリスト (`kadm5.acl`)
- ホスト名管理用ファイル (`hosts`)

## 目的
- Kerberosの仕組みを実際に手を動かして学習するため
- LPIC-3 300「Mixed Environment」試験対策の一環として、Kerberos認証の理解を深めるため

## ファイル構成
kerberos-lab-config/
├── hosts # /etc/hosts相当のホスト名解決設定 
├── kadm5.acl # Kerberos管理サーバーアクセス制御 
├── krb5.conf # Kerberosクライアント・サーバー共通設定

## 注意事項
- 本リポジトリの設定はラボ検証用です。本番環境で利用する場合は適切なセキュリティ対策が必要です。
- 内容は学習・検証目的に特化しています。
