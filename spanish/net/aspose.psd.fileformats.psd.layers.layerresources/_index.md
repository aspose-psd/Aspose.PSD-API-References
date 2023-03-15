---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Referencia de API de Aspose.PSD para .NET
description: El espacio de nombres contiene entidades de formato de archivo PSD contenidas en capas.
type: docs
weight: 270
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/
---
El espacio de nombres contiene entidades de formato de archivo PSD contenidas en capas.

## Clases

| Clase | Descripción |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | Clase base para recursos de capa de ajustes |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | La sección con datos animados. |
| [BlncResource](./blncresource/) | La clase BlncResource es un recurso de la capa de ajuste de color. |
| [BlwhResource](./blwhresource/) | La clase BlwhResource es un recurso de la capa de ajuste de blanco y negro. |
| [BooleanResource](./booleanresource/) | Clase BooleanResource. Es un pseudo recurso. Photoshop no lo tiene |
| [BritResource](./britresource/) | Clase BritResource. Recurso de ajuste de brillo/contraste Layer |
| [CgEdResource](./cgedresource/) | Clase CgEdResource. Datos adicionales del generador de contenido (Photoshop CS5) |
| [ClassID](./classid/) | El objeto de Id. de clase PSD. |
| [ClblResource](./clblresource/) | Class ClblResource. Este recurso contiene información sobre la combinación de elementos recortados. |
| [CmlsResource](./cmlsresource/) | Clase CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) tiene 6 gamas de colores donde puede cambiar los parámetros de HSV. Cada rango tiene 4 puntos clave para identificar los límites del rango. Y es ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Administrador de capa de ajuste de curvas que manipula curvas |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Administrador de la capa de ajuste de curvas que manipula el mapa de píxeles |
| [CurvesManager](./curvesmanager/) | Clase base para administrar CurvResource |
| [CurvResource](./curvresource/) | Clase CurvResource. Recurso de ajuste de curvas Capa 1 byte - 0 si usa curvas, 1 si usa píxeles en el mapa si es 0 entonces: 2 bytes - corto. El valor predeterminado es 1 4 bytes - int. Usado solo el último byte por bit. El primer bit es para 1 canal, el cuarto bit para 4 canales por ejemplo 2 bytes - recuento de puntos cortos 4 bytes * recuento de puntos - puntos de curva 2 cortos: primera posición, segunda altura 4 bytes - palabra "Crv " 2 bytes - corto predeterminado es 4 para Curves 4 bytes - int. El valor predeterminado es 1 4 bytes - recuento de puntos 4 bytes * recuento de puntos - puntos de la curva 2 cortos: primera posición, segunda altura 0-4 bytes - Previo a ser doblado por cuatro si 1 entonces: 2 bytes - corto. El valor predeterminado es 1 4 bytes - int. Usado solo el último byte. Un canal está en un bit. El primer bit es para 1 canal, el cuarto bit para 4 canales, por ejemplo 256 * recuento de canales cambiados - valores ordenados del canal en el rango 0 - 255 4 bytes - palabra "Crv " 2 bytes - corto. El valor predeterminado es 3 para píxeles en map 4 bytes - int Channel count (2 + 256) bytes - short 2 para índice de canal, 256 son valores ordenados del canal en el rango 0 - 255 |
| [CustResource](./custresource/) | Class CustResource. Este recurso contiene información sobre la combinación de elementos recortados. |
| [ExpaResource](./exparesource/) | Clase ExpaResource. Recurso de ajuste de exposición Layer |
| [FillLayerResource](./filllayerresource/) | Clase base para recursos de capa de relleno |
| [FilterEffectMaskData](./filtereffectmaskdata/) | La clase de datos de máscara de filtro. |
| [FXidResource](./fxidresource/) | El recurso Efectos de filtro contiene canales, una máscara de usuario y una máscara de hoja para el filtro inteligente. |
| [FxrpResource](./fxrpresource/) | Clase FxrpResource. El punto de referencia de layer |
| [GdFlResource](./gdflresource/) | Class GdFlResource. Este recurso contiene información sobre la combinación de elementos recortados. |
| [Hue2Resource](./hue2resource/) | Clase Hue2Resource. Recurso de ajuste de exposición Layer |
| [InfxResource](./infxresource/) | Class InfxResource. Este recurso contiene información sobre la combinación de elementos recortados. |
| [IopaResource](./ioparesource/) | Class IopaResource. Este recurso contiene información sobre la propiedad de opacidad de relleno del estilo de capa form |
| [KnkoResource](./knkoresource/) | Class KnkoResource. Este recurso contiene información sobre la combinación de elementos recortados. |
| [LayerSectionResource](./layersectionresource/) | El recurso de la sección de capa. |
| [LclrResource](./lclrresource/) | Class LclrResource. Este recurso contiene información sobre el color de la capa en la lista de capas es PS. Es solo |
| [LevelChannel](./levelchannel/) | Clase para trabajar con canales en Capa de Ajuste de Niveles |
| [LevlResource](./levlresource/) | Clase NivlRecurso. Recurso de ajuste de exposición Layer |
| [Lfx2Resource](./lfx2resource/) | recurso Lfx2 (recurso de efectos) |
| [LiFdDataSource](./lifddatasource/) | Define la clase de fuente de datos liFD en el archivo PSD que contiene información sobre un archivo incrustado. Esto es parte de la API de manipulación de formato de archivo PSD que ayuda a modificar los archivos de Adobe® Photoshop® |
| [LiFeDataSource](./lifedatasource/) | Define la clase LnkeDataSource que contiene información sobre el archivo vinculado externo. Esto es parte de la API de manipulación de formato de archivo PSD que ayuda a modificar los archivos de Adobe® Photoshop® |
| [LinkDataSource](./linkdatasource/) | Define la clase LinkDataSource que contiene información sobre un archivo vinculado o un activo en el archivo PSD. |
| [LinkResource](./linkresource/) | Define la clase LinkResource que contiene información sobre archivos vinculados o incrustados en la imagen en formato PSD. El recurso de vínculo puede contener varios[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) instancias a las que pueden acceder los indexadores en cualquier clase derivada. |
| [Lnk2Resource](./lnk2resource/) | Define la clase que contiene información sobre archivos incrustados en la imagen en formato PSD. El recurso de enlace puede contener varios[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instancias a las que puede acceder el indexador. |
| [Lnk3Resource](./lnk3resource/) | Define la clase que contiene información sobre un archivo incrustado en formato PSD de 32 bits por imagen de canal. El recurso de enlace puede contener varios[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instancias a las que puede acceder indexer. |
| [LnkeResource](./lnkeresource/) | Define la clase LnkeResource que contiene información sobre activos o archivos vinculados externos en la imagen en formato PSD. El recurso de vínculo puede contener varios[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instancias a las que puede acceder indexer. Esta es una parte de la API de manipulación de formato de archivo PSD que ayuda a modificar los archivos de Adobe® Photoshop® mediante programación |
| [LnsrResource](./lnsrresource/) | Clase lnsrResource. |
| [Lr16Resource](./lr16resource/) | El recurso lr32. |
| [Lr32Resource](./lr32resource/) | El recurso lr32. |
| [LspfResource](./lspfresource/) | Configuración de capa protegida |
| [LuniResource](./luniresource/) | Nombre de capa recurso |
| [LyidResource](./lyidresource/) | Clase LyidResource. |
| [MixrResource](./mixrresource/) | Clase MixrResource. Recurso de ajuste del mezclador de canales Layer |
| [MlstResource](./mlstresource/) | El recurso mlst. Esta clase, entre otras cosas, contiene información sobre la posición de la capa en la línea de tiempo. |
| [NvrtResource](./nvrtresource/) | Clase NvrtResource. Recurso de Invertir Capa de Ajuste. |
| [OSTypeStructure](./ostypestructure/) | Representa la estructura del tipo de SO. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | Representa el[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) registro de recursos. |
| [PattResource](./pattresource/) | Clase PattResource. Recurso con patrón data |
| [PattResourceData](./pattresourcedata/) | La clase para almacenar los datos de patrón para[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/) recurso. |
| [PhflResource](./phflresource/) | Clase PhflResource. Recurso de capa de ajuste de exposición 2 Versión ( = 3 ) o ( = 2 ) 12 4 bytes cada uno para el color XYZ (solo en la versión 3) 10 2 bytes de espacio de color seguido de 4 * 2 bytes de componente de color (solo en la versión 2) 4 Densidad 1 Conservar Luminosidad |
| [PhflResourceVersion2](./phflresourceversion2/) | Clase PhflResource. Recurso de capa de ajuste de exposición 2 Versión ( = 3 ) o ( = 2 ) 12 4 bytes cada uno para el color XYZ (solo en la versión 3) 10 2 bytes de espacio de color seguido de 4 * 2 bytes de componente de color (solo en la versión 2) 4 Densidad 1 Conservar Luminosidad |
| [PhflResourceVersion3](./phflresourceversion3/) | Clase PhflResource. Recurso de capa de ajuste de exposición 2 Versión ( = 3 ) o ( = 2 ) 12 4 bytes cada uno para el color XYZ (solo en la versión 3) 10 2 bytes de espacio de color seguido de 4 * 2 bytes de componente de color (solo en la versión 2) 4 Densidad 1 Conservar Luminosidad |
| [PlacedResource](./placedresource/) | Define la clase PlacedResource que contiene información común sobre una capa colocada o una capa de objeto inteligente en el archivo PSD. Se utiliza para admitir capas de objetos inteligentes en las imágenes de Adobe® Photoshop®. |
| [PlLdResource](./plldresource/) | Define la clase PlLdResource que contiene información sobre una capa colocada en el archivo PSD. Se utiliza para admitir capas de objetos inteligentes en las imágenes de Adobe® Photoshop®. Fue reemplazada por SoLdResource en Adobe® Photoshop® CS3 |
| [PostResource](./postresource/) | Clase PostResource. Ajustes de capa de posterización. |
| [PtFlResource](./ptflresource/) | Clase PtFlResource. Contiene datos de capa de relleno de patrón. |
| [ShmdResource](./shmdresource/) | Clase ShmdResource. Configuración de metadatos |
| [SmartObjectResource](./smartobjectresource/) | Define la clase SmartObjectResource que contiene información sobre una capa de objeto inteligente en un archivo PSD. Es la clase base para recursos Vendidos y Únicos que se utiliza para admitir capas de objetos inteligentes en las imágenes de Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator/) | Define la clase SmartResourceCreator que puede crear recursos PlLd, SoLd y SoLe. Se utiliza para admitir capas de objetos inteligentes en las imágenes de Adobe® Photoshop®. |
| [SoCoResource](./socoresource/) | Class SoCoResource. Este recurso contiene información sobre Color Fill Layers |
| [SoLdResource](./soldresource/) | Define la clase SoLdResource que contiene información sobre una capa de objeto inteligente en un archivo PSD. Se utiliza para admitir capas de objetos inteligentes en las imágenes de Adobe® Photoshop®. |
| [SoLeResource](./soleresource/) | Define la clase SoLeResource que contiene información sobre una capa de objetos inteligentes en un archivo PSD. Se utiliza para admitir capas de objetos inteligentes con enlaces de archivos externos en las imágenes de Adobe® Photoshop®. |
| [Txt2Resource](./txt2resource/) | clase de recurso Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo/) | Contiene información sobre la fuente de la herramienta de tipo. |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | La información de la herramienta de tipo. Para versión PSD superior o igual a la 6.0. |
| [TypeToolInfoResource](./typetoolinforesource/) | La información de la herramienta de tipo. Para la versión PSD inferior a 6.0. |
| [TypeToolLineInfo](./typetoollineinfo/) | Escriba información de línea de herramienta. |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | Escriba información de estilo de herramienta. |
| [UnknownResource](./unknownresource/) | El recurso desconocido. |
| [VectorPathDataResource](./vectorpathdataresource/) | Class VectorPathDataResource. Este recurso contiene información sobre la máscara de capa vectorial |
| [VibAResource](./vibaresource/) | Recurso VibA. |
| [VmskResource](./vmskresource/) | Class VmskResource. Este recurso contiene información sobre la máscara de capa vectorial |
| [VogkResource](./vogkresource/) | El recurso de datos de origen vectorial. |
| [VsmsResource](./vsmsresource/) | Class VsmsResource. Este recurso contiene información sobre la máscara de capa vectorial |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | El[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) cargador de recursos. |
| [IPlacedLayerResource](./iplacedlayerresource/) | Define la interfaz IPlacedLayerResource que contiene información sobre una capa colocada en el archivo PSD. Es una interfaz de marcado utilizada para designar recursos PlLd, Sold y Sole en las imágenes de Adobe® Photoshop®. Se utiliza para admitir capas de objetos inteligentes en las imágenes de Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | Define la interfaz ISmartObjectLayerResource que contiene información sobre un recurso de capa de objeto inteligente en el archivo PSD. También es una interfaz de marcado utilizada para designar recursos Vendidos y Únicos en las imágenes de Adobe® Photoshop®. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [LayerLockType](./layerlocktype/) | Opciones de bloqueo de capa |
| [LayerSectionSubtype](./layersectionsubtype/) | La sección subtipo |
| [LayerSectionType](./layersectiontype/) | La sección de capa type |
| [LinkDataSourceType](./linkdatasourcetype/) | Define la enumeración LinkDataSourceType para las fuentes de datos en el recurso de enlace PSD. |
| [LnsrResourceType](./lnsrresourcetype/) | Tipos de recurso Lnsr posibles descubiertos |
| [PlacedLayerType](./placedlayertype/) | Define la enumeración PlacedLayerType para el recurso PlLd de la capa colocada. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Colores posibles de la configuración de color de la hoja. Es el color decorativo de la interfaz de usuario de la capa en la lista de capas en PS |


