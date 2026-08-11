---
title: "RasterImage.SavePixels"
second_title: "Aspose.PSD for .NET API Reference"
description: "RasterImage メソッド。ピクセルを保存します"
type: docs
weight: 540
url: /ja/net/aspose.psd/rasterimage/savepixels/
---
{{< psd/tize >}}
## RasterImage.SavePixels method

ピクセルを保存します。

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 矩形 | Rectangle | ピクセルを保存する矩形。 |
| ピクセル | Color[] | ピクセル配列です。 |

## 例

この例では、Color 型の配列にピクセル情報をロードし、配列を操作して画像に戻す方法を示します。これらの操作を実行するために、MemoryStream オブジェクトを使用して新しい Image ファイル（PSD 形式）を作成します。

```csharp
[C#]

//MemoryStream のインスタンスを作成します。
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions のインスタンスを作成し、Source プロパティを含むさまざまなプロパティを設定します。
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image のインスタンスを作成します。
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //画像の境界を領域として指定して、画像のピクセルを取得します
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //配列をループし、代替インデックスピクセルの色を設定します
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //インデックスピクセルの色を黄色に設定します
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //インデックスピクセルの色を青に設定します
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //画像にピクセルの変更を適用します
        image.SavePixels(image.Bounds, pixels);

        // すべての変更を保存します。
        image.Save();
    }

    //MemoryStream をファイルに書き込みます
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 関連項目

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


