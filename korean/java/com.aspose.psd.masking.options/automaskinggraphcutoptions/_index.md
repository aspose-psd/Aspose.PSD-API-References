---
title: "AutoMaskingGraphCutOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "GraphCut 자동 마스킹 옵션."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

GraphCut 자동 마스킹 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | 새 인스턴스를 초기화합니다 [AutoMaskingGraphCutOptions] 클래스. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | 배경 객체 번호 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | 자동 마스킹 인수를 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | 기본 스트로크를 채웁니다. |
| [getArgs()](#getArgs--) | 분할 알고리즘에 대한 인수를 가져옵니다. |
| [getAssumedObjects()](#getAssumedObjects--) | 가정된 객체를 가져옵니다. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | 배경 교체 색상을 가져옵니다. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | 기본 스트로크를 계산해야 하는지 여부를 나타내는 값을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | 결합된 객체 사각형을 가져옵니다. |
| [getDecompose()](#getDecompose--) | 각 Shape를 마스크에서 개별 객체로 분리할지, 배경과 분리된 마스크의 통합 객체로 할지 여부를 나타내는 값을 가져옵니다. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | 기본 배경 스트로크를 가져옵니다. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | 미리 계산된 기본 전경 스트로크를 가져옵니다. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | 기본 객체 사각형들을 가져옵니다. |
| [getExportOptions()](#getExportOptions--) | 이미지 내보내기 옵션을 가져옵니다. |
| [getFeatheringRadius()](#getFeatheringRadius--) | 페더링 반경을 가져옵니다. |
| [getMaskingArea()](#getMaskingArea--) | 마스킹 영역을 가져옵니다. |
| [getMethod()](#getMethod--) | 분할 방법을 가져옵니다. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | 기본 포인트 사전 계산 프로세스 진행 이벤트 핸들러를 가져옵니다. |
| [hasHumans_internalized()](#hasHumans-internalized--) | 가정된 객체 컬렉션에 인간 객체가 포함되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | 분할 알고리즘의 인수를 설정합니다. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | 가정된 객체를 설정합니다. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | 배경 교체 색상을 설정합니다. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | 기본 스트로크를 계산해야 하는지 여부를 나타내는 값을 설정합니다. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | 결합된 객체 사각형. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | 각 Shape을 마스크에서 개별 객체로 분리할 필요가 있는지, 아니면 배경과 분리된 마스크에서 통합 객체로 할지 여부를 나타내는 값을 설정합니다. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | 기본 배경 스트로크. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | 미리 계산된 기본 전경 스트로크. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | 기본 객체 사각형들. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | 이미지 내보내기 옵션을 설정합니다. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | 페더링 반경을 설정합니다. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | 가정된 객체 컬렉션에 인간 객체가 포함되어 있는지 여부를 나타내는 값. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | 마스킹 영역을 설정합니다. |
| [setMethod(int value)](#setMethod-int-) | 분할 방법을 설정합니다. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 기본 포인트 사전 계산 프로세스 진행 이벤트 핸들러를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


새 인스턴스를 초기화합니다 [AutoMaskingGraphCutOptions] 클래스.

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


배경 객체 번호

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


자동 마스킹 인수를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 이미지입니다. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


기본 스트로크를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 이미지입니다. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


분할 알고리즘에 대한 인수를 가져옵니다.

값: 분할 알고리즘의 인수.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


가정된 객체를 가져옵니다.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - 가정된 객체.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


배경 교체 색상을 가져옵니다.

값: 배경 교체 색상. 이 색상은 결과 이미지의 배경 색상으로 사용됩니다.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


기본 스트로크를 계산해야 하는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 기본 스트로크를 계산해야 하는지 여부를 나타내는 값.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


결합된 객체 사각형을 가져옵니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


각 Shape를 마스크에서 개별 객체로 분리할지, 배경과 분리된 마스크의 통합 객체로 할지 여부를 나타내는 값을 가져옵니다.

값: 분해하면 true, 그렇지 않으면 false.

**Returns:**
boolean - 각 Shape을 마스크에서 개별 객체로 분리할 필요가 있는지, 아니면 배경과 분리된 마스크에서 통합 객체로 할지 여부를 나타내는 값.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


기본 배경 스트로크를 가져옵니다.

**Returns:**
com.aspose.psd.Point[] - 기본 배경 스트로크.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


미리 계산된 기본 전경 스트로크를 가져옵니다.

**Returns:**
com.aspose.psd.Point[] - 사전 계산된 기본 전경 스트로크.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


기본 객체 사각형들을 가져옵니다.

**Returns:**
com.aspose.psd.Rectangle[] - 기본 객체 사각형.
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
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


기본 포인트 사전 계산 프로세스 진행 이벤트 핸들러를 가져옵니다.

값: 진행 이벤트 핸들러.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


가정된 객체 컬렉션에 인간 객체가 포함되어 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 가정된 객체 컬렉션에 인간 객체가 포함되어 있는지를 나타내는 값.
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

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


가정된 객체를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | 가정된 객체. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

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

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


기본 스트로크를 계산해야 하는지 여부를 나타내는 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 기본 스트로크를 계산해야 하는지를 나타내는 값. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


결합된 객체 사각형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | 결합된 객체 사각형. |

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

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


기본 배경 스트로크.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 기본 배경 스트로크. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


미리 계산된 기본 전경 스트로크.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 사전 계산된 기본 전경 스트로크. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


기본 객체 사각형들.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 기본 객체 사각형. |

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

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


가정된 객체 컬렉션에 인간 객체가 포함되어 있는지 여부를 나타내는 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 가정된 객체 컬렉션에 인간 객체가 포함되어 있는지를 나타내는 값. |

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

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


기본 포인트 사전 계산 프로세스 진행 이벤트 핸들러를 설정합니다.

값: 진행 이벤트 핸들러.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | 기본 포인트 사전 계산 프로세스 진행 이벤트 핸들러. |

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

