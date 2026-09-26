---
name: extreme-simple-bw-line-core-accent
description: "Create student-copyable educational visuals with extremely simple black-and-white line art and restrained accent colors on 2–4 core information elements; use for elementary teaching slides, story maps, diagrams, and worksheets, not full-color decorative decks."
---

# 極致簡單黑白線稿加核心資訊顏色標示

把教學內容轉成「學生看得懂、畫得出、記得住」的視覺：黑白線稿是主體，低飽和色彩只標示每頁 2–4 類核心資訊。適用於國小教學投影片、故事地圖、概念圖、流程圖與可列印學習單。

不適用於需要照片、全彩插畫、精緻寫實、品牌主視覺或裝飾性海報的任務。

## 核心判斷順序

1. 先找出本頁唯一的教學主張：學生看完這頁，應該能說出什麼？
2. 把主張拆成 2–4 個可看見的資訊主角，例如人物、樹、物品、動作符號或關鍵圖示。
3. 其餘元素退到黑、深灰、淺灰，避免和核心資訊競爭。
4. 把每個主角降解成學生能模仿的基本形：圓、橢圓、矩形、三角形、短直線、簡單曲線。
5. 最後才決定色彩與版面，確認文字、空白與作答區沒有被圖像搶走。

## 視覺規則

### 線稿

- 使用粗而清楚的黑色外輪廓；內部只保留辨識動作所需的少量線條。
- 移除細密排線、寫實解剖、複雜樹皮、葉脈、衣服皺褶、遠景材質與小裝飾。
- 每個物件優先用一個輪廓說清楚，不用陰影堆出細節。
- 灰階只作少量辨識輔助，不用灰階取代輪廓。
- 同一角色、植物或物品跨頁維持相同的簡化造型。

### 常用基本形

- 人物：橢圓頭、簡單身體、四肢用短線或圓柱形表示，以一個姿勢線索表達動作。
- 樹木：圓雲狀樹冠、簡單樹幹、少量枝葉；不要畫滿葉片。
- 房子：矩形牆面＋三角屋頂。
- 船：弧形或矩形船身＋三角帆。
- 蘋果、錢幣、太陽：圓形加一個辨識記號。
- 風、雨、雪、雲：三條曲線、短直線、星號、雲朵輪廓即可。
- 流程或關係：使用粗箭頭、圓點、簡短連線，不增加裝飾性圖表。

### 色彩

- 基底：白色或米白背景；文字、框線、箭頭以黑色／深灰為主。
- 建議重點色：低飽和橄欖綠、蘋果紅、灰藍、赭金；使用色鉛筆淡洗感，不用螢光色、漸層或大面積純色塊。
- 每頁只選 2–4 類核心資訊上色；不是把每個物件都染色。
- 同一類資訊在整套簡報中盡量使用同一色，例如植物用綠、果實或情感符號用紅、移動／水面用藍、木材／結構用赭金。
- 標題、段落、關鍵詞、作答線與邊框預設維持黑白；只有使用者明確要求時才替文字上色。

## 投影片與學習單工作流

1. 先確認受眾、課堂情境、頁數、語言、16:9 規格、教材來源與使用權限。
2. 對既有簡報做風格變更時，保留原始版本，另建新版本資料夾與 PDF。
3. 全套改風格前，先做一張代表頁樣本，確認線條複雜度、核心色範圍、文字可讀性與留白。
4. 每頁逐張製作；在提示中明確寫出「保留文字、版面與頁碼，只改線稿複雜度或指定色彩」。
5. 學習單優先保留書寫線、空白框與列印邊界；圖示簡化，但不填入答案。
6. 若頁面是故事或流程，先保留因果順序與動作辨識，再刪除裝飾細節。

## 影像編修提示骨架

```text
Use case: precise-object-edit
Asset type: one complete 16:9 classroom slide or printable worksheet
Input images: Image 1: edit target
Primary request: simplify only the black-and-gray line art to a student-copyable level
Invariants: keep exact Traditional Chinese text, layout, page number, whitespace, and approved accent colors
Simplification: use bold contours, basic shapes, few interior lines, no hatching or realistic texture
Color edits: color only the named 2–4 core information classes; keep everything else black/gray
Constraints: one slide only, exact 16:9, no new text, no altered writing space
Avoid: dense detail, full-page color, bright neon, gradients, watermark, logos, or extra objects
```

## QA 清單

- 頁數、頁碼、16:9 比例與輸出格式正確。
- 所有可見文字與原核准版本一致，沒有新字、錯字或文字位移。
- 每頁可明確指出 2–4 類上色核心資訊；其他圖像仍以黑白灰為主。
- 主要圖像可以用基本形狀重畫，沒有依賴細密紋理才能辨識。
- 故事順序、因果關係、人物動作或概念關係仍然清楚。
- 學習單的作答線、空白區、邊界與列印可用性完整。
- 原始版本、簡化版本與 QA 報告分開保存，避免覆蓋可回復來源。
