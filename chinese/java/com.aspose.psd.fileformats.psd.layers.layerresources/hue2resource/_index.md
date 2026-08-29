---
title: "Hue2Resource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "类 Hue2Resource。"
type: docs
weight: 36
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class Hue2Resource extends AdjustmentLayerResource
```

类 Hue2Resource。Exposure Adjustment Layer 的资源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Hue2Resource()](#Hue2Resource--) | 初始化 [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) 类的新实例。 |
| [Hue2Resource(byte[] data)](#Hue2Resource-byte---) | 初始化 [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
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
| [getColorize()](#getColorize--) | 获取或设置一个值，指示此 [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) 是否为彩色化。 |
| [getData()](#getData--) | 获取或设置数据。 |
| [getHeader_internalized()](#getHeader-internalized--) | 获取或设置标题。 |
| [getHue()](#getHue--) | 获取或设置主色相。 |
| [getKey()](#getKey--) | 获取图层资源键。 |
| [getLength()](#getLength--) | 获取图层资源长度（字节）。 |
| [getLightness()](#getLightness--) | 获取或设置主亮度。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 获取前缀长度。 |
| [getPsdVersion()](#getPsdVersion--) | 获取图层资源所需的最小 psd 版本。 |
| [getRanges()](#getRanges--) | 获取 Hue/Saturation Adjustment Layer 的范围。 |
| [getSaturation()](#getSaturation--) | 获取或设置主饱和度。 |
| [getSignature()](#getSignature--) | 获取图层资源签名。 |
| [getVersion()](#getVersion--) | 获取版本。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 确定资源是否为 PSB specific。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 获取指示此实例是否为资源 PSB specific 的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 将资源保存到指定的流容器。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 保存自定义资源头部。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 保存头部签名、标识符和长度。 |
| [setColorize(boolean value)](#setColorize-boolean-) | 获取或设置一个值，指示此 [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) 是否为彩色化。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 获取或设置标题。 |
| [setHue(short value)](#setHue-short-) | 获取或设置主色相。 |
| [setLightness(short value)](#setLightness-short-) | 获取或设置主亮度。 |
| [setRanges(ColorRangeHsl[] value)](#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---) | 获取 Hue/Saturation Adjustment Layer 的范围。 |
| [setSaturation(short value)](#setSaturation-short-) | 获取或设置主饱和度。 |
| [setVersion(short value)](#setVersion-short-) | 获取版本。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hue2Resource() {#Hue2Resource--}
```
public Hue2Resource()
```


初始化 [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) 类的新实例。

### Hue2Resource(byte[] data) {#Hue2Resource-byte---}
```
public Hue2Resource(byte[] data)
```


初始化 [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 资源的数据。 |

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
### getColorize() {#getColorize--}
```
public final boolean getColorize()
```


获取或设置一个值，指示此 [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) 是否为彩色化。

值：  true  如果着色；否则，  false 。

**Returns:**
boolean
### getData() {#getData--}
```
public final byte[] getData()
```


获取或设置数据。

值：数据。

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


获取或设置标题。

值：头部。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHue() {#getHue--}
```
public final short getHue()
```


获取或设置主色相。

值：主色相。

**Returns:**
short
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
### getLightness() {#getLightness--}
```
public final short getLightness()
```


获取或设置主亮度。

值：主亮度。

**Returns:**
short
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
### getRanges() {#getRanges--}
```
public final ColorRangeHsl[] getRanges()
```


获取 Hue/Saturation Adjustment Layer 的范围。PS 中的范围如果被更改，名称可能会变化，因此我们应通过索引进行操作。

值：范围。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl[]
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


获取或设置主饱和度。

值：主饱和度。

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


获取图层资源签名。

**Returns:**
int
### getVersion() {#getVersion--}
```
public final short getVersion()
```


获取版本。默认是 2

值：版本。

**Returns:**
short
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

### setColorize(boolean value) {#setColorize-boolean-}
```
public final void setColorize(boolean value)
```


获取或设置一个值，指示此 [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) 是否为彩色化。

值：  true  如果着色；否则，  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


获取或设置主色相。

值：主色相。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


获取或设置主亮度。

值：主亮度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setRanges(ColorRangeHsl[] value) {#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---}
```
public void setRanges(ColorRangeHsl[] value)
```


获取 Hue/Saturation Adjustment Layer 的范围。PS 中的范围如果被更改，名称可能会变化，因此我们应通过索引进行操作。

值：范围。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [ColorRangeHsl\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


获取或设置主饱和度。

值：主饱和度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


获取版本。默认是 2

值：版本。

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

