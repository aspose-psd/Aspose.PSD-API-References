---
title: RasterImage.SavePixels
second_title: Aspose.PSD for .NET API リファレンス
description: RasterImage 方法. ピクセルを保存します
type: docs
weight: 520
url: /ja/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

ピクセルを保存します。

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rectangle | Rectangle | ピクセルを保存する四角形。 |
| pixels | Color[] | ピクセル配列。 |

### 例

この例では、Type Color の配列にピクセル情報をロードし、配列を操作して画像に戻す方法を示します。これらの操作を実行するために、この例では、MemoryStream オブジェクトを使用して新しいイメージ ファイル (PSD 形式) を作成します。

```csharp
[C#]

//MemoryStream のインスタンスを作成する
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions のインスタンスを作成し、Source プロパティを含むさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image のインスタンスを作成する
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //領域を画像境界として指定して、画像のピクセルを取得します
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //配列をループし、代替インデックス付きピクセルの色を設定します
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //インデックス付きピクセルの色を黄色に設定
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //インデックス付きピクセルの色を青に設定
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // ピクセルの変更を画像に適用します
        image.SavePixels(image.Bounds, pixels);

        // すべての変更を保存します。
        image.Save();
    }

    //メモリストリームをファイルに書き込む
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 関連項目

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* 名前空間 [Aspose.PSD](../../rasterimage/)
* 組み立て [Aspose.PSD](../../../)


