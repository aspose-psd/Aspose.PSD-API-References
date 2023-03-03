---
title: Class LinkResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource कक्ष. LinkResource वर्ग क परभषत करत है जसमें PSD प्ररूप छव में लंक क गई य एम्बेडेड फ़इलं के बरे में जनकर हत है लंक संसधन में कई शमल ह सकते हैंLinkDataSource ऐसे उदहरण जन्हें अनुक्रमणक द्वर कस भ व्युत्पन्न वर्ग में पहुँच ज सकत है
type: docs
weight: 2710
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

LinkResource वर्ग को परिभाषित करता है जिसमें PSD प्रारूप छवि में लिंक की गई या एम्बेडेड फ़ाइलों के बारे में जानकारी होती है। लिंक संसाधन में कई शामिल हो सकते हैं[`LinkDataSource`](../linkdatasource/) ऐसे उदाहरण जिन्हें अनुक्रमणिका द्वारा किसी भी व्युत्पन्न वर्ग में पहुँचा जा सकता है।

```csharp
public abstract class LinkResource : LayerResource
```

## गुण

| नाम | विवरण |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | उन लिंक डेटा स्रोतों की संख्या प्राप्त करता है जिन तक अनुक्रमणिका द्वारा पहुँचा जा सकता है। |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि यह लिंक संसाधन उदाहरण खाली है या नहीं। |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | हो जाता है[`LinkDataSource`](../linkdatasource/) निर्दिष्ट इंडेक्स पर जो लिंक डेटा स्रोत अद्वितीय पहचानकर्ता है.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | बाइट्स में PSD वैश्विक लिंक संसाधन लंबाई प्राप्त करता है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | PSD प्रारूप संस्करण प्राप्त करता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | PSD वैश्विक लिंक संसाधन हस्ताक्षर प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | संसाधन ब्लॉक डेटा सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

### यह सभी देखें

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


