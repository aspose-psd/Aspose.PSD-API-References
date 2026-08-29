---
title: "Image.RotateFlip"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Image-Methode. Dreht, spiegelt oder dreht und spiegelt das Bild."
type: docs
weight: 230
url: /de/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Dreht, spiegelt oder dreht und spiegelt das Bild.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Typ des RotateFlip. |

## Beispiele

Dieses Beispiel demonstriert die Verwendung der Rotate-Operation auf einem Bild. Das Beispiel lädt eine vorhandene Bilddatei von einem Speicherort und führt die Rotate-Operation auf dem Bild aus, basierend auf dem Wert des Enums Aspose.PSD.RotateFlipType

```csharp
[C#]

//Erstelle eine Instanz der Image-Klasse und initialisiere sie mit einer vorhandenen Bilddatei über den Dateipfad.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Drehe das Bild um 180 Grad um die X-Achse.
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // Speichere alle Änderungen.
    image.Save();
}
```

### Siehe auch

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


