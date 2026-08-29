---
title: "क्लास LinkDataSource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource क्लास। LinkDataSource क्लास को परिभाषित करता है जो PSD फ़ाइल में लिंक की गई फ़ाइल या एसेट के बारे में जानकारी रखता है।"
type: docs
weight: 2990
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
{{< psd/tize >}}
## LinkDataSource class

LinkDataSource क्लास को परिभाषित करता है जो PSD फ़ाइल में लिंक्ड फ़ाइल या एसेट के बारे में जानकारी रखता है।

```csharp
public abstract class LinkDataSource
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | PSD एसेट लॉक है या नहीं यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। Adobe® Photoshop® СС Libraries एसेट्स के लिए एसेट लॉक स्थिति। |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Adobe® Photoshop® СС Libraries एसेट्स के लिए एसेट संशोधित समय प्राप्त करता है या सेट करता है। |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Lnk2 / LnkE Adobe® Photoshop® रिसोर्स के liFE या liFD डेटा स्रोत में चाइल्ड डॉक्यूमेंट पहचानकर्ता प्राप्त करता है या सेट करता है। |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | चाइल्ड डॉक्यूमेंट के लिए वर्तमान में चयनित कंप का ID प्राप्त करता है या सेट करता है, यदि कोई चयनित नहीं है तो यह -1 होगा। कंप्स पेज लेआउट की संरचनाएँ हैं जिन्हें डिज़ाइनर बना सकते हैं। लेयर कंप्स का उपयोग करके आप एक ही Adobe® Photoshop® फ़ाइल में लेआउट के कई संस्करण बना, प्रबंधित और देख सकते हैं। लेयर कंप लेयर्स पैनल की स्थिति का स्नैपशॉट है। लेयर कंप्स तीन प्रकार के लेयर विकल्प सहेजते हैं लेकिन यह प्रॉपर्टी स्मार्ट ऑब्जेक्ट्स के लिए लेयर कंप चयन पहचानकर्ता प्राप्त करती है। [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | PSD फ़ॉर्मेट LnkE / Lnk2 रिसोर्स में फ़ाइल निर्माता प्राप्त करता है या सेट करता है। |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Adobe® Photoshop® Lnk2 / LnkE रिसोर्स द्वारा शामिल या लिंक की गई एम्बेडेड या बाहरी फ़ाइल का प्रकार प्राप्त करता है या सेट करता है। |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | इस लिंक डेटा स्रोत में फ़ाइल ओपन डिस्क्रिप्टर: CompId और OriginalCompId है या नहीं यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | यह दर्शाने वाला मान प्राप्त करता है कि यह PSD लिंक डेटा स्रोत Adobe® Photoshop® СС Library आइटम से लिंक करता है या नहीं। |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | लिंक डेटा स्रोत की लंबाई बाइट्स में प्राप्त करता है। |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | चाइल्ड डॉक्यूमेंट के लिए वर्तमान में चयनित कंप का मूल ID प्राप्त करता है, यदि कोई चयनित नहीं है तो यह -1 होगा। यह प्रॉपर्टी स्मार्ट ऑब्जेक्ट्स के लिए मूल लेयर कंप चयन पहचानकर्ता प्राप्त करती है। [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Adobe® Photoshop® ग्लोबल लिंक रिसोर्स में डेटा स्रोत का मूल फ़ाइल नाम प्राप्त करता है। |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Adobe® Photoshop® ग्लोबल लिंक डेटा स्रोत प्रकार प्राप्त करता है जो निम्नलिखित में से एक हो सकता है या कोई नहीं: PSD Lnk2Resource से संबंधित एम्बेडेड लिंक्ड फ़ाइल liFD, PSD LnkeResource से संबंधित बाहरी लिंक्ड फ़ाइल liFE, लिंक्ड फ़ाइल उपनाम liFA। |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | PSD लिंक रिसोर्स में डेटा स्रोत का ग्लोबल यूनिक आइडेंटिफायर प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | PSD LnkE / Lnk2 रिसोर्स में डेटा स्रोत का संस्करण प्राप्त करता है। |

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


