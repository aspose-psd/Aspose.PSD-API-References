---
title: "WarpSettings"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "वॉर्प के साथ लेयर के पैरामीटर"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

वॉर्प के साथ लेयर के पैरामीटर
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | नया उदाहरण प्रारंभ करता है [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) क्लास का। |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | नया उदाहरण प्रारंभ करता है [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) क्लास का। |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | नया उदाहरण प्रारंभ करता है [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) क्लास का। |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | नया उदाहरण प्रारंभ करता है [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) क्लास का। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | ProcessingArea का डिफ़ॉल्ट मान |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | वॉर्प इमेज की सीमाएँ प्राप्त करता है या सेट करता है |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | warp ग्रिड का आकार प्राप्त करता है या सेट करता है। |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | mesh लाइनों का आकार प्राप्त करता है या सेट करता है। |
| [getMeshPoints()](#getMeshPoints--) | फ़ोटोशॉप मेष पॉइंट्स |
| [getRenderQuality()](#getRenderQuality--) | warp रेंडर क्वालिटी का मान प्राप्त करता है या सेट करता है - गति और गुणवत्ता के बीच। |
| [getRotate()](#getRotate--) | रोटेट मान प्राप्त करता है या सेट करता है |
| [getStyle()](#getStyle--) | वॉर्प की शैली प्राप्त करता है या सेट करता है |
| [getValue()](#getValue--) | वॉर्प का मान प्राप्त करता है या सेट करता है |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | MeshPoints में उपयोगकर्ता परिवर्तन प्राप्त करता है या सेट करता है |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | वॉर्प इमेज की सीमाएँ प्राप्त करता है या सेट करता है |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | warp ग्रिड का आकार प्राप्त करता है या सेट करता है। |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | mesh लाइनों का आकार प्राप्त करता है या सेट करता है। |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | फ़ोटोशॉप मेष पॉइंट्स |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | यह संसाधन वेक्टरों से मेष पॉइंट लौटाता है |
| [setRenderQuality(int value)](#setRenderQuality-int-) | warp रेंडर क्वालिटी का मान प्राप्त करता है या सेट करता है - गति और गुणवत्ता के बीच। |
| [setRotate(int value)](#setRotate-int-) | रोटेट मान प्राप्त करता है या सेट करता है |
| [setStyle(int value)](#setStyle-int-) | वॉर्प की शैली प्राप्त करता है या सेट करता है |
| [setValue(double value)](#setValue-double-) | वॉर्प का मान प्राप्त करता है या सेट करता है |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | यह इस वॉर्प पैरामीटर को PlacedResource में सहेजता है |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | यह इस वॉर्प पैरामीटर को PlacedResource में सहेजता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


नया उदाहरण प्रारंभ करता है [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | warp के मेष बिंदु। |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | वॉर्प इमेज की सीमाएँ |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


नया उदाहरण प्रारंभ करता है [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | warp के मेष बिंदु। |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | वॉर्प इमेज की सीमाएँ |
| style | int | warp की शैली। |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


नया उदाहरण प्रारंभ करता है [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | वॉर्प सेटिंग्स वाले PS आइटम्स |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | वॉर्प इमेज की सीमाएँ |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


नया उदाहरण प्रारंभ करता है [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | वॉर्प सेटिंग्स वाला संसाधन |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


ProcessingArea का डिफ़ॉल्ट मान

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


वॉर्प इमेज की सीमाएँ प्राप्त करता है या सेट करता है

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


warp ग्रिड का आकार प्राप्त करता है या सेट करता है। डिफ़ॉल्ट 1 है।

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


mesh लाइनों का आकार प्राप्त करता है या सेट करता है। GridSize वह परिभाषा है जो PS से आती है और क्लाइंट चयन कर सकता है। प्रत्येक GridSize में 4 mesh लाइन्स होती हैं। यदि GridSize की संख्या 1 से अधिक है, तो पहले ग्रिड की अंतिम mesh लाइन और दूसरे ग्रिड की पहली mesh लाइन एक ही Mesh Line बन जाती हैं।

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


फ़ोटोशॉप मेष पॉइंट्स

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


warp रेंडर क्वालिटी का मान प्राप्त करता है या सेट करता है - गति और गुणवत्ता के बीच।

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


रोटेट मान प्राप्त करता है या सेट करता है

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


वॉर्प की शैली प्राप्त करता है या सेट करता है

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


वॉर्प का मान प्राप्त करता है या सेट करता है

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


MeshPoints में उपयोगकर्ता परिवर्तन प्राप्त करता है या सेट करता है

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


वॉर्प इमेज की सीमाएँ प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


warp ग्रिड का आकार प्राप्त करता है या सेट करता है। डिफ़ॉल्ट 1 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


mesh लाइनों का आकार प्राप्त करता है या सेट करता है। GridSize वह परिभाषा है जो PS से आती है और क्लाइंट चयन कर सकता है। प्रत्येक GridSize में 4 mesh लाइन्स होती हैं। यदि GridSize की संख्या 1 से अधिक है, तो पहले ग्रिड की अंतिम mesh लाइन और दूसरे ग्रिड की पहली mesh लाइन एक ही Mesh Line बन जाती हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


फ़ोटोशॉप मेष पॉइंट्स

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


यह संसाधन वेक्टरों से मेष पॉइंट लौटाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | वॉर्प सेटिंग्स वाला संसाधन |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


warp रेंडर क्वालिटी का मान प्राप्त करता है या सेट करता है - गति और गुणवत्ता के बीच।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


रोटेट मान प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


वॉर्प की शैली प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


वॉर्प का मान प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


यह इस वॉर्प पैरामीटर को PlacedResource में सहेजता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | वॉर्प सेटिंग्स वाला संसाधन |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - इस WarpParams से वॉर्प पैरामीटर वाला संसाधन
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


यह इस वॉर्प पैरामीटर को PlacedResource में सहेजता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | वॉर्प सेटिंग्स वाला संसाधन |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

