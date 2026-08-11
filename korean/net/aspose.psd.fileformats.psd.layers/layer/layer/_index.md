---
title: "Layer.Layer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Layer 생성자. Layer 클래스의 새 인스턴스를 초기화합니다. 지연 초기화를 위한 생성자"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

[`Layer`](../) 클래스의 새 인스턴스를 초기화합니다. 지연 초기화를 위한 생성자.

```csharp
public Layer()
```

## 예제

다음 예제는 Aspose.PSD에서 단순 생성자 버전을 사용할 경우 새로 만든 레이어에 그릴 수 있는 방법을 보여줍니다

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

    // Pen 도구로 사각형을 그립니다
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Solid Brush를 사용하여 파란색으로 또 다른 사각형을 그립니다
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 또 보기

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

새로운 [`Layer`](../) 클래스 인스턴스를 초기화합니다.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | RasterImage | 이미지. |
| disposeImage | Boolean | 만약 `true` 로 설정하면 [dispose image]. |

## 예제

다음 코드는 직접 로드하지 않고 JPEG/PNG/등 이미지 파일을 PsdImage에 로드하는 기능을 보여줍니다.

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

### 또 보기

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

새로운 [`Layer`](../) 클래스 인스턴스를 초기화합니다.

```csharp
public Layer(Stream stream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 이미지 스트림 |

## 예제

다음 예제는 Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif 이미지들을 레이어로 PsdImage에 추가하는 방법을 보여줍니다.

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

### 또 보기

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

바이트 배열에서 새로운 [`Layer`](../) 클래스 인스턴스를 초기화합니다.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bounds | Rectangle | 레이어 경계. |
| redBytes | Byte[] | 빨간색 바이트. |
| greenBytes | Byte[] | 녹색 바이트. |
| blueBytes | Byte[] | 파란색 바이트. |
| name | String | 레이어 이름입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 바이트 배열은 비어 있을 수 없으며, 바이트 배열 길이는 경계 차원 (bounds.Width * bounds.Height)과 동일해야 합니다. |

### 또 보기

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


