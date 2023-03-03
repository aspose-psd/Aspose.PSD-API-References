---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD per riferimento API .NET
description: PsdImage proprietà. Ottiene o imposta langolo globale.
type: docs
weight: 100
url: /it/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Ottiene o imposta l'angolo globale.

```csharp
public int GlobalAngle { get; set; }
```

### Esempi

Il codice seguente illustra il supporto per la proprietà PsdImage.GlobalAngle per modificare il valore dell'angolo globale.

```csharp
[C#]

// Quando la proprietà DropShadowEffect.UseGlobalLight è 'true', l'oggetto DropShadowEffect utilizza il valore dell'angolo dalla proprietà PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Guarda anche

* class [PsdImage](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* assemblea [Aspose.PSD](../../../)


