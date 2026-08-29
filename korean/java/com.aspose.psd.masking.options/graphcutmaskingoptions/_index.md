---
title: "GraphCutMaskingOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "GraphCut 자동 마스킹 옵션."
type: docs
weight: 14
url: /ko/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

GraphCut 자동 마스킹 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | 배경 객체 번호 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | 분할 알고리즘에 대한 인수를 가져옵니다. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | 배경 교체 색상을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | 각 Shape를 마스크에서 개별 객체로 분리할지, 배경과 분리된 마스크의 통합 객체로 할지 여부를 나타내는 값을 가져옵니다. |
| [getExportOptions()](#getExportOptions--) | 이미지 내보내기 옵션을 가져옵니다. |
| [getFeatheringRadius()](#getFeatheringRadius--) | 페더링 반경을 가져옵니다. |
| [getMaskingArea()](#getMaskingArea--) | 마스킹 영역을 가져옵니다. |
| [getMethod()](#getMethod--) | 분할 방법을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | 분할 알고리즘의 인수를 설정합니다. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | 배경 교체 색상을 설정합니다. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | 각 Shape을 마스크에서 개별 객체로 분리할 필요가 있는지, 아니면 배경과 분리된 마스크에서 통합 객체로 할지 여부를 나타내는 값을 설정합니다. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | 이미지 내보내기 옵션을 설정합니다. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | 페더링 반경을 설정합니다. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | 마스킹 영역을 설정합니다. |
| [setMethod(int value)](#setMethod-int-) | 분할 방법을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


배경 객체 번호

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


분할 알고리즘에 대한 인수를 가져옵니다.

값: 분할 알고리즘의 인수.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


배경 교체 색상을 가져옵니다.

값: 배경 교체 색상. 이 색상은 결과 이미지의 배경 색상으로 사용됩니다.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


각 Shape를 마스크에서 개별 객체로 분리할지, 배경과 분리된 마스크의 통합 객체로 할지 여부를 나타내는 값을 가져옵니다.

값: 분해하면 true, 그렇지 않으면 false.

**Returns:**
boolean - 각 Shape을 마스크에서 개별 객체로 분리할 필요가 있는지, 아니면 배경과 분리된 마스크에서 통합 객체로 할지 여부를 나타내는 값.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


이미지 내보내기 옵션을 가져옵니다.

값: 결과 이미지를 생성하는 데 사용될 이미지 내보내기 옵션.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


페더링 반경을 가져옵니다.

**Returns:**
int - 페더링 반경.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


마스킹 영역을 가져옵니다.

값: 소스 이미지의 일부 영역인 마스킹 영역. Rectangle.Empty 값은 전체 소스 이미지 영역을 의미합니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


분할 방법을 가져옵니다.

값: 분할 방법.

**Returns:**
int - 분할 방법.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


분할 알고리즘의 인수를 설정합니다.

값: 분할 알고리즘의 인수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | 분할 알고리즘의 인수. |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


배경 교체 색상을 설정합니다.

값: 배경 교체 색상. 이 색상은 결과 이미지의 배경 색상으로 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 배경 교체 색상. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


각 Shape을 마스크에서 개별 객체로 분리할 필요가 있는지, 아니면 배경과 분리된 마스크에서 통합 객체로 할지 여부를 나타내는 값을 설정합니다.

값: 분해하면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 각 Shape을 마스크에서 개별 객체로 분리할 필요가 있는지, 아니면 배경과 분리된 마스크에서 통합 객체로 할지 여부를 나타내는 값. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


이미지 내보내기 옵션을 설정합니다.

값: 결과 이미지를 생성하는 데 사용될 이미지 내보내기 옵션.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 이미지 내보내기 옵션. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


페더링 반경을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 페더링 반경. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


마스킹 영역을 설정합니다.

값: 소스 이미지의 일부 영역인 마스킹 영역. Rectangle.Empty 값은 전체 소스 이미지 영역을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | 마스킹 영역. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


분할 방법을 설정합니다.

값: 분할 방법.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 분할 방법. |

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

