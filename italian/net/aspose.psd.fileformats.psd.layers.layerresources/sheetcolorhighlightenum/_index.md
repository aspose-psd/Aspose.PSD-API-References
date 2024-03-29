---
title: Enum SheetColorHighlightEnum
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum enum. Possibili colori dellimpostazione del colore del foglio. È il colore decorativo dellinterfaccia utente del livello nellelenco dei livelli in PS
type: docs
weight: 2970
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

Possibili colori dell'impostazione del colore del foglio. È il colore decorativo dell'interfaccia utente del livello nell'elenco dei livelli in PS

```csharp
public enum SheetColorHighlightEnum : short
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NoColor | `0` | Il colore non è specificato. |
| Red | `1` | Il colore rosso. |
| Orange | `2` | Il colore arancione. |
| Yellow | `3` | Il colore giallo. |
| Green | `4` | Il colore verde. |
| Blue | `5` | Il colore blu. |
| Violet | `6` | Il colore viola. |
| Gray | `7` | Il colore grigio. |

### Esempi

L'esempio seguente mostra come modificare l'evidenziazione del colore del foglio in Aspose.PSD (impostazione del colore del foglio)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Nel file i colori dell'evidenziazione dei livelli sono in questo ordine
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// Layer Sheet Color viene utilizzato per evidenziare visivamente i layer. 
// Ad esempio puoi aggiornare alcuni livelli in PSD e quindi evidenziare per colore il livello che desideri attirare l'attenzione.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // I colori dovrebbero essere invertiti
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // La risorsa lcrl è sempre presente nell'elenco delle risorse del file psd.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Inversione dei colori del foglio di stile. Impostazione dell'evidenziazione del colore del livello.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assemblea [Aspose.PSD](../../)


