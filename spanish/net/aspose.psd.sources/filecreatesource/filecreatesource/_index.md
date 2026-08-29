---
title: "FileCreateSource.FileCreateSource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor FileCreateSource. Inicializa una nueva instancia de la clase FileCreateSource"
type: docs
weight: 10
url: /es/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

Inicializa una nueva instancia de la clase [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo a crear. |

## Ejemplos

Este ejemplo crea un nuevo archivo Image en una ubicación de disco especificada por la propiedad Source de la instancia BmpOptions. Si no se pasa el segundo parámetro al constructor de FileCreateSource, entonces, por defecto, el archivo a crear tiene la propiedad IsTemporal establecida en True. Con IsTemporal establecida en True, no se guardará ningún archivo en disco al final de la ejecución.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Crea una instancia de PsdOptions y establece sus diversas propiedades.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Cree una instancia de FileCreateSource y asígnela como Source para la instancia de PsdOptions
//Si no se pasa el segundo parámetro, entonces, por defecto, el archivo tiene IsTemporal establecida en True.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Crea una instancia de Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //realiza algún procesamiento de imagen
}
```

### Ver también

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Inicializa una nueva instancia de la clase [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo a crear. |
| isTemporal | Boolean | Si se establece en `true`, el archivo creado será temporal. |

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

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


