---
title: "SmartObjectLayer.ReplaceContents"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "SmartObjectLayer 메서드. 스마트 오브젝트 레이어에 포함된 스마트 오브젝트 콘텐츠를 교체합니다"
type: docs
weight: 160
url: /ko/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/
---
{{< psd/tize >}}
## ReplaceContents(Image) {#replacecontents}

스마트 오브젝트 레이어에 임베드된 스마트 오브젝트 내용을 교체합니다.

```csharp
public void ReplaceContents(Image image)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | Image | 이미지. |

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

* class [Image](../../../aspose.psd/image/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(Image, ResolutionSetting) {#replacecontents_1}

스마트 오브젝트 레이어에 임베드된 스마트 오브젝트 내용을 교체합니다.

```csharp
public void ReplaceContents(Image image, ResolutionSetting resolution)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | Image | 이미지. |
| 해상도 | ResolutionSetting | 해상도 설정입니다. null인 경우 이미지 해상도가 사용됩니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 포함된 스마트 오브젝트만 교체할 수 있습니다. |

## 예제

이 예제는 새 콘텐츠 파일의 해상도가 다를 때 ReplaceContents 메서드가 올바르게 작동함을 보여줍니다.

```csharp
[C#]

// 이 예제는 새 콘텐츠 파일의 해상도가 다를 때 ReplaceContents 메서드가 올바르게 작동함을 보여줍니다.
string fileName = "CommonPsb.psd";
string filePath = baseFolder + fileName; // original PSD image
string newContentPath = baseFolder + "image.jpg"; // the new content file for the smart object
string outputFilePath = outputFolder + "ChangedPsd";
string pngOutputPath = outputFilePath + ".png"; // the output PNG file
string psdOutputPath = outputFilePath + ".psd"; // the output PSD file
using (PsdImage psd = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < psd.Layers.Length; i++)
    {
        var layer = psd.Layers[i];
        SmartObjectLayer smartObjectLayer = layer as SmartObjectLayer;
        if (smartObjectLayer != null)
        {
            smartObjectLayer.ReplaceContents(newContentPath);

            psd.Save(psdOutputPath);
            psd.Save(pngOutputPath, new PngOptions() { ColorType = Aspose.PSD.FileFormats.Png.PngColorType.TruecolorWithAlpha });
        }
    }
}
```

### 또 보기

