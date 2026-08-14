---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /hi/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **क्लास** | **विवरण** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | आर्टबोर्ड लेयर क्लास। |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | ब्लेंड रेंज। |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | चैनल जानकारी। |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | ग्लोबल लेयर मास्क सेक्शन। |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | फ़िल सेटिंग्स के लिए बेस इंटरफ़ेस |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | लेयर रिसोर्स लोडर। |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Shape लेयर की विशेषताओं का वर्णन करता है। |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | psd लेयर। |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | लेयर ब्लेंडिंग रेंजेज़ डेटा। |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | ग्रुप लेयर क्लास |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | PSD लेयर्स के लिए हैश कैलकुलेटर। यह विभिन्न PSD फ़ाइलों में समान या अलग लेयर्स खोजने के लिए उपयोग किया जा सकता है। |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | PSD फ़ाइल में लेयर मास्क डेटा के बारे में जानकारी रखने वाली बेस LayerMaskData क्लास को परिभाषित करता है।<br/>            यह प्रोग्रामेटिक रूप से Adobe® Photoshop® फ़ाइलों को संशोधित करने और PSD फ़ॉर्मेट संपादन को स्वचालित करने में मदद कर सकता है।<br/>            यदि लेयर में केवल रास्टर मास्क है तो ImageData रास्टर मास्क डेटा बाइट्स रखती है।<br/>            यदि लेयर में केवल वेक्टर मास्क है तो ImageData वेक्टर मास्क को रास्टराइज़्ड (कैश्ड) डेटा बाइट्स रखती है।<br/>            यदि लेयर में दोनों, लेयर और वेक्टर मास्क हैं तो ImageData रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क को संयुक्त रूप से रखती है।<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) बाइट्स की लंबाई [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) प्रॉपर्टीज़ के Width * Height के बराबर होनी चाहिए।<br/>            ध्यान दें, केवल LayerMaskData को हटाना / जोड़ना / अपडेट करना सही सहेजने के लिए पर्याप्त नहीं है<br/>            क्योंकि चैनल अपडेट नहीं होते; हालांकि यह सही रेंडरिंग प्रदान कर सकता है।<br/>            इस हेतु [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) मेथड का उपयोग किया जाना चाहिए। |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखने वाली LayerMaskDataFull क्लास को परिभाषित करता है<br/>            जब लेयर में दोनों, लेयर और वेक्टर मास्क होते हैं। अन्यथा, एक [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) उपयोग किया जाता है।<br/>            ImageData रास्टर मास्क और रास्टराइज़्ड वेक्टर मास्क को संयुक्त रूप से रखती है।<br/>            ImageData बाइट्स की लंबाई MaskRectangle.Width * MaskRectangle.Height प्रॉपर्टीज़ के बराबर होनी चाहिए। |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | PSD फ़ाइल लेयर में मास्क डेटा के बारे में जानकारी रखने वाली LayerMaskDataShort क्लास को परिभाषित करता है<br/>            जब लेयर में केवल रास्टर या वेक्टर मास्क हो लेकिन दोनों नहीं। अन्यथा, एक [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) उपयोग किया जाता है।<br/>            यदि लेयर में केवल रास्टर मास्क है तो ImageData रास्टर मास्क डेटा बाइट्स रखती है।<br/>            यदि लेयर में केवल वेक्टर मास्क है तो ImageData वेक्टर मास्क को रास्टराइज़्ड (कैश्ड) डेटा बाइट्स रखती है।<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) बाइट्स की लंबाई [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) प्रॉपर्टीज़ के Width * Height के बराबर होनी चाहिए। |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | लेयर जानकारी का प्रतिनिधित्व करता है। |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | PSD फ़ाइलों के लोडिंग के लिए लेयर रिसोर्सेज़ रेजिस्ट्री को परिभाषित करें। |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | लिंक्ड लेयर्स मैनेजर क्लास। |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | फ़ोल्डर (लेयर ग्रुप) की सीमाओं को चिह्नित करने के लिए सेक्शन डिवाइडर लेयर। |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Shape लेयर। Shape लेयर और संबंधित रिसोर्सेज़ के साथ कार्य की लॉजिक को संलग्न करता है। |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | टेक्स्ट लेयर क्लास |
## **Enumerations**
| **Enumeration** | **विवरण** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | लेयर फ़्लैग्स |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | लेयर मास्क फ़्लैग्स |
