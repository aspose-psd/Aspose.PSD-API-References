---
title: StringFormat
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5520
url: /net/aspose.psd/stringformat/
---
## StringFormat class

Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

```csharp
public sealed class StringFormat : DisposableObject
```

## Constructors

| Name | Description |
| --- | --- |
| [StringFormat](stringformat)() | Initializes a new [`StringFormat`](../stringformat) object. |
| [StringFormat](stringformat)(StringFormat) | Initializes a new [`StringFormat`](../stringformat) object from the specified existing [`StringFormat`](../stringformat) object. |
| [StringFormat](stringformat)(StringFormatFlags) | Initializes a new [`StringFormat`](../stringformat) object with the specified [`StringFormatFlags`](../stringformatflags) enumeration and language. |

## Properties

| Name | Description |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault) { get; } | Gets a generic default [`StringFormat`](../stringformat) object. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic) { get; } | Gets a generic typographic [`StringFormat`](../stringformat) object. |
| [Alignment](../../aspose.psd/stringformat/alignment) { get; set; } | Gets or sets text alignment information on the vertical plane. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage) { get; set; } | Gets or sets the language that is used when local digits are substituted for western digits. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod) { get; set; } | Gets or sets the method to be used for digit substitution. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset) { get; } | Gets the number of spaces between the beginning of a line of text and the first tab stop. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags) { get; set; } | Gets or sets a [`StringFormatFlags`](../stringformatflags) enumeration that contains formatting information. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix) { get; set; } | Gets or sets the [`HotkeyPrefix`](../hotkeyprefix) object for this [`StringFormat`](../stringformat) object. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment) { get; set; } | Gets or sets the line alignment on the horizontal plane. |
| [TabStops](../../aspose.psd/stringformat/tabstops) { get; } | Gets an array of distances between tab stops in the units specified by the [`PageUnit`](../graphics/pageunit) property. |
| [Trimming](../../aspose.psd/stringformat/trimming) { get; set; } | Gets or sets the [`StringTrimming`](../stringtrimming) enumeration for this [`StringFormat`](../stringformat) object. |

## Methods

| Name | Description |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone)() | Creates a deep clone of this [`StringFormat`](../stringformat) object. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Disposes the current instance. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops)(float, float[]) | Sets tab stops for this [`StringFormat`](../stringformat) object. |
| override [ToString](../../aspose.psd/stringformat/tostring)() | Converts this [`StringFormat`](../stringformat) object to a human-readable string. |

### See Also

* class [DisposableObject](../disposableobject)
* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
