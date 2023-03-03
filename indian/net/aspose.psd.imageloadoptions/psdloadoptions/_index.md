---
title: Class PsdLoadOptions
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions कक्ष. Psd लड वकल्प
type: docs
weight: 4770
url: /hi/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Psd लोड विकल्प

```csharp
public class PsdLoadOptions : LoadOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | प्राप्त करता है या सेट करता है कि प्रदान की गई छवि को ताना परिवर्तन के साथ या उसके बिना सहेजना है या नहीं। |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | हो जाता है या सेट करता है[`Image`](../../aspose.psd/image/) पृष्ठभूमि[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | डेटा रिकवरी मोड प्राप्त या सेट करता है। |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | यह इंगित करने वाला मान प्राप्त या सेट करता है कि क्या [अल्फ़ा चैनल को अनदेखा करें]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि PSD पाठ परत निश्चित चौड़ाई को UpdateText ऑपरेशन निष्पादन पर अनदेखा किया जाएगा या नहीं। |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि [लोड प्रभाव संसाधन] (डिफ़ॉल्ट रूप से संसाधन लोड नहीं होता है)। इस विकल्प को सेट करने पर केवल समर्थित प्रभाव ही अंतिम मर्ज की गई छवि के लिए रेंडर किए जाएंगे. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | प्रगति ईवेंट हैंडलर प्राप्त या सेट करता है। |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि [केवल पढ़ने के लिए मोड का उपयोग करें]। यह रीड-ओनली मोड है, जो Adobe Photoshop के साथ समान संगतता के लिए समर्थित है। जब यह विकल्प सेट किया जाता है, तो परतों के लिए लागू किए गए सभी परिवर्तन अंतिम छवि में सहेजे नहीं जाएंगे। सभी डेटा का उपयोग इमेजडेटा सेक्शन से किया जाता है, इसलिए यह फोटोशॉप के समान है। डिफ़ॉल्ट रूप से सभी लोड की गई छवियां Adobe Photoshop संगत के समान नहीं हैं। |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि [लोड प्रभाव संसाधन के लिए डिस्क का उपयोग करें] (डिफ़ॉल्ट रूप से डिस्क का उपयोग प्रभाव संसाधन को लोड करने के लिए किया जाता है, लेकिन यदि यह मान गलत पर सेट करके पर्याप्त है तो मेमोरी का उपयोग किया जा सकता है)। |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि ICC प्रोफ़ाइल रूपांतरण लागू किया जाना चाहिए या नहीं। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि दस्तावेज़ रूपांतरण प्रगति सही ढंग से और बिना किसी अपवाद के काम करती है।

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### यह सभी देखें

* class [LoadOptions](../../aspose.psd/loadoptions/)
* नाम स्थान [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* सभा [Aspose.PSD](../../)


