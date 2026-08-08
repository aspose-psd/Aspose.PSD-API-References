---
title: "WarpSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "워프가 적용된 레이어 매개변수"
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

워프가 적용된 레이어 매개변수
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | 새로운 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) 클래스 인스턴스를 초기화합니다. |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 새로운 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) 클래스 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | ProcessingArea의 기본값 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | warp 이미지의 경계를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Photoshop 메시 포인트 |
| [getProcessingArea()](#getProcessingArea--) | processing area size의 값을 가져오거나 설정합니다. |
| [getRotate()](#getRotate--) | rotate 값을 가져오거나 설정합니다. |
| [getStyle()](#getStyle--) | warp 스타일을 가져오거나 설정합니다. |
| [getValue()](#getValue--) | warp 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | MeshPoints의 사용자 변경을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | warp 이미지의 경계를 가져오거나 설정합니다. |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Photoshop 메시 포인트 |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 리소스 벡터에서 mesh 포인트를 반환합니다. |
| [setProcessingArea(int value)](#setProcessingArea-int-) | processing area size의 값을 가져오거나 설정합니다. |
| [setRotate(int value)](#setRotate-int-) | rotate 값을 가져오거나 설정합니다. |
| [setStyle(int value)](#setStyle-int-) | warp 스타일을 가져오거나 설정합니다. |
| [setValue(double value)](#setValue-double-) | warp 값을 가져오거나 설정합니다. |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 이 warp 매개변수를 PlacedResource에 저장합니다. |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 이 warp 매개변수를 PlacedResource에 저장합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


새로운 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | warp 설정이 있는 PS 항목 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | warp 이미지의 경계 |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


새로운 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | warp 설정이 있는 리소스 |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
```


ProcessingArea의 기본값

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


warp 이미지의 경계를 가져오거나 설정합니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMeshPoints() {#getMeshPoints--}
```
public final Point[] getMeshPoints()
```


Photoshop 메시 포인트

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


processing area size의 값을 가져오거나 설정합니다. 기본값은 10이며, 범위는 [2;40]입니다.

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


rotate 값을 가져오거나 설정합니다.

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


warp 스타일을 가져오거나 설정합니다.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


warp 값을 가져오거나 설정합니다.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultMeshPoints_internalized() {#isDefaultMeshPoints-internalized--}
```
public final boolean isDefaultMeshPoints_internalized()
```


MeshPoints의 사용자 변경을 가져오거나 설정합니다.

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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


warp 이미지의 경계를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Photoshop 메시 포인트

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


리소스 벡터에서 mesh 포인트를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | warp 설정이 있는 리소스 |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


processing area size의 값을 가져오거나 설정합니다. 기본값은 10이며, 범위는 [2;40]입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


rotate 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


warp 스타일을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


warp 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


이 warp 매개변수를 PlacedResource에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | warp 설정이 있는 리소스 |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - 이 WarpParams에서 가져온 warp 매개변수 리소스
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


이 warp 매개변수를 PlacedResource에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | warp 설정이 있는 리소스 |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - Resource with warp params from this WarpParams
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

