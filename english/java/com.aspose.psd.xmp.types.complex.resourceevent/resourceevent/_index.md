---
title: ResourceEvent
second_title: Aspose.PSD for Java API Reference
description: Containing dimensions for a drawn object.
type: docs
weight: 10
url: /java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Containing dimensions for a drawn object.
## Constructors

| Constructor | Description |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Initializes a new instance of the  ResourceEvent  class. |
## Methods

| Method | Description |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Adds the specified key. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Gets action. |
| [getActionDate()](#getActionDate--) | Gets or sets the action date. |
| [getChanged()](#getChanged--) | Gets the semicolon-delimited list of the parts of the resource that were changed since the previous event history. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Gets value of the xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the default namespace URI. |
| [getParameters()](#getParameters--) | Gets or sets the additional description of the action. |
| [getPrefix()](#getPrefix--) | Gets the prefix. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Gets or sets the software agent name. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Sets action. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Gets or sets the action date. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Sets the semicolon-delimited list of the parts of the resource that were changed since the previous event history. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Gets or sets value of the xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Gets or sets the additional description of the action. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Gets or sets the software agent name. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Initializes a new instance of the  ResourceEvent  class.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Adds the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | java.lang.Object | The value to add to. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public String getAction()
```


Gets action.

Defined values are: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. New values should be verbs in the past tense.

**Returns:**
java.lang.String - The action.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Gets or sets the action date.

**Returns:**
java.util.Date - The action date.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Gets the semicolon-delimited list of the parts of the resource that were changed since the previous event history.

**Returns:**
java.lang.String - The semicolon-delimited list of the parts of the resource that were changed since the previous event history.
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


Gets value of the xmpMM:InstanceId.

**Returns:**
java.util.UUID - The value of the xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Gets the default namespace URI.

**Returns:**
java.lang.String - The default namespace URI.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Gets or sets the additional description of the action.

Value: The additional description of the action.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Gets the prefix.

**Returns:**
java.lang.String - The prefix.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Gets or sets the software agent name.

**Returns:**
java.lang.String - The software agent name.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
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


Sets action.

Defined values are: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. New values should be verbs in the past tense.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The action. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Gets or sets the action date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The action date. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Sets the semicolon-delimited list of the parts of the resource that were changed since the previous event history.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The semicolon-delimited list of the parts of the resource that were changed since the previous event history. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Gets or sets value of the xmpMM:InstanceId.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID | The value of the xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Gets or sets the additional description of the action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The additional description of the action. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Gets or sets the software agent name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The software agent name. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

