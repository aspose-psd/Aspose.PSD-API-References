---
title: Image.RotateFlip
second_title: Aspose.PSD für .NET-API-Referenz
description: Image methode. Dreht kippt oder dreht und kippt das Bild.
type: docs
weight: 220
url: /de/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

Dreht, kippt oder dreht und kippt das Bild.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Typ des Rotierens Flip. |

### Beispiele

Dieses Beispiel demonstriert die Verwendung des Rotate-Vorgangs an einem Bild. Beispiel lädt eine vorhandene Bilddatei von einem Speicherort auf der Festplatte und führt den Rotate-Vorgang für das Bild gemäß dem Wert von Enum Aspose.PSD.RotateFlipType aus

```csharp
[C#]

//Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Bilddatei über den Dateipfad
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Drehen Sie das Bild um 180 Grad um die X-Achse
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // Alle Änderungen speichern.
    image.Save();
}
```

### Siehe auch

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)


