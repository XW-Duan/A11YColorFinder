# A11Y Color Finder

## 项目简介 / Project Overview

**A11Y Color Finder** 是一个基于OKLCH色彩模型的网页工具，用于根据 [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) AA 和 AAA 标准，找到最接近输入颜色且符合对比度要求的颜色。通过输入一个 HEX 颜色代码，用户可以快速获取与白色或黑色具有足够对比度的颜色，确保文本和背景的可读性。

**A11Y Color Finder** is a web tool based on the OKLCH color model, designed to find the closest color to the input that complies with [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) AA and AAA standards. By entering a HEX color code, users can quickly obtain colors that have sufficient contrast with white or black, ensuring the readability of text against backgrounds.

---

## 功能 / Features

- **颜色输入**：支持 HEX 颜色代码输入和颜色选择器。
- **对比度选择**：用户可以选择计算符合 AA (4.5:1) 或 AAA (7:1) 对比度标准的临近色。
- **即时结果**：计算完成后，显示符合条件的临近色及其对比度。
- **复制功能**：点击颜色代码或预览即可复制 HEX 代码。
- **响应式设计**：适配不同设备，确保良好的用户体验。

- **Color Input**: Supports HEX color code input and color picker.
- **Contrast Selection**: Users can choose to calculate adjacent colors that meet AA (4.5:1) or AAA (7:1) contrast standards.
- **Instant Results**: Displays adjacent colors that meet the criteria along with their contrast ratios upon calculation.
- **Copy Functionality**: Click on the color code or preview to copy the HEX code.
- **Responsive Design**: Adapts to various devices to ensure a good user experience.

---

## 安装 / Installation

1. **克隆仓库 / Clone the Repository**

   ```bash
   git clone https://github.com/XW-Duan/A11YColorFinder.git

	2.	导航到项目目录 / Navigate to the Project Directory

cd A11YColorFinder


	3.	打开 index.html 文件 / Open the index.html File
直接在浏览器中打开 index.html 文件即可使用，无需额外安装。
Simply open the index.html file in your browser to use the tool without any additional installation.

使用方法 / Usage
	1.	输入颜色 / Enter a Color
在文本框中输入一个有效的 HEX 颜色代码（例如 #FFFFFF），或者使用右侧的颜色选择器选择颜色。
Enter a valid HEX color code (e.g., #FFFFFF) in the text box or use the color picker on the right to select a color.
	2.	选择对比度标准 / Select Contrast Standards
勾选 AA 对比度 (4.5:1) 和/或 AAA 对比度 (7:1)，根据需要选择。
Check AA Contrast (4.5:1) and/or AAA Contrast (7:1) based on your requirements.
	3.	开始计算 / Start Calculation
点击 开始计算 按钮，工具将自动计算并显示最接近输入颜色且符合选定对比度标准的临近色。
Click the Start Calculation button to automatically compute and display the closest adjacent colors that meet the selected contrast standards.
	4.	查看结果 / View Results
计算完成后，结果区域将显示符合条件的颜色预览、HEX 代码和对比度比例。点击颜色代码或预览可以复制 HEX 代码。
After calculation, the results section will display color previews, HEX codes, and contrast ratios that meet the criteria. Click on the HEX code or preview to copy the HEX code.

### 项目编码由ChatGPT完成
