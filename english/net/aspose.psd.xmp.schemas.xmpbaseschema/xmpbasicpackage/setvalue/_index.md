---
title: XmpBasicPackage.SetValue
second_title: Aspose.PSD for .NET API Reference
description: XmpBasicPackage method. Sets the value
type: docs
weight: 120
url: /net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Sets the value.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | The string representation of key that is identified with added value. |
| value | IXmlValue | The value to add to. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../xmpbasicpackage/)
* assembly [Aspose.PSD](../../../)


