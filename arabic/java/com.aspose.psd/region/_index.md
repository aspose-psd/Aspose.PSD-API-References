---
title: "Region"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يصف داخل الشكل الرسومي المكوّن من مستطيلات ومسارات."
type: docs
weight: 90
url: /ar/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

يصف داخل الشكل الرسومي المكوّن من المستطيلات والمسارات. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Region()](#Region--) | يُنشئ كائنًا جديدًا من  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | يُنشئ كائنًا جديدًا من  T:Aspose.Imaging.Region  من البنية المحددة  T:Aspose.Imaging.RectangleF . |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | يُنشئ كائنًا جديدًا من  T:Aspose.Imaging.Region  من البنية المحددة  T:Aspose.Imaging.Rectangle . |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | يُنشئ كائنًا جديدًا من  T:Aspose.Imaging.Region  باستخدام  T:Aspose.Imaging.GraphicsPath  المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | يُحدّث هذا  com.aspose.psd.Region  ليحتوي على الجزء من  com.aspose.psd.GraphicsPath  المحدد والذي لا يتقاطع مع هذا  com.aspose.psd.region . |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | يُحدّث هذا  com.aspose.psd.Region  ليحتوي على الجزء من بنية  com.aspose.psd.Rectangle  المحددة والذي لا يتقاطع مع هذا  com.aspose.psd.region . |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | يُحدّث هذا  com.aspose.psd.Region  ليحتوي على الجزء من بنية  com.aspose.psd.RectangleF  المحددة والذي لا يتقاطع مع هذا  com.aspose.psd.region . |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | يُحدّث هذا  com.aspose.psd.Region  ليحتوي على الجزء من  com.aspose.psd.Region  المحدد والذي لا يتقاطع مع هذا  com.aspose.psd.region . |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة دقيقة من هذا  com.aspose.psd.region . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | يُحدّث هذا  com.aspose.psd.Region  ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع  com.aspose.psd.graphicsPath  المحدد. |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | يُحدّث هذا  com.aspose.psd.Region  ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع بنية  com.aspose.psd.Rectangle  المحددة. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | يُحدّث هذا  com.aspose.psd.Region  ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع بنية  com.aspose.psd.RectangleF  المحددة. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | يُحدّث هذا com.aspose.psd.Region ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع com.aspose.psd.region المحدد. |
| [getActions_internalized()](#getActions-internalized--) | يحصل على إجراءات المنطقة. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | يُحدّث هذا com.aspose.psd.Region إلى تقاطع نفسه مع com.aspose.psd.graphicsPath المحدد. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | يُحدّث هذا com.aspose.psd.Region إلى تقاطع نفسه مع بنية com.aspose.psd.Rectangle المحددة. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | يُحدّث هذا com.aspose.psd.Region إلى تقاطع نفسه مع بنية com.aspose.psd.RectangleF المحددة. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | يُحدّث هذا com.aspose.psd.Region إلى تقاطع نفسه مع com.aspose.psd.region المحدد. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | يفحص ما إذا كان هذا com.aspose.psd.Region لديه داخلية فارغة على سطح الرسم المحدد. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | يفحص ما إذا كان com.aspose.psd.Region المحدد مطابقًا لهذا com.aspose.psd.Region على سطح الرسم المحدد. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | يفحص ما إذا كان هذا com.aspose.psd.Region لديه داخلية لا نهائية على سطح الرسم المحدد. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | يفحص ما إذا كانت بنية com.aspose.psd.Point المحددة موجودة داخل هذا com.aspose.psd.region. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | يفحص ما إذا كانت بنية com.aspose.psd.Point المحددة موجودة داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | يفحص ما إذا كانت بنية com.aspose.psd.PointF المحددة موجودة داخل هذا com.aspose.psd.region. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | يفحص ما إذا كانت بنية com.aspose.psd.PointF المحددة موجودة داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | يفحص ما إذا كان أي جزء من بنية com.aspose.psd.Rectangle المحددة موجودًا داخل هذا com.aspose.psd.region. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | يفحص ما إذا كان أي جزء من بنية com.aspose.psd.Rectangle المحددة موجودًا داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | يفحص ما إذا كان أي جزء من بنية com.aspose.psd.RectangleF المحددة موجودًا داخل هذا com.aspose.psd.region. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | يفحص ما إذا كان أي جزء من بنية com.aspose.psd.RectangleF المحددة موجودًا داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد. |
| [isVisible(float x, float y)](#isVisible-float-float-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.region. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا com.aspose.psd.region. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن com.aspose.psd.Region هذا عند الرسم باستخدام كائن com.aspose.psd.Graphics المحدد. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا com.aspose.psd.region. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد. |
| [makeEmpty()](#makeEmpty--) | يُهيئ هذا com.aspose.psd.Region إلى داخلية فارغة. |
| [makeInfinite()](#makeInfinite--) | يُهيئ كائن com.aspose.psd.Region هذا إلى داخلية لا نهائية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | يحصل أو يعيّن منطقة التغيير. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | يحوّل هذا  com.aspose.psd.Region  باستخدام الـ  com.aspose.psd.matrix  المحدد . |
| [translate(float dx, float dy)](#translate-float-float-) | يُزاحِم إحداثيات هذا  com.aspose.psd.Region  بالمقدار المحدد . |
| [translate(int dx, int dy)](#translate-int-int-) | يُزاحِم إحداثيات هذا  com.aspose.psd.Region  بالمقدار المحدد . |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد بينه وبين الـ  com.aspose.psd.graphicsPath  المحدد . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد بينه وبين بنية الـ  com.aspose.psd.Rectangle  المحددة . |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد بينه وبين بنية الـ  com.aspose.psd.RectangleF  المحددة . |
| [union(Region region)](#union-com.aspose.psd.Region-) | يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد بينه وبين الـ  com.aspose.psd.region  المحدد . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد مطروحًا منه تقاطع نفسه مع الـ  com.aspose.psd.graphicsPath  المحدد . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية الـ  com.aspose.psd.Rectangle  المحددة . |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية الـ  com.aspose.psd.RectangleF  المحددة . |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد مطروحًا منه تقاطع نفسه مع الـ  com.aspose.psd.region  المحدد . |
### Region() {#Region--}
```
public Region()
```


يُنشئ كائنًا جديدًا من  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


يُنشئ كائنًا جديدًا من  T:Aspose.Imaging.Region  من البنية المحددة  T:Aspose.Imaging.RectangleF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية  T:Aspose.Imaging.RectangleF  التي تحدد داخل الـ  T:Aspose.Imaging.Region  الجديد . |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


يُنشئ كائنًا جديدًا من  T:Aspose.Imaging.Region  من البنية المحددة  T:Aspose.Imaging.Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | بنية  T:Aspose.Imaging.Rectangle  التي تحدد داخل الـ  T:Aspose.Imaging.Region  الجديد . |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


يُنشئ كائنًا جديدًا من  T:Aspose.Imaging.Region  باستخدام  T:Aspose.Imaging.GraphicsPath  المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | كائن  T:Aspose.Imaging.GraphicsPath  الذي يحدد الـ  T:Aspose.Imaging.Region  الجديد . |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


يُحدّث هذا  com.aspose.psd.Region  ليحتوي على الجزء من  com.aspose.psd.GraphicsPath  المحدد والذي لا يتقاطع مع هذا  com.aspose.psd.region .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | الـ  com.aspose.psd.GraphicsPath  لتكملة هذا  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


يُحدّث هذا  com.aspose.psd.Region  ليحتوي على الجزء من بنية  com.aspose.psd.Rectangle  المحددة والذي لا يتقاطع مع هذا  com.aspose.psd.region .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | بنية الـ  com.aspose.psd.Rectangle  لتكملة هذا  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


يُحدّث هذا  com.aspose.psd.Region  ليحتوي على الجزء من بنية  com.aspose.psd.RectangleF  المحددة والذي لا يتقاطع مع هذا  com.aspose.psd.region .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية الـ  com.aspose.psd.RectangleF  لتكملة هذا  com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


يُحدّث هذا  com.aspose.psd.Region  ليحتوي على الجزء من  com.aspose.psd.Region  المحدد والذي لا يتقاطع مع هذا  com.aspose.psd.region .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | كائن الـ  com.aspose.psd.Region  لتكملة هذا كائن الـ  com.aspose.psd.Region . |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


ينشئ نسخة عميقة دقيقة من هذا  com.aspose.psd.region .

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


يُحدّث هذا  com.aspose.psd.Region  ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع  com.aspose.psd.graphicsPath  المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | الـ  com.aspose.psd.GraphicsPath  لاستبعاده من هذا  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


يُحدّث هذا  com.aspose.psd.Region  ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع بنية  com.aspose.psd.Rectangle  المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | بنية الـ  com.aspose.psd.Rectangle  لاستبعادها من هذا  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


يُحدّث هذا  com.aspose.psd.Region  ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع بنية  com.aspose.psd.RectangleF  المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية الـ  com.aspose.psd.RectangleF  لاستبعادها من هذا  com.aspose.psd.region . |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


يُحدّث هذا com.aspose.psd.Region ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع com.aspose.psd.region المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | الـ  com.aspose.psd.Region  لاستبعاده من هذا  com.aspose.psd.region . |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


يحصل على إجراءات المنطقة.

**Returns:**
com.aspose.internal.RegionAction[] - إجراءات المنطقة .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


يُحدّث هذا com.aspose.psd.Region إلى تقاطع نفسه مع com.aspose.psd.graphicsPath المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | الـ  com.aspose.psd.GraphicsPath  للتقاطع مع هذا  com.aspose.psd.region . |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


يُحدّث هذا com.aspose.psd.Region إلى تقاطع نفسه مع بنية com.aspose.psd.Rectangle المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | بنية الـ  com.aspose.psd.Rectangle  للتقاطع مع هذا  com.aspose.psd.region . |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


يُحدّث هذا com.aspose.psd.Region إلى تقاطع نفسه مع بنية com.aspose.psd.RectangleF المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | بنية الـ  com.aspose.psd.RectangleF  للتقاطع مع هذا  com.aspose.psd.region . |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


يُحدّث هذا com.aspose.psd.Region إلى تقاطع نفسه مع com.aspose.psd.region المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | الـ com.aspose.psd.Region للتقاطع مع هذا com.aspose.psd.region. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


يفحص ما إذا كان هذا com.aspose.psd.Region لديه داخلية فارغة على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سطح رسم. |

**Returns:**
boolean - true إذا كان داخل هذا com.aspose.psd.Region فارغًا عندما يتم تطبيق التحويل المرتبط بـ g؛ وإلا false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


يفحص ما إذا كان com.aspose.psd.Region المحدد مطابقًا لهذا com.aspose.psd.Region على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | الـ com.aspose.psd.Region للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سطح رسم. |

**Returns:**
boolean - True إذا كان داخل المنطقة مماثلًا لداخل هذه المنطقة عندما يتم تطبيق التحويل المرتبط بالمعامل g؛ وإلا false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


يفحص ما إذا كان هذا com.aspose.psd.Region لديه داخلية لا نهائية على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سطح رسم. |

**Returns:**
boolean - true إذا كان داخل هذا com.aspose.psd.Region لا نهائيًا عندما يتم تطبيق التحويل المرتبط بـ g؛ وإلا false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


يفحص ما إذا كانت بنية com.aspose.psd.Point المحددة موجودة داخل هذا com.aspose.psd.region.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | الـ com.aspose.psd.Point بنية للاختبار. |

**Returns:**
boolean - true عندما تكون point داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


يفحص ما إذا كانت بنية com.aspose.psd.Point المحددة موجودة داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | الـ com.aspose.psd.Point بنية للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سياق رسومي. |

**Returns:**
boolean - true عندما تكون point داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


يفحص ما إذا كانت بنية com.aspose.psd.PointF المحددة موجودة داخل هذا com.aspose.psd.region.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | الـ com.aspose.psd.PointF بنية للاختبار. |

**Returns:**
boolean - true عندما تكون point داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


يفحص ما إذا كانت بنية com.aspose.psd.PointF المحددة موجودة داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | الـ com.aspose.psd.PointF بنية للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سياق رسومي. |

**Returns:**
boolean - true عندما تكون point داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


يفحص ما إذا كان أي جزء من بنية com.aspose.psd.Rectangle المحددة موجودًا داخل هذا com.aspose.psd.region.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | الـ com.aspose.psd.Rectangle بنية للاختبار. |

**Returns:**
boolean - This method returns true عندما يكون أي جزء من rect داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


يفحص ما إذا كان أي جزء من بنية com.aspose.psd.Rectangle المحددة موجودًا داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | الـ com.aspose.psd.Rectangle بنية للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سياق رسومي. |

**Returns:**
boolean - true عندما يكون أي جزء من rect داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


يفحص ما إذا كان أي جزء من بنية com.aspose.psd.RectangleF المحددة موجودًا داخل هذا com.aspose.psd.region.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | الـ com.aspose.psd.RectangleF بنية للاختبار. |

**Returns:**
boolean - true عندما يكون أي جزء من rect داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


يفحص ما إذا كان أي جزء من بنية com.aspose.psd.RectangleF المحددة موجودًا داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | الـ com.aspose.psd.RectangleF بنية للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سياق رسومي. |

**Returns:**
boolean - true عندما يكون rect داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.region.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للنقطة للاختبار. |
| ص | float | الإحداثي الصادي للنقطة للاختبار. |

**Returns:**
boolean - True عندما تكون النقطة المحددة داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للنقطة للاختبار. |
| ص | float | الإحداثي الصادي للنقطة للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سياق رسومي. |

**Returns:**
boolean - True عندما تكون النقطة المحددة داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا com.aspose.psd.region.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | إحداثي x للزاوية العليا اليسرى للمستطيل للاختبار. |
| ص | float | إحداثي y للزاوية العليا اليسرى للمستطيل للاختبار. |
| العرض | float | عرض المستطيل للاختبار. |
| الارتفاع | float | ارتفاع المستطيل للاختبار. |

**Returns:**
boolean - true عندما يكون أي جزء من المستطيل المحدد داخل هذا كائن com.aspose.psd.Region؛ وإلا false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | إحداثي x للزاوية العليا اليسرى للمستطيل للاختبار. |
| ص | float | إحداثي y للزاوية العليا اليسرى للمستطيل للاختبار. |
| العرض | float | عرض المستطيل للاختبار. |
| الارتفاع | float | ارتفاع المستطيل للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سياق رسومي. |

**Returns:**
boolean - true عندما يكون أي جزء من المستطيل المحدد داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن com.aspose.psd.Region هذا عند الرسم باستخدام كائن com.aspose.psd.Graphics المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للنقطة للاختبار. |
| ص | int | الإحداثي الصادي للنقطة للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سياق رسومي. |

**Returns:**
boolean - true عندما تكون النقطة المحددة داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا com.aspose.psd.region.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | إحداثي x للزاوية العليا اليسرى للمستطيل للاختبار. |
| ص | int | إحداثي y للزاوية العليا اليسرى للمستطيل للاختبار. |
| العرض | int | عرض المستطيل للاختبار. |
| الارتفاع | int | ارتفاع المستطيل للاختبار. |

**Returns:**
boolean - true عندما يكون أي جزء من المستطيل المحدد داخل هذا com.aspose.psd.Region؛ وإلا false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا com.aspose.psd.Region عند الرسم باستخدام com.aspose.psd.graphics المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | إحداثي x للزاوية العليا اليسرى للمستطيل للاختبار. |
| ص | int | إحداثي y للزاوية العليا اليسرى للمستطيل للاختبار. |
| العرض | int | عرض المستطيل للاختبار. |
| الارتفاع | int | ارتفاع المستطيل للاختبار. |
| g | [Graphics](../../com.aspose.psd/graphics) | كائن com.aspose.psd.Graphics يمثل سياق رسومي. |

**Returns:**
boolean - true عندما يكون أي جزء من المستطيل المحدد داخل هذا com.aspose.psd.Region؛ وإلا false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


يُهيئ هذا com.aspose.psd.Region إلى داخلية فارغة.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


يُهيئ كائن com.aspose.psd.Region هذا إلى داخلية لا نهائية.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


يحصل أو يعيّن منطقة التغيير.

القيمة: المنطقة عند التغيير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


يحوّل هذا  com.aspose.psd.Region  باستخدام الـ  com.aspose.psd.matrix  المحدد .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة  com.aspose.psd.Matrix  التي تُستخدم لتحويل هذا  com.aspose.psd.region . |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


يُزاحِم إحداثيات هذا  com.aspose.psd.Region  بالمقدار المحدد .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | المقدار لإزاحة هذا  com.aspose.psd.Region  أفقياً. |
| dy | float | المقدار لإزاحة هذا  com.aspose.psd.Region  عمودياً. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


يُزاحِم إحداثيات هذا  com.aspose.psd.Region  بالمقدار المحدد .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | int | المقدار لإزاحة هذا  com.aspose.psd.Region  أفقياً. |
| dy | int | المقدار لإزاحة هذا  com.aspose.psd.Region  عمودياً. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد بينه وبين الـ  com.aspose.psd.graphicsPath  المحدد .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | مسار الرسومات  com.aspose.psd.GraphicsPath  للاتحاد مع هذا  com.aspose.psd.region . |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد بينه وبين بنية الـ  com.aspose.psd.Rectangle  المحددة .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | الهيكل  com.aspose.psd.Rectangle  للاتحاد مع هذا  com.aspose.psd.region . |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد بينه وبين بنية الـ  com.aspose.psd.RectangleF  المحددة .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | الهيكل  com.aspose.psd.RectangleF  للاتحاد مع هذا  com.aspose.psd.region . |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد بينه وبين الـ  com.aspose.psd.region  المحدد .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | المنطقة  com.aspose.psd.Region  للاتحاد مع هذا  com.aspose.psd.region . |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد مطروحًا منه تقاطع نفسه مع الـ  com.aspose.psd.graphicsPath  المحدد .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | مسار الرسومات  com.aspose.psd.GraphicsPath  لإجراء XOR مع هذا  com.aspose.psd.region . |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية الـ  com.aspose.psd.Rectangle  المحددة .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | الهيكل  com.aspose.psd.Rectangle  لإجراء XOR مع هذا  com.aspose.psd.region . |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية الـ  com.aspose.psd.RectangleF  المحددة .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | الهيكل  com.aspose.psd.RectangleF  لإجراء XOR مع هذا  com.aspose.psd.region . |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


يُحدّث هذا  com.aspose.psd.Region  إلى الاتحاد مطروحًا منه تقاطع نفسه مع الـ  com.aspose.psd.region  المحدد .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | المنطقة  com.aspose.psd.Region  لإجراء XOR مع هذا  com.aspose.psd.region . |

