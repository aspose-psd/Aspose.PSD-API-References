---
title: "क्लास PsdLoadOptions"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions क्लास. Psd लोड विकल्प"
type: docs
weight: 5250
url: /hi/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

PSD लोड विकल्प

```csharp
public class PsdLoadOptions : LoadOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | यदि लेयर में कोई बदलाव नहीं किया गया है तो रेंडरिंग के दौरान मूल लेयर पिक्सेल को संरक्षित करना चाहिए या नहीं, इसे प्राप्त करता है या सेट करता है। |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | रेंडर की गई इमेज के साथ, वॉर्प ट्रांसफ़ॉर्म के साथ या बिना, सहेजना चाहिए या नहीं, इसे प्राप्त करता है या सेट करता है। |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | [`Image`](../../aspose.psd/image/) पृष्ठभूमि [`Color`](../../aspose.psd/color/) को प्राप्त करता है या सेट करता है। |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | डेटा रिकवरी मोड को प्राप्त करता है या सेट करता है। |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [अल्फा चैनल को अनदेखा करें]। |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि UpdateText ऑपरेशन के निष्पादन पर PSD टेक्स्ट लेयर की निश्चित चौड़ाई को अनदेखा किया जाएगा या नहीं। |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [इफ़ेक्ट्स रिसोर्स लोड करें] (डिफ़ॉल्ट रूप से रिसोर्स लोड नहीं होता)। जब यह विकल्प सेट किया जाता है, तो केवल समर्थित इफ़ेक्ट्स को अंतिम मर्ज्ड इमेज में रेंडर किया जाएगा। |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [रीड‑ओनली मोड का उपयोग करें]। यह रीड‑ओनली मोड है, जो Adobe Photoshop के साथ समान संगतता के लिए समर्थित है। जब यह विकल्प सेट किया जाता है, तो लेयर्स पर लागू सभी परिवर्तन अंतिम इमेज में सहेजे नहीं जाते। सभी डेटा ImageData सेक्शन से उपयोग किया जाता है, इसलिए यह Photoshop के समान है। डिफ़ॉल्ट रूप से सभी लोड की गई इमेजेज Adobe Photoshop के साथ संगत नहीं होतीं। |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | PSD इमेज लोड करते समय उपयोग किए जाने वाले रीड‑ओनली मोड को प्राप्त करता है या सेट करता है। |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [इफ़ेक्ट्स रिसोर्स लोड करने के लिए डिस्क का उपयोग करें] (डिफ़ॉल्ट रूप से इफ़ेक्ट्स रिसोर्स लोड करने के लिए डिस्क उपयोग की जाती है, लेकिन यदि यह पर्याप्त हो तो इस मान को false सेट करके मेमोरी उपयोग की जा सकती है)। |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि ICC प्रोफ़ाइल रूपांतरण लागू किया जाना चाहिए या नहीं। |

## उदाहरण

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

### देखें भी

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


