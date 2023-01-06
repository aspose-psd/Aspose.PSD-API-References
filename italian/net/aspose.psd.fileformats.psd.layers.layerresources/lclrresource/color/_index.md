---
title: Color
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Ottiene o imposta il colore del livello.
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

Ottiene o imposta il colore del livello.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Valore della proprietà

Il colore.

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

// Il colore del foglio di livello viene utilizzato per evidenziare visivamente i livelli. 
// Ad esempio puoi aggiornare alcuni livelli in PSD e poi evidenziare per colore il livello che vuoi attirare l'attenzione.
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
            // La risorsa lcrl si presenta sempre nell'elenco delle risorse del file psd.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Rovescio dei colori dei fogli di stile. Impostazione dell'evidenziazione del colore del livello.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Guarda anche

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum)
* class [LclrResource](../../lclrresource)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->