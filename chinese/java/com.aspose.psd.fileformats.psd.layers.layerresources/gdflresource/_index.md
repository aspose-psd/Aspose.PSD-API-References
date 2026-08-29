---
title: "GdFlResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "GdFlResource 类。"
type: docs
weight: 33
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class GdFlResource extends FillLayerResource
```

类 GdFlResource. 此资源包含有关剪切元素混合的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GdFlResource()](#GdFlResource--) | 初始化 [.GdFlResource](../../null/\#GdFlResource) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | 默认比例。 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB header version。 |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-specific resource signature。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD header version。 |
| [ResourceSignature](#ResourceSignature) | common resource signature。 |
| [TypeToolKey](#TypeToolKey) | 类型工具信息键。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | venture license。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addUnknownStructure_internalized(OSTypeStructure structure)](#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | 添加未知结构。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 检查并设置资源是否为 PSB specific。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateDefaultControlPoints_internalized()](#generateDefaultControlPoints-internalized--) | 生成默认控制点。 |
| [generateDefaultTransparencyPoints_internalized()](#generateDefaultTransparencyPoints-internalized--) | 生成默认透明点。 |
| [getAlignWithLayer()](#getAlignWithLayer--) | 获取或设置一个值，指示是否 [align with layer]。 |
| [getAngle()](#getAngle--) | 获取或设置角度。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取 RGB 的颜色。 |
| [getColorModel()](#getColorModel--) | 颜色模型 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [getColorPoints()](#getColorPoints--) | 获取颜色点。 |
| [getDither()](#getDither--) | 获取或设置一个值，指示此 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) 是否抖动。 |
| [getGradientInterval()](#getGradientInterval--) | 获取或设置渐变间隔。 |
| [getGradientMode()](#getGradientMode--) | 此渐变的模式。 |
| [getGradientName()](#getGradientName--) | 获取或设置渐变的名称。 |
| [getGradientType()](#getGradientType--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getHorizontalOffset()](#getHorizontalOffset--) | 获取或设置水平偏移。 |
| [getInterpolationMethod()](#getInterpolationMethod--) | 获取或设置渐变的插值方法。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) | 获取图层资源长度（字节）。 |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat 的最大颜色。 |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat 的最小颜色。 |
| [getOffset_internalized()](#getOffset-internalized--) | 获取或设置偏移量。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getReverse()](#getReverse--) | 获取或设置一个值，指示此 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) 是否反向。 |
| [getRndNumberSeed()](#getRndNumberSeed--) | 用于生成噪声渐变颜色的随机数种子。 |
| [getRoughness()](#getRoughness--) | 粗糙度因子。 |
| [getScale()](#getScale--) | 获取或设置比例。 |
| [getShowTransparency()](#getShowTransparency--) | 显示透明度的标志。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getTransparencyPoints()](#getTransparencyPoints--) | 获取透明点。 |
| [getUseVectorColor()](#getUseVectorColor--) | 使用矢量颜色的标志。 |
| [getVerticalOffset()](#getVerticalOffset--) | 获取或设置垂直偏移量。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源保存到指定的流容器。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | 获取或设置一个值，指示是否 [align with layer]。 |
| [setAngle(double value)](#setAngle-double-) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 获取 RGB 的颜色。 |
| [setColorModel(String value)](#setColorModel-java.lang.String-) | 颜色模型 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | 获取颜色点。 |
| [setDither(boolean value)](#setDither-boolean-) | 获取或设置一个值，指示此 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) 是否抖动。 |
| [setGradientInterval(double value)](#setGradientInterval-double-) | 获取或设置渐变间隔。 |
| [setGradientMode(String value)](#setGradientMode-java.lang.String-) | 此渐变的模式。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 获取或设置渐变的名称。 |
| [setGradientType(int value)](#setGradientType-int-) |  |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) |  |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | 获取或设置渐变的插值方法。 |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat 的最大颜色。 |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat 的最小颜色。 |
| [setOffset_internalized(OffsetEntity value)](#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | 获取或设置偏移量。 |
| [setReverse(boolean value)](#setReverse-boolean-) | 获取或设置一个值，指示此 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) 是否反向。 |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | 用于生成噪声渐变颜色的随机数种子。 |
| [setRoughness(int value)](#setRoughness-int-) | 粗糙度因子。 |
| [setScale(double value)](#setScale-double-) | 获取或设置比例。 |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | 显示透明度的标志。 |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | 获取透明点。 |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | 使用矢量颜色的标志。 |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) |  |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GdFlResource() {#GdFlResource--}
```
public GdFlResource()
```


初始化 [.GdFlResource](../../null/\#GdFlResource) 类的新实例。

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


默认比例。

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB header version。

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB-specific resource signature。

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD header version。

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


common resource signature。

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


类型工具信息键。

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


venture license。

### addUnknownStructure_internalized(OSTypeStructure structure) {#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public void addUnknownStructure_internalized(OSTypeStructure structure)
```


添加未知结构。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 结构。 |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


