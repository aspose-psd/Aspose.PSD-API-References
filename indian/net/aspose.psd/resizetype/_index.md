---
title: Enum ResizeType
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.ResizeType एनुम. आकर बदलने के प्रकर क नर्दष्ट करत है
type: docs
weight: 5370
url: /hi/net/aspose.psd/resizetype/
---
## ResizeType enumeration

आकार बदलने के प्रकार को निर्दिष्ट करता है।

```csharp
public enum ResizeType
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| None | `0` | आकार बदलने की प्रक्रिया के दौरान पिक्सेल संरक्षित नहीं होते हैं। |
| LeftTopToLeftTop | `1` | नई छवि का बायां शीर्ष बिंदु मूल छवि के बाएं शीर्ष बिंदु से मिल जाएगा। आवश्यकता पड़ने पर फसल होगी। |
| RightTopToRightTop | `2` | नई छवि का दायां शीर्ष बिंदु मूल छवि के दाएं शीर्ष बिंदु से मिल जाएगा। आवश्यकता पड़ने पर फसल होगी। |
| RightBottomToRightBottom | `3` | नई छवि का दायां निचला बिंदु मूल छवि के दाएं निचले बिंदु से मिल जाएगा। आवश्यकता पड़ने पर फसल होगी। |
| LeftBottomToLeftBottom | `4` | नई छवि का बायां निचला बिंदु मूल छवि के बाएं निचले बिंदु के साथ मिल जाएगा। आवश्यकता पड़ने पर फसल होगी। |
| CenterToCenter | `5` | नई छवि का केंद्र मूल छवि के केंद्र के साथ मिल जाएगा। आवश्यकता पड़ने पर फसल होगी। |
| LanczosResample | `6` | एक = 3. के साथ लैंक्ज़ोस एल्गोरिथम का उपयोग करके पुन: नमूना |
| NearestNeighbourResample | `7` | निकटतम पड़ोसी एल्गोरिथम का उपयोग करके पुन: नमूना करें। |
| AdaptiveResample | `8` | भारित और मिश्रित तर्कसंगत फ़ंक्शन और lanczos3 इंटरपोलेशन एल्गोरिदम के आधार पर अनुकूली एल्गोरिदम का उपयोग करके पुन: नमूना। |
| BilinearResample | `9` | बिलिनियर इंटरपोलेशन का उपयोग करके पुनः नमूना लें। छवि पूर्व-फ़िल्टरिंग को आवश्यकता होने पर पुनः नमूना लेने से पहले शोर को हटाने की अनुमति है |
| HighQualityResample | `10` | उच्च गुणवत्ता वाला नमूना |
| CatmullRom | `11` | कैटमुल-रोम क्यूबिक इंटरपोलेशन विधि। |
| CubicConvolution | `12` | क्यूबिक कनवल्शन इंटरपोलेशन विधि |
| CubicBSpline | `13` | क्यूबिकबीस्पलाइन क्यूबिक इंटरपोलेशन विधि |
| Mitchell | `14` | मिचेल क्यूबिक इंटरपोलेशन विधि |
| SinC | `15` | सिनक (लैंक्ज़ोस3) क्यूबिक इंटरपोलेशन विधि |
| Bell | `16` | बेल प्रक्षेप विधि |

### उदाहरण

निम्न कोड दर्शाता है कि एक नए SinC आकार प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड दर्शाता है कि एक नए बेल आकार प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड दर्शाता है कि एक नए मिशेल आकार प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड प्रदर्शित करता है कि एक नए CatmullRom आकार प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड प्रदर्शित करता है कि एक नए क्यूबिकबीस्पलाइन आकार बदलने के प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड प्रदर्शित करता है कि एक नए क्यूबिक कनवॉल्यूशन आकार बदलने के प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


