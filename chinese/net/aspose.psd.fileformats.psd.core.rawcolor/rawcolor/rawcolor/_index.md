---
title: "RawColor.RawColor"
second_title: "Aspose.PSD for .NET API 参考"
description: "RawColor 构造函数。初始化 RawColor 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

初始化 [`RawColor`](../) 类的新实例。

```csharp
public RawColor(ColorComponent[] components)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 组件 | ColorComponent[] | 自定义颜色组件。 |

### 另请参阅

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

使用预定义的颜色模式，从像素数据格式初始化 [`RawColor`](../) 类的新实例。

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | 像素数据格式。 |
| colorMode | Int16 | 颜色应遵循的模式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 通道数量与 PixelFormat 不匹配，无法获取通道索引。请使用 Components 数组参数创建 RawColor |

### 另请参阅

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


