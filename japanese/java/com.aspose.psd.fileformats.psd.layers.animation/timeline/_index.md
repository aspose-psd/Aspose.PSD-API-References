---
title: "タイムライン"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "タイムラインオプションモデル。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

タイムラインオプションモデル。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Timeline()](#Timeline--) | 新しい [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | 現在のタイムライン値を入力 PsdImage に適用します ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | AFSt 値を取得または設定します。 |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | アクティブフレームインデックスを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | IDでフレームを取得します。 |
| [getFrames()](#getFrames--) | フレームのリストを取得します。 |
| [getFramesList()](#getFramesList--) | フレームのリストを取得します。 |
| [getFsID()](#getFsID--) | FsID の値を取得または設定します。 |
| [getLoopesCount()](#getLoopesCount--) | ループ回数を取得または設定します。 |
| [getPsdImage()](#getPsdImage--) | この [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) の PsdImage を取得または設定します ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | 指定されたストリームに、保存オプションに従って指定された形式で PsdImage と Timeline のデータを保存します。 |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | 指定されたファイル場所に、保存オプションに従って指定された形式で PsdImage と Timeline のデータを保存します。 |
| [setAFSt(int value)](#setAFSt-int-) | AFSt 値を取得または設定します。 |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | アクティブフレームインデックスを取得または設定します。 |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | フレームのリストを取得します。 |
| [setFsID(int value)](#setFsID-int-) | FsID の値を取得または設定します。 |
| [setLoopesCount(int value)](#setLoopesCount-int-) | ループ回数を取得または設定します。 |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | この [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) の PsdImage を取得または設定します ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | アクティブフレームを対象のフレームに切り替えます。 |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | 現在のタイムライン値を入力 PsdImage に適用します ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


新しい [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) クラスのインスタンスを初期化します。

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


現在のタイムライン値を入力 PsdImage に適用します ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | psd 画像です。 |

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
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


AFSt 値を取得または設定します。

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


アクティブフレームインデックスを取得または設定します。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrame(int frameId) {#getFrame-int-}
```
public Frame getFrame(int frameId)
```


IDでフレームを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| frameId | int | フレーム ID です。 |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


フレームのリストを取得します。

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


フレームのリストを取得します。

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


FsID の値を取得または設定します。

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


ループ回数を取得または設定します。

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


この [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) の PsdImage を取得または設定します ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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




### save(System.IO.Stream outputStream, ImageOptionsBase options) {#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-}
```
public void save(System.IO.Stream outputStream, ImageOptionsBase options)
```


指定されたストリームに、保存オプションに従って指定された形式で PsdImage と Timeline のデータを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | 出力ストリームです。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | オプション。 |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


指定されたファイル場所に、保存オプションに従って指定された形式で PsdImage と Timeline のデータを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ファイルパスです。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | オプション。 |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


AFSt 値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


アクティブフレームインデックスを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


フレームのリストを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


FsID の値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


ループ回数を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


この [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) の PsdImage を取得または設定します ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


アクティブフレームを対象のフレームに切り替えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| targetActiveFrameIndex | int | 対象フレームインデックスです。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFrameFromPsdImage_internalized(int frameIndex) {#updateFrameFromPsdImage-internalized-int-}
```
public void updateFrameFromPsdImage_internalized(int frameIndex)
```


現在のタイムライン値を入力 PsdImage に適用します ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| frameIndex | int | レイヤー状態を更新するフレームインデックスです。 |

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

