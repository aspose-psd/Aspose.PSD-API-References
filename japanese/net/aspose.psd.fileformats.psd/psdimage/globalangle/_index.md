---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdImage プロパティ。グローバル角度を取得または設定します"
type: docs
weight: 100
url: /ja/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

グローバル角度を取得または設定します。

```csharp
public int GlobalAngle { get; set; }
```

## 例

以下のコードは、グローバル角度値を変更するための PsdImage.GlobalAngle プロパティのサポートを示しています。

```csharp
[C#]

// DropShadowEffect.UseGlobalLight プロパティが 'true' の場合、DropShadowEffect オブジェクトは PsdImage.GlobalAngle プロパティから角度値を使用します。

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### 関連項目

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


