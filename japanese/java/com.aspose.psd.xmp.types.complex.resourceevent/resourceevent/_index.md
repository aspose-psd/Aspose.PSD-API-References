---
title: "ResourceEvent"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "描画されたオブジェクトの寸法を含む。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

描画されたオブジェクトの寸法を含む。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | 新しい ResourceEvent クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 指定されたキーを追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | アクションを取得します。 |
| [getActionDate()](#getActionDate--) | アクションの日付を取得または設定します。 |
| [getChanged()](#getChanged--) | 前回のイベント履歴以降に変更されたリソースの部分のセミコロン区切りリストを取得します。 |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | xmpMM:InstanceId の値を取得します。 |
| [getNamespaceUri()](#getNamespaceUri--) | デフォルトの名前空間 URI を取得します。 |
| [getParameters()](#getParameters--) | アクションの追加説明を取得または設定します。 |
| [getPrefix()](#getPrefix--) | プレフィックスを取得します。 |
| [getSofwareAgentName()](#getSofwareAgentName--) | ソフトウェアエージェント名を取得または設定します。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 形式で含まれる文字列値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | アクションを設定します。 |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | アクションの日付を取得または設定します。 |
| [setChanged(String value)](#setChanged-java.lang.String-) | 前回のイベント履歴以降に変更されたリソースの部分のセミコロン区切りリストを設定します。 |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | xmpMM:InstanceId の値を取得または設定します。 |
| [setParameters(String value)](#setParameters-java.lang.String-) | アクションの追加説明を取得または設定します。 |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | ソフトウェアエージェント名を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


新しい ResourceEvent クラスのインスタンスを初期化します。

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


指定されたキーを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 追加された値で識別されるキーの文字列表現です。 |
| 値 | java.lang.Object | 追加する対象の値。 |

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
### getAction() {#getAction--}
```
public String getAction()
```


アクションを取得します。

定義された値は: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved です。新しい値は過去形の動詞である必要があります。

**Returns:**
java.lang.String - アクション。
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


アクションの日付を取得または設定します。

**Returns:**
java.util.Date - アクションの日付。
### getChanged() {#getChanged--}
```
public String getChanged()
```


前回のイベント履歴以降に変更されたリソースの部分のセミコロン区切りリストを取得します。

**Returns:**
java.lang.String - 前回のイベント履歴以降に変更されたリソースの部分のセミコロン区切りリスト。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


xmpMM:InstanceId の値を取得します。

**Returns:**
java.util.UUID - xmpMM:InstanceId の値。
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


デフォルトの名前空間 URI を取得します。

**Returns:**
java.lang.String - デフォルトの名前空間 URI。
### getParameters() {#getParameters--}
```
public String getParameters()
```


アクションの追加説明を取得または設定します。

Value: アクションの追加説明。

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


プレフィックスを取得します。

**Returns:**
java.lang.String - プレフィックス。
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


ソフトウェアエージェント名を取得または設定します。

**Returns:**
java.lang.String - ソフトウェアエージェント名。
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 形式で含まれる文字列値を取得します。

**Returns:**
java.lang.String - XMP 形式で含まれる文字列値を返します。
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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


アクションを設定します。

定義された値は: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved です。新しい値は過去形の動詞である必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | アクション。 |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


アクションの日付を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date | アクションの日付。 |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


前回のイベント履歴以降に変更されたリソースの部分のセミコロン区切りリストを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 前回のイベント履歴以降に変更されたリソースの部分のセミコロン区切りリスト。 |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


xmpMM:InstanceId の値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.UUID | xmpMM:InstanceId の値。 |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


アクションの追加説明を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | アクションの追加説明。 |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


ソフトウェアエージェント名を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | ソフトウェアエージェント名。 |

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

