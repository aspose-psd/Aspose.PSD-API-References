---
title: "ColorComponent 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | 初始化 [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/) 类的新实例。<br/> 请检查 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_depth | byte | r | 获取颜色组件/通道的位深度 |
| 描述 | 字符串 | r | 获取颜色组件的描述 |
| full_name | 字符串 | r | 获取颜色组件的完整名称，包括名称和以空格分隔的描述 |
| name | 字符串 | r | 获取颜色组件的名称。 |
| permitted_full_names [static] | 字符串 | r | 获取允许的完整名称。 |
| value | ulong | 读/写 | 获取或设置该值。 <br/> 请注意，如果您尝试设置的值超过当前位深度所能存储的范围，将会抛出异常 |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

初始化 [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/) 类的新实例。<br/> 请检查

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bit_depth | byte | 位深度。 |
| full_name | 字符串 | 完整名称。 |

