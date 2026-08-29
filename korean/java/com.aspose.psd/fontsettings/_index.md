---
title: "FontSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "일반 이미지 벡터 형식 렌더러의 글꼴 설정."
type: docs
weight: 47
url: /ko/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

일반 이미지 벡터 형식 렌더러의 글꼴 설정.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | 글꼴 패밀리 이름으로 adobe 글꼴 이름을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | 기본 글꼴 이름을 가져옵니다. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | 기본 글꼴 폴더를 가져옵니다. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | 글꼴 이름으로 글꼴 교체 배열을 가져옵니다. |
| [getFontsFolders()](#getFontsFolders--) | Aspose.Imaging이 TrueType 글꼴을 찾는 폴더 목록을 포함하는 배열의 복사본을 가져옵니다. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | 값을 가져오거나 설정합니다. 이는 [get alternative font] 여부를 나타냅니다. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | 가장 적합한 교체 글꼴을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | 지정된 글꼴 이름이 [is font allowed]인지 여부를 판단합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | 글꼴 캐시 파일을 제거합니다. |
| [reset()](#reset--) | 글꼴 폴더와 기본 글꼴 이름을 시스템 기본값으로 재설정합니다. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | 글꼴 사용을 글꼴 목록으로 제한합니다. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | 기본 글꼴 이름을 설정합니다. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | 글꼴 교체 목록을 설정합니다. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | 폴더에 대한 글꼴 폴더 목록을 재정의합니다. |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | 여러 폴더에 대한 글꼴 폴더 목록을 재정의합니다. |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | TrueType 글꼴이 로드되는 폴더를 설정하고 로드된 모든 글꼴을 지웁니다. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | 값을 가져오거나 설정합니다. 이는 [get alternative font] 여부를 나타냅니다. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | 텍스트 레이어가 포함된 PSD 파일에 대한 글꼴 캐시를 업데이트합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


글꼴 패밀리 이름으로 adobe 글꼴 이름을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontFamilyName | java.lang.String | 글꼴 패밀리 이름. |

**Returns:**
java.lang.String - 글꼴 패밀리 이름으로 adobe 글꼴 이름.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


기본 글꼴 이름을 가져옵니다.

**Returns:**
java.lang.String - 기본 글꼴 이름
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


기본 글꼴 폴더를 가져옵니다.

**Returns:**
java.lang.String[] - 시스템 폴더를 반환합니다
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


글꼴 이름으로 글꼴 교체 배열을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 글꼴 이름. |

**Returns:**
java.lang.String[] - 제공된 글꼴에 대한 교체 이름 배열
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Aspose.Imaging이 TrueType 글꼴을 찾는 폴더 목록을 포함하는 배열의 복사본을 가져옵니다.

반환된 값은 Aspose.Imaging이 사용하는 데이터의 복사본입니다. 반환된 배열의 항목을 변경해도 문서 렌더링에 영향을 주지 않습니다. 새로운 글꼴 위치를 지정하려면 setFontsFolders 메서드를 사용하십시오.

**Returns:**
java.lang.String[] - 현재 글꼴 위치의 복사본입니다.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


값을 가져오거나 설정합니다. 이는 [get alternative font] 여부를 나타냅니다.

값:  true  if [get alternative font]; otherwise,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


가장 적합한 교체 글꼴을 가져옵니다. 모든 교체 글꼴이 허용되지 않으면 첫 번째 허용되고 사용 가능한 글꼴이 반환됩니다. 사용 가능한 글꼴이 없으면 인수에서 전달된 글꼴이 반환됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 글꼴 이름. |

**Returns:**
java.lang.String - 교체된 글꼴의 이름
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


지정된 글꼴 이름이 [is font allowed]인지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 글꼴 이름. |

**Returns:**
boolean -  true  if [is font allowed] [the specified font name]; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


글꼴 캐시 파일을 제거합니다.

### reset() {#reset--}
```
public static void reset()
```


글꼴 폴더와 기본 글꼴 이름을 시스템 기본값으로 재설정합니다.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


글꼴을 글꼴 목록으로 제한합니다. 제한하기 전에 실제 글꼴 이름을 확인하십시오. 허용된 글꼴 목록을 Null로 설정하면 제한을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontList | java.lang.String[] | 글꼴 목록. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


기본 글꼴 이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 글꼴의 기본 이름. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


글꼴 교체 목록을 설정합니다. 글꼴이 허용되지 않으면 교체 글꼴을 찾습니다. 목록의 첫 번째 글꼴이 먼저 사용됩니다. 해당 글꼴도 제한된 경우 목록에서 다음 글꼴이 선택됩니다. 글꼴에 교체 글꼴이 없거나 모든 교체 글꼴이 허용되지 않으면 허용된 글꼴 목록에서 첫 번째 허용된 글꼴이 사용됩니다. 허용되고 사용 가능한 글꼴이 없으면 라이브러리는 허용되지 않더라도 시스템 기본 글꼴을 사용하려 시도합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontToReplace | java.lang.String | 교체할 글꼴. |
| fontNames | java.lang.String[] | 유사도 순서대로 나열된 교체 글꼴 이름. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


폴더에 대한 글꼴 폴더 목록을 재정의합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| folder | java.lang.String | TrueType 글꼴이 포함된 폴더. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


여러 폴더에 대한 글꼴 폴더 목록을 재정의합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| folders | java.lang.String[] | 폴더 배열 |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


TrueType 글꼴이 로드되는 폴더를 설정하고 로드된 모든 글꼴을 지웁니다. 글꼴 폴더에 대한 검사는 수행되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| folders | java.lang.String[] | 글꼴 폴더. |
| 재귀 | boolean | 설정이 true [recursive]인 경우. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


값을 가져오거나 설정합니다. 이는 [get alternative font] 여부를 나타냅니다.

값:  true  if [get alternative font]; otherwise,  false .

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
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


텍스트 레이어가 포함된 PSD 파일에 대한 글꼴 캐시를 업데이트합니다. 이 메서드는 FontSettings.setFontsFolder(fontsFolder) 메서드를 사용하여 폴더 fontsFolder에서 가져온 글꼴이나 FontSettings.reset()으로 글꼴을 재설정한 경우가 PSD 파일을 처리할 때 고려되도록 보장합니다. PSD 이미지에 대해 FontSettings.setFontsFolder(fontsFolder) 또는 FontSettings.reset()을 호출할 때마다 이 메서드를 사용하십시오. 이 메서드를 호출하지 않으면 글꼴이 업데이트된다는 보장이 없습니다.

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

