---
title: "Font 类"
type: docs
weight: 1340
url: /zh/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | 使用指定的大小初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。字符集被设置为 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)，字体样式设置为 [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/)。 |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | 使用指定的大小和样式初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。字符集被设置为 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)。 |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | 使用指定的大小、样式和单位初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。 |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | 使用指定的大小、样式、单位和字符集初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。 |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | 使用指定的大小和单位初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。字符集被设置为 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)，样式被设置为 [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/)。 |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | 初始化一个使用指定现有 [Font](/psd/python-net/aspose.psd/font/) 和 [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 枚举的新 [Font](/psd/python-net/aspose.psd/font/)。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bold | bool | r | 获取一个值，指示此 [Font](/psd/python-net/aspose.psd/font/) 是否为粗体。 |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | 获取一个字节值，指定此 [Font](/psd/python-net/aspose.psd/font/) 使用的字符集。 |
| italic | bool | r | 获取一个值，指示此 [Font](/psd/python-net/aspose.psd/font/) 是否为斜体。 |
| name | string | r | 获取此 [Font](/psd/python-net/aspose.psd/font/) 的字体名称。 |
| size | float | r | 获取此 [Font](/psd/python-net/aspose.psd/font/) 的 em 大小，单位为 [Font.unit](/psd/python-net/aspose.psd/font/) 属性指定的单位。 |
| strikeout | bool | r | 获取一个值，指示此 [Font](/psd/python-net/aspose.psd/font/) 是否在字体上指定水平划线。 |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | 获取此 [Font](/psd/python-net/aspose.psd/font/) 的样式信息。 |
| underline | bool | r | 获取一个值，指示此 [Font](/psd/python-net/aspose.psd/font/) 是否带下划线。 |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | 获取此 [Font](/psd/python-net/aspose.psd/font/) 的度量单位。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 创建此 [Font](/psd/python-net/aspose.psd/font/) 的精确深拷贝。 |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

使用指定的大小初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。字符集被设置为 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)，字体样式设置为 [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em-size（以点为单位）。 |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

使用指定的大小和样式初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。字符集被设置为 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)，图形单位设置为 [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em-size（以点为单位）。 |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 新字体的 [FontStyle](/psd/python-net/aspose.psd/fontstyle/)。 |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

使用指定的大小、样式和单位初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em-size，使用 <paramref name=\"unit\" /> 参数指定的单位。 |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 新字体的 [FontStyle](/psd/python-net/aspose.psd/fontstyle/)。 |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 新字体的 [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)。 |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

使用指定的大小、样式、单位和字符集初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em-size，使用 <paramref name=\"unit\" /> 参数指定的单位。 |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 新字体的 [FontStyle](/psd/python-net/aspose.psd/fontstyle/)。 |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 新字体的 [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)。 |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | 此字体使用的字符集。 |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

使用指定的大小和单位初始化一个新的 [Font](/psd/python-net/aspose.psd/font/)。字符集被设置为 [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/)，样式被设置为 [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) 名称的字符串表示形式。 |
| em_size | float | 新字体的 em-size，使用 <paramref name=\"unit\" /> 参数指定的单位。 |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 新字体的 [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)。 |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

初始化一个使用指定现有 [Font](/psd/python-net/aspose.psd/font/) 和 [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 枚举的新 [Font](/psd/python-net/aspose.psd/font/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 用于创建新 [Font](/psd/python-net/aspose.psd/font/) 的现有 [Font](/psd/python-net/aspose.psd/font/)。 |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | 要应用于新 [Font](/psd/python-net/aspose.psd/font/) 的 [FontStyle](/psd/python-net/aspose.psd/fontstyle/)。可以使用 OR 运算符组合 [FontStyle](/psd/python-net/aspose.psd/fontstyle/) 枚举的多个值。 |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

创建此 [Font](/psd/python-net/aspose.psd/font/) 的精确深拷贝。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 此方法创建的 [Font](/psd/python-net/aspose.psd/font/)。 |


