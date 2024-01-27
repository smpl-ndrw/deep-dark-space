# Deep Dark Space Theme

## Recommended Settings

```json
"editor.guides.bracketPairs": "active",
"editor.bracketPairColorization.enabled": false
```

## HTML

![HTML](/images/HTML.png)

## CSS

![CSS](/images/CSS.png)

## JavaScript

![JavaScript](/images/JS.png)

![JavaScript](/images/JS-1.png)

## TypeScript

![TypeScript](/images/TS.png)

## C

![C](/images/C.png)

## C++

![C++](/images/C++.png)

## Clojure

![Clojure](/images/CLOJURE.png)

## C#

![C#](/images/CS.png)

## Dart

![Dart](/images/DART.png)

## Go

![Go](/images/GO.png)

## Java

![Java](/images/JAVA.png)

## Markdown ;)

![Markdown](/images/MARKDOWN.png)

## PHP

![PHP](/images/PHP.png)

## Python

![Python](/images/PYTHON.png)

## Ruby

![Ruby](/images/RUBY.png)

## Rust

![Rust](/images/RUST.png)

## Swift

![Swift](/images/SWIFT.png)

## YAML

![YAML](/images/YAML.png)

## "fontStyle": "_italic_"

If you want **all** your code to be **_italicized_**, like on my screenshots, add these settings to your **_settings.json_** file.

```json
"editor.tokenColorCustomizations": {
  "[Deep Dark Space]": {
    "textMateRules": [
      {
        "scope": [
          "source",
          "text.html",
          "entity.other.attribute-name.class.css",
          "entity.other.attribute-name.id.css"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  }
}
```

If you want to italicize **only** **_strings_**, **_keywords_**, **_functions_**, **_variables_**, **_numbers_** or **_types_**, add these settings to your **_settings.json_** file.

For example, let's italicize **only** the **_keywords_**:

```json
"editor.tokenColorCustomizations": {
  "[Deep Dark Space]": {
    "keywords": {
        "fontStyle": "italic"
      }
  }
}
```

But not all fonts look good in italic style. I prefer to use **_JetBrains Mono_** or **_Fira Code_**.

## License

[MIT License](./LICENSE)

### **_I hope you enjoyed my theme._**
