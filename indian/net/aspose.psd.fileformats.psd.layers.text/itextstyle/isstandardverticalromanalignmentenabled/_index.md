---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ITextStyle property. मानक ऊर्ध्वाधर रोमन संरेखण प्राप्त करता है या सेट करता है। यह BaselineDirection संसाधन मान पर आधारित है और केवल तब लागू होता है जब पाठ अभिविन्यास ऊर्ध्वाधर हो।"
type: docs
weight: 170
url: /hi/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

मानक वर्टिकल रोमन अलाइनमेंट को प्राप्त करता है या सेट करता है। यह BaselineDirection रिसोर्स वैल्यू पर आधारित है और केवल तब लागू होता है जब टेक्स्ट ओरिएंटेशन वर्टिकल हो।

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## उदाहरण

निम्नलिखित कोड नए IsStandardVerticalRomanAlignmentEnabled प्रॉपर्टी के समर्थन को दर्शाता है।

```csharp
[C#]

// निम्नलिखित कोड नए IsStandardVerticalRomanAlignmentEnabled प्रॉपर्टी को संपादित करने की क्षमता को दर्शाता है।
// यह वर्तमान में रेंडरिंग को प्रभावित नहीं करता, बल्कि केवल आपको प्रॉपर्टी मान को संपादित करने की अनुमति देता है।

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // सही पढ़ना
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // सही पढ़ना
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### देखें भी

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


