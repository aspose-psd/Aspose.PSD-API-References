---
title: "MultiPageOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "다중 페이지를 지원하는 형식의 기본 클래스."
type: docs
weight: 17
url: /ko/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

다중 페이지를 지원하는 형식의 기본 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | MultiPageOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | 내보내기 영역을 가져오거나 설정합니다. |
| [getMergeLayers()](#getMergeLayers--) | [merege layers] 여부를 나타내는 값을 가져옵니다. |
| [getMode()](#getMode--) | 모드를 가져오거나 설정합니다. |
| [getOutputLayersNames()](#getOutputLayersNames--) | 출력 레이어 이름을 가져오거나 설정합니다(내보내기 형식이 레이어 명명을 지원하는 경우에 작동합니다, 예: Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | 페이지 래스터화 옵션을 가져옵니다. |
| [getPageTitles()](#getPageTitles--) | 페이지 제목을 가져오거나 설정합니다. |
| [getPages()](#getPages--) | 페이지를 가져오거나 설정합니다. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | 시간 간격을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | 범위 배열에서 페이지를 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | 내보내기 영역을 가져오거나 설정합니다. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | [merege layers] 여부를 나타내는 값을 설정합니다. |
| [setMode(int value)](#setMode-int-) | 모드를 가져오거나 설정합니다. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | 출력 레이어 이름을 가져오거나 설정합니다(내보내기 형식이 레이어 명명을 지원하는 경우에 작동합니다, 예: Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | 페이지 래스터화 옵션을 설정합니다. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | 페이지 제목을 가져오거나 설정합니다. |
| [setPages(int[] value)](#setPages-int---) | 페이지를 가져오거나 설정합니다. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | 시간 간격을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 페이지 | int[] | 페이지들. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 페이지 | int[] | 페이지 배열. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 내보내기 영역. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pageTitles | java.lang.String[] | 페이지 제목들. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pageTitles | java.lang.String[] | 페이지 제목들. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 내보내기 영역. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | IntRange. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | IntRange. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 내보내기 영역. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | IntRange. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | IntRange. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 내보내기 영역. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 페이지 | int | 페이지 인덱스. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


MultiPageOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 페이지 | int | 페이지 인덱스. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | 내보내기 영역. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


내보내기 영역을 가져오거나 설정합니다.

값: 내보내기 영역.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


[merege layers] 여부를 나타내는 값을 가져옵니다.

값: true이면 [merege layers]; 그렇지 않으면 false.

**Returns:**
boolean - [merege layers] 여부를 나타내는 값.
### getMode() {#getMode--}
```
public int getMode()
```


모드를 가져오거나 설정합니다.

값: 모드.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


출력 레이어 이름을 가져오거나 설정합니다(내보내기 형식이 레이어 명명을 지원하는 경우에 작동합니다, 예: Psd)

값: 출력 레이어 이름들.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


페이지 래스터화 옵션을 가져옵니다.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - 페이지 래스터화 옵션.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


페이지 제목을 가져오거나 설정합니다.

값: 페이지 제목들.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


페이지를 가져오거나 설정합니다.

값: 페이지들.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


시간 간격을 가져옵니다.

값: 시간 간격.

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


범위 배열에서 페이지를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | 범위들. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


내보내기 영역을 가져오거나 설정합니다.

값: 내보내기 영역.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


[merege layers] 여부를 나타내는 값을 설정합니다.

값: true이면 [merege layers]; 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | [merege layers] 여부를 나타내는 값. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


모드를 가져오거나 설정합니다.

값: 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


출력 레이어 이름을 가져오거나 설정합니다(내보내기 형식이 레이어 명명을 지원하는 경우에 작동합니다, 예: Psd)

값: 출력 레이어 이름들.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


페이지 래스터화 옵션을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | 페이지 래스터화 옵션. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


페이지 제목을 가져오거나 설정합니다.

값: 페이지 제목들.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


페이지를 가져오거나 설정합니다.

값: 페이지들.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


시간 간격을 설정합니다.

값: 시간 간격.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | 시간 간격. |

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

