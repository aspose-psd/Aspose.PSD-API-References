---
title: "Класс SmartObjectResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SmartObjectResource. Определяет класс SmartObjectResource, который содержит информацию о слое Smart Object в файле PSD. Является базовым классом для ресурсов Sold и Sole, используемых для поддержки слоёв Smart Object в изображениях Adobe Photoshop."
type: docs
weight: 3340
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---
{{< psd/tize >}}
## SmartObjectResource class

Определяет класс SmartObjectResource, который содержит информацию о слое смарт‑объекта в файле PSD. Это базовый класс для ресурсов Sold и Sole, используемый для поддержки слоёв смарт‑объектов в изображениях Adobe® Photoshop®.

```csharp
public abstract class SmartObjectResource : PlacedResource, ISmartObjectLayerResource
```

## Свойства

| Имя | Описание |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy/) { get; set; } | Получает или задает политику сглаживания данных слоя Smart Object в изображении PSD. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | Получает или задает положение снизу размещённого слоя в изображении PSD. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | Получает или задает границы размещённого слоя в файле PSD. |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp/) { get; set; } | Получает или задает значение компа данных слоя Smart Object в файле PSD. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid/) { get; set; } | Получает или задает идентификатор текущего выбранного компа для дочернего документа, который будет -1, если ничего не выбрано. Компы — это композиции макета страницы, которые дизайнеры могут создавать. Используя layer comps, вы можете создавать, управлять и просматривать несколько версий макета в одном файле Adobe Photoshop. Компа слоя — это снимок состояния панели Layers. Layer comps сохраняют три типа параметров слоя, но это свойство получает идентификатор выбора Layer Comp для слоя Smart Object в файле PSD. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop/) { get; set; } | Получает или задает обрезку данных слоя Smart Object в изображении PSD. |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator/) { get; set; } | Получает или задает знаменатель длительности. |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator/) { get; set; } | Получает или задает числитель длительности. |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount/) { get; set; } | Получает или задает количество кадров данных слоя смарт‑объекта в файле PSD. |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator/) { get; set; } | Получает или задает знаменатель шага кадра. |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator/) { get; set; } | Получает или задает числитель шага кадра. |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height/) { get; set; } | Получает или задает высоту. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | Получает или задает единицу измерения горизонтальных точек сетки. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | Получает или задает значение, указывающее, является ли стиль деформации этого экземпляра пользовательским. Если true, содержит точки сетки. Если false, удаляет точки сетки. |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items/) { get; set; } | Получает или задает элементы дескриптора данных слоя смарт‑объекта в файле PSD. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | Получает или задает положение слева размещённого слоя в файле PSD. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length/) { get; } | Получает длину ресурса смарт‑объекта в байтах. |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix/) { get; set; } | Получает или задает неаффинную матрицу преобразования данных слоя смарт‑объекта в файле PSD. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid/) { get; } | Получает исходный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. Это свойство получает исходный идентификатор выбора слоя Comp для смарт‑объекта в файле PSD. [Композиции слоёв в смарт‑объектах](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber/) { get; set; } | Получает или задает номер страницы данных слоя смарт‑объекта в файле PSD. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | Получает или задает значение перспективы размещённого слоя в файле PSD. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | Получает или задает другое значение перспективы размещённого слоя в файле PSD. |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid/) { get; set; } | Получает или задает уникальный идентификатор этих данных слоя смарт‑объекта в изображении PSD. |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype/) { get; set; } | Получает или задает тип данных слоя смарт‑объекта в файле PSD. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution/) { get; set; } | Получает или задает разрешение данных слоя смарт‑объекта в файле PSD. |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit/) { get; set; } | Получает или задает единицу измерения разрешения данных слоя смарт‑объекта в файле PSD. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | Получает или задает положение справа размещённого слоя в файле PSD. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | Получает или задает верхнее положение размещённого слоя в изображении PSD. |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages/) { get; set; } | Получает или задает общее количество страниц данных слоя смарт‑объекта в файле PSD. |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix/) { get; set; } | Получает или задает матрицу преобразования данных слоя смарт‑объекта в файле PSD. |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | Получает или задает глобальный уникальный идентификатор данных слоя смарт‑объекта `SmartObjectResource` в изображении PSD. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | Получает или задает значение порядка U размещённого слоя в файле PSD. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | Получает или задает значение искажения размещённого слоя в изображении PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | Получает версию размещённого слоя в файле PSD, обычно 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | Получает или задает единицу измерения вертикальных точек сетки. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | Получает или задает значение порядка V размещённого слоя в файле PSD. |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width/) { get; set; } | Получает или задает ширину. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save/)(StreamContainer, int) | Сохраняет ресурс смарт‑объекта в указанный потоковый контейнер. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Примеры

Следующий код демонстрирует поддержку ресурсов SoLEResource, SmartObjectResource и PlacedResource.

