---
title: "SoLeResource"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define la clase SoLeResource que contiene información sobre una capa de objeto inteligente en un archivo PSD."
type: docs
weight: 16
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
```
public class SoLeResource extends SmartObjectResource
```

Define la clase SoLeResource que contiene información sobre una capa de objeto inteligente en un archivo PSD. Se utiliza para admitir capas de objeto inteligente con enlaces a archivos externos en las imágenes Adobe\ufffd Photoshop\ufffd.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)](#SoLeResource-java.util.UUID-boolean-boolean-) | Inicializa una nueva instancia de la clase [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource). |
| [SoLeResource()](#SoLeResource--) | Inicializa una nueva instancia de la clase [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource). |
## Campos

| Campo | Descripción |
| --- | --- |
| [AntiAliasPolicyKey_internalized](#AntiAliasPolicyKey-internalized) | La clave de la política de antialias |
| [BottomKey_internalized](#BottomKey-internalized) | La clave inferior. |
| [BoundsKey_internalized](#BoundsKey-internalized) | La clave de los límites |
| [CompIdKey_internalized](#CompIdKey-internalized) | El nombre de la clave de CompID |
| [CompInfoKey_internalized](#CompInfoKey-internalized) | El nombre de la clave de información de comp |
| [CompKey_internalized](#CompKey-internalized) | La clave de comp |
| [CompNoneValue_internalized](#CompNoneValue-internalized) | El valor de comp que significa 'none' |
| [CropKey_internalized](#CropKey-internalized) | La clave de recorte |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | El nombre de la deformación de sobre personalizada |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | El nombre de la clase de deformación predeterminada |
| [DenominatorKey_internalized](#DenominatorKey-internalized) | La clave del denominador |
| [DurationKey_internalized](#DurationKey-internalized) | La clave de duración |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | El nombre de la clase de deformación predeterminada |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | La versión esperada del descriptor de deformación |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | La versión esperada de la deformación |
| [FrameCountKey_internalized](#FrameCountKey-internalized) | La clave de recuento de fotogramas |
| [FrameStepKey_internalized](#FrameStepKey-internalized) | La clave de paso de fotogramas |
| [HeightKey_internalized](#HeightKey-internalized) | La clave de altura |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | El nombre del identificador horizontal |
| [IdentKey_internalized](#IdentKey-internalized) | La clave de identificador único |
| [ItemsPropertyCannotBeNull_internalized](#ItemsPropertyCannotBeNull-internalized) | La propiedad items no puede ser nula |
| [LeftKey_internalized](#LeftKey-internalized) | La clave izquierda. |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | El nombre de la clave de puntos de malla |
| [NonAffineTransformKey_internalized](#NonAffineTransformKey-internalized) | La clave de transformación no afín |
| [NullClassId_internalized](#NullClassId-internalized) | El identificador de clase nula |
| [NumeratorKey_internalized](#NumeratorKey-internalized) | La clave del numerador |
| [OptionalKeys_internalized](#OptionalKeys-internalized) | La colección de claves opcionales |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | El nombre del identificador de orientación |
| [OriginalCompIdKey_internalized](#OriginalCompIdKey-internalized) | El nombre de la clave del CompID original |
| [PageNumberKey_internalized](#PageNumberKey-internalized) | La clave del número de página |
| [PlacedIdKey_internalized](#PlacedIdKey-internalized) | La clave del identificador colocado |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | El valor de versión esperado |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versión del encabezado PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma de recurso específica de PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versión del encabezado PSD |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | El nombre del identificador de la clase de punto racional |
| [ResolutionKey_internalized](#ResolutionKey-internalized) | La clave de resolución |
| [ResourceSignature](#ResourceSignature) | La firma de recurso común. |
| [RightKey_internalized](#RightKey-internalized) | La clave derecha. |
| [SizeKey_internalized](#SizeKey-internalized) | La clave de tamaño |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | El tamaño de double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | El tamaño de int |
| [SmartVersionValue_internalized](#SmartVersionValue-internalized) | El valor esperado de la versión del recurso del objeto inteligente. |
| [TopKey_internalized](#TopKey-internalized) | La clave superior. |
| [TotalPagesKey_internalized](#TotalPagesKey-internalized) | La clave del total de páginas |
| [TransformKey_internalized](#TransformKey-internalized) | La clave de transformación |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | El recuento de valores de transformación |
| [TypeKey_internalized](#TypeKey-internalized) | La clave de tipo |
| [TypeToolKey](#TypeToolKey) | La clave de información de la herramienta de tipo: 'SoLE'. |
| [TypeValue_internalized](#TypeValue-internalized) | El valor de tipo esperado. |
| [UOrderKey_internalized](#UOrderKey-internalized) | La clave de orden u |
| [VOrderKey_internalized](#VOrderKey-internalized) | La clave de orden v |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | El nombre del identificador vertical |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | El nombre personalizado de deformación |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | La longitud del encabezado de deformación. |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | La longitud del encabezado de deformación. |
| [WarpKey_internalized](#WarpKey-internalized) | La clave de deformación. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | El nombre de deformación ninguno |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | La clave de perspectiva de deformación |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | El otro de perspectiva de deformación |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | La clave de rotación de deformación |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | La clave de estilo de deformación |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | La clave de valor de deformación |
| [WidthKey_internalized](#WidthKey-internalized) | La clave de ancho |
| [YouCannotAccessCropPropertyMessage_internalized](#YouCannotAccessCropPropertyMessage-internalized) | No puede acceder a la propiedad Crop mensaje |
| [YouCannotSetCompIdPropertyMessage_internalized](#YouCannotSetCompIdPropertyMessage-internalized) | No puede establecer la propiedad CompId mensaje |
| [YouCannotSetCompPropertyMessage_internalized](#YouCannotSetCompPropertyMessage-internalized) | No puede establecer la propiedad Comp mensaje |
| [YouCannotSetOriginalCompIdPropertyMessage_internalized](#YouCannotSetOriginalCompIdPropertyMessage-internalized) | No puede establecer la propiedad OriginalCompId mensaje |
| [ZeroChar_internalized](#ZeroChar-internalized) | El carácter cero. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licencia venture. |
## Métodos

| Método | Descripción |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Asegura que el valor real especificado sea igual al valor esperado. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Comprueba y establece si el recurso es específico de PSB. |
| [convertListStructureToDoubleArray_internalized(ListStructure list)](#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-) | Convierte la estructura de lista a una matriz de dobles. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Obtiene o establece la política de antialias de los datos de capa del objeto inteligente en la imagen PSD. |
| [getBottom()](#getBottom--) | Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD. |
| [getBounds()](#getBounds--) | Obtiene o establece los límites de la capa colocada en el archivo PSD. |
| [getClass()](#getClass--) |  |
| [getComp()](#getComp--) | Obtiene o establece el valor comp de los datos de capa del objeto inteligente en el archivo PSD. |
| [getCompId()](#getCompId--) | Obtiene o establece el ID del comp seleccionado actualmente para el documento hijo, que será -1 si no se selecciona ninguno. |
| [getCrop()](#getCrop--) | Obtiene o establece el recorte de los datos de capa del objeto inteligente en la imagen PSD. |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Obtiene o establece el tipo de unidad predeterminado para los valores asignados como Izquierda, Superior, Derecha, Inferior, TransformMatrix. |
| [getDurationDenominator()](#getDurationDenominator--) | Obtiene o establece el denominador de la duración. |
| [getDurationNumerator()](#getDurationNumerator--) | Obtiene o establece el numerador de la duración. |
| [getFrameCount()](#getFrameCount--) | Obtiene o establece el recuento de fotogramas de los datos de capa del objeto inteligente en el archivo PSD. |
| [getFrameStepDenominator()](#getFrameStepDenominator--) | Obtiene o establece el denominador del paso de fotograma. |
| [getFrameStepNumerator()](#getFrameStepNumerator--) | Obtiene o establece el numerador del paso de fotograma. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getHeight()](#getHeight--) | Obtiene o establece la altura. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Obtiene o establece la unidad de medida de los puntos de malla horizontal. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [getItems()](#getItems--) | Obtiene o establece los elementos del descriptor de los datos de capa del objeto inteligente en el archivo PSD. |
| [getKey()](#getKey--) | Obtiene la clave del recurso de capa. |
| [getLeft()](#getLeft--) | Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD. |
| [getLength()](#getLength--) | Obtiene la longitud del recurso de objeto inteligente en bytes. |
| [getNonAffineTransformMatrix()](#getNonAffineTransformMatrix--) | Obtiene o establece la matriz de transformación no afín de los datos de capa de objeto inteligente en el archivo PSD. |
| [getOriginalCompId()](#getOriginalCompId--) | Obtiene el ID original del Comp seleccionado actualmente para el documento hijo, que será -1 si no se selecciona ninguno. |
| [getPageNumber()](#getPageNumber--) | Obtiene o establece el número de página de los datos de capa de objeto inteligente en el archivo PSD. |
| [getPerspective()](#getPerspective--) | Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD. |
| [getPlacedId()](#getPlacedId--) | Obtiene o establece el identificador único de estos datos de capa de objeto inteligente en la imagen PSD. |
| [getPlacedId_internalized()](#getPlacedId-internalized--) |  |
| [getPlacedLayerType()](#getPlacedLayerType--) | Obtiene o establece el tipo de los datos de capa de objeto inteligente en el archivo PSD. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtiene la longitud del prefijo. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión mínima de PSD requerida para el recurso de capa. |
| [getResolution()](#getResolution--) | Obtiene o establece la resolución de los datos de capa de objeto inteligente en el archivo PSD. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtiene o establece la unidad de medida de resolución de los datos de capa de objeto inteligente en el archivo PSD. |
| [getRight()](#getRight--) | Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD. |
| [getSignature()](#getSignature--) | Obtiene la firma del recurso de capa. |
| [getTop()](#getTop--) | Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD. |
| [getTotalPages()](#getTotalPages--) | Obtiene o establece el número total de páginas de los datos de capa de objeto inteligente en el archivo PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Obtiene o establece la matriz de transformación de los datos de capa de objeto inteligente en el archivo PSD. |
| [getUOrder()](#getUOrder--) | Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD. |
| [getUniqueId()](#getUniqueId--) | Obtiene o establece el identificador único global de los datos de capa de objeto inteligente [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) en la imagen PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD. |
| [getValue()](#getValue--) | Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD. |
| [getVersion()](#getVersion--) | Obtiene la versión de la capa colocada en el archivo PSD, normalmente 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Obtiene o establece la unidad de medida de los puntos de malla vertical. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Obtiene o establece el ID de clase. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Obtiene o establece el nombre de clase de deformación. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Obtiene o establece la versión del descriptor de deformación. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Los elementos de deformación. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Obtiene o establece la versión de deformación. |
| [getWidth()](#getWidth--) | Obtiene o establece el ancho. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Obtiene el [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) en el índice especificado. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Obtiene un valor que indica si esta instancia tiene unidades de límites. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeBounds_internalized(Rectangle bounds)](#initializeBounds-internalized-com.aspose.psd.Rectangle-) | Inicializa los límites y matrices. |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina si el recurso es específico de PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtiene un valor que indica si esta instancia es un recurso específico de PSB. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Obtiene o establece un valor que indica si la orientación de rotación de esta instancia es horizontal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Guarda el recurso de objeto inteligente en el contenedor de flujo especificado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Guarda el encabezado del recurso personalizado. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Guarda la firma del encabezado, el identificador y la longitud. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Obtiene o establece la política de antialias de los datos de capa del objeto inteligente en la imagen PSD. |
| [setBottom(double value)](#setBottom-double-) | Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtiene o establece los límites de la capa colocada en el archivo PSD. |
| [setComp(int value)](#setComp-int-) | Obtiene o establece el valor comp de los datos de capa del objeto inteligente en el archivo PSD. |
| [setCompId(int value)](#setCompId-int-) | Obtiene o establece el ID del comp seleccionado actualmente para el documento hijo, que será -1 si no se selecciona ninguno. |
| [setCrop(int value)](#setCrop-int-) | Obtiene o establece el recorte de los datos de capa del objeto inteligente en la imagen PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Obtiene o establece el tipo de unidad predeterminado para los valores asignados como Izquierda, Superior, Derecha, Inferior, TransformMatrix. |
| [setDurationDenominator(int value)](#setDurationDenominator-int-) | Obtiene o establece el denominador de la duración. |
| [setDurationNumerator(int value)](#setDurationNumerator-int-) | Obtiene o establece el numerador de la duración. |
| [setFrameCount(int value)](#setFrameCount-int-) | Obtiene o establece el recuento de fotogramas de los datos de capa del objeto inteligente en el archivo PSD. |
| [setFrameStepDenominator(int value)](#setFrameStepDenominator-int-) | Obtiene o establece el denominador del paso de fotograma. |
| [setFrameStepNumerator(int value)](#setFrameStepNumerator-int-) | Obtiene o establece el numerador del paso de fotograma. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setHeight(double value)](#setHeight-double-) | Obtiene o establece la altura. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Obtiene o establece la unidad de medida de los puntos de malla horizontal. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtiene o establece los elementos del descriptor de los datos de capa del objeto inteligente en el archivo PSD. |
| [setLeft(double value)](#setLeft-double-) | Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD. |
| [setNonAffineTransformMatrix(double[] value)](#setNonAffineTransformMatrix-double---) | Obtiene o establece la matriz de transformación no afín de los datos de capa de objeto inteligente en el archivo PSD. |
| [setOriginalCompId_internalized(int value)](#setOriginalCompId-internalized-int-) | Obtiene el ID original del Comp seleccionado actualmente para el documento hijo, que será -1 si no se selecciona ninguno. |
| [setPageNumber(int value)](#setPageNumber-int-) | Obtiene o establece el número de página de los datos de capa de objeto inteligente en el archivo PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | Obtiene o establece el identificador único de estos datos de capa de objeto inteligente en la imagen PSD. |
| [setPlacedId_internalized(System.Guid value)](#setPlacedId-internalized-com.aspose.ms.System.Guid-) |  |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Obtiene o establece el tipo de los datos de capa de objeto inteligente en el archivo PSD. |
| [setResolution(double value)](#setResolution-double-) | Obtiene o establece la resolución de los datos de capa de objeto inteligente en el archivo PSD. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Obtiene o establece la unidad de medida de resolución de los datos de capa de objeto inteligente en el archivo PSD. |
| [setRight(double value)](#setRight-double-) | Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Obtiene o establece un valor que indica si la orientación de rotación de esta instancia es horizontal. |
| [setTop(double value)](#setTop-double-) | Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Obtiene o establece el número total de páginas de los datos de capa de objeto inteligente en el archivo PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Obtiene o establece la matriz de transformación de los datos de capa de objeto inteligente en el archivo PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Obtiene o establece el identificador único global de los datos de capa de objeto inteligente [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) en la imagen PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD. |
| [setValue(double value)](#setValue-double-) | Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD. |
| [setVersion(int value)](#setVersion-int-) | Obtiene la versión de la capa colocada en el archivo PSD, normalmente 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Obtiene o establece la unidad de medida de los puntos de malla vertical. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtiene o establece el ID de clase. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Obtiene o establece el nombre de clase de deformación. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Obtiene o establece la versión del descriptor de deformación. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Obtiene o establece la versión de deformación. |
| [setWidth(double value)](#setWidth-double-) | Obtiene o establece el ancho. |
| [toString()](#toString--) | Devuelve una String que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo) {#SoLeResource-java.util.UUID-boolean-boolean-}
```
public SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)
```


Inicializa una nueva instancia de la clase [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uniqueId | java.util.UUID | El identificador único de los datos de la capa colocada [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource). |
| isCustom | boolean | si se establece a  true  [es personalizado]. |
| hasCompInfo | boolean | si se establece a  true  [tiene información de composición]. |

### SoLeResource() {#SoLeResource--}
```
public SoLeResource()
```


Inicializa una nueva instancia de la clase [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource).

### AntiAliasPolicyKey_internalized {#AntiAliasPolicyKey-internalized}
```
public static final String AntiAliasPolicyKey_internalized
```


La clave de la política de antialias

### BottomKey_internalized {#BottomKey-internalized}
```
public static final String BottomKey_internalized
```


La clave inferior.

### BoundsKey_internalized {#BoundsKey-internalized}
```
public static final String BoundsKey_internalized
```


La clave de los límites

### CompIdKey_internalized {#CompIdKey-internalized}
```
public static final String CompIdKey_internalized
```


El nombre de la clave de CompID

### CompInfoKey_internalized {#CompInfoKey-internalized}
```
public static final String CompInfoKey_internalized
```


El nombre de la clave de información de comp

### CompKey_internalized {#CompKey-internalized}
```
public static final String CompKey_internalized
```


La clave de comp

### CompNoneValue_internalized {#CompNoneValue-internalized}
```
public static final int CompNoneValue_internalized
```


El valor de comp que significa 'none'

### CropKey_internalized {#CropKey-internalized}
```
public static final String CropKey_internalized
```


La clave de recorte

### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


El nombre de la deformación de sobre personalizada

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


El nombre de la clase de deformación predeterminada

### DenominatorKey_internalized {#DenominatorKey-internalized}
```
public static final String DenominatorKey_internalized
```


La clave del denominador

### DurationKey_internalized {#DurationKey-internalized}
```
public static final String DurationKey_internalized
```


La clave de duración

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


El nombre de la clase de deformación predeterminada

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


La versión esperada del descriptor de deformación

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


La versión esperada de la deformación

### FrameCountKey_internalized {#FrameCountKey-internalized}
```
public static final String FrameCountKey_internalized
```


La clave de recuento de fotogramas

### FrameStepKey_internalized {#FrameStepKey-internalized}
```
public static final String FrameStepKey_internalized
```


La clave de paso de fotogramas

### HeightKey_internalized {#HeightKey-internalized}
```
public static final String HeightKey_internalized
```


La clave de altura

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


El nombre del identificador horizontal

### IdentKey_internalized {#IdentKey-internalized}
```
public static final String IdentKey_internalized
```


La clave de identificador único

### ItemsPropertyCannotBeNull_internalized {#ItemsPropertyCannotBeNull-internalized}
```
public static final String ItemsPropertyCannotBeNull_internalized
```


La propiedad items no puede ser nula

### LeftKey_internalized {#LeftKey-internalized}
```
public static final String LeftKey_internalized
```


La clave izquierda.

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


El nombre de la clave de puntos de malla

### NonAffineTransformKey_internalized {#NonAffineTransformKey-internalized}
```
public static final String NonAffineTransformKey_internalized
```


La clave de transformación no afín

### NullClassId_internalized {#NullClassId-internalized}
```
public static final String NullClassId_internalized
```


El identificador de clase nula

### NumeratorKey_internalized {#NumeratorKey-internalized}
```
public static final String NumeratorKey_internalized
```


La clave del numerador

### OptionalKeys_internalized {#OptionalKeys-internalized}
```
public static final String[] OptionalKeys_internalized
```


La colección de claves opcionales

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


El nombre del identificador de orientación

### OriginalCompIdKey_internalized {#OriginalCompIdKey-internalized}
```
public static final String OriginalCompIdKey_internalized
```


El nombre de la clave del CompID original

### PageNumberKey_internalized {#PageNumberKey-internalized}
```
public static final String PageNumberKey_internalized
```


La clave del número de página

### PlacedIdKey_internalized {#PlacedIdKey-internalized}
```
public static final String PlacedIdKey_internalized
```


La clave del identificador colocado

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


El valor de versión esperado

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


La versión del encabezado PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


La firma de recurso específica de PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


La versión del encabezado PSD

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


El nombre del identificador de la clase de punto racional

### ResolutionKey_internalized {#ResolutionKey-internalized}
```
public static final String ResolutionKey_internalized
```


La clave de resolución

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


La firma de recurso común.

### RightKey_internalized {#RightKey-internalized}
```
public static final String RightKey_internalized
```


La clave derecha.

### SizeKey_internalized {#SizeKey-internalized}
```
public static final String SizeKey_internalized
```


La clave de tamaño

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


El tamaño de double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


El tamaño de int

### SmartVersionValue_internalized {#SmartVersionValue-internalized}
```
public static final int SmartVersionValue_internalized
```


El valor esperado de la versión del recurso del objeto inteligente.

### TopKey_internalized {#TopKey-internalized}
```
public static final String TopKey_internalized
```


La clave superior.

### TotalPagesKey_internalized {#TotalPagesKey-internalized}
```
public static final String TotalPagesKey_internalized
```


La clave del total de páginas

### TransformKey_internalized {#TransformKey-internalized}
```
public static final String TransformKey_internalized
```


La clave de transformación

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


El recuento de valores de transformación

### TypeKey_internalized {#TypeKey-internalized}
```
public static final String TypeKey_internalized
```


La clave de tipo

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


La clave de información de la herramienta de tipo: 'SoLE'.

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


El valor de tipo esperado.

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


La clave de orden u

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


La clave de orden v

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


El nombre del identificador vertical

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


El nombre personalizado de deformación

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


La longitud del encabezado de deformación.

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


La longitud del encabezado de deformación.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


La clave de deformación. También el nombre de clase de deformación predeterminado.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


El nombre de deformación ninguno

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


La clave de perspectiva de deformación

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


El otro de perspectiva de deformación

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


La clave de rotación de deformación

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


La clave de estilo de deformación

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


La clave de valor de deformación

### WidthKey_internalized {#WidthKey-internalized}
```
public static final String WidthKey_internalized
```


La clave de ancho

### YouCannotAccessCropPropertyMessage_internalized {#YouCannotAccessCropPropertyMessage-internalized}
```
public static final String YouCannotAccessCropPropertyMessage_internalized
```


No puede acceder a la propiedad Crop mensaje

### YouCannotSetCompIdPropertyMessage_internalized {#YouCannotSetCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetCompIdPropertyMessage_internalized
```


No puede establecer la propiedad CompId mensaje

### YouCannotSetCompPropertyMessage_internalized {#YouCannotSetCompPropertyMessage-internalized}
```
public static final String YouCannotSetCompPropertyMessage_internalized
```


No puede establecer la propiedad Comp mensaje

### YouCannotSetOriginalCompIdPropertyMessage_internalized {#YouCannotSetOriginalCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetOriginalCompIdPropertyMessage_internalized
```


No puede establecer la propiedad OriginalCompId mensaje

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


El carácter cero.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


La licencia venture.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Asegura que el valor real especificado sea igual al valor esperado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| actualValue | java.lang.Object | El valor real. |
| expectedValue | java.lang.Object | El valor esperado. |
| mensaje | java.lang.String | El mensaje. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Comprueba y establece si el recurso es específico de PSB. Algunos recursos no se reconocen por ahora, pero tenemos una lista completa de recursos específicos de PSB que cambian su comportamiento al guardar. Por lo tanto, debemos comprobar esto al menos en UnknownResource.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | int | La clave. |

### convertListStructureToDoubleArray_internalized(ListStructure list) {#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-}
```
public static double[] convertListStructureToDoubleArray_internalized(ListStructure list)
```


Convierte la estructura de lista a una matriz de dobles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| list | [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) | La instancia  ListStructure . |

**Returns:**
double[] - La matriz  double[]  creada.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Obtiene o establece la política de antialias de los datos de capa del objeto inteligente en la imagen PSD.

Valor: La política anti alias de los datos de capa de objeto inteligente.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD.

Valor: La ubicación inferior de la capa colocada.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtiene o establece los límites de la capa colocada en el archivo PSD.

Valor: Los límites de la capa colocada.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComp() {#getComp--}
```
public final int getComp()
```


Obtiene o establece el valor de composición de los datos de capa de objeto inteligente en el archivo PSD.  Composiciones de capa en objetos inteligentes

Valor: El valor de composición, es -1 si no hay ninguno.

**Returns:**
int
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Obtiene o establece el ID de la composición seleccionada actualmente para el documento hijo, que será -1 si no hay ninguna seleccionada. Las composiciones son composiciones de un diseño de página que los diseñadores pueden crear. Usando composiciones de capa, puedes crear, gestionar y ver múltiples versiones de un diseño en un solo archivo Adobe\\ufffd Photoshop\\ufffd. Una composición de capa es una captura del estado del panel Capas. Las composiciones de capa guardan tres tipos de opciones de capa pero esta propiedad obtiene el identificador de selección de Layer Comp para la capa de objeto inteligente en el archivo PSD.  Composiciones de capa en objetos inteligentes

Valor: El ID de la composición seleccionada actualmente para el documento hijo en la imagen PSD, que será -1 si no hay ninguna seleccionada.

**Returns:**
int
### getCrop() {#getCrop--}
```
public final int getCrop()
```


Obtiene o establece el recorte de los datos de capa del objeto inteligente en la imagen PSD.

Valor: El valor de recorte de la información de capa colocada.

**Returns:**
int
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Obtiene o establece el tipo de unidad predeterminado para los valores asignados como Izquierda, Superior, Derecha, Inferior, TransformMatrix.

Valor: El tipo de unidad de medida predeterminado.

**Returns:**
int
### getDurationDenominator() {#getDurationDenominator--}
```
public final int getDurationDenominator()
```


Obtiene o establece el denominador de la duración.

Valor: El denominador de la duración.

**Returns:**
int
### getDurationNumerator() {#getDurationNumerator--}
```
public final int getDurationNumerator()
```


Obtiene o establece el numerador de la duración.

Valor: El numerador de la duración.

**Returns:**
int
### getFrameCount() {#getFrameCount--}
```
public final int getFrameCount()
```


Obtiene o establece el recuento de fotogramas de los datos de capa del objeto inteligente en el archivo PSD.

Valor: El recuento de fotogramas de la información de capa colocada.

**Returns:**
int
### getFrameStepDenominator() {#getFrameStepDenominator--}
```
public final int getFrameStepDenominator()
```


Obtiene o establece el denominador del paso de fotograma.

Valor: El denominador del paso de fotogramas.

**Returns:**
int
### getFrameStepNumerator() {#getFrameStepNumerator--}
```
public final int getFrameStepNumerator()
```


Obtiene o establece el numerador del paso de fotograma.

Valor: El numerador del paso de fotograma.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtiene o establece la altura.

Valor: La altura.

**Returns:**
double
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Obtiene o establece la unidad de medida de los puntos de malla horizontal.

Valor: La unidad de medida de los puntos de malla horizontales.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD.

Valor: Los puntos de malla horizontales de la capa colocada.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Obtiene o establece los elementos del descriptor de los datos de capa del objeto inteligente en el archivo PSD.

Valor: Los elementos descriptivos de la información de capa colocada.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Obtiene la clave del recurso de capa.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD.

Valor: La ubicación izquierda de la capa colocada.

**Returns:**
double
### getLength() {#getLength--}
```
public int getLength()
```


Obtiene la longitud del recurso de objeto inteligente en bytes.

**Returns:**
int
### getNonAffineTransformMatrix() {#getNonAffineTransformMatrix--}
```
public final double[] getNonAffineTransformMatrix()
```


Obtiene o establece la matriz de transformación no afín de los datos de capa de objeto inteligente en el archivo PSD.

Valor: La matriz de transformación no afín de la capa de objeto inteligente.

**Returns:**
double[]
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Obtiene el ID original del Comp actualmente seleccionado para el documento hijo, que será -1 si no hay ninguno seleccionado. Esta propiedad obtiene el identificador de selección original del Comp de capa para la capa de objeto inteligente en el archivo PSD.  Layer comps in Smart Objects

Valor: El ID original del comp actualmente seleccionado para el documento hijo en la imagen PSD, que será -1 si no hay ninguno seleccionado.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Obtiene o establece el número de página de los datos de capa de objeto inteligente en el archivo PSD.

Valor: El número de página de los datos de la capa de objeto inteligente.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD.

Valor: El valor de perspectiva de la capa colocada.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD.

Valor: El otro valor de perspectiva de la capa colocada.

**Returns:**
double
### getPlacedId() {#getPlacedId--}
```
public final UUID getPlacedId()
```


Obtiene o establece el identificador único de estos datos de capa de objeto inteligente en la imagen PSD.

Valor: El identificador único de este recurso de capa de objeto inteligente.

**Returns:**
java.util.UUID
### getPlacedId_internalized() {#getPlacedId-internalized--}
```
public final System.Guid getPlacedId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Obtiene o establece el tipo de los datos de capa de objeto inteligente en el archivo PSD.

Valor: El tipo de los datos de la capa de objeto inteligente.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Obtiene la longitud del prefijo. El valor predeterminado es 12 para recursos 8BIM y 16 para 8B64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| psdVersion | int | La versión PSD. |

**Returns:**
int - La longitud del prefijo.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones.

**Returns:**
int
### getResolution() {#getResolution--}
```
public final double getResolution()
```


Obtiene o establece la resolución de los datos de capa de objeto inteligente en el archivo PSD.

Valor: La resolución de la capa de objeto inteligente.

**Returns:**
double
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


Obtiene o establece la unidad de medida de resolución de los datos de capa de objeto inteligente en el archivo PSD.

Valor: La unidad de medida de resolución de la capa de objeto inteligente.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD.

Valor: La ubicación derecha de la capa colocada.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtiene la firma del recurso de capa.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD.

Valor: La ubicación superior de la capa colocada.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Obtiene o establece el número total de páginas de los datos de capa de objeto inteligente en el archivo PSD.

Valor: El número total de páginas de los datos de la capa de objeto inteligente.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Obtiene o establece la matriz de transformación de los datos de capa de objeto inteligente en el archivo PSD.

Valor: La matriz de transformación de los datos de la capa de objeto inteligente.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD.

Valor: El valor de orden U de la capa colocada.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Obtiene o establece el identificador único global de los datos de capa de objeto inteligente [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) en la imagen PSD.

Valor: El identificador único global de los datos de la capa de objeto inteligente [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD.

Valor: El valor de orden V de la capa colocada.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD.

Valor: El valor de deformación de la capa colocada.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtiene la versión de la capa colocada en el archivo PSD, normalmente 3.

Valor: La versión de la capa colocada.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Obtiene o establece la unidad de medida de los puntos de malla vertical.

Valor: La unidad de medida de los puntos de malla verticales.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD.

Valor: Los puntos de malla horizontales de la capa colocada.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Obtiene o establece el ID de clase.

Valor: El ID de clase.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Obtiene o establece el nombre de clase de deformación.

Valor: El nombre de clase de deformación.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Obtiene o establece la versión del descriptor de deformación.

Valor: La versión del descriptor de deformación.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Los elementos de deformación.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Obtiene o establece la versión de deformación.

Valor: La versión de deformación.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtiene o establece el ancho.

Valor: El ancho.

**Returns:**
double
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Obtiene el [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | java.lang.String | El nombre de la clave. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Obtiene un valor que indica si esta instancia tiene unidades de límites.

Valor:  true  si esta instancia tiene unidades de límites; de lo contrario,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initProreties_internalized(PlaceResourceParams plLdResourceParams) {#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public final void initProreties_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### initializeBounds_internalized(Rectangle bounds) {#initializeBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void initializeBounds_internalized(Rectangle bounds)
```


Inicializa los límites y matrices.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites. |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. Si es verdadero, contiene puntos de malla. Si se establece en falso, elimina los puntos de malla.

Valor:  true  si la capa colocada tiene estilo personalizado; de lo contrario,  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Determina si el recurso es específico de PSB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | int | La clave del recurso. |

**Returns:**
boolean -  true  si el recurso es específico de PSB; de lo contrario,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Obtiene un valor que indica si esta instancia es un recurso específico de PSB.

Valor:  true  si esta instancia es un recurso específico de PSB; de lo contrario,  false .

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Obtiene o establece un valor que indica si la orientación de rotación de esta instancia es horizontal.

Valor:  true  si la orientación de rotación es horizontal; de lo contrario,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Guarda el recurso de objeto inteligente en el contenedor de flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psdVersion | int | La versión PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Guarda el encabezado del recurso personalizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| firma | int | La firma. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Guarda la firma del encabezado, el identificador y la longitud.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| firma | int | La firma. |
| isLengthLong | boolean | si se establece en  true  la longitud es larga. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Obtiene o establece la política de antialias de los datos de capa del objeto inteligente en la imagen PSD.

Valor: La política anti alias de los datos de capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Obtiene o establece la ubicación inferior de la capa colocada en la imagen PSD.

Valor: La ubicación inferior de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Obtiene o establece los límites de la capa colocada en el archivo PSD.

Valor: Los límites de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setComp(int value) {#setComp-int-}
```
public final void setComp(int value)
```


Obtiene o establece el valor de composición de los datos de capa de objeto inteligente en el archivo PSD.  Composiciones de capa en objetos inteligentes

Valor: El valor de composición, es -1 si no hay ninguno.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Obtiene o establece el ID de la composición seleccionada actualmente para el documento hijo, que será -1 si no hay ninguna seleccionada. Las composiciones son composiciones de un diseño de página que los diseñadores pueden crear. Usando composiciones de capa, puedes crear, gestionar y ver múltiples versiones de un diseño en un solo archivo Adobe\\ufffd Photoshop\\ufffd. Una composición de capa es una captura del estado del panel Capas. Las composiciones de capa guardan tres tipos de opciones de capa pero esta propiedad obtiene el identificador de selección de Layer Comp para la capa de objeto inteligente en el archivo PSD.  Composiciones de capa en objetos inteligentes

Valor: El ID de la composición seleccionada actualmente para el documento hijo en la imagen PSD, que será -1 si no hay ninguna seleccionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setCrop(int value) {#setCrop-int-}
```
public final void setCrop(int value)
```


Obtiene o establece el recorte de los datos de capa del objeto inteligente en la imagen PSD.

Valor: El valor de recorte de la información de capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Obtiene o establece un valor que indica si el estilo de deformación de esta instancia es personalizado. Si es verdadero, contiene puntos de malla. Si se establece en falso, elimina los puntos de malla.

Valor:  true  si la capa colocada tiene estilo personalizado; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Obtiene o establece el tipo de unidad predeterminado para los valores asignados como Izquierda, Superior, Derecha, Inferior, TransformMatrix.

Valor: El tipo de unidad de medida predeterminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDurationDenominator(int value) {#setDurationDenominator-int-}
```
public final void setDurationDenominator(int value)
```


Obtiene o establece el denominador de la duración.

Valor: El denominador de la duración.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDurationNumerator(int value) {#setDurationNumerator-int-}
```
public final void setDurationNumerator(int value)
```


Obtiene o establece el numerador de la duración.

Valor: El numerador de la duración.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFrameCount(int value) {#setFrameCount-int-}
```
public final void setFrameCount(int value)
```


Obtiene o establece el recuento de fotogramas de los datos de capa del objeto inteligente en el archivo PSD.

Valor: El recuento de fotogramas de la información de capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFrameStepDenominator(int value) {#setFrameStepDenominator-int-}
```
public final void setFrameStepDenominator(int value)
```


Obtiene o establece el denominador del paso de fotograma.

Valor: El denominador del paso de fotogramas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFrameStepNumerator(int value) {#setFrameStepNumerator-int-}
```
public final void setFrameStepNumerator(int value)
```


Obtiene o establece el numerador del paso de fotograma.

Valor: El numerador del paso de fotograma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Obtiene o establece la altura.

Valor: La altura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Obtiene o establece la unidad de medida de los puntos de malla horizontal.

Valor: La unidad de medida de los puntos de malla horizontales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD.

Valor: Los puntos de malla horizontales de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Obtiene o establece los elementos del descriptor de los datos de capa del objeto inteligente en el archivo PSD.

Valor: Los elementos descriptivos de la información de capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Obtiene o establece la ubicación izquierda de la capa colocada en el archivo PSD.

Valor: La ubicación izquierda de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setNonAffineTransformMatrix(double[] value) {#setNonAffineTransformMatrix-double---}
```
public final void setNonAffineTransformMatrix(double[] value)
```


Obtiene o establece la matriz de transformación no afín de los datos de capa de objeto inteligente en el archivo PSD.

Valor: La matriz de transformación no afín de la capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setOriginalCompId_internalized(int value) {#setOriginalCompId-internalized-int-}
```
public final void setOriginalCompId_internalized(int value)
```


Obtiene el ID original del Comp actualmente seleccionado para el documento hijo, que será -1 si no hay ninguno seleccionado. Esta propiedad obtiene el identificador de selección original del Comp de capa para la capa de objeto inteligente en el archivo PSD.  Layer comps in Smart Objects

Valor: El ID original del comp actualmente seleccionado para el documento hijo en la imagen PSD, que será -1 si no hay ninguno seleccionado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Obtiene o establece el número de página de los datos de capa de objeto inteligente en el archivo PSD.

Valor: El número de página de los datos de la capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Obtiene o establece el valor de perspectiva de la capa colocada en el archivo PSD.

Valor: El valor de perspectiva de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Obtiene o establece el otro valor de perspectiva de la capa colocada en el archivo PSD.

Valor: El otro valor de perspectiva de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public final void setPlacedId(UUID value)
```


Obtiene o establece el identificador único de estos datos de capa de objeto inteligente en la imagen PSD.

Valor: El identificador único de este recurso de capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID |  |

### setPlacedId_internalized(System.Guid value) {#setPlacedId-internalized-com.aspose.ms.System.Guid-}
```
public final void setPlacedId_internalized(System.Guid value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.Guid |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Obtiene o establece el tipo de los datos de capa de objeto inteligente en el archivo PSD.

Valor: El tipo de los datos de la capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setResolution(double value) {#setResolution-double-}
```
public final void setResolution(double value)
```


Obtiene o establece la resolución de los datos de capa de objeto inteligente en el archivo PSD.

Valor: La resolución de la capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public final void setResolutionUnit(int value)
```


Obtiene o establece la unidad de medida de resolución de los datos de capa de objeto inteligente en el archivo PSD.

Valor: La unidad de medida de resolución de la capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Obtiene o establece la ubicación derecha de la capa colocada en el archivo PSD.

Valor: La ubicación derecha de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Obtiene o establece un valor que indica si la orientación de rotación de esta instancia es horizontal.

Valor:  true  si la orientación de rotación es horizontal; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Obtiene o establece la ubicación superior de la capa colocada en la imagen PSD.

Valor: La ubicación superior de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Obtiene o establece el número total de páginas de los datos de capa de objeto inteligente en el archivo PSD.

Valor: El número total de páginas de los datos de la capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Obtiene o establece la matriz de transformación de los datos de capa de objeto inteligente en el archivo PSD.

Valor: La matriz de transformación de los datos de la capa de objeto inteligente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Obtiene o establece el valor de orden U de la capa colocada en el archivo PSD.

Valor: El valor de orden U de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Obtiene o establece el identificador único global de los datos de capa de objeto inteligente [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) en la imagen PSD.

Valor: El identificador único global de los datos de la capa de objeto inteligente [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Obtiene o establece el valor de orden V de la capa colocada en el archivo PSD.

Valor: El valor de orden V de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Obtiene o establece el valor de deformación de la capa colocada en la imagen PSD.

Valor: El valor de deformación de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Obtiene la versión de la capa colocada en el archivo PSD, normalmente 3.

Valor: La versión de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Obtiene o establece la unidad de medida de los puntos de malla vertical.

Valor: La unidad de medida de los puntos de malla verticales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Obtiene o establece los puntos de malla horizontal de la capa colocada en el archivo PSD.

Valor: Los puntos de malla horizontales de la capa colocada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Obtiene o establece el ID de clase.

Valor: El ID de clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Obtiene o establece el nombre de clase de deformación.

Valor: El nombre de clase de deformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Obtiene o establece la versión del descriptor de deformación.

Valor: La versión del descriptor de deformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Obtiene o establece la versión de deformación.

Valor: La versión de deformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Obtiene o establece el ancho.

Valor: El ancho.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una String que representa esta instancia.

**Returns:**
java.lang.String - Una String que representa esta instancia.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

