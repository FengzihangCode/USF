<image src="https://github.com/user-attachments/assets/563db63c-954f-4d47-839e-c475d88ab7fc" height="128"/>

Language:  <a href="./README.md">简体中文</a>｜English

# USF - Universal Schedule Format

USF (Universal Schedule Format) is an efficient curriculum data format, which aims to streamline efficiently and support the use of course names, teachers, classrooms, time periods and single and double weekly rules.

## Features

✅ Compact & Efficient: Reduce redundant fields compared with traditional formats

✅ Simple & Convenient: Simple JSON structure, suitable for various applications

✅ Support Week Rules: Weeks rules can be set for courses

✅ Autocomplete: Automatic code complete can be turned on in VS Code and JetBrains IDEs

## Format
USF files are encoded in UTF-8 format.

## Autocomplete
### Visual Studio
#### Import
Install "JSON Schema" extension and import [Schema](https://raw.githubusercontent.com/USF-org/USF/refs/heads/main/usf.schema.json)

Or import by following steps

![VSCodeDemo](https://github.com/user-attachments/assets/5df5f3e5-a471-439b-8690-5ef8b74a7c5e)

### JetBrains
#### Use $schema Keyword
Type `# $schema: USF` at the top of the file to enable autocomplete

![JetBrainsDemo](https://github.com/user-attachments/assets/3e831b42-3e03-403c-a100-d87605e03393)

See Also [Use $schema keyword](https://www.jetbrains.com/help/idea/yaml.html#use-schema-keyword)
