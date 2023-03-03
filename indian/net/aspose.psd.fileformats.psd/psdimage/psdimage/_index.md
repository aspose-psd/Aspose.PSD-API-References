---
title: PsdImage.PsdImage
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdImage नर्मत. क एक नय उदहरण प्ररंभ करत हैPsdImage रेखपुंज छव से नर्दष्ट पथ से वर्ग पथ में पएसड छव नहं डफ़ल्ट मपदंडं के सथ psd छव क इनशयलइज़ करने के लए उपयग कय जत है  कलर मड  rgb 4 चैनल 8 बट प्रत चैनल कम्प्रेशन  र.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

का एक नया उदाहरण प्रारंभ करता है[`PsdImage`](../) रेखापुंज छवि से निर्दिष्ट पथ से वर्ग (पथ में पीएसडी छवि नहीं)। डिफ़ॉल्ट मापदंडों के साथ psd छवि को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, 8 बिट प्रति चैनल, कम्प्रेशन - रॉ.

```csharp
public PsdImage(string path)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | String | पिक्सेल और पैलेट डेटा को लोड करने और आरंभ करने का पथ। |

### यह सभी देखें

* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

का एक नया उदाहरण प्रारंभ करता है[`PsdImage`](../) रास्टर छवि से निर्दिष्ट पथ से कक्षा (पथ में पीएसडी छवि नहीं) कन्स्ट्रक्टर पैरामीटर के साथ।

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | String | पिक्सेल और पैलेट डेटा को लोड करने और आरंभ करने का पथ। |
| colorMode | ColorModes | रंग मोड। |
| channelBitDepth | Int16 | प्रति चैनल PSD बिट गहराई। |
| channels | Int16 | PSD चैनल गिने जाते हैं। |
| psdVersion | Int32 | पीएसडी संस्करण। |
| compression | CompressionMethod | उपयोग करने के लिए संपीड़न। |

### यह सभी देखें

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

का एक नया उदाहरण प्रारंभ करता है[`PsdImage`](../) रेखापुंज छवि से निर्दिष्ट पथ से वर्ग (धारा में psd छवि नहीं)। डिफ़ॉल्ट मापदंडों के साथ psd छवि को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, 8 बिट प्रति चैनल, कम्प्रेशन - रॉ.

```csharp
public PsdImage(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | पिक्सेल और पैलेट डेटा को लोड करने और आरंभ करने के लिए स्ट्रीम। |

### यह सभी देखें

* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

का एक नया उदाहरण प्रारंभ करता है[`PsdImage`](../) रास्टर छवि से निर्दिष्ट पथ से कक्षा (स्ट्रीम में पीएसडी छवि नहीं) कन्स्ट्रक्टर पैरामीटर के साथ।

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | पिक्सेल और पैलेट डेटा को लोड करने और आरंभ करने के लिए स्ट्रीम। |
| colorMode | ColorModes | रंग मोड। |
| channelBitDepth | Int16 | प्रति चैनल PSD बिट गहराई। |
| channels | Int16 | PSD चैनल गिने जाते हैं। |
| psdVersion | Int32 | पीएसडी संस्करण। |
| compression | CompressionMethod | उपयोग करने के लिए संपीड़न। |

### यह सभी देखें

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`PsdImage`](../) चैनल 8 बिट/चैनल और कोई संपीड़न के साथ आरजीबी रंग मोड के साथ मौजूदा रेखापुंज छवि (पीएसडी छवि नहीं) से वर्ग।

```csharp
public PsdImage(RasterImage rasterImage)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rasterImage | RasterImage | पिक्सेल और पैलेट डेटा को लोड करने और आरंभ करने के लिए छवि। |

### यह सभी देखें

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`PsdImage`](../) कंस्ट्रक्टर मापदंडों के साथ मौजूदा रेखापुंज छवि (psd छवि नहीं) से वर्ग।

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rasterImage | RasterImage | पिक्सेल और पैलेट डेटा को लोड करने और आरंभ करने के लिए छवि। |
| colorMode | ColorModes | रंग मोड। |
| channelBitDepth | Int16 | प्रति चैनल PSD बिट गहराई। |
| channels | Int16 | PSD चैनल गिने जाते हैं। |
| psdVersion | Int32 | पीएसडी संस्करण। |
| compression | CompressionMethod | उपयोग करने के लिए संपीड़न। |

### यह सभी देखें

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`PsdImage`](../) वर्ग निर्दिष्ट चौड़ाई और ऊंचाई के साथ। खाली पीएसडी इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है।

```csharp
public PsdImage(int width, int height)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | Int32 | छवि की चौड़ाई। |
| height | Int32 | छवि ऊंचाई। |

### यह सभी देखें

* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`PsdImage`](../) वर्ग निर्दिष्ट चौड़ाई, ऊंचाई, पैलेट, रंग मोड, चैनलों की संख्या और चैनल बिट-लंबाई और निर्दिष्ट संपीड़न मोड पैरामीटर के साथ। खाली पीएसडी इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है।

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | Int32 | छवि की चौड़ाई। |
| height | Int32 | छवि ऊंचाई। |
| colorPalette | IColorPalette | रंग पैलेट। |
| colorMode | ColorModes | रंग मोड। |
| channelBitDepth | Int16 | प्रति चैनल PSD बिट गहराई। |
| channels | Int16 | PSD चैनल गिने जाते हैं। |
| psdVersion | Int32 | पीएसडी संस्करण। |
| compression | CompressionMethod | उपयोग करने के लिए संपीड़न। |

### यह सभी देखें

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)


