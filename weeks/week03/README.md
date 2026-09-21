# Week 03：多步驟算術、整除與模數

## 今天的內容

把題意的單位與公式先寫清楚，再拆成中間變數。需要小數時使用適當型態；`std::fixed` 與 `std::setprecision` 可以控制小數位數。

### 整除、餘數與模數

對非負整數而言，`a / b` 取得整數商，`a % b` 取得餘數。例如：

```cpp
int quotient = 17 / 5;  // 3
int remainder = 17 % 5; // 2
```

因為 `17 = 3 * 5 + 2`。餘數可用來拆解時間、分組，也能把持續增加的數值限制在固定週期內，例如 `(position + steps) % 8` 的結果一定落在 0～7。

本週題目只對非負整數使用 `%`。除數不可為 0；負數餘數的語言規則留到有實際需求時再討論。

## 題目

依課堂進度選題，不要求全部完成。作答檔 main.cpp 留空，請自行撰寫完整程式。

### 本週練習

| 題目 | 難度 |
|---|---|
| [01 展區圍邊與面積](problems/basic/01-exhibitArea/README.md) | 基礎 |
| [02 量測數據換算](problems/basic/02-measurementConversion/README.md) | 基礎 |
| [03 紀錄時間換算](problems/basic/03-durationConversion/README.md) | 基礎：整除與模數 |
| [04 模型指標取整](problems/advanced/04-roundedIndicator/README.md) | 進階 |

## 操作與測試

在 VS Code 開啟題目資料夾，閱讀 README 後完成程式。空白 main.cpp 尚不能編譯，要先寫出程式入口。修改後重新編譯，用範例核對結果，再試零、最小值或邊界情況；不要額外輸出「請輸入」等提示文字。

範例中的空格與空行都是輸入輸出的一部分。題目寫「直到輸入結束」時，Windows 終端機可在新行按 Ctrl+Z 再按 Enter；WSL／Linux 可在空行按 Ctrl+D。這些按鍵不屬於輸入資料。

下課前確認程式已儲存；要保留的進度請 commit 並 push 到自己的 GitHub repo。
