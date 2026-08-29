---
title: "क्लास PsdColorPalette"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.PsdColorPalette क्लास. PSD कलर पैलेट"
type: docs
weight: 4040
url: /hi/net/aspose.psd.fileformats.psd/psdcolorpalette/
---
{{< psd/tize >}}
## PsdColorPalette class

PSD रंग पैलेट।

```csharp
public class PsdColorPalette : IPsdColorPalette
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PsdColorPalette](psdcolorpalette/#constructor_6)(byte[]) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है और IsCompactPalette false है। |
| [PsdColorPalette](psdcolorpalette/#constructor)(Color[]) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है और IsCompactPalette false है। |
| [PsdColorPalette](psdcolorpalette/#constructor_4)(IColorPalette) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PsdColorPalette](psdcolorpalette/#constructor_7)(byte[], bool) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PsdColorPalette](psdcolorpalette/#constructor_8)(byte[], short) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है और IsCompactPalette false है। |
| [PsdColorPalette](psdcolorpalette/#constructor_1)(Color[], bool) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PsdColorPalette](psdcolorpalette/#constructor_2)(Color[], short) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है और IsCompactPalette false है। |
| [PsdColorPalette](psdcolorpalette/#constructor_5)(IColorPalette, short) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PsdColorPalette](psdcolorpalette/#constructor_10)(int[], bool) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PsdColorPalette](psdcolorpalette/#constructor_9)(byte[], short, bool) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PsdColorPalette](psdcolorpalette/#constructor_3)(Color[], short, bool) | `PsdColorPalette` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Argb32Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/argb32entries/) { get; } | 32-बिट ARGB रंगों की एक एरे प्राप्त करता है। |
| [Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/entries/) { get; } | [`Color`](../../aspose.psd/color/) संरचनाओं की एक एरे प्राप्त करता है। |
| [EntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/entriescount/) { get; } | एंट्री की गिनती प्राप्त करता है। |
| [HasTransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/hastransparentcolor/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि पारदर्शी रंग मौजूद है या नहीं। |
| [IsCompactPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/) { get; } | पैलेट को कॉम्पैक्ट है या नहीं दर्शाने वाला मान प्राप्त करता है। |
| [RawEntries](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentries/) { get; } | रॉ रंग पैलेट प्रविष्टियों का डेटा प्राप्त करता है। |
| [RawEntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentriescount/) { get; } | रॉ रंग पैलेट प्रविष्टियों की गिनती प्राप्त करता है। |
| [TransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentcolor/) { get; } | पारदर्शी रंग प्राप्त करता है। |
| [TransparentIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentindex/) { get; } | पारदर्शी रंग का सूचकांक प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette)(IColorPalette) | पैलेट की कॉपी बनाता है। |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | पैलेट की कॉपी बनाता है। |
| [GetArgb32Color](../../aspose.psd.fileformats.psd/psdcolorpalette/getargb32color/)(int) | इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है। |
| [GetColor](../../aspose.psd.fileformats.psd/psdcolorpalette/getcolor/)(int) | इंडेक्स द्वारा पैलेट रंग प्राप्त करता है। |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | निकटतम रंग का इंडेक्स प्राप्त करता है। |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | निकटतम रंग का इंडेक्स प्राप्त करता है। |

### देखें भी

* interface [IPsdColorPalette](../../aspose.psd/ipsdcolorpalette/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


