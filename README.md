<img src="astronaut-icon.gif" width="200" align="center"/>

<br/>

<h1 align="center">Deep Dark Space</h1>

## Recommended Settings

```json
"editor.guides.bracketPairs": "active",
"editor.bracketPairColorization.enabled": false
```

## HTML / CSS

![HTML_CSS](/images/HTML_CSS.png)

## JavaScript / TypeScript

![JavaScript_TypeScript](/images/JS_TS.png)

## C / C++

![C_C++](/images/C_C++.png)

## Clojure / C#

![Clojure_C#](/images/CLOJURE_CS.png)

## Dart / Go

![Dart_Go](/images/DART_GO.png)

## Java / Swift

![Java_Swift](/images/JAVA_SWIFT.png)

## PHP / Python

![PHP_Python](/images/PHP_PYTHON.png)

## Ruby / Rust

![Ruby_Rust](/images/RUBY_RUST.png)

## Markdown / JSON

![Markdown_JSON](/images/MARKDOWN_JSON.png)

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

3. If you want to italicize **only** the **words** - **_true, false, undefined_** or **_null_**, add these settings to your **_settings.json_** file.

```json
"editor.tokenColorCustomizations": {
  "[Deep Dark Space]": {
    "textMateRules": [
      {
        "scope": [
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

**Words** **_function, interface, class, type_**, and **_let, const_** are italicized by default. If you want to make them in normal font style, add these settings to your **_settings.json_** file.

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

          "storage.type", // let, const + function, interface, class, type
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

A more complete [LIST](https://code.visualstudio.com/api/language-extensions/semantic-highlight-guide#semantic-token-classification) of tokens that can be italicized.

But not all fonts look good in italic style. I prefer to use **_JetBrains Mono_** or **_Fira Code_**.

## License

[MIT License](./LICENSE)

<h3 align="center"><strong><em>I hope you enjoyed my theme.</em></strong></h3>
