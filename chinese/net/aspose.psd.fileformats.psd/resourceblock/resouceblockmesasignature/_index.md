---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Aspose.PSD for .NET API 参考
description: ResourceBlock 场地. ImageReady 的资源签名
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady 的资源签名。

```csharp
public const int ResouceBlockMeSaSignature;
```

### 例子

下一个代码示例演示了使用带有 MeSa 签名的资源正确加载和保存 PSD 文件的能力。

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

### 也可以看看

* class [ResourceBlock](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* 部件 [Aspose.PSD](../../../)


