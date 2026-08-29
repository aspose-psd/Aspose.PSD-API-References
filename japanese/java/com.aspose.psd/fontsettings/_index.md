---
title: "FontSettings"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "一般的なイメージングベクターフォーマットレンダラのフォント設定です。"
type: docs
weight: 47
url: /ja/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

一般的なイメージングベクターフォーマットレンダラのフォント設定です。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | フォントファミリ名からAdobeフォント名を取得します。 |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | デフォルトのフォント名を取得します。 |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | デフォルトのフォントフォルダーを取得します。 |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | フォント名でフォント置換配列を取得します |
| [getFontsFolders()](#getFontsFolders--) | Aspose.Imaging が TrueType フォントを検索するフォルダーのリストを含む配列のコピーを取得します。 |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | 代替フォントを取得するかどうかを示す値を取得または設定します。[get alternative font] |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | 最も適切な置換フォントを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | 指定されたフォント名が許可されているかどうかを判定します。[is font allowed] [the specified font name] |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | フォントキャッシュファイルを削除します。 |
| [reset()](#reset--) | フォントフォルダーとデフォルトのフォント名をシステム既定にリセットします。 |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | フォントの使用をフォントリストで制限します。 |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | デフォルトのフォント名を設定します。 |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | フォント置換リストを設定します。 |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | フォルダー用のフォントフォルダーリストを上書きします |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | フォルダー用のフォントフォルダーリストを上書きします |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | TrueType フォントが読み込まれるフォルダーを設定し、すべての読み込まれたフォントをクリアします。 |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | 代替フォントを取得するかどうかを示す値を取得または設定します。[get alternative font] |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | テキストレイヤーを含む PSD ファイル用にフォントキャッシュを更新します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


フォントファミリ名からAdobeフォント名を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontFamilyName | java.lang.String | フォントファミリ名です。 |

**Returns:**
java.lang.String - フォントファミリ名からAdobeフォント名を取得します。
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


デフォルトのフォント名を取得します。

**Returns:**
java.lang.String - デフォルトフォントの名前
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


デフォルトのフォントフォルダーを取得します。

**Returns:**
java.lang.String[] - システムフォルダーを返します
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


フォント名でフォント置換配列を取得します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | フォントの名前。 |

**Returns:**
java.lang.String[] - 提供されたフォントの置換名の配列
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Aspose.Imaging が TrueType フォントを検索するフォルダーのリストを含む配列のコピーを取得します。

返された値は Aspose.Imaging が使用するデータのコピーです。返された配列のエントリを変更しても、ドキュメントのレンダリングには影響しません。新しいフォントの場所を指定するには setFontsFolders メソッドを使用します。

**Returns:**
java.lang.String[] - 現在のフォント位置のコピーです。
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


代替フォントを取得するかどうかを示す値を取得または設定します。[get alternative font]

値:  true  は [get alternative font] の場合; それ以外は,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


最も適切な置換フォントを取得します。すべての置換が許可されていない場合、最初に許可され利用可能なフォントが返されます。利用可能なフォントがない場合は、引数で指定されたフォントが返されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | フォントの名前。 |

**Returns:**
java.lang.String - 置換されたフォントの名前
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


指定されたフォント名が許可されているかどうかを判定します。[is font allowed] [the specified font name]

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | フォントの名前。 |

**Returns:**
boolean -  true  は [is font allowed] [the specified font name] の場合; それ以外は,  false .
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


フォントキャッシュファイルを削除します。

### reset() {#reset--}
```
public static void reset()
```


フォントフォルダーとデフォルトのフォント名をシステム既定にリセットします。

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


フォントの使用をフォントリストで制限します。制限を設定する前に実際のフォント名を確認してください。Allowed フォントリストを Null に設定すると制限が解除されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontList | java.lang.String[] | フォントリストです。 |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


デフォルトのフォント名を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | フォントのデフォルト名です。 |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


フォント置換リストを設定します。フォントが許可されていない場合、置換フォントが検索されます。リスト内の最初のフォントが最初に使用されます。もしそれも制限されている場合、リストの次のフォントが選択されます。フォントに置換がない、またはすべての置換が許可されていない場合は、Allowed フォントリストから最初に許可されたフォントが使用されます。許可され利用可能なフォントがない場合、ライブラリはシステム既定フォントを使用しようとします（たとえ許可されていなくても）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontToReplace | java.lang.String | 置換対象のフォントです。 |
| fontNames | java.lang.String[] | 類似度順の置換フォント名です。 |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


フォルダー用のフォントフォルダーリストを上書きします

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| folder | java.lang.String | TrueType フォントが格納されたフォルダーです。 |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


フォルダー用のフォントフォルダーリストを上書きします

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| folders | java.lang.String[] | フォルダーの配列 |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


TrueType フォントがロードされるフォルダーを設定し、すべてのロード済みフォントをクリアします。フォルダーに対するチェックは行われません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| folders | java.lang.String[] | フォントフォルダーです。 |
| 再帰 | boolean | true に設定された場合 [recursive]。 |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


代替フォントを取得するかどうかを示す値を取得または設定します。[get alternative font]

値:  true  は [get alternative font] の場合; それ以外は,  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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


テキストレイヤーを含む PSD ファイルのフォントキャッシュを更新します。このメソッドは、FontSettings.setFontsFolder(fontsFolder) メソッドでフォルダー fontsFolder から取得したフォント、または FontSettings.reset() でリセットされたフォントが PSD ファイルの処理時に考慮されることを保証します。PSD 画像に対して FontSettings.setFontsFolder(fontsFolder) または FontSettings.reset() が呼び出されるたびにこのメソッドを使用してください。このメソッドを呼び出さない場合、フォントが更新される保証はありません。

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

