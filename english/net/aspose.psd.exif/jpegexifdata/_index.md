---
title: JpegExifData
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 990
url: /net/aspose.psd.exif/jpegexifdata/
---
## JpegExifData class

EXIF data container for jpeg files.

```csharp
public sealed class JpegExifData : ExifData
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegExifData](jpegexifdata)() | Initializes a new instance of the [`JpegExifData`](../jpegexifdata) class. |
| [JpegExifData](jpegexifdata)(TiffDataType[]) | Initializes a new instance of the [`JpegExifData`](../jpegexifdata) class with data from array. |
| [JpegExifData](jpegexifdata)(TiffDataType[], TiffDataType[], TiffDataType[]) | Initializes a new instance of the [`JpegExifData`](../jpegexifdata) class with data from array. |

## Properties

| Name | Description |
| --- | --- |
| [Artist](artist) { get; set; } | Gets or sets the artist. |
| [BitsPerSample](bitspersample) { get; set; } | Gets or sets the bits per sample. |
| [Compression](compression) { get; set; } | Gets or sets the compression. |
| [Copyright](copyright) { get; set; } | Gets or sets the copyright. |
| [DateTime](datetime) { get; set; } | Gets or sets the date time. |
| [ImageDescription](imagedescription) { get; set; } | Gets or sets the image description. |
| [ImageLength](imagelength) { get; set; } | Gets or sets the image length. |
| [ImageWidth](imagewidth) { get; set; } | Gets or sets the image width. |
| [Make](make) { get; set; } | Gets or sets the manufacturer of the recording equipment. |
| [Model](model) { get; set; } | Gets or sets the model. |
| [Orientation](orientation) { get; set; } | Gets or sets the orientation. |
| [PhotometricInterpretation](photometricinterpretation) { get; set; } | Gets or sets the photometric interpretation. |
| [PlanarConfiguration](planarconfiguration) { get; set; } | Gets or sets the planar configuration. |
| [PrimaryChromaticities](primarychromaticities) { get; set; } | Gets or sets the chromaticity of the three primary colors of the image. |
| [ReferenceBlackWhite](referenceblackwhite) { get; set; } | Gets or sets the reference black white. |
| [ResolutionUnit](resolutionunit) { get; set; } | Gets or sets the resolution unit. |
| [SamplesPerPixel](samplesperpixel) { get; set; } | Gets or sets the samples per pixel. |
| [Software](software) { get; set; } | Gets or sets the software. |
| [Thumbnail](thumbnail) { get; set; } | Gets or sets the thumbnail image. |
| [TransferFunction](transferfunction) { get; set; } | Gets or sets the transfer function. |
| [XResolution](xresolution) { get; set; } | Gets or sets the x resolution. |
| [YCbCrCoefficients](ycbcrcoefficients) { get; set; } | Gets or sets the matrix coefficients for transformation from RGB to YCbCr image data. |
| [YCbCrPositioning](ycbcrpositioning) { get; set; } | Gets or sets the position of chrominance components in relation to the luminance component. |
| [YCbCrSubSampling](ycbcrsubsampling) { get; set; } | Gets or sets the sampling ratio of chrominance components in relation to the luminance component. |
| [YResolution](yresolution) { get; set; } | Gets or sets the y resolution. |

## Methods

| Name | Description |
| --- | --- |
| [SerializeExifData](serializeexifdata)() | Serializes the EXIF data. Writes the tags values and contents. The most influencing size tag is Thumbnail tag contents. |

## Other Members

| Name | Description |
| --- | --- |
| const [MaxExifSegmentSize](maxexifsegmentsize) | The maximum EXIF segment size in bytes allowed. |

### See Also

* class [ExifData](../exifdata)
* namespace [Aspose.PSD.Exif](../../aspose.psd.exif)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->