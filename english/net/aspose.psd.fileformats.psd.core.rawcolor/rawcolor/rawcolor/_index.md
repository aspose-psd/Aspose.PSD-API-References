---
title: RawColor.RawColor
second_title: Aspose.PSD for .NET API Reference
description: RawColor constructor. Initializes a new instance of the RawColor class
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

Initializes a new instance of the [`RawColor`](../) class.

```csharp
public RawColor(ColorComponent[] components)
```

| Parameter | Type | Description |
| --- | --- | --- |
| components | ColorComponent[] | The custom color components. |

### See Also

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

Initializes a new instance of the [`RawColor`](../) class from pixel data format using predefined color modes

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | The pixel data format. |
| colorMode | Int16 | Mode for the color to follow. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Channels count differs from PixelFormat, index of channels can not be obtained. Please create RawColor with Components' Array argument |

### See Also

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../rawcolor/)
* assembly [Aspose.PSD](../../../)


