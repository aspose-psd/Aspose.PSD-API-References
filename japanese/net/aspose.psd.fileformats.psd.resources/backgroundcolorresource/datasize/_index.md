---
title: "BackgroundColorResource.DataSize"
second_title: "Aspose.PSD for .NET API Reference"
description: "BackgroundColorResource プロパティ。リソース データサイズ（バイト）を取得します"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

リソースデータのサイズ（バイト）を取得します。

```csharp
public override int DataSize { get; }
```

### Property Value

リソースデータサイズです。

## 例

次の例は BackgroundColorResource リソースのサポートを示しています。

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // BackgroundColorResource を更新する
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### 関連項目

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


