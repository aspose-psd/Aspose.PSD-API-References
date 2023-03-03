---
title: FillLayer.ReplaceNonTransparentColors
second_title: .NET API 참조용 Aspose.PSD
description: FillLayer 방법. 모든 불투명 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 저장합니다. 참고 투명하지 않은 이미지에 사용하면 모든 색상이 단일 색상으로 교체됩니다.
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

모든 불투명 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 저장합니다. 참고: 투명하지 않은 이미지에 사용하면 모든 색상이 단일 색상으로 교체됩니다.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newColorArgb | Int32 | 투명하지 않은 색상을 대체할 새로운 색상 ARGB 값입니다. |

### 예

다음 코드는 CMYK ColorMode 16비트 지원과 Aspose.PSD.Graphics 클래스를 사용하여 그리는 기능을 보여줍니다.

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### 또한보십시오

* class [FillLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* 집회 [Aspose.PSD](../../../)


