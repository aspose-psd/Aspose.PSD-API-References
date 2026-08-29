---
title: "VectorPath"
second_title: "Aspose.PSD 的 Java API 参考"
description: "包含矢量路径的类。"
type: docs
weight: 17
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpath/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPath](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipath)
```
public class VectorPath implements IPath
```

包含矢量路径的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VectorPath()](#VectorPath--) | 初始化 VectorPath 的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(VectorPathDataResource vectorPathDataResource)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathDataResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | 获取路径中形状的数组。 |
| [getVersion()](#getVersion--) | 获取或设置版本。 |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | 获取或设置一个值，以指示此实例是否已禁用。 |
| [isFillStartsWithAllPixels()](#isFillStartsWithAllPixels--) | 获取或设置一个值，指示填充是否从所有像素开始。 |
| [isInverted()](#isInverted--) | 获取或设置一个值，以指示此实例是否已反转。 |
| [isNotLinked()](#isNotLinked--) | 获取或设置一个值，以指示此实例是否未链接。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | 获取或设置一个值，以指示此实例是否已禁用。 |
| [setFillStartsWithAllPixels(boolean value)](#setFillStartsWithAllPixels-boolean-) | 获取或设置一个值，指示填充是否从所有像素开始。 |
| [setInverted(boolean value)](#setInverted-boolean-) | 获取或设置一个值，以指示此实例是否已反转。 |
| [setItems(IPathShape[] shapes)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---) | 设置路径中形状的数组。 |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | 获取或设置一个值，以指示此实例是否未链接。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPath() {#VectorPath--}
```
public VectorPath()
```


初始化 VectorPath 的新实例。

### create_internalized(VectorPathDataResource vectorPathDataResource) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathDataResource-}
```
public static VectorPath create_internalized(VectorPathDataResource vectorPathDataResource)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| vectorPathDataResource | [VectorPathDataResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdataresource) |  |

**Returns:**
[VectorPath](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpath)
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
### getItems() {#getItems--}
```
public final IPathShape[] getItems()
```


获取路径中形状的数组。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape[] - IPathShape 数组。
### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取或设置版本。

值：版本。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


获取或设置一个值，以指示此实例是否已禁用。

Value:  true  如果此实例已禁用；否则为  false 。

**Returns:**
boolean
### isFillStartsWithAllPixels() {#isFillStartsWithAllPixels--}
```
public final boolean isFillStartsWithAllPixels()
```


获取或设置一个值，指示填充是否从所有像素开始。

值： 填充是否从所有像素开始。

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


获取或设置一个值，以指示此实例是否已反转。

Value:  true  如果此实例已反转；否则为  false 。

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


获取或设置一个值，以指示此实例是否未链接。

Value:  true  如果此实例未链接；否则为  false 。

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


获取或设置一个值，以指示此实例是否已禁用。

Value:  true  如果此实例已禁用；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFillStartsWithAllPixels(boolean value) {#setFillStartsWithAllPixels-boolean-}
```
public final void setFillStartsWithAllPixels(boolean value)
```


获取或设置一个值，指示填充是否从所有像素开始。

值： 填充是否从所有像素开始。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


获取或设置一个值，以指示此实例是否已反转。

Value:  true  如果此实例已反转；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setItems(IPathShape[] shapes) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---}
```
public final void setItems(IPathShape[] shapes)
```


设置路径中形状的数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| shapes | [IPathShape\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape) | IPathShape 数组。 |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


获取或设置一个值，以指示此实例是否未链接。

Value:  true  如果此实例未链接；否则为  false 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


获取或设置版本。

值：版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

