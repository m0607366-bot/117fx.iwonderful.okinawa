# FXエントリー配信サービス（117fx.iwonderful.okinawa）

WordPress（Twenty Twenty-Four）から EmDash（Cloudflare Workers ＋ D1 ＋ R2）へ移したサイト。blog.delta-a.net の仕組みを流用。

- 記事はなく、固定ページだけ。トップは固定ページ「2-2」（site.ts の frontPage）。
- 検索エンジンには載せない（site.ts の noindex。WordPress の「検索エンジンでの表示」オフと同じ）。
- 広告・アナリティクスなし、サイドバーなし。
- メールでログイン（送信元 noreply@mail.delta-a.net）。
- `npm run deploy` … 公開
