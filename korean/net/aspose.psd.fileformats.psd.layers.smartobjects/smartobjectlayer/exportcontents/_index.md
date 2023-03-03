---
title: SmartObjectLayer.ExportContents
second_title: .NET API 참조용 Aspose.PSD
description: SmartObjectLayer 방법. 포함되거나 연결된 콘텐츠를 파일로 내보냅니다.
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/
---
## SmartObjectLayer.ExportContents method

포함되거나 연결된 콘텐츠를 파일로 내보냅니다.

```csharp
public void ExportContents(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 내보내기 파일 경로입니다. |

### 예

다음 코드는 Embedded Smart objects의 지원을 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// 이 예제는 PSD 파일에서 스마트 오브젝트 레이어를 변경하고 스마트 오브젝트 원본 임베디드 콘텐츠를 내보내거나 업데이트하는 방법을 보여줍니다.
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

        // PSD 스마트 개체 레이어에서 포함된 스마트 개체 이미지를 내보내겠습니다.
        smartObjectLayer.ExportContents(exportPath);

        // 원본 이미지가 제대로 저장되었는지 확인해보자
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // 원본 스마트 오브젝트 이미지를 반전시키자
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // PSD 레이어에 포함된 스마트 오브젝트 이미지를 교체해 보겠습니다.
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 업데이트된 이미지가 제대로 저장되었는지 확인해보자
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 또한보십시오

* class [SmartObjectLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* 집회 [Aspose.PSD](../../../)


