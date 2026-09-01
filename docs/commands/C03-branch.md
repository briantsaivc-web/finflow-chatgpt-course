# C03｜建立試驗分支

```cmd
git switch main
git pull
git switch -c feature/你的功能名稱
```

完成並測試後：

```cmd
git add .
git commit -m "完成你的功能名稱"
git push -u origin feature/你的功能名稱
```

