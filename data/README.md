# data/

把 Make Me a Hanzi 的兩個資料檔放進這個資料夾：

- `dictionary.txt`
- `graphics.txt`

下載來源（來自 skishore/makemeahanzi 專案）：

- https://raw.githubusercontent.com/skishore/makemeahanzi/master/dictionary.txt
- https://raw.githubusercontent.com/skishore/makemeahanzi/master/graphics.txt

放進這個資料夾後，網頁的 `index.html` 會自動從 `data/dictionary.txt` 和 `data/graphics.txt` 讀取，
首次載入後會存進瀏覽器 IndexedDB 快取，之後不用重複下載。

檔案較大（dictionary.txt 約 2.45MB，graphics.txt 約 29.4MB），用一般的 `git add` / `git commit` / `git push`
上傳即可，不需要 Git LFS。
