---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "नेमस्पेस PSD फ़ाइल फ़ॉर्मेट लेयर्स शामिल करता है"
type: docs
weight: 230
url: /hi/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
यह namespace PSD फ़ाइल फ़ॉर्मेट लेयर्स शामिल करता है।

## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | आर्टबोर्ड लेयर क्लास। |
| [BlendRange](./blendrange/) | ब्लेंड रेंज। |
| [ChannelInformation](./channelinformation/) | चैनल जानकारी। |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | वैश्विक लेयर मास्क अनुभाग। |
| [Layer](./layer/) | psd लेयर। |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | लेयर ब्लेंडिंग रेंज डेटा। |
| [LayerGroup](./layergroup/) | ग्रुप लेयर क्लास |
| [LayerHashCalculator](./layerhashcalculator/) | PSD लेयर्स के लिए हैश कैलकुलेटर। इसे विभिन्न PSD फ़ाइलों में समान या अलग लेयर्स खोजने के लिए उपयोग किया जा सकता है। |
| [LayerMaskData](./layermaskdata/) | PSD फ़ाइल में लेयर मास्क डेटा के बारे में जानकारी रखने वाली बेस LayerMaskData क्लास को परिभाषित करता है। यह प्रोग्रामेटिक रूप से Adobe® Photoshop® फ़ाइलों को संशोधित करने और PSD फ़ॉर्मेट संपादन को स्वचालित करने में मदद कर सकता है। यदि लेयर में केवल रास्टर मास्क है तो ImageData रास्टर मास्क डेटा बाइट्स को रखता है। यदि लेयर में केवल वेक्टर मास्क है तो ImageData वेक्टर मास्क को रास्टराइज़्ड (कैश्ड) डेटा बाइट्स को रखता है। यदि लेयर में दोनों, लेयर और वेक्टर मास्क हैं तो ImageData रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क को संयुक्त रूप से रखता है। [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) बाइट्स की लंबाई Width * Height के बराबर होनी चाहिए जैसा कि [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) प्रॉपर्टीज़ में है। ध्यान दें, केवल LayerMaskData को हटाना/जोड़ना/अपडेट करना सही सहेजने के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं होते; हालांकि यह सही रेंडरिंग प्रदान कर सकता है। इसके लिए [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) मेथड का उपयोग किया जाना चाहिए। |
| [LayerMaskDataFull](./layermaskdatafull/) | PSD फ़ाइल लेयर में जब लेयर में दोनों लेयर और वेक्टर मास्क होते हैं तो मास्क डेटा के बारे में जानकारी रखने वाली LayerMaskDataFull क्लास को परिभाषित करता है। अन्यथा, एक [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) का उपयोग किया जाता है। ImageData रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क को संयुक्त रूप से रखता है। ImageData बाइट्स की लंबाई MaskRectangle.Width * MaskRectangle.Height प्रॉपर्टीज़ के बराबर होनी चाहिए। |
| [LayerMaskDataShort](./layermaskdatashort/) | जब लेयर में केवल रास्टर या वेक्टर मास्क हो लेकिन दोनों नहीं, तब PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखने वाली LayerMaskDataShort क्लास को परिभाषित करता है। अन्यथा, एक [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) का उपयोग किया जाता है। यदि लेयर में केवल रास्टर मास्क है तो ImageData रास्टर मास्क डेटा बाइट्स को रखता है। यदि लेयर में केवल वेक्टर मास्क है तो ImageData वेक्टर मास्क को रास्टराइज़्ड (कैश्ड) डेटा बाइट्स को रखता है। [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) बाइट्स की लंबाई Width * Height के बराबर होनी चाहिए जैसा कि [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) प्रॉपर्टीज़ में है। |
| [LayerResource](./layerresource/) | लेयर जानकारी का प्रतिनिधित्व करता है। |
| [LayerResourcesRegistry](./layerresourcesregistry/) | PSD फ़ाइलों के लोडिंग के लिए लेयर रिसोर्सेज रजिस्ट्री को परिभाषित करें। |
| [LinkedLayersManager](./linkedlayersmanager/) | लिंक्ड लेयर्स मैनेजर क्लास। |
| [SectionDividerLayer](./sectiondividerlayer/) | फ़ोल्डर (लेयर समूह) की सीमाओं को चिह्नित करने के लिए सेक्शन डिवाइडर लेयर। |
| [ShapeLayer](./shapelayer/) | शेप लेयर। शेप लेयर और संबंधित रिसोर्सेज के साथ कार्य की लॉजिक को संलग्न करता है। |
| [TextLayer](./textlayer/) | टेक्स्ट लेयर क्लास |
## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | फ़िल सेटिंग्स के लिए बेस इंटरफ़ेस |
| [ILayerResourceLoader](./ilayerresourceloader/) | लेयर रिसोर्स लोडर। |
| [IShapeLayer](./ishapelayer/) | शेप लेयर की प्रॉपर्टीज़ का वर्णन करता है। |
## एन्यूमरेशन

| एन्यूमरेशन | विवरण |
| --- | --- |
| [LayerFlags](./layerflags/) | लेयर फ्लैग्स |
| [LayerMaskFlags](./layermaskflags/) | लेयर मास्क फ्लैग्स |


