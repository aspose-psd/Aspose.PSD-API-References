---
title: "LinkResource.Item"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LinkResource 속성. 지정된 인덱스의 LinkDataSource를 가져오며, 이는 링크 데이터 소스의 고유 식별자입니다."
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/
---
{{< psd/tize >}}
## LinkResource indexer

지정된 인덱스의 [`LinkDataSource`](../../linkdatasource/)를 가져오며, 이는 링크 데이터 소스의 고유 식별자입니다..

```csharp
public LinkDataSource this[Guid index] { get; }
```

| 매개변수 | 설명 |
| --- | --- |
| index | 링크 데이터 소스 고유 식별자로서의 인덱스입니다. |

### 반환 값

[`LinkDataSource`](../../linkdatasource/) 인스턴스입니다.

### Property Value

[`LinkDataSource`](../../linkdatasource/)입니다.

## 예제

다음 코드는 임베디드 스마트 객체 지원을 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// 이 예제는 PSD 파일에서 스마트 객체 레이어를 변경하고 스마트 객체 원본 임베디드 콘텐츠를 내보내기/업데이트하는 방법을 보여줍니다.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // PSD 스마트 객체 레이어에서 임베디드 스마트 객체 이미지를 내보냅시다
        smartObjectLayer.ExportContents(exportPath);

        // 원본 이미지가 올바르게 저장되었는지 확인합시다
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // 원본 스마트 객체 이미지를 반전시킵시다
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // PSD 레이어의 임베디드 스마트 객체 이미지를 교체합시다
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 업데이트된 이미지가 올바르게 저장되었는지 확인합시다
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 또 보기

* class [LinkDataSource](../../linkdatasource/)
* class [LinkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


