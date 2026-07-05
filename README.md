# ig-story-assets

Instagram ストーリーズの API 投稿（Graph API `media_type=STORIES`）用の**一時公開置き場**。

- Meta のサーバーが `image_url` を取得しに来るため、投稿する画像を数分だけここに置く。
- 画像は投稿完了後に自動で整理（削除コミット）される。正本は手元の制作フォルダにある。
- 置かれるのは「これから Instagram で全世界公開される画像」のみ。個人情報・秘密情報は置かない。
- 自動運用の実体: threads-webapp の `wa_ig_story.py`（投稿ボタン＝人間判断）。
