---
title: "Класс SoLdResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoLdResource class. Определяет класс SoLdResource, который содержит информацию о слое смарт‑объекта в файле PSD. Используется для поддержки слоёв смарт‑объектов в изображениях Adobe Photoshop."
type: docs
weight: 3370
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
{{< psd/tize >}}
## SoLdResource class

Определяет класс SoLdResource, который содержит информацию о слое умного объекта в файле PSD. Используется для поддержки слоёв умных объектов в изображениях Adobe® Photoshop®.

```csharp
public class SoLdResource : SmartObjectResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SoLdResource](soldresource/#constructor)() | Инициализирует новый экземпляр класса `SoLdResource`. Этот конструктор по умолчанию предназначен для использования SoLdResourceLoader. Используйте [`SmartResourceCreator`](../smartresourcecreator/) для создания классов SoLdResource. |
| [SoLdResource](soldresource/#constructor_1)(Guid, bool, bool) | Инициализирует новый экземпляр класса `SoLdResource`. Необходимо установить свойство Items или вызвать InitializeItems(), чтобы получить готовый экземпляр. Этот конструктор предназначен для использования [`SmartResourceCreator`](../smartresourcecreator/) и в модульных тестах. Используйте [`SmartResourceCreator`](../smartresourcecreator/) для создания классов SoLdResource. |

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
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | Получает или задает глобальный уникальный идентификатор данных слоя смарт‑объекта [`SmartObjectResource`](../smartobjectresource/) в изображении PSD. |
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

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey/) | Ключ информации инструмента типа: 'SoLd'. |

## Примеры

Следующий код демонстрирует поддержку ресурса SoLdResource.

```csharp
[C#]

// Этот пример показывает, как получить или установить свойства данных слоя смарт‑объекта файла PSD.

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

                // Эти значения также следует изменить в PlLdResource (с указанным UniqueId)
                // и некоторые из них должны соответствовать подлежащему смарт‑объекту в LinkDataSource
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

                // Этот уникальный Id следует изменить в ссылках, если они есть
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // Будьте осторожны с некоторыми параметрами: изображение может стать нечитаемым в Adobe® Photoshop®
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // Не меняйте это иначе 
 вы не сможете использовать свободное трансформирование
                // или измените подлежащий смарт‑объект на векторный тип
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // Должен существовать действительный PlLdResource с этим уникальным Id
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### См. также

* class [SmartObjectResource](../smartobjectresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


