---
title: "SmartObjectResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет класс SmartObjectResource, который содержит информацию о слое смарт‑объекта в файле PSD."
type: docs
weight: 13
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.ISmartObjectLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/ismartobjectlayerresource)
```
public abstract class SmartObjectResource extends PlacedResource implements ISmartObjectLayerResource
```

Определяет класс SmartObjectResource, который содержит информацию о слое смарт-объекта в файле PSD. Является базовым классом для ресурсов Sold и Sole, используемых для поддержки слоёв смарт-объектов в изображениях Adobe\\ufffd Photoshop\\ufffd.
## Поля

| Поле | Описание |
| --- | --- |
| [AntiAliasPolicyKey_internalized](#AntiAliasPolicyKey-internalized) | Ключ политики сглаживания |
| [BottomKey_internalized](#BottomKey-internalized) | Нижний ключ |
| [BoundsKey_internalized](#BoundsKey-internalized) | Ключ границ |
| [CompIdKey_internalized](#CompIdKey-internalized) | Имя ключа CompID |
| [CompInfoKey_internalized](#CompInfoKey-internalized) | Имя ключа информации о comp |
| [CompKey_internalized](#CompKey-internalized) | Ключ comp |
| [CompNoneValue_internalized](#CompNoneValue-internalized) | Значение comp, означающее 'none' |
| [CropKey_internalized](#CropKey-internalized) | Ключ обрезки |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Имя пользовательского конвертного искажения |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Имя класса искажения по умолчанию |
| [DenominatorKey_internalized](#DenominatorKey-internalized) | Ключ знаменателя |
| [DurationKey_internalized](#DurationKey-internalized) | Ключ длительности |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Имя класса искажения по умолчанию |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Ожидаемая версия дескриптора искажения |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Ожидаемая версия искажения |
| [FrameCountKey_internalized](#FrameCountKey-internalized) | Ключ количества кадров |
| [FrameStepKey_internalized](#FrameStepKey-internalized) | Ключ шага кадра |
| [HeightKey_internalized](#HeightKey-internalized) | Ключ высоты |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Имя горизонтального идентификатора |
| [IdentKey_internalized](#IdentKey-internalized) | Ключ уникального идентификатора |
| [ItemsPropertyCannotBeNull_internalized](#ItemsPropertyCannotBeNull-internalized) | Свойство items не может быть null |
| [LeftKey_internalized](#LeftKey-internalized) | Левый ключ |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Имя ключа точек сетки |
| [NonAffineTransformKey_internalized](#NonAffineTransformKey-internalized) | Ключ неаффинного преобразования |
| [NullClassId_internalized](#NullClassId-internalized) | Идентификатор нулевого класса |
| [NumeratorKey_internalized](#NumeratorKey-internalized) | Ключ числителя |
| [OptionalKeys_internalized](#OptionalKeys-internalized) | Коллекция необязательных ключей |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Имя идентификатора ориентации |
| [OriginalCompIdKey_internalized](#OriginalCompIdKey-internalized) | Имя ключа оригинального CompID |
| [PageNumberKey_internalized](#PageNumberKey-internalized) | Ключ номера страницы |
| [PlacedIdKey_internalized](#PlacedIdKey-internalized) | Ключ размещённого идентификатора |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Ожидаемое значение версии |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Версия заголовка PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Подпись ресурса, специфичная для PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Версия заголовка PSD |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Имя идентификатора класса рациональной точки |
| [ResolutionKey_internalized](#ResolutionKey-internalized) | Ключ разрешения |
| [ResourceSignature](#ResourceSignature) | Общая подпись ресурса. |
| [RightKey_internalized](#RightKey-internalized) | Правый ключ |
| [SizeKey_internalized](#SizeKey-internalized) | Ключ размера |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | Размер типа double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | Размер типа int |
| [SmartVersionValue_internalized](#SmartVersionValue-internalized) | Ожидаемое значение версии ресурса смарт‑объекта. |
| [TopKey_internalized](#TopKey-internalized) | Верхний ключ |
| [TotalPagesKey_internalized](#TotalPagesKey-internalized) | Ключ общего количества страниц |
| [TransformKey_internalized](#TransformKey-internalized) | Ключ трансформации |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Количество значений трансформации |
| [TypeKey_internalized](#TypeKey-internalized) | Ключ типа |
| [TypeValue_internalized](#TypeValue-internalized) | Ожидаемое значение типа. |
| [UOrderKey_internalized](#UOrderKey-internalized) | Ключ порядка u |
| [VOrderKey_internalized](#VOrderKey-internalized) | Ключ порядка v |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Имя вертикального идентификатора |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Пользовательское имя искажения |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Длина заголовка искажения. |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Длина заголовка искажения. |
| [WarpKey_internalized](#WarpKey-internalized) | Ключ искажения. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Имя отсутствующего искажения |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Ключ перспективы искажения |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Другой параметр перспективы искажения |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Ключ вращения искажения |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Ключ стиля искажения |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Ключ значения искажения |
| [WidthKey_internalized](#WidthKey-internalized) | Ключ ширины |
| [YouCannotAccessCropPropertyMessage_internalized](#YouCannotAccessCropPropertyMessage-internalized) | Вы не можете получить доступ к свойству Crop |
| [YouCannotSetCompIdPropertyMessage_internalized](#YouCannotSetCompIdPropertyMessage-internalized) | Вы не можете установить свойство CompId |
| [YouCannotSetCompPropertyMessage_internalized](#YouCannotSetCompPropertyMessage-internalized) | Вы не можете установить свойство Comp |
| [YouCannotSetOriginalCompIdPropertyMessage_internalized](#YouCannotSetOriginalCompIdPropertyMessage-internalized) | Вы не можете установить свойство OriginalCompId |
| [ZeroChar_internalized](#ZeroChar-internalized) | Нулевой символ. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Лицензия предприятия. |
## Методы

| Метод | Описание |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Проверяет, что указанное фактическое значение равно ожидаемому значению. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Проверяет и устанавливает, является ли ресурс специфичным для PSB. |
| [convertListStructureToDoubleArray_internalized(ListStructure list)](#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-) | Преобразует структуру списка в массив double. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Получает или задает политику сглаживания данных слоя смарт‑объекта в изображении PSD. |
| [getBottom()](#getBottom--) | Получает или задает положение снизу размещённого слоя в изображении PSD. |
| [getBounds()](#getBounds--) | Получает или задает границы размещённого слоя в файле PSD. |
| [getClass()](#getClass--) |  |
| [getComp()](#getComp--) | Получает или задает значение comp данных слоя смарт‑объекта в файле PSD. |
| [getCompId()](#getCompId--) | Получает или задает идентификатор текущего выбранного компонента для дочернего документа, который будет -1, если ничего не выбрано. |
| [getCrop()](#getCrop--) | Получает или задает обрезку данных слоя смарт‑объекта в изображении PSD. |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Получает или задает тип единицы измерения по умолчанию для назначенных значений, таких как Left, Top, Right, Bottom, TransformMatrix. |
| [getDurationDenominator()](#getDurationDenominator--) | Получает или задает знаменатель длительности. |
| [getDurationNumerator()](#getDurationNumerator--) | Получает или задает числитель длительности. |
| [getFrameCount()](#getFrameCount--) | Получает или задает количество кадров данных слоя смарт‑объекта в файле PSD. |
| [getFrameStepDenominator()](#getFrameStepDenominator--) | Получает или задает знаменатель шага кадра. |
| [getFrameStepNumerator()](#getFrameStepNumerator--) | Получает или задает числитель шага кадра. |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getHeight()](#getHeight--) | Получает или задает высоту. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Получает или задает единицу измерения горизонтальных точек сетки. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [getItems()](#getItems--) | Получает или задает элементы дескриптора данных слоя смарт‑объекта в файле PSD. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLeft()](#getLeft--) | Получает или задает положение слева размещённого слоя в файле PSD. |
| [getLength()](#getLength--) | Получает длину ресурса смарт‑объекта в байтах. |
| [getNonAffineTransformMatrix()](#getNonAffineTransformMatrix--) | Получает или задает неаффинную матрицу преобразования данных слоя смарт-объекта в файле PSD. |
| [getOriginalCompId()](#getOriginalCompId--) | Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. |
| [getPageNumber()](#getPageNumber--) | Получает или задает номер страницы данных слоя смарт-объекта в файле PSD. |
| [getPerspective()](#getPerspective--) | Получает или задает значение перспективы размещённого слоя в файле PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Получает или задает другое значение перспективы размещённого слоя в файле PSD. |
| [getPlacedId()](#getPlacedId--) | Получает или задает уникальный идентификатор этих данных слоя смарт-объекта в изображении PSD. |
| [getPlacedId_internalized()](#getPlacedId-internalized--) |  |
| [getPlacedLayerType()](#getPlacedLayerType--) | Получает или задает тип данных слоя смарт-объекта в файле PSD. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, требуемую для ресурса слоя. |
| [getResolution()](#getResolution--) | Получает или задает разрешение данных слоя смарт-объекта в файле PSD. |
| [getResolutionUnit()](#getResolutionUnit--) | Получает или задает единицу измерения разрешения данных слоя смарт-объекта в файле PSD. |
| [getRight()](#getRight--) | Получает или задает положение справа размещённого слоя в файле PSD. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [getTop()](#getTop--) | Получает или задает положение сверху размещённого слоя в изображении PSD. |
| [getTotalPages()](#getTotalPages--) | Получает или задает общее количество страниц данных слоя смарт-объекта в файле PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Получает или задает матрицу преобразования данных слоя смарт-объекта в файле PSD. |
| [getUOrder()](#getUOrder--) | Получает или задает значение порядка U размещённого слоя в файле PSD. |
| [getUniqueId()](#getUniqueId--) | Получает или задает глобальный уникальный идентификатор данных слоя смарт-объекта [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) в изображении PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Получает или задает значение порядка V размещённого слоя в файле PSD. |
| [getValue()](#getValue--) | Получает или задает значение искажения размещённого слоя в изображении PSD. |
| [getVersion()](#getVersion--) | Получает версию размещённого слоя в файле PSD, обычно 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Получает или задает единицу измерения вертикальных точек сетки. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Получает или задает идентификатор класса. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Получает или задает название класса искажения. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Получает или задает версию дескриптора искажения. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Элементы деформации. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Получает или задает версию искажения. |
| [getWidth()](#getWidth--) | Получает или задает ширину. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Получает [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) по указанному индексу. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Получает значение, указывающее, имеет ли данный экземпляр единицы границ. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeBounds_internalized(Rectangle bounds)](#initializeBounds-internalized-com.aspose.psd.Rectangle-) | Инициализирует границы и матрицы. |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | Получает или задает значение, указывающее, является ли стиль warp данного экземпляра пользовательским. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Получает или задает значение, указывающее, является ли ориентация вращения данного экземпляра горизонтальной. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет ресурс смарт-объекта в указанный потоковый контейнер. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Получает или задает политику сглаживания данных слоя смарт‑объекта в изображении PSD. |
| [setBottom(double value)](#setBottom-double-) | Получает или задает положение снизу размещённого слоя в изображении PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Получает или задает границы размещённого слоя в файле PSD. |
| [setComp(int value)](#setComp-int-) | Получает или задает значение comp данных слоя смарт‑объекта в файле PSD. |
| [setCompId(int value)](#setCompId-int-) | Получает или задает идентификатор текущего выбранного компонента для дочернего документа, который будет -1, если ничего не выбрано. |
| [setCrop(int value)](#setCrop-int-) | Получает или задает обрезку данных слоя смарт‑объекта в изображении PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Получает или задает значение, указывающее, является ли стиль warp данного экземпляра пользовательским. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Получает или задает тип единицы измерения по умолчанию для назначенных значений, таких как Left, Top, Right, Bottom, TransformMatrix. |
| [setDurationDenominator(int value)](#setDurationDenominator-int-) | Получает или задает знаменатель длительности. |
| [setDurationNumerator(int value)](#setDurationNumerator-int-) | Получает или задает числитель длительности. |
| [setFrameCount(int value)](#setFrameCount-int-) | Получает или задает количество кадров данных слоя смарт‑объекта в файле PSD. |
| [setFrameStepDenominator(int value)](#setFrameStepDenominator-int-) | Получает или задает знаменатель шага кадра. |
| [setFrameStepNumerator(int value)](#setFrameStepNumerator-int-) | Получает или задает числитель шага кадра. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setHeight(double value)](#setHeight-double-) | Получает или задает высоту. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Получает или задает единицу измерения горизонтальных точек сетки. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Получает или задает элементы дескриптора данных слоя смарт‑объекта в файле PSD. |
| [setLeft(double value)](#setLeft-double-) | Получает или задает положение слева размещённого слоя в файле PSD. |
| [setNonAffineTransformMatrix(double[] value)](#setNonAffineTransformMatrix-double---) | Получает или задает неаффинную матрицу преобразования данных слоя смарт-объекта в файле PSD. |
| [setOriginalCompId_internalized(int value)](#setOriginalCompId-internalized-int-) | Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. |
| [setPageNumber(int value)](#setPageNumber-int-) | Получает или задает номер страницы данных слоя смарт-объекта в файле PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Получает или задает значение перспективы размещённого слоя в файле PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Получает или задает другое значение перспективы размещённого слоя в файле PSD. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | Получает или задает уникальный идентификатор этих данных слоя смарт-объекта в изображении PSD. |
| [setPlacedId_internalized(System.Guid value)](#setPlacedId-internalized-com.aspose.ms.System.Guid-) |  |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Получает или задает тип данных слоя смарт-объекта в файле PSD. |
| [setResolution(double value)](#setResolution-double-) | Получает или задает разрешение данных слоя смарт-объекта в файле PSD. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Получает или задает единицу измерения разрешения данных слоя смарт-объекта в файле PSD. |
| [setRight(double value)](#setRight-double-) | Получает или задает положение справа размещённого слоя в файле PSD. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Получает или задает значение, указывающее, является ли ориентация вращения данного экземпляра горизонтальной. |
| [setTop(double value)](#setTop-double-) | Получает или задает положение сверху размещённого слоя в изображении PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Получает или задает общее количество страниц данных слоя смарт-объекта в файле PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Получает или задает матрицу преобразования данных слоя смарт-объекта в файле PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Получает или задает значение порядка U размещённого слоя в файле PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Получает или задает глобальный уникальный идентификатор данных слоя смарт-объекта [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) в изображении PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Получает или задает значение порядка V размещённого слоя в файле PSD. |
| [setValue(double value)](#setValue-double-) | Получает или задает значение искажения размещённого слоя в изображении PSD. |
| [setVersion(int value)](#setVersion-int-) | Получает версию размещённого слоя в файле PSD, обычно 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Получает или задает единицу измерения вертикальных точек сетки. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задает идентификатор класса. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Получает или задает название класса искажения. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Получает или задает версию дескриптора искажения. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Получает или задает версию искажения. |
| [setWidth(double value)](#setWidth-double-) | Получает или задает ширину. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AntiAliasPolicyKey_internalized {#AntiAliasPolicyKey-internalized}
```
public static final String AntiAliasPolicyKey_internalized
```


Ключ политики сглаживания

### BottomKey_internalized {#BottomKey-internalized}
```
public static final String BottomKey_internalized
```


Нижний ключ

### BoundsKey_internalized {#BoundsKey-internalized}
```
public static final String BoundsKey_internalized
```


Ключ границ

### CompIdKey_internalized {#CompIdKey-internalized}
```
public static final String CompIdKey_internalized
```


Имя ключа CompID

### CompInfoKey_internalized {#CompInfoKey-internalized}
```
public static final String CompInfoKey_internalized
```


Имя ключа информации о comp

### CompKey_internalized {#CompKey-internalized}
```
public static final String CompKey_internalized
```


Ключ comp

### CompNoneValue_internalized {#CompNoneValue-internalized}
```
public static final int CompNoneValue_internalized
```


Значение comp, означающее 'none'

### CropKey_internalized {#CropKey-internalized}
```
public static final String CropKey_internalized
```


Ключ обрезки

### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Имя пользовательского конвертного искажения

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Имя класса искажения по умолчанию

### DenominatorKey_internalized {#DenominatorKey-internalized}
```
public static final String DenominatorKey_internalized
```


Ключ знаменателя

### DurationKey_internalized {#DurationKey-internalized}
```
public static final String DurationKey_internalized
```


Ключ длительности

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Имя класса искажения по умолчанию

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


Ожидаемая версия дескриптора искажения

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


Ожидаемая версия искажения

### FrameCountKey_internalized {#FrameCountKey-internalized}
```
public static final String FrameCountKey_internalized
```


Ключ количества кадров

### FrameStepKey_internalized {#FrameStepKey-internalized}
```
public static final String FrameStepKey_internalized
```


Ключ шага кадра

### HeightKey_internalized {#HeightKey-internalized}
```
public static final String HeightKey_internalized
```


Ключ высоты

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Имя горизонтального идентификатора

### IdentKey_internalized {#IdentKey-internalized}
```
public static final String IdentKey_internalized
```


Ключ уникального идентификатора

### ItemsPropertyCannotBeNull_internalized {#ItemsPropertyCannotBeNull-internalized}
```
public static final String ItemsPropertyCannotBeNull_internalized
```


Свойство items не может быть null

### LeftKey_internalized {#LeftKey-internalized}
```
public static final String LeftKey_internalized
```


Левый ключ

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Имя ключа точек сетки

### NonAffineTransformKey_internalized {#NonAffineTransformKey-internalized}
```
public static final String NonAffineTransformKey_internalized
```


Ключ неаффинного преобразования

### NullClassId_internalized {#NullClassId-internalized}
```
public static final String NullClassId_internalized
```


Идентификатор нулевого класса

### NumeratorKey_internalized {#NumeratorKey-internalized}
```
public static final String NumeratorKey_internalized
```


Ключ числителя

### OptionalKeys_internalized {#OptionalKeys-internalized}
```
public static final String[] OptionalKeys_internalized
```


Коллекция необязательных ключей

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Имя идентификатора ориентации

### OriginalCompIdKey_internalized {#OriginalCompIdKey-internalized}
```
public static final String OriginalCompIdKey_internalized
```


Имя ключа оригинального CompID

### PageNumberKey_internalized {#PageNumberKey-internalized}
```
public static final String PageNumberKey_internalized
```


Ключ номера страницы

### PlacedIdKey_internalized {#PlacedIdKey-internalized}
```
public static final String PlacedIdKey_internalized
```


Ключ размещённого идентификатора

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


Ожидаемое значение версии

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Версия заголовка PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Подпись ресурса, специфичная для PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Версия заголовка PSD

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Имя идентификатора класса рациональной точки

### ResolutionKey_internalized {#ResolutionKey-internalized}
```
public static final String ResolutionKey_internalized
```


Ключ разрешения

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Общая подпись ресурса.

### RightKey_internalized {#RightKey-internalized}
```
public static final String RightKey_internalized
```


Правый ключ

### SizeKey_internalized {#SizeKey-internalized}
```
public static final String SizeKey_internalized
```


Ключ размера

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


Размер типа double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


Размер типа int

### SmartVersionValue_internalized {#SmartVersionValue-internalized}
```
public static final int SmartVersionValue_internalized
```


Ожидаемое значение версии ресурса смарт‑объекта.

### TopKey_internalized {#TopKey-internalized}
```
public static final String TopKey_internalized
```


Верхний ключ

### TotalPagesKey_internalized {#TotalPagesKey-internalized}
```
public static final String TotalPagesKey_internalized
```


Ключ общего количества страниц

### TransformKey_internalized {#TransformKey-internalized}
```
public static final String TransformKey_internalized
```


Ключ трансформации

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Количество значений трансформации

### TypeKey_internalized {#TypeKey-internalized}
```
public static final String TypeKey_internalized
```


Ключ типа

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


Ожидаемое значение типа.

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


Ключ порядка u

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


Ключ порядка v

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Имя вертикального идентификатора

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Пользовательское имя искажения

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Длина заголовка искажения.

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Длина заголовка искажения.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


Ключ warp. Также название класса warp по умолчанию.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Имя отсутствующего искажения

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


Ключ перспективы искажения

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


Другой параметр перспективы искажения

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


Ключ вращения искажения

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


Ключ стиля искажения

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


Ключ значения искажения

### WidthKey_internalized {#WidthKey-internalized}
```
public static final String WidthKey_internalized
```


Ключ ширины

### YouCannotAccessCropPropertyMessage_internalized {#YouCannotAccessCropPropertyMessage-internalized}
```
public static final String YouCannotAccessCropPropertyMessage_internalized
```


Вы не можете получить доступ к свойству Crop

### YouCannotSetCompIdPropertyMessage_internalized {#YouCannotSetCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetCompIdPropertyMessage_internalized
```


Вы не можете установить свойство CompId

### YouCannotSetCompPropertyMessage_internalized {#YouCannotSetCompPropertyMessage-internalized}
```
public static final String YouCannotSetCompPropertyMessage_internalized
```


Вы не можете установить свойство Comp

### YouCannotSetOriginalCompIdPropertyMessage_internalized {#YouCannotSetOriginalCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetOriginalCompIdPropertyMessage_internalized
```


Вы не можете установить свойство OriginalCompId

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Нулевой символ.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Лицензия предприятия.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Проверяет, что указанное фактическое значение равно ожидаемому значению.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| actualValue | java.lang.Object | Фактическое значение. |
| expectedValue | java.lang.Object | Ожидаемое значение. |
| message | java.lang.String | Сообщение. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Проверяет и устанавливает, является ли ресурс специфичным для PSB. Некоторые ресурсы пока не распознаются, но у нас есть полный список ресурсов, специфичных для PSB, которые изменяют своё поведение при сохранении. Поэтому нам необходимо проверять это хотя бы в UnknownResource.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ. |

### convertListStructureToDoubleArray_internalized(ListStructure list) {#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-}
```
public static double[] convertListStructureToDoubleArray_internalized(ListStructure list)
```


Преобразует структуру списка в массив double.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| list | [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) | Экземпляр ListStructure. |

**Returns:**
double[] - созданный массив double[].
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Получает или задает политику сглаживания данных слоя смарт‑объекта в изображении PSD.

Значение: Политика сглаживания данных слоя смарт-объекта.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Получает или задает положение снизу размещённого слоя в изображении PSD.

Значение: Нижнее расположение размещённого слоя.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Получает или задает границы размещённого слоя в файле PSD.

Значение: Границы размещённого слоя.

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


Получает или задает значение компоновки данных слоя смарт-объекта в файле PSD.  Слойные компоновки в смарт-объектах

Значение: Значение компоновки, равно -1, если отсутствует.

**Returns:**
int
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Получает или задает ID текущей выбранной компоновки (comp) для дочернего документа, который будет -1, если ничего не выбрано. Компоновки — это составные части макета страницы, которые дизайнеры могут создавать. С помощью слойных компоновок вы можете создавать, управлять и просматривать несколько вариантов макета в одном файле Adobe\ufffd Photoshop\ufffd. Слойная компоновка — это снимок состояния панели Layers. Слойные компоновки сохраняют три типа параметров слоя, но это свойство получает идентификатор выбора Layer Comp для смарт-объекта в файле PSD.  Слойные компоновки в смарт-объектах

Значение: ID текущей выбранной компоновки (comp) для дочернего документа в изображении PSD, который будет -1, если ничего не выбрано.

**Returns:**
int
### getCrop() {#getCrop--}
```
public final int getCrop()
```


Получает или задает обрезку данных слоя смарт‑объекта в изображении PSD.

Значение: Значение обрезки информации размещённого слоя.

**Returns:**
int
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Получает или задает тип единицы измерения по умолчанию для назначенных значений, таких как Left, Top, Right, Bottom, TransformMatrix.

Значение: Тип единицы измерения по умолчанию.

**Returns:**
int
### getDurationDenominator() {#getDurationDenominator--}
```
public final int getDurationDenominator()
```


Получает или задает знаменатель длительности.

Значение: Знаменатель длительности.

**Returns:**
int
### getDurationNumerator() {#getDurationNumerator--}
```
public final int getDurationNumerator()
```


Получает или задает числитель длительности.

Значение: Числитель длительности.

**Returns:**
int
### getFrameCount() {#getFrameCount--}
```
public final int getFrameCount()
```


Получает или задает количество кадров данных слоя смарт‑объекта в файле PSD.

Значение: Количество кадров в информации размещённого слоя.

**Returns:**
int
### getFrameStepDenominator() {#getFrameStepDenominator--}
```
public final int getFrameStepDenominator()
```


Получает или задает знаменатель шага кадра.

Значение: Знаменатель шага кадра.

**Returns:**
int
### getFrameStepNumerator() {#getFrameStepNumerator--}
```
public final int getFrameStepNumerator()
```


Получает или задает числитель шага кадра.

Значение: Числитель шага кадра.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Получает или задает заголовок.

Значение: Заголовок.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Получает или задает высоту.

Значение: Высота.

**Returns:**
double
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Получает или задает единицу измерения горизонтальных точек сетки.

Значение: Единица измерения горизонтальных точек сетки.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD.

Значение: Горизонтальные точки сетки размещённого слоя.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Получает или задает элементы дескриптора данных слоя смарт‑объекта в файле PSD.

Value: Элементы дескриптора информации о размещённом слое.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Получает ключ ресурса слоя.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Получает или задает положение слева размещённого слоя в файле PSD.

Значение: Левая позиция размещённого слоя.

**Returns:**
double
### getLength() {#getLength--}
```
public int getLength()
```


Получает длину ресурса смарт‑объекта в байтах.

**Returns:**
int
### getNonAffineTransformMatrix() {#getNonAffineTransformMatrix--}
```
public final double[] getNonAffineTransformMatrix()
```


Получает или задает неаффинную матрицу преобразования данных слоя смарт-объекта в файле PSD.

Value: Неаффинная матрица преобразования слоя смарт‑объекта.

**Returns:**
double[]
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Получает исходный ID текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. Это свойство получает исходный идентификатор выбора Comp слоя для смарт‑объекта в файле PSD.  Layer comps in Smart Objects

Value: Исходный ID текущего выбранного компа для дочернего документа в изображении PSD, который будет -1, если ничего не выбрано.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Получает или задает номер страницы данных слоя смарт-объекта в файле PSD.

Value: Номер страницы данных слоя смарт‑объекта.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Получает или задает значение перспективы размещённого слоя в файле PSD.

Значение: Значение перспективы размещённого слоя.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Получает или задает другое значение перспективы размещённого слоя в файле PSD.

Значение: Другое значение перспективы размещённого слоя.

**Returns:**
double
### getPlacedId() {#getPlacedId--}
```
public final UUID getPlacedId()
```


Получает или задает уникальный идентификатор этих данных слоя смарт-объекта в изображении PSD.

Value: Уникальный идентификатор этого ресурса слоя смарт‑объекта.

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


Получает или задает тип данных слоя смарт-объекта в файле PSD.

Value: Тип данных слоя смарт‑объекта.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Получает длину префикса. Значение по умолчанию — 12 для ресурсов 8BIM и 16 для 8B64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| psdVersion | int | Версия PSD. |

**Returns:**
int — длина префикса.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений.

**Returns:**
int
### getResolution() {#getResolution--}
```
public final double getResolution()
```


Получает или задает разрешение данных слоя смарт-объекта в файле PSD.

Value: Разрешение слоя смарт‑объекта.

**Returns:**
double
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


Получает или задает единицу измерения разрешения данных слоя смарт-объекта в файле PSD.

Value: Единица измерения разрешения слоя смарт‑объекта.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Получает или задает положение справа размещённого слоя в файле PSD.

Значение: Правая позиция размещённого слоя.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает подпись ресурса слоя.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Получает или задает положение сверху размещённого слоя в изображении PSD.

Значение: Верхняя позиция размещённого слоя.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Получает или задает общее количество страниц данных слоя смарт-объекта в файле PSD.

Value: Общее количество страниц данных слоя смарт‑объекта.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Получает или задает матрицу преобразования данных слоя смарт-объекта в файле PSD.

Value: Матрица преобразования данных слоя смарт‑объекта.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Получает или задает значение порядка U размещённого слоя в файле PSD.

Значение: Значение порядка U размещённого слоя.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Получает или задает глобальный уникальный идентификатор данных слоя смарт-объекта [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) в изображении PSD.

Value: Глобальный уникальный идентификатор данных слоя смарт‑объекта [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

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


Получает или задает значение порядка V размещённого слоя в файле PSD.

Значение: Значение порядка V размещённого слоя.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Получает или задает значение искажения размещённого слоя в изображении PSD.

Значение: Значение искажения размещённого слоя.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Получает версию размещённого слоя в файле PSD, обычно 3.

Значение: Версия размещённого слоя.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Получает или задает единицу измерения вертикальных точек сетки.

Значение: Единица измерения вертикальных точек сетки.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD.

Значение: Горизонтальные точки сетки размещённого слоя.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Получает или задает идентификатор класса.

Значение: Идентификатор класса.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Получает или задает название класса искажения.

Значение: Имя класса искажения.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Получает или задает версию дескриптора искажения.

Значение: Версия дескриптора искажения.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Элементы деформации.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Получает или задает версию искажения.

Значение: Версия искажения.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Получает или задает ширину.

Значение: Ширина.

**Returns:**
double
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Получает [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | java.lang.String | Имя ключа. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Получает значение, указывающее, имеет ли данный экземпляр единицы границ.

Значение:  true  если у этого экземпляра есть единицы границ; иначе,  false .

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### initializeBounds_internalized(Rectangle bounds) {#initializeBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void initializeBounds_internalized(Rectangle bounds)
```


Инициализирует границы и матрицы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы. |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Получает или задает значение, указывающее, является ли стиль искажения этого экземпляра пользовательским. Если true, содержит точки сетки. Если установить false, удаляет точки сетки.

Значение:  true  если размещённый слой имеет пользовательский стиль; в противном случае  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Определяет, является ли ресурс специфичным для PSB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ ресурса. |

**Returns:**
boolean —  true  если ресурс специфичен для PSB; иначе,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB.

Значение:  true  если этот экземпляр является ресурсом, специфичным для PSB; иначе,  false .

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Получает или задает значение, указывающее, является ли ориентация вращения данного экземпляра горизонтальной.

Значение:  true  если ориентация вращения горизонтальна; в противном случае  false .

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


Сохраняет ресурс смарт-объекта в указанный потоковый контейнер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psdVersion | int | Версия PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Сохраняет пользовательский заголовок ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| подпись | int | Подпись. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Сохраняет подпись заголовка, идентификатор и длину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| подпись | int | Подпись. |
| isLengthLong | boolean | если установлено значение  true , длина считается длинной. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Получает или задает политику сглаживания данных слоя смарт‑объекта в изображении PSD.

Значение: Политика сглаживания данных слоя смарт-объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Получает или задает положение снизу размещённого слоя в изображении PSD.

Значение: Нижнее расположение размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Получает или задает границы размещённого слоя в файле PSD.

Значение: Границы размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setComp(int value) {#setComp-int-}
```
public final void setComp(int value)
```


Получает или задает значение компоновки данных слоя смарт-объекта в файле PSD.  Слойные компоновки в смарт-объектах

Значение: Значение компоновки, равно -1, если отсутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Получает или задает ID текущей выбранной компоновки (comp) для дочернего документа, который будет -1, если ничего не выбрано. Компоновки — это составные части макета страницы, которые дизайнеры могут создавать. С помощью слойных компоновок вы можете создавать, управлять и просматривать несколько вариантов макета в одном файле Adobe\ufffd Photoshop\ufffd. Слойная компоновка — это снимок состояния панели Layers. Слойные компоновки сохраняют три типа параметров слоя, но это свойство получает идентификатор выбора Layer Comp для смарт-объекта в файле PSD.  Слойные компоновки в смарт-объектах

Значение: ID текущей выбранной компоновки (comp) для дочернего документа в изображении PSD, который будет -1, если ничего не выбрано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setCrop(int value) {#setCrop-int-}
```
public final void setCrop(int value)
```


Получает или задает обрезку данных слоя смарт‑объекта в изображении PSD.

Значение: Значение обрезки информации размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Получает или задает значение, указывающее, является ли стиль искажения этого экземпляра пользовательским. Если true, содержит точки сетки. Если установить false, удаляет точки сетки.

Значение:  true  если размещённый слой имеет пользовательский стиль; в противном случае  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Получает или задает тип единицы измерения по умолчанию для назначенных значений, таких как Left, Top, Right, Bottom, TransformMatrix.

Значение: Тип единицы измерения по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDurationDenominator(int value) {#setDurationDenominator-int-}
```
public final void setDurationDenominator(int value)
```


Получает или задает знаменатель длительности.

Значение: Знаменатель длительности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDurationNumerator(int value) {#setDurationNumerator-int-}
```
public final void setDurationNumerator(int value)
```


Получает или задает числитель длительности.

Значение: Числитель длительности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFrameCount(int value) {#setFrameCount-int-}
```
public final void setFrameCount(int value)
```


Получает или задает количество кадров данных слоя смарт‑объекта в файле PSD.

Значение: Количество кадров в информации размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFrameStepDenominator(int value) {#setFrameStepDenominator-int-}
```
public final void setFrameStepDenominator(int value)
```


Получает или задает знаменатель шага кадра.

Значение: Знаменатель шага кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFrameStepNumerator(int value) {#setFrameStepNumerator-int-}
```
public final void setFrameStepNumerator(int value)
```


Получает или задает числитель шага кадра.

Значение: Числитель шага кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Получает или задает заголовок.

Значение: Заголовок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Получает или задает высоту.

Значение: Высота.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Получает или задает единицу измерения горизонтальных точек сетки.

Значение: Единица измерения горизонтальных точек сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD.

Значение: Горизонтальные точки сетки размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Получает или задает элементы дескриптора данных слоя смарт‑объекта в файле PSD.

Value: Элементы дескриптора информации о размещённом слое.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Получает или задает положение слева размещённого слоя в файле PSD.

Значение: Левая позиция размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setNonAffineTransformMatrix(double[] value) {#setNonAffineTransformMatrix-double---}
```
public final void setNonAffineTransformMatrix(double[] value)
```


Получает или задает неаффинную матрицу преобразования данных слоя смарт-объекта в файле PSD.

Value: Неаффинная матрица преобразования слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setOriginalCompId_internalized(int value) {#setOriginalCompId-internalized-int-}
```
public final void setOriginalCompId_internalized(int value)
```


Получает исходный ID текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. Это свойство получает исходный идентификатор выбора Comp слоя для смарт‑объекта в файле PSD.  Layer comps in Smart Objects

Value: Исходный ID текущего выбранного компа для дочернего документа в изображении PSD, который будет -1, если ничего не выбрано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Получает или задает номер страницы данных слоя смарт-объекта в файле PSD.

Value: Номер страницы данных слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Получает или задает значение перспективы размещённого слоя в файле PSD.

Значение: Значение перспективы размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Получает или задает другое значение перспективы размещённого слоя в файле PSD.

Значение: Другое значение перспективы размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public final void setPlacedId(UUID value)
```


Получает или задает уникальный идентификатор этих данных слоя смарт-объекта в изображении PSD.

Value: Уникальный идентификатор этого ресурса слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID |  |

### setPlacedId_internalized(System.Guid value) {#setPlacedId-internalized-com.aspose.ms.System.Guid-}
```
public final void setPlacedId_internalized(System.Guid value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Guid |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Получает или задает тип данных слоя смарт-объекта в файле PSD.

Value: Тип данных слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setResolution(double value) {#setResolution-double-}
```
public final void setResolution(double value)
```


Получает или задает разрешение данных слоя смарт-объекта в файле PSD.

Value: Разрешение слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public final void setResolutionUnit(int value)
```


Получает или задает единицу измерения разрешения данных слоя смарт-объекта в файле PSD.

Value: Единица измерения разрешения слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Получает или задает положение справа размещённого слоя в файле PSD.

Значение: Правая позиция размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Получает или задает значение, указывающее, является ли ориентация вращения данного экземпляра горизонтальной.

Значение:  true  если ориентация вращения горизонтальна; в противном случае  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Получает или задает положение сверху размещённого слоя в изображении PSD.

Значение: Верхняя позиция размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Получает или задает общее количество страниц данных слоя смарт-объекта в файле PSD.

Value: Общее количество страниц данных слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Получает или задает матрицу преобразования данных слоя смарт-объекта в файле PSD.

Value: Матрица преобразования данных слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Получает или задает значение порядка U размещённого слоя в файле PSD.

Значение: Значение порядка U размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Получает или задает глобальный уникальный идентификатор данных слоя смарт-объекта [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) в изображении PSD.

Value: Глобальный уникальный идентификатор данных слоя смарт‑объекта [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Получает или задает значение порядка V размещённого слоя в файле PSD.

Значение: Значение порядка V размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Получает или задает значение искажения размещённого слоя в изображении PSD.

Значение: Значение искажения размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Получает версию размещённого слоя в файле PSD, обычно 3.

Значение: Версия размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Получает или задает единицу измерения вертикальных точек сетки.

Значение: Единица измерения вертикальных точек сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD.

Значение: Горизонтальные точки сетки размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Получает или задает идентификатор класса.

Значение: Идентификатор класса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Получает или задает название класса искажения.

Значение: Имя класса искажения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Получает или задает версию дескриптора искажения.

Значение: Версия дескриптора искажения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Получает или задает версию искажения.

Значение: Версия искажения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Получает или задает ширину.

Значение: Ширина.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает объект String, представляющий этот экземпляр.

**Returns:**
java.lang.String — объект String, представляющий этот экземпляр.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

