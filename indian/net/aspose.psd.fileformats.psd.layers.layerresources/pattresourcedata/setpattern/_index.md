---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PattResourceData मेथड। पैटर्न पिक्सेल बफ़र और लक्ष्य आकार सेट करती है, Width / Height को अपडेट करती है और डिफ़ॉल्ट संपीड़न मोड 0 का उपयोग करके सहेजने के लिए डेटा संग्रहीत करती है।"
type: docs
weight: 110
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

पैटर्न पिक्सेल बफ़र और लक्ष्य आकार सेट करता है, [`Width`](../width/) / [`Height`](../height/) को अपडेट करता है, और डिफ़ॉल्ट संपीड़न मोड (0) का उपयोग करके सहेजने के लिए डेटा संग्रहीत करता है।

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| पिक्सेल | Int32[] | `0xAARRGGBB` फ़ॉर्मेट में 32-बिट पिक्सेल। |
| सीमाएँ | Rectangle | पैटर्न के पिक्सेल बाउंड्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | पिक्सेल एरे की लंबाई बाउंड्स क्षेत्र के बराबर होनी चाहिए। |

### देखें भी

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


