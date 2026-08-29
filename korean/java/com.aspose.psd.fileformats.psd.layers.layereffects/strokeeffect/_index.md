---
title: "StrokeEffect"
second_title: "Java용 Aspose.PSD API 참조"
description: "PSD 레이어에 대한 Adobe Photoshop 스트로크 효과입니다."
type: docs
weight: 17
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

PSD 레이어용 Adobe® Photoshop® 스트로크 효과.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | 블렌드 모드를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | 엔터티를 가져옵니다. |
| [getEffectType()](#getEffectType--) | 효과 유형을 가져옵니다. |
| [getFillSettings()](#getFillSettings--) | 채우기 설정을 가져오거나 설정합니다. |
| [getOpacity()](#getOpacity--) | 불투명도를 가져오거나 설정합니다. |
| [getOverprint()](#getOverprint--) | 이 [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)가 현재 레이어 내용에 스트로크를 혼합할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getPosition()](#getPosition--) | 스트로크 효과의 위치를 가져오거나 설정하여 스트로크를 PSD 레이어 내용에 맞추는 정렬을 제어합니다. |
| [getSize()](#getSize--) | 스트로크 효과의 너비를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | 블렌드 모드를 가져오거나 설정합니다. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | 채우기 설정을 가져오거나 설정합니다. |
| [setOpacity(byte value)](#setOpacity-byte-) | 불투명도를 가져오거나 설정합니다. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | 이 [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)가 현재 레이어 내용에 스트로크를 혼합할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setPosition(short value)](#setPosition-short-) | 스트로크 효과의 위치를 가져오거나 설정하여 스트로크를 PSD 레이어 내용에 맞추는 정렬을 제어합니다. |
| [setSize(int value)](#setSize-int-) | 스트로크 효과의 너비를 가져오거나 설정합니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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


블렌드 모드를 가져오거나 설정합니다.

값: 블렌드 모드.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | 레이어 픽셀 경계. |
| globalAngle | int | 전역 조명을 계산하기 위한 전역 각도입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


엔터티를 가져옵니다.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


효과 유형을 가져옵니다.

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


채우기 설정을 가져오거나 설정합니다.

값: 채우기 설정.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


불투명도를 가져오거나 설정합니다.

값: 불투명도.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


이 [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)가 현재 레이어 내용에 스트로크를 혼합할지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 현재 레이어 내용에 스트로크를 혼합해야 하면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


스트로크 효과의 위치를 가져오거나 설정하여 스트로크를 PSD 레이어 내용에 맞추는 정렬을 제어합니다. 값은 PSD 레이어 내용 내부에 스트로크를 그리려면 [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside), 레이어 내용 주변에 스트로크를 그리려면 [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside), 내부와 외부 모두에 스트로크를 그리려면 [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center)으로 지정할 수 있습니다.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


스트로크 효과의 너비를 가져오거나 설정합니다.

값: 스트로크 효과의 너비.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 보이면; 그렇지 않으면  false .

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


블렌드 모드를 가져오거나 설정합니다.

값: 블렌드 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


채우기 설정을 가져오거나 설정합니다.

값: 채우기 설정.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


불투명도를 가져오거나 설정합니다.

값: 불투명도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


이 [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)가 현재 레이어 내용에 스트로크를 혼합할지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 현재 레이어 내용에 스트로크를 혼합해야 하면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


스트로크 효과의 위치를 가져오거나 설정하여 스트로크를 PSD 레이어 내용에 맞추는 정렬을 제어합니다. 값은 PSD 레이어 내용 내부에 스트로크를 그리려면 [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside), 레이어 내용 주변에 스트로크를 그리려면 [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside), 내부와 외부 모두에 스트로크를 그리려면 [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center)으로 지정할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


스트로크 효과의 너비를 가져오거나 설정합니다.

값: 스트로크 효과의 너비.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 보이면; 그렇지 않으면  false .

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