* class [Image](../../../aspose.psd/image/)
* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, ResolutionSetting) {#replacecontents_3}

내용을 파일로 교체합니다. 이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다.

```csharp
public void ReplaceContents(string linkedPath, ResolutionSetting resolution)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| linkedPath | String | 연결된 경로. |
| 해상도 | ResolutionSetting | 해상도 설정입니다. null인 경우 이미지 해상도가 사용됩니다. |

### 또 보기

* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, ResolutionSetting, bool) {#replacecontents_4}

내용을 파일로 교체합니다. 이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다.

```csharp
public void ReplaceContents(string linkedPath, ResolutionSetting resolution, bool isReplaceOnlyThis)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| linkedPath | String | 연결된 경로. |
| 해상도 | ResolutionSetting | 해상도 설정입니다. null인 경우 이미지 해상도가 사용됩니다. |
| isReplaceOnlyThis | Boolean | 이 플래그는 이 Smart Layer에서 콘텐츠를 교체하거나 이 콘텐츠가 있는 모든 Smart Layer에 교체함을 표시합니다. |

## 예제

이 예제는 새 콘텐츠 파일의 해상도가 다를 때 ReplaceContents 메서드가 올바르게 작동함을 보여줍니다.

```csharp
[C#]

// 이 예제는 새 콘텐츠 파일의 해상도가 다를 때 ReplaceContents 메서드가 올바르게 작동함을 보여줍니다.
string fileName = "CommonPsb.psd";
string filePath = baseFolder + fileName; // original PSD image
string newContentPath = baseFolder + "image.jpg"; // the new content file for the smart object
string outputFilePath = outputFolder + "ChangedPsd";
string pngOutputPath = outputFilePath + ".png"; // the output PNG file
string psdOutputPath = outputFilePath + ".psd"; // the output PSD file
using (PsdImage psd = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < psd.Layers.Length; i++)
    {
        var layer = psd.Layers[i];
        SmartObjectLayer smartObjectLayer = layer as SmartObjectLayer;
        if (smartObjectLayer != null)
        {
            smartObjectLayer.ReplaceContents(newContentPath);

            psd.Save(psdOutputPath);
            psd.Save(pngOutputPath, new PngOptions() { ColorType = Aspose.PSD.FileFormats.Png.PngColorType.TruecolorWithAlpha });
        }
    }
}
```

다음 코드는 동일한 소스 참조를 가진 여러 스마트 객체에서 콘텐츠를 교체하는 지원을 보여줍니다.

```csharp
[C#]

string srcFile = "Source.psd";
string replaceAll = "replaceAll.jpg";
string replaceOne = "replaceOne.jpg";
string outFileImgAll = "output_All.png";
string outFileImgOne = "output_one.png";

// 이 작업은 동일한 링크가 있는 모든 스마트 레이어에서 동일한 컨텍스트를 교체합니다.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // 이 작업은 동일한 콘텐츠를 사용하는 모든 SmartLayers의 콘텐츠를 교체합니다.
    smartObjectLayer.ReplaceContents(replaceAll, false);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgAll, new PngOptions());
}

//이 작업은 선택된 레이어의 컨텍스트만 교체하고, 다른 모든 레이어는 동일한 컨텍스트를 그대로 유지합니다.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // 선택된 SmartLayer의 콘텐츠만 교체합니다.
    smartObjectLayer.ReplaceContents(replaceOne, true);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgOne, new PngOptions());
}
```

### 또 보기

* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string) {#replacecontents_2}

내용을 파일로 교체합니다. 이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다.

```csharp
public void ReplaceContents(string linkedPath)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| linkedPath | String | 연결된 경로. |

### 또 보기

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, bool) {#replacecontents_5}

내용을 파일로 교체합니다. 이후에 UpdateModifiedContent 메서드를 호출할 필요가 없습니다.

```csharp
public void ReplaceContents(string linkedPath, bool isReplaceOnlyThis)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| linkedPath | String | 연결된 경로. |
| isReplaceOnlyThis | Boolean | 이 플래그는 이 Smart Layer에서 콘텐츠를 교체하거나 이 콘텐츠가 있는 모든 Smart Layer에 교체함을 표시합니다. |

## 예제

다음 코드는 동일한 소스 참조를 가진 여러 스마트 객체에서 콘텐츠를 교체하는 지원을 보여줍니다.

```csharp
[C#]

string srcFile = "Source.psd";
string replaceAll = "replaceAll.jpg";
string replaceOne = "replaceOne.jpg";
string outFileImgAll = "output_All.png";
string outFileImgOne = "output_one.png";

// 이 작업은 동일한 링크가 있는 모든 스마트 레이어에서 동일한 컨텍스트를 교체합니다.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // 이 작업은 동일한 콘텐츠를 사용하는 모든 SmartLayers의 콘텐츠를 교체합니다.
    smartObjectLayer.ReplaceContents(replaceAll, false);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgAll, new PngOptions());
}

//이 작업은 선택된 레이어의 컨텍스트만 교체하고, 다른 모든 레이어는 동일한 컨텍스트를 그대로 유지합니다.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // 선택된 SmartLayer의 콘텐츠만 교체합니다.
    smartObjectLayer.ReplaceContents(replaceOne, true);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgOne, new PngOptions());
}
```

다음 코드는 연결된 스마트 객체 업데이트 지원을 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// 이 예제는 이러한 메서드를 사용하여 외부 또는 내장 스마트 객체 레이어를 업데이트하는 방법을 보여줍니다:
// RelinkToFile, UpdateModifiedContent, ExportContents
ExampleOfUpdatingSmartObjectLayer("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfUpdatingSmartObjectLayer("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfUpdatingSmartObjectLayer(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // 이 예제는 PSD 파일에서 스마트 객체 레이어를 변경하고 해당 콘텐츠를 내보내기/업데이트하는 방법을 보여줍니다.
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "updating_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_modified.png";
    string png2OutputPath = dataDir + fileName + "_updated_modified.png";
    string psd2OutputPath = dataDir + fileName + "_updated_modified.psd";
    string exportPath = dataDir + fileName + "_exported." + GetFormatExt(format);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        var contentType = smartObjectLayer.ContentType;
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        if (contentType == SmartObjectType.AvailableLinked)
        {
            Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
            // PSD 스마트 객체 레이어에서 외부 스마트 객체 이미지를 새 위치로 내보냅시다
            // 우리는 이를 수정할 것이기 때문입니다.
            smartObjectLayer.ExportContents(exportPath);
            smartObjectLayer.RelinkToFile(exportPath);
        }

        // 스마트 객체의 콘텐츠를 반전시킵시다: 내부(캐시되지 않은) 이미지
        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(new LoadOptions()))
        {
            InvertImage(innerImage);
            using (var stream = new MemoryStream())
            {
                innerImage.Save(stream);
                smartObjectLayer.Contents = stream.ToArray();
            }
        }

        // 수정된 콘텐츠가 아직 렌더링에 영향을 주지 않는지 확인합시다.
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        smartObjectLayer.UpdateModifiedContent();

        // 업데이트된 콘텐츠가 렌더링에 영향을 주고 PSD 이미지가 올바르게 저장되는지 확인합시다
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// 이 예제는 ConvertToLinked 메서드를 사용하여 내장 스마트 객체를 외부 링크된 콘텐츠로 변환하는 방법을 보여줍니다.
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("new_panama-papers-4.psd", 0x10caa, 0, 0, 0x280, 0x169, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r3-embedded.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-tiff.psd", 0xca94, 0, 0, 0xb, 0x10, FileFormat.Tiff);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-bmp.psd", 0x278, 0, 0, 0xb, 0x10, FileFormat.Bmp);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-gif.psd", 0x3ec, 0, 0, 0xb, 0x10, FileFormat.Gif);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg.psd", 0x327, 0, 0, 0xb, 0x10, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg2000.psd", 0x519f, 0, 0, 0xb, 0x10, FileFormat.Jpeg2000);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-psd.psd", 0xc074, 0, 0, 0xb, 0x10, FileFormat.Psd);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfEmbeddedSmartObjectLayerToLinkedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // 이는 PSD 파일의 내장 스마트 객체 레이어를 외부 레이어로 변환하는 방법을 보여줍니다.
    var formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_linked_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_external.png";
    string psdOutputPath = dataDir + fileName + "_to_external.psd";
    string externalPath = dataDir + fileName + "_external." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        Directory.CreateDirectory(Path.GetDirectoryName(externalPath));
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer.ConvertToLinked(externalPath);

        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        // 변환된 이미지가 올바르게 저장되었는지 확인합시다
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);
    }
}

