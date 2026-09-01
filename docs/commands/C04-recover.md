# C04｜回到正常版本

先用唯讀指令查看歷史：

```cmd
git status
git log --oneline -10
```

如果只是想暫時查看舊版本，可建立救援分支：

```cmd
git switch -c rescue/檢查舊版 舊版commit代碼
```

不要在不知道影響範圍時使用 `git reset --hard` 或強制 push。把 `git status` 與 `git log` 輸出交給 AI 分析後再決定。

