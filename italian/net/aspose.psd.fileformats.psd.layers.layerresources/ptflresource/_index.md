---
title: PtFlResource
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Classe PtFlResource. Contiene i dati del livello di riempimento pattern.
type: docs
weight: 2930
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
## PtFlResource class

Classe PtFlResource. Contiene i dati del livello di riempimento pattern.

```csharp
public class PtFlResource : FillLayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PtFlResource](ptflresource)(string, string) | Inizializza una nuova istanza di[`PtFlResource`](../ptflresource) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer) { get; set; } | Ottiene o imposta un valore che indica se [align with layer]. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer) { get; set; } | Ottiene o imposta un valore che indica se questa istanza è collegata al livello. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/key) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset) { get; set; } | Ottiene o imposta l'offset. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid) { get; set; } | Ottiene o imposta l'identificatore del modello. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname) { get; set; } | Ottiene o imposta il nome del pattern. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/psdversion) { get; } | Ottiene la versione psd minima richiesta per la risorsa di livello. 0 indica nessuna restrizione. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale) { get; set; } | Ottiene o imposta la scala. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/signature) { get; } | Ottiene la firma della risorsa del livello. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save)(StreamContainer, int) | Salva la risorsa nel contenitore del flusso specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey) | Il tipo di chiave info strumento. |

### Esempi

Nell'esempio seguente viene illustrato il supporto del caricamento e della modifica di una risorsa PtFlResource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // Lettura
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // La modifica
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // Non abbiamo dati di pattern in PattResource, quindi possiamo aggiungerli.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### Guarda anche

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* class [FillLayerResource](../filllayerresource)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
