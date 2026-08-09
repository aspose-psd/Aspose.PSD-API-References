---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD for .NET API 参考"
description: "ResourceBlock 字段。ImageReady 的资源签名"
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady 的资源签名。

```csharp
public const int ResouceBlockMeSaSignature;
```

## 示例

下面的代码示例演示了正确加载和保存带有 MeSa 签名资源的 PSD 文件的能力。

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

### 另请参阅

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


