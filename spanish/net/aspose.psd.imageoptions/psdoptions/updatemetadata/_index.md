---
title: "PsdOptions.UpdateMetadata"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PsdOptions. Obtiene o establece un valor que indica si se actualizan los metadatos. Si el valor es verdadero, los metadatos se actualizarán al guardar una imagen"
type: docs
weight: 110
url: /es/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Obtiene o establece un valor que indica si [update metadata]. Si el valor es verdadero, los metadatos se actualizarán al guardar una imagen.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` si [actualizar metadatos]; de lo contrario, `false`.

## Ejemplos

El siguiente código demuestra el uso de la opción UpdateMetadata para actualizar el valor CreatorTool en los datos xmp.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Si deseas que la herramienta creadora cambie, asegúrate de que la propiedad \"UpdateMetadata\" esté establecida en true. Está establecida en true por defecto.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Guardando la imagen. 
    image.Save(path, psdOptions);

    // Comprobando la herramienta creadora en el código.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Aquí se actualizará la información de la herramienta creadora.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Ver también

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


