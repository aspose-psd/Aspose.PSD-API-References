---
title: "IPlacedLayerResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "PSD 파일에서 배치된 레이어에 대한 정보를 포함하는 IPlacedLayerResource 인터페이스를 정의합니다."
type: docs
weight: 17
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

IPlacedLayerResource 인터페이스를 정의합니다. 이 인터페이스는 PSD 파일의 배치 레이어에 대한 정보를 포함합니다. Adobe\\ufffd Photoshop\\ufffd 이미지에서 PlLd, Sold 및 Sole 리소스를 지정하는 데 사용되는 마크업 인터페이스이며, Adobe\\ufffd Photoshop\\ufffd 이미지에서 스마트 객체 레이어를 지원하는 데 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | PSD 이미지에 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다. |
| [getBottom()](#getBottom--) | PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| [getBounds()](#getBounds--) | PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | 수평 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [getItems()](#getItems--) | 왜곡 항목을 가져오거나 설정합니다. |
| [getLeft()](#getLeft--) | PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| [getPageNumber()](#getPageNumber--) | PSD 파일에 배치된 레이어의 페이지 번호를 가져오거나 설정합니다. |
| [getPerspective()](#getPerspective--) | PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다. |
| [getPerspectiveOther()](#getPerspectiveOther--) | PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다. |
| [getPlacedLayerType()](#getPlacedLayerType--) | PSD 파일에 배치된 레이어의 유형을 가져오거나 설정합니다. |
| [getRight()](#getRight--) | PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다. |
| [getTop()](#getTop--) | PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| [getTotalPages()](#getTotalPages--) | PSD 파일에 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다. |
| [getTransformMatrix()](#getTransformMatrix--) | PSD 파일에 배치된 레이어의 변환 행렬을 가져오거나 설정합니다. |
| [getUOrder()](#getUOrder--) | PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| [getUniqueId()](#getUniqueId--) | PSD 이미지에서 스마트 객체 배치 레이어의 전역 고유 식별자를 가져오거나 설정합니다. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다. |
| [getValue()](#getValue--) | PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | PSD 파일에서 배치 레이어의 버전을 가져옵니다(보통 3-5). |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | 수직 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [isCustom()](#isCustom--) | 이 인스턴스의 워프 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | PSD 이미지에 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다. |
| [setBottom(double value)](#setBottom-double-) | PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다. |
| [setCustom(boolean value)](#setCustom-boolean-) | 이 인스턴스의 워프 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | 수평 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 왜곡 항목을 가져오거나 설정합니다. |
| [setLeft(double value)](#setLeft-double-) | PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| [setPageNumber(int value)](#setPageNumber-int-) | PSD 파일에 배치된 레이어의 페이지 번호를 가져오거나 설정합니다. |
| [setPerspective(double value)](#setPerspective-double-) | PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | PSD 파일에 배치된 레이어의 유형을 가져오거나 설정합니다. |
| [setRight(double value)](#setRight-double-) | PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다. |
| [setTop(double value)](#setTop-double-) | PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| [setTotalPages(int value)](#setTotalPages-int-) | PSD 파일에 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | PSD 파일에 배치된 레이어의 변환 행렬을 가져오거나 설정합니다. |
| [setUOrder(int value)](#setUOrder-int-) | PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | PSD 이미지에서 스마트 객체 배치 레이어의 전역 고유 식별자를 가져오거나 설정합니다. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다. |
| [setValue(double value)](#setValue-double-) | PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | 수직 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


PSD 이미지에 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다.

값: 배치된 레이어의 anti alias 정책.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 하단 위치.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다.

값: 배치된 레이어 경계.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


수평 메시 포인트의 측정 단위를 가져오거나 설정합니다.

값: 수평 메시 포인트의 측정 단위.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다.

값: 배치된 레이어의 수평 메시 포인트.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


왜곡 항목을 가져오거나 설정합니다.

값: 워프 항목.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 왼쪽 위치.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


PSD 파일에 배치된 레이어의 페이지 번호를 가져오거나 설정합니다.

값: 배치된 레이어의 페이지 번호.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다.

값: 배치된 레이어의 원근값.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다.

값: 배치된 레이어의 다른 원근값.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


PSD 파일에 배치된 레이어의 유형을 가져오거나 설정합니다.

값: 배치된 레이어의 유형.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 오른쪽 위치.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 상단 위치.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


PSD 파일에 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다.

값: 배치된 레이어의 총 페이지 수.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


PSD 파일에 배치된 레이어의 변환 행렬을 가져오거나 설정합니다.

값: 배치된 레이어의 변환 행렬.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다.

값: 배치된 레이어의 U 차수 값.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


PSD 이미지에서 스마트 객체 배치 레이어의 전역 고유 식별자를 가져오거나 설정합니다.

값: 배치된 레이어의 고유 식별자.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다.

값: 배치된 레이어의 V 차수 값.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다.

값: 배치된 레이어의 왜곡 값.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


PSD 파일에서 배치 레이어의 버전을 가져옵니다(보통 3-5).

값: 배치 또는 스마트 객체 레이어 버전.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


수직 메시 포인트의 측정 단위를 가져오거나 설정합니다.

값: 수직 메쉬 포인트의 측정 단위.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다.

값: 배치된 레이어의 수평 메시 포인트.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


이 인스턴스의 왜곡 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. true이면 메쉬 포인트를 포함합니다. false로 설정하면 메쉬 포인트를 지웁니다.

값: 배치 또는 스마트 객체 레이어 리소스에 사용자 정의 스타일이 있으면 true, 그렇지 않으면 false.

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


PSD 이미지에 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다.

값: 배치된 레이어의 anti alias 정책.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 하단 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다.

값: 배치된 레이어 경계.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


이 인스턴스의 왜곡 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. true이면 메쉬 포인트를 포함합니다. false로 설정하면 메쉬 포인트를 지웁니다.

값: 배치 또는 스마트 객체 레이어 리소스에 사용자 정의 스타일이 있으면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


수평 메시 포인트의 측정 단위를 가져오거나 설정합니다.

값: 수평 메시 포인트의 측정 단위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다.

값: 배치된 레이어의 수평 메시 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


왜곡 항목을 가져오거나 설정합니다.

값: 워프 항목.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 왼쪽 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


PSD 파일에 배치된 레이어의 페이지 번호를 가져오거나 설정합니다.

값: 배치된 레이어의 페이지 번호.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다.

값: 배치된 레이어의 원근값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다.

값: 배치된 레이어의 다른 원근값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


PSD 파일에 배치된 레이어의 유형을 가져오거나 설정합니다.

값: 배치된 레이어의 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 오른쪽 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 상단 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


PSD 파일에 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다.

값: 배치된 레이어의 총 페이지 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


PSD 파일에 배치된 레이어의 변환 행렬을 가져오거나 설정합니다.

값: 배치된 레이어의 변환 행렬.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다.

값: 배치된 레이어의 U 차수 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


PSD 이미지에서 스마트 객체 배치 레이어의 전역 고유 식별자를 가져오거나 설정합니다.

값: 배치된 레이어의 고유 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다.

값: 배치된 레이어의 V 차수 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다.

값: 배치된 레이어의 왜곡 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


수직 메시 포인트의 측정 단위를 가져오거나 설정합니다.

값: 수직 메쉬 포인트의 측정 단위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다.

값: 배치된 레이어의 수평 메시 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

