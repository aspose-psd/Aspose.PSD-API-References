---
title: "IText"
second_title: "Java용 Aspose.PSD API 참조"
description: "텍스트 레이어용 텍스트 편집 인터페이스"
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

텍스트 레이어용 텍스트 편집 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | 텍스트 부분을 끝에 추가합니다 |
| [getItems()](#getItems--) | 항목을 가져옵니다. |
| [getText()](#getText--) | 텍스트를 가져옵니다. |
| [getTextOrientation()](#getTextOrientation--) | 텍스트 방향을 가져오거나 설정합니다. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | 지정된 위치에 [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) 을 삽입합니다 |
| [producePortion()](#producePortion--) | 기본 매개변수로 새로운 부분을 생성합니다 |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 입력 또는 기본 매개변수를 사용하여 새로운 부분을 생성합니다. |
| [removePortion(int index)](#removePortion-int-) | 지정된 인덱스의 부분을 제거합니다. |
| [setTextOrientation(int value)](#setTextOrientation-int-) | 텍스트 방향을 가져오거나 설정합니다. |
| [updateLayerData()](#updateLayerData--) | 레이어 데이터를 업데이트합니다. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


텍스트 부분을 끝에 추가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | 해당 부분. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


항목을 가져옵니다.

값: 항목들.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


텍스트를 가져옵니다.

값: 텍스트.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


텍스트 방향을 가져오거나 설정합니다.

값: 텍스트 방향.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


지정된 위치에 [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) 을 삽입합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | 해당 부분. |
| 인덱스 | int | 해당 인덱스. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


기본 매개변수로 새로운 부분을 생성합니다

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


입력 또는 기본 매개변수를 사용하여 새로운 부분을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | 새로운 ITextPortion을 만들기 위한 텍스트 부분들. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | null이 아닌 경우 새   에 적용될 스타일이며, 그렇지 않으면 기본값이 됩니다. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | null이 아닌 경우 새   에 적용될 단락이며, 그렇지 않으면 기본값이 됩니다. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - 입력 매개변수를 기반으로 새로운 ITextPortion 부분을 반환합니다.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


지정된 인덱스의 부분을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 해당 인덱스. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


텍스트 방향을 가져오거나 설정합니다.

값: 텍스트 방향.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


레이어 데이터를 업데이트합니다.

