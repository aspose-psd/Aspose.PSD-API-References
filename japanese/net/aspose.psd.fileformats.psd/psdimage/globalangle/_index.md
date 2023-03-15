---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 財産. グローバル角度を取得または設定します
type: docs
weight: 100
url: /ja/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

グローバル角度を取得または設定します。

```csharp
public int GlobalAngle { get; set; }
```

### 例

次のコードは、グローバル角度値を変更するための PsdImage.GlobalAngle プロパティのサポートを示しています。

```csharp
[C#]

// DropShadowEffect.UseGlobalLight プロパティが「true」の場合、DropShadowEffect オブジェクトは PsdImage.GlobalAngle プロパティの角度値を使用します。

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### 関連項目

* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


