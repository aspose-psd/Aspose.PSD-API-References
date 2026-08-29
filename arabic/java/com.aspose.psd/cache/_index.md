---
title: "Cache"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحتوي على إعدادات الذاكرة المؤقتة."
type: docs
weight: 14
url: /ar/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

يحتوي على إعدادات الذاكرة المؤقتة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | يحصل على عدد البايتات المخصصة على القرص. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | يحصل على عدد البايتات المخصصة في الذاكرة. |
| [getCacheFolder()](#getCacheFolder--) | يحصل على مجلد الذاكرة المؤقتة. |
| [getCacheType()](#getCacheType--) | يحصل على أو يضبط مخطط التخزين المؤقت المستخدم. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | يحصل على قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | يحصل على الحد الأقصى المتاح لمساحة القرص للتخزين المؤقت. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | يحصل على الحد الأقصى المتاح للذاكرة للتخزين المؤقت في الذاكرة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | يضبط مجلد التخزين المؤقت. |
| [setCacheType(int value)](#setCacheType-int-) | يضبط مخطط التخزين المؤقت المستخدم. |
| [setDefaults()](#setDefaults--) | يضبط إعدادات التخزين المؤقت إلى القيم الافتراضية. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | يضبط قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | يضبط الحد الأقصى المتاح لمساحة القرص للتخزين المؤقت. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | يضبط الحد الأقصى المتاح للذاكرة للتخزين المؤقت في الذاكرة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


يحصل على عدد البايتات المخصصة على القرص.

**Returns:**
long - عدد البايتات المخصصة على القرص.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


يحصل على عدد البايتات المخصصة في الذاكرة.

**Returns:**
long - عدد البايتات المخصصة في الذاكرة.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


يحصل على مجلد الذاكرة المؤقتة.

**Returns:**
java.lang.String - مجلد التخزين المؤقت.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


يحصل على أو يضبط مخطط التخزين المؤقت المستخدم.

**Returns:**
int - مخطط التخزين المؤقت المستخدم.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExactReallocateOnly() {#getExactReallocateOnly--}
```
public static boolean getExactReallocateOnly()
```


يحصل على قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة، يجب أن يكون الأداء أعلى.

**Returns:**
boolean -  true  إذا كانت إعادة التخصيص دقيقة؛ وإلا،  false .

ستقوم إعادة التخصيص الدقيقة بإعادة تخصيص الذاكرة الإضافية فقط حتى الحد الأعلى المحدد. عند تمرير الحد الأعلى للذاكرة أثناء إعادة التخصيص، سيتم نسخ البيانات المخزنة مؤقتًا إلى القرص إذا كان ذلك ممكنًا. عند تمرير الحد الأعلى لذاكرة القرص أثناء إعادة التخصيص، يتم إلقاء الاستثناء المناسب. يجب أن يكون الأداء أعلى إذا تم إيقاف هذا الخيار حيث لن يتم إجراء نسخ إضافي إذا كان ذلك ممكنًا، ومع ذلك قد يؤدي ذلك أيضًا إلى تجاوز الحدود العليا المحددة للذاكرة أو القرص.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


يحصل على الحد الأقصى المتاح لمساحة القرص للتخزين المؤقت. القيمة المحددة هي عدد الميغابايت.

**Returns:**
int - الحد الأقصى المتاح لمساحة القرص للتخزين المؤقت.

القيمة 0 ستستهلك كل الذاكرة المتاحة وتعمل كعدم وجود حد أعلى.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


يحصل على الحد الأقصى المتاح للذاكرة للتخزين المؤقت في الذاكرة. القيمة المحددة هي عدد الميغابايت.

**Returns:**
int - الحد الأقصى للذاكرة للتخزين المؤقت.

القيمة 0 ستستهلك كل الذاكرة المتاحة وتعمل كعدم وجود حد أعلى.
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




### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


يضبط مجلد التخزين المؤقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | مجلد التخزين المؤقت. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


يضبط مخطط التخزين المؤقت المستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | مخطط التخزين المؤقت المستخدم. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


يضبط إعدادات التخزين المؤقت إلى القيم الافتراضية.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان إعادة التخصيص يجب أن تكون دقيقة أم لا. إذا كانت إعادة التخصيص غير دقيقة يجب أن تكون الأداء أعلى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | صحيح إذا كانت إعادة التخصيص دقيقة؛ وإلا، خطأ. |

ستقوم إعادة التخصيص الدقيقة بإعادة تخصيص الذاكرة الإضافية فقط حتى الحد الأعلى المحدد. عند تمرير الحد الأعلى للذاكرة داخل الذاكرة أثناء إعادة التخصيص، سيتم نسخ البيانات المخزنة مؤقتًا إلى القرص إذا أمكن. عند تمرير الحد الأعلى لذاكرة القرص أثناء إعادة التخصيص، يتم إلقاء الاستثناء المناسب. يجب أن يكون الأداء أعلى إذا تم إيقاف هذا الخيار لأنه لن يتم تنفيذ نسخ إضافي إذا كان ذلك ممكنًا، ومع ذلك قد يؤدي ذلك أيضًا إلى تجاوز الحدود العليا المحددة للذاكرة أو القرص. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


يضبط الحد الأقصى للمساحة المتاحة على القرص للتخزين المؤقت. القيمة المحددة هي عدد الميغابايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | الحد الأقصى للمساحة المتاحة على القرص للتخزين المؤقت. |

القيمة 0 ستستهلك كل الذاكرة المتاحة وتعمل كعدم وجود حد أعلى. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


يضبط الحد الأقصى للذاكرة المتاحة للتخزين المؤقت في الذاكرة. القيمة المحددة هي عدد الميغابايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | الحد الأقصى للذاكرة للتخزين المؤقت. |

القيمة 0 ستستهلك كل الذاكرة المتاحة وتعمل كعدم وجود حد أعلى. |

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

