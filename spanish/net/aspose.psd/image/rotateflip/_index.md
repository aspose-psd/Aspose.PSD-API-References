---
title: "Image.RotateFlip"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Image. Gira, voltea o gira y voltea la imagen"
type: docs
weight: 230
url: /es/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Rota, voltea o rota y voltea la imagen.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Tipo de la rotación y volteo. |

## Ejemplos

Este ejemplo muestra el uso de la operación Rotate en una imagen. El ejemplo carga un archivo de imagen existente desde alguna ubicación del disco y realiza la operación Rotate en la imagen según el valor del Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Crear una instancia de la clase image e inicializarla con un archivo de imagen existente mediante la ruta del archivo
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Girar la imagen 180 grados alrededor del eje X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // Guarda todos los cambios.
    image.Save();
}
```

### Ver también

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


