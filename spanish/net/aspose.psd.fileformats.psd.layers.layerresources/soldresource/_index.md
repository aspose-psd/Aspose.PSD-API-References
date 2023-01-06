---
title: SoLdResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Define la clase SoLdResource que contiene información sobre una capa de objeto inteligente en un archivo PSD. Se utiliza para admitir capas de objetos inteligentes en las imágenes de Adobe Photoshop.
type: docs
weight: 2990
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
## SoLdResource class

Define la clase SoLdResource que contiene información sobre una capa de objeto inteligente en un archivo PSD. Se utiliza para admitir capas de objetos inteligentes en las imágenes de Adobe® Photoshop®.

```csharp
public class SoLdResource : SmartObjectResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SoLdResource](soldresource#constructor)() | Inicializa una nueva instancia del[`SoLdResource`](../soldresource) class. Este constructor predeterminado está diseñado para ser utilizado porSoLdResourceLoader . Uso[`SmartResourceCreator`](../smartresourcecreator) para crear clases de SoLdResource. |
| [SoLdResource](soldresource#constructor_1)(Guid, bool, bool) | Inicializa una nueva instancia del[`SoLdResource`](../soldresource) class. Es necesario establecer la propiedad Items o llamar a InitializeItems() para obtener una instancia lista. Este constructor está diseñado para ser utilizado por[`SmartResourceCreator`](../smartresourcecreator) y en pruebas unitarias. Uso[`SmartResourceCreator`](../smartresourcecreator) para crear clases de SoLdResource. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy) { get; set; } | Obtiene o establece la política antialiasing de los datos de la capa de objetos inteligentes en la imagen PSD. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom) { get; set; } | Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds) { get; set; } | Obtiene o establece los límites de la capa colocada en el archivo PSD. |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp) { get; set; } | Obtiene o establece el valor de compensación de los datos de la capa del objeto inteligente en el archivo PSD. [Composiciones de capas en objetos inteligentes](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid) { get; set; } | Obtiene o establece el ID de la composición actualmente seleccionada para el documento secundario, que será -1 si no se selecciona ninguna. Las composiciones son composiciones de un diseño de página que los diseñadores pueden crear. Con las composiciones de capas, puede crear, administrar y ver varias versiones de un diseño en un solo archivo de Adobe® Photoshop®. Una composición de capa es una instantánea de un estado del panel Capas. Las composiciones de capa guardan tres tipos de opciones de capa pero esta propiedad obtiene el identificador de selección de composición de capa para la capa de objeto inteligente en el archivo PSD. [Composiciones de capas en objetos inteligentes](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop) { get; set; } | Obtiene o establece el recorte de los datos de la capa del objeto inteligente en la imagen PSD. |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator) { get; set; } | Obtiene o establece el denominador de duración. |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator) { get; set; } | Obtiene o establece el numerador de duración. |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount) { get; set; } | Obtiene o establece el número de fotogramas de los datos de la capa del objeto inteligente en el archivo PSD. |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator) { get; set; } | Obtiene o establece el denominador de paso de cuadro. |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator) { get; set; } | Obtiene o establece el numerador de pasos de cuadro. |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height) { get; set; } | Obtiene o establece la altura. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints) { get; set; } | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit) { get; set; } | Obtiene o establece la unidad de medida de los puntos de la malla horizontal. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom) { get; set; } | Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. Si es verdadero, contiene puntos de malla. Si se establece en falso, borra los puntos de malla. |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items) { get; set; } | Obtiene o establece los elementos descriptores de los datos de la capa de objeto inteligente en el archivo PSD. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/key) { get; } | Obtiene la clave de recurso de capa de objeto inteligente SoLd. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left) { get; set; } | Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length) { get; } | Obtiene la longitud del recurso del objeto inteligente en bytes. |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix) { get; set; } | Obtiene o establece la matriz de transformación no afín de los datos de la capa de objeto inteligente en el archivo PSD. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid) { get; } | Obtiene el ID original del Comp seleccionado actualmente para el documento secundario, que será -1 si no se selecciona ninguno. Esta propiedad obtiene el identificador de selección de Comp de capa original para la capa de objeto inteligente en el archivo PSD. [Composiciones de capas en objetos inteligentes](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber) { get; set; } | Obtiene o establece el número de página de los datos de la capa del objeto inteligente en el archivo PSD. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective) { get; set; } | Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother) { get; set; } | Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD. |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid) { get; set; } | Obtiene o establece el identificador único de los datos de esta capa de objeto inteligente en la imagen PSD. |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype) { get; set; } | Obtiene o establece el tipo de datos de la capa de objeto inteligente en el archivo PSD. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion) { get; } | Obtiene la versión psd mínima necesaria para el recurso de objeto inteligente. 0 indica que no hay restricciones. |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution) { get; set; } | Obtiene o establece la resolución de los datos de la capa del objeto inteligente en el archivo PSD. |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit) { get; set; } | Obtiene o establece la unidad de medida de resolución de los datos de la capa de objeto inteligente en el archivo PSD. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right) { get; set; } | Obtiene o establece la ubicación correcta de la capa colocada en el archivo PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature) { get; } | Obtiene la firma del recurso del objeto inteligente. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top) { get; set; } | Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD. |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages) { get; set; } | Obtiene o establece el número total de páginas de los datos de la capa de objeto inteligente en el archivo PSD. |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix) { get; set; } | Obtiene o establece la matriz de transformación de los datos de la capa de objeto inteligente en el archivo PSD. |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid) { get; set; } | Obtiene o establece el identificador único global de los datos de la capa de objeto inteligente[`SmartObjectResource`](../smartobjectresource) en la imagen PSD. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder) { get; set; } | Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value) { get; set; } | Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version) { get; } | Obtiene la versión de la capa colocada en el archivo PSD, generalmente 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints) { get; set; } | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit) { get; set; } | Obtiene o establece la unidad de medida de los puntos de malla vertical. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder) { get; set; } | Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD. |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width) { get; set; } | Obtiene o establece el ancho. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save)(StreamContainer, int) | Guarda el recurso de objeto inteligente en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey) | La clave de información de la herramienta tipo: 'Sold'. |

### Ejemplos

El siguiente código demuestra la compatibilidad con el recurso SoLdResource.

```csharp
[C#]

// Este ejemplo muestra cómo obtener o establecer las propiedades de datos de la capa de objeto inteligente del archivo PSD.

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

                // Estos valores también deben cambiarse en PlLdResource (con el UniqueId especificado)
                // y algunos de ellos deben estar de acuerdo con el objeto inteligente subrayado en LinkDataSource
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

                // Esta identificación única debe cambiarse en las referencias, si las hay
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // Tenga cuidado con algunos parámetros: la imagen puede volverse ilegible con Adobe® Photoshop®
                ////recurso.UOrder = 6;
                ////recurso.VOrden = 9;

                // No cambie esto, de lo contrario no podrá usar la transformación libre
                // o cambie el objeto inteligente subrayado al tipo de vector
                ////recurso.PlacedLayerType = PlacedLayerType.Vector;

                // Debería haber un PlLdResource válido con este ID único
                ////recurso.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### Ver también

* class [SmartObjectResource](../smartobjectresource)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->