---
title: "SoLeResource"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce la classe SoLeResource che contiene informazioni su un livello oggetto intelligente in un file PSD."
type: docs
weight: 16
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
```
public class SoLeResource extends SmartObjectResource
```

Definisce la classe SoLeResource che contiene informazioni su un livello smart object in un file PSD. È utilizzata per supportare i livelli smart object con collegamenti a file esterni nelle immagini Adobe\\ufffd Photoshop\\ufffd.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)](#SoLeResource-java.util.UUID-boolean-boolean-) | Inizializza una nuova istanza della classe [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource). |
| [SoLeResource()](#SoLeResource--) | Inizializza una nuova istanza della classe [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [AntiAliasPolicyKey_internalized](#AntiAliasPolicyKey-internalized) | La chiave della politica anti alias |
| [BottomKey_internalized](#BottomKey-internalized) | La chiave inferiore. |
| [BoundsKey_internalized](#BoundsKey-internalized) | La chiave dei limiti |
| [CompIdKey_internalized](#CompIdKey-internalized) | Il nome della chiave di CompID |
| [CompInfoKey_internalized](#CompInfoKey-internalized) | Il nome della chiave delle informazioni comp |
| [CompKey_internalized](#CompKey-internalized) | La chiave comp |
| [CompNoneValue_internalized](#CompNoneValue-internalized) | Il valore comp che significa 'none' |
| [CropKey_internalized](#CropKey-internalized) | La chiave crop |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Il nome della deformazione a involucro personalizzata |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Il nome della classe di deformazione predefinita |
| [DenominatorKey_internalized](#DenominatorKey-internalized) | La chiave del denominatore |
| [DurationKey_internalized](#DurationKey-internalized) | La chiave della durata |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Il nome della classe di deformazione predefinita |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | La versione prevista del descrittore di deformazione |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | La versione prevista della deformazione |
| [FrameCountKey_internalized](#FrameCountKey-internalized) | La chiave del conteggio dei frame |
| [FrameStepKey_internalized](#FrameStepKey-internalized) | La chiave del passo del frame |
| [HeightKey_internalized](#HeightKey-internalized) | La chiave dell'altezza |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Il nome dell'identificatore orizzontale |
| [IdentKey_internalized](#IdentKey-internalized) | La chiave dell'identificatore univoco |
| [ItemsPropertyCannotBeNull_internalized](#ItemsPropertyCannotBeNull-internalized) | La proprietà items non può essere null |
| [LeftKey_internalized](#LeftKey-internalized) | La chiave sinistra. |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Il nome della chiave dei punti della mesh |
| [NonAffineTransformKey_internalized](#NonAffineTransformKey-internalized) | La chiave della trasformazione non affine |
| [NullClassId_internalized](#NullClassId-internalized) | L'identificatore della classe null |
| [NumeratorKey_internalized](#NumeratorKey-internalized) | La chiave del numeratore |
| [OptionalKeys_internalized](#OptionalKeys-internalized) | La collezione di chiavi opzionali |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Il nome dell'identificatore di orientamento |
| [OriginalCompIdKey_internalized](#OriginalCompIdKey-internalized) | Il nome chiave del CompID originale |
| [PageNumberKey_internalized](#PageNumberKey-internalized) | La chiave del numero di pagina |
| [PlacedIdKey_internalized](#PlacedIdKey-internalized) | La chiave dell'identificatore posizionato |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Il valore della versione prevista |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La versione dell'intestazione PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La firma della risorsa specifica per PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La versione dell'intestazione PSD |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Il nome dell'identificatore della classe di punto razionale |
| [ResolutionKey_internalized](#ResolutionKey-internalized) | La chiave della risoluzione |
| [ResourceSignature](#ResourceSignature) | La firma della risorsa comune. |
| [RightKey_internalized](#RightKey-internalized) | La chiave destra. |
| [SizeKey_internalized](#SizeKey-internalized) | La chiave della dimensione |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | La dimensione del double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | La dimensione dell'int |
| [SmartVersionValue_internalized](#SmartVersionValue-internalized) | Il valore previsto della versione della risorsa smart object. |
| [TopKey_internalized](#TopKey-internalized) | La chiave superiore. |
| [TotalPagesKey_internalized](#TotalPagesKey-internalized) | La chiave del totale delle pagine |
| [TransformKey_internalized](#TransformKey-internalized) | La chiave della trasformazione |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Il conteggio dei valori di trasformazione |
| [TypeKey_internalized](#TypeKey-internalized) | La chiave del tipo |
| [TypeToolKey](#TypeToolKey) | La chiave di informazioni dello strumento tipo: 'SoLE'. |
| [TypeValue_internalized](#TypeValue-internalized) | Il valore previsto del tipo. |
| [UOrderKey_internalized](#UOrderKey-internalized) | La chiave dell'ordine u |
| [VOrderKey_internalized](#VOrderKey-internalized) | La chiave dell'ordine v |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Il nome dell'identificatore verticale |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Il nome personalizzato del warp |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | La lunghezza dell'intestazione del warp. |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | La lunghezza dell'intestazione del warp. |
| [WarpKey_internalized](#WarpKey-internalized) | La chiave del warp. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Il nome none del warp |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | La chiave di prospettiva del warp |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | L'altro della prospettiva del warp |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | La chiave di rotazione del warp |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | La chiave di stile del warp |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | La chiave del valore del warp |
| [WidthKey_internalized](#WidthKey-internalized) | La chiave della larghezza |
| [YouCannotAccessCropPropertyMessage_internalized](#YouCannotAccessCropPropertyMessage-internalized) | Non è possibile accedere al messaggio della proprietà Crop |
| [YouCannotSetCompIdPropertyMessage_internalized](#YouCannotSetCompIdPropertyMessage-internalized) | Non è possibile impostare il messaggio della proprietà CompId |
| [YouCannotSetCompPropertyMessage_internalized](#YouCannotSetCompPropertyMessage-internalized) | Non è possibile impostare il messaggio della proprietà Comp |
| [YouCannotSetOriginalCompIdPropertyMessage_internalized](#YouCannotSetOriginalCompIdPropertyMessage-internalized) | Non è possibile impostare il messaggio della proprietà OriginalCompId |
| [ZeroChar_internalized](#ZeroChar-internalized) | Il carattere zero. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licenza venture. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Verifica che il valore reale specificato sia uguale al valore atteso. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Verifica e imposta se la risorsa è specifica per PSB. |
| [convertListStructureToDoubleArray_internalized(ListStructure list)](#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-) | Converte la struttura dell'elenco in un array di double. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Ottiene o imposta la politica anti-alias dei dati del livello dell'oggetto smart nell'immagine PSD. |
| [getBottom()](#getBottom--) | Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD. |
| [getBounds()](#getBounds--) | Ottiene o imposta i limiti del livello posizionato nel file PSD. |
| [getClass()](#getClass--) |  |
| [getComp()](#getComp--) | Ottiene o imposta il valore comp dei dati del livello dell'oggetto smart nel file PSD. |
| [getCompId()](#getCompId--) | Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. |
| [getCrop()](#getCrop--) | Ottiene o imposta il ritaglio dei dati del livello dell'oggetto smart nell'immagine PSD. |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Ottiene o imposta il tipo di unità predefinito per i valori assegnati come Sinistra, Top, Right, Bottom, TransformMatrix. |
| [getDurationDenominator()](#getDurationDenominator--) | Ottiene o imposta il denominatore della durata. |
| [getDurationNumerator()](#getDurationNumerator--) | Ottiene o imposta il numeratore della durata. |
| [getFrameCount()](#getFrameCount--) | Ottiene o imposta il conteggio dei fotogrammi dei dati del livello dell'oggetto smart nel file PSD. |
| [getFrameStepDenominator()](#getFrameStepDenominator--) | Ottiene o imposta il denominatore del passo del fotogramma. |
| [getFrameStepNumerator()](#getFrameStepNumerator--) | Ottiene o imposta il numeratore del passo del fotogramma. |
| [getHeader_internalized()](#getHeader-internalized--) | Ottiene o imposta l'intestazione. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Ottiene o imposta l'unità di misura dei punti della griglia orizzontale. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD. |
| [getItems()](#getItems--) | Ottiene o imposta gli elementi del descrittore dei dati del livello dell'oggetto smart nel file PSD. |
| [getKey()](#getKey--) | Ottiene la chiave della risorsa del livello. |
| [getLeft()](#getLeft--) | Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD. |
| [getLength()](#getLength--) | Ottiene la lunghezza della risorsa smart object in byte. |
| [getNonAffineTransformMatrix()](#getNonAffineTransformMatrix--) | Ottiene o imposta la matrice di trasformazione non affine dei dati del livello smart object nel file PSD. |
| [getOriginalCompId()](#getOriginalCompId--) | Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. |
| [getPageNumber()](#getPageNumber--) | Ottiene o imposta il numero di pagina dei dati del livello smart object nel file PSD. |
| [getPerspective()](#getPerspective--) | Ottiene o imposta il valore di prospettiva del livello posizionato nel file PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Ottiene o imposta l'altro valore di prospettiva del livello posizionato nel file PSD. |
| [getPlacedId()](#getPlacedId--) | Ottiene o imposta l'identificatore univoco di questi dati del livello smart object nell'immagine PSD. |
| [getPlacedId_internalized()](#getPlacedId-internalized--) |  |
| [getPlacedLayerType()](#getPlacedLayerType--) | Ottiene o imposta il tipo dei dati del livello smart object nel file PSD. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ottiene la lunghezza del prefisso. |
| [getPsdVersion()](#getPsdVersion--) | Ottiene la versione minima di PSD richiesta per la risorsa del livello. |
| [getResolution()](#getResolution--) | Ottiene o imposta la risoluzione dei dati del livello smart object nel file PSD. |
| [getResolutionUnit()](#getResolutionUnit--) | Ottiene o imposta l'unità di misura della risoluzione dei dati del livello smart object nel file PSD. |
| [getRight()](#getRight--) | Ottiene o imposta la posizione destra del livello posizionato nel file PSD. |
| [getSignature()](#getSignature--) | Ottiene la firma della risorsa del livello. |
| [getTop()](#getTop--) | Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD. |
| [getTotalPages()](#getTotalPages--) | Ottiene o imposta il numero totale di pagine dei dati del livello smart object nel file PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene o imposta la matrice di trasformazione dei dati del livello smart object nel file PSD. |
| [getUOrder()](#getUOrder--) | Ottiene o imposta il valore dell'ordine U del livello posizionato nel file PSD. |
| [getUniqueId()](#getUniqueId--) | Ottiene o imposta l'identificatore globale univoco dei dati del livello smart object [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) nell'immagine PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD. |
| [getValue()](#getValue--) | Ottiene o imposta il valore di deformazione del livello posizionato nell'immagine PSD. |
| [getVersion()](#getVersion--) | Ottiene la versione del livello posizionato nel file PSD, solitamente 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Ottiene o imposta l'unità di misura dei punti della griglia verticale. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Ottiene o imposta l'ID della classe. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Ottiene o imposta il nome della classe di deformazione. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Ottiene o imposta la versione del descrittore di deformazione. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Gli elementi di deformazione. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Ottiene o imposta la versione della deformazione. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Ottiene il [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) all'indice specificato. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Ottiene un valore che indica se questa istanza ha unità di confine. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeBounds_internalized(Rectangle bounds)](#initializeBounds-internalized-com.aspose.psd.Rectangle-) | Inizializza i limiti e le matrici. |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determina se la risorsa è specifica per PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Ottiene o imposta un valore che indica se l'orientamento di rotazione di questa istanza è orizzontale. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Salva la risorsa smart object nel contenitore di stream specificato. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Salva l'intestazione della risorsa personalizzata. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Salva la firma, l'identificatore e la lunghezza dell'intestazione. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Ottiene o imposta la politica anti-alias dei dati del livello dell'oggetto smart nell'immagine PSD. |
| [setBottom(double value)](#setBottom-double-) | Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Ottiene o imposta i limiti del livello posizionato nel file PSD. |
| [setComp(int value)](#setComp-int-) | Ottiene o imposta il valore comp dei dati del livello dell'oggetto smart nel file PSD. |
| [setCompId(int value)](#setCompId-int-) | Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. |
| [setCrop(int value)](#setCrop-int-) | Ottiene o imposta il ritaglio dei dati del livello dell'oggetto smart nell'immagine PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Ottiene o imposta il tipo di unità predefinito per i valori assegnati come Sinistra, Top, Right, Bottom, TransformMatrix. |
| [setDurationDenominator(int value)](#setDurationDenominator-int-) | Ottiene o imposta il denominatore della durata. |
| [setDurationNumerator(int value)](#setDurationNumerator-int-) | Ottiene o imposta il numeratore della durata. |
| [setFrameCount(int value)](#setFrameCount-int-) | Ottiene o imposta il conteggio dei fotogrammi dei dati del livello dell'oggetto smart nel file PSD. |
| [setFrameStepDenominator(int value)](#setFrameStepDenominator-int-) | Ottiene o imposta il denominatore del passo del fotogramma. |
| [setFrameStepNumerator(int value)](#setFrameStepNumerator-int-) | Ottiene o imposta il numeratore del passo del fotogramma. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ottiene o imposta l'intestazione. |
| [setHeight(double value)](#setHeight-double-) | Ottiene o imposta l'altezza. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Ottiene o imposta l'unità di misura dei punti della griglia orizzontale. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Ottiene o imposta gli elementi del descrittore dei dati del livello dell'oggetto smart nel file PSD. |
| [setLeft(double value)](#setLeft-double-) | Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD. |
| [setNonAffineTransformMatrix(double[] value)](#setNonAffineTransformMatrix-double---) | Ottiene o imposta la matrice di trasformazione non affine dei dati del livello smart object nel file PSD. |
| [setOriginalCompId_internalized(int value)](#setOriginalCompId-internalized-int-) | Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. |
| [setPageNumber(int value)](#setPageNumber-int-) | Ottiene o imposta il numero di pagina dei dati del livello smart object nel file PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Ottiene o imposta il valore di prospettiva del livello posizionato nel file PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Ottiene o imposta l'altro valore di prospettiva del livello posizionato nel file PSD. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | Ottiene o imposta l'identificatore univoco di questi dati del livello smart object nell'immagine PSD. |
| [setPlacedId_internalized(System.Guid value)](#setPlacedId-internalized-com.aspose.ms.System.Guid-) |  |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Ottiene o imposta il tipo dei dati del livello smart object nel file PSD. |
| [setResolution(double value)](#setResolution-double-) | Ottiene o imposta la risoluzione dei dati del livello smart object nel file PSD. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Ottiene o imposta l'unità di misura della risoluzione dei dati del livello smart object nel file PSD. |
| [setRight(double value)](#setRight-double-) | Ottiene o imposta la posizione destra del livello posizionato nel file PSD. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Ottiene o imposta un valore che indica se l'orientamento di rotazione di questa istanza è orizzontale. |
| [setTop(double value)](#setTop-double-) | Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Ottiene o imposta il numero totale di pagine dei dati del livello smart object nel file PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Ottiene o imposta la matrice di trasformazione dei dati del livello smart object nel file PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Ottiene o imposta il valore dell'ordine U del livello posizionato nel file PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Ottiene o imposta l'identificatore globale univoco dei dati del livello smart object [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) nell'immagine PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD. |
| [setValue(double value)](#setValue-double-) | Ottiene o imposta il valore di deformazione del livello posizionato nell'immagine PSD. |
| [setVersion(int value)](#setVersion-int-) | Ottiene la versione del livello posizionato nel file PSD, solitamente 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Ottiene o imposta l'unità di misura dei punti della griglia verticale. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Ottiene o imposta l'ID della classe. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Ottiene o imposta il nome della classe di deformazione. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Ottiene o imposta la versione del descrittore di deformazione. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Ottiene o imposta la versione della deformazione. |
| [setWidth(double value)](#setWidth-double-) | Ottiene o imposta la larghezza. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo) {#SoLeResource-java.util.UUID-boolean-boolean-}
```
public SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)
```


Inizializza una nuova istanza della classe [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | java.util.UUID | L'identificatore univoco dei dati del livello posizionato [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource). |
| isCustom | boolean | se impostato su  true  [è personalizzato]. |
| hasCompInfo | boolean | se impostato su  true  [ha informazioni di composizione]. |

### SoLeResource() {#SoLeResource--}
```
public SoLeResource()
```


Inizializza una nuova istanza della classe [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource).

### AntiAliasPolicyKey_internalized {#AntiAliasPolicyKey-internalized}
```
public static final String AntiAliasPolicyKey_internalized
```


La chiave della politica anti alias

### BottomKey_internalized {#BottomKey-internalized}
```
public static final String BottomKey_internalized
```


La chiave inferiore.

### BoundsKey_internalized {#BoundsKey-internalized}
```
public static final String BoundsKey_internalized
```


La chiave dei limiti

### CompIdKey_internalized {#CompIdKey-internalized}
```
public static final String CompIdKey_internalized
```


Il nome della chiave di CompID

### CompInfoKey_internalized {#CompInfoKey-internalized}
```
public static final String CompInfoKey_internalized
```


Il nome della chiave delle informazioni comp

### CompKey_internalized {#CompKey-internalized}
```
public static final String CompKey_internalized
```


La chiave comp

### CompNoneValue_internalized {#CompNoneValue-internalized}
```
public static final int CompNoneValue_internalized
```


Il valore comp che significa 'none'

### CropKey_internalized {#CropKey-internalized}
```
public static final String CropKey_internalized
```


La chiave crop

### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Il nome della deformazione a involucro personalizzata

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Il nome della classe di deformazione predefinita

### DenominatorKey_internalized {#DenominatorKey-internalized}
```
public static final String DenominatorKey_internalized
```


La chiave del denominatore

### DurationKey_internalized {#DurationKey-internalized}
```
public static final String DurationKey_internalized
```


La chiave della durata

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Il nome della classe di deformazione predefinita

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


La versione prevista del descrittore di deformazione

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


La versione prevista della deformazione

### FrameCountKey_internalized {#FrameCountKey-internalized}
```
public static final String FrameCountKey_internalized
```


La chiave del conteggio dei frame

### FrameStepKey_internalized {#FrameStepKey-internalized}
```
public static final String FrameStepKey_internalized
```


La chiave del passo del frame

### HeightKey_internalized {#HeightKey-internalized}
```
public static final String HeightKey_internalized
```


La chiave dell'altezza

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Il nome dell'identificatore orizzontale

### IdentKey_internalized {#IdentKey-internalized}
```
public static final String IdentKey_internalized
```


La chiave dell'identificatore univoco

### ItemsPropertyCannotBeNull_internalized {#ItemsPropertyCannotBeNull-internalized}
```
public static final String ItemsPropertyCannotBeNull_internalized
```


La proprietà items non può essere null

### LeftKey_internalized {#LeftKey-internalized}
```
public static final String LeftKey_internalized
```


La chiave sinistra.

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Il nome della chiave dei punti della mesh

### NonAffineTransformKey_internalized {#NonAffineTransformKey-internalized}
```
public static final String NonAffineTransformKey_internalized
```


La chiave della trasformazione non affine

### NullClassId_internalized {#NullClassId-internalized}
```
public static final String NullClassId_internalized
```


L'identificatore della classe null

### NumeratorKey_internalized {#NumeratorKey-internalized}
```
public static final String NumeratorKey_internalized
```


La chiave del numeratore

### OptionalKeys_internalized {#OptionalKeys-internalized}
```
public static final String[] OptionalKeys_internalized
```


La collezione di chiavi opzionali

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Il nome dell'identificatore di orientamento

### OriginalCompIdKey_internalized {#OriginalCompIdKey-internalized}
```
public static final String OriginalCompIdKey_internalized
```


Il nome chiave del CompID originale

### PageNumberKey_internalized {#PageNumberKey-internalized}
```
public static final String PageNumberKey_internalized
```


La chiave del numero di pagina

### PlacedIdKey_internalized {#PlacedIdKey-internalized}
```
public static final String PlacedIdKey_internalized
```


La chiave dell'identificatore posizionato

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


Il valore della versione prevista

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


La versione dell'intestazione PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


La firma della risorsa specifica per PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


La versione dell'intestazione PSD

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Il nome dell'identificatore della classe di punto razionale

### ResolutionKey_internalized {#ResolutionKey-internalized}
```
public static final String ResolutionKey_internalized
```


La chiave della risoluzione

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


La firma della risorsa comune.

### RightKey_internalized {#RightKey-internalized}
```
public static final String RightKey_internalized
```


La chiave destra.

### SizeKey_internalized {#SizeKey-internalized}
```
public static final String SizeKey_internalized
```


La chiave della dimensione

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


La dimensione del double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


La dimensione dell'int

### SmartVersionValue_internalized {#SmartVersionValue-internalized}
```
public static final int SmartVersionValue_internalized
```


Il valore previsto della versione della risorsa smart object.

### TopKey_internalized {#TopKey-internalized}
```
public static final String TopKey_internalized
```


La chiave superiore.

### TotalPagesKey_internalized {#TotalPagesKey-internalized}
```
public static final String TotalPagesKey_internalized
```


La chiave del totale delle pagine

### TransformKey_internalized {#TransformKey-internalized}
```
public static final String TransformKey_internalized
```


La chiave della trasformazione

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Il conteggio dei valori di trasformazione

### TypeKey_internalized {#TypeKey-internalized}
```
public static final String TypeKey_internalized
```


La chiave del tipo

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


La chiave di informazioni dello strumento tipo: 'SoLE'.

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


Il valore previsto del tipo.

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


La chiave dell'ordine u

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


La chiave dell'ordine v

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Il nome dell'identificatore verticale

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Il nome personalizzato del warp

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


La lunghezza dell'intestazione del warp.

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


La lunghezza dell'intestazione del warp.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


La chiave di deformazione. È anche il nome predefinito della classe di deformazione.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Il nome none del warp

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


La chiave di prospettiva del warp

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


L'altro della prospettiva del warp

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


La chiave di rotazione del warp

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


La chiave di stile del warp

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


La chiave del valore del warp

### WidthKey_internalized {#WidthKey-internalized}
```
public static final String WidthKey_internalized
```


La chiave della larghezza

### YouCannotAccessCropPropertyMessage_internalized {#YouCannotAccessCropPropertyMessage-internalized}
```
public static final String YouCannotAccessCropPropertyMessage_internalized
```


Non è possibile accedere al messaggio della proprietà Crop

### YouCannotSetCompIdPropertyMessage_internalized {#YouCannotSetCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetCompIdPropertyMessage_internalized
```


Non è possibile impostare il messaggio della proprietà CompId

### YouCannotSetCompPropertyMessage_internalized {#YouCannotSetCompPropertyMessage-internalized}
```
public static final String YouCannotSetCompPropertyMessage_internalized
```


Non è possibile impostare il messaggio della proprietà Comp

### YouCannotSetOriginalCompIdPropertyMessage_internalized {#YouCannotSetOriginalCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetOriginalCompIdPropertyMessage_internalized
```


Non è possibile impostare il messaggio della proprietà OriginalCompId

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Il carattere zero.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


La licenza venture.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Verifica che il valore reale specificato sia uguale al valore atteso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| actualValue | java.lang.Object | Il valore effettivo. |
| expectedValue | java.lang.Object | Il valore previsto. |
| messaggio | java.lang.String | Il messaggio. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Verifica e imposta se la risorsa è specifica PSB. Alcune risorse non sono ancora riconosciute, ma disponiamo di un elenco completo di risorse specifiche PSB che ne modificano il comportamento durante il salvataggio. Pertanto è necessario controllare questo in UnknownResource almeno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | int | La chiave. |

### convertListStructureToDoubleArray_internalized(ListStructure list) {#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-}
```
public static double[] convertListStructureToDoubleArray_internalized(ListStructure list)
```


Converte la struttura dell'elenco in un array di double.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| list | [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) | L'istanza  ListStructure  . |

**Returns:**
double[] - L'array  double[]  creato.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Ottiene o imposta la politica anti-alias dei dati del livello dell'oggetto smart nell'immagine PSD.

Valore: La politica di anti-alias dei dati del livello smart object.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD.

Valore: La posizione inferiore del livello posizionato.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Ottiene o imposta i limiti del livello posizionato nel file PSD.

Valore: I limiti del livello posizionato.

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


Ottiene o imposta il valore comp dei dati del livello smart object nel file PSD.  Layer comps in Smart Objects

Valore: Il valore comp, è -1 se nessuno.

**Returns:**
int
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. I comp sono composizioni di un layout di pagina che i designer possono creare. Utilizzando i layer comp, è possibile creare, gestire e visualizzare più versioni di un layout in un unico file Adobe\ufffd Photoshop\ufffd. Un layer comp è un'istantanea di uno stato del pannello Layers. I layer comp salvano tre tipi di opzioni di livello ma questa proprietà ottiene l'identificatore di selezione del Layer Comp per il livello smart object nel file PSD.  Layer comps in Smart Objects

Valore: L'ID del comp attualmente selezionato per il documento figlio nell'immagine PSD, che sarà -1 se nessuno è selezionato.

**Returns:**
int
### getCrop() {#getCrop--}
```
public final int getCrop()
```


Ottiene o imposta il ritaglio dei dati del livello dell'oggetto smart nell'immagine PSD.

Valore: Il valore di ritaglio delle informazioni del livello posizionato.

**Returns:**
int
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Ottiene o imposta il tipo di unità predefinito per i valori assegnati come Sinistra, Top, Right, Bottom, TransformMatrix.

Valore: Il tipo di unità di misura predefinita.

**Returns:**
int
### getDurationDenominator() {#getDurationDenominator--}
```
public final int getDurationDenominator()
```


Ottiene o imposta il denominatore della durata.

Valore: Il denominatore della durata.

**Returns:**
int
### getDurationNumerator() {#getDurationNumerator--}
```
public final int getDurationNumerator()
```


Ottiene o imposta il numeratore della durata.

Valore: Il numeratore della durata.

**Returns:**
int
### getFrameCount() {#getFrameCount--}
```
public final int getFrameCount()
```


Ottiene o imposta il conteggio dei fotogrammi dei dati del livello dell'oggetto smart nel file PSD.

Valore: Il conteggio dei fotogrammi delle informazioni del livello posizionato.

**Returns:**
int
### getFrameStepDenominator() {#getFrameStepDenominator--}
```
public final int getFrameStepDenominator()
```


Ottiene o imposta il denominatore del passo del fotogramma.

Valore: Il denominatore del passo del fotogramma.

**Returns:**
int
### getFrameStepNumerator() {#getFrameStepNumerator--}
```
public final int getFrameStepNumerator()
```


Ottiene o imposta il numeratore del passo del fotogramma.

Valore: il numeratore del passo del fotogramma.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ottiene o imposta l'intestazione.

Valore: L'intestazione.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Ottiene o imposta l'altezza.

Valore: L'altezza.

**Returns:**
double
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Ottiene o imposta l'unità di misura dei punti della griglia orizzontale.

Valore: L'unità di misura dei punti della griglia orizzontale.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD.

Valore: I punti della griglia orizzontale del livello posizionato.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Ottiene o imposta gli elementi del descrittore dei dati del livello dell'oggetto smart nel file PSD.

Valore: gli elementi descrittori delle informazioni del livello posizionato.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Ottiene la chiave della risorsa del livello.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD.

Valore: La posizione sinistra del livello posizionato.

**Returns:**
double
### getLength() {#getLength--}
```
public int getLength()
```


Ottiene la lunghezza della risorsa smart object in byte.

**Returns:**
int
### getNonAffineTransformMatrix() {#getNonAffineTransformMatrix--}
```
public final double[] getNonAffineTransformMatrix()
```


Ottiene o imposta la matrice di trasformazione non affine dei dati del livello smart object nel file PSD.

Valore: la matrice di trasformazione non affine del livello oggetto intelligente.

**Returns:**
double[]
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. Questa proprietà ottiene l'identificatore di selezione del Comp del livello originale per il livello oggetto intelligente nel file PSD.  Comp dei livelli negli oggetti intelligenti

Valore: l'ID originale del comp attualmente selezionato per il documento figlio nell'immagine PSD, che sarà -1 se nessuno è selezionato.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Ottiene o imposta il numero di pagina dei dati del livello smart object nel file PSD.

Valore: il numero di pagina dei dati del livello oggetto intelligente.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Ottiene o imposta il valore di prospettiva del livello posizionato nel file PSD.

Valore: Il valore di prospettiva del livello posizionato.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Ottiene o imposta l'altro valore di prospettiva del livello posizionato nel file PSD.

Valore: L'altro valore di prospettiva del livello posizionato.

**Returns:**
double
### getPlacedId() {#getPlacedId--}
```
public final UUID getPlacedId()
```


Ottiene o imposta l'identificatore univoco di questi dati del livello smart object nell'immagine PSD.

Valore: l'identificatore unico di questa risorsa di livello oggetto intelligente.

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


Ottiene o imposta il tipo dei dati del livello smart object nel file PSD.

Valore: il tipo dei dati del livello oggetto intelligente.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Ottiene la lunghezza del prefisso. Il valore predefinito è 12 per le risorse 8BIM e 16 per 8B64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| psdVersion | int | La versione PSD. |

**Returns:**
int - La lunghezza del prefisso.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Ottiene la versione minima di psd richiesta per la risorsa di livello. 0 indica nessuna restrizione.

**Returns:**
int
### getResolution() {#getResolution--}
```
public final double getResolution()
```


Ottiene o imposta la risoluzione dei dati del livello smart object nel file PSD.

Valore: la risoluzione del livello oggetto intelligente.

**Returns:**
double
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


Ottiene o imposta l'unità di misura della risoluzione dei dati del livello smart object nel file PSD.

Valore: l'unità di misura della risoluzione del livello oggetto intelligente.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Ottiene o imposta la posizione destra del livello posizionato nel file PSD.

Valore: La posizione destra del livello posizionato.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ottiene la firma della risorsa del livello.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD.

Valore: La posizione superiore del livello posizionato.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Ottiene o imposta il numero totale di pagine dei dati del livello smart object nel file PSD.

Valore: il numero totale di pagine dei dati del livello oggetto intelligente.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Ottiene o imposta la matrice di trasformazione dei dati del livello smart object nel file PSD.

Valore: la matrice di trasformazione dei dati del livello oggetto intelligente.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Ottiene o imposta il valore dell'ordine U del livello posizionato nel file PSD.

Valore: Il valore dell'ordine U del livello posizionato.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Ottiene o imposta l'identificatore globale univoco dei dati del livello smart object [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) nell'immagine PSD.

Valore: l'identificatore unico globale dei dati del livello oggetto intelligente [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

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


Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD.

Valore: Il valore dell'ordine V del livello posizionato.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Ottiene o imposta il valore di deformazione del livello posizionato nell'immagine PSD.

Valore: Il valore di deformazione del livello posizionato.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Ottiene la versione del livello posizionato nel file PSD, solitamente 3.

Valore: La versione del livello posizionato.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Ottiene o imposta l'unità di misura dei punti della griglia verticale.

Valore: L'unità di misura dei punti della griglia verticale.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD.

Valore: I punti della griglia orizzontale del livello posizionato.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Ottiene o imposta l'ID della classe.

Valore: L'ID della classe.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Ottiene o imposta il nome della classe di deformazione.

Valore: Il nome della classe di deformazione.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Ottiene o imposta la versione del descrittore di deformazione.

Valore: La versione del descrittore di deformazione.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Gli elementi di deformazione.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Ottiene o imposta la versione della deformazione.

Valore: La versione della deformazione.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Ottiene o imposta la larghezza.

Valore: La larghezza.

**Returns:**
double
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Ottiene il [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) all'indice specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | java.lang.String | Il nome della chiave. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Ottiene un valore che indica se questa istanza ha unità di confine.

Valore:  true  se questa istanza ha unità di confine; altrimenti,  false .

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### initializeBounds_internalized(Rectangle bounds) {#initializeBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void initializeBounds_internalized(Rectangle bounds)
```


Inizializza i limiti e le matrici.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti. |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato. Se true contiene punti della mesh. Se impostato a false elimina i punti della mesh.

Valore:  true  se il livello posizionato ha uno stile personalizzato; altrimenti,  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Determina se la risorsa è specifica per PSB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | int | La chiave della risorsa. |

**Returns:**
boolean -  true  se la risorsa è specifica PSB; altrimenti,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Ottiene un valore che indica se questa istanza è una risorsa specifica per PSB.

Valore:  true  se questa istanza è una risorsa specifica PSB; altrimenti,  false .

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Ottiene o imposta un valore che indica se l'orientamento di rotazione di questa istanza è orizzontale.

Valore:  true  se l'orientamento di rotazione è orizzontale; altrimenti,  false .

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


Salva la risorsa smart object nel contenitore di stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |
| psdVersion | int | La versione PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Salva l'intestazione della risorsa personalizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |
| firma | int | La firma. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Salva la firma, l'identificatore e la lunghezza dell'intestazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |
| firma | int | La firma. |
| isLengthLong | boolean | se impostato su  true  la lunghezza è lunga. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Ottiene o imposta la politica anti-alias dei dati del livello dell'oggetto smart nell'immagine PSD.

Valore: La politica di anti-alias dei dati del livello smart object.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Ottiene o imposta la posizione inferiore del livello posizionato nell'immagine PSD.

Valore: La posizione inferiore del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Ottiene o imposta i limiti del livello posizionato nel file PSD.

Valore: I limiti del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setComp(int value) {#setComp-int-}
```
public final void setComp(int value)
```


Ottiene o imposta il valore comp dei dati del livello smart object nel file PSD.  Layer comps in Smart Objects

Valore: Il valore comp, è -1 se nessuno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Ottiene o imposta l'ID del comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. I comp sono composizioni di un layout di pagina che i designer possono creare. Utilizzando i layer comp, è possibile creare, gestire e visualizzare più versioni di un layout in un unico file Adobe\ufffd Photoshop\ufffd. Un layer comp è un'istantanea di uno stato del pannello Layers. I layer comp salvano tre tipi di opzioni di livello ma questa proprietà ottiene l'identificatore di selezione del Layer Comp per il livello smart object nel file PSD.  Layer comps in Smart Objects

Valore: L'ID del comp attualmente selezionato per il documento figlio nell'immagine PSD, che sarà -1 se nessuno è selezionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setCrop(int value) {#setCrop-int-}
```
public final void setCrop(int value)
```


Ottiene o imposta il ritaglio dei dati del livello dell'oggetto smart nell'immagine PSD.

Valore: Il valore di ritaglio delle informazioni del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Ottiene o imposta un valore che indica se lo stile di deformazione di questa istanza è personalizzato. Se true contiene punti della mesh. Se impostato a false elimina i punti della mesh.

Valore:  true  se il livello posizionato ha uno stile personalizzato; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Ottiene o imposta il tipo di unità predefinito per i valori assegnati come Sinistra, Top, Right, Bottom, TransformMatrix.

Valore: Il tipo di unità di misura predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDurationDenominator(int value) {#setDurationDenominator-int-}
```
public final void setDurationDenominator(int value)
```


Ottiene o imposta il denominatore della durata.

Valore: Il denominatore della durata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDurationNumerator(int value) {#setDurationNumerator-int-}
```
public final void setDurationNumerator(int value)
```


Ottiene o imposta il numeratore della durata.

Valore: Il numeratore della durata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFrameCount(int value) {#setFrameCount-int-}
```
public final void setFrameCount(int value)
```


Ottiene o imposta il conteggio dei fotogrammi dei dati del livello dell'oggetto smart nel file PSD.

Valore: Il conteggio dei fotogrammi delle informazioni del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFrameStepDenominator(int value) {#setFrameStepDenominator-int-}
```
public final void setFrameStepDenominator(int value)
```


Ottiene o imposta il denominatore del passo del fotogramma.

Valore: Il denominatore del passo del fotogramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFrameStepNumerator(int value) {#setFrameStepNumerator-int-}
```
public final void setFrameStepNumerator(int value)
```


Ottiene o imposta il numeratore del passo del fotogramma.

Valore: il numeratore del passo del fotogramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Ottiene o imposta l'intestazione.

Valore: L'intestazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ottiene o imposta l'altezza.

Valore: L'altezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Ottiene o imposta l'unità di misura dei punti della griglia orizzontale.

Valore: L'unità di misura dei punti della griglia orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD.

Valore: I punti della griglia orizzontale del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Ottiene o imposta gli elementi del descrittore dei dati del livello dell'oggetto smart nel file PSD.

Valore: gli elementi descrittori delle informazioni del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Ottiene o imposta la posizione sinistra del livello posizionato nel file PSD.

Valore: La posizione sinistra del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setNonAffineTransformMatrix(double[] value) {#setNonAffineTransformMatrix-double---}
```
public final void setNonAffineTransformMatrix(double[] value)
```


Ottiene o imposta la matrice di trasformazione non affine dei dati del livello smart object nel file PSD.

Valore: la matrice di trasformazione non affine del livello oggetto intelligente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setOriginalCompId_internalized(int value) {#setOriginalCompId-internalized-int-}
```
public final void setOriginalCompId_internalized(int value)
```


Ottiene l'ID originale del Comp attualmente selezionato per il documento figlio, che sarà -1 se nessuno è selezionato. Questa proprietà ottiene l'identificatore di selezione del Comp del livello originale per il livello oggetto intelligente nel file PSD.  Comp dei livelli negli oggetti intelligenti

Valore: l'ID originale del comp attualmente selezionato per il documento figlio nell'immagine PSD, che sarà -1 se nessuno è selezionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Ottiene o imposta il numero di pagina dei dati del livello smart object nel file PSD.

Valore: il numero di pagina dei dati del livello oggetto intelligente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Ottiene o imposta il valore di prospettiva del livello posizionato nel file PSD.

Valore: Il valore di prospettiva del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Ottiene o imposta l'altro valore di prospettiva del livello posizionato nel file PSD.

Valore: L'altro valore di prospettiva del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public final void setPlacedId(UUID value)
```


Ottiene o imposta l'identificatore univoco di questi dati del livello smart object nell'immagine PSD.

Valore: l'identificatore unico di questa risorsa di livello oggetto intelligente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

### setPlacedId_internalized(System.Guid value) {#setPlacedId-internalized-com.aspose.ms.System.Guid-}
```
public final void setPlacedId_internalized(System.Guid value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.Guid |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Ottiene o imposta il tipo dei dati del livello smart object nel file PSD.

Valore: il tipo dei dati del livello oggetto intelligente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setResolution(double value) {#setResolution-double-}
```
public final void setResolution(double value)
```


Ottiene o imposta la risoluzione dei dati del livello smart object nel file PSD.

Valore: la risoluzione del livello oggetto intelligente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public final void setResolutionUnit(int value)
```


Ottiene o imposta l'unità di misura della risoluzione dei dati del livello smart object nel file PSD.

Valore: l'unità di misura della risoluzione del livello oggetto intelligente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Ottiene o imposta la posizione destra del livello posizionato nel file PSD.

Valore: La posizione destra del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Ottiene o imposta un valore che indica se l'orientamento di rotazione di questa istanza è orizzontale.

Valore:  true  se l'orientamento di rotazione è orizzontale; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Ottiene o imposta la posizione superiore del livello posizionato nell'immagine PSD.

Valore: La posizione superiore del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Ottiene o imposta il numero totale di pagine dei dati del livello smart object nel file PSD.

Valore: il numero totale di pagine dei dati del livello oggetto intelligente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Ottiene o imposta la matrice di trasformazione dei dati del livello smart object nel file PSD.

Valore: la matrice di trasformazione dei dati del livello oggetto intelligente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Ottiene o imposta il valore dell'ordine U del livello posizionato nel file PSD.

Valore: Il valore dell'ordine U del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Ottiene o imposta l'identificatore globale univoco dei dati del livello smart object [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) nell'immagine PSD.

Valore: l'identificatore unico globale dei dati del livello oggetto intelligente [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Ottiene o imposta il valore dell'ordine V del livello posizionato nel file PSD.

Valore: Il valore dell'ordine V del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Ottiene o imposta il valore di deformazione del livello posizionato nell'immagine PSD.

Valore: Il valore di deformazione del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Ottiene la versione del livello posizionato nel file PSD, solitamente 3.

Valore: La versione del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Ottiene o imposta l'unità di misura dei punti della griglia verticale.

Valore: L'unità di misura dei punti della griglia verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Ottiene o imposta i punti della griglia orizzontale del livello posizionato nel file PSD.

Valore: I punti della griglia orizzontale del livello posizionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Ottiene o imposta l'ID della classe.

Valore: L'ID della classe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Ottiene o imposta il nome della classe di deformazione.

Valore: Il nome della classe di deformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Ottiene o imposta la versione del descrittore di deformazione.

Valore: La versione del descrittore di deformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Ottiene o imposta la versione della deformazione.

Valore: La versione della deformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ottiene o imposta la larghezza.

Valore: La larghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una String che rappresenta questa istanza.

**Returns:**
java.lang.String - Una String che rappresenta questa istanza.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

