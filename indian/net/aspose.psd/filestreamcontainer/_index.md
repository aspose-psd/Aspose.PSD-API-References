---
title: Class FileStreamContainer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileStreamContainer कक्ष. फइल स्ट्रम प्रसेसंग के लए सहयक
type: docs
weight: 4250
url: /hi/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

फाइल स्ट्रीम प्रोसेसिंग के लिए सहायक।

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि स्ट्रीम पढ़ने का समर्थन करती है या नहीं। |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि स्ट्रीम खोज का समर्थन करती है या नहीं। |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि धारा लेखन का समर्थन करती है या नहीं। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | फ़ाइल पथ प्राप्त करता है। |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि स्ट्रीम स्पष्ट रूप से बनाई गई थी या नहीं। |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि यह स्ट्रीम बंद होने पर निपटाया गया है या नहीं। |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि स्ट्रीम अस्थायी है या नहीं। |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | बाइट्स में स्ट्रीम की लंबाई प्राप्त या सेट करता है। यह मान से कम हैLengthStreamContainer कंस्ट्रक्टर में पारित प्रारंभिक स्ट्रीम स्थिति द्वारा। |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | स्ट्रीम के भीतर वर्तमान स्थिति प्राप्त या सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पारित प्रारंभिक स्ट्रीम स्थिति से ऑफसेट का प्रतिनिधित्व करता है। |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | डेटा स्ट्रीम प्राप्त करता है। |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | एक ऑब्जेक्ट प्राप्त करता है जिसका उपयोग सिंक्रनाइज़ संसाधन तक पहुंच को सिंक्रनाइज़ करने के लिए किया जा सकता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | एक नई फ़ाइल स्ट्रीम बनाता है। |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | एक मौजूदा फ़ाइल स्ट्रीम खोलता है। यदि फ़ाइल स्ट्रीम मौजूद नहीं है तो उपयुक्त अपवाद फेंक दिया जाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है और किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस पर लिखा जाता है। |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | निर्दिष्ट बाइट बफर भरने के लिए बाइट पढ़ता है। |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | वर्तमान स्ट्रीम से बाइट्स के अनुक्रम को पढ़ता है और बाइट्स की संख्या से स्ट्रीम के भीतर स्थिति को आगे बढ़ाता है। |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम के भीतर स्थिति को एक बाइट से आगे बढ़ाता है, या स्ट्रीम के अंत में -1 लौटाता है। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। डिफ़ॉल्ट बफ़र आकार का उपयोग करता है[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) और धारा[`Length`](../streamcontainer/length/) मान. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। डिफ़ॉल्ट बफ़र आकार का उपयोग करता है[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) और धारा[`Length`](../streamcontainer/length/) मान. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | सभी स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। स्ट्रीम का उपयोग करता है[`Length`](../streamcontainer/length/) मान. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। स्ट्रीम का उपयोग करता है[`Length`](../streamcontainer/length/) मान. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | स्ट्रीम के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है (कॉपी करता है)। |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है। |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | स्ट्रीम की स्थिति को स्ट्रीम की शुरुआत में सेट करता है। यह मान StreamContainer कंस्ट्रक्टर में पारित प्रारंभिक स्ट्रीम स्थिति से ऑफसेट का प्रतिनिधित्व करता है। |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | स्ट्रीम डेटा को इसमें कनवर्ट करता हैByte सरणी. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | स्ट्रीम डेटा को इसमें कनवर्ट करता हैByte सरणी. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | सभी निर्दिष्ट बाइट्स को स्ट्रीम में लिखता है। |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | बाइट्स के अनुक्रम को वर्तमान स्ट्रीम में लिखता है और इस स्ट्रीम के भीतर वर्तमान स्थिति को लिखे गए बाइट्स की संख्या से आगे बढ़ाता है। |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | स्ट्रीम में वर्तमान स्थिति के लिए एक बाइट लिखता है और स्ट्रीम के भीतर स्थिति को एक बाइट आगे बढ़ाता है। |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | निहित डेटा को दूसरे में कॉपी करता है[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | निहित डेटा को दूसरे में कॉपी करता है[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | से एक स्पष्ट रूपांतरण करता है`FileStreamContainer` कोStream . (2 operators) |

### यह सभी देखें

* class [StreamContainer](../streamcontainer/)
* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


