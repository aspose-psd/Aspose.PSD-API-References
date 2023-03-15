---
title: Class LinkDataSource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource clase. Define la clase LinkDataSource que contiene información sobre un archivo vinculado o un activo en el archivo PSD.
type: docs
weight: 2690
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
## LinkDataSource class

Define la clase LinkDataSource que contiene información sobre un archivo vinculado o un activo en el archivo PSD.

```csharp
public abstract class LinkDataSource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Obtiene o establece un valor que indica si el recurso PSD está bloqueado. El estado de bloqueo del recurso, para los recursos de las bibliotecas de Adobe® Photoshop® СС. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Obtiene o establece la hora de modificación del recurso, para los recursos de las bibliotecas de Adobe® Photoshop® СС. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Obtiene o establece el identificador de documento secundario en la fuente de datos liFE o liFD del recurso Lnk2 / LnkE Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Obtiene o establece el ID de la composición actualmente seleccionada para el documento secundario, que será -1 si no se selecciona ninguna. Las composiciones son composiciones de un diseño de página que los diseñadores pueden crear. Con las composiciones de capas, puede crear, administrar y ver varias versiones de un diseño en un solo archivo de Adobe® Photoshop®. Una composición de capa es una instantánea de un estado del panel Capas. Las composiciones de capa guardan tres tipos de opciones de capa pero esta propiedad obtiene el identificador de selección de composición de capa para objetos inteligentes. [Composiciones de capas en objetos inteligentes](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Obtiene o establece el creador del archivo en formato PSD LnkE / Lnk2 resource. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Obtiene o establece el tipo de archivo incrustado o externo que contiene o vincula el recurso Adobe® Photoshop® Lnk2 / LnkE. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Obtiene o establece un valor que indica si esta fuente de datos de vínculo tiene el descriptor de apertura de archivo: CompId y OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Obtiene un valor que indica si esta fuente de datos de vínculo PSD se vincula con el elemento de la biblioteca de Adobe® Photoshop® СС. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Obtiene la longitud del origen de datos del vínculo en bytes. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Obtiene el ID original del Comp seleccionado actualmente para el documento secundario, que será -1 si no se selecciona ninguno. Esta propiedad obtiene el identificador de selección de Comp de capa original para objetos inteligentes. [Composiciones de capas en objetos inteligentes](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Obtiene el nombre de archivo original de la fuente de datos en el recurso de vínculo global de Adobe® Photoshop®. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Obtiene el tipo de fuente de datos de vínculo global de Adobe® Photoshop® que puede ser uno de los siguientes o ninguno: El archivo vinculado incrustado liFD que corresponde al PSD Lnk2Resource El archivo vinculado externo liFE que corresponde al PSD LnkeResource El archivo vinculado alias liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Obtiene el identificador único global de la fuente de datos en el recurso de enlace PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Obtiene la versión de la fuente de datos en el recurso PSD LnkE/Lnk2. |

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* asamblea [Aspose.PSD](../../)


