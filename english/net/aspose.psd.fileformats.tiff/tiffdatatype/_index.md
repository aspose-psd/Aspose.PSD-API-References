---
title: TiffDataType
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 4010
url: /net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

The tiff data type.

```csharp
public abstract class TiffDataType : IComparable
```

## Properties

| Name | Description |
| --- | --- |
| [AlignedDataSize](aligneddatasize) { get; } | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| abstract [Count](count) { get; } | Gets the count of elements. |
| abstract [DataSize](datasize) { get; } | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| [Id](id) { get; } | Gets tag id integer representation. |
| [IsValid](isvalid) { get; } | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| [TagId](tagid) { get; } | Gets the tag id. |
| abstract [TagType](tagtype) { get; } | Gets the tag type. |
| abstract [Value](value) { get; set; } | Gets or sets the value this data type contains. |

## Methods

| Name | Description |
| --- | --- |
| static [ReadTag](readtag)(TiffStreamReader, long) | Reads the tag data. |
| [CompareTo](compareto)(object) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| virtual [DeepClone](deepclone)() | Performs a deep clone of this instance. |
| override [ToString](tostring)() | Returns a String that represents this instance. |
| abstract [WriteAdditionalData](writeadditionaldata)(TiffStreamWriter) | Writes the additional tag data. |
| [WriteTag](writetag)(TiffStreamWriter, long) | Writes the tag data. |

### See Also

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->