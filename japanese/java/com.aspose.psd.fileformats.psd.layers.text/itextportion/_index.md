---
title: "ITextPortion"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "テキスト部分を操作するインターフェイス"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.fileformats.psd.layers.text/itextportion/
---
```
public interface ITextPortion
```

テキスト部分を操作するインターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParagraph()](#getParagraph--) | スタイルを設定します。 |
| [getStyle()](#getStyle--) | スタイルを取得します。 |
| [getText()](#getText--) | テキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | テキストを取得または設定します。 |
### getParagraph() {#getParagraph--}
```
public abstract ITextParagraph getParagraph()
```


スタイルを設定します。

値: 段落。

**Returns:**
[ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph)
### getStyle() {#getStyle--}
```
public abstract ITextStyle getStyle()
```


スタイルを取得します。

値: スタイル。

**Returns:**
[ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle)
### getText() {#getText--}
```
public abstract String getText()
```


テキストを取得または設定します。

値: テキスト。

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


テキストを取得または設定します。

値: テキスト。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

