---
title: "ImageAttributes"
second_title: "Java용 Aspose.PSD API 참조"
description: "com.aspose.psd.ImageAttributes 객체는 렌더링 중 비트맵 및 메타파일 색상이 어떻게 조작되는지에 대한 정보를 포함합니다."
type: docs
weight: 55
url: /ko/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

com.aspose.psd.ImageAttributes 객체는 색상 조정 행렬, 그레이스케일 조정 행렬, 감마 보정 값, 색상 매핑 테이블 및 색상 임계값을 포함한 여러 색상 조정 설정을 유지합니다. 렌더링 중에 색상을 보정, 어둡게, 밝게, 제거할 수 있습니다. 이러한 조작을 적용하려면 com.aspose.psd.ImageAttributes 객체를 초기화하고 해당 com.aspose.psd.ImageAttributes 객체의 경로(및 [Image](../../com.aspose.psd/image) 경로)를 drawImage 메서드에 전달하십시오.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | com.aspose.psd.ImageAttributes 클래스를 새 인스턴스로 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | GDI 이미지 속성입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | 이 com.aspose.psd.ImageAttributes 객체의 브러시 색상 재매핑 테이블을 지웁니다. |
| [clearColorKey()](#clearColorKey--) | 기본 카테고리의 색상 키(투명도 범위)를 지웁니다. |
| [clearColorKey(int type)](#clearColorKey-int-) | 지정된 카테고리의 색상 키(투명도 범위)를 지웁니다. |
| [clearColorMatrix()](#clearColorMatrix--) | 기본 카테고리의 색상 조정 행렬을 지웁니다. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | 지정된 카테고리의 색상 조정 행렬을 지웁니다. |
| [clearGamma()](#clearGamma--) | 기본 카테고리의 감마 보정을 비활성화합니다. |
| [clearGamma(int type)](#clearGamma-int-) | 지정된 카테고리의 감마 보정을 비활성화합니다. |
| [clearNoOp()](#clearNoOp--) | 기본 카테고리의 NoOp 설정을 지웁니다. |
| [clearNoOp(int type)](#clearNoOp-int-) | 지정된 카테고리의 NoOp 설정을 지웁니다. |
| [clearOutputChannel()](#clearOutputChannel--) | 기본 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | 지정된 카테고리의 (시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | 기본 카테고리의 출력 채널 색상 프로파일 설정을 지웁니다. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | 지정된 카테고리의 출력 채널 색상 프로파일 설정을 지웁니다. |
| [clearRemapTable()](#clearRemapTable--) | 기본 카테고리의 색상 재매핑 테이블을 지웁니다. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | 지정된 카테고리의 색상 재매핑 테이블을 지웁니다. |
| [clearThreshold()](#clearThreshold--) | 기본 카테고리의 임계값을 지웁니다. |
| [clearThreshold(int type)](#clearThreshold-int-) | 지정된 카테고리의 임계값을 지웁니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | 브러시 카테고리의 색상 재매핑 테이블을 설정합니다. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | 기본 카테고리의 색상 키를 설정합니다. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | 지정된 카테고리의 색상 키(투명도 범위)를 설정합니다. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | 기본 카테고리의 색상 보정 매트릭스와 그레이스케일 보정 매트릭스를 설정합니다. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | 기본 카테고리의 색상 보정 매트릭스와 그레이스케일 보정 매트릭스를 설정합니다. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | 지정된 카테고리의 색상 보정 매트릭스와 그레이스케일 보정 매트릭스를 설정합니다. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | 기본 카테고리의 색상 보정 매트릭스를 설정합니다. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | 기본 카테고리의 색상 보정 매트릭스를 설정합니다. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | 지정된 카테고리의 색상 보정 매트릭스를 설정합니다. |
| [setGamma(float gamma)](#setGamma-float-) | 기본 카테고리의 감마 값을 설정합니다. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | 지정된 카테고리의 감마 값을 설정합니다. |
| [setNoOp()](#setNoOp--) | 기본 카테고리의 색상 보정을 끕니다. |
| [setNoOp(int type)](#setNoOp-int-) | 지정된 카테고리의 색상 보정을 끕니다. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | 기본 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | 지정된 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | 기본 카테고리의 출력 채널 색상 프로파일 파일을 설정합니다. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | 지정된 카테고리의 출력 채널 색상 프로파일 파일을 설정합니다. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | 기본 카테고리의 색상 재매핑 테이블을 설정합니다. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | 지정된 카테고리의 색상 재매핑 테이블을 설정합니다. |
| [setThreshold(float threshold)](#setThreshold-float-) | 기본 카테고리의 임계값(투명도 범위)을 설정합니다. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | 지정된 카테고리의 임계값(투명도 범위)을 설정합니다. |
| [setWrapMode(int mode)](#setWrapMode-int-) | 텍스처를 도형 전체에 타일링하거나 도형 경계에서 어떻게 타일링할지 결정하는 랩 모드를 설정합니다. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | 텍스처를 도형 전체에 타일링하거나 도형 경계에서 어떻게 타일링할지 결정하는 랩 모드와 색상을 설정합니다. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | 텍스처를 도형 전체에 타일링하거나 도형 경계에서 어떻게 타일링할지 결정하는 랩 모드와 색상을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


com.aspose.psd.ImageAttributes 클래스를 새 인스턴스로 초기화합니다.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


GDI 이미지 속성입니다.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


이 com.aspose.psd.ImageAttributes 객체의 브러시 색상 재매핑 테이블을 지웁니다.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


기본 카테고리의 색상 키(투명도 범위)를 지웁니다.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


지정된 카테고리의 색상 키(투명도 범위)를 지웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 색상 키가 지워지는 카테고리를 지정하는 Aspose.Imaging.ColorAdjustType의 요소입니다. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


기본 카테고리의 색상 조정 행렬을 지웁니다.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


지정된 카테고리의 색상 조정 행렬을 지웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 색 보정 행렬이 지워지는 범주를 지정합니다. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


기본 카테고리의 감마 보정을 비활성화합니다.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


지정된 카테고리의 감마 보정을 비활성화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 감마 보정이 비활성화되는 범주를 지정합니다. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


기본 카테고리의 NoOp 설정을 지웁니다.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


지정된 카테고리의 NoOp 설정을 지웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, NoOp 설정이 지워지는 범주를 지정합니다. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


기본 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


지정된 카테고리의 (시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 출력 채널 설정이 지워지는 범주를 지정합니다. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


기본 카테고리의 출력 채널 색상 프로파일 설정을 지웁니다.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


지정된 카테고리의 출력 채널 색상 프로파일 설정을 지웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 출력 채널 프로파일 설정이 지워지는 범주를 지정합니다. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


기본 카테고리의 색상 재매핑 테이블을 지웁니다.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


지정된 카테고리의 색상 재매핑 테이블을 지웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 재매핑 테이블이 지워지는 범주를 지정합니다. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


기본 카테고리의 임계값을 지웁니다.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


지정된 카테고리의 임계값을 지웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 임계값이 지워지는 범주를 지정합니다. |

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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


브러시 카테고리의 색상 재매핑 테이블을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap 객체 배열입니다. |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


기본 카테고리의 색상 키를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | 낮은 색키 값입니다. |
| colorHigh | [Color](../../com.aspose.psd/color) | 높은 색키 값입니다. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


지정된 카테고리의 색상 키(투명도 범위)를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | 낮은 색키 값입니다. |
| colorHigh | [Color](../../com.aspose.psd/color) | 높은 색키 값입니다. |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 색키가 설정되는 범주를 지정합니다. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


기본 카테고리의 색상 보정 매트릭스와 그레이스케일 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 색 보정 행렬입니다. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 그레이스케일 보정 행렬입니다. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


기본 카테고리의 색상 보정 매트릭스와 그레이스케일 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 색 보정 행렬입니다. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 그레이스케일 보정 행렬입니다. |
| 플래그 | int | Aspose.Imaging.ColorMatrixFlag의 요소이며, 색 보정 및 그레이스케일 보정 행렬에 영향을 받을 이미지 및 색상의 유형을 지정합니다. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


지정된 카테고리의 색상 보정 매트릭스와 그레이스케일 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 색 보정 행렬입니다. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 그레이스케일 보정 행렬입니다. |
| 모드 | int | Aspose.Imaging.ColorMatrixFlag의 요소이며, 색 보정 및 그레이스케일 보정 행렬에 영향을 받을 이미지 및 색상의 유형을 지정합니다. |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 색 보정 및 그레이스케일 보정 행렬이 설정되는 범주를 지정합니다. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


기본 카테고리의 색상 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 색 보정 행렬입니다. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


기본 카테고리의 색상 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 색 보정 행렬입니다. |
| 플래그 | int | Aspose.Imaging.ColorMatrixFlag의 요소이며, 색 보정 행렬에 영향을 받을 이미지 및 색상의 유형을 지정합니다. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


지정된 카테고리의 색상 보정 매트릭스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 색 보정 행렬입니다. |
| 모드 | int | Aspose.Imaging.ColorMatrixFlag의 요소이며, 색 보정 행렬에 영향을 받을 이미지 및 색상의 유형을 지정합니다. |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 색 보정 행렬이 설정되는 범주를 지정합니다. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


기본 카테고리의 감마 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 감마 | float | 감마 보정 값입니다. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


지정된 카테고리의 감마 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 감마 | float | 감마 보정 값입니다. |
| type | int | Aspose.Imaging.ColorAdjustType 열거형의 요소이며, 감마 값이 설정되는 범주를 지정합니다. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


기본 카테고리의 색상 보정을 끕니다.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


지정된 카테고리의 색상 보정을 끕니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 색 보정이 꺼지는 범주를 지정합니다. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


기본 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 플래그 | int | Aspose.Imaging.ColorChannelFlag의 요소이며, 출력 채널을 지정합니다. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


지정된 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 플래그 | int | Aspose.Imaging.ColorChannelFlag의 요소이며, 출력 채널을 지정합니다. |
| type | int | Aspose.Imaging.ColorAdjustType의 요소이며, 출력 채널이 설정되는 범주를 지정합니다. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


기본 카테고리의 출력 채널 색상 프로파일 파일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | 색 프로파일 파일의 경로 이름입니다. 색 프로파일 파일이 %SystemRoot%\\System32\\Spool\\Drivers\\Color 디렉터리에 있는 경우, 이 매개변수는 파일 이름이 될 수 있습니다. 그렇지 않으면, 이 매개변수는 전체 경로 이름이어야 합니다. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


지정된 카테고리의 출력 채널 색상 프로파일 파일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | 색 프로파일 파일의 경로 이름입니다. 색 프로파일 파일이 %SystemRoot%\\System32\\Spool\\Drivers\\Color 디렉터리에 있는 경우, 이 매개변수는 파일 이름이 될 수 있습니다. 그렇지 않으면, 이 매개변수는 전체 경로 이름이어야 합니다. |
| type | int | Aspose.Imaging.ColorAdjustType의 요소로, 출력 채널 색상 프로파일 파일이 설정되는 범주를 지정합니다. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


기본 카테고리의 색상 재매핑 테이블을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap 유형의 색상 쌍 배열입니다. 각 색상 쌍은 기존 색상(첫 번째 값)과 매핑될 색상(두 번째 값)을 포함합니다. |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


지정된 카테고리의 색상 재매핑 테이블을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap 유형의 색상 쌍 배열입니다. 각 색상 쌍은 기존 색상(첫 번째 값)과 매핑될 색상(두 번째 값)을 포함합니다. |
| type | int | Aspose.Imaging.ColorAdjustType의 요소로, 색상 재매핑 테이블이 설정되는 범주를 지정합니다. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


기본 카테고리의 임계값(투명도 범위)을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| threshold | float | 임계값을 지정하는 실수입니다. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


지정된 카테고리의 임계값(투명도 범위)을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| threshold | float | 0.0에서 1.0 사이의 임계값으로, 색상이 최대값 또는 최소값으로 매핑되도록 정렬하는 분기점으로 사용됩니다. |
| type | int | Aspose.Imaging.ColorAdjustType의 요소로, 색상 임계값이 설정되는 범주를 지정합니다. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드를 설정합니다. 텍스처가 채우려는 도형보다 작을 경우 텍스처가 도형 전체에 타일링되어 채워집니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 모드 | int | Aspose.Imaging.WrapMode의 요소로, 이미지의 반복 복사본이 영역을 타일링하는 방식을 지정합니다. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 채우려는 도형보다 작을 경우 텍스처가 도형 전체에 타일링되어 채워집니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 모드 | int | Aspose.Imaging.WrapMode의 요소로, 이미지의 반복 복사본이 영역을 타일링하는 방식을 지정합니다. |
| color | [Color](../../com.aspose.psd/color) | 렌더링된 이미지 외부 픽셀의 색상을 지정하는 com.aspose.psd.ImageAttributes 객체입니다. 모드 매개변수가 WrapMode.Clamp으로 설정되고 DrawImage에 전달된 소스 사각형이 이미지 자체보다 클 경우 이 색상이 표시됩니다. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 채우려는 도형보다 작을 경우 텍스처가 도형 전체에 타일링되어 채워집니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 모드 | int | Aspose.Imaging.WrapMode의 요소로, 이미지의 반복 복사본이 영역을 타일링하는 방식을 지정합니다. |
| color | [Color](../../com.aspose.psd/color) | 렌더링된 이미지 외부 픽셀의 색상을 지정하는 색상 객체입니다. 모드 매개변수가 WrapMode.Clamp으로 설정되고 DrawImage에 전달된 소스 사각형이 이미지 자체보다 클 경우 이 색상이 표시됩니다. |
| 클램프 | boolean | 이 매개변수는 효과가 없습니다. false로 설정하십시오. |

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

