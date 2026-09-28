# Dawn Tracker 使用教程

本文件只整理 Dawn Tracker 的正常使用、連接、佩戴、校準、配對、開關機與固件更新。
故障排查請查看《Dawn Tracker 故障排查 FAQ.md》。
各型號硬體參數請查看《Dawn Tracker 參數.md》。

目前適用型號：

- Dawn Tracker Mini 2T
- Dawn Tracker Mini 2
- Dawn Tracker Mini 2 Pro
- Dawn Tracker Lite 2（v2.1）

其他舊型號已過時，本教程不再以舊版 Mini / Lite / Slim 作為主要說明對象。

---

## 1. 基本說明

Dawn Tracker 是基於 SlimeVR 使用流程的無線全身追蹤器。

典型使用流程：

Dawn Tracker → Dawn Tracker 接收器 → 電腦 → SlimeVR Server → SteamVR / VRChat / 其他支援全身追蹤的應用

如果 SlimeVR Server 首次設定中出現 Wi‑Fi 設定頁面，可直接跳過並使用接收器。

---

## 2. 首次使用流程

建議首次使用按以下順序完成：

1. 安裝 SlimeVR Server。
2. 連接 Dawn Tracker 接收器。
3. 開啟所有 Tracker。
4. 確認 Tracker 已連接。
5. 分配 Tracker 身體部位。
6. 正確佩戴 Tracker。
7. 完成佩戴校準。
8. 設定身體比例。
9. 進入 SteamVR / VRChat 檢查追蹤效果。

---

## 3. 安裝 SlimeVR Server

1. 下載並安裝 SlimeVR Server / SlimeVR Installer。
2. 安裝時保留 SteamVR 相關元件。
3. 安裝完成後啟動 SlimeVR Server。
4. 首次設定遇到 Wi‑Fi 頁面時，Dawn Tracker 可直接跳過 Wi‑Fi 設定並使用接收器。

---

## 4. 連接接收器與 Tracker

### 4.1 連接接收器

1. 使用可傳輸資料的 USB 數據線將 Dawn Tracker 接收器連接到電腦。
2. 等待系統識別接收器。
3. 打開 SlimeVR Server。
4. 開啟所有 Tracker。
5. 確認 Tracker 是否出現在 SlimeVR Server 的「設備」列表中。SlimeVR Server 不會顯示 Receiver。

注意：

- Dawn Tracker 均使用獨立接收器方案，無需配網。
- 不要使用只能充電、不能傳輸資料的 USB 線。
- 如果接收不穩，可更換 USB 線或 USB 口。
- 若有明顯卡頓，可使用 USB 延長線讓接收器遠離電腦主機和高干擾設備。

---

## 5. 開機與關機

### 5.1 Mini 2 系列

適用：

- Dawn Tracker Mini 2T
- Dawn Tracker Mini 2
- Dawn Tracker Mini 2 Pro

關閉全部 Tracker：

- 單擊接收器靠近 Type‑C 接口的按鈕，即可關閉所有 Tracker。
- 也可以在 Dawn Tracker Tools 中選擇 Receiver，使用「全部關機」功能。

開機：

- Tracker 從充電底座取下後會自動開機。

### 5.2 Dawn Tracker Lite 2（v2.1）

Lite 2 的實體開關機方式以產品本體與對應版本說明為準。

---

## 6. 接收器與 Tracker 配對

正常出廠套裝已完成配對，正常使用或一般連接故障時不要重新配對。

只有在以下情況下才需要進行配對：

- 更換接收器。
- 新增 Tracker。
- 已明確確認配對資訊丟失。

如果只是連不上、掉線、TPS 低或信號差，應先按《Dawn Tracker 故障排查 FAQ.md》排查，不要優先重新配對。

確實需要配對時，可使用以下兩種方式。

### 6.1 使用 Dawn Tracker Tools 配對

#### 接收器進入配對模式

