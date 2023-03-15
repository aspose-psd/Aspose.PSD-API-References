---
title: PsdImage.Rotate
second_title: Aspose.PSD per riferimento API .NET
description: PsdImage metodo. Ruota limmagine attorno al centro.
type: docs
weight: 610
url: /it/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Ruota l'immagine attorno al centro.

```csharp
public override void Rotate(float angle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | Single | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |

### Esempi

Il codice seguente dimostra la possibilità di ruotare l'immagine in base a un valore di angolo specifico.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotazione dell'intera immagine
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Strato rotante
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Guarda anche

* class [PsdImage](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assemblea [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Ruota l'immagine attorno al centro.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | Single | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | Boolean | se impostato su`VERO` le dimensioni dell'immagine verranno modificate in base alle proiezioni del rettangolo ruotato (punti d'angolo) in altri casi che lasciano intatte le dimensioni e vengono ruotati solo i contenuti interni dell'immagine. |
| backgroundColor | Color | Colore dello sfondo. |

### Guarda anche

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assemblea [Aspose.PSD](../../../)


