---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ResourceBlock 필드. ImageReady의 리소스 서명"
type: docs
weight: 90
url: /ko/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady의 리소스 서명.

```csharp
public const int ResouceBlockMeSaSignature;
```

## 예제

다음 코드 예제는 MeSa 서명을 가진 리소스를 포함한 PSD 파일을 올바르게 로드하고 저장하는 기능을 보여줍니다.

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(2)1..psd";
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### 또 보기

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