1. 打開 Dawn Tracker Tools。
2. 在裝置列表選擇名稱帶有「Receiver」的接收器。
3. 輸入：

`pair`

4. 接收器進入配對狀態。

#### Tracker 進入配對模式

方法一：按鍵配對

1. 確認 Tracker 已開機。
2. 若該型號 / 批次支援按鍵配對，長按 Tracker 按鈕約 5 秒進入配對模式。

方法二：有線配對

1. 將 Tracker 以數據方式連接到電腦。
2. Dawn Tracker Mini 2 系列需透過充電底座的數據口連接。
3. Dawn Tracker Lite 2 可使用 Type‑C 數據線連接。
4. 打開 Dawn Tracker Tools。
5. 選擇對應 Tracker。
6. 輸入：

`pair`

### 6.2 使用 SmolSlime Web Configurator 配對

也可以使用：

https://marco5699.github.io/SmolSlimeWebConfigurator/SmolSlimeConfigurator.html

操作時：

1. 使用支援 Web Serial / WebUSB 的瀏覽器打開配置器。
2. 將接收器或 Tracker 連接到電腦。
3. 在網頁中選擇對應裝置。
4. 按頁面提供的配對功能完成操作。

如果瀏覽器無法看到裝置，可先關閉可能佔用串口的 Dawn Tracker Tools / SlimeVR Server，再重新連接。

配對完成後，回到 SlimeVR Server 確認 Tracker 是否已出現在列表中。

---

## 7. Tracker 部位分配

在 Tracker 全部連接成功後進行部位分配。

1. 進入 SlimeVR Server 的「追蹤器分配」頁面。
2. 選擇需要設定的身體部位。
3. 輕拍 / 雙擊對應 Tracker 進行識別。
4. 如果輕拍識別不明顯，可輕微晃動目標 Tracker，再選擇高亮裝置。
5. 分配到正確身體部位。
6. 重複直到全部 Tracker 分配完成。

### 7.1 推薦部位分配

| 套裝 | 推薦部位 |
|---|---|
| 6 點 | 胸部、腰部 / 臀部、左大腿、右大腿、左小腿 / 腳踝、右小腿 / 腳踝 |
| 8 點（上臂方案） | 6 點基礎 + 左上臂、右上臂 |
| 8 點（腳部方案） | 6 點基礎 + 左腳、右腳 |
| 10 點 | 6 點基礎 + 左上臂、右上臂、左腳、右腳 |

說明：

- 8 點可按需求在「雙上臂」與「雙腳」之間選擇。
- VR 頭顯通常負責頭部追蹤。
- VR 控制器通常負責雙手追蹤。
- 左右部位不要分配反。

---

## 8. Tracker 佩戴

佩戴穩定性會直接影響追蹤效果。

### 8.1 基本原則

- Tracker 必須固定穩，不要鬆動。
- 不要裝在容易晃動的寬鬆衣物上。
- 左右對稱部位高度盡量一致。
- 大腿 Tracker 不要太靠近膝蓋。
- 腳部 Tracker 要避免旋轉或滑動。
- 每次大幅改變佩戴位置後，都應重新做佩戴校準。

### 8.2 常見佩戴位置

| 部位 | 建議位置 |
|---|---|
| 胸部 | 胸前 |
| 腰部 / 臀部 | 腰前、腰後或穩定的髖部位置 |
| 大腿 | 大腿前側或側前方 |
| 小腿 / 腳踝 | 小腿前側或側邊 |
| 腳部 | 腳背或腳側，必須固定穩 |
| 上臂 | 上臂外側或側前方 |

Tracker 可以佩戴在對應部位的前側、後側或側邊，但 SlimeVR Server 中的佩戴方向必須與實際一致。

### 8.3 綁帶快拆卡扣

參考影片：
https://www.bilibili.com/video/BV1SqoQBMEXa/?share_source=copy_web&vd_source=5b000fac399bb0c6c212a0cbbf3ec0ec&t=182