// 이 예제는 EmbedLinked 메서드를 사용하여 PSD 파일에 외부 스마트 객체 레이어 하나 또는 모든 링크된 레이어를 임베드하는 방법을 보여줍니다.
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
void ExampleOfLinkedSmartObjectLayerToEmbeddedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_embedded_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_embedded.png";
    string psdOutputPath = dataDir + fileName + "_to_embedded.psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer0 = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer0.EmbedLinked();
        AssertAreEqual(contentsLength, smartObjectLayer0.Contents.Length);
        AssertAreEqual(left, smartObjectLayer0.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer0.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer0.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer0.ContentsBounds.Bottom);
        if (image.Layers.Length >= 2)
        {
            var smartObjectLayer1 = (SmartObjectLayer)image.Layers[1];
            AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer0.ContentType);
            AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer1.ContentType);

            image.SmartObjectProvider.EmbedAllLinked();
            foreach (Layer layer in image.Layers)
            {
                var smartLayer = layer as SmartObjectLayer;
                if (smartLayer != null)
                {
                    AssertAreEqual(SmartObjectType.Embedded, smartLayer.ContentType);
                }
            }
        }

        Directory.CreateDirectory(Path.GetDirectoryName(psdOutputPath));
        // 변환된 이미지가 올바르게 저장되었는지 확인합시다
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer.ContentType);
    }
}

// 이 예제는 Adobe® Photoshop® 외부 스마트 객체 레이어를 변경하고 해당 콘텐츠를 내보내기/업데이트하는 방법을 보여줍니다
// ExportContents 및 ReplaceContents 메서드를 사용하여.
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked2.psd", 0x4aea, 0, 0, 10, 10, FileFormat.Psd);
void ExampleOfExternalSmartObjectLayerSupport(string filePath, int contentsLength, int left, int top, int right, int bottom, FileFormat format)
{
    string formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "external_support_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + ".png";
    string psdOutputPath = dataDir + fileName + ".psd";
    string linkOutputPath = dataDir + fileName + "_inverted." + formatExt;
    string png2OutputPath = dataDir + fileName + "_updated.png";
    string psd2OutputPath = dataDir + fileName + "_updated.psd";
    string exportPath = dataDir + fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[image.Layers.Length - 1];
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
        // PSD 스마트 객체 레이어에서 링크된 스마트 객체 이미지를 내보냅시다
        smartObjectLayer.ExportContents(exportPath);

        // 원본 이미지가 올바르게 저장되었는지 확인합시다
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // 링크된 스마트 객체 이미지를 반전시킵시다
            InvertImage(innerImage);
            innerImage.Save(linkOutputPath);

            // PSD 레이어에서 링크된 스마트 객체 이미지를 교체합시다
            smartObjectLayer.ReplaceContents(linkOutputPath);
        }

        // 업데이트된 이미지가 올바르게 저장되었는지 확인합시다
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// 이미지를 반전시킵니다.
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// 래스터 이미지를 반전시킵니다.
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

// 형식 확장자를 가져옵니다.
string GetFormatExt(FileFormat format)
{
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : format.ToString().ToLowerInvariant();
    return formatExt;
}
```

### 또 보기

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


