---
title: "क्लास TiffDataType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Tiff.TiffDataType क्लास। tiff डेटा प्रकार"
type: docs
weight: 4680
url: /hi/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

tiff डेटा टाइप।

```csharp
public abstract class TiffDataType : IComparable
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | टैग डेटा को फिट करने के लिए 12 बाइट्स पर्याप्त न हों, ऐसी स्थिति में अतिरिक्त डेटा आकार बाइट्स में प्राप्त करता है। |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | तत्वों की गिनती प्राप्त करता है। |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | टैग डेटा को फिट करने के लिए 12 बाइट्स पर्याप्त न हों, ऐसी स्थिति में अतिरिक्त डेटा आकार बाइट्स में प्राप्त करता है। |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | टैग आईडी का पूर्णांक प्रतिनिधित्व प्राप्त करता है। |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | टैग डेटा वैध है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। वैध टैग में वह डेटा होता है जिसे संरक्षित किया जा सकता है। अमान्य टैग को संग्रहीत नहीं किया जा सकता। |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | टैग आईडी प्राप्त करता है। |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | टैग प्रकार प्राप्त करता है। |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | इस डेटा प्रकार में मौजूद मान को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | टैग डेटा को पढ़ता है। |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | वर्तमान उदाहरण की उसी प्रकार के दूसरे ऑब्जेक्ट के साथ तुलना करता है और एक पूर्णांक लौटाता है जो दर्शाता है कि वर्तमान उदाहरण क्रम में पहले आता है, बाद में, या दूसरे ऑब्जेक्ट के समान स्थिति में है। |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | इस उदाहरण की गहरी क्लोन बनाता है। |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | अतिरिक्त टैग डेटा लिखता है। |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | टैग डेटा लिखता है। |

### देखें भी

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


