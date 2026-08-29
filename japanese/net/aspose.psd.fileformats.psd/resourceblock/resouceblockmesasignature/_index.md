---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD for .NET API Reference"
description: "ResourceBlock フィールド。ImageReady のリソース署名です。"
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady のリソースシグネチャです。

```csharp
public const int ResouceBlockMeSaSignature;
```

## 例

次のコード例は、MeSa 署名を持つリソースを含む PSD ファイルを正しく読み込みおよび保存できることを示しています。

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

### 関連項目

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


