---
title: "ITextPortion"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "واجهة للتلاعب بأجزاء النص."
type: docs
weight: 13
url: /ar/java/com.aspose.psd.fileformats.psd.layers.text/itextportion/
---
```
public interface ITextPortion
```

واجهة للتلاعب بأجزاء النص.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getParagraph()](#getParagraph--) | يعيّن النمط. |
| [getStyle()](#getStyle--) | يحصل على النمط. |
| [getText()](#getText--) | يحصل أو يضبط النص. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يضبط النص. |
### getParagraph() {#getParagraph--}
```
public abstract ITextParagraph getParagraph()
```


يعيّن النمط.

القيمة: الفقرة.

**Returns:**
[ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph)
### getStyle() {#getStyle--}
```
public abstract ITextStyle getStyle()
```


يحصل على النمط.

القيمة: النمط.

**Returns:**
[ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle)
### getText() {#getText--}
```
public abstract String getText()
```


يحصل أو يضبط النص.

القيمة: النص.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


يحصل أو يضبط النص.

القيمة: النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

