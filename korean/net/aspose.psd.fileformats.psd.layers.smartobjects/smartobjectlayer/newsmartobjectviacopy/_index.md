---
title: SmartObjectLayer.NewSmartObjectViaCopy
second_title: .NET API 참조용 Aspose.PSD
description: SmartObjectLayer 방법. 이를 대처하여 새로운 스마트 오브젝트 레이어를 생성합니다. Adobe Photoshop의 Layer  Smart Objects  New Smart Object via Copy 기능을 재현합니다. 임베디드 스마트 오브젝트에 대해서만 활성화됩니다. 또한 복사됩니다. 포함된 이미지를 공유하려면 사용DuplicateLayer 방법.
type: docs
weight: 120
url: /ko/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
## SmartObjectLayer.NewSmartObjectViaCopy method

이를 대처하여 새로운 스마트 오브젝트 레이어를 생성합니다. Adobe� Photoshop의 `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` 기능을 재현합니다�. 임베디드 스마트 오브젝트에 대해서만 활성화됩니다. 또한 복사됩니다. 포함된 이미지를 공유하려면 사용[`DuplicateLayer`](../duplicatelayer/) 방법.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### 반환 값

복제된[`SmartObjectLayer`](../) 사례.

### 예

이 예제는 PSD 이미지에서 스마트 개체 레이어를 복사하는 방법을 보여줍니다.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// 이 예제는 PSD 이미지에서 스마트 개체 레이어를 복사하는 방법을 보여줍니다.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // 복사할 레이어 번호
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // 포함된 스마트 개체 이미지를 반전시키겠습니다(내부 PSD 이미지의 경우 첫 번째 레이어만 반전함).
            InvertImage(innerImage);

            // PSD 레이어에 포함된 스마트 오브젝트 이미지를 교체해 보겠습니다.
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 복제된 레이어는 포함된 이미지를 원본 스마트 개체와 공유합니다.
        // 명시적으로 업데이트해야 하며 그렇지 않으면 렌더링 캐시가 변경되지 않은 상태로 유지됩니다.
        // NewSmartObjectViaCopy에 의해 생성된 새 레이어가
        // 포함된 이미지를 다른 사람과 공유하지 않습니다.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// PSD 이미지를 포함한 래스터 이미지를 반전시킵니다.
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

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### 또한보십시오

* class [SmartObjectLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* 집회 [Aspose.PSD](../../../)


