---
title: "SmartObjectLayer.DuplicateLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "SmartObjectLayer 메서드. 이 레이어를 복사하여 새로운 스마트 오브젝트 레이어를 생성합니다. 임베드된 스마트 오브젝트의 경우 임베드된 이미지가 공유된다는 점에 유의하십시오. 임베드된 이미지를 복사하려면 NewSmartObjectViaCopy 메서드를 사용하십시오."
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/
---
{{< psd/tize >}}
## SmartObjectLayer.DuplicateLayer method

이 레이어를 복사하여 새로운 스마트 오브젝트 레이어를 생성합니다. 임베드된 스마트 오브젝트의 경우 임베드된 이미지가 공유됩니다. 임베드된 이미지를 복사하려면 [`NewSmartObjectViaCopy`](../newsmartobjectviacopy/) 메서드를 사용하십시오.

```csharp
public SmartObjectLayer DuplicateLayer()
```

### 반환 값

복제된 [`SmartObjectLayer`](../) 인스턴스입니다.

## 예제

이 예제들은 PSD 이미지에서 스마트 객체 레이어를 복사하는 방법을 보여줍니다.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// 이 예제들은 PSD 이미지에서 스마트 객체 레이어를 복사하는 방법을 보여줍니다.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
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
            // 임베드된 스마트 객체 이미지를 반전시켜 보겠습니다 (내부 PSD 이미지의 경우 첫 번째 레이어만 반전합니다).
            InvertImage(innerImage);

            // PSD 레이어의 임베디드 스마트 객체 이미지를 교체합시다
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // 복제된 레이어는 원본 스마트 오브젝트와 임베드된 이미지를 공유합니다.
        // 그리고 명시적으로 업데이트해야 하며, 그렇지 않으면 렌더링 캐시가 변경되지 않은 상태로 유지됩니다.
        // 우리는 NewSmartObjectViaCopy에 의해 생성된 새 레이어가
        // 다른 레이어와 임베드된 이미지를 공유하지 않도록 합니다.
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

### 또 보기

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


