---
title: Class TiffDataType
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Tiff.TiffDataType कक्ष. झगड़ डेट प्रकर
type: docs
weight: 4210
url: /hi/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

झगड़ा डेटा प्रकार।

```csharp
public abstract class TiffDataType : IComparable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | बाइट्स में अतिरिक्त डेटा आकार प्राप्त करता है (यदि 12 बाइट्स टैग डेटा को फिट करने के लिए पर्याप्त नहीं हैं)। |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | तत्वों की गिनती प्राप्त करता है। |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | बाइट्स में अतिरिक्त डेटा आकार प्राप्त करता है (यदि 12 बाइट्स टैग डेटा को फिट करने के लिए पर्याप्त नहीं हैं)। |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | टैग आईडी पूर्णांक प्रतिनिधित्व प्राप्त करता है। |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि टैग डेटा मान्य है या नहीं। मान्य टैग में डेटा होता है जिसे संरक्षित किया जा सकता है। अमान्य टैग संग्रहीत नहीं किया जा सकता. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | टैग आईडी प्राप्त करता है। |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | टैग प्रकार प्राप्त करता है। |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | इस डेटा प्रकार में शामिल मान प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | टैग डेटा पढ़ता है। |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | वर्तमान उदाहरण की तुलना उसी प्रकार के किसी अन्य ऑब्जेक्ट से करता है और एक पूर्णांक लौटाता है जो इंगित करता है कि क्या वर्तमान उदाहरण अन्य ऑब्जेक्ट के रूप में क्रमबद्ध क्रम में उसी स्थिति में पूर्ववर्ती, अनुवर्ती, या होता है। |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | इस उदाहरण का गहरा क्लोन करता है। |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | अतिरिक्त टैग डेटा लिखता है। |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | टैग डेटा लिखता है। |

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* सभा [Aspose.PSD](../../)


