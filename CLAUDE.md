# Tokyo On Foot — セッションの入口

⚠️ このリポジトリは PUBLIC。個人情報・鍵を置かない。

## 現在地（2026-10-21）

- **2026-10-20 SEO/Search Console**：5ページに canonical・OGP（`img/og.jpg`）・Twitter カード、`robots.txt`・`sitemap.xml` を追加（`a2de21a`・本番反映済み）。Search Console（omata.yusuke1990）に URL プレフィックス `https://tokyo-on-foot.vercel.app/` を登録・所有権確認済み・sitemap 送信済み（送信直後は「取得できませんでした」表示。数日後に再確認）。検証メタは index.html の `<head>`、削除すると所有権が失効する
- `index.html`（入口・4企画のカード）＋ 下層 `ori.html` `nori.html` `iwakan.html` `kiguya.html`（説明→最後に遷移先）＋ `style.css` ＋ `img/`（16枚・各企画4枚の正方形・計2.1MB）。ORI の抽選は `ori.html` の末尾。構成は j-cat.co.jp の事業一覧の比率（番号・英字大・和文小・正方形写真・1px罫・pillボタン）
- 世界観 v2：藍 #1F3352 ／ 和紙の白 #F7F4EE＋薄い粒 ／ 金茶 #B08A4A。書体＝Crimson Pro（英字）・Shippori Mincho B1（和文見出し）・Zen Kaku Gothic New（本文）。生成り #F1ECE2 は廃止
- 4企画：01 ORI（抽選つき・帰る駅はユーザー指定）／02 NORI（nori-olive-eta.vercel.app へ）／03 違和看／04 危惧屋（X の #危惧屋 へ）
- 写真の出典は `~/ai-projects/personal/knowledge/2026-10-19_tokyo-street-photo-sources/raw/candidates/photo-meta.tsv`（Unsplash・Pexels・ぱくたそ。クレジット不要の16枚だけを使用。Commons は未使用）
- 傘の一行（キャッチ）は未決のため載せていない。企画の正本・未決事項はオーナーのメモリ（tokyo-on-foot-project）
- Artifact 版（claude.ai）は index をページ、他を files として同じ内容を公開。更新はこのリポジトリ → Artifact の順。ページを足すときは `scratchpad/gen.py` 相当の生成でなく、各 html を直接編集してよい

## インフラ情報
- Vercelアカウント: omata.yusuke1990@gmail.com / team slug `omt1990`（push で自動デプロイ。CLI 直デプロイ禁止）
- Supabase: 不要（データを持たない）
- GitHubリポジトリ: omt1990/tokyo-on-foot（PUBLIC）
- 本番URL: https://tokyo-on-foot.vercel.app（2026-10-13 接続。デプロイの成否は GitHub の deployments → statuses で見る）
- ステータス: LIVE
- 区分: 個人
