# Wiki_Django
# Django用Wiki

詳細はWikiに記載<br />

+ RESTFUL APIバックエンドとして利用可能
+ https://www.django-rest-framework.org/

## メリット
+ マイグレーション機能 (DBのテーブル/スキーマの変更が容易)
+ 管理サイト機能 (DBレコードのCRUD画面が簡単に用意できる)
+ セキュリティ対策が充実 (XSS, CSRF, SQLインジェクション対策, クリックジャッキング対策, SSL/TSL:HTTPS, パスワード暗号化)
+ キャッシュの利用が容易
+ GeoDjango機能 (地理空間データが利用可能)

## デメリット
+ ネットワーク越しのI/O待ちでアプリ全体が一時待機になる(同期的)
+ 非同期対応が完全でない.
+ https://docs.djangoproject.com/ja/4.2/topics/async/
+ ASIG (Asynchronous Server Gateway Interface)
+ asynioライブラリ
+ websocketライブラリ (wsプロトコル)

## 非同期対応
+ WSGIサーバをASGIサーバに切り替えることで非同期対応する
+ Djangoフレームワークのどのレベルまで非同期に対応しているかは随時チェックが必要

+ 
