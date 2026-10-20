# limisys.github.io

GitHub Pages 用户站点的双站同构发布树（与 `caseos-research` 内容同构，差异仅页脚/canonical/清单类）。

## 结构
- 31 个 HTML 页面（15 英 + 15 中 + 1 双语时间戳页 timestamps.html），相对路径与 caseos 树完全一致。
- `assets/`：site.css、katex、spine.svg、dag.svg、favicon.svg。
- `files/`：评审稿 PDF；`ots/`：58 个 OpenTimestamps 证明（.ots）。
- `404.html`、`robots.txt`、`sitemap.xml`、`.nojekyll`、`README.md`。

## 构建
```bash
python3 build_release.py
```
构建器位于 `../build_release.py`，只读 `src/`，幂等产出本树与 caseos 树。

## Pages 设置
- Repository: `limisys/limisys.github.io`
- Settings → Pages → Deploy from a branch → `main` / root

## 许可
- 文字 CC BY 4.0 · 源码 Apache-2.0
