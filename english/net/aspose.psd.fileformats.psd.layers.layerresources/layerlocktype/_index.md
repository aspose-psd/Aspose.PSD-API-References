---
title: Enum LayerLockType
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LayerLockType enum. Layer lock options
type: docs
weight: 2740
url: /net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/
---
{{< psd/tize >}}
## LayerLockType enumeration

Layer lock options

```csharp
[Flags]
public enum LayerLockType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No layer lock |
| LockTransparentPixels | `1` | Partially lock a layer - Confines editing to the opaque portions of the layer. This option is equivalent to the Preserve Transparency option in earlier versions of Photoshop. |
| LockImagePixels | `2` | Partially lock a layer - Prevents modification of the layer’s pixels using the painting tools. |
| LockPosition | `4` | Partially lock a layer - Prevents the layer’s pixels from being moved. |
| LockAll | `7` | Lock all properties of a layer |

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


