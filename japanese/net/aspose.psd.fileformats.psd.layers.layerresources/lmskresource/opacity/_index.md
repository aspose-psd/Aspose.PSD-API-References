---
title: "LmskResource.Opacity"
second_title: "Aspose.PSD for .NET API Reference"
description: "LmskResource プロパティ。 不透明度を取得します"
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/
---
{{< psd/tize >}}
## LmskResource.Opacity property

不透明度を取得します。

```csharp
public short Opacity { get; set; }
```

### Property Value

不透明度です。

## 例

以下のコードは、LmskResource プロパティを変更して 16 ビット画像のレイヤーマスク表示オプションを変更する方法を示しています。

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 16ビット画像をロードします。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // LmskResource を検索します。
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // LmskResource のプロパティを確認します。
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // LmskResource のプロパティを変更します。
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // 画像を保存します。
    image.Save(outputPsd);
}
```

### 関連項目

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


