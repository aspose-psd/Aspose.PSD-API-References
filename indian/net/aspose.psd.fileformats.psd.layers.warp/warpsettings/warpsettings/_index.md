---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "WarpSettings कन्स्ट्रक्टर। WarpSettings क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

नया इंस्टेंस इनिशियलाइज़ करता है [`WarpSettings`](../) क्लास का।

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| meshPoints | PointF[] | वॉर्प के मेष बिंदु |
| सीमाएँ | Rectangle | वॉर्प इमेज की सीमाएँ |

## उदाहरण

निम्नलिखित कोड WarpSettings.GridSize प्रॉपर्टी के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // वॉर्प सेटिंग्स प्राप्त करें
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // नया आकार सेट करें
    // फ़ोटोशॉप के लिए मान 1 से 50 के बीच हो सकता है और आप PSD फ़ाइल को सही ढंग से सहेज नहीं सकते।
    warpSettings.GridSize = new Size(100, 100);

    // वैध मान सेट करें
    warpSettings.GridSize = new Size(3, 3);

    // x3 ग्रिड के साथ उदाहरण फ़ाइल रेंडर करें
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### देखें भी

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

नया इंस्टेंस इनिशियलाइज़ करता है [`WarpSettings`](../) क्लास का।

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| meshPoints | PointF[] | वॉर्प के मेष बिंदु |
| सीमाएँ | Rectangle | वॉर्प इमेज की सीमाएँ |
| style | WarpStyles | वॉर्प की शैली |

## उदाहरण

निम्नलिखित कोड WarpSettings.GridSize प्रॉपर्टी के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // वॉर्प सेटिंग्स प्राप्त करें
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // नया आकार सेट करें
    // फ़ोटोशॉप के लिए मान 1 से 50 के बीच हो सकता है और आप PSD फ़ाइल को सही ढंग से सहेज नहीं सकते।
    warpSettings.GridSize = new Size(100, 100);

    // वैध मान सेट करें
    warpSettings.GridSize = new Size(3, 3);

    // x3 ग्रिड के साथ उदाहरण फ़ाइल रेंडर करें
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### देखें भी

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

नया इंस्टेंस इनिशियलाइज़ करता है [`WarpSettings`](../) क्लास का।

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | वॉर्प सेटिंग्स वाले PS आइटम्स |
| सीमाएँ | Rectangle | वॉर्प इमेज की सीमाएँ |

### देखें भी

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

नया इंस्टेंस इनिशियलाइज़ करता है [`WarpSettings`](../) क्लास का।

```csharp
public WarpSettings(PlacedResource placedResource)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| placedResource | PlacedResource | वॉर्प सेटिंग्स वाला रिसोर्स |

### देखें भी

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


