---
title: "PlLdResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يعرّف فئة PlLdResource التي تحتوي على معلومات حول طبقة موضوعة في ملف PSD."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource)
```
public class PlLdResource extends PlacedResource
```

يعرّف فئة PlLdResource التي تحتوي على معلومات حول طبقة موضوعة في ملف PSD. يُستخدم لدعم طبقات الكائن الذكي في صور Adobe® Photoshop®. تم استبداله بـ SoLdResource في Adobe® Photoshop® CS3.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PlLdResource()](#PlLdResource--) | يُنشئ مثيلاً جديدًا للفئة [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | اسم التشويه المخصص للمغلف |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | اسم فئة التشويه الافتراضية |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | اسم فئة التشويه الافتراضية |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | إصدار موصّف التشويه المتوقع |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | إصدار التشويه المتوقع |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | اسم المعرف الأفقي |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | اسم مفتاح نقاط الشبكة |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | اسم معرف الاتجاه |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | قيمة الإصدار المتوقعة |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | إصدار رأس PSB |
| [PsbResourceSignature](#PsbResourceSignature) | توقيع المورد الخاص بـ PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | إصدار رأس PSD |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | اسم معرف فئة النقطة النسبية |
| [ResourceSignature](#ResourceSignature) | توقيع المورد المشترك. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | حجم الـ double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | حجم الـ int |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | عدد قيم التحويل |
| [TypeToolKey](#TypeToolKey) | مفتاح معلومات أداة النوع. |
| [TypeValue_internalized](#TypeValue-internalized) | قيمة النوع المتوقعة |
| [UOrderKey_internalized](#UOrderKey-internalized) | مفتاح ترتيب u |
| [VOrderKey_internalized](#VOrderKey-internalized) | مفتاح ترتيب v |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | اسم المعرف العمودي |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | الاسم المخصص للتشويه |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | طول رأس التشويه. |
| [WarpKey_internalized](#WarpKey-internalized) | مفتاح التشويه. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | اسم عدم وجود التشويه |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | مفتاح منظور الالتواء |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | العنصر الآخر لمنظور الالتواء |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | مفتاح دوران الالتواء |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | مفتاح نمط الالتواء |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | مفتاح قيمة الالتواء |
| [ZeroChar_internalized](#ZeroChar-internalized) | الحرف الصفري. |
| [ventureLicense_internalized](#ventureLicense-internalized) | رخصة المشروع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | يؤكد أن القيمة الفعلية المحددة تساوي القيمة المتوقعة. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. |
| [create_internalized(PlaceResourceParams plLdResourceParams)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [create_internalized(System.Guid uniqueId, boolean isCustom)](#create-internalized-com.aspose.ms.System.Guid-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | يحصل أو يضبط سياسة إلغاء التنعيم للطبقة الموضوعة في صورة PSD. |
| [getBottom()](#getBottom--) | يحصل أو يضبط موقع القاع للطبقة الموضوعة في صورة PSD. |
| [getBounds()](#getBounds--) | يحصل أو يضبط حدود الطبقة الموضوعة في ملف PSD. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | يحصل أو يضبط نوع الوحدة الافتراضية للقيم المعينة مثل اليسار، الأعلى، اليمين، الأسفل، TransformMatrix. |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | يحصل أو يضبط وحدة القياس لنقاط الشبكة الأفقية. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [getItems()](#getItems--) | يحصل أو يضبط عناصر الالتواء. |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getLeft()](#getLeft--) | يحصل أو يضبط موقع اليسار للطبقة الموضوعة في ملف PSD. |
| [getLength()](#getLength--) | يحصل على طول مورد PlLd بالبايت. |
| [getPageNumber()](#getPageNumber--) | يحصل أو يضبط رقم الصفحة للطبقة الموضوعة في ملف PSD. |
| [getPerspective()](#getPerspective--) | يحصل أو يضبط قيمة المنظور للطبقة الموضوعة في ملف PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | يحصل أو يضبط القيمة الأخرى للمنظور للطبقة الموضوعة في ملف PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | يحصل أو يضبط نوع الطبقة الموضوعة في ملف PSD. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getRight()](#getRight--) | يحصل أو يضبط موقع اليمين للطبقة الموضوعة في ملف PSD. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [getTop()](#getTop--) | يحصل أو يضبط موقع الأعلى للطبقة الموضوعة في صورة PSD. |
| [getTotalPages()](#getTotalPages--) | يحصل أو يضبط إجمالي عدد الصفحات للطبقة الموضوعة في ملف PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | يحصل أو يضبط مصفوفة التحويل للطبقة الموضوعة في ملف PSD. |
| [getUOrder()](#getUOrder--) | يحصل أو يضبط قيمة ترتيب U للطبقة الموضوعة في ملف PSD. |
| [getUniqueId()](#getUniqueId--) | يحصل أو يضبط المعرف الفريد العالمي للطبقة الموضوعة في صورة PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | يحصل أو يعيّن قيمة ترتيب V للطبقة الموضوعة في ملف PSD. |
| [getValue()](#getValue--) | يحصل أو يعيّن قيمة warp للطبقة الموضوعة في صورة PSD. |
| [getVersion()](#getVersion--) | يحصل على إصدار الطبقة الموضوعة في ملف PSD، عادةً 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | يحصل أو يعيّن وحدة القياس لنقاط الشبكة العمودية. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | يحصل أو يعيّن معرف الفئة. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | يحصل أو يعيّن اسم فئة warp. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | يحصل أو يعيّن إصدار موصّف warp. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | عناصر الالتواء. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | يحصل أو يعيّن إصدار warp. |
| [get_Item(String index)](#get-Item-java.lang.String-) | يحصل على [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) في الفهرس المحدد. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على وحدات الحدود. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان نمط warp لهذا الكائن مخصصًا. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت اتجاهات الدوران لهذا الكائن أفقية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ مورد PlLD إلى حاوية الدفق المحددة. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | يحصل أو يضبط سياسة إلغاء التنعيم للطبقة الموضوعة في صورة PSD. |
| [setBottom(double value)](#setBottom-double-) | يحصل أو يضبط موقع القاع للطبقة الموضوعة في صورة PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | يحصل أو يضبط حدود الطبقة الموضوعة في ملف PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان نمط warp لهذا الكائن مخصصًا. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | يحصل أو يضبط نوع الوحدة الافتراضية للقيم المعينة مثل اليسار، الأعلى، اليمين، الأسفل، TransformMatrix. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | يحصل أو يضبط وحدة القياس لنقاط الشبكة الأفقية. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | يحصل أو يضبط عناصر الالتواء. |
| [setLeft(double value)](#setLeft-double-) | يحصل أو يضبط موقع اليسار للطبقة الموضوعة في ملف PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | يحصل أو يضبط رقم الصفحة للطبقة الموضوعة في ملف PSD. |
| [setPerspective(double value)](#setPerspective-double-) | يحصل أو يضبط قيمة المنظور للطبقة الموضوعة في ملف PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | يحصل أو يضبط القيمة الأخرى للمنظور للطبقة الموضوعة في ملف PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | يحصل أو يضبط نوع الطبقة الموضوعة في ملف PSD. |
| [setRight(double value)](#setRight-double-) | يحصل أو يضبط موقع اليمين للطبقة الموضوعة في ملف PSD. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت اتجاهات الدوران لهذا الكائن أفقية. |
| [setTop(double value)](#setTop-double-) | يحصل أو يضبط موقع الأعلى للطبقة الموضوعة في صورة PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | يحصل أو يضبط إجمالي عدد الصفحات للطبقة الموضوعة في ملف PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | يحصل أو يضبط مصفوفة التحويل للطبقة الموضوعة في ملف PSD. |
| [setUOrder(int value)](#setUOrder-int-) | يحصل أو يضبط قيمة ترتيب U للطبقة الموضوعة في ملف PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | يحصل أو يضبط المعرف الفريد العالمي للطبقة الموضوعة في صورة PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | يحصل أو يعيّن قيمة ترتيب V للطبقة الموضوعة في ملف PSD. |
| [setValue(double value)](#setValue-double-) | يحصل أو يعيّن قيمة warp للطبقة الموضوعة في صورة PSD. |
| [setVersion(int value)](#setVersion-int-) | يحصل على إصدار الطبقة الموضوعة في ملف PSD، عادةً 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | يحصل أو يعيّن وحدة القياس لنقاط الشبكة العمودية. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | يحصل أو يعيّن معرف الفئة. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | يحصل أو يعيّن اسم فئة warp. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | يحصل أو يعيّن إصدار موصّف warp. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | يحصل أو يعيّن إصدار warp. |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlLdResource() {#PlLdResource--}
```
public PlLdResource()
```


يُنشئ مثيلاً جديدًا للفئة [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource). تم تصميم هذا المُنشئ الافتراضي للاستخدام بواسطة PlLdResourceLoader. استخدم [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) لإنشاء فئات PlLdResource.

### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


اسم التشويه المخصص للمغلف

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


اسم فئة التشويه الافتراضية

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


اسم فئة التشويه الافتراضية

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


إصدار موصّف التشويه المتوقع

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


إصدار التشويه المتوقع

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


اسم المعرف الأفقي

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


اسم مفتاح نقاط الشبكة

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


اسم معرف الاتجاه

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


قيمة الإصدار المتوقعة

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


إصدار رأس PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


توقيع المورد الخاص بـ PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


إصدار رأس PSD

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


اسم معرف فئة النقطة النسبية

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


توقيع المورد المشترك.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


حجم الـ double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


حجم الـ int

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


عدد قيم التحويل

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


مفتاح معلومات أداة النوع.

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


قيمة النوع المتوقعة

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


مفتاح ترتيب u

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


مفتاح ترتيب v

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


اسم المعرف العمودي

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


الاسم المخصص للتشويه

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


طول رأس التشويه.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


مفتاح warp. أيضًا اسم الفئة الافتراضية warp.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


اسم عدم وجود التشويه

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


مفتاح منظور الالتواء

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


العنصر الآخر لمنظور الالتواء

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


مفتاح دوران الالتواء

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


مفتاح نمط الالتواء

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


مفتاح قيمة الالتواء

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


الحرف الصفري.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


رخصة المشروع.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


يؤكد أن القيمة الفعلية المحددة تساوي القيمة المتوقعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| actualValue | java.lang.Object | القيمة الفعلية. |
| expectedValue | java.lang.Object | القيمة المتوقعة. |
| message | java.lang.String | الرسالة. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. بعض الموارد غير معروفة حاليًا، لكن لدينا قائمة كاملة بالموارد الخاصة بـ PSB التي تغير سلوكها عند الحفظ. لذلك نحتاج إلى التحقق من ذلك في UnknownResource على الأقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | المفتاح. |

### create_internalized(PlaceResourceParams plLdResourceParams) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public static PlLdResource create_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource)
### create_internalized(System.Guid uniqueId, boolean isCustom) {#create-internalized-com.aspose.ms.System.Guid-boolean-}
```
public static PlLdResource create_internalized(System.Guid uniqueId, boolean isCustom)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid |  |
| isCustom | boolean |  |

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource)
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
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


يحصل أو يضبط سياسة إلغاء التنعيم للطبقة الموضوعة في صورة PSD.

القيمة: سياسة مكافحة التمويه للطبقة الموضوعة.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


يحصل أو يضبط موقع القاع للطبقة الموضوعة في صورة PSD.

القيمة: الموقع السفلي للطبقة الموضوعة.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


يحصل أو يضبط حدود الطبقة الموضوعة في ملف PSD.

القيمة: حدود الطبقة الموضوعة.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


يحصل أو يضبط نوع الوحدة الافتراضية للقيم المعينة مثل اليسار، الأعلى، اليمين، الأسفل، TransformMatrix.

القيمة: نوع وحدة القياس الافتراضية.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


يحصل أو يضبط وحدة القياس لنقاط الشبكة الأفقية.

القيمة: وحدة قياس نقاط الشبكة الأفقية.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD.

القيمة: نقاط الشبكة الأفقية للطبقة الموضوعة.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


يحصل أو يضبط عناصر الالتواء.

القيمة: عناصر warp.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


يحصل على مفتاح مورد الطبقة.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


يحصل أو يضبط موقع اليسار للطبقة الموضوعة في ملف PSD.

القيمة: الموقع الأيسر للطبقة الموضوعة.

**Returns:**
double
### getLength() {#getLength--}
```
public int getLength()
```


يحصل على طول مورد PlLd بالبايت.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


يحصل أو يضبط رقم الصفحة للطبقة الموضوعة في ملف PSD.

القيمة: رقم الصفحة للطبقة الموضوعة.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


يحصل أو يضبط قيمة المنظور للطبقة الموضوعة في ملف PSD.

القيمة: قيمة المنظور للطبقة الموضوعة.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


يحصل أو يضبط القيمة الأخرى للمنظور للطبقة الموضوعة في ملف PSD.

القيمة: قيمة المنظور الأخرى للطبقة الموضوعة.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


يحصل أو يضبط نوع الطبقة الموضوعة في ملف PSD.

القيمة: نوع الطبقة الموضوعة.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


يحصل على طول البادئة. القيمة الافتراضية هي 12 لموارد 8BIM و 16 لموارد 8B64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| psdVersion | int | إصدار PSD. |

**Returns:**
int - طول البادئة.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


يحصل أو يضبط موقع اليمين للطبقة الموضوعة في ملف PSD.

القيمة: الموقع الأيمن للطبقة الموضوعة.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل على توقيع مورد الطبقة.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


يحصل أو يضبط موقع الأعلى للطبقة الموضوعة في صورة PSD.

القيمة: الموقع العلوي للطبقة الموضوعة.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


يحصل أو يضبط إجمالي عدد الصفحات للطبقة الموضوعة في ملف PSD.

القيمة: إجمالي الصفحات للطبقة الموضوعة.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


يحصل أو يضبط مصفوفة التحويل للطبقة الموضوعة في ملف PSD.

القيمة: مصفوفة التحويل للطبقة الموضوعة.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


يحصل أو يضبط قيمة ترتيب U للطبقة الموضوعة في ملف PSD.

القيمة: قيمة ترتيب U للطبقة الموضوعة.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


يحصل أو يضبط المعرف الفريد العالمي للطبقة الموضوعة في صورة PSD.

القيمة: المعرف الفريد للطبقة الموضوعة.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


يحصل أو يعيّن قيمة ترتيب V للطبقة الموضوعة في ملف PSD.

القيمة: قيمة ترتيب V للطبقة الموضوعة.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


يحصل أو يعيّن قيمة warp للطبقة الموضوعة في صورة PSD.

القيمة: قيمة التشويه للطبقة الموضوعة.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


يحصل على إصدار الطبقة الموضوعة في ملف PSD، عادةً 3.

القيمة: إصدار الطبقة الموضوعة.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


يحصل أو يعيّن وحدة القياس لنقاط الشبكة العمودية.

القيمة: وحدة القياس لنقاط الشبكة العمودية.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD.

القيمة: نقاط الشبكة الأفقية للطبقة الموضوعة.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


يحصل أو يعيّن معرف الفئة.

القيمة: معرف الفئة.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


يحصل أو يعيّن اسم فئة warp.

القيمة: اسم فئة التشويه.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


يحصل أو يعيّن إصدار موصّف warp.

القيمة: إصدار موصّف التشويه.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


عناصر الالتواء.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


يحصل أو يعيّن إصدار warp.

القيمة: إصدار التشويه.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


يحصل على [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | java.lang.String | اسم المفتاح. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على وحدات الحدود.

القيمة:  true  إذا كان لهذا الكائن وحدات حدود؛ وإلا،  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initProreties_internalized(PlaceResourceParams plLdResourceParams) {#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public final void initProreties_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان نمط التشويه لهذا الكائن مخصصًا. إذا كان true فإنه يحتوي على نقاط الشبكة. إذا تم تعيينه إلى false فإنه يمسح نقاط الشبكة.

القيمة:  true  إذا كانت الطبقة الموضوعة ذات نمط مخصص؛ وإلا،  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


يحدد ما إذا كان المورد خاصًا بـ PSB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | مفتاح المورد. |

**Returns:**
boolean -  true  إذا كان المورد خاصًا بـ PSD؛ وإلا،  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB.

القيمة:  true  إذا كان هذا الكائن خاصًا بـ PSB؛ وإلا،  false .

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت اتجاهات الدوران لهذا الكائن أفقية.

القيمة:  true  إذا كان اتجاه الدوران أفقيًا؛ وإلا،  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


يحفظ مورد PlLD إلى حاوية الدفق المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ إليها. |
| psdVersion | int | إصدار PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


يحفظ رأس المورد المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| التوقيع | int | التوقيع. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


يحفظ توقيع الرأس، المعرف والطول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| التوقيع | int | التوقيع. |
| isLengthLong | boolean | إذا تم ضبطه على  true  يكون الطول طويلًا. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


يحصل أو يضبط سياسة إلغاء التنعيم للطبقة الموضوعة في صورة PSD.

القيمة: سياسة مكافحة التمويه للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


يحصل أو يضبط موقع القاع للطبقة الموضوعة في صورة PSD.

القيمة: الموقع السفلي للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


يحصل أو يضبط حدود الطبقة الموضوعة في ملف PSD.

القيمة: حدود الطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان نمط التشويه لهذا الكائن مخصصًا. إذا كان true فإنه يحتوي على نقاط الشبكة. إذا تم تعيينه إلى false فإنه يمسح نقاط الشبكة.

القيمة:  true  إذا كانت الطبقة الموضوعة ذات نمط مخصص؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


يحصل أو يضبط نوع الوحدة الافتراضية للقيم المعينة مثل اليسار، الأعلى، اليمين، الأسفل، TransformMatrix.

القيمة: نوع وحدة القياس الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


يحصل أو يضبط وحدة القياس لنقاط الشبكة الأفقية.

القيمة: وحدة قياس نقاط الشبكة الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD.

القيمة: نقاط الشبكة الأفقية للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


يحصل أو يضبط عناصر الالتواء.

القيمة: عناصر warp.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


يحصل أو يضبط موقع اليسار للطبقة الموضوعة في ملف PSD.

القيمة: الموقع الأيسر للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


يحصل أو يضبط رقم الصفحة للطبقة الموضوعة في ملف PSD.

القيمة: رقم الصفحة للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


يحصل أو يضبط قيمة المنظور للطبقة الموضوعة في ملف PSD.

القيمة: قيمة المنظور للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


يحصل أو يضبط القيمة الأخرى للمنظور للطبقة الموضوعة في ملف PSD.

القيمة: قيمة المنظور الأخرى للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


يحصل أو يضبط نوع الطبقة الموضوعة في ملف PSD.

القيمة: نوع الطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


يحصل أو يضبط موقع اليمين للطبقة الموضوعة في ملف PSD.

القيمة: الموقع الأيمن للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت اتجاهات الدوران لهذا الكائن أفقية.

القيمة:  true  إذا كان اتجاه الدوران أفقيًا؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


يحصل أو يضبط موقع الأعلى للطبقة الموضوعة في صورة PSD.

القيمة: الموقع العلوي للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


يحصل أو يضبط إجمالي عدد الصفحات للطبقة الموضوعة في ملف PSD.

القيمة: إجمالي الصفحات للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


يحصل أو يضبط مصفوفة التحويل للطبقة الموضوعة في ملف PSD.

القيمة: مصفوفة التحويل للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


يحصل أو يضبط قيمة ترتيب U للطبقة الموضوعة في ملف PSD.

القيمة: قيمة ترتيب U للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


يحصل أو يضبط المعرف الفريد العالمي للطبقة الموضوعة في صورة PSD.

القيمة: المعرف الفريد للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


يحصل أو يعيّن قيمة ترتيب V للطبقة الموضوعة في ملف PSD.

القيمة: قيمة ترتيب V للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


يحصل أو يعيّن قيمة warp للطبقة الموضوعة في صورة PSD.

القيمة: قيمة التشويه للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


يحصل على إصدار الطبقة الموضوعة في ملف PSD، عادةً 3.

القيمة: إصدار الطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


يحصل أو يعيّن وحدة القياس لنقاط الشبكة العمودية.

القيمة: وحدة القياس لنقاط الشبكة العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


يحصل أو يضبط نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD.

القيمة: نقاط الشبكة الأفقية للطبقة الموضوعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


يحصل أو يعيّن معرف الفئة.

القيمة: معرف الفئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


يحصل أو يعيّن اسم فئة warp.

القيمة: اسم فئة التشويه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


يحصل أو يعيّن إصدار موصّف warp.

القيمة: إصدار موصّف التشويه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


يحصل أو يعيّن إصدار warp.

القيمة: إصدار التشويه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل هذا الكائن.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
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

