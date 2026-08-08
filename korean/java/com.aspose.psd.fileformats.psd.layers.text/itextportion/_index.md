---
title: "ITextPortion"
second_title: "Java용 Aspose.PSD API 참조"
description: "텍스트 부분을 조작하는 인터페이스"
type: docs
weight: 13
url: /ko/java/com.aspose.psd.fileformats.psd.layers.text/itextportion/
---
```
public interface ITextPortion
```

텍스트 부분을 조작하는 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParagraph()](#getParagraph--) | 스타일을 설정합니다. |
| [getStyle()](#getStyle--) | 스타일을 가져옵니다. |
| [getText()](#getText--) | 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 텍스트를 가져오거나 설정합니다. |
### getParagraph() {#getParagraph--}
```
public abstract ITextParagraph getParagraph()
```


스타일을 설정합니다.

값: 단락.

**Returns:**
[ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph)
### getStyle() {#getStyle--}
```
public abstract ITextStyle getStyle()
```


스타일을 가져옵니다.

값: 스타일.

**Returns:**
[ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle)
### getText() {#getText--}
```
public abstract String getText()
```


텍스트를 가져오거나 설정합니다.

값: 텍스트.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


텍스트를 가져오거나 설정합니다.

값: 텍스트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

