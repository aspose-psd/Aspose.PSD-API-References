---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PixelDataFormat प्रॉपर्टी। 64 बिट प्रति पिक्सेल के लिए परिभाषित PixelDataFormat प्राप्त करता है, जिसमें अल्फा, रेड, ग्रीन और ब्लू के प्रत्येक के लिए 16 बिट होते हैं।"
type: docs
weight: 110
url: /hi/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

[`PixelDataFormat`](../) को प्राप्त करता है जो 64 बिट प्रति पिक्सेल के लिए परिभाषित है, जिसमें अल्फा, रेड, ग्रीन और ब्लू के प्रत्येक के लिए 16 बिट होते हैं।

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

यह [`PixelDataFormat`](../) 64 बिट प्रति पिक्सेल के लिए परिभाषित है, जिसमें अल्फा, रेड, ग्रीन और ब्लू के प्रत्येक के लिए 16 बिट होते हैं।

## उदाहरण

निम्नलिखित कोड पुरानी Color स्ट्रक्ट के बजाय RawColor क्लास के समर्थन को दर्शाता है।

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### देखें भी

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