检查并设置资源是否为 PSB 特定。某些资源目前尚未被识别，但我们拥有完整的 PSB 特定资源列表，这会在保存时改变它们的行为。因此至少需要在 UnknownResource 中进行此检查。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | int | 键。 |

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
### generateDefaultControlPoints_internalized() {#generateDefaultControlPoints-internalized--}
```
public static IGradientColorPoint[] generateDefaultControlPoints_internalized()
```


生成默认控制点。

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[] - 默认控制点。
### generateDefaultTransparencyPoints_internalized() {#generateDefaultTransparencyPoints-internalized--}
```
public static IGradientTransparencyPoint[] generateDefaultTransparencyPoints_internalized()
```


生成默认透明点。

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[] - 默认透明点。
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


获取或设置一个值，指示是否 [align with layer]。

值：如果 [align with layer] 为 true；否则为 false。

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public double getAngle()
```


获取或设置角度。

角度。

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


获取 RGB 的颜色。

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB Color
### getColorModel() {#getColorModel--}
```
public final String getColorModel()
```


颜色模型 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Returns:**
java.lang.String
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


获取颜色点。

值：颜色点。

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


获取或设置一个值，指示此 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) 是否抖动。

值： true 表示抖动；否则为 false。

**Returns:**
boolean
### getGradientInterval() {#getGradientInterval--}
```
public final double getGradientInterval()
```


获取或设置渐变间隔。

值：梯度间隔。

**Returns:**
double
### getGradientMode() {#getGradientMode--}
```
public final String getGradientMode()
```


此梯度的模式。确定 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs"。

**Returns:**
java.lang.String
### getGradientName() {#getGradientName--}
```
public String getGradientName()
```


获取或设置渐变的名称。

值：渐变的名称。

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public int getGradientType()
```




**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


获取或设置标题。

值：头部。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalOffset() {#getHorizontalOffset--}
```
public double getHorizontalOffset()
```


获取或设置水平偏移。

水平偏移。

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


获取或设置渐变的插值方法。

**Returns:**
long
### getKey() {#getKey--}
```
public final int getKey()
```


获取图层资源键。

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


获取图层资源长度（字节）。

**Returns:**
int
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


PixelDataFormat 的最大颜色。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat 的最小颜色。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getOffset_internalized() {#getOffset-internalized--}
```
public final OffsetEntity getOffset_internalized()
```


获取或设置偏移量。

值：偏移量。

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


获取前缀长度。默认值为 8BIM 资源的 12，8B64 资源的 16。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| psdVersion | int | PSD 版本。 |

**Returns:**
int - 前缀长度。
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


获取图层资源所需的最低 PSD 版本。0 表示没有限制。

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


获取或设置一个值，指示此 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) 是否反向。

值： true 表示反向；否则为 false。

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


用于生成噪声渐变颜色的随机数种子。

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


粗糙度因子。

**Returns:**
int
### getScale() {#getScale--}
```
public final double getScale()
```


获取或设置比例。

**Returns:**
double
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


显示透明度的标志。

**Returns:**
boolean
### getSignature() {#getSignature--}
```
public int getSignature()
```


获取图层资源签名。

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


获取透明点。

值：透明点。

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


使用矢量颜色的标志。

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public double getVerticalOffset()
```


获取或设置垂直偏移量。

垂直偏移。

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


确定资源是否为 PSB specific。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | int | 资源键。 |

**Returns:**
boolean - 如果资源是 PSB 特定则为 true；否则为 false。
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


获取指示此实例是否为资源 PSB specific 的值。

值：如果此实例是资源 PSD 特定则为 true；否则为 false。

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


将资源保存到指定的流容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psdVersion | int | PSD 版本。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


保存自定义资源头部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |
| 签名 | int | 签名。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


保存头部签名、标识符和长度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |
| 签名 | int | 签名。 |
| isLengthLong | boolean | 如果设置为 true，则长度为长。 |

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


获取或设置一个值，指示是否 [align with layer]。

值：如果 [align with layer] 为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


获取 RGB 的颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setColorModel(String value) {#setColorModel-java.lang.String-}
```
public final void setColorModel(String value)
```


颜色模型 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


获取颜色点。

值：颜色点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


获取或设置一个值，指示此 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) 是否抖动。

值： true 表示抖动；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setGradientInterval(double value) {#setGradientInterval-double-}
```
public final void setGradientInterval(double value)
```


获取或设置渐变间隔。

值：梯度间隔。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setGradientMode(String value) {#setGradientMode-java.lang.String-}
```
public final void setGradientMode(String value)
```


此梯度的模式。确定 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs"。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public void setGradientName(String value)
```


获取或设置渐变的名称。

值：渐变的名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public void setGradientType(int value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


获取或设置标题。

值：头部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public void setHorizontalOffset(double value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


获取或设置渐变的插值方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


PixelDataFormat 的最大颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat 的最小颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setOffset_internalized(OffsetEntity value) {#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setOffset_internalized(OffsetEntity value)
```


获取或设置偏移量。

值：偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


获取或设置一个值，指示此 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) 是否反向。

值： true 表示反向；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


用于生成噪声渐变颜色的随机数种子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


粗糙度因子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


获取或设置比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


显示透明度的标志。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


获取透明点。

值：透明点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


使用矢量颜色的标志。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public void setVerticalOffset(double value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
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

