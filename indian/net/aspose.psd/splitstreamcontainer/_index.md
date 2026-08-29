---
title: "क्लास SplitStreamContainer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.SplitStreamContainer क्लास। वह स्प्लिट स्ट्रीम कंटेनर दर्शाता है जो स्ट्रीम को रखता है और स्ट्रीम प्रोसेसिंग रूटीन प्रदान करता है।"
type: docs
weight: 6130
url: /hi/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

स्प्लिट स्ट्रीम कंटेनर का प्रतिनिधित्व करता है जो स्ट्रीम को रखता है और स्ट्रीम प्रोसेसिंग रूटीन प्रदान करता है।

```csharp
public class SplitStreamContainer : StreamContainer
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | `SplitStreamContainer` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | `SplitStreamContainer` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | `SplitStreamContainer` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम पढ़ने का समर्थन करता है या नहीं। |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम सीकिंग का समर्थन करता है या नहीं। |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि स्ट्रीम लिखने का समर्थन करता है या नहीं। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह स्ट्रीम बंद होने पर डिस्पोज़ हो जाता है या नहीं। |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | बाइट्स में स्ट्रीम की लंबाई प्राप्त करता है या सेट करता है। यह मान स्ट्रीम कंटेनर कंस्ट्रक्टर में पास की गई प्रारंभिक स्ट्रीम स्थिति द्वारा लंबाई से कम होता है। |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त करता है या सेट करता है। यह मान स्ट्रीम कंटेनर कंस्ट्रक्टर में पास की गई प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट दर्शाता है। |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | डेटा स्ट्रीम प्राप्त करता है। |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | सिंक्रनाइज़्ड संसाधन तक पहुँच को समन्वयित करने के लिए उपयोग किया जा सकने वाला ऑब्जेक्ट प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | इस स्ट्रीम के सभी बफ़र साफ़ करता है और किसी भी बफ़र किए गए डेटा को आधारभूत डिवाइस पर लिखवाता है। |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | स्ट्रीम कंटेनर को निर्दिष्ट स्थिति में सम्मिलित करता है। |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | निर्दिष्ट बाइट बफ़र को भरने के लिए बाइट्स पढ़ता है। |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला पढ़ता है और पढ़े गए बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है। |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम में स्थिति को एक बाइट से आगे बढ़ाता है, या यदि स्ट्रीम के अंत में हो तो -1 लौटाता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) और स्ट्रीम [`Length`](../streamcontainer/length/) मान का उपयोग करता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। डिफ़ॉल्ट बफ़र आकार [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) और स्ट्रीम [`Length`](../streamcontainer/length/) मान का उपयोग करता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | स्ट्रीम के सभी डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। स्ट्रीम [`Length`](../streamcontainer/length/) मान का उपयोग करता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। स्ट्रीम [`Length`](../streamcontainer/length/) मान का उपयोग करता है। |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता (कॉपी करता) है। |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है। |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | स्ट्रीम की स्थिति को स्ट्रीम की शुरुआत में सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पास की गई प्रारंभिक स्ट्रीम स्थिति से ऑफ़सेट को दर्शाता है। |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | स्ट्रीम डेटा को बाइट एरे में परिवर्तित करता है। |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | स्ट्रीम डेटा को बाइट एरे में परिवर्तित करता है। |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | निर्दिष्ट सभी बाइट्स को स्ट्रीम में लिखता है। |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला लिखता है और लिखे गए बाइट्स की संख्या के अनुसार इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है। |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | स्ट्रीम में वर्तमान स्थिति पर एक बाइट लिखता है और स्ट्रीम में स्थिति को एक बाइट से आगे बढ़ाता है। |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | समाहित डेटा को दूसरे [`StreamContainer`](../streamcontainer/) में कॉपी करता है। |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | समाहित डेटा को दूसरे [`StreamContainer`](../streamcontainer/) में कॉपी करता है। |

### देखें भी

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


