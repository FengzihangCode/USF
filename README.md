<image src="https://github.com/user-attachments/assets/563db63c-954f-4d47-839e-c475d88ab7fc" height="128"/>

语言：简体中文｜<a href="./README_en.md">English</a>

# USF - 通用课程表格式

USF（Universal Schedule Format）是一种高效的课程表数据格式，旨在高效精简的同时又支持课程名称、教师、教室、时间段和单双周规则的使用

## 特点

✅ 紧凑高效：比传统格式减少冗余字段

✅ 简单方便：简单的 JSON 结构，适用于各类应用

✅ 支持单双周：可设置课程的单双周规则

✅ 自动补全：可在 VS Code 与 JetBrains 系列 IDE 中开启自动代码补全

## 格式
USF 文件采用 UTF-8 编码格式

## 自动补全
### Visual Studio
#### 导入
安装 "JSON Schema" 扩展并导入 [Schema](https://raw.githubusercontent.com/USF-org/USF/refs/heads/main/usf.schema.json)

或通过如下方式导入

![VSCodeDemo](https://github.com/user-attachments/assets/5df5f3e5-a471-439b-8690-5ef8b74a7c5e)

### JetBrains
#### 使用 $schema 关键字
在文件顶部，输入`# $schema: USF`即可正常使用

![JetBrainsDemo](https://github.com/user-attachments/assets/3e831b42-3e03-403c-a100-d87605e03393)


也可参考 [Use $schema keyword](https://www.jetbrains.com/help/idea/yaml.html#use-schema-keyword)
