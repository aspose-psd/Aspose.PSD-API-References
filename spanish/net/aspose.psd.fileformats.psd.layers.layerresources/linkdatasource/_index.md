---
title: "Clase LinkDataSource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource. Define la clase LinkDataSource que contiene información sobre un archivo vinculado o un recurso en el archivo PSD."
type: docs
weight: 2990
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
{{< psd/tize >}}
## LinkDataSource class

Define la clase LinkDataSource que contiene información sobre un archivo vinculado o un recurso en el archivo PSD.

```csharp
public abstract class LinkDataSource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Obtiene o establece un valor que indica si el recurso PSD está bloqueado. El estado bloqueado del recurso, para los recursos de Adobe® Photoshop® СС Libraries. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Obtiene o establece la hora de modificación del recurso, para los recursos de Adobe® Photoshop® СС Libraries. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Obtiene o establece el identificador del documento hijo en la fuente de datos liFE o liFD del recurso Lnk2 / LnkE de Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Obtiene o establece el ID de la composición (comp) actualmente seleccionada para el documento hijo, que será -1 si no hay ninguna seleccionada. Las composiciones son combinaciones de un diseño de página que los diseñadores pueden crear. Usando composiciones de capas, puedes crear, gestionar y ver múltiples versiones de un diseño en un solo archivo de Adobe® Photoshop®. Una composición de capa es una captura instantánea del estado del panel Capas. Las composiciones de capa guardan tres tipos de opciones de capa pero esta propiedad obtiene el identificador de selección de la composición de capa para objetos inteligentes. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Obtiene o establece el creador del archivo en el recurso de formato PSD LnkE / Lnk2. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Obtiene o establece el tipo del archivo incrustado o externo que el recurso Adobe® Photoshop® Lnk2 / LnkE contiene o enlaza. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Obtiene o establece un valor que indica si esta fuente de datos de enlace tiene el descriptor de archivo abierto: CompId y OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Obtiene un valor que indica si esta fuente de datos de enlace PSD enlaza al elemento de la Biblioteca Adobe® Photoshop® СС. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Obtiene la longitud de la fuente de datos de enlace en bytes. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Obtiene el ID original de la Comp (composición) actualmente seleccionada para el documento hijo, que será -1 si no hay ninguna seleccionada. Esta propiedad obtiene el identificador de selección de la composición de capa original para objetos inteligentes. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Obtiene el nombre de archivo original de la fuente de datos en el recurso de enlace global de Adobe® Photoshop®. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Obtiene el tipo de fuente de datos de enlace global de Adobe® Photoshop® que puede ser uno de los siguientes o ninguno: el archivo enlazado incrustado liFD que corresponde al recurso PSD Lnk2, el archivo enlazado externo liFE que corresponde al recurso PSD Lnke, el alias de archivo enlazado liFA. |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Obtiene el identificador único global de la fuente de datos en el recurso de enlace PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Obtiene la versión de la fuente de datos en el recurso PSD LnkE / Lnk2. |

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


