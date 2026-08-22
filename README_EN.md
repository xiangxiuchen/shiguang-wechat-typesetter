# Shiguang WeChat Typesetter

Shiguang is a local-first, single-HTML typesetting editor for WeChat Official Account articles.

- No account required
- Article content is not uploaded by Shiguang
- One-click article layout with local structure detection and a generic closing section when no custom brand ending exists
- Local Markdown file import with fenced code, formulas, links, images, task lists, and variable-column tables
- 35 visual themes, 16 article structures, and 33 content blocks
- Sanitized rich-text copy and static preflight checks for WeChat
- Local drafts, snapshots, and JSON project backups

## Try it

- [Open the web app](https://xiangxiuchen.github.io/shiguang-wechat-typesetter/app/)
- [Download the latest release](https://github.com/xiangxiuchen/shiguang-wechat-typesetter/releases/latest)
- [Chinese documentation](README.md)

Before publishing, always verify the result in WeChat through: paste → save draft → reopen → mobile preview. Images, title, summary, and cover must be handled in the official WeChat editor.

Fastest workflow: copy the complete article or select a local `.md` file, open **One-click article layout**, keep **Replace current article** selected, review the detected structure, and generate. Fenced code is preserved character-for-character. Formula LaTeX is kept in a formula asset list and must be replaced with uploaded images before stable WeChat publishing. An existing brand ending is preserved; otherwise Shiguang adds a generic like/follow/thank-you ending.

## License and attribution

The open-source free edition is licensed under the [Mozilla Public License 2.0](LICENSE).

Created and maintained by **Crush / [xiangxiuchen](https://github.com/xiangxiuchen)**.
