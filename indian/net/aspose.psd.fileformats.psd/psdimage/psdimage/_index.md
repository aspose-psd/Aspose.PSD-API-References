---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdImage कंस्ट्रक्टर। निर्दिष्ट पाथ से रास्टर इमेज (psd इमेज नहीं) के आधार पर PsdImage क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। डिफ़ॉल्ट पैरामीटर्स के साथ psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है: कलर मोड rgb, 4 चैनल, प्रति चैनल 8 बिट, कंप्रेशन Raw"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

निर्दिष्ट पाथ से रास्टर इमेज (psd इमेज नहीं) के आधार पर [`PsdImage`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। डिफ़ॉल्ट पैरामीटर्स के साथ psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, प्रति चैनल 8 बिट, कंप्रेशन - Raw।

```csharp
public PsdImage(string path)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| पाथ | String | पिक्सेल और पैलेट डेटा लोड करने और इनिशियलाइज़ करने के लिए पाथ। |

### देखें भी

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

निर्दिष्ट पाथ से रास्टर इमेज (psd इमेज नहीं) के साथ कंस्ट्रक्टर पैरामीटर्स का उपयोग करके [`PsdImage`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| पाथ | String | पिक्सेल और पैलेट डेटा लोड करने और इनिशियलाइज़ करने के लिए पाथ। |
| colorMode | ColorModes | रंग मोड। |
| channelBitDepth | Int16 | PSD की प्रति चैनल बिट गहराई। |
| channels | Int16 | PSD चैनल्स की गिनती। |
| psdVersion | Int32 | PSD संस्करण। |
| compression | CompressionMethod | उपयोग करने के लिए संपीड़न। |

### देखें भी

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

निर्दिष्ट पथ से रास्टर इमेज (स्ट्रीम में PSD इमेज नहीं) के आधार पर [`PsdImage`](../) क्लास की नई इंस्टेंस को प्रारंभ करता है। डिफ़ॉल्ट पैरामीटरों के साथ PSD इमेज को प्रारंभ करने के लिए उपयोग किया जाता है - रंग मोड - rgb, 4 चैनल, प्रति चैनल 8 बिट, संपीड़न - Raw।

```csharp
public PsdImage(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | पिक्सेल और पैलेट डेटा लोड करने और प्रारंभ करने के लिए स्ट्रीम। |

### देखें भी

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

निर्दिष्ट पथ से रास्टर इमेज (स्ट्रीम में PSD इमेज नहीं) के आधार पर, कंस्ट्रक्टर पैरामीटरों के साथ, [`PsdImage`](../) क्लास की नई इंस्टेंस को प्रारंभ करता है।

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | पिक्सेल और पैलेट डेटा लोड करने और प्रारंभ करने के लिए स्ट्रीम। |
| colorMode | ColorModes | रंग मोड। |
| channelBitDepth | Int16 | PSD की प्रति चैनल बिट गहराई। |
| channels | Int16 | PSD चैनल्स की गिनती। |
| psdVersion | Int32 | PSD संस्करण। |
| compression | CompressionMethod | उपयोग करने के लिए संपीड़न। |

### देखें भी

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

मौजूदा रास्टर इमेज (PSD इमेज नहीं) से, RGB रंग मोड, 4 चैनल, प्रति चैनल 8 बिट, और बिना संपीड़न के, [`PsdImage`](../) क्लास की नई इंस्टेंस को प्रारंभ करता है।

```csharp
public PsdImage(RasterImage rasterImage)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rasterImage | RasterImage | पिक्सेल और पैलेट डेटा लोड करने और प्रारंभ करने के लिए इमेज। |

### देखें भी

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

मौजूदा रास्टर इमेज (PSD इमेज नहीं) से, कंस्ट्रक्टर पैरामीटरों के साथ, [`PsdImage`](../) क्लास की नई इंस्टेंस को प्रारंभ करता है।

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rasterImage | RasterImage | पिक्सेल और पैलेट डेटा लोड करने और प्रारंभ करने के लिए इमेज। |
| colorMode | ColorModes | रंग मोड। |
| channelBitDepth | Int16 | PSD की प्रति चैनल बिट गहराई। |
| channels | Int16 | PSD चैनल्स की गिनती। |
| psdVersion | Int32 | PSD संस्करण। |
| compression | CompressionMethod | उपयोग करने के लिए संपीड़न। |

### देखें भी

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

निर्दिष्ट चौड़ाई और ऊँचाई के साथ [`PsdImage`](../) क्लास की नई इंस्टेंस को प्रारंभ करता है। खाली PSD इमेज को प्रारंभ करने के लिए उपयोग किया जाता है।

```csharp
public PsdImage(int width, int height)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| चौड़ाई | Int32 | इमेज की चौड़ाई। |
| ऊँचाई | Int32 | चित्र की ऊँचाई। |

### देखें भी

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

निर्दिष्ट चौड़ाई, ऊँचाई, पैलेट, रंग मोड, चैनल संख्या और चैनल बिट-लंबाई, तथा निर्दिष्ट संपीड़न मोड पैरामीटरों के साथ [`PsdImage`](../) क्लास की नई इंस्टेंस को प्रारंभ करता है। खाली PSD इमेज को प्रारंभ करने के लिए उपयोग किया जाता है।

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| चौड़ाई | Int32 | इमेज की चौड़ाई। |
| ऊँचाई | Int32 | चित्र की ऊँचाई। |
| colorPalette | IColorPalette | रंग पैलेट। |
| colorMode | ColorModes | रंग मोड। |
| channelBitDepth | Int16 | PSD की प्रति चैनल बिट गहराई। |
| channels | Int16 | PSD चैनल्स की गिनती। |
| psdVersion | Int32 | PSD संस्करण। |
| compression | CompressionMethod | उपयोग करने के लिए संपीड़न। |

### देखें भी

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


