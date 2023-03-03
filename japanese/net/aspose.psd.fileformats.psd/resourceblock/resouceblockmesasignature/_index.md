---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Aspose.PSD for .NET API リファレンス
description: ResourceBlock 分野. ImageReady. のリソース署名
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady. のリソース署名

```csharp
public const int ResouceBlockMeSaSignature;
```

### 例

次のコード例は、MeSa 署名付きのリソースを使用して PSD ファイルの読み込みと保存を修正する機能を示しています。

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

### 関連項目

* class [ResourceBlock](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* 組み立て [Aspose.PSD](../../../)


