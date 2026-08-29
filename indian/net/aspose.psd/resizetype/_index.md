---
title: "एनम ResizeType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ResizeType एनम। री-साइज़ प्रकार निर्दिष्ट करता है।"
type: docs
weight: 5870
url: /hi/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

रिसाइज़ प्रकार को निर्दिष्ट करता है।

```csharp
public enum ResizeType
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | `0` | री-साइज़ ऑपरेशन के दौरान पिक्सेल संरक्षित नहीं होते हैं। |
| LeftTopToLeftTop | `1` | नई इमेज का बायाँ ऊपर बिंदु मूल इमेज के बाएँ ऊपर बिंदु के साथ मेल खाएगा। आवश्यकता होने पर क्रॉप किया जाएगा। |
| RightTopToRightTop | `2` | नई इमेज का दायाँ ऊपर बिंदु मूल इमेज के दाएँ ऊपर बिंदु के साथ मेल खाएगा। आवश्यकता होने पर क्रॉप किया जाएगा। |
| RightBottomToRightBottom | `3` | नई इमेज का दायाँ नीचे बिंदु मूल इमेज के दाएँ नीचे बिंदु के साथ मेल खाएगा। आवश्यकता होने पर क्रॉप किया जाएगा। |
| LeftBottomToLeftBottom | `4` | नई छवि का बायाँ निचला बिंदु मूल छवि के बाएँ निचले बिंदु के साथ मेल खाएगा। आवश्यकता होने पर क्रॉप किया जाएगा। |
| CenterToCenter | `5` | नई छवि का केंद्र मूल छवि के केंद्र के साथ मेल खाएगा। आवश्यकता होने पर क्रॉप किया जाएगा। |
| LanczosResample | `6` | a=3 के साथ लैंज़ोस एल्गोरिद्म का उपयोग करके पुनः नमूना लें। |
| NearestNeighbourResample | `7` | निकटतम पड़ोसी एल्गोरिद्म का उपयोग करके पुनः नमूना लें। |
| AdaptiveResample | `8` | वज़नित और मिश्रित रैशनल फ़ंक्शन तथा लैंज़ोस3 इंटरपोलेशन एल्गोरिद्म पर आधारित अनुकूलन एल्गोरिद्म का उपयोग करके पुनः नमूना लें। |
| BilinearResample | `9` | बिलीनियर इंटरपोलेशन का उपयोग करके पुनः नमूना लें। आवश्यकता होने पर पुनः नमूना से पहले शोर हटाने के लिए छवि प्री‑फ़िल्टरिंग की अनुमति है। |
| HighQualityResample | `10` | उच्च गुणवत्ता वाला पुनः नमूना |
| CatmullRom | `11` | Catmull‑Rom क्यूबिक इंटरपोलेशन विधि। |
| CubicConvolution | `12` | Cubic Convolution इंटरपोलेशन विधि |
| CubicBSpline | `13` | CubicBSpline क्यूबिक इंटरपोलेशन विधि |
| Mitchell | `14` | Mitchell क्यूबिक इंटरपोलेशन विधि |
| SinC | `15` | Sinc (Lanczos3) क्यूबिक इंटरपोलेशन विधि |
| Bell | `16` | Bell इंटरपोलेशन विधि |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि नई SinC रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई Bell रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई Mitchell रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई CatmullRom रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई CubicBSpline रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई CubicConvolution रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


