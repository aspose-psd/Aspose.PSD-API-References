---
title: Class SplitStreamContainer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.SplitStreamContainer कक्ष. स्प्लट स्ट्रम कंटेनर क प्रतनधत्व करत है जसमें स्ट्रम हत है और स्ट्रम प्रसेसंग रूटन प्रदन करत है
type: docs
weight: 5630
url: /hi/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

स्प्लिट स्ट्रीम कंटेनर का प्रतिनिधित्व करता है जिसमें स्ट्रीम होता है और स्ट्रीम प्रोसेसिंग रूटीन प्रदान करता है।

```csharp
public class SplitStreamContainer : StreamContainer
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | का एक नया उदाहरण प्रारंभ करता है`SplitStreamContainer` वर्ग. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | का एक नया उदाहरण प्रारंभ करता है`SplitStreamContainer` वर्ग. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | का एक नया उदाहरण प्रारंभ करता है`SplitStreamContainer` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि स्ट्रीम पढ़ने का समर्थन करती है या नहीं। |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि स्ट्रीम खोज का समर्थन करती है या नहीं। |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि धारा लेखन का समर्थन करती है या नहीं। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि यह स्ट्रीम बंद होने पर निपटाया गया है या नहीं। |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | बाइट्स में स्ट्रीम की लंबाई प्राप्त या सेट करता है। यह मान से कम हैLengthStreamContainer कंस्ट्रक्टर में पारित प्रारंभिक स्ट्रीम स्थिति द्वारा। |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त या सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पारित प्रारंभिक स्ट्रीम स्थिति से ऑफसेट का प्रतिनिधित्व करता है। |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | डेटा स्ट्रीम प्राप्त करता है। |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | एक ऑब्जेक्ट प्राप्त करता है जिसका उपयोग सिंक्रनाइज़ संसाधन तक पहुंच को सिंक्रनाइज़ करने के लिए किया जा सकता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है और किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखा जाता है। |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | स्ट्रीम कंटेनर को निर्दिष्ट स्थिति में सम्मिलित करता है। |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | निर्दिष्ट बाइट बफर भरने के लिए बाइट पढ़ता है। |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | वर्तमान स्ट्रीम से बाइट्स के अनुक्रम को पढ़ता है और बाइट्स की संख्या से स्ट्रीम के भीतर स्थिति को आगे बढ़ाता है। |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम के भीतर स्थिति को एक बाइट से आगे बढ़ाता है, या स्ट्रीम के अंत में -1 लौटाता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। डिफ़ॉल्ट बफ़र आकार का उपयोग करता है[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) और धारा[`Length`](../streamcontainer/length/) मान. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। डिफ़ॉल्ट बफ़र आकार का उपयोग करता है[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) और धारा[`Length`](../streamcontainer/length/) मान. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | सभी स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। स्ट्रीम का उपयोग करता है[`Length`](../streamcontainer/length/) मान. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। स्ट्रीम का उपयोग करता है[`Length`](../streamcontainer/length/) मान. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है। |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | स्ट्रीम की स्थिति को स्ट्रीम की शुरुआत में सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पारित प्रारंभिक स्ट्रीम स्थिति से ऑफसेट का प्रतिनिधित्व करता है। |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | स्ट्रीम डेटा को इसमें कनवर्ट करता हैByte सरणी. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | स्ट्रीम डेटा को इसमें कनवर्ट करता हैByte सरणी. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | सभी निर्दिष्ट बाइट्स को स्ट्रीम में लिखता है। |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | बाइट्स के अनुक्रम को वर्तमान स्ट्रीम में लिखता है और इस स्ट्रीम के भीतर वर्तमान स्थिति को लिखे गए बाइट्स की संख्या से आगे बढ़ाता है। |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | स्ट्रीम में वर्तमान स्थिति के लिए एक बाइट लिखता है और स्ट्रीम के भीतर स्थिति को एक बाइट आगे बढ़ाता है। |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | निहित डेटा को दूसरे में कॉपी करता है[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | निहित डेटा को दूसरे में कॉपी करता है[`StreamContainer`](../streamcontainer/) . |

### यह सभी देखें

* class [StreamContainer](../streamcontainer/)
* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


