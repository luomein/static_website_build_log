---
draft: false
date: 2024-05-30
categories:
  - markdown
  - html
  - multi-language

---

# furigana, <ruby>振<rt>ふ</rt>り<rt></rt>仮名<rt>がな</rt></ruby>

This is standard HTML5 tag.

```
<ruby>振<rt>ふ</rt>り<rt></rt>仮名<rt>がな</rt></ruby>
```

<!-- more -->

The `<ruby>` tag in HTML has nothing to do with the Ruby programming language. They are completely unrelated. 

The name of `<ruby>` tag comes from ruby character.

> [Ruby characters are small, annotative glosses that are usually placed above or to the right of logographic characters of languages in the East Asian cultural sphere, such as Chinese hanzi, Japanese kanji, and Korean hanja, to show the logographs' pronunciation](https://en.wikipedia.org/wiki/Ruby_character)

## `<ruby>` Element and Its Sub-tags


* `<ruby>`: The container element for ruby annotations.

* `<rb>`: Stands for "ruby base" and is used to specify the base text that the annotations apply to. This is the main text (e.g., kanji). This is optional but useful if the base text and annotations are complex or need clear demarcation.

* `<rt>`: Stands for "ruby text" and is used to specify the annotation text (e.g., furigana or phonetic guide).

* `<rp>`: Stands for "ruby parentheses" and is used to provide fallback parentheses for browsers that do not support ruby annotations. This is optional and mainly for accessibility.

## Practical Use Cases

### Full Word Annotation

 <ruby>振り仮名<rt>ふりがな</rt></ruby>

```
  <ruby>振り仮名<rt>ふりがな</rt></ruby>

```

### Individual Character Annotation

 <ruby>
    振<rt>ふ</rt>り<rt></rt>仮<rt>が</rt>名<rt>な</rt>
</ruby>


```

  <ruby>
    振<rt>ふ</rt>り<rt></rt>仮<rt>が</rt>名<rt>な</rt>
  </ruby>

```
