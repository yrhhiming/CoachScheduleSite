# Coach Schedule App 英文版第二次翻譯檢查

檢查頁面：

- 中文版：https://yrhhiming.github.io/CoachScheduleSite
- 英文版：https://yrhhiming.github.io/CoachScheduleSite/en.html

## 整體判斷

英文版整體可用，沒有明顯嚴重文法錯誤。

但有幾處中文與英文的語意、用詞或功能描述不完全一致，值得修改。

## 需要修正或調整的地方

### 1. 拖曳排課 — 功能描述不完全一致

**中文版：**

> 長按課次拖曳，秒排、複製、移動課表

**英文版：**

> Long-press and drag a session to schedule, copy, or move it in seconds

問題：

- `schedule` 在這裡不完全等於中文的「排課」。
- 中文的「課次」是 session，這個翻譯正確。
- `in seconds` 是「幾秒內」，中文的「秒排」是口語化的快速排課，意思接近。
- 英文整體自然，但 `schedule, copy, or move it` 會讓人以為拖曳本身可以直接完成三種動作，需看實際 App 操作邏輯。

**建議修改：**

> Long-press and drag sessions to quickly schedule, copy, or move them.

---

### 2. 學生管理 — 「近期課表」被翻成 upcoming schedule

**中文版：**

> 搜尋、序號、一鍵複製近期課表傳給學生

**英文版：**

> Search, numbered list, and one-tap copy of a client's upcoming schedule

差異：

- `upcoming schedule` 是「即將到來的課表」，不一定等於「近期課表」。
- 中文有「傳給學生」，英文只有 copy，沒有明確翻出分享給學生。

**建議修改：**

如果原意是近期課表：

> Search, numbered list, and one-tap copy of a client's recent schedule to share with them.

如果原意是未來課程：

> Search, numbered list, and one-tap copy of a client's upcoming schedule to share with them.

---

### 3. 教練休假日 — 英文增加了中文沒有的限制

**中文版：**

> 設定休假，那天自動不排課

**英文版：**

> Set a day off and the app blocks new sessions on it automatically

英文寫成 `blocks new sessions`，意思偏向「阻止新增課次」。

如果實際功能是休假日不能排課，建議：

> Set a day off and the app automatically prevents scheduling on that day.

如果 App 只會阻止新增課次，目前英文可以保留。

---

### 4. 完全離線 — `no network` 不自然

**中文版：**

> 資料只存在你的手機，不連網、不上傳

**英文版：**

> Your data stays on your phone — no network, no upload

`no network` 不是很自然的英文產品說法，可能被理解為「沒有網路功能」，而不是「App 不會連線」。

**建議修改：**

> Your data stays on your phone — no internet connection, no uploads.

或：

> Your data stays on your phone. The app works completely offline, with no data uploads.

---

### 5. 第一個畫面 — `one and only coach` 文法正確，但略口語

**中文版：**

> 這就是這個 App 唯一的一位教練。

**英文版：**

> that's the app's one and only coach.

這句沒有文法錯誤，但 `one and only coach` 帶有口語強調感。

如果要表達產品定位，可以改成：

> This app is designed for one coach to manage their own schedule.

若只想忠實翻譯，原句可保留。

---

### 6. `This Week` — 中文是「本週」，翻譯正確

**中文版：**

> 送出名字後會進入「本週」畫面

**英文版：**

> After you submit your name you land on the Week screen

文法正確。

若 App 介面上的實際按鈕名稱是 `This Week`，建議統一：

> After you submit your name, you land on the “This Week” screen.

---

### 7. 選單 — `View` 翻譯正確，但可更自然

**中文版：**

> 顯示方式：切換「週」或「月」檢視

**英文版：**

> View: switch between Week or Month

建議：

> View: switch between Week and Month views.

`between A and B` 比 `between A or B` 更自然。

---

### 8. 設定 — `Students` 與 `Clients` 不一致

英文版有以下混用：

- `Client Management`
- `Students`
- `manage all your clients`

中文統一使用「學生」，英文卻混用 `Client` 與 `Student`。

對個人教練 App 而言，`Clients` 通常比 `Students` 更自然，但最重要的是統一。

#### 如果採用 Clients

> Client Management

