---
title: "ITextStyle"
second_title: "Java용 Aspose.PSD API 참조"
description: "텍스트 스타일 작업을 위한 인터페이스"
type: docs
weight: 14
url: /ko/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

텍스트 스타일 작업을 위한 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | 지정된 스타일을 적용합니다. |
| [getAutoKerning()](#getAutoKerning--) | 자동 커닝을 가져오거나 설정합니다. |
| [getAutoLeading()](#getAutoLeading--) | 값을 가져오거나 설정합니다, 이는 [automatic leading]인지 여부를 나타냅니다. |
| [getBaselineShift()](#getBaselineShift--) | 기준선 이동. |
| [getContextualAlternates()](#getContextualAlternates--) | 문자를 연결하는 데 사용되는 컨텍스트 대체 문자. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | 특히 스크립트 글꼴에서 문자를 연결하는 데 사용되는 선택적 합자. |
| [getFauxBold()](#getFauxBold--) | 가짜 굵게가 활성화되는지를 가져오거나 설정합니다. |
| [getFauxItalic()](#getFauxItalic--) | 가짜 굵게가 활성화되는지를 가져오거나 설정합니다. |
| [getFillColor()](#getFillColor--) | 채우기 색상을 가져오거나 설정합니다. |
| [getFontBaseline()](#getFontBaseline--) | 글꼴 기준선. |
| [getFontCaps()](#getFontCaps--) | 글꼴 대문자. |
| [getFontIndex()](#getFontIndex--) | 글꼴 인덱스를 가져옵니다. |
| [getFontName()](#getFontName--) | 글꼴 이름을 가져오거나 설정합니다. |
| [getFontSize()](#getFontSize--) | 글꼴 크기를 가져오거나 설정합니다. |
| [getFractions()](#getFractions--) | 분수 기호를 특수 글리프로 교체할 수 있습니다. |
| [getHindiNumbers()](#getHindiNumbers--) | 값을 가져오거나 설정합니다, 이는 [hindi numbers]인지 여부를 나타냅니다. |
| [getHorizontalScale()](#getHorizontalScale--) | 수평 스케일. |
| [getKerning()](#getKerning--) | 커닝을 가져오거나 설정합니다. |
| [getLanguageIndex()](#getLanguageIndex--) | 언어 인덱스를 가져옵니다. |
| [getLeading()](#getLeading--) | 리딩을 가져오거나 설정합니다. |
| [getStandardLigatures()](#getStandardLigatures--) | 문자를 함께 연결하는 데 사용되는 표준 문맥 합자입니다. |
| [getStrikethrough()](#getStrikethrough--) | 취소선인지 여부를 나타내는 값을 가져오거나 설정합니다 [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | 스트로크의 색상을 가져오거나 설정합니다. |
| [getTracking()](#getTracking--) | 트래킹을 가져오거나 설정합니다. |
| [getUnderline()](#getUnderline--) | 밑줄인지 여부를 나타내는 값을 가져오거나 설정합니다 [underline]. |
| [getVerticalScale()](#getVerticalScale--) | 수직 스케일입니다. |
| [get_noBreak()](#get-noBreak--) | 줄 바꿈 방지 값을 가져오거나 설정합니다. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | 지정된 스타일이 같은지 여부를 결정합니다. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | 표준 수직 로마 정렬을 가져오거나 설정합니다. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | 자동 커닝을 가져오거나 설정합니다. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | 값을 가져오거나 설정합니다, 이는 [automatic leading]인지 여부를 나타냅니다. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | 기준선 이동. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | 문자를 연결하는 데 사용되는 컨텍스트 대체 문자. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | 특히 스크립트 글꼴에서 문자를 연결하는 데 사용되는 선택적 합자. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | 가짜 굵게가 활성화되는지를 가져오거나 설정합니다. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | 가짜 굵게가 활성화되는지를 가져오거나 설정합니다. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | 채우기 색상을 가져오거나 설정합니다. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | 글꼴 기준선. |
| [setFontCaps(int value)](#setFontCaps-int-) | 글꼴 대문자. |
| [setFontName(String value)](#setFontName-java.lang.String-) | 글꼴 이름을 가져오거나 설정합니다. |
| [setFontSize(double value)](#setFontSize-double-) | 글꼴 크기를 가져오거나 설정합니다. |
| [setFractions(boolean value)](#setFractions-boolean-) | 분수 기호를 특수 글리프로 교체할 수 있습니다. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | 값을 가져오거나 설정합니다, 이는 [hindi numbers]인지 여부를 나타냅니다. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | 수평 스케일. |
| [setKerning(int value)](#setKerning-int-) | 커닝을 가져오거나 설정합니다. |
| [setLeading(double value)](#setLeading-double-) | 리딩을 가져오거나 설정합니다. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | 문자를 함께 연결하는 데 사용되는 표준 문맥 합자입니다. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | 취소선인지 여부를 나타내는 값을 가져오거나 설정합니다 [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | 스트로크의 색상을 가져오거나 설정합니다. |
| [setTracking(int value)](#setTracking-int-) | 트래킹을 가져오거나 설정합니다. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | 밑줄인지 여부를 나타내는 값을 가져오거나 설정합니다 [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | 수직 스케일입니다. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | 표준 수직 로마 정렬을 가져오거나 설정합니다. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | 줄 바꿈 방지 값을 가져오거나 설정합니다. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


지정된 스타일을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | 스타일입니다. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


자동 커닝을 가져오거나 설정합니다.

값: 두 문자 사이의 자동 커닝입니다.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


값을 가져오거나 설정합니다, 이는 [automatic leading]인지 여부를 나타냅니다.

값: [automatic leading]이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


기준선 이동.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


문자를 연결하는 데 사용되는 컨텍스트 대체 문자.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


특히 스크립트 글꼴에서 문자를 연결하는 데 사용되는 선택적 합자.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


가짜 굵게가 활성화되는지를 가져오거나 설정합니다.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


가짜 굵게가 활성화되는지를 가져오거나 설정합니다.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


채우기 색상을 가져오거나 설정합니다.

값: 채우기 색상입니다.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


글꼴 기준선.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


글꼴 대문자.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


글꼴 인덱스를 가져옵니다.

값: 글꼴입니다.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


글꼴 이름을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


글꼴 크기를 가져오거나 설정합니다.

값: 글꼴 크기입니다.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


분수 기호를 특수 글리프로 교체할 수 있습니다.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


값을 가져오거나 설정합니다, 이는 [hindi numbers]인지 여부를 나타냅니다.

값: [hindi numbers]이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


수평 스케일.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


커닝을 가져오거나 설정합니다.

값: 두 문자 사이의 커닝입니다.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


언어 인덱스를 가져옵니다.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


리딩을 가져오거나 설정합니다.

값: 리딩입니다.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


문자를 함께 연결하는 데 사용되는 표준 문맥 합자입니다.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


취소선인지 여부를 나타내는 값을 가져오거나 설정합니다 [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


스트로크의 색상을 가져오거나 설정합니다.

값: 스트로크 색상입니다.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


트래킹을 가져오거나 설정합니다.

값: 트래킹입니다.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


밑줄인지 여부를 나타내는 값을 가져오거나 설정합니다 [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


수직 스케일입니다.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


줄 바꿈 방지 값을 가져오거나 설정합니다.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


지정된 스타일이 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | 스타일입니다. |

**Returns:**
boolean - 지정된 스타일이 같으면 true, 그렇지 않으면 false.
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


표준 수직 로마 정렬을 가져오거나 설정합니다. 이 값은 BaselineDirection 리소스 값을 기반으로 하며 텍스트 방향이 [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical)인 경우에만 적용됩니다.

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


자동 커닝을 가져오거나 설정합니다.

값: 두 문자 사이의 자동 커닝입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


값을 가져오거나 설정합니다, 이는 [automatic leading]인지 여부를 나타냅니다.

값: [automatic leading]이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


기준선 이동.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


문자를 연결하는 데 사용되는 컨텍스트 대체 문자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


특히 스크립트 글꼴에서 문자를 연결하는 데 사용되는 선택적 합자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


가짜 굵게가 활성화되는지를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


가짜 굵게가 활성화되는지를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


채우기 색상을 가져오거나 설정합니다.

값: 채우기 색상입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


글꼴 기준선.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


글꼴 대문자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


글꼴 이름을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


글꼴 크기를 가져오거나 설정합니다.

값: 글꼴 크기입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


분수 기호를 특수 글리프로 교체할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


값을 가져오거나 설정합니다, 이는 [hindi numbers]인지 여부를 나타냅니다.

값: [hindi numbers]이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


수평 스케일.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


커닝을 가져오거나 설정합니다.

값: 두 문자 사이의 커닝입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


리딩을 가져오거나 설정합니다.

값: 리딩입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


문자를 함께 연결하는 데 사용되는 표준 문맥 합자입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


취소선인지 여부를 나타내는 값을 가져오거나 설정합니다 [strikethrough].

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


스트로크의 색상을 가져오거나 설정합니다.

값: 스트로크 색상입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


트래킹을 가져오거나 설정합니다.

값: 트래킹입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


밑줄인지 여부를 나타내는 값을 가져오거나 설정합니다 [underline].

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


수직 스케일입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


표준 수직 로마 정렬을 가져오거나 설정합니다. 이 값은 BaselineDirection 리소스 값을 기반으로 하며 텍스트 방향이 [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical)인 경우에만 적용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


줄 바꿈 방지 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

