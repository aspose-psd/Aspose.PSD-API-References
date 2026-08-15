---
title: "Clase LinkDataSource"
type: docs
weight: 530
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---

**Summary:** Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | Obtiene o establece un valor que indica si el activo PSD está bloqueado.<br/>            El estado de bloqueo del activo, para los activos de Bibliotecas Adobe® Photoshop® СС. |
| asset_mod_time | double | r/w | Obtiene o establece la hora de modificación del activo, para los activos de las Bibliotecas СС de Adobe® Photoshop®. |
| child_doc_id | string | r/w | Obtiene o establece el identificador del documento hijo en la fuente de datos liFE o liFD del recurso Lnk2 / LnkE de Adobe® Photoshop®. |
| comp_id | int | r/w | Obtiene o establece el ID del comp seleccionado actualmente para el documento hijo, que será -1 si no hay ninguno seleccionado.<br/>            Los comps son composiciones de un diseño de página que los diseñadores pueden crear. Usando comps de capa, puedes crear, gestionar y ver múltiples versiones<br/>            de un diseño en un solo archivo de Adobe® Photoshop®. Un comp de capa es una captura de estado del panel Capas. Los comps de capa guardan tres tipos de opciones de capa pero<br/>            esta propiedad obtiene el identificador de selección del Comp de Capa para Objetos Inteligentes.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| file_creator | string | r/w | Obtiene o establece el creador del archivo en el recurso de formato PSD LnkE / Lnk2. |
| file_type | string | r/w | Obtiene o establece el tipo del archivo incrustado o externo que el recurso Adobe® Photoshop® Lnk2 / LnkE contiene o enlaza. |
| has_file_open_descriptor | bool | r/w | Obtiene o establece un valor que indica si esta fuente de datos de enlace tiene el descriptor de archivo abierto: CompId y OriginalCompId. |
| is_library_link | bool | r | Obtiene un valor que indica si esta fuente de datos de enlace PSD enlaza al elemento de la Biblioteca СС de Adobe® Photoshop®. |
| longitud | long | r | Obtiene la longitud del origen de datos del enlace en bytes. |
| original_comp_id | int | r | Obtiene el ID original del Comp actualmente seleccionado para el documento hijo, que será -1 si no hay ninguno seleccionado.<br/>            Esta propiedad obtiene el identificador de selección del Comp de capa original para Objetos Inteligentes.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Capas comp en Objetos Inteligentes</see> |
| original_file_name | string | r | Obtiene el nombre de archivo original del origen de datos en el recurso de enlace global de Adobe® Photoshop®. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Obtiene el tipo de origen de datos de enlace global de Adobe® Photoshop® que puede ser uno de los siguientes o ninguno:<br/>            El archivo enlazado incrustado liFD que corresponde al recurso PSD Lnk2Resource<br/>            El archivo enlazado externo liFE que corresponde al recurso PSD LnkeResource<br/>            El alias de archivo enlazado liFA |
| unique_id | Guid | r | Obtiene el identificador único global del origen de datos en el recurso de enlace PSD. |
| version | int | r | Obtiene la versión del origen de datos en el recurso PSD LnkE / Lnk2. |