> Settings: Clients, Days Off, Language, Week Starts On

> Tap “Clients” in the menu to manage all your clients.

#### 如果採用 Students

則所有相關介面與說明都使用 `Students`，不要混用 `Clients`。

---

### 9. 「一週的第一天」翻譯正確

**中文版：**

> 一週的第一天

**英文版：**

> Week Starts On

這個翻譯符合日曆設定的常見用語，不需要修改。

---

### 10. 新增學生 — `ID` 是否等於「學號」

**中文版：**

> 輸入姓名（學號、備註可選填），按「完成」

**英文版：**

> Enter a name (ID and notes are optional), tap Done

這句翻譯正確。

但如果欄位確實是「學號」，建議寫得更精確：

> Enter a name (Student ID and notes are optional), then tap Done.

如果欄位是一般學生編號，`ID` 即可。

---

### 11. 「向左滑」— 可讓受詞更明確

**中文版：**

> 向左滑：停用開關、複製課表、刪除學生

**英文版：**

> Swipe left: pause toggle, copy schedule, delete

建議：

> Swipe left: pause, copy schedule, or delete a client.

如果統一使用 Students：

> Swipe left: pause, copy schedule, or delete a student.

---

### 12. 「一格一人，絕不重複」— 英文可更自然

**中文版：**

> 一格一人，絕不重複。

**英文版：**

> one slot, one person, never overlapping.

英文意思可理解，但 `never overlapping` 不是完整自然的句子。

**建議修改：**

> One slot, one person — no overlapping sessions.

或：

> Each slot can have only one person. Sessions never overlap.

---

### 13. 「取代」— 翻譯正確

**中文版：**

> 取代：拖到已有課次的格子

**英文版：**

> Replace: drag onto a slot that's already taken

這句正確，可以保留。

---

### 14. 「兩堂課疊在同一格」— 翻譯正確

**中文版：**

> 不會不小心把兩堂課疊在同一格。

**英文版：**

> so two sessions can never accidentally stack in the same slot.

`stack` 在排課介面中可以理解為重疊，沒有問題。

---

### 15. 教練休假日 — 休假編輯模式翻譯正確

**中文版：**

> 並自動進入休假編輯模式。

**英文版：**

> switches straight into day-off editing mode.

這句自然，可以保留。

---

### 16. 粉紅提示條 — `toggle it off` 指代不夠明確

**中文版：**

> 上方粉紅提示條，點日期切換休假；休假日整欄鋪淡粉紅色

**英文版：**

> Pink banner up top — tap a date to toggle it off; days off get a soft pink column

`toggle it off` 的 `it` 指代不夠明確，可能讓人不清楚是在切換日期還是休假狀態。

**建議修改：**

> Pink banner up top — tap a date to toggle the day off; days off are highlighted with a soft pink column.

---

## 重大語意差異整理

| 項目 | 中文原意 | 英文目前版本 | 判斷 |
|---|---|---|---|
| 學生管理 | 近期課表傳給學生 | upcoming schedule | 語意略不同 |
| 教練休假日 | 自動不排課 | blocks new sessions | 可能縮小功能範圍 |
| 完全離線 | 不連網、不上傳 | no network, no upload | 英文不自然 |
| 學生 / 客戶 | 統一使用學生 | Client / Student 混用 | 產品術語不一致 |
| 排課核心 | 一格一人，絕不重複 | one slot, one person, never overlapping | 文法可改善 |
| 休假提示 | 點日期切換休假 | toggle it off | 指代不夠明確 |

## 建議優先修改順序

1. 統一 `Client` 與 `Student`。
2. 將 `no network, no upload` 改成自然英文。
3. 確認 `upcoming schedule` 是否真的是「近期課表」。
4. 確認 `blocks new sessions` 是否符合休假日的實際功能。
5. 將 `never overlapping` 改成 `no overlapping sessions`。
6. 將 `toggle it off` 改成明確的 `toggle the day off`。

## 最終判斷

英文版整體可用，沒有明顯嚴重文法錯誤。

最重要的問題不是基本文法，而是：

- 產品術語一致性
- 中文功能描述與英文功能描述是否完全相同
- 離線功能的英文表達是否精確
- 休假日與課表操作的實際行為是否被正確描述
