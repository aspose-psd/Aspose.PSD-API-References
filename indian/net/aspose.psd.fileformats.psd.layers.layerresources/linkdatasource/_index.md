---
title: Class LinkDataSource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource कक्ष. LinkDataSource वर्ग क परभषत करत है जसमें लंक क गई फ़इल य PSD फ़इल में संपत्त के बरे में जनकर हत है
type: docs
weight: 2690
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
## LinkDataSource class

LinkDataSource वर्ग को परिभाषित करता है जिसमें लिंक की गई फ़ाइल या PSD फ़ाइल में संपत्ति के बारे में जानकारी होती है।

```csharp
public abstract class LinkDataSource
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि क्या PSD संपत्ति लॉक है। |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Adobe® Photoshop® СС पुस्तकालयों की संपत्ति के लिए संपत्ति संशोधित समय प्राप्त या सेट करता है। |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Lnk2 / LnkE Adobe® Photoshop® संसाधन के liFE या liFD डेटा स्रोत में बाल दस्तावेज़ पहचानकर्ता प्राप्त या सेट करता है। |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | चाइल्ड दस्तावेज़ के लिए वर्तमान में चयनित COMP की आईडी प्राप्त या सेट करता है, जो -1 होगा यदि कोई भी चयनित नहीं है। Comps पृष्ठ लेआउट की रचनाएँ हैं जो डिज़ाइनर बना सकते हैं। लेयर कंप्स का उपयोग करके, आप एक ही Adobe® Photoshop® फ़ाइल में लेआउट के कई संस्करण बना, प्रबंधित और देख सकते हैं। एक परत कॉम्प परत पैनल की स्थिति का एक स्नैपशॉट है। परत कम्पास तीन प्रकार के परत विकल्पों को सहेजते हैं लेकिन यह संपत्ति स्मार्ट वस्तुओं के लिए परत कॉम्प चयन पहचानकर्ता प्राप्त करती है। [स्मार्ट ऑब्जेक्ट्स में लेयर कंप्स](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | फ़ाइल निर्माता को PSD प्रारूप LnkE / Lnk2 संसाधन में प्राप्त या सेट करता है। |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | एम्बेडेड या बाहरी फ़ाइल के प्रकार को प्राप्त या सेट करता है जिसमें Adobe® Photoshop® Lnk2 / LnkE संसाधन शामिल है या लिंक करता है। |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | यह इंगित करने वाला मान प्राप्त या सेट करता है कि क्या इस लिंक डेटा स्रोत में फ़ाइल ओपन डिस्क्रिप्टर है: CompId और OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि क्या यह PSD लिंक डेटा स्रोत Adobe® Photoshop® СС लाइब्रेरी आइटम से लिंक करता है। |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | बाइट्स में लिंक डेटा स्रोत की लंबाई प्राप्त करता है। |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | चाइल्ड दस्तावेज़ के लिए वर्तमान में चयनित कॉम्प की मूल आईडी प्राप्त करता है, जो -1 होगा यदि कोई भी चयनित नहीं है। यह संपत्ति स्मार्ट ऑब्जेक्ट्स के लिए मूल परत कॉम्प चयन पहचानकर्ता प्राप्त करती है। [स्मार्ट ऑब्जेक्ट्स में लेयर कंप्स](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Adobe® Photoshop® वैश्विक लिंक संसाधन में डेटा स्रोत का मूल फ़ाइल नाम प्राप्त करता है। |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Adobe® Photoshop® वैश्विक लिंक डेटा स्रोत प्रकार प्राप्त करता है जो निम्न में से एक या कोई नहीं हो सकता है: एम्बेड की गई लिंक की गई फ़ाइल liFD जो कि PSD Lnk2Resource के अनुरूप है बाहरी लिंक की गई फ़ाइल liFE जो PSD LnkeResource लिंक की गई फ़ाइल उपनाम liFA से मेल खाती है |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | PSD लिंक संसाधन में डेटा स्रोत का वैश्विक विशिष्ट पहचानकर्ता प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | PSD LnkE / Lnk2 संसाधन में डेटा स्रोत का संस्करण प्राप्त करता है। |

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


