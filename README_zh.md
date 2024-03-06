# 发票光学字符识别项目

## 项目概述
本项目基于Python 3开发，旨在使用光学字符识别技术自动识别并提取发票上的信息。它专为财务、会计以及任何需要大量处理发票的领域设计，目的是提高效率并减少手动输入错误。

## 特点
- **自动文本识别：** 利用OCR技术自动识别发票上的文本，包括但不限于发票号码、日期、金额等。
- **支持多种发票格式：** 能够处理不同格式和布局的发票，包括数字发票和纸质发票。
- **数据导出：** 识别的数据可以导出为JSON, CSV格式，方便后续使用。
- **用户友好界面：** 简单易用的界面让用户轻松上传和处理发票。

## 开始使用
以下步骤将帮助您快速设置并运行项目。

### 先决条件
- Python 3
- 其他依赖项请参见`Pipfile`文件。

### 安装
1. 克隆仓库到您的本地机器。
   ```
   git clone https://github.com/dowdah/invoice_ocr.git
   ```
2. 导航到项目目录并安装所需的依赖项。
   ```
   cd invoice_ocr
   pipenv install
   ```

### 使用
1. 运行主程序。
   ```
   python main.py <发票图片路径>
   ```
2. 系统将处理图片并显示识别结果。
3. 您可以选择将结果导出到CSV文件。

## 技术架构
- **OCR引擎：** 该项目使用[Tesseract](https://github.com/tesseract-ocr/tesseract)作为主要的OCR引擎。
- **图像处理：** 使用[OpenCV](https://opencv.org/)进行初步图像处理以提高识别准确性。

## 贡献指南
我们欢迎所有形式的贡献，包括但不限于新功能提案、错误修复、文档更新等。

## 许可证
该项目根据MIT许可证授权。详情请见`LICENSE`文件。

## 联系方式
如有任何问题或建议，请通过以下方式与我们联系：
- 电子邮件：dowdah@sheldonwonderland.top
- GitHub Issues