---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD for .NET API Reference"
description: "AiImage プロパティ。アクティブページのインデックスを取得または設定します"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

アクティブページのインデックスを取得または設定します。

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

このプロパティは PDF 形式の AI 画像にのみ適用されます。画像が PDF 形式でない場合やページが存在しない場合、プロパティは -1 になります。このプロパティは、AI 画像のどのページがレンダリングの基礎になるかを示します。

## 例

以下のコードは、Ai 画像でアクティブページを変更できる機能のサポートを示しています。

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// AI 画像をロードします。
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // デフォルトでは、ActivePageIndex は 0 です。
    // したがって、このプロパティを変更せずに AI 画像を保存すると、最初のページがレンダリングされて保存されます。
    image.Save(firstPageOutputPng, new PngOptions());

    // アクティブページインデックスを2ページ目に変更します。
    image.ActivePageIndex = 1;

    // AI 画像の2ページ目を PNG 画像として保存します。
    image.Save(secondPageOutputPng, new PngOptions());

    // アクティブページインデックスを3ページ目に変更します。
    image.ActivePageIndex = 2;

    // AI 画像の3ページ目を PNG 画像として保存します。
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### 関連項目

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


