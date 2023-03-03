---
title: Layer.Layer
second_title: .NET API 참조용 Aspose.PSD
description: Layer 건설자. 의 새 인스턴스를 초기화합니다.Layer 수업. 지연 초기화를 위한 생성자.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

의 새 인스턴스를 초기화합니다.[`Layer`](../) 수업. 지연 초기화를 위한 생성자.

```csharp
public Layer()
```

### 예

다음 예제는 Aspose.PSD에서 간단한 생성자 버전을 사용하는 경우 새로 만든 레이어에 그릴 수 있는 방법을 보여줍니다.

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

    // 펜 도구로 사각형 그리기
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 단색 브러시로 파란색의 다른 사각형을 그립니다.
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 또한보십시오

* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`Layer`](../) 클래스.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| image | RasterImage | 이미지. |
| disposeImage | Boolean | 로 설정된 경우`진실` [이미지 폐기]. |

### 예

다음 코드는 JPEG/PNG/etc 이미지 파일을 직접 로드하지 않고 PsdImage에 로드하는 기능을 보여줍니다.

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

### 또한보십시오

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`Layer`](../) 클래스.

```csharp
public Layer(Stream stream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 이미지 스트림 |

### 예

다음 예제는 Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif 이미지를 레이어로 PsdImage에 추가하는 방법을 보여줍니다.

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

### 또한보십시오

* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`Layer`](../) 바이트 배열의 클래스.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| bounds | Rectangle | 레이어 경계입니다. |
| redBytes | Byte[] | 레드 바이트. |
| greenBytes | Byte[] | 녹색 바이트. |
| blueBytes | Byte[] | 파란색 바이트. |
| name | String | 레이어 이름입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 바이트 배열은 비어 있을 수 없습니다. |

### 또한보십시오

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)


