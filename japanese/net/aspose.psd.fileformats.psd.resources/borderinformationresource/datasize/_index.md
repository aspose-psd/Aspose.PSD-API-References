---
title: BorderInformationResource.DataSize
second_title: Aspose.PSD for .NET API リファレンス
description: BorderInformationResource 財産. リソース データ サイズをバイト単位で取得します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
## BorderInformationResource.DataSize property

リソース データ サイズをバイト単位で取得します。

```csharp
public override int DataSize { get; }
```

### プロパティ値

リソースのデータサイズ.

### 例

次の例は、BorderInformationResource リソースのサポートを示しています。

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // BorderInformationResource を更新します
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### 関連項目

* class [BorderInformationResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* 組み立て [Aspose.PSD](../../../)


