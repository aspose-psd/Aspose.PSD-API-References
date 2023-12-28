---
title: XmpBasicPackage.ContainsKey
second_title: Aspose.PSD for .NET API Reference
description: XmpBasicPackage method. Determines whether the specified key contains key
type: docs
weight: 40
url: /net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

Determines whether the specified key contains key.

```csharp
public override bool ContainsKey(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | The key to be checked. |

### Return Value

Returns true if the specified key contains key.

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
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../xmpbasicpackage/)
* assembly [Aspose.PSD](../../../)


