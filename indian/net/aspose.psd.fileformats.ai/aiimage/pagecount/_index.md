---
title: "AiImage.PageCount"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "AiImage प्रॉपर्टी। पृष्ठों की संख्या। पुराने AI फ़ॉर्मेट इमेज के लिए यह हमेशा 0 के बराबर होती है।"
type: docs
weight: 110
url: /hi/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

पेजों की संख्या। पुराने AI फ़ॉर्मेट इमेजेज़ के लिए हमेशा 0 के बराबर होती है।

```csharp
public int PageCount { get; }
```

### Property Value

पृष्ठों की संख्या।

## उदाहरण

निम्नलिखित कोड AiImage प्रॉपर्टी के समर्थन को दर्शाता है, जो पृष्ठों की संख्या AiImage.PageCount के लिए है।

```csharp
[C#]

string sourceFile = "2241.ai";
string[] outputFiles = new string[3]
{
    "2241_pageNumber_0.png",
    "2241_pageNumber_1.png",
    "2241_pageNumber_2.png",
};

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.PageCount, 3);

    for (int i = 0; i < image.PageCount; i++)
    {
        image.ActivePageIndex = i;
        image.Save(outputFiles[i], new PngOptions());
    }
}
```

### देखें भी

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


