---
title: PsdOptions.UpdateMetadata
second_title: Aspose.PSD for .NET API Reference
description: PsdOptions property. Gets or sets a value indicating whether update metadata. If the value is true the metadata will be updated while saving an image
type: docs
weight: 100
url: /net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Gets or sets a value indicating whether [update metadata]. If the value is true, the metadata will be updated while saving an image.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` if [update metadata]; otherwise, `false`.

## Examples

The following code demonstrates the using UpdateMetadata option to update CreatorTool value in xmp data.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // If you want the creator tool to change, make sure that the "UpdateMetadata" property is set to true. It's set to true by default.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Saving the image. 
    image.Save(path, psdOptions);

    // Checking creator tool in code.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Here will be updated creator tool info.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### See Also

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


