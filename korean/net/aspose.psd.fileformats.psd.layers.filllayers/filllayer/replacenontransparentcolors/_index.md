---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "FillLayer 메서드. 모든 비투명 색상을 새로운 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체된다는 점에 유의하십시오."
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

투명하지 않은 모든 색상을 새 색상으로 교체하고 원래 알파 값을 유지하여 부드러운 가장자리를 보존합니다. 참고: 투명도가 없는 이미지에 사용하면 모든 색상이 하나의 색상으로 교체됩니다.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorArgb | Int32 | 비투명 색상을 교체하기 위한 새로운 색상 ARGB 값. |

## 예제

다음 코드는 CMYK ColorMode 16비트 지원 및 Aspose.PSD.Graphics 클래스를 사용한 그리기 기능을 보여줍니다.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 또 보기

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


