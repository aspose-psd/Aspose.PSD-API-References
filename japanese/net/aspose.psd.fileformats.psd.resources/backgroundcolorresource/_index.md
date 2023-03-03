---
title: Class BackgroundColorResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource クラス. 画像印刷設定の枠線情報を持つリソース.
type: docs
weight: 3640
url: /ja/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
## BackgroundColorResource class

画像印刷設定の枠線情報を持つリソース.

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | 背景色を取得または設定します。 |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | リソース データ サイズをバイト単位で取得します。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意の識別子を取得または設定します。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | 必要最小限の PSD バージョンを取得します。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | リソース名を取得または設定します。サイズを均等にするためにパディングされた Pascal 文字列 (null 名は 2 バイトの 0 で構成されます). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | リソース署名を取得します。常に '8BIM'. である必要があります |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | データを含むリソース ブロック サイズをバイト単位で取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 指定したストリームにリソース ブロックを保存します。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | リソース値を検証します。 |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 組み立て [Aspose.PSD](../../)


