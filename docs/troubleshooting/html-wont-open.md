# HTML 打不開怎麼辦

## 先檢查檔名

Windows 可能把檔案存成 `index.html.txt`。請在檔案總管開啟「顯示副檔名」，確認真正檔名是：

```text
index.html
```

## 再檢查內容

用記事本開啟，第一段通常應包含：

```html
<!doctype html>
<html lang="zh-Hant">
```

如果內容前後出現三個反引號：

````text
```html
...
```
````

請刪除最前與最後的反引號，只留下 HTML 本身。

## 仍然失敗

把以下三項一起提供給 AI：

1. 完整檔名截圖。
2. 瀏覽器畫面截圖。
3. 檔案開頭 30 行。

使用 [P04 Bug 診斷卡](../prompts/P04-debug.md)，不要只說「不能用」。

