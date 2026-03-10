# 放射性元素定年模擬器 | Radioactive Dating Simulator

[![GitHub license](https://img.shields.io/github/license/xun73/C14-Dating-Simulator?color=blue)](https://github.com/xun73/C14-Dating-Simulator/blob/main/LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Live-Demo-brightgreen)](https://xun73.github.io/C14-Dating-Simulator/)

這是一個互動式的科學模擬工具，旨在幫助學生與教育者理解放射性同位素（以碳-14 為例）的衰變原理與定年應用。

This is an interactive scientific simulation tool designed to help students and educators understand the principles of radioactive isotope decay (using Carbon-14 as an example) and its applications in dating.

## 🔗 線上演示 | Live Demo
**[立即體驗 / Try it Now](https://xun73.github.io/C14-Dating-Simulator/)**

---

## ✨ 核心功能 | Key Features

* **微觀與宏觀觀察 (Micro & Macro Views)**：
    * **微觀 (Micro)**：即時觀察個別原子的衰變狀態切換（從 $^{14}C$ 變為 $^{14}N$）。
    * **宏觀 (Macro)**：動態繪製衰變曲線，對比「實際隨機衰變」與「理論計算」的數量差異。
* **互動式參數 (Interactive Parameters)**：
    * 可自定義初始 $^{14}C$ 數量 ($N_0$)。
    * 滑動時間軸觀察不同半衰期 ($T_{1/2}$) 時間點的即時變化。
* **雙語界面 (Bilingual Support)**：支援繁體中文與英文介面一鍵切換。
* **響應式設計 (Responsive Design)**：優化介面排版，支援電腦與行動裝置瀏覽。

---

## 🔬 科學原理 | Scientific Principle

本模擬器基於放射性衰變公式進行理論計算：
This simulator performs theoretical calculations based on the radioactive decay formula:

$$N(t) = N_0 \times \left(\frac{1}{2}\right)^{\frac{t}{T_{1/2}}}$$

* **半衰期 ($T_{1/2}$)**：設定為 **5,730 年** (碳-14)。
* **最大觀測時間**：可模擬至 12 個半衰期 (**68,760 年**)。

---

## 🛠️ 技術架構 | Technologies

* **HTML5 Canvas**: 用於高效能渲染原子狀態動畫與統計圖表。
* **Tailwind CSS**: 用於精美且響應式的 UI 介面設計。
* **Vanilla JavaScript**: 核心衰變機率演算法與邏輯控制。

---

## 👨‍🏫 關於作者 | About the Author

* **製作人 (Author)**: 吳秉勳 (Bing-Syun Wu)
* **單位 (Affiliation)**: 臺中市立惠文高中 地球科學科 (Earth Science Teacher, Hui-Wen Senior High School)

---

### 授權條款 | License
本專案採用 **MIT License** 授權。歡迎教學使用、分享與二次開發。
This project is licensed under the **MIT License**. Feel free to use it for teaching, sharing, or further development.
