## なにこれ

Switchのスクショをなんとか効率よくBlueskyに投稿できないか難産するやつです。

## アプローチ

1. SwitchのスクショをFacebookに投稿（非公開での投稿）
2. 本ツールで新着を取得
3. コメントを加えてBlueskyに投稿

## 欲しい機能

- Facebook上の投稿単位での管理
- コメントのテンプレ機能

# 実装のためのメモ

1. fields=posts{full_picture} で記事のIDを取得
2. {post_id}/attachments で画像を全取得
