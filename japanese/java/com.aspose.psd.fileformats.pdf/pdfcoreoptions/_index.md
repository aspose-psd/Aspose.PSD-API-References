---
title: "PdfCoreOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PDF変換の共通オプション"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.fileformats.pdf/pdfcoreoptions/
---

**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

PDF変換の共通オプション
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | 文書アウトラインのどのレベルでブックマークオブジェクトを表示するかを指定します。 |
| [getClass()](#getClass--) |  |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | PDF ファイルを表示したときに、文書アウトラインで展開して表示するレベル数を指定します。 |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | 文書アウトラインに含めるアウトライン項目のレベル数を指定します。 |
| [getJpegQuality()](#getJpegQuality--) | 画像の JPEG 圧縮品質を指定します（JPEG 圧縮を使用する場合）。 |
| [getPdfCompliance()](#getPdfCompliance--) | PDF 準拠性を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | 文書アウトラインのどのレベルでブックマークオブジェクトを表示するかを指定します。 |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | PDF ファイルを表示したときに、文書アウトラインで展開して表示するレベル数を指定します。 |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | 文書アウトラインに含めるアウトライン項目のレベル数を指定します。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 画像の JPEG 圧縮品質を指定します（JPEG 圧縮を使用する場合）。 |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | PDF 準拠性を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


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
### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


文書アウトラインのどのレベルでブックマークオブジェクトを表示するかを指定します。0 - 表示しない。1 - 第1レベルで表示し、以下同様。デフォルトは 0 です。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


PDF ファイルを表示したときに、文書アウトラインで展開して表示するレベル数を指定します。0 - 文書アウトラインは展開されません。1 - 第1レベルの項目が展開され、以下同様。デフォルトは 0 です。

**Returns:**
int
### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


文書アウトラインに含めるアウトライン項目のレベル数を指定します。0 - アウトラインなし、1 - 1 レベルのアウトライン、以下同様。デフォルトは 0 です。

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


画像の JPEG 圧縮品質を指定します（JPEG 圧縮を使用する場合）。デフォルトは 95 です。

**Returns:**
int
### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


PDF 準拠性を取得します。

**Returns:**
int - PDF 準拠性。
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




### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


文書アウトラインのどのレベルでブックマークオブジェクトを表示するかを指定します。0 - 表示しない。1 - 第1レベルで表示し、以下同様。デフォルトは 0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


PDF ファイルを表示したときに、文書アウトラインで展開して表示するレベル数を指定します。0 - 文書アウトラインは展開されません。1 - 第1レベルの項目が展開され、以下同様。デフォルトは 0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


文書アウトラインに含めるアウトライン項目のレベル数を指定します。0 - アウトラインなし、1 - 1 レベルのアウトライン、以下同様。デフォルトは 0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


画像の JPEG 圧縮品質を指定します（JPEG 圧縮を使用する場合）。デフォルトは 95 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


PDF 準拠性を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | PDF 準拠性。 |

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

