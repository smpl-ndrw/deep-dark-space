<div align="center">
# Deep Dark Space
</div>

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

## Markdown

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

## JSON

![JSON](/images/JSON.png)

## "fontStyle": "_italic_"

1. If you want **all** your code to be **_italicized_**, like on my screenshots, add these settings to your **_settings.json_** file.

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

2. If you want to italicize **only** the **_strings, keywords, functions, variables, numbers_** or **_types_**, add these settings to your **_settings.json_** file.

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

3. If you want to italicize **only** the **words** - **_let, const, true, false, undefined_** or **_null_**, add these settings to your **_settings.json_** file.

```json
"editor.tokenColorCustomizations": {
  "[Deep Dark Space]": {
    "textMateRules": [
      {
        "scope": [
          "storage.type", // let, const + function, interface, class, type

          "constant.language.boolean", // true, false
          "constant.language.undefined",
          "constant.language.null",
          "constant.language" // true, false, undefined, null
        ],
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  }
}
```

**Words** **_function, interface, class_**, and **_type_** are italicized by default. If you want to make them in normal font, add these settings to your **_settings.json_** file.

```json
"editor.tokenColorCustomizations": {
  "[Deep Dark Space]": {
    "textMateRules": [
      {
        "scope": [
          "storage.type.function",
          "storage.type.interface",
          "storage.type.class",
          "storage.type.type"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  }
}
```

4. If you want to italicize **only** the **_class_** or **_parameter_**, add these settings to your **_settings.json_** file.

For example, let's italicize **only** the **_parameter_**:

```json
"editor.semanticTokenColorCustomizations": {
  "[Deep Dark Space]": {
    "enabled": true,
    "rules": {
      "parameter": {
        "fontStyle": "italic"
      }
    }
  }
},
```

A more complete [list](https://code.visualstudio.com/api/language-extensions/semantic-highlight-guide#semantic-token-classification) of tokens that can be italicized.

But not all fonts look good in italic style. I prefer to use **_JetBrains Mono_** or **_Fira Code_**.

## License

[MIT License](./LICENSE)

### **_I hope you enjoyed my theme._**
