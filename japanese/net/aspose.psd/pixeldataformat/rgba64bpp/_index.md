---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Aspose.PSD for .NET API Reference"
description: "PixelDataFormat プロパティ。アルファ、赤、緑、青それぞれに 16 ビット、合計 64 ビット/ピクセルで定義された PixelDataFormat を取得します。"
type: docs
weight: 110
url: /ja/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

アルファ、赤、緑、青それぞれに 16 ビット、合計 64 ビット/ピクセル で定義された [`PixelDataFormat`](../) を取得します。

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

アルファ、赤、緑、青それぞれに 16 ビット、合計 64 ビット/ピクセル で定義された [`PixelDataFormat`](../) です。

## 例

次のコードは、廃止された Color 構造体の代わりに RawColor クラスのサポートを示しています。

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### 関連項目

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


