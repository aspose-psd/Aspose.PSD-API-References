---
title: "XmpBasicPackage.ContainsKey"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "XmpBasicPackage método. Determina si la clave especificada contiene la clave"
type: docs
weight: 40
url: /es/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

Determina si la clave especificada contiene la clave.

```csharp
public override bool ContainsKey(string key)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | String | La clave a comprobar. |

### Valor devuelto

Devuelve true si la clave especificada contiene la clave.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


