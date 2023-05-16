---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD for .NET API Reference
description: SmartObjectLayer property. Gets or sets the smart object layer contents. The embedded smart object contents is the embedded raw image file Data and its properties. The linked smart object contents is the raw content of the linked image file if it is available and its properties LiFeDataSource. We do not support loading from the Adobe Photoshop  Graphics Library when IsLibraryLink is true. For regular link files at first we use RelativePath to look for the file relatively to the source image path SourceImagePath if it is not available we look at FullPath if not then we look for the link file in the same directory where our image is SourceImagePath
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
{{< psd/tize >}}
## SmartObjectLayer.Contents property

Gets or sets the smart object layer contents. The embedded smart object contents is the embedded raw image file: [`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) and its properties. The linked smart object contents is the raw content of the linked image file if it is available and its properties: [`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). We do not support loading from the Adobe� Photoshop� �� Graphics Library when [`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) is true. For regular link files, at first, we use [`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) to look for the file relatively to the source image path SourceImagePath, if it is not available we look at [`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), if not then we look for the link file in the same directory where our image is: SourceImagePath.

```csharp
public byte[] Contents { get; set; }
```

### Property Value

The byte[] smart object layer contents.

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | Cannot get contents from Adobe� Photoshop� �� library. |

## Examples

The following code demonstrates the support of Embedded Smart objects.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// This example demonstrates how to change the smart object layer in the PSD file and export / update smart object original embedded contents.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Let's export the embedded smart object image from the PSD smart object layer
        smartObjectLayer.ExportContents(exportPath);

        // Let's check if the original image is saved correctly
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Let's invert original smart object image
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Let's replace the embedded smart object image in the PSD layer
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Let's check if the updated image is saved correctly
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### See Also

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* assembly [Aspose.PSD](../../../)


