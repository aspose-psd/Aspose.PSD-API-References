---
title: "AiLayerSection"
second_title: "Java용 Aspose.PSD API 참조"
description: "Ai 형식 레이어 섹션"
type: docs
weight: 15
url: /ko/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Ai 형식 레이어 섹션
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | 래스터 이미지를 추가합니다. |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | 파란색 구성 요소를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | 색상의 인덱스를 가져오거나 설정합니다. |
| [getColorNumber()](#getColorNumber--) | 색상 번호를 가져오거나 설정합니다. |
| [getData()](#getData--) | 문자열 데이터를 가져옵니다. |
| [getDimValue()](#getDimValue--) | 퍼센트로 표시된 어두워짐 값을 가져오거나 설정합니다. |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getGreen()](#getGreen--) | 녹색 구성 요소를 가져오거나 설정합니다. |
| [getName()](#getName--) | 레이어 이름을 가져오거나 설정합니다. |
| [getRasterImages()](#getRasterImages--) | 래스터 이미지를 가져옵니다. |
| [getRed()](#getRed--) | 빨간색 구성 요소를 가져오거나 설정합니다. |
| [getStream_internalized()](#getStream-internalized--) | 내부 스트림을 가져옵니다. |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | 이 인스턴스에 다중 레이어 마스크가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | 이 레이어가 어두워졌는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isLocked()](#isLocked--) | 이 레이어가 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isPreview()](#isPreview--) | 이 레이어가 미리 보기인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isPrinted()](#isPrinted--) | 이 레이어가 인쇄되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isShown()](#isShown--) | 이 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isTemplate()](#isTemplate--) | 이 레이어가 템플릿 레이어인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | 파란색 구성 요소를 가져오거나 설정합니다. |
| [setColorIndex(int value)](#setColorIndex-int-) | 색상의 인덱스를 가져오거나 설정합니다. |
| [setColorNumber(int value)](#setColorNumber-int-) | 색상 번호를 가져오거나 설정합니다. |
| [setDimValue(int value)](#setDimValue-int-) | 퍼센트로 표시된 어두워짐 값을 가져오거나 설정합니다. |
| [setGreen(int value)](#setGreen-int-) | 녹색 구성 요소를 가져오거나 설정합니다. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | 이 레이어가 어두워졌는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setLocked(boolean value)](#setLocked-boolean-) | 이 레이어가 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | 이 인스턴스에 다중 레이어 마스크가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 레이어 이름을 가져오거나 설정합니다. |
| [setPreview(boolean value)](#setPreview-boolean-) | 이 레이어가 미리 보기인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | 이 레이어가 인쇄되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setRed(int value)](#setRed-int-) | 빨간색 구성 요소를 가져오거나 설정합니다. |
| [setShown(boolean value)](#setShown-boolean-) | 이 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | 이 레이어가 템플릿 레이어인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


래스터 이미지를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | 래스터 이미지입니다. |

### close() {#close--}
```
public void close()
```


Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 문에서 사용할 수 있습니다. 이 메서드는 단순히 dispose 메서드를 호출합니다.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| properties | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlue() {#getBlue--}
```
public final int getBlue()
```


파란색 구성 요소를 가져오거나 설정합니다.

값: 파란색 구성 요소.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


색상의 인덱스를 가져오거나 설정합니다. 이 인수는 \\u20131와 26 사이의 값을 가질 수 있습니다. 각 정수는 레이어에 사용자 식별을 위해 할당될 수 있는 색상을 나타냅니다.

값: 색상의 인덱스.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


색상 번호를 가져오거나 설정합니다. -1은 빨강, 초록, 파랑 속성에서 가져온 사용자 정의 색상 값입니다. 레이어\\u2019의 색상 설정을 지정합니다.

값: 색상 번호.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


문자열 데이터를 가져옵니다.

**Returns:**
java.lang.String - 섹션의 문자열 데이터
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


디밍 값을 백분율로 가져오거나 설정합니다. 레이어에 포함된 연결 이미지 및 비트맵 이미지의 강도를 지정된 백분율로 감소시킵니다.

값: 백분율로 표시된 디밍 값.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getGreen() {#getGreen--}
```
public final int getGreen()
```


녹색 구성 요소를 가져오거나 설정합니다.

값: 녹색 색상 구성 요소.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


레이어 이름을 가져오거나 설정합니다. 레이어 패널에 표시되는 항목의 이름을 지정합니다.

값: 레이어 이름.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


래스터 이미지를 가져옵니다.

값: 래스터 이미지.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


빨간색 구성 요소를 가져오거나 설정합니다.

값: 빨간색 색상 구성 요소.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


내부 스트림을 가져옵니다.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


이 인스턴스에 다중 레이어 마스크가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스에 다중 레이어 마스크가 있으면 true; 그렇지 않으면 false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


이 레이어가 디밍되었는지 여부를 나타내는 값을 가져오거나 설정합니다. 레이어에 포함된 연결 이미지 및 비트맵 이미지의 강도를 감소시킵니다.

값:  true  이 레이어가 디밍된 경우 true; 그렇지 않으면 false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


이 레이어가 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. 항목에 대한 변경을 방지합니다.

값:  true  이 레이어가 잠겨 있는 경우 true; 그렇지 않으면 false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


이 레이어가 미리보기인지 여부를 나타내는 값을 가져오거나 설정합니다. 레이어에 포함된 아트워크를 윤곽선 대신 색상으로 표시합니다.

값:  true  이 레이어가 미리보기인 경우 true; 그렇지 않으면 false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


이 레이어가 인쇄되는지 여부를 나타내는 값을 가져오거나 설정합니다. true인 경우 레이어에 포함된 아트워크를 인쇄 가능하게 합니다.

값:  true  이 레이어가 인쇄된 경우 true; 그렇지 않으면 false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


이 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. true인 경우 레이어에 포함된 모든 아트워크를 아트보드에 표시합니다.

값:  true  이 레이어가 표시된 경우 true; 그렇지 않으면 false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


이 레이어가 템플릿 레이어인지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 레이어가 템플릿인 경우 true; 그렇지 않으면 false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


파란색 구성 요소를 가져오거나 설정합니다.

값: 파란색 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


색상의 인덱스를 가져오거나 설정합니다. 이 인수는 \\u20131와 26 사이의 값을 가질 수 있습니다. 각 정수는 레이어에 사용자 식별을 위해 할당될 수 있는 색상을 나타냅니다.

값: 색상의 인덱스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


색상 번호를 가져오거나 설정합니다. -1은 빨강, 초록, 파랑 속성에서 가져온 사용자 정의 색상 값입니다. 레이어\\u2019의 색상 설정을 지정합니다.

값: 색상 번호.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


디밍 값을 백분율로 가져오거나 설정합니다. 레이어에 포함된 연결 이미지 및 비트맵 이미지의 강도를 지정된 백분율로 감소시킵니다.

값: 백분율로 표시된 디밍 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


녹색 구성 요소를 가져오거나 설정합니다.

값: 녹색 색상 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


이 레이어가 디밍되었는지 여부를 나타내는 값을 가져오거나 설정합니다. 레이어에 포함된 연결 이미지 및 비트맵 이미지의 강도를 감소시킵니다.

값:  true  이 레이어가 디밍된 경우 true; 그렇지 않으면 false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


이 레이어가 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. 항목에 대한 변경을 방지합니다.

값:  true  이 레이어가 잠겨 있는 경우 true; 그렇지 않으면 false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


이 인스턴스에 다중 레이어 마스크가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스에 다중 레이어 마스크가 있으면 true; 그렇지 않으면 false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


레이어 이름을 가져오거나 설정합니다. 레이어 패널에 표시되는 항목의 이름을 지정합니다.

값: 레이어 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


이 레이어가 미리보기인지 여부를 나타내는 값을 가져오거나 설정합니다. 레이어에 포함된 아트워크를 윤곽선 대신 색상으로 표시합니다.

값:  true  이 레이어가 미리보기인 경우 true; 그렇지 않으면 false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


이 레이어가 인쇄되는지 여부를 나타내는 값을 가져오거나 설정합니다. true인 경우 레이어에 포함된 아트워크를 인쇄 가능하게 합니다.

값:  true  이 레이어가 인쇄된 경우 true; 그렇지 않으면 false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


빨간색 구성 요소를 가져오거나 설정합니다.

값: 빨간색 색상 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


이 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. true인 경우 레이어에 포함된 모든 아트워크를 아트보드에 표시합니다.

값:  true  이 레이어가 표시된 경우 true; 그렇지 않으면 false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


이 레이어가 템플릿 레이어인지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 레이어가 템플릿인 경우 true; 그렇지 않으면 false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

