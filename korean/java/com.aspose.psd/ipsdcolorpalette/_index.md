---
title: "IPsdColorPalette"
second_title: "Java용 Aspose.PSD API 참조"
description: "The pasd 색상 팔레트"
type: docs
weight: 134
url: /ko/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

The pasd 색상 팔레트
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | 원시 색상 팔레트 항목 데이터를 가져옵니다. |
| [getRawEntriesCount()](#getRawEntriesCount--) | 원시 색상 팔레트 항목 수를 가져옵니다. |
| [getTransparentColor()](#getTransparentColor--) | 투명 색상을 가져옵니다. |
| [getTransparentIndex()](#getTransparentIndex--) | 투명 색상의 인덱스를 가져옵니다. |
| [hasTransparentColor()](#hasTransparentColor--) | 투명 색상이 존재하는지 여부를 나타내는 값을 가져옵니다. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


원시 색상 팔레트 항목 데이터를 가져옵니다.

값: 원시 색상 팔레트 항목 데이터.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


원시 색상 팔레트 항목 수를 가져옵니다.

값: 원시 색상 팔레트 항목 수.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


투명 색상을 가져옵니다.

값: 투명 색상.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


투명 색상의 인덱스를 가져옵니다.

값: 투명 색상의 인덱스.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


투명 색상이 존재하는지 여부를 나타내는 값을 가져옵니다.

값: true 투명 색상이 존재하면; 그렇지 않으면 false.

**Returns:**
boolean
