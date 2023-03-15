---
title: TextLayer.Resize
second_title: Aspose.PSD per riferimento API .NET
description: TextLayer metodo. Ridimensiona limmagine. Il predefinitoLeftTopToLeftTopviene utilizzato.
type: docs
weight: 90
url: /it/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| resizeType | ResizeType | Il tipo di trasformazione di ridimensionamento[`ResizeType`](../../../aspose.psd/resizetype/) |

### Esempi

Il codice seguente mostra la funzione TextLayer.Resize con il parametro per scegliere il meccanismo di ridimensionamento.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Imposta la nuova dimensione del livello di testo
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Imposta il meccanismo per il modo in cui la funzione di ridimensionamento ridimensionerà il livello (valore predefinito)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Nuovo meccanismo di ridimensionamento per il livello di testo usando qui
    // Non solo il livello ma anche la matrice di trasformazione del livello di testo verrà modificata
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Il motivo del delta è un carattere predefinito diverso
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Va tutto bene
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Guarda anche

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* assemblea [Aspose.PSD](../../../)


