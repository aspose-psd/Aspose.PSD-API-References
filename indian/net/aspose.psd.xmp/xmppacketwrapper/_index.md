---
title: "क्लास XmpPacketWrapper"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Xmp.XmpPacketWrapper क्लास। हेडर और ट्रेलर सहित सीरियलाइज़्ड XMP पैकेज शामिल करता है"
type: docs
weight: 6790
url: /hi/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

हेडर और ट्रेलर सहित सीरियलाइज़्ड xmp पैकेज को शामिल करता है।

```csharp
public class XmpPacketWrapper
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | `XmpPacketWrapper` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | `XmpPacketWrapper` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | हेडर प्रोसेसिंग इंस्ट्रक्शन प्राप्त करता है। |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | XMP मेटा प्राप्त करता है। वैकल्पिक। |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | XMP के अंदर [`XmpPackage`](../xmppackage/) की सरणी प्राप्त करता है। |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | XMP संरचना के अंदर पैकेजों की संख्या प्राप्त करता है। |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | ट्रेलर प्रोसेसिंग इंस्ट्रक्शन प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | पैकेज जोड़ता है। |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | XMP के अंदर सभी [`XmpPackage`](../xmppackage/) हटाता है। |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | निर्धारित करता है कि पैकेज XMP रैपर में मौजूद है या नहीं। |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | नेमस्पेस URI द्वारा पैकेज प्राप्त करता है। |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | XMP पैकेज को हटाता है। |

## टिप्पणियाँ

एक रैपर जिसमें दो XML प्रोसेसिंग इंस्ट्रक्शन (PIs) की जोड़ी होती है, rdf:RDF तत्व के चारों ओर रखा जा सकता है।

### देखें भी

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