---

## 9. 佩戴校準

完成佩戴與部位分配後，進入 SlimeVR Server 的「佩戴校準」頁面。

推薦順序：

1. 完整重置。
2. 佩戴重置。
3. 使用雙腳 Tracker 時，再做腳部佩戴重置。
4. 檢查預覽骨架。
5. 再進行身體比例設定。

### 9.1 完整重置

完整重置主要用於重新對齊使用者面向方向與 Tracker 朝向。

姿勢：

- 自然站直。
- 雙腳與肩同寬。
- 雙手自然下垂。
- 頭和身體朝向正前方。
- 保持短暫靜止後執行完整重置。

### 9.2 佩戴重置

佩戴重置用於校正 Tracker 實際綁在身體上的角度。

建議姿勢：

- 雙腿彎曲，做類似滑雪的微蹲姿勢。
- 上半身向前傾。
- 雙腿保持靠攏、朝向一致。
- 手臂彎曲。
- 雙手靠近胸口。
- 雙臂盡量貼近身體。
- 身體不要左右歪。
- 腳不要明顯內八或外八。

如果使用上臂 Tracker，佩戴重置時特別要注意雙臂貼近身體。

### 9.3 腳部佩戴重置

如果有分配左腳 / 右腳 Tracker，完成一般佩戴重置後，再做腳部佩戴重置。

---

## 10. 身體比例設定

1. 先確認 VR 頭顯的地面高度 / 安全邊界已正確設定。
2. 進入 SlimeVR Server 的「身體比例」頁面。
3. 按軟體提示完成自動設定。
4. 如果自動結果不理想，再使用手動方式微調。
5. 調整完成後檢查預覽骨架。
6. 必要時重新做完整重置與佩戴重置。

---

## 11. 持續校準

如果使用的 SlimeVR Server 版本中存在「持續校準」：

1. 進入「設定」。
2. 找到「持續校準」。
3. 選擇「配置持續校準」。
4. 按軟體示例完成需要的姿勢動作。

持續校準不能替代正確佩戴、正確部位分配與正確身體比例設定。

---

## 12. 固件更新

請使用 Dawn Tracker 官方固件與對應工具。

### 12.1 Dawn Tracker Lite 2（v2.1）

Lite 2 刷寫固件使用：

**Dawn Tracker(WCH)燒錄工具**

流程：

1. 使用可傳輸資料的 Type‑C 數據線將 Lite 2 連接到電腦。
2. 打開 Dawn Tracker(WCH)燒錄工具。
3. 選擇對應設備與固件。
4. 按工具提示完成燒錄。

### 12.2 Dawn Tracker Mini 2 系列

適用：

- Dawn Tracker Mini 2T
- Dawn Tracker Mini 2
- Dawn Tracker Mini 2 Pro

Mini 2 系列使用 Dawn Tracker Tools 更新。

流程：

1. 將 Tracker 放入 / 連接到支援數據傳輸的充電底座接口。
2. 使用數據線把底座連接到電腦。
3. 打開 Dawn Tracker Tools。
4. 選擇對應 Tracker / Receiver。
5. 按工具提示執行更新。

充電底座靠近 Type‑C 母座的數據口可用於 Tracker 有線數據連接。

不要刷寫來源不明的非官方固件。

---

## 13. 磁力計

目前型號中：

- Dawn Tracker Mini 2：支援磁力計。
- Dawn Tracker Mini 2 Pro：支援磁力計。
- Dawn Tracker Mini 2T：不使用磁力計。
- Dawn Tracker Lite 2（v2.1）：不使用磁力計。

若需要在支援磁力計的型號上開啟磁力計，可在 Dawn Tracker Tools 選擇 Receiver 後使用：

`send all mag on`

完成後重啟 SlimeVR Server。

若目前固件版本的指令行為與此不同，以最新 Dawn Tracker Tools / 固件說明為準。
