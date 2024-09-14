![image](https://github.com/user-attachments/assets/b4c6868d-ccc2-475a-a4dc-db0ea896e067)



# Axure 嵌入 HTML 网页文件的元件

此项目提供了一个可在 Axure RP9 原型中嵌入自定义 HTML 内容的元件，方便用户在原型设计中集成 HTML、CSS 和 JavaScript。

## 功能特点
- 轻松将 HTML 内容嵌入到 Axure RP9 原型中
- 支持完全自定义和响应式设计
- 简单易用，兼容 HTML、CSS 和 JavaScript

## 快速开始

### 环境要求
- Axure RP9 
- 基本的 HTML 和 Axure 自定义元件知识

### 安装步骤
1. 下载元件文件（`BLF-Axure-HTML-Tool.rplib`）。
2. 打开 Axure，并将该元件导入到你的项目中。
3. 按照以下使用说明将 HTML 内容嵌入原型中。

## 使用说明
### HTML嵌入
1. 在 Axure 中将 **HTML页面** 拖拽到你的原型页面，元件大小即为页面大小，支持拖入多个页面。  
         ![image](https://github.com/user-attachments/assets/64ed1fb1-c617-4bf0-b881-990d526f21d4)
2. 双击该元件以编辑其 HTML 内容。  
       ![image](https://github.com/user-attachments/assets/68af7074-3520-47c9-9978-3e45b792e2cf)
3. 将**HTML加载**工具（表现为一个动态面板，是透明的），拖入对应的Axure页面，注意**放在一个角落，一个页面只需要一个**。  
        ![image](https://github.com/user-attachments/assets/c667231d-c02b-467c-8e34-5b429ed74b93)
4. 预览页面，即可在原型中显示插入的HTML页面。  
   ![image](https://github.com/user-attachments/assets/e4d1e879-aecb-462d-9012-4f5d6acbac50)
### JavaScript 嵌入
1. 在 Axure 中将 **JS执行器** 拖拽到你的原型页面，填入JS代码。  
![image](https://github.com/user-attachments/assets/b33828be-3487-4ffd-bdf8-675216ca32b6)
![image](https://github.com/user-attachments/assets/54ba3348-4d9b-44ec-bdfd-9c5b4277435d)
3. 预览页面。
4. 元件中的JS代码会自动在页面加载时执行。
### JavaScript 调试
1. 在 Axure 中将 **JS调试器** 拖拽到你的原型页面，填入JS代码。  
![image](https://github.com/user-attachments/assets/08bbf594-50e5-4537-acf7-5cbf61249fd5)
![image](https://github.com/user-attachments/assets/3bb1b5f0-66b8-4cee-8479-af5acc66741f)
3. 预览页面。
4. 双击元件执行JS代码，支持在预览状态随时调整代码内容，双击运行。

## 项目结构
- **`html_embed_widget.rp`**: Axure 元件文件，包含可嵌入 HTML 内容的示例。
- **`README.md`**: 项目的说明文档，提供使用指南。
- **`examples/`**: 示例文件夹，内含使用该元件的详细演示。

## 常见问题
**1. 如何在 Axure 中调整嵌入内容的样式？**  
你可以直接在 HTML 元件中使用内联样式或添加外部 CSS 来自定义显示效果。

**2. Axure 中的交互功能会受影响吗？**  
使用该元件嵌入 HTML 不会影响 Axure 内的交互功能，你可以继续使用 Axure 提供的事件和交互逻辑。

## 许可证
此项目基于 MIT 许可证开源，详情请查看 [LICENSE](LICENSE) 文件。

