---
title: "IPlacedLayerResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يعرّف واجهة IPlacedLayerResource التي تحتوي على معلومات حول طبقة موضوعة في ملف PSD."
type: docs
weight: 17
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

يعرّف واجهة IPlacedLayerResource التي تحتوي على معلومات حول طبقة موضوعة في ملف PSD. هي واجهة توصيفية تُستخدم لتحديد موارد PlLd و Sold و Sole في صور Adobe\ufffd Photoshop\ufffd. تُستخدم لدعم طبقات الكائن الذكي في صور Adobe\ufffd Photoshop\ufffd.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | يحصل أو يضبط سياسة إلغاء التنعيم للطبقة الموضوعة في صورة PSD. |
| [getBottom()](#getBottom--) | يحصل أو يضبط موقع القاع للطبقة الموضوعة في صورة PSD. |
| [getBounds()](#getBounds--) | يحصل أو يضبط حدود الطبقة الموضوعة في ملف PSD. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | يحصل أو يضبط وحدة القياس لنقاط الشبكة الأفقية. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [getItems()](#getItems--) | يحصل أو يضبط عناصر الالتواء. |
| [getLeft()](#getLeft--) | يحصل أو يضبط موقع اليسار للطبقة الموضوعة في ملف PSD. |
| [getPageNumber()](#getPageNumber--) | يحصل أو يضبط رقم الصفحة للطبقة الموضوعة في ملف PSD. |
| [getPerspective()](#getPerspective--) | يحصل أو يضبط قيمة المنظور للطبقة الموضوعة في ملف PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | يحصل أو يضبط القيمة الأخرى للمنظور للطبقة الموضوعة في ملف PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | يحصل أو يضبط نوع الطبقة الموضوعة في ملف PSD. |
| [getRight()](#getRight--) | يحصل أو يضبط موقع اليمين للطبقة الموضوعة في ملف PSD. |
| [getTop()](#getTop--) | يحصل أو يضبط موقع الأعلى للطبقة الموضوعة في صورة PSD. |
| [getTotalPages()](#getTotalPages--) | يحصل أو يضبط إجمالي عدد الصفحات للطبقة الموضوعة في ملف PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل أو يضبط مصفوفة التحويل للطبقة الموضوعة في ملف PSD. |
| [getUOrder()](#getUOrder--) | يحصل أو يضبط قيمة ترتيب U للطبقة الموضوعة في ملف PSD. |
| [getUniqueId()](#getUniqueId--) | يحصل أو يعيّن المعرف العالمي الفريد للطبقة الموضوعة أو طبقة الكائن الذكي في صورة PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | يحصل أو يعيّن قيمة ترتيب V للطبقة الموضوعة في ملف PSD. |
| [getValue()](#getValue--) | يحصل أو يعيّن قيمة warp للطبقة الموضوعة في صورة PSD. |
| [getVersion()](#getVersion--) | يحصل على إصدار الطبقة الموضوعة في ملف PSD، عادةً 3-5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | يحصل أو يعيّن وحدة القياس لنقاط الشبكة العمودية. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [isCustom()](#isCustom--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان نمط warp لهذا الكائن مخصصًا. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | يحصل أو يضبط سياسة إلغاء التنعيم للطبقة الموضوعة في صورة PSD. |
| [setBottom(double value)](#setBottom-double-) | يحصل أو يضبط موقع القاع للطبقة الموضوعة في صورة PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | يحصل أو يضبط حدود الطبقة الموضوعة في ملف PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان نمط warp لهذا الكائن مخصصًا. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | يحصل أو يضبط وحدة القياس لنقاط الشبكة الأفقية. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | يحصل أو يضبط عناصر الالتواء. |
| [setLeft(double value)](#setLeft-double-) | يحصل أو يضبط موقع اليسار للطبقة الموضوعة في ملف PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | يحصل أو يضبط رقم الصفحة للطبقة الموضوعة في ملف PSD. |
| [setPerspective(double value)](#setPerspective-double-) | يحصل أو يضبط قيمة المنظور للطبقة الموضوعة في ملف PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | يحصل أو يضبط القيمة الأخرى للمنظور للطبقة الموضوعة في ملف PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | يحصل أو يضبط نوع الطبقة الموضوعة في ملف PSD. |
| [setRight(double value)](#setRight-double-) | يحصل أو يضبط موقع اليمين للطبقة الموضوعة في ملف PSD. |
| [setTop(double value)](#setTop-double-) | يحصل أو يضبط موقع الأعلى للطبقة الموضوعة في صورة PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | يحصل أو يضبط إجمالي عدد الصفحات للطبقة الموضوعة في ملف PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | يحصل أو يضبط مصفوفة التحويل للطبقة الموضوعة في ملف PSD. |
| [setUOrder(int value)](#setUOrder-int-) | يحصل أو يضبط قيمة ترتيب U للطبقة الموضوعة في ملف PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | يحصل أو يعيّن المعرف العالمي الفريد للطبقة الموضوعة أو طبقة الكائن الذكي في صورة PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | يحصل أو يعيّن قيمة ترتيب V للطبقة الموضوعة في ملف PSD. |
| [setValue(double value)](#setValue-double-) | يحصل أو يعيّن قيمة warp للطبقة الموضوعة في صورة PSD. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | يحصل أو يعيّن وحدة القياس لنقاط الشبكة العمودية. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


يحصل أو يضبط سياسة إلغاء التنعيم للطبقة الموضوعة في صورة PSD.

القيمة: سياسة مكافحة التمويه للطبقة الموضوعة.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


يحصل أو يضبط موقع القاع للطبقة الموضوعة في صورة PSD.

القيمة: الموقع السفلي للطبقة الموضوعة.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


يحصل أو يضبط حدود الطبقة الموضوعة في ملف PSD.

القيمة: حدود الطبقة الموضوعة.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


يحصل أو يضبط وحدة القياس لنقاط الشبكة الأفقية.

القيمة: وحدة قياس نقاط الشبكة الأفقية.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD.

القيمة: نقاط الشبكة الأفقية للطبقة الموضوعة.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


يحصل أو يضبط عناصر الالتواء.

القيمة: عناصر warp.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


يحصل أو يضبط موقع اليسار للطبقة الموضوعة في ملف PSD.

القيمة: الموقع الأيسر للطبقة الموضوعة.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


يحصل أو يضبط رقم الصفحة للطبقة الموضوعة في ملف PSD.

القيمة: رقم الصفحة للطبقة الموضوعة.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


يحصل أو يضبط قيمة المنظور للطبقة الموضوعة في ملف PSD.

القيمة: قيمة المنظور للطبقة الموضوعة.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


يحصل أو يضبط القيمة الأخرى للمنظور للطبقة الموضوعة في ملف PSD.

القيمة: قيمة المنظور الأخرى للطبقة الموضوعة.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


يحصل أو يضبط نوع الطبقة الموضوعة في ملف PSD.

القيمة: نوع الطبقة الموضوعة.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


يحصل أو يضبط موقع اليمين للطبقة الموضوعة في ملف PSD.

القيمة: الموقع الأيمن للطبقة الموضوعة.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


يحصل أو يضبط موقع الأعلى للطبقة الموضوعة في صورة PSD.

القيمة: الموقع العلوي للطبقة الموضوعة.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


يحصل أو يضبط إجمالي عدد الصفحات للطبقة الموضوعة في ملف PSD.

القيمة: إجمالي الصفحات للطبقة الموضوعة.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


يحصل أو يضبط مصفوفة التحويل للطبقة الموضوعة في ملف PSD.

القيمة: مصفوفة التحويل للطبقة الموضوعة.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


يحصل أو يضبط قيمة ترتيب U للطبقة الموضوعة في ملف PSD.

القيمة: قيمة ترتيب U للطبقة الموضوعة.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


يحصل أو يعيّن المعرف العالمي الفريد للطبقة الموضوعة أو طبقة الكائن الذكي في صورة PSD.

القيمة: المعرف الفريد للطبقة الموضوعة.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


يحصل أو يعيّن قيمة ترتيب V للطبقة الموضوعة في ملف PSD.

القيمة: قيمة ترتيب V للطبقة الموضوعة.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


يحصل أو يعيّن قيمة warp للطبقة الموضوعة في صورة PSD.

القيمة: قيمة التشويه للطبقة الموضوعة.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


يحصل على إصدار الطبقة الموضوعة في ملف PSD، عادةً 3-5.

القيمة: إصدار الطبقة الموضوعة أو طبقة الكائن الذكي.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


يحصل أو يعيّن وحدة القياس لنقاط الشبكة العمودية.

القيمة: وحدة القياس لنقاط الشبكة العمودية.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD.

القيمة: نقاط الشبكة الأفقية للطبقة الموضوعة.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان نمط التشويه لهذا الكائن مخصصًا. إذا كان true فإنه يحتوي على نقاط الشبكة. إذا تم تعيينه إلى false فإنه يمسح نقاط الشبكة.

القيمة:  true  إذا كان مورد الطبقة الموضوعة أو طبقة الكائن الذكي يحتوي على نمط مخصص؛ وإلا،  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


يحصل أو يضبط سياسة إلغاء التنعيم للطبقة الموضوعة في صورة PSD.

القيمة: سياسة مكافحة التمويه للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


يحصل أو يضبط موقع القاع للطبقة الموضوعة في صورة PSD.

القيمة: الموقع السفلي للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


يحصل أو يضبط حدود الطبقة الموضوعة في ملف PSD.

القيمة: حدود الطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان نمط التشويه لهذا الكائن مخصصًا. إذا كان true فإنه يحتوي على نقاط الشبكة. إذا تم تعيينه إلى false فإنه يمسح نقاط الشبكة.

القيمة:  true  إذا كان مورد الطبقة الموضوعة أو طبقة الكائن الذكي يحتوي على نمط مخصص؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


يحصل أو يضبط وحدة القياس لنقاط الشبكة الأفقية.

القيمة: وحدة قياس نقاط الشبكة الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD.

القيمة: نقاط الشبكة الأفقية للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


يحصل أو يضبط عناصر الالتواء.

القيمة: عناصر warp.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


يحصل أو يضبط موقع اليسار للطبقة الموضوعة في ملف PSD.

القيمة: الموقع الأيسر للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


يحصل أو يضبط رقم الصفحة للطبقة الموضوعة في ملف PSD.

القيمة: رقم الصفحة للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


يحصل أو يضبط قيمة المنظور للطبقة الموضوعة في ملف PSD.

القيمة: قيمة المنظور للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


يحصل أو يضبط القيمة الأخرى للمنظور للطبقة الموضوعة في ملف PSD.

القيمة: قيمة المنظور الأخرى للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


يحصل أو يضبط نوع الطبقة الموضوعة في ملف PSD.

القيمة: نوع الطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


يحصل أو يضبط موقع اليمين للطبقة الموضوعة في ملف PSD.

القيمة: الموقع الأيمن للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


يحصل أو يضبط موقع الأعلى للطبقة الموضوعة في صورة PSD.

القيمة: الموقع العلوي للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


يحصل أو يضبط إجمالي عدد الصفحات للطبقة الموضوعة في ملف PSD.

القيمة: إجمالي الصفحات للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


يحصل أو يضبط مصفوفة التحويل للطبقة الموضوعة في ملف PSD.

القيمة: مصفوفة التحويل للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


يحصل أو يضبط قيمة ترتيب U للطبقة الموضوعة في ملف PSD.

القيمة: قيمة ترتيب U للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


يحصل أو يعيّن المعرف العالمي الفريد للطبقة الموضوعة أو طبقة الكائن الذكي في صورة PSD.

القيمة: المعرف الفريد للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


يحصل أو يعيّن قيمة ترتيب V للطبقة الموضوعة في ملف PSD.

القيمة: قيمة ترتيب V للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


يحصل أو يعيّن قيمة warp للطبقة الموضوعة في صورة PSD.

القيمة: قيمة التشويه للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


يحصل أو يعيّن وحدة القياس لنقاط الشبكة العمودية.

القيمة: وحدة القياس لنقاط الشبكة العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD.

القيمة: نقاط الشبكة الأفقية للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

