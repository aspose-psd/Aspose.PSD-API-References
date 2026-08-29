---
title: "Image.Create"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Image. Crea una nueva imagen usando las opciones de creación especificadas"
type: docs
weight: 10
url: /es/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Crea una nueva imagen usando las opciones de creación especificadas.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Las opciones de imagen. |
| width | Int32 | El ancho. |
| height | Int32 | El alto. |

### Valor devuelto

La imagen recién creada.

## Ejemplos

Este ejemplo crea un nuevo archivo Image en una ubicación de disco especificada por la propiedad Source de la instancia PsdOptions. Se establecen varias propiedades de la instancia PsdOptions antes de crear la imagen real. Especialmente la propiedad Source, que en este caso se refiere a la ubicación real del disco.

```csharp
[C#]

//Cree una instancia de PsdOptions y establezca sus diversas propiedades
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Cree una instancia de FileCreateSource y asígnela como Source para la instancia de PsdOptions
//El segundo parámetro Boolean determina si el archivo a crear es Temporal o no
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Cree una instancia de Image e inicialícela con una instancia de PsdOptions llamando al método Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //realiza algún procesamiento de imagen

    // guarde todos los cambios
    image.Save();
}
```

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


