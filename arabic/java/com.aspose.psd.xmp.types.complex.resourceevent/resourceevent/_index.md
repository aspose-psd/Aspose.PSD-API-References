---
title: "ResourceEvent"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحتوي على أبعاد كائن مرسوم."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

يحتوي على أبعاد كائن مرسوم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | يُنشئ مثيلاً جديدًا للفئة  ResourceEvent . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | يضيف المفتاح المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | يحصل الإجراء. |
| [getActionDate()](#getActionDate--) | يحصل أو يضبط تاريخ الإجراء. |
| [getChanged()](#getChanged--) | يحصل على القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الحدث السابق. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | يحصل على قيمة xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | يحصل على URI مساحة الاسم الافتراضية. |
| [getParameters()](#getParameters--) | يحصل أو يضبط الوصف الإضافي للإجراء. |
| [getPrefix()](#getPrefix--) | يحصل على البادئة. |
| [getSofwareAgentName()](#getSofwareAgentName--) | يحصل أو يضبط اسم وكيل البرنامج. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على القيمة النصية المحتواة بتنسيق XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | يضبط الإجراء. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | يحصل أو يضبط تاريخ الإجراء. |
| [setChanged(String value)](#setChanged-java.lang.String-) | يضبط القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الحدث السابق. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | يحصل أو يضبط قيمة xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | يحصل أو يضبط الوصف الإضافي للإجراء. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | يحصل أو يضبط اسم وكيل البرنامج. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


يُنشئ مثيلاً جديدًا للفئة  ResourceEvent .

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


يضيف المفتاح المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | تمثيل السلسلة للمفتاح الذي يتم التعرف عليه مع القيمة المضافة. |
| القيمة | java.lang.Object | القيمة التي سيتم الإضافة إليها. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public String getAction()
```


يحصل الإجراء.

القيم المعرفة هي: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. يجب أن تكون القيم الجديدة أفعالًا في صيغة الماضي.

**Returns:**
java.lang.String - الإجراء.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


يحصل أو يضبط تاريخ الإجراء.

**Returns:**
java.util.Date - تاريخ الإجراء.
### getChanged() {#getChanged--}
```
public String getChanged()
```


يحصل على القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الحدث السابق.

**Returns:**
java.lang.String - القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الحدث السابق.
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


يحصل على قيمة xmpMM:InstanceId.

**Returns:**
java.util.UUID - قيمة xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


يحصل على URI مساحة الاسم الافتراضية.

**Returns:**
java.lang.String - مساحة الاسم الافتراضية URI.
### getParameters() {#getParameters--}
```
public String getParameters()
```


يحصل أو يضبط الوصف الإضافي للإجراء.

القيمة: الوصف الإضافي للإجراء.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


يحصل على البادئة.

**Returns:**
java.lang.String - البادئة.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


يحصل أو يضبط اسم وكيل البرنامج.

**Returns:**
java.lang.String - اسم وكيل البرنامج.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يحصل على القيمة النصية المحتواة بتنسيق XMP.

**Returns:**
java.lang.String - يُرجِع القيمة النصية المحتواة بتنسيق XMP.
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


يضبط الإجراء.

القيم المعرفة هي: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. يجب أن تكون القيم الجديدة أفعالًا في صيغة الماضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | الإجراء. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


يحصل أو يضبط تاريخ الإجراء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Date | تاريخ الإجراء. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


يضبط القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الحدث السابق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القائمة المفصولة بفواصل منقوطة لأجزاء المورد التي تم تغييرها منذ تاريخ الحدث السابق. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


يحصل أو يضبط قيمة xmpMM:InstanceId.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.UUID | قيمة xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


يحصل أو يضبط الوصف الإضافي للإجراء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | الوصف الإضافي للإجراء. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


يحصل أو يضبط اسم وكيل البرنامج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | اسم وكيل البرنامج. |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

