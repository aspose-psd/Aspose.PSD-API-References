---
title: XmpBasicPackage.Item
second_title: Aspose.PSD for .NET API Reference
description: XmpBasicPackage property. Gets or sets the Object with the specified key
type: docs
weight: 20
url: /net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Gets or sets the Object with the specified key.

```csharp
public override object this[string key] { get; set; }
```

| Parameter | Description |
| --- | --- |
| key | The key that identifies value. |

### Return Value

Returns the Object with the specified key.

### Property Value

The Object.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


