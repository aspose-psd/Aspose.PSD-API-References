---
title: Class SoLdResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoLdResource 수업. PSD 파일의 스마트 개체 레이어에 대한 정보가 포함된 SoLdResource 클래스를 정의합니다. Adobe Photoshop 이미지에서 스마트 개체 레이어를 지원하는 데 사용됩니다.
type: docs
weight: 3020
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
## SoLdResource class

PSD 파일의 스마트 개체 레이어에 대한 정보가 포함된 SoLdResource 클래스를 정의합니다. Adobe® Photoshop® 이미지에서 스마트 개체 레이어를 지원하는 데 사용됩니다.

```csharp
public class SoLdResource : SmartObjectResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SoLdResource](soldresource/#constructor)() | 의 새 인스턴스를 초기화합니다.`SoLdResource` class. 이 기본 생성자는 다음에서 사용하도록 설계되었습니다.SoLdResourceLoader . 사용[`SmartResourceCreator`](../smartresourcecreator/) SoLdResource 클래스 생성용. |
| [SoLdResource](soldresource/#constructor_1)(Guid, bool, bool) | 의 새 인스턴스를 초기화합니다.`SoLdResource` class. 준비된 인스턴스를 얻으려면 Items 속성을 설정하거나 InitializeItems()를 호출해야 합니다. 이 생성자는 다음에서 사용하도록 설계되었습니다.[`SmartResourceCreator`](../smartresourcecreator/) 및 단위 테스트에서. 사용[`SmartResourceCreator`](../smartresourcecreator/) SoLdResource 클래스 생성용. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy/) { get; set; } | PSD 이미지에서 스마트 개체 레이어 데이터의 앤티 앨리어스 정책을 가져오거나 설정합니다. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | PSD 이미지에서 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다. |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 comp 값을 가져오거나 설정합니다. [스마트 오브젝트의 레이어 구성 요소](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid/) { get; set; } | 자식 문서에 대해 현재 선택된 구성 요소의 ID를 가져오거나 설정합니다. 아무것도 선택하지 않으면 -1이 됩니다. 구성 요소는 디자이너가 만들 수 있는 페이지 레이아웃의 구성 요소입니다. 레이어 구성 요소를 사용하면 단일 Adobe® Photoshop® 파일에서 레이아웃의 여러 버전 을 만들고 관리하고 볼 수 있습니다. 레이어 구성 요소는 레이어 패널 상태의 스냅샷입니다. 레이어 구성 요소는 세 가지 유형의 레이어 옵션을 저장하지만 이 속성은 PSD 파일에서 고급 개체 레이어에 대한 레이어 구성 요소 선택 식별자를 가져옵니다. [스마트 오브젝트의 레이어 구성 요소](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop/) { get; set; } | PSD 이미지에서 스마트 개체 레이어 데이터의 자르기를 가져오거나 설정합니다. |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator/) { get; set; } | 기간 분모를 가져오거나 설정합니다. |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator/) { get; set; } | 기간 분자를 가져오거나 설정합니다. |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 프레임 수를 가져오거나 설정합니다. |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator/) { get; set; } | 프레임 단계 분모를 가져오거나 설정합니다. |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator/) { get; set; } | 프레임 단계 분자를 가져오거나 설정합니다. |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height/) { get; set; } | 높이를 가져오거나 설정합니다. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | PSD 파일에 배치된 레이어의 수평 메쉬 포인트를 가져오거나 설정합니다. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | 수평 메쉬 포인트의 측정 단위를 가져오거나 설정합니다. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | 이 인스턴스 뒤틀기 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. true인 경우 메쉬 포인트를 포함합니다. false로 설정하면 메쉬 점을 지웁니다. |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 설명자 항목을 가져오거나 설정합니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/key/) { get; } | SoLd 스마트 개체 계층 리소스 키를 가져옵니다. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | PSD 파일에서 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length/) { get; } | 스마트 개체 리소스 길이를 바이트 단위로 가져옵니다. |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 비아핀 변환 매트릭스를 가져오거나 설정합니다. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid/) { get; } | 하위 문서에 대해 현재 선택한 Comp의 원래 ID를 가져옵니다. 아무것도 선택하지 않은 경우 -1이 됩니다. 이 속성은 PSD 파일의 스마트 개체 레이어에 대한 원래 레이어 Comp 선택 식별자를 가져옵니다. [스마트 오브젝트의 레이어 구성 요소](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 페이지 번호를 가져오거나 설정합니다. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | PSD 파일에 배치된 레이어의 원근 값을 가져오거나 설정합니다. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | PSD 파일에 배치된 레이어의 원근 다른 값을 가져오거나 설정합니다. |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid/) { get; set; } | PSD 이미지에서 이 스마트 개체 레이어 데이터의 고유 식별자를 가져오거나 설정합니다. |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 유형을 가져오거나 설정합니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion/) { get; } | 스마트 개체 리소스에 필요한 최소 psd 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 해상도를 가져오거나 설정합니다. |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 해상도 측정 단위를 가져오거나 설정합니다. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | PSD 파일에서 배치된 레이어의 올바른 위치를 가져오거나 설정합니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature/) { get; } | 스마트 개체 리소스 서명을 가져옵니다. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | PSD 이미지에서 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 총 페이지 수를 가져오거나 설정합니다. |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix/) { get; set; } | PSD 파일에서 스마트 개체 레이어 데이터의 변형 매트릭스를 가져오거나 설정합니다. |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | 스마트 개체 레이어 데이터의 전역 고유 식별자를 가져오거나 설정합니다.[`SmartObjectResource`](../smartobjectresource/) PSD 이미지에서. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | PSD 이미지에 배치된 레이어의 워프 값을 가져오거나 설정합니다. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | PSD 파일에 배치된 레이어의 버전을 가져옵니다. 일반적으로 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | PSD 파일에 배치된 레이어의 수평 메쉬 포인트를 가져오거나 설정합니다. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | 수직 메쉬 포인트의 측정 단위를 가져오거나 설정합니다. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다. |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width/) { get; set; } | 너비를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save/)(StreamContainer, int) | 스마트 개체 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey/) | 유형 도구 정보 키: 'SoLd'. |

### 예

다음 코드는 SoLdResource 리소스의 지원을 보여줍니다.

```csharp
[C#]

// 이 예제는 PSD 파일의 스마트 개체 레이어 데이터 속성을 가져오거나 설정하는 방법을 보여줍니다.

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

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
var outputFilePath = "LayeredSmartObjects8bit2_output.psd";
var expectedValues = new object[]
{
    new object[]
    {
        true,
        "76f05a3b-7523-5e42-a1bb-27f4735bffa0",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        149d,
        310d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        310d,
        149d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "d3388655-19e4-9742-82f2-f553bb01046a",
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 0.0d, 0.0d, 0.0d,
            49.666666666666664d, 49.666666666666664d, 49.666666666666664d, 49.666666666666664d,
            99.333333333333329d, 99.333333333333329d, 99.333333333333329d, 99.333333333333329d,
            149, 149, 149, 149,
        },
    },
    new object[]
    {
        true,
        "cf0477a8-8f92-ac4f-9462-f78e26234851",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        721d,
        1280d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        1280d,
        721d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "625cc4b9-2c5f-344f-8636-03caf2bd3489",
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 0.0, 0.0, 0.0,
            240.33333333333331, 240.33333333333331, 240.33333333333331, 240.33333333333331,
            480.66666666666663, 480.66666666666663, 480.66666666666663, 480.66666666666663,
            721, 721, 721, 721,
        },
        0,
        0
    }
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLdResource resource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            resource = imageResource as SoLdResource;
            if (resource != null)
            {
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[0], resource.IsCustom);
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                AssertAreEqual(expectedValue[2], resource.PageNumber);
                AssertAreEqual(expectedValue[3], resource.TotalPages);
                AssertAreEqual(expectedValue[4], resource.AntiAliasPolicy);
                AssertAreEqual(expectedValue[5], resource.PlacedLayerType);
                AssertAreEqual(8, resource.TransformMatrix.Length);
                AssertAreEqual((double[])expectedValue[6], resource.TransformMatrix);
                AssertAreEqual(expectedValue[7], resource.Value);
                AssertAreEqual(expectedValue[8], resource.Perspective);
                AssertAreEqual(expectedValue[9], resource.PerspectiveOther);
                AssertAreEqual(expectedValue[10], resource.Top);
                AssertAreEqual(expectedValue[11], resource.Left);
                AssertAreEqual(expectedValue[12], resource.Bottom);
                AssertAreEqual(expectedValue[13], resource.Right);
                AssertAreEqual(expectedValue[14], resource.UOrder);
                AssertAreEqual(expectedValue[15], resource.VOrder);

                AssertAreEqual(expectedValue[16], resource.Crop);
                AssertAreEqual(expectedValue[17], resource.FrameStepNumerator);
                AssertAreEqual(expectedValue[18], resource.FrameStepDenominator);
                AssertAreEqual(expectedValue[19], resource.DurationNumerator);
                AssertAreEqual(expectedValue[20], resource.DurationDenominator);
                AssertAreEqual(expectedValue[21], resource.FrameCount);
                AssertAreEqual(expectedValue[22], resource.Width);
                AssertAreEqual(expectedValue[23], resource.Height);
                AssertAreEqual(expectedValue[24], resource.Resolution);
                AssertAreEqual(expectedValue[25], resource.ResolutionUnit);
                AssertAreEqual(expectedValue[26], resource.Comp);
                AssertAreEqual(expectedValue[27], resource.CompId);
                AssertAreEqual(expectedValue[28], resource.OriginalCompId);
                AssertAreEqual(expectedValue[29], resource.PlacedId.ToString());
                AssertAreEqual((IEnumerable)expectedValue[30], resource.NonAffineTransformMatrix);
                if (resource.IsCustom)
                {
                    AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
                    AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
                    var temp = resource.VerticalMeshPoints;
                    resource.VerticalMeshPoints = resource.HorizontalMeshPoints;
                    resource.HorizontalMeshPoints = temp;
                }

                // 이 값은 PlLdResource(지정된 UniqueId 포함)에서도 변경되어야 합니다.
                // 그리고 그 중 일부는 LinkDataSource의 밑줄 스마트 개체와 일치해야 합니다.
                resource.PageNumber = 2;
                resource.TotalPages = 3;
                resource.AntiAliasPolicy = 0;
                resource.Value = 1.23456789;
                resource.Perspective = 0.123456789;
                resource.PerspectiveOther = 0.987654321;
                resource.Top = -126;
                resource.Left = -215;
                resource.Bottom = 248;
                resource.Right = 145;
                resource.Crop = 4;
                resource.FrameStepNumerator = 1;
                resource.FrameStepDenominator = 601;
                resource.DurationNumerator = 2;
                resource.DurationDenominator = 602;
                resource.FrameCount = 11;
                resource.Width = 541;
                resource.Height = 249;
                resource.Resolution = 144;
                resource.Comp = 21;
                resource.CompId = 22;
                resource.TransformMatrix = new double[8]
                {
                    12.937922786050663,
                    19.419959734187131,
                    2.85445817782261,
                    1.0540625423957124,
                    7.20861031651307,
                    14.634102808208553,
                    17.292074924741144,
                    4
                };
                resource.NonAffineTransformMatrix = new double[8]
                {
                    129.937922786050663,
                    195.419959734187131,
                    26.85445817782261,
                    12.0540625423957124,
                    72.20861031651307,
                    147.634102808208553,
                    175.292074924741144,
                    42
                };

                // 이 고유 ID는 참조에서 변경되어야 합니다.
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // 일부 매개변수에 주의: Adobe® Photoshop®에서 이미지를 읽을 수 없게 될 수 있습니다.
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // 변경하지 않으면 자유 변형을 사용할 수 없습니다.
                // 또는 밑줄 스마트 객체를 벡터 유형으로 변경
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // 이 고유 ID를 가진 유효한 PlLdResource가 있어야 합니다.
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### 또한보십시오

* class [SmartObjectResource](../smartobjectresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


