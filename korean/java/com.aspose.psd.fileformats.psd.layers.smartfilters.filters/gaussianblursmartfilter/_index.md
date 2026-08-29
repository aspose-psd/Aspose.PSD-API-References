---
title: "GaussianBlurSmartFilter"
second_title: "Java용 Aspose.PSD API 참조"
description: "GaussianBlur 스마트 필터입니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class GaussianBlurSmartFilter extends SmartFilter
```

GaussianBlur 스마트 필터입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter--) | 새 인스턴스를 초기화합니다 [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) 클래스의. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [FilterType](#FilterType) | 현재 스마트 필터의 식별자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | 현재 필터를 입력 RasterImage 이미지에 적용합니다. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | 현재 필터를 입력 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 마스크 데이터에 적용합니다. |
| [crate_internalized(DescriptorStructure sourceDescriptor)](#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | 해당 유형의 현재 인스턴스에 대한 멤버별 복제본을 만듭니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | 블렌딩 모드를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | 스마트 필터 유형 식별자를 가져옵니다. |
| [getName()](#getName--) | 스마트 필터 이름을 가져옵니다. |
| [getOpacity()](#getOpacity--) | 스마트 필터의 불투명도 값을 가져오거나 설정합니다. |
| [getRadius()](#getRadius--) | 가우시안 스마트 필터의 반경을 가져오거나 설정합니다. |
| [getSourceDescriptor()](#getSourceDescriptor--) | 스마트 필터 데이터가 포함된 소스 디스크립터 구조입니다. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | 스마트 필터의 활성화 상태를 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | 블렌딩 모드를 가져오거나 설정합니다. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 스마트 필터의 활성화 상태를 가져오거나 설정합니다. |
| [setOpacity(double value)](#setOpacity-double-) | 스마트 필터의 불투명도 값을 가져오거나 설정합니다. |
| [setRadius(double value)](#setRadius-double-) | 가우시안 스마트 필터의 반경을 가져오거나 설정합니다. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | 스마트 필터 정보를 [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) 데이터에 저장하고 반환합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussianBlurSmartFilter() {#GaussianBlurSmartFilter--}
```
public GaussianBlurSmartFilter()
```


새 인스턴스를 초기화합니다 [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) 클래스의.

### FilterType {#FilterType}
```
public static final int FilterType
```


현재 스마트 필터의 식별자.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


현재 필터를 입력 RasterImage 이미지에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | 래스터 이미지입니다. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


현재 필터를 입력 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 마스크 데이터에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 마스크 데이터가 있는 레이어. |

### crate_internalized(DescriptorStructure sourceDescriptor) {#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static GaussianBlurSmartFilter crate_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


해당 유형의 현재 인스턴스에 대한 멤버별 복제본을 만듭니다.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


블렌딩 모드를 가져오거나 설정합니다.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


스마트 필터 유형 식별자를 가져옵니다.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


스마트 필터 이름을 가져옵니다.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


스마트 필터의 불투명도 값을 가져오거나 설정합니다.

**Returns:**
double
### getRadius() {#getRadius--}
```
public final double getRadius()
```


가우시안 스마트 필터의 반경을 가져오거나 설정합니다.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


스마트 필터 데이터가 포함된 소스 디스크립터 구조입니다.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


스마트 필터의 활성화 상태를 가져오거나 설정합니다.

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




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


블렌딩 모드를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


스마트 필터의 활성화 상태를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


스마트 필터의 불투명도 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


가우시안 스마트 필터의 반경을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


스마트 필터 정보를 [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) 데이터에 저장하고 반환합니다.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
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

