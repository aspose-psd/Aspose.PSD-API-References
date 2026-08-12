---
title: "XmpBasicPackage.SetValue"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "XmpBasicPackage método. Establece el valor"
type: docs
weight: 120
url: /es/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Establece el valor.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | String | La representación en cadena de la clave que se identifica con el valor añadido. |
| valor | IXmlValue | El valor al que se añadirá. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


