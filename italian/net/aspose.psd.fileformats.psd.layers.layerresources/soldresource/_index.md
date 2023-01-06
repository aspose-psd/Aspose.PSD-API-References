---
title: SoLdResource
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Definisce la classe SoLdResource che contiene informazioni su un livello di oggetti intelligenti in un file PSD. Viene utilizzato per supportare i livelli di oggetti intelligenti nelle immagini di Adobe Photoshop.
type: docs
weight: 2990
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
## SoLdResource class

Definisce la classe SoLdResource che contiene informazioni su un livello di oggetti intelligenti in un file PSD. Viene utilizzato per supportare i livelli di oggetti intelligenti nelle immagini di Adobe® Photoshop®.

```csharp
public class SoLdResource : SmartObjectResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SoLdResource](soldresource#constructor)() | Inizializza una nuova istanza di[`SoLdResource`](../soldresource) class. Questo costruttore predefinito è progettato per essere utilizzato daSoLdResourceLoader . Usa[`SmartResourceCreator`](../smartresourcecreator) per la creazione di classi SoLdResource. |
| [SoLdResource](soldresource#constructor_1)(Guid, bool, bool) | Inizializza una nuova istanza di[`SoLdResource`](../soldresource) class. È necessario impostare la proprietà Items o chiamare InitializeItems() per ottenere un'istanza pronta. Questo costruttore è progettato per essere utilizzato da[`SmartResourceCreator`](../smartresourcecreator) e negli unit test. Utilizzare[`SmartResourceCreator`](../smartresourcecreator) per la creazione di classi SoLdResource. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy) { get; set; } | Ottiene o imposta la politica anti alias dei dati del livello oggetto intelligente nell'immagine PSD. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom) { get; set; } | Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds) { get; set; } | Ottiene o imposta i limiti del livello posizionato nel file PSD. |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp) { get; set; } | Ottiene o imposta il valore comp dei dati del livello oggetto intelligente nel file PSD. [Composizioni di livello in Oggetti avanzati](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid) { get; set; } | Ottiene o imposta l'ID della composizione attualmente selezionata per il documento figlio, che sarà -1 se non ne è selezionato nessuno. Le composizioni sono composizioni di un layout di pagina che i designer possono creare. Utilizzando le composizioni di livelli, potete creare, gestire e visualizzare più versioni di un layout in un unico file Adobe® Photoshop®. Una composizione di livelli è un'istantanea di uno stato del pannello Livelli. Le composizioni livelli salvano tre tipi di opzioni di livello ma questa proprietà ottiene l'identificatore di selezione della composizione livelli per il livello oggetto intelligente nel file PSD. [Composizioni di livello in Oggetti avanzati](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop) { get; set; } | Ottiene o imposta il ritaglio dei dati del livello oggetto intelligente nell'immagine PSD. |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator) { get; set; } | Ottiene o imposta il denominatore della durata. |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator) { get; set; } | Ottiene o imposta il numeratore della durata. |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount) { get; set; } | Ottiene o imposta il conteggio dei fotogrammi dei dati del livello oggetto intelligente nel file PSD. |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator) { get; set; } | Ottiene o imposta il denominatore del passo del frame. |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator) { get; set; } | Ottiene o imposta il numeratore del passo del fotogramma. |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height) { get; set; } | Ottiene o imposta l'altezza. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints) { get; set; } | Ottiene o imposta i punti della mesh orizzontale del livello posizionato nel file PSD. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit) { get; set; } | Ottiene o imposta l'unità di misura dei punti mesh orizzontali. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom) { get; set; } | Ottiene o imposta un valore che indica se questo stile di warp dell'istanza è personalizzato. Se true contiene punti mesh. Se impostato su false cancella i punti della mesh. |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items) { get; set; } | Ottiene o imposta gli elementi del descrittore dei dati del livello oggetto intelligente nel file PSD. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/key) { get; } | Ottiene la chiave della risorsa del livello di oggetti intelligenti SoLd. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left) { get; set; } | Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length) { get; } | Ottiene la lunghezza della risorsa dell'oggetto intelligente in byte. |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix) { get; set; } | Ottiene o imposta la matrice di trasformazione non affine dei dati del livello oggetto intelligente nel file PSD. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid) { get; } | Ottiene l'ID originale della Comp attualmente selezionata per il documento figlio, che sarà -1 se non ne è selezionato nessuno. Questa proprietà ottiene l'identificatore di selezione della composizione del livello originale per il livello dell'oggetto intelligente nel file PSD. [Composizioni di livello in Oggetti avanzati](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber) { get; set; } | Ottiene o imposta il numero di pagina dei dati del livello oggetto intelligente nel file PSD. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective) { get; set; } | Ottiene o imposta il valore prospettico del livello posizionato nel file PSD. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother) { get; set; } | Ottiene o imposta la prospettiva altro valore del livello posizionato nel file PSD. |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid) { get; set; } | Ottiene o imposta l'identificatore univoco dei dati di questo livello di oggetti intelligenti nell'immagine PSD. |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype) { get; set; } | Ottiene o imposta il tipo di dati del livello oggetto intelligente nel file PSD. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/psdversion) { get; } | Ottiene la versione psd minima richiesta per la risorsa oggetto intelligente. 0 indica nessuna restrizione. |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution) { get; set; } | Ottiene o imposta la risoluzione dei dati del livello oggetto intelligente nel file PSD. |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit) { get; set; } | Ottiene o imposta l'unità di misura della risoluzione dei dati del livello oggetto intelligente nel file PSD. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right) { get; set; } | Ottiene o imposta la posizione corretta del livello posizionato nel file PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/signature) { get; } | Ottiene la firma della risorsa dell'oggetto intelligente. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top) { get; set; } | Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD. |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages) { get; set; } | Ottiene o imposta il numero totale di pagine dei dati del livello oggetto intelligente nel file PSD. |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix) { get; set; } | Ottiene o imposta la matrice di trasformazione dei dati del livello oggetto intelligente nel file PSD. |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid) { get; set; } | Ottiene o imposta l'identificatore univoco globale dei dati del livello dell'oggetto intelligente[`SmartObjectResource`](../smartobjectresource) nell'immagine PSD. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder) { get; set; } | Ottiene o imposta il valore dell'ordine U del livello inserito nel file PSD. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value) { get; set; } | Ottiene o imposta il valore di warp del livello posizionato nell'immagine PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version) { get; } | Ottiene la versione del livello inserito nel file PSD, in genere 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints) { get; set; } | Ottiene o imposta i punti della mesh orizzontale del livello posizionato nel file PSD. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit) { get; set; } | Ottiene o imposta l'unità di misura dei punti della mesh verticale. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder) { get; set; } | Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD. |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width) { get; set; } | Ottiene o imposta la larghezza. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save)(StreamContainer, int) | Salva la risorsa dell'oggetto intelligente nel contenitore del flusso specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey) | Il tipo di chiave info strumento: 'SoLd'. |

### Esempi

Il codice seguente illustra il supporto della risorsa SoLdResource.

```csharp
[C#]

// Questo esempio mostra come ottenere o impostare le proprietà dei dati del livello degli oggetti intelligenti del file PSD.

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

                // Questi valori devono essere modificati anche in PlLdResource (con il UniqueId specificato).
                // e alcuni di essi devono essere in accordo con l'oggetto smart sottolineato nel LinkDataSource
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

                // Questo ID univoco dovrebbe essere modificato nei riferimenti, se presenti
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // Fai attenzione con alcuni parametri: l'immagine potrebbe diventare illeggibile da Adobe® Photoshop®
                ////risorsa.UOrdine = 6;
                ////risorsa.VOrder = 9;

                // Non modificarlo altrimenti non sarai in grado di utilizzare la trasformazione gratuita
                // o cambia l'oggetto intelligente sottolineato nel tipo vettoriale
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // Dovrebbe esserci PlLdResource valido con questo ID univoco
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### Guarda anche

* class [SmartObjectResource](../smartobjectresource)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
