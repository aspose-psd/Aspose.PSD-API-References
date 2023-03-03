---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: नम स्थन में PSD फ़इल स्वरूप परतें हैं.
type: docs
weight: 210
url: /hi/net/aspose.psd.fileformats.psd.layers/
---
नाम स्थान में PSD फ़ाइल स्वरूप परतें हैं.

## कक्षाओं

| कक्षा | विवरण |
| --- | --- |
| [BlendRange](./blendrange/) | ब्लेंड रेंज। |
| [ChannelInformation](./channelinformation/) | चैनल की जानकारी। |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | ग्लोबल लेयर मास्क सेक्शन. |
| [Layer](./layer/) | पीएसडी परत. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | परत सम्मिश्रण श्रेणी डेटा. |
| [LayerGroup](./layergroup/) | ग्रुप लेयर क्लास |
| [LayerHashCalculator](./layerhashcalculator/) | PSD परतों के लिए हैश कैलकुलेटर। इसका उपयोग अलग-अलग PSD फ़ाइलों में समान या अलग-अलग परतों को खोजने के लिए किया जा सकता है |
| [LayerMaskData](./layermaskdata/) | आधार LayerMaskData वर्ग को परिभाषित करता है जिसमें PSD फ़ाइल में लेयर मास्क डेटा के बारे में जानकारी होती है। यह Adobe® Photoshop® फ़ाइलों को प्रोग्रामेटिक रूप से संशोधित करने और PSD प्रारूप संपादन को स्वचालित करने में मदद कर सकता है। यदि परत में केवल एक रेखापुंज मुखौटा है तो ImageData में रेखापुंज होता है मास्क डेटा बाइट्स. यदि लेयर में केवल वेक्टर मास्क है तो ImageData में वेक्टर मास्क रैस्टराइज़्ड (कैश्ड) डेटा बाइट्स होते हैं। यदि लेयर में लेयर और वेक्टर मास्क दोनों हैं तो इमेजडेटा में रैस्टर मास्क और रैस्टराइज़्ड वेक्टर मास्क संयुक्त होते हैं। [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)बाइट्स की लंबाई समान चौड़ाई * की ऊँचाई होनी चाहिए[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. नोटिस, कि सिर्फ LayerMaskData को हटाना/जोड़ना/अपडेट करना सही सेविंग के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं होते हैं; हालांकि यह सही प्रतिपादन प्रदान कर सकता है। द[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) उसके लिए विधि का उपयोग किया जाना चाहिए। |
| [LayerMaskDataFull](./layermaskdatafull/) | LayerMaskDataFull क्लास को परिभाषित करता है जिसमें PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी होती है, जब लेयर में लेयर और वेक्टर मास्क दोनों होते हैं। अन्यथा, ए[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) उपयोग किया जाता है। इमेजडाटा में रास्टर मास्क और रास्टराइज्ड वेक्टर मास्क संयुक्त होते हैं। इमेजडाटा बाइट्स की लंबाई मास्करेक्टेंगल के बराबर होनी चाहिए। |
| [LayerMaskDataShort](./layermaskdatashort/) | LayerMaskDataShort वर्ग को परिभाषित करता है जिसमें PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी होती है जब परत में केवल रेखापुंज या वेक्टर मास्क होता है लेकिन दोनों नहीं। अन्यथा, ए[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) उपयोग किया जाता है। यदि परत में केवल एक रेखापुंज मुखौटा है, तो ImageData में रेखापुंज मुखौटा डेटा बाइट्स शामिल हैं।[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)बाइट्स की लंबाई समान चौड़ाई * की ऊँचाई होनी चाहिए[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) गुण. |
| [LayerResource](./layerresource/) | परत जानकारी का प्रतिनिधित्व करता है। |
| [LayerResourcesRegistry](./layerresourcesregistry/) | PSD फ़ाइलें लोड करने के लिए परत संसाधन रजिस्ट्री को परिभाषित करें। |
| [LinkedLayersManager](./linkedlayersmanager/) | लिंक्ड लेयर मैनेजर क्लास. |
| [SectionDividerLayer](./sectiondividerlayer/) | फ़ोल्डर (परत समूह) की सीमाओं को चिह्नित करने के लिए अनुभाग विभाजक परत . |
| [TextLayer](./textlayer/) | पाठ परत वर्ग |
## इंटरफेस

| इंटरफेस | विवरण |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | भरने की सेटिंग के लिए बेस इंटरफ़ेस |
| [ILayerResourceLoader](./ilayerresourceloader/) | परत संसाधन लोडर. |
## गणना

| गणना | विवरण |
| --- | --- |
| [LayerFlags](./layerflags/) | परत फ़्लैग करती है |
| [LayerMaskFlags](./layermaskflags/) | लेयर मास्क फ़्लैग करता है |


