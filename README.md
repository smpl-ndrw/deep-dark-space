<div align="center">
	<img src="astronaut-icon.gif" width="200"/>
</div>

<h1 align="center">DEEP DARK SPACE</h1>

<h1 align="center">BLACK MOON MODE ADDED</h1>

## Recommended Settings

```json
"editor.guides.bracketPairs": "active",
"editor.bracketPairColorization.enabled": false
```

<h1 align="center">HTML / CSS</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/HTML_CSS.png" target="_blank"><img src="/images/Classic/HTML_CSS.png" width="340" /></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/HTML_CSS.png" target="_blank"><img src="/images/BlackMoon/HTML_CSS.png" width="340" /></a>

<h1 align="center">JavaScript / TypeScript</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/JS_TS.png" target="_blank"><img src="/images/Classic/JS_TS.png" width="340" /></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/JS_TS.png" target="_blank"><img src="/images/BlackMoon/JS_TS.png" width="340" /></a>

<h1 align="center">C / C++</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/C_CPP.png" target="_blank"><img src="/images/Classic/C_CPP.png" width="340"/></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/C_CPP.png" target="_blank"><img src="/images/BlackMoon/C_CPP.png" width="340"/></a>

<h1 align="center">Clojure / C#</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/CLOJURE_CS.png" target="_blank"><img src="/images/Classic/CLOJURE_CS.png" width="340" /></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/CLOJURE_CS.png" target="_blank"><img src="/images/BlackMoon/CLOJURE_CS.png" width="340" /></a>

<h1 align="center">Dart / Go</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/DART_GO.png" target="_blank"><img src="/images/Classic/DART_GO.png" width="340" /></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/DART_GO.png" target="_blank"><img src="/images/BlackMoon/DART_GO.png" width="340" /></a>

<h1 align="center">Java / Swift</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/JAVA_SWIFT.png" target="_blank"><img src="/images/Classic/JAVA_SWIFT.png" width="340" /></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/JAVA_SWIFT.png" target="_blank"><img src="/images/BlackMoon/JAVA_SWIFT.png" width="340" /></a>

<h1 align="center">PHP / Python</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/PHP_PYTHON.png" target="_blank"><img src="/images/Classic/PHP_PYTHON.png" width="340" /></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/PHP_PYTHON.png" target="_blank"><img src="/images/BlackMoon/PHP_PYTHON.png" width="340" /></a>

<h1 align="center">Ruby / Rust</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/RUBY_RUST.png" target="_blank"><img src="/images/Classic/RUBY_RUST.png" width="340" /></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/RUBY_RUST.png" target="_blank"><img src="/images/BlackMoon/RUBY_RUST.png" width="340" /></a>

<h1 align="center">Markdown / JSON</h1>

<a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/Classic/MARKDOWN_JSON.png" target="_blank"><img src="/images/Classic/MARKDOWN_JSON.png" width="340" /></a> <a href="https://github.com/smpl-ndrw/deep-dark-space/blob/main/images/BlackMoon/MARKDOWN_JSON.png" target="_blank"><img src="/images/BlackMoon/MARKDOWN_JSON.png" width="340" /></a>

## "fontStyle": "_italic_"

1. If you want **all** your code to be **_italicized_**, like on my screenshots, add these settings to your **_settings.json_** file.

```json
"editor.tokenColorCustomizations": {
  "[Deep Dark Space], [Deep Dark Space - Black Moon]": {
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
  "[Deep Dark Space], [Deep Dark Space - Black Moon]": {
    "keywords": {
      "fontStyle": "italic"
    }
  }
}
```

3. If you want to italicize **only** the **words** - **_true, false, undefined_** or **_null_**, add these settings to your **_settings.json_** file.

```json
"editor.tokenColorCustomizations": {
  "[Deep Dark Space], [Deep Dark Space - Black Moon]": {
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
  "[Deep Dark Space], [Deep Dark Space - Black Moon]": {
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

After many updates to the theme, the list of words that are italicized by default has grown a lot. To find out the word's token, use the [SCOPE INSPECTOR](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide#scope-inspector) tool that is built into VS Code.

4. If you want to italicize **only** the **_class_** or **_parameter_**, add these settings to your **_settings.json_** file.

For example, let's italicize **only** the **_parameter_**:

```json
"editor.semanticTokenColorCustomizations": {
  "[Deep Dark Space], [Deep Dark Space - Black Moon]": {
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
