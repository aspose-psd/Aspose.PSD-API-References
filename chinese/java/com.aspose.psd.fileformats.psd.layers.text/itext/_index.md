---
title: "IText"
second_title: "Aspose.PSD 的 Java API 参考"
description: "文本图层的文本编辑接口"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

文本图层的文本编辑接口
## Methods

| Method | 描述 |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | 在末尾添加文本部分 |
| [getItems()](#getItems--) | 获取项目。 |
| [getText()](#getText--) | 获取文本。 |
| [getTextOrientation()](#getTextOrientation--) | 获取或设置文本方向。 |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | 将 [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) 插入指定位置 |
| [producePortion()](#producePortion--) | 使用默认参数生成新的部分 |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 使用输入或默认参数生成新的部分。 |
| [removePortion(int index)](#removePortion-int-) | 删除指定索引处的部分 |
| [setTextOrientation(int value)](#setTextOrientation-int-) | 获取或设置文本方向。 |
| [updateLayerData()](#updateLayerData--) | 更新图层数据。 |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


在末尾添加文本部分

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | 该部分。 |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


获取项目。

值：项目。

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


获取文本。

Value: 文本。

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


获取或设置文本方向。

值：文本方向。

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


将 [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) 插入指定位置

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | 该部分。 |
| index | int | 该索引。 |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


使用默认参数生成新的部分

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


使用输入或默认参数生成新的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | 用于创建新的 ITextPortion 的文本部分。 |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | 如果不为 null，则将在新的   中应用该样式，否则将使用默认值。 |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | 如果不为 null，则将在新的   中应用的段落，否则将使用默认值。 |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - 根据输入参数返回新的 ITextPortion 部分。
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


删除指定索引处的部分

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | int | 该索引。 |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


获取或设置文本方向。

值：文本方向。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


更新图层数据。

