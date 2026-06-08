# Release notes

## 2026-06-08: Markdown initial release

### 正體中文

這是本專案第一次將《公部門開源軟體應用參考手冊》整理為可在版本控制系統中閱讀、比對與維護的 Markdown 發布版本。此版本承接過往原始編輯文件與 PDF 版本的內容脈絡，並將手冊拆分為正體中文與英文兩份 Markdown 文件，以便後續修訂、翻譯對照、公開審閱與再利用。

#### 版本定位

- 正體中文 Markdown 是本次內容整理的原文基準版本。
- 英文 Markdown 是依正體中文內容維護的對照翻譯版本，用於跨語言閱讀、引用與國際協作。
- Markdown 版本適合在可解析 MD 格式的地方，包含但不限於 GitHub 上閱讀、比對、翻譯維護、議題追蹤與無障礙輔助工具解析。
- PDF 版本保留固定版面與頁碼，較適合列印、傳閱與依頁碼引用。

#### 本次整理原則

- 依無障礙 Markdown 的常見建議整理文件結構，包含清楚的標題層級、具描述性的連結文字、圖片替代文字、簡化表格，以及避免僅以視覺格式傳達資訊。
- 參考 The A11Y Project 對 Markdown 內容的建議，優先使用 Markdown 原生語法表示標題、連結與圖片，並讓連結文字可由脈絡理解。
- 參考 Standard for Public Code 中「Use plain English」對跨語言文件的原則，明確標示語言角色，提供英文版本作為跨語言協作入口，並維持不同語言版本的章節、附錄與修訂資訊可對應查找。
- 表格類型避免不必要的「跨欄、跨列的表格儲存格合併」，將其以不同段落拆分，便利於無障礙閱讀理解。
- 保留既有修訂歷史，並將日期、檢核表符號與 PDF 頁數來源等差異寫入 Markdown 文件的無障礙閱讀說明。

#### 後續維護建議

- 新增或修改章節時，應同步檢查正體中文與英文 Markdown 的標題、錨點、附錄與修訂歷史是否可對應。
- 若 Markdown 與 PDF 因版面設計差異、圖片最佳化或發布方式因而產生差異，建議於 README 或修訂歷史（即本文件）中說明。
- 若未來調整語言政策，應明確記錄哪些語言為原文最新基準版本、對照翻譯版本，以便利後續翻譯或使用者理解差異。

---

### English

This is the first release of the Public Sector Open-Source Software Playbook as Markdown files that can be read, compared, and maintained in version control. This release carries forward the content from the earlier source editing files and PDF publications, while providing separate Traditional Chinese and English Markdown documents for future revision, translation alignment, public review, and reuse.

#### Release scope

- The Traditional Chinese Markdown file is the source-language baseline for this release.
- The English Markdown file is an aligned translation maintained from the Traditional Chinese version for cross-language reading, citation, and international collaboration.
- The Markdown files are suitable in environments that can parse MD format, including but not limited to reading on GitHub, comparison, translation maintenance, issue tracking, and parsing by accessibility assistive tools.
- The PDF files preserve the fixed-layout publication format and page references, and are more suitable for printing, circulation, and page-number citations.

#### Principles applied

- The documents were structured according to common accessibility-friendly Markdown practices, including clear heading hierarchy, descriptive link text, image alternative text, simpler tables, and avoidance of purely visual cues.
- The release refers to The A11Y Project's Markdown content guidance by preferring native Markdown syntax for headings, links, and images, and by making link text understandable from context.
- The release also refers to the Standard for Public Code criterion "Use plain English" for cross-language documentation: document the language roles, provide English as a collaboration entry point, and keep chapters, appendices, and revision information comparable across language versions.
- Tables avoid unnecessary merged cells that span columns or rows. Where needed, content is split into separate paragraphs or sections to improve accessibility and reading comprehension.
- Existing revision history is preserved, and accessibility notes in the Markdown files explain date formats, checklist symbols, and the relationship to PDF source page counts.

#### Maintenance notes

- When adding or changing sections, maintain comparable headings, anchors, appendices, and revision history across the Traditional Chinese and English Markdown files.
- If Markdown and PDF versions differ because of layout design, image optimization, or publication method, document the difference in README or the revision history (this file).
- If the language policy changes later, document clearly which language is the latest source-language baseline and which languages are aligned translation versions, so later translators and users can understand the differences.

## References

- [The A11Y Project: Content Style Guide](https://www.a11yproject.com/content-style-guide/)
- [Standard for Public Code: Use plain English](https://www.standardforpubliccode.org/criteria/use-plain-english.html)
- [Foundation for Public Code: The Standard for Public Code](https://www.publiccode.net/standard)
