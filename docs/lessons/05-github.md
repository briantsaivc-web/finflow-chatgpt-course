# 單元 5｜GitHub 是你的時光機

## 四個白話名詞

| 名詞 | 白話 |
|---|---|
| Repository | 這個專案的雲端資料夾與歷史 |
| commit | 一個有說明文字的存檔點 |
| push | 把本機存檔送到 GitHub |
| branch | 從正常版本分出一條試驗路線 |

## 第一次推送

使用 [C01 第一次推送](../commands/C01-first-push.md)。看到 GitHub 網頁出現檔案後才算成功。

## 每次修改的固定節奏

1. 先確認目前遊戲能玩。
2. 一次完成一個小主題。
3. 執行 `git status --short` 看變動。
4. `git add .`
5. 寫清楚 commit 訊息。
6. `git push`

[複製 C02 日常更新](../commands/C02-daily-push.md)

## 好與壞的 commit 訊息

```text
不好：update
不好：修正
較好：修正 NPC 在商城冷卻時重複購買造成的死鎖
較好：新增單元 4 Debug 教學與 Bug 紀錄表
```

## 大改之前先開分支

如果這次會改很多檔案、換架構或不確定是否成功，使用 [C03 建立分支](../commands/C03-branch.md)。

## 改壞時不要慌

先停止繼續修改，記錄目前錯誤，再用 [C04 回到正常版本](../commands/C04-recover.md) 查明可回復的存檔點。不要在不理解目標的情況下使用強制覆蓋或刪除整個資料夾。

## 本單元存檔

- GitHub 上看得到專案
- 至少三筆有意義的 commit
- 能指出哪一筆是最後正常版本
- 至少練習一次建立 branch

