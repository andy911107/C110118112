### 甘特圖

```mermaid
gantt
    title 甘特圖

    section 任務1
    研擬計畫 1d      :a1, 2023-10-02, 1d
    
    section 任務2
    任務分配 4d     :a2, after a1, 4d

    section 任務3
    取得硬體 17d      :a3, after a1, 17d

    section 任務4
    程式開發 70d      :a4, after a2, 70d

    section 任務5
    安裝硬體 10d     :a5, after a3, 10d

    section 任務6
    程式測試 30d     :a6, after a4, 30d

    section 任務7
    撰寫使用手冊 25d  :a7, after a5, 25d

    section 任務8
    轉換檔案 20d     :a8, after a5, 20d

    section 任務9
    系統測試 25d     :a9, after a6, 25d

    section 任務10
    使用者訓練 20d   :a10, after a7 a8, 20d

    section 任務11
    使用者測試 25d   :a11, after a9 a10, 25d
```

### PERT

![PERTJPG](PERT.jpg "PERT圖")

# 關鍵路徑
```
1 -> 2 -> 4 -> 6 -> 9 -> 11
```
