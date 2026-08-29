---
title: "SmartObjectLayer.Contents"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "SmartObjectLayer 속성. 스마트 오브젝트 레이어 콘텐츠를 가져오거나 설정합니다. 임베드된 스마트 오브젝트 콘텐츠는 임베드된 원시 이미지 파일 Data와 그 속성입니다. 연결된 스마트 오브젝트 콘텐츠는 사용 가능한 경우 연결된 이미지 파일의 원시 콘텐츠와 그 속성 LiFeDataSource입니다. IsLibraryLink가 true인 경우 Adobe Photoshop Graphics Library에서 로드하는 것을 지원하지 않습니다. 일반 링크 파일의 경우 처음에 RelativePath를 사용하여 파일을 SourceImagePath(소스 이미지 경로)와 상대적으로 찾으며, 사용 불가능하면 FullPath를 확인하고, 그래도 없으면 이미지가 있는 동일 디렉터리인 SourceImagePath에서 링크 파일을 찾습니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
{{< psd/tize >}}
## SmartObjectLayer.Contents property

스마트 오브젝트 레이어 콘텐츠를 가져오거나 설정합니다. 임베드된 스마트 오브젝트 콘텐츠는 임베드된 원시 이미지 파일: [`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) 및 그 속성입니다. 연결된 스마트 오브젝트 콘텐츠는 사용 가능한 경우 연결된 이미지 파일의 원시 콘텐츠와 그 속성: [`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 입니다. [`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/)가 true인 경우 Adobe Photoshop Graphics Library에서 로드를 지원하지 않습니다. 일반 링크 파일의 경우 먼저 [`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/)를 사용하여 파일을 SourceImagePath(소스 이미지 경로)와 상대적으로 찾고, 사용 불가능하면 [`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/)를 확인하며, 그래도 없으면 이미지가 있는 동일 디렉터리인 SourceImagePath에서 링크 파일을 찾습니다.

```csharp
public byte[] Contents { get; set; }
```

### Property Value

byte[] 스마트 오브젝트 레이어 콘텐츠.

### 예외

| 예외 | 조건 |
| --- | --- |
| NotSupportedException | Adobe Photoshop 라이브러리에서 내용을 가져올 수 없습니다. |

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

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


