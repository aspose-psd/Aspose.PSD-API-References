---
title: Class XmpPacketWrapper
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Xmp.XmpPacketWrapper कक्ष. में हेडर और ट्रेलर सहत क्रमबद्ध xmp पैकेज शमल है
type: docs
weight: 6290
url: /hi/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

में हेडर और ट्रेलर सहित क्रमबद्ध xmp पैकेज शामिल है।

```csharp
public class XmpPacketWrapper
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`XmpPacketWrapper` वर्ग. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | का एक नया उदाहरण प्रारंभ करता है`XmpPacketWrapper` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | हेडर प्रोसेसिंग निर्देश प्राप्त करता है। |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | XMP मेटा प्राप्त करता है। वैकल्पिक. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | की सरणी प्राप्त करता है[`XmpPackage`](../xmppackage/) XMP. के अंदर |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | एक्सएमपी संरचना के अंदर पैकेज की मात्रा प्राप्त करता है। |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | ट्रेलर प्रोसेसिंग निर्देश प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | पैकेज जोड़ता है। |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | सभी को हटा देता है[`XmpPackage`](../xmppackage/) XMP. के अंदर |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | निर्धारित करता है कि पैकेज xmp आवरण में मौजूद है या नहीं। |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | नेमस्पेस URI. द्वारा पैकेज प्राप्त करता है |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | XMP पैकेज को हटाता है। |

### टिप्पणियों

एक रैपर जिसमें XML प्रोसेसिंग निर्देश (PIs) की एक जोड़ी होती है, को rdf:RDF तत्व के आसपास रखा जा सकता है।

### यह सभी देखें

* नाम स्थान [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* सभा [Aspose.PSD](../../)


