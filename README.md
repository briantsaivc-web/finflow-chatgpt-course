# FinFlow ChatGPT Course

《不會寫程式，照樣做出一款真的遊戲》線上課程資源。

## v0.6 重點

- `slides/output/`：100 頁正式課程簡報。
- `instructor/`：100 頁完整授課稿。
- `examples/checkpoints/CP01～CP06/`：六個可玩階段版本。
- `docs/prompts/`：可直接複製的 Prompt 卡。

## v0.7 試教現場包

- `workbook/`：可列印、可編輯的學員實作手冊。
- `instructor/two-hour-run-of-show.md`：120 分鐘講師流程。
- `instructor/forms/pilot-feedback.md`：試教回饋與觀察表。

## v0.8 兩小時正式工作坊

- `slides/output/FinFlow_兩小時零基礎AI遊戲工作坊_48頁_v0.8.pptx`
- `instructor/workshop-48-slide-notes.md`
- `instructor/demo-bugs/`：四個現場故障示範。
- `instructor/workshop-fallback-plan.md`：120／90／60 分鐘備援。
- `docs/forms/`：課前與課後問卷。

## 本地預覽

```cmd
py -m pip install -r requirements.txt
py -m mkdocs serve
```

瀏覽器開啟 `http://127.0.0.1:8000/`。

## 內容分區

- `docs/`：GitHub Pages 線上內容
- `slides/`：演講與課程簡報
- `book/`：實體書稿
- `shared/`：三版本共用 Prompt、checklist 與素材
- `examples/`：starter、checkpoint 與故障版遊戲
