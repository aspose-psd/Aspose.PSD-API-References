---
title: "Layer.Layer"
second_title: "Aspose.PSD for .NET API Reference"
description: "Layer コンストラクタ。Layer クラスの新しいインスタンスを初期化します。遅延初期化用のコンストラクタ"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

[`Layer`](../) クラスの新しいインスタンスを初期化します。遅延初期化用のコンストラクタ。

```csharp
public Layer()
```

## 例

以下の例は、Aspose.PSD でシンプルコンストラクタ バージョンを使用した場合に、新しく作成されたレイヤーに描画できる方法を示しています

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

    // ペンツールで矩形を描く
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Solid Brush を使用して青色で別の長方形を描画する
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 関連項目

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

新しい [`Layer`](../) クラスのインスタンスを初期化します。

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | RasterImage | 画像です。 |
| disposeImage | Boolean | `true` に設定した場合は [dispose image]。 |

## 例

以下のコードは、JPEG/PNG/その他の画像ファイルを直接読み込むことなく PsdImage にロードする機能を示しています。

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

新しい [`Layer`](../) クラスのインスタンスを初期化します。

```csharp
public Layer(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 画像ストリーム |

## 例

次の例は、Bmp、Jpeg、Jpeg2000、Png、Psd、Tiff、Gif 画像をレイヤーとして PsdImage に追加できる方法を示しています

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

バイト配列から新しい [`Layer`](../) クラスのインスタンスを初期化します。

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bounds | Rectangle | レイヤーの境界。 |
| redBytes | Byte[] | 赤バイトです。 |
| greenBytes | Byte[] | 緑バイトです。 |
| blueBytes | Byte[] | 青バイトです。 |
| name | 文字列 | レイヤー名です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | バイト配列は空であってはならず、バイト配列の長さは bounds の寸法 (bounds.Width * bounds.Height) と等しくなければなりません。 |

### 関連項目

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


