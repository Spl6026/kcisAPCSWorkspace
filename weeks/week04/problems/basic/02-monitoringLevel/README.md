# 02 監測指數分級

難度：基礎

## 題目說明

某監測系統使用自訂指數分級：低於 35 為 Pleasant；35～60 為 Unpleasant；高於 60 為 Health Hazard。依讀值輸出對應標記。這是本題的分類規則，不代表實際空氣品質標準。

## 輸入格式

輸入一個整數指數 x。

## 輸出格式

輸出 Pleasant、Unpleasant 或 Health Hazard，大小寫與空格須相同。

## 資料範圍

0 ≤ x ≤ 500。

## 範例 1

### 輸入

```text
35
```

### 輸出

```text
Unpleasant
```

## 範例 2

### 輸入

```text
61
```

### 輸出

```text
Health Hazard
```

## 範例說明

35 包含在中間區間；61 超過上界。
