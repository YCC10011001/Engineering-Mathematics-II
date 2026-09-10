# Linear Algebra — course site

Slides, exercises and answers for the Linear Algebra course
(I-Wei Lai, Department of Electrical Engineering, National Taiwan Normal University).

Published with GitHub Pages: **https://ycc10011001.github.io/linear-algebra/**

---

## ⚠ 這個 repo 裡的檔案是**生成出來的，不要直接編輯**

每個 `.html` 都是建置產物。要改內容，請回到私有的工作室 repo
（`Desktop/YCC10011001`）改 `numeracy-deck-kit/lecture1.html`（簡報＋題目）或 `lecture1-answer.html`（答案），
然後重新建置：

```bash
cd ~/Desktop/YCC10011001/numeracy-deck-kit
python build-site.py ../../linear-algebra
```

在這裡直接改，下一次建置就會被整個蓋掉。

完整的維修流程寫在工作室 repo 的 `MAINTENANCE.md`。

## 資料夾＝網址

| 檔案 | 網址 |
|---|---|
| `index.html` | https://ycc10011001.github.io/linear-algebra/ |
| `lecture1/index.html` | https://ycc10011001.github.io/linear-algebra/lecture1/ （簡報，題目在最後 10 頁）|
| `lecture1/answer.html` | https://ycc10011001.github.io/linear-algebra/lecture1/answer.html |

`answer.html` 只有在工作室 repo 的 `build-site.py` 把該章的 `answer_public`
改成 `True` 之後才會被建出來——這就是「隔一週才公布答案」的開關。
