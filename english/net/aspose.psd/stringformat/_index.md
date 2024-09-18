---
title: Class StringFormat
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.StringFormat class. Encapsulates text layout information such as alignment orientation and tab stops display manipulations such as ellipsis insertion and national digit substitution and OpenType features. This class cannot be inherited
type: docs
weight: 6040
url: /net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

```csharp
public sealed class StringFormat : DisposableObject
```

## Constructors

| Name | Description |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Initializes a new `StringFormat` object. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Initializes a new `StringFormat` object from the specified existing `StringFormat` object. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Initializes a new `StringFormat` object with the specified [`StringFormatFlags`](../stringformatflags/) enumeration and language. |

## Properties

| Name | Description |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Gets a generic default `StringFormat` object. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Gets a generic typographic `StringFormat` object. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Gets or sets text alignment information on the vertical plane. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Gets or sets the custom character ident. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Gets or sets the language that is used when local digits are substituted for western digits. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Gets or sets the method to be used for digit substitution. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Gets the number of spaces between the beginning of a line of text and the first tab stop. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Gets or sets a [`StringFormatFlags`](../stringformatflags/) enumeration that contains formatting information. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Gets or sets the [`HotkeyPrefix`](../hotkeyprefix/) object for this `StringFormat` object. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Gets or sets the line alignment on the horizontal plane. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Gets an array of distances between tab stops in the units specified by the [`PageUnit`](../graphics/pageunit/) property. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Gets or sets the [`StringTrimming`](../stringtrimming/) enumeration for this `StringFormat` object. |

## Methods

| Name | Description |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Creates a deep clone of this `StringFormat` object. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Check if objects are equal. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Get hash code of the current object. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Sets tab stops for this `StringFormat` object. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Converts this `StringFormat` object to a human-readable string. |

### See Also

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


