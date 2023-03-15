---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD for .NET API リファレンス
description: BackgroundColorResource 財産. 必要最小限の PSD バージョンを取得します
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

必要最小限の PSD バージョンを取得します。

```csharp
public override int MinimalVersion { get; }
```

### プロパティ値

最小限の PSD バージョン。

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

* class [BackgroundColorResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* 組み立て [Aspose.PSD](../../../)


