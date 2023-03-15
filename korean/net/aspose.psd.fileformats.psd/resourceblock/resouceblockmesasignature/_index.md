---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: .NET API 참조용 Aspose.PSD
description: ResourceBlock 필드. ImageReady. 의 리소스 서명
type: docs
weight: 90
url: /ko/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady. 의 리소스 서명

```csharp
public const int ResouceBlockMeSaSignature;
```

### 예

다음 코드 예제는 MeSa 서명이 있는 리소스로 PSD 파일을 수정하고 저장하는 기능을 보여줍니다.

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(21..psd");
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### 또한보십시오

* class [ResourceBlock](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* 집회 [Aspose.PSD](../../../)