```csharp
[C#]

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

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

void CheckSmartObjectResourceValues(object[] expectedValue, SmartObjectResource resource)
{
    AssertAreEqual(expectedValue[0], resource.IsCustom);
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
    AssertAreEqual(expectedValue[30], resource.NonAffineTransformMatrix);
    if (resource.IsCustom)
    {
        AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
        AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
    }
}

void SetNewSmartValues(SmartObjectResource resource, object[] newValues)
{
    // Эти значения мы не меняем в ресурсе
    newValues[0] = resource.IsCustom;
    newValues[1] = resource.UniqueId.ToString();
    newValues[5] = resource.PlacedLayerType;
    newValues[14] = resource.UOrder;
    newValues[15] = resource.VOrder;
    newValues[28] = resource.OriginalCompId;

    // Эти значения также следует изменить в PlLdResource (с указанным UniqueId)
    // и некоторые из них должны соответствовать подлежащему смарт‑объекту в LinkDataSource
    resource.PageNumber = (int)newValues[2]; // 2;
    resource.TotalPages = (int)newValues[3]; // 3;
    resource.AntiAliasPolicy = (int)newValues[4]; // 0;
    resource.TransformMatrix = (double[])newValues[6];
    resource.Value = (double)newValues[7]; // 1.23456789;
    resource.Perspective = (double)newValues[8]; // 0.123456789;
    resource.PerspectiveOther = (double)newValues[9]; // 0.987654321;
    resource.Top = (double)newValues[10]; // -126;
    resource.Left = (double)newValues[11]; // -215;
    resource.Bottom = (double)newValues[12]; // 248;
    resource.Right = (double)newValues[13]; // 145;
    resource.Crop = (int)newValues[16]; // 5;
    resource.FrameStepNumerator = (int)newValues[17]; // 1;
    resource.FrameStepDenominator = (int)newValues[18]; // 601;
    resource.DurationNumerator = (int)newValues[19]; // 2;
    resource.DurationDenominator = (int)newValues[20]; // 602;
    resource.FrameCount = (int)newValues[21]; // 11;
    resource.Width = (double)newValues[22]; // 541;
    resource.Height = (double)newValues[23]; // 249;
    resource.Resolution = (double)newValues[24]; // 144;
    resource.ResolutionUnit = (UnitTypes)newValues[25];
    resource.Comp = (int)newValues[26]; // 21;
    resource.CompId = (int)newValues[27]; // 22;
    resource.NonAffineTransformMatrix = (double[])newValues[30];

    // Этот уникальный Id следует изменить в ссылках, если они есть
    resource.PlacedId = new Guid((string)newValues[29]);  // "12345678-9abc-def0-9876-54321fecba98");
    if (resource.IsCustom)
    {
        resource.HorizontalMeshPointUnit = (UnitTypes)newValues[31];
        resource.HorizontalMeshPoints = (double[])newValues[32];
        resource.VerticalMeshPointUnit = (UnitTypes)newValues[33];
        resource.VerticalMeshPoints = (double[])newValues[34];
    }

    // Будьте осторожны с некоторыми параметрами: сохранённое изображение может стать нечитаемым в Adobe® Photoshop®
    ////resource.UOrder = 6;
    ////resource.VOrder = 9;

    // Не меняйте это иначе 
 вы не сможете использовать свободное трансформирование
    // или измените подлежащий смарт‑объект на векторный тип
    ////resource.PlacedLayerType = PlacedLayerType.Vector;

    // Должен существовать действительный PlLdResource с этим уникальным Id
    ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");
}

object[] newSmartValues = new object[]
{
    true,
    null,
    2,
    3,
    0,
    PlacedLayerType.ImageStack,
    new double[8]
    {
        12.937922786050663,
        19.419959734187131,
        2.85445817782261,
        1.0540625423957124,
        7.20861031651307,
        14.634102808208553,
        17.292074924741144,
        4
    },
    1.23456789,
    0.123456789,
    0.987654321,
    -126d,
    -215d,
    248d,
    145d,
    4,
    4,
    5,
    1,
    601,
    2,
    602,
    11,
    541d,
    249d,
    144d,
    UnitTypes.Percent,
    21,
    22,
    23,
    "12345678-9abc-def0-9876-54321fecba98",
    new double[8]
    {
        129.937922786050663,
        195.419959734187131,
        26.85445817782261,
        12.0540625423957124,
        72.20861031651307,
        147.634102808208553,
        175.292074924741144,
        42
    },
    UnitTypes.Points,
    new double[16]
    {
        0.01d, 103.33333333333433d, 206.66686666666666d, 310.02d,
        0.20d, 103.33333333333533d, 206.69666666666666d, 310.03d,
        30.06d, 103.33333333336333d, 206.66660666666666d, 310.04d,
        04.05d, 103.33333333373333d, 206.66666166666666d, 310.05d
    },
    UnitTypes.Distance,
    new double[16]
    {
        0.06d, 0.07d, 0.08d, 0.09d,
        49.066666666666664d, 49.266666666666664d, 49.566666666666664d, 49.766666666666664d,
        99.133333333333329d, 99.433333333333329d, 99.633333333333329d, 99.833333333333329d,
        140, 141, 142, 143,
    },
};

object[] expectedValues = new object[]
{
    new object[]
    {
        false,
        "5867318f-3174-9f41-abca-22f56a75247e",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
        0d,
        0d,
        0d,
        0d,
        0d,
        2d,
        2d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        2d,
        2d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "64b3997c-06e0-be40-a349-41acf397c897",
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
    }
};

var sourceFilePath = "rgb8_2x2_linked.psd";
var outputPath = "rgb8_2x2_linked_output.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLeResource soleResource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as SoLeResource;
            if (resource != null)
            {
                soleResource = resource;
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                CheckSmartObjectResourceValues(expectedValue, resource);
                SetNewSmartValues(resource, newSmartValues);

                break;
            }
        }
    }

    AssertIsTrue(soleResource != null);
    image.Save(outputPath, new PsdOptions(image));
    using (PsdImage savedImage = (PsdImage)Image.Load(outputPath))
    {
        foreach (Layer imageLayer in savedImage.Layers)
        {
            foreach (var imageResource in imageLayer.Resources)
            {
                var resource = imageResource as SoLeResource;
                if (resource != null)
                {
                    CheckSmartObjectResourceValues(newSmartValues, resource);

                    break;
                }
            }
        }
    }
}
```

### См. также

* class [SoLdResource](../soldresource/)
* class [SoLeResource](../soleresource/)
* class [PlacedResource](../placedresource/)
* interface [ISmartObjectLayerResource](../ismartobjectlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


