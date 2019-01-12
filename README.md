# EditorConfig
## 介紹
[EditorConfig](https://editorconfig.org/) 幫助開發人員在不同的編輯器和IDE之間定義和維護一致的編碼風格。
## 編輯器外掛
- **Sublime Text**
    - [EditorConfig](https://github.com/sindresorhus/editorconfig-sublime#readme)
- **VSCode**
    - [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
## 配置 EditorConfig 設定檔
於根目錄新增檔案 .editorconfig，於此設定編輯風格。
```ini
root = true

[*]
charset = utf-8
indent_style = space
end_of_line = lf
insert_final_newline = true
trim_trailing_whitespace = true

[*.php]
indent_size = 4

[*.{js,html,json,pug,vue,css,scss,sass,yml}]
indent_size = 2

```