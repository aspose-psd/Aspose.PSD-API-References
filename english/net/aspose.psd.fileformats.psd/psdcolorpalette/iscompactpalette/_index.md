---
title: IsCompactPalette
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

Gets a value indicating whether compact it palette.

```csharp
public bool IsCompactPalette { get; }
```

## Property Value

`true` if compact it palette; otherwise, `false`.

### Remarks

Compact palette means that image will contain only the specified palette entries if possible or in other words the image will be more compact and occupy less space; otherwise there will be 2^BitsPerPixel entries and image will reserve more space for all possible palette entries. Setting this value to true and changing palette entries may cause performance penalty since data movement may occur so use it carefully.

### See Also

* class [PsdColorPalette](../../psdcolorpalette)
* namespace [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
