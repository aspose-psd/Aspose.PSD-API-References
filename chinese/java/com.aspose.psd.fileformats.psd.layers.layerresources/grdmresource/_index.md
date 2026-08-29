---
title: "GrdmResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "类 GrdmResource。"
type: docs
weight: 35
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

类 GrdmResource。包含有关 Gradient-Map 图层的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | 初始化一个新的 [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) 类的实例。 |
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
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 检查并设置资源是否为 PSB specific。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | 颜色模型。 |
| [getColorPoints()](#getColorPoints--) | 获取或设置颜色点。 |
| [getData()](#getData--) | 获取或设置数据。 |
| [getDither()](#getDither--) | 是否对梯度进行抖动。 |
| [getExpansionCount()](#getExpansionCount--) | 扩展计数 ( = 2 对于 Photoshop 6.0)。 |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | 长度 (= 32 对于 Photoshop 6.0) 没有关于其作用的信息。 |
| [getGradientMode()](#getGradientMode--) | 此梯度的模式 确定 'Gradient Type' = 'Solid/Noise' (0/1)。 |
| [getGradientName()](#getGradientName--) | 梯度的名称：Unicode 字符串，已填充。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getInterpolation()](#getInterpolation--) | 插值。 |
| [getInterpolationMethod()](#getInterpolationMethod--) | 获取或设置渐变的插值方法。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) | 获取图层资源长度（字节）。 |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat.Rgba64Bpp 格式的最大颜色。 |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat.Rgba64Bpp 格式的最小颜色。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取此资源所需的最低 PSD 版本。 |
| [getReverse()](#getReverse--) | 是否反转梯度。 |
| [getRndNumberSeed()](#getRndNumberSeed--) | 用于生成噪声渐变颜色的随机数种子。 |
| [getRoughness()](#getRoughness--) | 粗糙度因子 当 'Gradient type' = 'Noise' 时，我们可以分配 'Roughness' (0 - 2048)。 |
| [getShowTransparency()](#getShowTransparency--) | 显示透明度的标志 当 'Gradient type' = 'Noise' 时，我们可以将 'Add transparency' 设为 true。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getTransparencyPoints()](#getTransparencyPoints--) | 获取或设置透明度点。 |
| [getUseVectorColor()](#getUseVectorColor--) | 使用矢量颜色的标志。 |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | 初始化梯度的长度。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源数据保存到指定的流容器中。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setColorModel(short value)](#setColorModel-short-) | 颜色模型。 |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | 获取或设置颜色点。 |
| [setDither(boolean value)](#setDither-boolean-) | 是否对梯度进行抖动。 |
| [setExpansionCount(short value)](#setExpansionCount-short-) | 扩展计数 ( = 2 对于 Photoshop 6.0)。 |
| [setGradientMode(int value)](#setGradientMode-int-) | 此梯度的模式 确定 'Gradient Type' = 'Solid/Noise' (0/1)。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 梯度的名称：Unicode 字符串，已填充。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setInterpolation(short value)](#setInterpolation-short-) | 插值。 |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | 获取或设置渐变的插值方法。 |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp 格式的最大颜色。 |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp 格式的最小颜色。 |
| [setReverse(boolean value)](#setReverse-boolean-) | 是否反转梯度。 |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | 用于生成噪声渐变颜色的随机数种子。 |
| [setRoughness(int value)](#setRoughness-int-) | 粗糙度因子 当 'Gradient type' = 'Noise' 时，我们可以分配 'Roughness' (0 - 2048)。 |
| [setShowTransparency(short value)](#setShowTransparency-short-) | 显示透明度的标志 当 'Gradient type' = 'Noise' 时，我们可以将 'Add transparency' 设为 true。 |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | 获取或设置透明度点。 |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | 使用矢量颜色的标志。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


初始化一个新的 [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) 类的实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| psdVersion | int | 资源的 PSD 版本。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


颜色模型。当 'Gradient type' = 'Noise' 时，我们可以将 'Color Model' 设置为 RGB/SHB/LAB (3/4/6)。

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


获取或设置颜色点。

值：颜色点。

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


获取或设置数据。

值：数据。

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


是否对梯度进行抖动。

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


扩展计数 ( = 2 对于 Photoshop 6.0)。

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


长度 (= 32 对于 Photoshop 6.0) 没有关于其作用的信息。

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


此梯度的模式 确定 'Gradient Type' = 'Solid/Noise' (0/1)。

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


梯度的名称：Unicode 字符串，已填充。

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


获取或设置标题。

值：头部。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


插值。确定平滑度，当 'Gradient Type' = 'Solid' (GradientMode = 0)。

**Returns:**
short
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


PixelDataFormat.Rgba64Bpp 格式的最大颜色。颜色具有 ARGB 通道，每个通道为 16 位。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat.Rgba64Bpp 格式的最小颜色。颜色具有 ARGB 通道，每个通道为 16 位。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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


获取此资源所需的最低 PSD 版本。当插值方法显式存储时，需要版本 3。

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


是否反转梯度。

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


粗糙度因子 当 'Gradient type' = 'Noise' 时，我们可以分配 'Roughness' (0 - 2048)。

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


显示透明度的标志 当 'Gradient type' = 'Noise' 时，我们可以将 'Add transparency' 设为 true。

**Returns:**
short
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


获取或设置透明度点。

值：透明点。

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


使用矢量颜色的标志。

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


初始化渐变的长度。GradientLength 为只读，因此只能赋值一次。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short | 该值。 |

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


将资源数据保存到指定的流容器中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


颜色模型。当 'Gradient type' = 'Noise' 时，我们可以将 'Color Model' 设置为 RGB/SHB/LAB (3/4/6)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


获取或设置颜色点。

值：颜色点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


是否对梯度进行抖动。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


扩展计数 ( = 2 对于 Photoshop 6.0)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


此梯度的模式 确定 'Gradient Type' = 'Solid/Noise' (0/1)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


梯度的名称：Unicode 字符串，已填充。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


插值。确定平滑度，当 'Gradient Type' = 'Solid' (GradientMode = 0)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

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


PixelDataFormat.Rgba64Bpp 格式的最大颜色。颜色具有 ARGB 通道，每个通道为 16 位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp 格式的最小颜色。颜色具有 ARGB 通道，每个通道为 16 位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


是否反转梯度。

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


粗糙度因子 当 'Gradient type' = 'Noise' 时，我们可以分配 'Roughness' (0 - 2048)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


显示透明度的标志 当 'Gradient type' = 'Noise' 时，我们可以将 'Add transparency' 设为 true。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


获取或设置透明度点。

值：透明点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


使用矢量颜色的标志。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

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

