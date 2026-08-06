---
title: "ResourceEvent"
second_title: "Aspose.PSD 的 Java API 参考"
description: "包含已绘制对象的尺寸。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

包含已绘制对象的尺寸。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | 初始化 ResourceEvent 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 添加指定的键。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 获取操作。 |
| [getActionDate()](#getActionDate--) | 获取或设置操作日期。 |
| [getChanged()](#getChanged--) | 获取自上一次事件历史以来已更改的资源部件的分号分隔列表。 |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | 获取 xmpMM:InstanceId 的值。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取默认命名空间 URI。 |
| [getParameters()](#getParameters--) | 获取或设置操作的附加描述。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getSofwareAgentName()](#getSofwareAgentName--) | 获取或设置软件代理名称。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | 设置操作。 |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | 获取或设置操作日期。 |
| [setChanged(String value)](#setChanged-java.lang.String-) | 设置自上一次事件历史以来已更改的资源部件的分号分隔列表。 |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | 获取或设置 xmpMM:InstanceId 的值。 |
| [setParameters(String value)](#setParameters-java.lang.String-) | 获取或设置操作的附加描述。 |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | 获取或设置软件代理名称。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


初始化 ResourceEvent 类的新实例。

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


添加指定的键。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | key 的字符串表示形式，用于标识已添加的值。 |
| 值 | java.lang.Object | 要添加到的值。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public String getAction()
```


获取操作。

定义的值包括：converted、copied、created、cropped、edited、filtered、formatted、version\_updated、printed、published、managed、produced、resized、saved。新值应使用过去式动词。

**Returns:**
java.lang.String - 操作。
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


获取或设置操作日期。

**Returns:**
java.util.Date - 操作日期。
### getChanged() {#getChanged--}
```
public String getChanged()
```


获取自上一次事件历史以来已更改的资源部件的分号分隔列表。

**Returns:**
java.lang.String - 自上一次事件历史以来已更改的资源部件的分号分隔列表。
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


获取 xmpMM:InstanceId 的值。

**Returns:**
java.util.UUID - xmpMM:InstanceId 的值。
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取默认命名空间 URI。

**Returns:**
java.lang.String - 默认的命名空间 URI。
### getParameters() {#getParameters--}
```
public String getParameters()
```


获取或设置操作的附加描述。

值：操作的附加描述。

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

**Returns:**
java.lang.String - 前缀。
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


获取或设置软件代理名称。

**Returns:**
java.lang.String - 软件代理名称。
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式的字符串值。
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


设置操作。

定义的值包括：converted、copied、created、cropped、edited、filtered、formatted、version\_updated、printed、published、managed、produced、resized、saved。新值应使用过去式动词。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 操作。 |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


获取或设置操作日期。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.Date | 操作日期。 |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


设置自上一次事件历史以来已更改的资源部件的分号分隔列表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 自上一次事件历史以来已更改的资源部件的分号分隔列表。 |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


获取或设置 xmpMM:InstanceId 的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID | xmpMM:InstanceId 的值。 |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


获取或设置操作的附加描述。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 操作的附加描述。 |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


获取或设置软件代理名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 软件代理的名称。 |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

