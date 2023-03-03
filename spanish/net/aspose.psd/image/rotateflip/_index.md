---
title: Image.RotateFlip
second_title: Referencia de API de Aspose.PSD para .NET
description: Image método. Gira voltea o gira y voltea la imagen.
type: docs
weight: 220
url: /es/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

Gira, voltea o gira y voltea la imagen.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Tipo de rotación flip. |

### Ejemplos

Este ejemplo demuestra el uso de la operación Rotar en una imagen. El ejemplo carga un archivo de imagen existente desde alguna ubicación del disco y realiza la operación Rotar en la imagen de acuerdo con el valor de Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Cree una instancia de clase de imagen e inicialícela con un archivo de imagen existente a través de la ruta del archivo
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Rotar la imagen 180 grados sobre el eje X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // guarda todos los cambios.
    image.Save();
}
```

### Ver también

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* espacio de nombres [Aspose.PSD](../../image/)
* asamblea [Aspose.PSD](../../../)


