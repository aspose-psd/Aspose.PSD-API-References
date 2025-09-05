---
title: PsdLoadOptions.ReadOnlyType
second_title: Aspose.PSD for .NET API Reference
description: PsdLoadOptions property. Gets or sets the readonly mode used when loading a PSD image
type: docs
weight: 80
url: /net/aspose.psd.imageloadoptions/psdloadoptions/readonlytype/
---
{{< psd/tize >}}
## PsdLoadOptions.ReadOnlyType property

Gets or sets the read-only mode used when loading a PSD image.

```csharp
public ReadOnlyMode ReadOnlyType { get; set; }
```

### Property Value

One of the [`ReadOnlyMode`](../readonlymode/) values:

* !:ReadOnlyMode.None – No restrictions. Image content can be modified.
* !:ReadOnlyMode.Default – The image is fully read-only.
* !:ReadOnlyMode.MetadataEdit – Only metadata can be edited (such as [`ImageResources`](../../../aspose.psd.fileformats.psd/psdimage/imageresources/)), while image pixel content remains read-only.

### See Also

* enum [ReadOnlyMode](../../readonlymode/)
* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


