---
title: "VscgResource.Items"
second_title: "Aspose.PSD for .NET API Reference"
description: "VscgResource プロパティ。構造体アイテムの配列を取得または設定します。警告: Items 配列の値は、Items 内の構造体に格納されている塗り設定のタイプを決定する KeyForData プロパティと一致する必要があります"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/
---
{{< psd/tize >}}
## VscgResource.Items property

構造体アイテムの配列を取得または設定します。**Warning:** `Items` 配列の値は `KeyForData` プロパティと一致する必要があります。このプロパティは `Items` 内の構造体に格納される塗り設定のタイプを決定します。

```csharp
public OSTypeStructure[] Items { get; }
```

### Property Value

[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) アイテムの配列です。

## 例

以下のコードは VscgResource のサポートを示しています。

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// 変更をチェックしています
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### 関連項目

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [VscgResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


