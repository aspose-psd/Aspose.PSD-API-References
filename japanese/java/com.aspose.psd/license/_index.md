---
title: "License"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "コンポーネントのライセンス付与のためのメソッドを提供します。"
type: docs
weight: 65
url: /ja/java/com.aspose.psd/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

コンポーネントのライセンス付与のためのメソッドを提供します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [License()](#License--) | このクラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrorCodeMessages()](#getErrorCodeMessages--) | エラーコードメッセージを取得します。 |
| [getRenewSubscriptionStartMessage()](#getRenewSubscriptionStartMessage--) | サブスクリプション更新開始メッセージを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isLicensed_internalized()](#isLicensed-internalized--) | 製品がライセンスされているかどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLicense()](#removeLicense--) |  |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | コンポーネントにライセンスを付与します。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを付与します。 |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | コンポーネントにライセンスを付与します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


このクラスの新しいインスタンスを初期化します。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorCodeMessages() {#getErrorCodeMessages--}
```
public static ByteObjDictionary<String> getErrorCodeMessages()
```


エラーコードメッセージを取得します。

値: エラーコードメッセージ。

**Returns:**
com.aspose.java.optimization.maps.ByteObjDictionary<java.lang.String> - エラーコードメッセージ。
### getRenewSubscriptionStartMessage() {#getRenewSubscriptionStartMessage--}
```
public static String getRenewSubscriptionStartMessage()
```


サブスクリプション更新開始メッセージを取得します。

値: サブスクリプション更新開始メッセージ。

**Returns:**
java.lang.String - 更新サブスクリプション開始メッセージ。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLicensed_internalized() {#isLicensed-internalized--}
```
public static boolean isLicensed_internalized()
```


製品がライセンスされているかどうかを示す値を取得します。

**Returns:**
boolean -  製品がライセンスされている場合は true、そうでない場合は false 。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeLicense() {#removeLicense--}
```
public static void removeLicense()
```




### setLicense(File licenseFile) {#setLicense-java.io.File-}
```
public void setLicense(File licenseFile)
```


コンポーネントにライセンスを付与します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licenseFile | java.io.File | ファイルパス名の表現 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


コンポーネントにライセンスを付与します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | ライセンスを含むストリーム。 |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


コンポーネントにライセンスを付与します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licenseName | java.lang.String | 完全なファイル名または短いファイル名を使用できます。空文字列を使用して評価モードに切り替えます。 |

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

