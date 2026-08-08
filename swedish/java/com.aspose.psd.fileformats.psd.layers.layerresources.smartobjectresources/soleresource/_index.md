---
title: "SoLeResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar klassen SoLeResource som innehåller information om ett smart objekt‑lager i en PSD-fil."
type: docs
weight: 16
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
```
public class SoLeResource extends SmartObjectResource
```

Definierar klassen **SoLeResource** som innehåller information om ett smartobjektlager i en PSD-fil. Den används för att stödja smarta objektlager med externa fillänkar i Adobe\ufffd Photoshop\ufffd‑bilder.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)](#SoLeResource-java.util.UUID-boolean-boolean-) | Initierar en ny instans av klassen [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource). |
| [SoLeResource()](#SoLeResource--) | Initierar en ny instans av klassen [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [AntiAliasPolicyKey_internalized](#AntiAliasPolicyKey-internalized) | Nyckeln för anti-alias-policy |
| [BottomKey_internalized](#BottomKey-internalized) | Den nedre nyckeln |
| [BoundsKey_internalized](#BoundsKey-internalized) | Gränsnyckeln |
| [CompIdKey_internalized](#CompIdKey-internalized) | Nyckelnamnet för CompID |
| [CompInfoKey_internalized](#CompInfoKey-internalized) | Nyckelnamnet för kompinformation |
| [CompKey_internalized](#CompKey-internalized) | Comp-nyckeln |
| [CompNoneValue_internalized](#CompNoneValue-internalized) | Comp-värdet som betyder 'none' |
| [CropKey_internalized](#CropKey-internalized) | Crop-nyckeln |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Det anpassade kuvertförvrängningsnamnet |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Det förvalda förvrängningsklassnamnet |
| [DenominatorKey_internalized](#DenominatorKey-internalized) | Nämnare-nyckeln |
| [DurationKey_internalized](#DurationKey-internalized) | Varaktighetsnyckeln |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Det förvalda förvrängningsklassnamnet |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Den förväntade versionen av förvrängningsbeskrivaren |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Den förväntade warp-versionen |
| [FrameCountKey_internalized](#FrameCountKey-internalized) | Bildruteantal-nyckeln |
| [FrameStepKey_internalized](#FrameStepKey-internalized) | Bildrutesteg-nyckeln |
| [HeightKey_internalized](#HeightKey-internalized) | Höjdsnyckeln |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Det horisontella identifierarnamnet |
| [IdentKey_internalized](#IdentKey-internalized) | Unik identifierar-nyckeln |
| [ItemsPropertyCannotBeNull_internalized](#ItemsPropertyCannotBeNull-internalized) | Items-egenskapen får inte vara null |
| [LeftKey_internalized](#LeftKey-internalized) | Den vänstra nyckeln |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Namnet på nyckeln för mesh-punkter |
| [NonAffineTransformKey_internalized](#NonAffineTransformKey-internalized) | Icke-affin transform-nyckeln |
| [NullClassId_internalized](#NullClassId-internalized) | Null-klassidentifieraren |
| [NumeratorKey_internalized](#NumeratorKey-internalized) | Täljare-nyckeln |
| [OptionalKeys_internalized](#OptionalKeys-internalized) | Samlingen av valfria nycklar |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Namnet på orienteringsidentifieraren |
| [OriginalCompIdKey_internalized](#OriginalCompIdKey-internalized) | Nyckelnamnet för den ursprungliga CompID |
| [PageNumberKey_internalized](#PageNumberKey-internalized) | Sidnummer-nyckeln |
| [PlacedIdKey_internalized](#PlacedIdKey-internalized) | Placering-identifierar-nyckeln |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Det förväntade versionsvärdet |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB‑huvudversionen |
| [PsbResourceSignature](#PsbResourceSignature) | Den PSB‑specifika resurs‑signaturen. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD‑huvudversionen. |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Namnet på identifieraren för klassen rational point |
| [ResolutionKey_internalized](#ResolutionKey-internalized) | Upplösningsnyckeln |
| [ResourceSignature](#ResourceSignature) | Den gemensamma resurs‑signaturen. |
| [RightKey_internalized](#RightKey-internalized) | Den högra nyckeln |
| [SizeKey_internalized](#SizeKey-internalized) | Storleksnyckeln |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | Storleken på double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | Storleken på int |
| [SmartVersionValue_internalized](#SmartVersionValue-internalized) | Det förväntade värdet för smart objektresursversionen. |
| [TopKey_internalized](#TopKey-internalized) | Den övre nyckeln |
| [TotalPagesKey_internalized](#TotalPagesKey-internalized) | Totalt sidantal-nyckeln |
| [TransformKey_internalized](#TransformKey-internalized) | Transformationsnyckeln |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Antalet transformvärden |
| [TypeKey_internalized](#TypeKey-internalized) | Typnyckeln |
| [TypeToolKey](#TypeToolKey) | Typverktygsinfo-nyckeln: 'SoLE'. |
| [TypeValue_internalized](#TypeValue-internalized) | Det förväntade typvärdet. |
| [UOrderKey_internalized](#UOrderKey-internalized) | U-ordningsnyckeln |
| [VOrderKey_internalized](#VOrderKey-internalized) | V-ordningsnyckeln |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Namnet på vertikal identifierare |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Det anpassade warp-namnet |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Warp-headerns längd. |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Warp-headerns längd. |
| [WarpKey_internalized](#WarpKey-internalized) | Warp-nyckeln. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Namnet på warp none |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Warp-perspektivnyckeln |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Warp-perspektiv annat |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Warp-rotationsnyckeln |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Warp-stilsnyckeln |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Warp-värdesnyckeln |
| [WidthKey_internalized](#WidthKey-internalized) | Bredd-nyckeln |
| [YouCannotAccessCropPropertyMessage_internalized](#YouCannotAccessCropPropertyMessage-internalized) | Du kan inte komma åt Crop-egenskapen |
| [YouCannotSetCompIdPropertyMessage_internalized](#YouCannotSetCompIdPropertyMessage-internalized) | Du kan inte ange CompId-egenskapen |
| [YouCannotSetCompPropertyMessage_internalized](#YouCannotSetCompPropertyMessage-internalized) | Du kan inte ange Comp-egenskap meddelande |
| [YouCannotSetOriginalCompIdPropertyMessage_internalized](#YouCannotSetOriginalCompIdPropertyMessage-internalized) | Du kan inte ange OriginalCompId-egenskap meddelande |
| [ZeroChar_internalized](#ZeroChar-internalized) | Nolltecknet. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Venture‑licensen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Påstår att det specificerade faktiska värdet är lika med det förväntade värdet. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kontrollerar och sätter om resursen är PSB‑specifik. |
| [convertListStructureToDoubleArray_internalized(ListStructure list)](#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-) | Konverterar liststrukturen till en dubbelarray. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Hämtar eller anger anti-alias-policyn för smartobjektlagrets data i PSD-bilden. |
| [getBottom()](#getBottom--) | Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden. |
| [getBounds()](#getBounds--) | Hämtar eller anger gränserna för det placerade lagret i PSD‑filen. |
| [getClass()](#getClass--) |  |
| [getComp()](#getComp--) | Hämtar eller anger comp-värdet för smartobjektlagrets data i PSD-filen. |
| [getCompId()](#getCompId--) | Hämtar eller anger ID för den för närvarande valda komponenten för underdokumentet, vilket blir -1 om ingen är vald. |
| [getCrop()](#getCrop--) | Hämtar eller anger beskärningen för smartobjektlagrets data i PSD-bilden. |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Hämtar eller anger standardenhetstypen för tilldelade värden såsom Left, Top, Right, Bottom, TransformMatrix. |
| [getDurationDenominator()](#getDurationDenominator--) | Hämtar eller anger varaktighetens nämnare. |
| [getDurationNumerator()](#getDurationNumerator--) | Hämtar eller anger varaktighetens täljare. |
| [getFrameCount()](#getFrameCount--) | Hämtar eller anger bildruteantalet för smartobjektlagrets data i PSD-filen. |
| [getFrameStepDenominator()](#getFrameStepDenominator--) | Hämtar eller anger bildrutesstegets nämnare. |
| [getFrameStepNumerator()](#getFrameStepNumerator--) | Hämtar eller anger bildrutesstegets täljare. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Hämtar eller anger måttenheten för de horisontella nätpunkterna. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [getItems()](#getItems--) | Hämtar eller anger deskriptorelementen för smartobjektlagrets data i PSD-filen. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLeft()](#getLeft--) | Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen. |
| [getLength()](#getLength--) | Hämtar smartobjektresursens längd i byte. |
| [getNonAffineTransformMatrix()](#getNonAffineTransformMatrix--) | Hämtar eller anger den icke-affina transformmatrisen för smartobjektlagrets data i PSD-filen. |
| [getOriginalCompId()](#getOriginalCompId--) | Hämtar det ursprungliga ID:t för den för närvarande valda Comp för underdokumentet, vilket blir -1 om ingen är vald. |
| [getPageNumber()](#getPageNumber--) | Hämtar eller anger sidnumret för smartobjektlagrets data i PSD-filen. |
| [getPerspective()](#getPerspective--) | Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen. |
| [getPlacedId()](#getPlacedId--) | Hämtar eller anger den unika identifieraren för detta smartobjektlagrets data i PSD-bilden. |
| [getPlacedId_internalized()](#getPlacedId-internalized--) |  |
| [getPlacedLayerType()](#getPlacedLayerType--) | Hämtar eller anger typen av smartobjektlagrets data i PSD-filen. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getResolution()](#getResolution--) | Hämtar eller anger upplösningen för smartobjektlagrets data i PSD-filen. |
| [getResolutionUnit()](#getResolutionUnit--) | Hämtar eller anger enheten för upplösningsmått för smartobjektlagrets data i PSD-filen. |
| [getRight()](#getRight--) | Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getTop()](#getTop--) | Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden. |
| [getTotalPages()](#getTotalPages--) | Hämtar eller anger det totala sidantalet för smartobjektlagrets data i PSD-filen. |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger transformmatrisen för smartobjektlagrets data i PSD-filen. |
| [getUOrder()](#getUOrder--) | Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [getUniqueId()](#getUniqueId--) | Hämtar eller anger den globala unika identifieraren för smartobjektlagrets data [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) i PSD-bilden. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [getValue()](#getValue--) | Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden. |
| [getVersion()](#getVersion--) | Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Hämtar eller anger måttenheten för de vertikala nätpunkterna. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Hämtar eller anger klass‑ID. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Hämtar eller anger warp‑klassnamnet. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Hämtar eller anger warp‑beskrivarversionen. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Warp-objekten. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Hämtar eller anger warp‑versionen. |
| [getWidth()](#getWidth--) | Hämtar eller anger bredden. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Hämtar [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) på det angivna indexet. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Hämtar ett värde som indikerar om detta objekt har gränsenheter. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeBounds_internalized(Rectangle bounds)](#initializeBounds-internalized-com.aspose.psd.Rectangle-) | Initierar gränserna och matriserna. |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | Hämtar eller anger ett värde som indikerar om detta objekts warp‑stil är anpassad. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Hämtar eller anger ett värde som indikerar om detta objekts roteringsorientering är horisontell. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar smartobjektresursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Hämtar eller anger anti-alias-policyn för smartobjektlagrets data i PSD-bilden. |
| [setBottom(double value)](#setBottom-double-) | Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Hämtar eller anger gränserna för det placerade lagret i PSD‑filen. |
| [setComp(int value)](#setComp-int-) | Hämtar eller anger comp-värdet för smartobjektlagrets data i PSD-filen. |
| [setCompId(int value)](#setCompId-int-) | Hämtar eller anger ID för den för närvarande valda komponenten för underdokumentet, vilket blir -1 om ingen är vald. |
| [setCrop(int value)](#setCrop-int-) | Hämtar eller anger beskärningen för smartobjektlagrets data i PSD-bilden. |
| [setCustom(boolean value)](#setCustom-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekts warp‑stil är anpassad. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Hämtar eller anger standardenhetstypen för tilldelade värden såsom Left, Top, Right, Bottom, TransformMatrix. |
| [setDurationDenominator(int value)](#setDurationDenominator-int-) | Hämtar eller anger varaktighetens nämnare. |
| [setDurationNumerator(int value)](#setDurationNumerator-int-) | Hämtar eller anger varaktighetens täljare. |
| [setFrameCount(int value)](#setFrameCount-int-) | Hämtar eller anger bildruteantalet för smartobjektlagrets data i PSD-filen. |
| [setFrameStepDenominator(int value)](#setFrameStepDenominator-int-) | Hämtar eller anger bildrutesstegets nämnare. |
| [setFrameStepNumerator(int value)](#setFrameStepNumerator-int-) | Hämtar eller anger bildrutesstegets täljare. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setHeight(double value)](#setHeight-double-) | Hämtar eller anger höjden. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Hämtar eller anger måttenheten för de horisontella nätpunkterna. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Hämtar eller anger deskriptorelementen för smartobjektlagrets data i PSD-filen. |
| [setLeft(double value)](#setLeft-double-) | Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen. |
| [setNonAffineTransformMatrix(double[] value)](#setNonAffineTransformMatrix-double---) | Hämtar eller anger den icke-affina transformmatrisen för smartobjektlagrets data i PSD-filen. |
| [setOriginalCompId_internalized(int value)](#setOriginalCompId-internalized-int-) | Hämtar det ursprungliga ID:t för den för närvarande valda Comp för underdokumentet, vilket blir -1 om ingen är vald. |
| [setPageNumber(int value)](#setPageNumber-int-) | Hämtar eller anger sidnumret för smartobjektlagrets data i PSD-filen. |
| [setPerspective(double value)](#setPerspective-double-) | Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | Hämtar eller anger den unika identifieraren för detta smartobjektlagrets data i PSD-bilden. |
| [setPlacedId_internalized(System.Guid value)](#setPlacedId-internalized-com.aspose.ms.System.Guid-) |  |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Hämtar eller anger typen av smartobjektlagrets data i PSD-filen. |
| [setResolution(double value)](#setResolution-double-) | Hämtar eller anger upplösningen för smartobjektlagrets data i PSD-filen. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Hämtar eller anger enheten för upplösningsmått för smartobjektlagrets data i PSD-filen. |
| [setRight(double value)](#setRight-double-) | Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekts roteringsorientering är horisontell. |
| [setTop(double value)](#setTop-double-) | Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden. |
| [setTotalPages(int value)](#setTotalPages-int-) | Hämtar eller anger det totala sidantalet för smartobjektlagrets data i PSD-filen. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Hämtar eller anger transformmatrisen för smartobjektlagrets data i PSD-filen. |
| [setUOrder(int value)](#setUOrder-int-) | Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Hämtar eller anger den globala unika identifieraren för smartobjektlagrets data [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) i PSD-bilden. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [setValue(double value)](#setValue-double-) | Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden. |
| [setVersion(int value)](#setVersion-int-) | Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Hämtar eller anger måttenheten för de vertikala nätpunkterna. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Hämtar eller anger klass‑ID. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Hämtar eller anger warp‑klassnamnet. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Hämtar eller anger warp‑beskrivarversionen. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Hämtar eller anger warp‑versionen. |
| [setWidth(double value)](#setWidth-double-) | Hämtar eller anger bredden. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo) {#SoLeResource-java.util.UUID-boolean-boolean-}
```
public SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)
```


Initierar en ny instans av klassen [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | java.util.UUID | Den unika identifieraren för den placerade lagerdata [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource). |
| isCustom | boolean | om den är satt till  true  [är anpassad]. |
| hasCompInfo | boolean | om den är satt till  true  [har kompositionsinformation]. |

### SoLeResource() {#SoLeResource--}
```
public SoLeResource()
```


Initierar en ny instans av klassen [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource).

### AntiAliasPolicyKey_internalized {#AntiAliasPolicyKey-internalized}
```
public static final String AntiAliasPolicyKey_internalized
```


Nyckeln för anti-alias-policy

### BottomKey_internalized {#BottomKey-internalized}
```
public static final String BottomKey_internalized
```


Den nedre nyckeln

### BoundsKey_internalized {#BoundsKey-internalized}
```
public static final String BoundsKey_internalized
```


Gränsnyckeln

### CompIdKey_internalized {#CompIdKey-internalized}
```
public static final String CompIdKey_internalized
```


Nyckelnamnet för CompID

### CompInfoKey_internalized {#CompInfoKey-internalized}
```
public static final String CompInfoKey_internalized
```


Nyckelnamnet för kompinformation

### CompKey_internalized {#CompKey-internalized}
```
public static final String CompKey_internalized
```


Comp-nyckeln

### CompNoneValue_internalized {#CompNoneValue-internalized}
```
public static final int CompNoneValue_internalized
```


Comp-värdet som betyder 'none'

### CropKey_internalized {#CropKey-internalized}
```
public static final String CropKey_internalized
```


Crop-nyckeln

### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Det anpassade kuvertförvrängningsnamnet

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Det förvalda förvrängningsklassnamnet

### DenominatorKey_internalized {#DenominatorKey-internalized}
```
public static final String DenominatorKey_internalized
```


Nämnare-nyckeln

### DurationKey_internalized {#DurationKey-internalized}
```
public static final String DurationKey_internalized
```


Varaktighetsnyckeln

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Det förvalda förvrängningsklassnamnet

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


Den förväntade versionen av förvrängningsbeskrivaren

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


Den förväntade warp-versionen

### FrameCountKey_internalized {#FrameCountKey-internalized}
```
public static final String FrameCountKey_internalized
```


Bildruteantal-nyckeln

### FrameStepKey_internalized {#FrameStepKey-internalized}
```
public static final String FrameStepKey_internalized
```


Bildrutesteg-nyckeln

### HeightKey_internalized {#HeightKey-internalized}
```
public static final String HeightKey_internalized
```


Höjdsnyckeln

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Det horisontella identifierarnamnet

### IdentKey_internalized {#IdentKey-internalized}
```
public static final String IdentKey_internalized
```


Unik identifierar-nyckeln

### ItemsPropertyCannotBeNull_internalized {#ItemsPropertyCannotBeNull-internalized}
```
public static final String ItemsPropertyCannotBeNull_internalized
```


Items-egenskapen får inte vara null

### LeftKey_internalized {#LeftKey-internalized}
```
public static final String LeftKey_internalized
```


Den vänstra nyckeln

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Namnet på nyckeln för mesh-punkter

### NonAffineTransformKey_internalized {#NonAffineTransformKey-internalized}
```
public static final String NonAffineTransformKey_internalized
```


Icke-affin transform-nyckeln

### NullClassId_internalized {#NullClassId-internalized}
```
public static final String NullClassId_internalized
```


Null-klassidentifieraren

### NumeratorKey_internalized {#NumeratorKey-internalized}
```
public static final String NumeratorKey_internalized
```


Täljare-nyckeln

### OptionalKeys_internalized {#OptionalKeys-internalized}
```
public static final String[] OptionalKeys_internalized
```


Samlingen av valfria nycklar

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Namnet på orienteringsidentifieraren

### OriginalCompIdKey_internalized {#OriginalCompIdKey-internalized}
```
public static final String OriginalCompIdKey_internalized
```


Nyckelnamnet för den ursprungliga CompID

### PageNumberKey_internalized {#PageNumberKey-internalized}
```
public static final String PageNumberKey_internalized
```


Sidnummer-nyckeln

### PlacedIdKey_internalized {#PlacedIdKey-internalized}
```
public static final String PlacedIdKey_internalized
```


Placering-identifierar-nyckeln

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


Det förväntade versionsvärdet

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB‑huvudversionen

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Den PSB‑specifika resurs‑signaturen.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD‑huvudversionen.

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Namnet på identifieraren för klassen rational point

### ResolutionKey_internalized {#ResolutionKey-internalized}
```
public static final String ResolutionKey_internalized
```


Upplösningsnyckeln

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Den gemensamma resurs‑signaturen.

### RightKey_internalized {#RightKey-internalized}
```
public static final String RightKey_internalized
```


Den högra nyckeln

### SizeKey_internalized {#SizeKey-internalized}
```
public static final String SizeKey_internalized
```


Storleksnyckeln

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


Storleken på double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


Storleken på int

### SmartVersionValue_internalized {#SmartVersionValue-internalized}
```
public static final int SmartVersionValue_internalized
```


Det förväntade värdet för smart objektresursversionen.

### TopKey_internalized {#TopKey-internalized}
```
public static final String TopKey_internalized
```


Den övre nyckeln

### TotalPagesKey_internalized {#TotalPagesKey-internalized}
```
public static final String TotalPagesKey_internalized
```


Totalt sidantal-nyckeln

### TransformKey_internalized {#TransformKey-internalized}
```
public static final String TransformKey_internalized
```


Transformationsnyckeln

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Antalet transformvärden

### TypeKey_internalized {#TypeKey-internalized}
```
public static final String TypeKey_internalized
```


Typnyckeln

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Typverktygsinfo-nyckeln: 'SoLE'.

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


Det förväntade typvärdet.

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


U-ordningsnyckeln

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


V-ordningsnyckeln

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Namnet på vertikal identifierare

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Det anpassade warp-namnet

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Warp-headerns längd.

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Warp-headerns längd.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


Warp‑nyckeln. Även standard‑warp‑klassnamnet.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Namnet på warp none

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


Warp-perspektivnyckeln

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


Warp-perspektiv annat

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


Warp-rotationsnyckeln

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


Warp-stilsnyckeln

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


Warp-värdesnyckeln

### WidthKey_internalized {#WidthKey-internalized}
```
public static final String WidthKey_internalized
```


Bredd-nyckeln

### YouCannotAccessCropPropertyMessage_internalized {#YouCannotAccessCropPropertyMessage-internalized}
```
public static final String YouCannotAccessCropPropertyMessage_internalized
```


Du kan inte komma åt Crop-egenskapen

### YouCannotSetCompIdPropertyMessage_internalized {#YouCannotSetCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetCompIdPropertyMessage_internalized
```


Du kan inte ange CompId-egenskapen

### YouCannotSetCompPropertyMessage_internalized {#YouCannotSetCompPropertyMessage-internalized}
```
public static final String YouCannotSetCompPropertyMessage_internalized
```


Du kan inte ange Comp-egenskap meddelande

### YouCannotSetOriginalCompIdPropertyMessage_internalized {#YouCannotSetOriginalCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetOriginalCompIdPropertyMessage_internalized
```


Du kan inte ange OriginalCompId-egenskap meddelande

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Nolltecknet.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Venture‑licensen.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Påstår att det specificerade faktiska värdet är lika med det förväntade värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| actualValue | java.lang.Object | Det faktiska värdet. |
| expectedValue | java.lang.Object | Det förväntade värdet. |
| meddelande | java.lang.String | Meddelandet. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Kontrollerar och anger om resursen är PSB-specifik. Vissa resurser känns inte igen för närvarande, men vi har en fullständig lista över PSB-specifika resurser som ändrar deras beteende vid sparning. Så vi måste åtminstone kontrollera detta i UnknownResource.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | int | Nyckeln. |

### convertListStructureToDoubleArray_internalized(ListStructure list) {#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-}
```
public static double[] convertListStructureToDoubleArray_internalized(ListStructure list)
```


Konverterar liststrukturen till en dubbelarray.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| list | [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) | Den  ListStructure  instansen. |

**Returns:**
double[] - Den skapade  double[]  arrayen.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Hämtar eller anger anti-alias-policyn för smartobjektlagrets data i PSD-bilden.

Värde: Den anti-aliaspolicyn för smartobjektlagrets data.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden.

Värde: Den nedre platsen för det placerade lagret.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Hämtar eller anger gränserna för det placerade lagret i PSD‑filen.

Värde: Gränserna för det placerade lagret.

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


Hämtar eller anger comp‑värdet för smartobjektlagrets data i PSD‑filen.  Layer comps i Smart Objects

Värde: Comp‑värdet, är -1 om inget.

**Returns:**
int
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Hämtar eller anger ID för den för närvarande valda comp‑en för underdokumentet, vilket blir -1 om ingen är vald. Comp‑ar är sammansättningar av en sidlayout som designers kan skapa. Med layer comps kan du skapa, hantera och visa flera versioner av en layout i en enda Adobe\ufffd Photoshop\ufffd‑fil. En layer comp är en ögonblicksbild av ett tillstånd i lagerpanelen. Layer comps sparar tre typer av lageralternativ men den här egenskapen hämtar Layer Comp‑urvalsidentifieraren för smartobjektlagret i PSD‑filen.  Layer comps i Smart Objects

Värde: ID för den för närvarande valda comp‑en för underdokumentet i PSD‑bilden, vilket blir -1 om ingen är vald.

**Returns:**
int
### getCrop() {#getCrop--}
```
public final int getCrop()
```


Hämtar eller anger beskärningen för smartobjektlagrets data i PSD-bilden.

Värde: Beskärningsvärdet för placerad lagerinformation.

**Returns:**
int
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Hämtar eller anger standardenhetstypen för tilldelade värden såsom Left, Top, Right, Bottom, TransformMatrix.

Värde: Standardmåttenhetstypen.

**Returns:**
int
### getDurationDenominator() {#getDurationDenominator--}
```
public final int getDurationDenominator()
```


Hämtar eller anger varaktighetens nämnare.

Värde: Varaktighetens nämnare.

**Returns:**
int
### getDurationNumerator() {#getDurationNumerator--}
```
public final int getDurationNumerator()
```


Hämtar eller anger varaktighetens täljare.

Värde: Varaktighetens täljare.

**Returns:**
int
### getFrameCount() {#getFrameCount--}
```
public final int getFrameCount()
```


Hämtar eller anger bildruteantalet för smartobjektlagrets data i PSD-filen.

Värde: Antalet ramar för placerad lagerinformation.

**Returns:**
int
### getFrameStepDenominator() {#getFrameStepDenominator--}
```
public final int getFrameStepDenominator()
```


Hämtar eller anger bildrutesstegets nämnare.

Värde: Ramstegets nämnare.

**Returns:**
int
### getFrameStepNumerator() {#getFrameStepNumerator--}
```
public final int getFrameStepNumerator()
```


Hämtar eller anger bildrutesstegets täljare.

Värde: Ramstegets täljare.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Hämtar eller anger rubriken.

Värde: Headern.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar eller anger höjden.

Värde: Höjden.

**Returns:**
double
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Hämtar eller anger måttenheten för de horisontella nätpunkterna.

Värde: Måttenheten för de horisontella nätpunkterna.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Hämtar eller anger deskriptorelementen för smartobjektlagrets data i PSD-filen.

Värde: Deskriptorelementen för placerad lagerinformation.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Hämtar lagrets resursnyckel.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen.

Värde: Den vänstra platsen för det placerade lagret.

**Returns:**
double
### getLength() {#getLength--}
```
public int getLength()
```


Hämtar smartobjektresursens längd i byte.

**Returns:**
int
### getNonAffineTransformMatrix() {#getNonAffineTransformMatrix--}
```
public final double[] getNonAffineTransformMatrix()
```


Hämtar eller anger den icke-affina transformmatrisen för smartobjektlagrets data i PSD-filen.

Värde: Den icke‑affina transformationsmatrisen för smartobjektlagret.

**Returns:**
double[]
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Hämtar det ursprungliga ID:t för den för närvarande valda Comp‑en för underdokumentet, vilket blir -1 om ingen är vald. Denna egenskap hämtar det ursprungliga lager‑Comp‑urvalsidentifieraren för smartobjektlagret i PSD‑filen.  Layer comps i Smart Objects

Värde: Det ursprungliga ID:t för den för närvarande valda comp‑en för underdokumentet i PSD‑bilden, vilket blir -1 om ingen är vald.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Hämtar eller anger sidnumret för smartobjektlagrets data i PSD-filen.

Värde: Sidnumret för smartobjektlagrets data.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Perspektivvärdet för det placerade lagret.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Det andra perspektivvärdet för det placerade lagret.

**Returns:**
double
### getPlacedId() {#getPlacedId--}
```
public final UUID getPlacedId()
```


Hämtar eller anger den unika identifieraren för detta smartobjektlagrets data i PSD-bilden.

Värde: Den unika identifieraren för denna smartobjektlagerresurs.

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


Hämtar eller anger typen av smartobjektlagrets data i PSD-filen.

Värde: Typen av smartobjektlagrets data.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Hämtar prefixlängden. Standardvärdet är 12 för 8BIM-resurser och 16 för 8B64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdVersion | int | PSD-versionen. |

**Returns:**
int - Prefixlängden.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Hämtar den minsta psd-version som krävs för lagerresursen. 0 indikerar inga begränsningar.

**Returns:**
int
### getResolution() {#getResolution--}
```
public final double getResolution()
```


Hämtar eller anger upplösningen för smartobjektlagrets data i PSD-filen.

Värde: Upplösningen för smartobjektlagret.

**Returns:**
double
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


Hämtar eller anger enheten för upplösningsmått för smartobjektlagrets data i PSD-filen.

Värde: Upplösningens måttenhet för smartobjektlagret.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen.

Värde: Den högra platsen för det placerade lagret.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden.

Värde: Den övre platsen för det placerade lagret.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Hämtar eller anger det totala sidantalet för smartobjektlagrets data i PSD-filen.

Värde: Det totala antalet sidor för smartobjektlagrets data.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Hämtar eller anger transformmatrisen för smartobjektlagrets data i PSD-filen.

Värde: Transformationsmatrisen för smartobjektlagrets data.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: U‑ordningsvärdet för det placerade lagret.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Hämtar eller anger den globala unika identifieraren för smartobjektlagrets data [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) i PSD-bilden.

Värde: Den globala unika identifieraren för smartobjektlagrets data [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

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


Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: V-ordningsvärdet för det placerade lagret.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden.

Värde: Förvrängningsvärdet för det placerade lagret.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3.

Värde: Versionen för det placerade lagret.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Hämtar eller anger måttenheten för de vertikala nätpunkterna.

Värde: Måttenheten för de vertikala nätpunkterna.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Hämtar eller anger klass‑ID.

Värde: Klass-ID:t.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Hämtar eller anger warp‑klassnamnet.

Värde: Förvrängningsklassens namn.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Hämtar eller anger warp‑beskrivarversionen.

Värde: Versionen för förvrängningsbeskrivaren.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Warp-objekten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Hämtar eller anger warp‑versionen.

Värde: Förvrängningsversionen.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar eller anger bredden.

Värde: Bredden.

**Returns:**
double
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Hämtar [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | java.lang.String | Nyckelnamnet. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Hämtar ett värde som indikerar om detta objekt har gränsenheter.

Värde:  true  om detta objekt har gränsenheter; annars  false .

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### initializeBounds_internalized(Rectangle bounds) {#initializeBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void initializeBounds_internalized(Rectangle bounds)
```


Initierar gränserna och matriserna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Gränserna. |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Hämtar eller anger ett värde som indikerar om detta objekts förvrängningsstil är anpassad. Om true innehåller den nätpunkter. Om den sätts till false raderas nätpunkterna.

Värde:  true  om det placerade lagret har anpassad stil; annars  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Bestämmer om resursen är PSB‑specifik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | int | Resursnyckeln. |

**Returns:**
boolean - true om resursen är PSB-specifik; annars false.
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs.

Värde: true om detta objekt är PSB-specifik resurs; annars false.

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Hämtar eller anger ett värde som indikerar om detta objekts roteringsorientering är horisontell.

Värde:  true  om rotationsorienteringen är horisontell; annars  false .

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


Sparar smartobjektresursen till den angivna strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psdVersion | int | PSD-versionen. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Sparar den anpassade resursrubriken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| signatur | int | Signaturen. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Sparar rubrikens signatur, identifierare och längd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| signatur | int | Signaturen. |
| isLengthLong | boolean | Om satt till true är längden lång. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Hämtar eller anger anti-alias-policyn för smartobjektlagrets data i PSD-bilden.

Värde: Den anti-aliaspolicyn för smartobjektlagrets data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden.

Värde: Den nedre platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Hämtar eller anger gränserna för det placerade lagret i PSD‑filen.

Värde: Gränserna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setComp(int value) {#setComp-int-}
```
public final void setComp(int value)
```


Hämtar eller anger comp‑värdet för smartobjektlagrets data i PSD‑filen.  Layer comps i Smart Objects

Värde: Comp‑värdet, är -1 om inget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Hämtar eller anger ID för den för närvarande valda comp‑en för underdokumentet, vilket blir -1 om ingen är vald. Comp‑ar är sammansättningar av en sidlayout som designers kan skapa. Med layer comps kan du skapa, hantera och visa flera versioner av en layout i en enda Adobe\ufffd Photoshop\ufffd‑fil. En layer comp är en ögonblicksbild av ett tillstånd i lagerpanelen. Layer comps sparar tre typer av lageralternativ men den här egenskapen hämtar Layer Comp‑urvalsidentifieraren för smartobjektlagret i PSD‑filen.  Layer comps i Smart Objects

Värde: ID för den för närvarande valda comp‑en för underdokumentet i PSD‑bilden, vilket blir -1 om ingen är vald.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCrop(int value) {#setCrop-int-}
```
public final void setCrop(int value)
```


Hämtar eller anger beskärningen för smartobjektlagrets data i PSD-bilden.

Värde: Beskärningsvärdet för placerad lagerinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekts förvrängningsstil är anpassad. Om true innehåller den nätpunkter. Om den sätts till false raderas nätpunkterna.

Värde:  true  om det placerade lagret har anpassad stil; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Hämtar eller anger standardenhetstypen för tilldelade värden såsom Left, Top, Right, Bottom, TransformMatrix.

Värde: Standardmåttenhetstypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDurationDenominator(int value) {#setDurationDenominator-int-}
```
public final void setDurationDenominator(int value)
```


Hämtar eller anger varaktighetens nämnare.

Värde: Varaktighetens nämnare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDurationNumerator(int value) {#setDurationNumerator-int-}
```
public final void setDurationNumerator(int value)
```


Hämtar eller anger varaktighetens täljare.

Värde: Varaktighetens täljare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFrameCount(int value) {#setFrameCount-int-}
```
public final void setFrameCount(int value)
```


Hämtar eller anger bildruteantalet för smartobjektlagrets data i PSD-filen.

Värde: Antalet ramar för placerad lagerinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFrameStepDenominator(int value) {#setFrameStepDenominator-int-}
```
public final void setFrameStepDenominator(int value)
```


Hämtar eller anger bildrutesstegets nämnare.

Värde: Ramstegets nämnare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFrameStepNumerator(int value) {#setFrameStepNumerator-int-}
```
public final void setFrameStepNumerator(int value)
```


Hämtar eller anger bildrutesstegets täljare.

Värde: Ramstegets täljare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Hämtar eller anger rubriken.

Värde: Headern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Hämtar eller anger höjden.

Värde: Höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Hämtar eller anger måttenheten för de horisontella nätpunkterna.

Värde: Måttenheten för de horisontella nätpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Hämtar eller anger deskriptorelementen för smartobjektlagrets data i PSD-filen.

Värde: Deskriptorelementen för placerad lagerinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen.

Värde: Den vänstra platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setNonAffineTransformMatrix(double[] value) {#setNonAffineTransformMatrix-double---}
```
public final void setNonAffineTransformMatrix(double[] value)
```


Hämtar eller anger den icke-affina transformmatrisen för smartobjektlagrets data i PSD-filen.

Värde: Den icke‑affina transformationsmatrisen för smartobjektlagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setOriginalCompId_internalized(int value) {#setOriginalCompId-internalized-int-}
```
public final void setOriginalCompId_internalized(int value)
```


Hämtar det ursprungliga ID:t för den för närvarande valda Comp‑en för underdokumentet, vilket blir -1 om ingen är vald. Denna egenskap hämtar det ursprungliga lager‑Comp‑urvalsidentifieraren för smartobjektlagret i PSD‑filen.  Layer comps i Smart Objects

Värde: Det ursprungliga ID:t för den för närvarande valda comp‑en för underdokumentet i PSD‑bilden, vilket blir -1 om ingen är vald.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Hämtar eller anger sidnumret för smartobjektlagrets data i PSD-filen.

Värde: Sidnumret för smartobjektlagrets data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Perspektivvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Det andra perspektivvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public final void setPlacedId(UUID value)
```


Hämtar eller anger den unika identifieraren för detta smartobjektlagrets data i PSD-bilden.

Värde: Den unika identifieraren för denna smartobjektlagerresurs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

### setPlacedId_internalized(System.Guid value) {#setPlacedId-internalized-com.aspose.ms.System.Guid-}
```
public final void setPlacedId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Guid |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Hämtar eller anger typen av smartobjektlagrets data i PSD-filen.

Värde: Typen av smartobjektlagrets data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setResolution(double value) {#setResolution-double-}
```
public final void setResolution(double value)
```


Hämtar eller anger upplösningen för smartobjektlagrets data i PSD-filen.

Värde: Upplösningen för smartobjektlagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public final void setResolutionUnit(int value)
```


Hämtar eller anger enheten för upplösningsmått för smartobjektlagrets data i PSD-filen.

Värde: Upplösningens måttenhet för smartobjektlagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen.

Värde: Den högra platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekts roteringsorientering är horisontell.

Värde:  true  om rotationsorienteringen är horisontell; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden.

Värde: Den övre platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Hämtar eller anger det totala sidantalet för smartobjektlagrets data i PSD-filen.

Värde: Det totala antalet sidor för smartobjektlagrets data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Hämtar eller anger transformmatrisen för smartobjektlagrets data i PSD-filen.

Värde: Transformationsmatrisen för smartobjektlagrets data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: U‑ordningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Hämtar eller anger den globala unika identifieraren för smartobjektlagrets data [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) i PSD-bilden.

Värde: Den globala unika identifieraren för smartobjektlagrets data [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: V-ordningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden.

Värde: Förvrängningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3.

Värde: Versionen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Hämtar eller anger måttenheten för de vertikala nätpunkterna.

Värde: Måttenheten för de vertikala nätpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Hämtar eller anger klass‑ID.

Värde: Klass-ID:t.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Hämtar eller anger warp‑klassnamnet.

Värde: Förvrängningsklassens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Hämtar eller anger warp‑beskrivarversionen.

Värde: Versionen för förvrängningsbeskrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Hämtar eller anger warp‑versionen.

Värde: Förvrängningsversionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Hämtar eller anger bredden.

Värde: Bredden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En String som representerar detta objekt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

