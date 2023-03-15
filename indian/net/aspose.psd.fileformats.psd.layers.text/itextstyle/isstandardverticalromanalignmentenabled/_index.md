---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ITextStyle संपत्त. मनक लंबवत रमन संरेखण प्रप्त य सेट करत है यह बेसलइन डयरेक्शन संसधन मन पर आधरत केवल तभ लगू हत है जब टेक्स्ट ओरएंटेशन हत हैVertical .
type: docs
weight: 170
url: /hi/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

मानक लंबवत रोमन संरेखण प्राप्त या सेट करता है। यह बेसलाइन डायरेक्शन संसाधन मान पर आधारित केवल तभी लागू होता है जब टेक्स्ट ओरिएंटेशन होता हैVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### उदाहरण

निम्न कोड नई IsStandardVerticalRomanAlignmentEnabled संपत्ति के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

// निम्न कोड नई IsStandardVerticalRomanAlignmentEnabled संपत्ति को संपादित करने की क्षमता प्रदर्शित करता है।
// यह फिलहाल रेंडरिंग को प्रभावित नहीं करता है, लेकिन आपको केवल संपत्ति मूल्य को संपादित करने की अनुमति देता है।

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

### यह सभी देखें

* interface [ITextStyle](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* सभा [Aspose.PSD](../../../)


