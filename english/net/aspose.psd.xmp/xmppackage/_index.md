---
title: Class XmpPackage
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Xmp.XmpPackage class. Defines the XmpPackage class that represents base abstraction for XMP package
type: docs
weight: 6330
url: /net/aspose.psd.xmp/xmppackage/
---
{{< psd/tize >}}
## XmpPackage class

Defines the XmpPackage class that represents base abstraction for XMP package.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Gets or sets the Object with the specified key. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | Gets the keys in XMP package. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Gets the namespace URI. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Gets the prefix. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | Gets the XML namespace. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Adds the value. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Clears this instance. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Determines whether the specified key contains key. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | Converts XMP value to the XML representation. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Remove the value with the specified key. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Sets the value. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Sets the XMP type value. |

### See Also

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


