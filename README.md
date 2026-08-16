# ESP32 Key-Activated Servo Website
<nav>
  <a href="#english">English</a> |
  <a href="#traditional-chinese">繁體中文</a> |
  <a href="#simplified-chinese">简体中文</a>
</nav>

<a id="english"></a>
## English

### Purpose

This responsive website presents the development story of the ESP32 Key-Activated Servo project. It explains how a keypad-and-servo interaction from an Arduino reference video became a readable, multilingual ESP32/Wokwi project.

### Features

- English, Traditional Chinese, and Simplified Chinese language switching.
- Responsive desktop and mobile navigation.
- Development journey from source reference to ESP32 port and touched-up Wokwi circuit.
- Hardware BOM, GPIO assignments, software architecture, evidence screenshots, and design rules.
- External links to the source video, Wokwi reference circuits, and current project builds.
- Local PDF downloads for the project report and presentation.

### Files and folders

```text
Website/
├── index.html
├── styles.css
├── app.js
├── favicon.svg
├── assets/
│   ├── baseline-build.png
│   ├── baseline-wiring.png
│   ├── touched-circuit.png
│   ├── touched-code-monitor.png
│   ├── touched-monitor.png
│   └── unmodified-circuit.png
└── pdf/
    ├── ESP32_Key_Activated_Servo_Presentation.pdf
    └── ESP32_Key_Activated_Servo_Report.pdf
```

### Local preview

From this `Website` folder, start a local static server:

```powershell
python -m http.server 8765
```

Then open <http://127.0.0.1:8765/> in a browser.

### Resources

- [Source video](https://www.facebook.com/reel/1370244634609367)
- [Wokwi keypad-input reference](https://wokwi.com/projects/294980637632233994)
- [Wokwi ESP32 servo reference](https://wokwi.com/projects/323706614646309460)
- [Current Wokwi project — unmodified](https://wokwi.com/projects/472447224339786753)
- [Current Wokwi project — touched up](https://wokwi.com/projects/472451829266659329)
- [Project report](pdf/ESP32_Key_Activated_Servo_Report.pdf)
- [Project presentation](pdf/ESP32_Key_Activated_Servo_Presentation.pdf)

### Maintenance

Keep user-facing translations in the `locales` object in `app.js`. When adding screenshots or documents, place them in `assets/` or `pdf/` and use relative links in `index.html`.

### Known limitations

The website documents the project and links to Wokwi; it does not run the ESP32 sketch or simulate the circuit locally.

<a id="traditional-chinese"></a>
## 繁體中文

### 用途

本響應式網站介紹 ESP32 Key-Activated Servo 專案的開發歷程，說明如何將 Arduino 參考影片中的鍵盤與伺服馬達互動，發展成清晰的多語言 ESP32/Wokwi 專案。

### 功能

- 支援 English、繁體中文與简体中文切換。
- 支援桌面與行動裝置響應式導覽。
- 呈現從來源參考、ESP32 移植到修正版 Wokwi 電路的開發歷程。
- 包含硬體 BOM、GPIO 腳位、軟體架構、驗證截圖與設計規則。
- 提供來源影片、Wokwi 參考電路與目前專案版本的外部連結。
- 提供專案報告與簡報的本地 PDF 下載。

### 檔案與資料夾

```text
Website/
├── index.html
├── styles.css
├── app.js
├── favicon.svg
├── assets/
│   ├── baseline-build.png
│   ├── baseline-wiring.png
│   ├── touched-circuit.png
│   ├── touched-code-monitor.png
│   ├── touched-monitor.png
│   └── unmodified-circuit.png
└── pdf/
    ├── ESP32_Key_Activated_Servo_Presentation.pdf
    └── ESP32_Key_Activated_Servo_Report.pdf
```

### 本機預覽

請在 `Website` 資料夾中啟動靜態伺服器：

```powershell
python -m http.server 8765
```

然後使用瀏覽器開啟 <http://127.0.0.1:8765/>。

### 資源

- [來源影片](https://www.facebook.com/reel/1370244634609367)
- [Wokwi keypad-input 參考電路](https://wokwi.com/projects/294980637632233994)
- [Wokwi ESP32 伺服馬達參考電路](https://wokwi.com/projects/323706614646309460)
- [目前 Wokwi 專案 — 未修改](https://wokwi.com/projects/472447224339786753)
- [目前 Wokwi 專案 — 修正版](https://wokwi.com/projects/472451829266659329)
- [專案報告](pdf/ESP32_Key_Activated_Servo_Report.pdf)
- [專案簡報](pdf/ESP32_Key_Activated_Servo_Presentation.pdf)

### 維護

請在 `app.js` 的 `locales` 物件中維護使用者介面的翻譯。新增截圖或文件時，請放入 `assets/` 或 `pdf/`，並在 `index.html` 中使用相對路徑連結。

### 已知限制

本網站用於說明專案並連結至 Wokwi；不會在本機執行 ESP32 程式或模擬電路。

<a id="simplified-chinese"></a>
## 简体中文

### 用途

本响应式网站介绍 ESP32 Key-Activated Servo 项目的开发历程，说明如何将 Arduino 参考视频中的键盘与舵机交互，发展成清晰的多语言 ESP32/Wokwi 项目。

### 功能

- 支持 English、繁體中文和简体中文切换。
- 支持桌面和移动设备响应式导航。
- 展示从来源参考、ESP32 移植到修正版 Wokwi 电路的开发历程。
- 包含硬件 BOM、GPIO 引脚、软件架构、验证截图和设计规则。
- 提供来源视频、Wokwi 参考电路和当前项目版本的外部链接。
- 提供项目报告和演示文稿的本地 PDF 下载。

### 文件和文件夹

```text
Website/
├── index.html
├── styles.css
├── app.js
├── favicon.svg
├── assets/
│   ├── baseline-build.png
│   ├── baseline-wiring.png
│   ├── touched-circuit.png
│   ├── touched-code-monitor.png
│   ├── touched-monitor.png
│   └── unmodified-circuit.png
└── pdf/
    ├── ESP32_Key_Activated_Servo_Presentation.pdf
    └── ESP32_Key_Activated_Servo_Report.pdf
```

### 本地预览

请在 `Website` 文件夹中启动静态服务器：

```powershell
python -m http.server 8765
```

然后使用浏览器打开 <http://127.0.0.1:8765/>。

### 资源

- [来源视频](https://www.facebook.com/reel/1370244634609367)
- [Wokwi keypad-input 参考电路](https://wokwi.com/projects/294980637632233994)
- [Wokwi ESP32 舵机参考电路](https://wokwi.com/projects/323706614646309460)
- [当前 Wokwi 项目 — 未修改](https://wokwi.com/projects/472447224339786753)
- [当前 Wokwi 项目 — 修正版](https://wokwi.com/projects/472451829266659329)
- [项目报告](pdf/ESP32_Key_Activated_Servo_Report.pdf)
- [项目演示文稿](pdf/ESP32_Key_Activated_Servo_Presentation.pdf)

### 维护

请在 `app.js` 的 `locales` 对象中维护用户界面翻译。添加截图或文档时，请放入 `assets/` 或 `pdf/`，并在 `index.html` 中使用相对路径链接。

### 已知限制

本网站用于说明项目并链接至 Wokwi；不会在本地运行 ESP32 程序或模拟电路。
