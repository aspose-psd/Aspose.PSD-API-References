---
title: Layer.Layer
second_title: Aspose.PSD for .NET API リファレンス
description: Layer コンストラクタ. の新しいインスタンスを初期化しますLayerクラス遅延初期化のコンストラクター.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

の新しいインスタンスを初期化します[`Layer`](../)クラス。遅延初期化のコンストラクター.

```csharp
public Layer()
```

### 例

次の例は、単純なコンストラクター バージョンが Aspose.PSD で使用されている場合に、新しく作成されたレイヤーに描画する方法を示しています。

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // ペンツールで長方形を描く
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 青色のソリッド ブラシで別の四角形を描画します
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 関連項目

* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

の新しいインスタンスを初期化します[`Layer`](../)class.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| image | RasterImage | 画像。 |
| disposeImage | Boolean | に設定した場合`真実` 【処分画像】。 |

### 例

次のコードは、直接ロードせずに JPEG/PNG/etc 画像ファイルを PsdImage にロードする機能を示しています。

```csharp
[C#]

string filePath = "PsdExample.psd";
string outputFilePath = "PsdResult.psd";
using (var image = new PsdImage(200, 200))
{
    using (var im = Image.Load(filePath))
    {
        Layer layer = null;
        try
        {
            layer = new Layer((RasterImage)im);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }
    }

    image.Save(outputFilePath);
}
```

### 関連項目

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

の新しいインスタンスを初期化します[`Layer`](../)class.

```csharp
public Layer(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 画像ストリーム |

### 例

次の例は、Bmp、Jpeg、Jpeg2000、Png、Psd、Tiff、Gif 画像をレイヤーとして PsdImage に追加する方法を示しています。

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### 関連項目

* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

の新しいインスタンスを初期化します[`Layer`](../)バイト配列からのクラス.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| bounds | Rectangle | レイヤーの境界。 |
| redBytes | Byte[] | 赤いバイト。 |
| greenBytes | Byte[] | 緑のバイト。 |
| blueBytes | Byte[] | ブルーバイト。 |
| name | String | レイヤー名。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | バイト配列を空にすることはできません または バイト配列の長さは境界次元 (bounds.Width * bounds.Height) と等しくなければなりません |

### 関連項目

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)


