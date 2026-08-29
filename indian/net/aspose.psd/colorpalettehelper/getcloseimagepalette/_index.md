---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ColorPaletteHelper मेथड। रास्टर इमेज से रंग पैलेट प्राप्त करता है; यदि इमेज के पास पैलेट नहीं है तो इमेज को पैलेटाइज़ करता है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय उसका उपयोग किया जाएगा।"
type: docs
weight: 60
url: /hi/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | RasterImage | रास्टर इमेज। |
| entriesCount | Int32 | वांछित एंट्रीज़ की संख्या। |

### रिटर्न वैल्यू

रंग पैलेट जो *image* से सबसे अधिक बार आने वाले रंगों से शुरू होता है और *entriesCount* एंट्रीज़ रखता है।

### देखें भी

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | RasterImage | रास्टर इमेज। |
| destBounds | Rectangle | गंतव्य इमेज की सीमाएँ। |
| entriesCount | Int32 | वांछित एंट्रीज़ की संख्या। |

### रिटर्न वैल्यू

रंग पैलेट जो *image* से सबसे अधिक बार आने वाले रंगों से शुरू होता है और *entriesCount* एंट्रीज़ रखता है।

### देखें भी

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | RasterImage | रास्टर इमेज। |
| destBounds | Rectangle | गंतव्य इमेज की सीमाएँ। |
| entriesCount | Int32 | वांछित एंट्रीज़ की संख्या। |
| useImagePalette | बूलियन | यदि सेट किया गया है, तो यह उपलब्ध होने पर अपना स्वयं का इमेज पैलेट उपयोग करेगा। |

### रिटर्न वैल्यू

रंग पैलेट जो *image* से सबसे अधिक बार आने वाले रंगों से शुरू होता है और *entriesCount* एंट्रीज़ रखता है।

### देखें भी

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


