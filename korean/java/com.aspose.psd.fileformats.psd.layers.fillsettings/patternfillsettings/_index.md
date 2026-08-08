---
title: "PatternFillSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "패턴 채우기 효과 설정"
type: docs
weight: 20
url: /ko/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

패턴 채우기 효과 설정
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | 새로운 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 클래스 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | LFX2 리소스 노드를 생성합니다. |
| [getAlignWithLayer()](#getAlignWithLayer--) | 이 [link with layer]인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getAngle()](#getAngle--) | 각도 값을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 색상을 가져오거나 설정합니다. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | 채우기 유형 |
| [getHorizontalOffset()](#getHorizontalOffset--) | 수평 오프셋 값을 가져오거나 설정합니다. |
| [getLinked()](#getLinked--) | 이 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 가 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getPatternData()](#getPatternData--) | 패턴 데이터를 가져오거나 설정합니다. |
| [getPatternHeight()](#getPatternHeight--) | 패턴의 높이를 가져오거나 설정합니다. |
| [getPatternId()](#getPatternId--) | 패턴 식별자를 가져오거나 설정합니다. |
| [getPatternName()](#getPatternName--) | 패턴 이름을 가져오거나 설정합니다. |
| [getPatternWidth()](#getPatternWidth--) | 패턴의 너비를 가져오거나 설정합니다. |
| [getPhase_internalized()](#getPhase-internalized--) | 위상을 가져오거나 설정합니다. |
| [getPointType()](#getPointType--) | 점의 유형을 가져오거나 설정합니다. |
| [getScale()](#getScale--) | 스케일을 가져오거나 설정합니다. |
| [getVerticalOffset()](#getVerticalOffset--) | 수직 오프셋 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 값 변경을 발생시킵니다. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | 이 [link with layer]인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setAngle(double value)](#setAngle-double-) | 각도 값을 가져오거나 설정합니다. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 색상을 가져오거나 설정합니다. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | 수평 오프셋 값을 가져오거나 설정합니다. |
| [setLinked(boolean value)](#setLinked-boolean-) | 이 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 가 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setPatternData(int[] value)](#setPatternData-int---) | 패턴 데이터를 가져오거나 설정합니다. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | 패턴의 픽셀 버퍼와 저장 시 사용할 압축 모드를 설정합니다. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | 패턴의 높이를 가져오거나 설정합니다. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | 패턴 식별자를 가져오거나 설정합니다. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | 패턴 이름을 가져오거나 설정합니다. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | 패턴의 너비를 가져오거나 설정합니다. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | 위상을 가져오거나 설정합니다. |
| [setPointType(String value)](#setPointType-java.lang.String-) | 점의 유형을 가져오거나 설정합니다. |
| [setScale(double value)](#setScale-double-) | 스케일을 가져오거나 설정합니다. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | 수직 오프셋 값을 가져오거나 설정합니다. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | 패턴의 기본 데이터를 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 인스턴스로 설정합니다. |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 인스턴스로부터 패턴 속성을 업데이트합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


새로운 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 클래스 인스턴스를 초기화합니다.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


LFX2 리소스 노드를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pointType | java.lang.String | 점의 유형. |
| color | [Color](../../com.aspose.psd/color) | 색상. |
| patternName | java.lang.String | 패턴 이름. |
| identifier | java.lang.String | 식별자. |
| 스케일 | double | 스케일. |
| linked | boolean | true 로 설정된 경우 [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | 오프셋. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 목록
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


이 [link with layer]인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: true 인 경우 [link with layer]; 그렇지 않으면 false.

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


각도 값을 가져오거나 설정합니다.

값: 각도.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


색상을 가져오거나 설정합니다.

값: 색상.

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


채우기 유형

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


수평 오프셋 값을 가져오거나 설정합니다.

값: 수평 오프셋.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


이 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 가 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 연결된 경우 true, 그렇지 않으면 false.

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


패턴 데이터를 가져오거나 설정합니다.

값: 패턴 데이터.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


패턴의 높이를 가져오거나 설정합니다.

값: 패턴의 높이.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


패턴 식별자를 가져오거나 설정합니다.

값: 패턴 식별자.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


패턴 이름을 가져오거나 설정합니다.

값: 패턴 이름.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


패턴의 너비를 가져오거나 설정합니다.

값: 패턴의 너비.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


위상을 가져오거나 설정합니다.

값: 단계.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


점의 유형을 가져오거나 설정합니다.

값: 포인트 유형.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


스케일을 가져오거나 설정합니다.

값: 스케일.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


수직 오프셋 값을 가져오거나 설정합니다.

값: 수직 오프셋.

**Returns:**
int
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


값 변경을 발생시킵니다.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


이 [link with layer]인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: true 인 경우 [link with layer]; 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


각도 값을 가져오거나 설정합니다.

값: 각도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


색상을 가져오거나 설정합니다.

값: 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


수평 오프셋 값을 가져오거나 설정합니다.

값: 수평 오프셋.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


이 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 가 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 연결된 경우 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


패턴 데이터를 가져오거나 설정합니다.

값: 패턴 데이터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


패턴의 픽셀 버퍼와 저장 시 사용할 압축 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| patternData | int[] | 0xAARRGGBB 형식의 32비트 픽셀. |
| compressionModeOnSave | byte | psd 파일 저장 시 패턴 데이터 압축을 정의하는 데 사용되는 압축 모드. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


패턴의 높이를 가져오거나 설정합니다.

값: 패턴의 높이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


패턴 식별자를 가져오거나 설정합니다.

값: 패턴 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


패턴 이름을 가져오거나 설정합니다.

값: 패턴 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


패턴의 너비를 가져오거나 설정합니다.

값: 패턴의 너비.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


위상을 가져오거나 설정합니다.

값: 단계.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


점의 유형을 가져오거나 설정합니다.

값: 포인트 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


스케일을 가져오거나 설정합니다.

값: 스케일.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


수직 오프셋 값을 가져오거나 설정합니다.

값: 수직 오프셋.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


패턴의 기본 데이터를 [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) 인스턴스로 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | 패턴 채우기 설정입니다. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 인스턴스로부터 패턴 속성을 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | 패턴 데이터를 포함하는 [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 인스턴스. |

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

