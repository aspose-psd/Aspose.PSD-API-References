---
title: "WarpSettings"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "معلمات الطبقة ذات الالتواء"
type: docs
weight: 12
url: /ar/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

معلمات الطبقة ذات الالتواء
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | ينشئ مثيلًا جديدًا من الفئة [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | ينشئ مثيلًا جديدًا من الفئة [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | ينشئ مثيلًا جديدًا من الفئة [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | ينشئ مثيلًا جديدًا من الفئة [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | القيمة الافتراضية لـ ProcessingArea |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | يحصل أو يعيّن حدود صورة الالتواء |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | يحصل أو يعيّن حجم شبكة التشويه. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | يحصل أو يعيّن حجم خطوط الشبكة. |
| [getMeshPoints()](#getMeshPoints--) | نقاط شبكة Photoshop |
| [getRenderQuality()](#getRenderQuality--) | يحصل أو يعيّن قيمة جودة عرض التشويه - بين السرعة والجودة. |
| [getRotate()](#getRotate--) | يحصل أو يعيّن قيمة الدوران |
| [getStyle()](#getStyle--) | يحصل أو يعيّن نمط الالتواء |
| [getValue()](#getValue--) | يحصل أو يعيّن قيمة الالتواء |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | يحصل أو يعيّن تغيّر المستخدم في MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | يحصل أو يعيّن حدود صورة الالتواء |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | يحصل أو يعيّن حجم شبكة التشويه. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | يحصل أو يعيّن حجم خطوط الشبكة. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | نقاط شبكة Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | يعيد نقطة الشبكة من متجهات المورد |
| [setRenderQuality(int value)](#setRenderQuality-int-) | يحصل أو يعيّن قيمة جودة عرض التشويه - بين السرعة والجودة. |
| [setRotate(int value)](#setRotate-int-) | يحصل أو يعيّن قيمة الدوران |
| [setStyle(int value)](#setStyle-int-) | يحصل أو يعيّن نمط الالتواء |
| [setValue(double value)](#setValue-double-) | يحصل أو يعيّن قيمة الالتواء |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | يحفظ معلمات الالتواء هذه إلى PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | يحفظ معلمات الالتواء هذه إلى PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


ينشئ مثيلًا جديدًا من الفئة [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | نقاط شبكة التشويه. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود صورة الالتواء |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


ينشئ مثيلًا جديدًا من الفئة [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | نقاط شبكة التشويه. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود صورة الالتواء |
| النمط | int | نمط التشويه. |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


ينشئ مثيلًا جديدًا من الفئة [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | عناصر PS بإعدادات الالتواء |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود صورة الالتواء |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


ينشئ مثيلًا جديدًا من الفئة [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | المورد بإعدادات الالتواء |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


القيمة الافتراضية لـ ProcessingArea

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


يحصل أو يعيّن حدود صورة الالتواء

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGridSize() {#getGridSize--}
```
public final Size getGridSize()
```


يحصل أو يعيّن حجم شبكة التشويه. القيمة الافتراضية هي 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


يحصل أو يعيّن حجم خطوط الشبكة. GridSize هو تعريف من PS يمكن للعميل اختياره. كل GridSize يحتوي على 4 خطوط شبكة. إذا كان عدد GridSize أكبر من 1، فإن آخر خط شبكة في الشبكة الأولى وأول خط شبكة في الشبكة الثانية يصبحان خط شبكة واحد.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


نقاط شبكة Photoshop

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


يحصل أو يعيّن قيمة جودة عرض التشويه - بين السرعة والجودة.

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


يحصل أو يعيّن قيمة الدوران

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


يحصل أو يعيّن نمط الالتواء

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


يحصل أو يعيّن قيمة الالتواء

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultMeshPoints_internalized() {#isDefaultMeshPoints-internalized--}
```
public final boolean isDefaultMeshPoints_internalized()
```


يحصل أو يعيّن تغيّر المستخدم في MeshPoints

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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


يحصل أو يعيّن حدود صورة الالتواء

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


يحصل أو يعيّن حجم شبكة التشويه. القيمة الافتراضية هي 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


يحصل أو يعيّن حجم خطوط الشبكة. GridSize هو تعريف من PS يمكن للعميل اختياره. كل GridSize يحتوي على 4 خطوط شبكة. إذا كان عدد GridSize أكبر من 1، فإن آخر خط شبكة في الشبكة الأولى وأول خط شبكة في الشبكة الثانية يصبحان خط شبكة واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


نقاط شبكة Photoshop

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


يعيد نقطة الشبكة من متجهات المورد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | المورد بإعدادات الالتواء |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


يحصل أو يعيّن قيمة جودة عرض التشويه - بين السرعة والجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


يحصل أو يعيّن قيمة الدوران

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


يحصل أو يعيّن نمط الالتواء

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


يحصل أو يعيّن قيمة الالتواء

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


يحفظ معلمات الالتواء هذه إلى PlacedResource

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | المورد بإعدادات الالتواء |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - المورد مع معلمات الالتواء من هذا WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


يحفظ معلمات الالتواء هذه إلى PlacedResource

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | المورد بإعدادات الالتواء |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - Resource with warp params from this WarpParams
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

