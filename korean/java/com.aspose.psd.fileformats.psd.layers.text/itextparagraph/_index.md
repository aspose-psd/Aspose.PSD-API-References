---
title: "ITextParagraph"
second_title: "Java용 Aspose.PSD API 참조"
description: "단락 작업을 위한 인터페이스"
type: docs
weight: 12
url: /ko/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

단락 작업을 위한 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 지정된 단락을 적용합니다. |
| [getAutoHyphenate()](#getAutoHyphenate--) | 자동 [automatic hyphenate] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getAutoLeading()](#getAutoLeading--) | 자동 리딩을 가져오거나 설정합니다. |
| [getBurasagari()](#getBurasagari--) | 이 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 가 burasagiri인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | 연속 하이픈을 가져오거나 설정합니다. |
| [getEndIndent()](#getEndIndent--) | 끝 들여쓰기를 가져오거나 설정합니다. |
| [getEveryLineComposer()](#getEveryLineComposer--) | 이 [every line composer] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getFirstLineIndent()](#getFirstLineIndent--) | 첫 번째 줄 들여쓰기를 가져오거나 설정합니다. |
| [getGlyphSpacing()](#getGlyphSpacing--) | 글리프 간격을 가져오거나 설정합니다. |
| [getHanging()](#getHanging--) | 이 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 가 hanging인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | 하이픈이 포함된 단어의 크기를 가져오거나 설정합니다. |
| [getJustification()](#getJustification--) | 정렬을 가져오거나 설정합니다. |
| [getKinsokuOrder()](#getKinsokuOrder--) | 킨소쿠 순서를 가져오거나 설정합니다. |
| [getLeadingType()](#getLeadingType--) | 리딩 유형을 가져오거나 설정합니다. |
| [getLetterSpacing()](#getLetterSpacing--) | 문자 간격을 가져오거나 설정합니다. |
| [getPostHyphen()](#getPostHyphen--) | 후행 하이픈을 가져오거나 설정합니다. |
| [getPreHyphen()](#getPreHyphen--) | 전 hyphen을 가져오거나 설정합니다. |
| [getSpaceAfter()](#getSpaceAfter--) | 뒤의 공백을 가져오거나 설정합니다. |
| [getSpaceBefore()](#getSpaceBefore--) | 앞의 공백을 가져오거나 설정합니다. |
| [getStartIndent()](#getStartIndent--) | 시작 들여쓰기를 가져오거나 설정합니다. |
| [getWordSpacing()](#getWordSpacing--) | 단어 간격을 가져오거나 설정합니다. |
| [getZone()](#getZone--) | 영역을 가져오거나 설정합니다. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 지정된 단락이 같은지 여부를 결정합니다. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | 자동 [automatic hyphenate] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | 자동 리딩을 가져오거나 설정합니다. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | 이 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 가 burasagiri인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | 연속 하이픈을 가져오거나 설정합니다. |
| [setEndIndent(double value)](#setEndIndent-double-) | 끝 들여쓰기를 가져오거나 설정합니다. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | 이 [every line composer] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | 첫 번째 줄 들여쓰기를 가져오거나 설정합니다. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | 글리프 간격을 가져오거나 설정합니다. |
| [setHanging(boolean value)](#setHanging-boolean-) | 이 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 가 hanging인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | 하이픈이 포함된 단어의 크기를 가져오거나 설정합니다. |
| [setJustification(int value)](#setJustification-int-) | 정렬을 가져오거나 설정합니다. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | 킨소쿠 순서를 가져오거나 설정합니다. |
| [setLeadingType(int value)](#setLeadingType-int-) | 리딩 유형을 가져오거나 설정합니다. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | 문자 간격을 가져오거나 설정합니다. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | 후행 하이픈을 가져오거나 설정합니다. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | 전 hyphen을 가져오거나 설정합니다. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | 뒤의 공백을 가져오거나 설정합니다. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | 앞의 공백을 가져오거나 설정합니다. |
| [setStartIndent(double value)](#setStartIndent-double-) | 시작 들여쓰기를 가져오거나 설정합니다. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | 단어 간격을 가져오거나 설정합니다. |
| [setZone(double value)](#setZone-double-) | 영역을 가져오거나 설정합니다. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


지정된 단락을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | 단락. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


자동 [automatic hyphenate] 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true 이면 [automatic hyphenate]; 그렇지 않으면  false .

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


자동 리딩을 가져오거나 설정합니다.

값: 자동 리딩.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


이 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 가 burasagiri인지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true 이면 burasagiri; 그렇지 않으면  false .

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


연속 하이픈을 가져오거나 설정합니다.

값: 연속 hyphens.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


끝 들여쓰기를 가져오거나 설정합니다.

값: 끝 들여쓰기.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


이 [every line composer] 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true 이면 [every line composer]; 그렇지 않으면  false .

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


첫 번째 줄 들여쓰기를 가져오거나 설정합니다.

값: 첫 번째 줄 들여쓰기.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


글리프 간격을 가져오거나 설정합니다.

값: 글리프 간격.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


이 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 가 hanging인지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true 이면 hanging; 그렇지 않으면  false .

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


하이픈이 포함된 단어의 크기를 가져오거나 설정합니다.

값: 하이픈이 적용된 단어의 크기.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


정렬을 가져오거나 설정합니다.

값: 정렬.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


킨소쿠 순서를 가져오거나 설정합니다.

값: kinsoku 순서.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


리딩 유형을 가져오거나 설정합니다.

값: 리딩 유형.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


문자 간격을 가져오거나 설정합니다.

값: 문자 간격.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


후행 하이픈을 가져오거나 설정합니다.

값: 후 hyphen.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


전 hyphen을 가져오거나 설정합니다.

값: 전 hyphen.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


뒤의 공백을 가져오거나 설정합니다.

값: 뒤 공백.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


앞의 공백을 가져오거나 설정합니다.

값: 앞의 공백.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


시작 들여쓰기를 가져오거나 설정합니다.

값: 시작 들여쓰기.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


단어 간격을 가져오거나 설정합니다.

값: 단어 간격.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


영역을 가져오거나 설정합니다.

값: 영역.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


지정된 단락이 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | 단락. |

**Returns:**
불리언 - 지정된 단락이 동일하면 true, 그렇지 않으면 false.
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


자동 [automatic hyphenate] 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true 이면 [automatic hyphenate]; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


자동 리딩을 가져오거나 설정합니다.

값: 자동 리딩.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


이 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 가 burasagiri인지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true 이면 burasagiri; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


연속 하이픈을 가져오거나 설정합니다.

값: 연속 hyphens.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


끝 들여쓰기를 가져오거나 설정합니다.

값: 끝 들여쓰기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


이 [every line composer] 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true 이면 [every line composer]; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


첫 번째 줄 들여쓰기를 가져오거나 설정합니다.

값: 첫 번째 줄 들여쓰기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


글리프 간격을 가져오거나 설정합니다.

값: 글리프 간격.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


이 [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) 가 hanging인지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true 이면 hanging; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


하이픈이 포함된 단어의 크기를 가져오거나 설정합니다.

값: 하이픈이 적용된 단어의 크기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


정렬을 가져오거나 설정합니다.

값: 정렬.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


킨소쿠 순서를 가져오거나 설정합니다.

값: kinsoku 순서.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


리딩 유형을 가져오거나 설정합니다.

값: 리딩 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


문자 간격을 가져오거나 설정합니다.

값: 문자 간격.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


후행 하이픈을 가져오거나 설정합니다.

값: 후 hyphen.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


전 hyphen을 가져오거나 설정합니다.

값: 전 hyphen.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


뒤의 공백을 가져오거나 설정합니다.

값: 뒤 공백.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


앞의 공백을 가져오거나 설정합니다.

값: 앞의 공백.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


시작 들여쓰기를 가져오거나 설정합니다.

값: 시작 들여쓰기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


단어 간격을 가져오거나 설정합니다.

값: 단어 간격.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


영역을 가져오거나 설정합니다.

값: 영역.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

