---
title: BackgroundColorResource.Color
second_title: Aspose.PSD for .NET API リファレンス
description: BackgroundColorResource 財産. 背景色を取得または設定します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

背景色を取得または設定します。

```csharp
public Color Color { get; set; }
```

### 例

次の例は、BackgroundColorResource リソースのサポートを示しています。

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

    // BackgroundColorResource を更新します
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### 関連項目

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* 組み立て [Aspose.PSD](../../../)


