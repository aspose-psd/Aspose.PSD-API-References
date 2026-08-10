---
title: "क्लास FileStreamContainer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileStreamContainer क्लास। फ़ाइल स्ट्रीम प्रोसेसिंग के लिए सहायक"
type: docs
weight: 4720
url: /hi/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

फ़ाइल स्ट्रीम प्रोसेसिंग के लिए सहायक।

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम पढ़ने का समर्थन करता है या नहीं। |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम सीकिंग का समर्थन करता है या नहीं। |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम लिखने का समर्थन करता है या नहीं। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | फ़ाइल पथ प्राप्त करता है। |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम स्पष्ट रूप से बनाई गई थी या नहीं। |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह स्ट्रीम बंद होने पर डिस्पोज़ हो जाता है या नहीं। |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि स्ट्रीम अस्थायी है या नहीं। |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | बाइट्स में स्ट्रीम की लंबाई प्राप्त करता है या सेट करता है। यह मान स्ट्रीम कंटेनर कंस्ट्रक्टर में पास की गई प्रारंभिक स्ट्रीम स्थिति द्वारा लंबाई से कम होता है। |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त करता है या सेट करता है। यह मान स्ट्रीम कंटेनर कंस्ट्रक्टर में पास की गई प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट दर्शाता है। |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | डेटा स्ट्रीम प्राप्त करता है। |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | सिंक्रनाइज़्ड संसाधन तक पहुँच को समन्वयित करने के लिए उपयोग किया जा सकने वाला ऑब्जेक्ट प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | एक नई फ़ाइल स्ट्रीम बनाता है। |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | मौजूदा फ़ाइल स्ट्रीम को खोलता है। यदि फ़ाइल स्ट्रीम मौजूद नहीं है तो उपयुक्त अपवाद फेंका जाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | इस स्ट्रीम के सभी बफ़र साफ़ करता है और किसी भी बफ़र किए गए डेटा को आधारभूत डिवाइस पर लिखवाता है। |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | निर्दिष्ट बाइट बफ़र को भरने के लिए बाइट्स पढ़ता है। |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला पढ़ता है और पढ़े गए बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है। |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम में स्थिति को एक बाइट से आगे बढ़ाता है, या यदि स्ट्रीम के अंत में हो तो -1 लौटाता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) और स्ट्रीम [`Length`](../streamcontainer/length/) मान का उपयोग करता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) और स्ट्रीम [`Length`](../streamcontainer/length/) मान का उपयोग करता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | स्ट्रीम के सभी डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। स्ट्रीम [`Length`](../streamcontainer/length/) मान का उपयोग करता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। स्ट्रीम [`Length`](../streamcontainer/length/) मान का उपयोग करता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है। |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | स्ट्रीम की स्थिति को स्ट्रीम की शुरुआत में सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पास की गई प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट को दर्शाता है। |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | स्ट्रीम डेटा को बाइट एरे में परिवर्तित करता है। |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | स्ट्रीम डेटा को बाइट एरे में परिवर्तित करता है। |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | निर्दिष्ट सभी बाइट्स को स्ट्रीम में लिखता है। |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला लिखता है और लिखे गए बाइट्स की संख्या के अनुसार इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है। |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | स्ट्रीम में वर्तमान स्थिति पर एक बाइट लिखता है और स्ट्रीम में स्थिति को एक बाइट से आगे बढ़ाता है। |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | समाहित डेटा को दूसरे [`StreamContainer`](../streamcontainer/) में कॉपी करता है। |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | समाहित डेटा को दूसरे [`StreamContainer`](../streamcontainer/) में कॉपी करता है। |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | `FileStreamContainer` से Stream में स्पष्ट रूपांतरण करता है। (2 ऑपरेटर) |

### देखें भी

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


