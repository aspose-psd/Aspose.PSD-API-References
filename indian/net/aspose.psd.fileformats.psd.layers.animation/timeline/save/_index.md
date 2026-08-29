---
title: "Timeline.Save"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Timeline मेथड। निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ॉर्मेट में, सेव विकल्पों के अनुसार, PsdImages और Timeline डेटा को सहेजता है।"
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

सेव विकल्पों के अनुसार निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान में PsdImage और Timeline डेटा को सहेजता है।

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ। |
| विकल्प | ImageOptionsBase | विकल्प। |

## उदाहरण

निम्नलिखित कोड टाइमलाइन को GIF इमेज में एक्सपोर्ट करने के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### देखें भी

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

सेव विकल्पों के अनुसार निर्दिष्ट फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में PsdImage और Timeline डेटा को सहेजता है।

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| outputStream | Stream | आउटपुट स्ट्रीम। |
| विकल्प | ImageOptionsBase | विकल्प। |

## उदाहरण

निम्नलिखित कोड टाइमलाइन को GIF इमेज में एक्सपोर्ट करने के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### देखें भी

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


