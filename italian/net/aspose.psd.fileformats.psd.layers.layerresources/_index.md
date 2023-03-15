---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Aspose.PSD per riferimento API .NET
description: Lo spazio dei nomi contiene entità in formato file PSD contenute nei livelli.
type: docs
weight: 270
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/
---
Lo spazio dei nomi contiene entità in formato file PSD contenute nei livelli.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | Classe base per le risorse del livello di regolazione |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | La sezione con i dati animati. |
| [BlncResource](./blncresource/) | La classe BlncResource è una risorsa del livello di regolazione del colore. |
| [BlwhResource](./blwhresource/) | La classe BlwhResource è una risorsa del livello di regolazione del bianco e nero. |
| [BooleanResource](./booleanresource/) | Classe BooleanResource. È una pseudo risorsa. Photoshop non ce l'ha |
| [BritResource](./britresource/) | Classe BritResource. Risorsa di livello di regolazione luminosità/contrasto |
| [CgEdResource](./cgedresource/) | Classe CgEdResource. Dati aggiuntivi del generatore di contenuti (Photoshop CS5) |
| [ClassID](./classid/) | L'oggetto ID classe PSD. |
| [ClblResource](./clblresource/) | Class ClblResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [CmlsResource](./cmlsresource/) | Classe CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) ha 6 gamme di colori in cui è possibile modificare i parametri HSV. Ogni intervallo ha 4 punti chiave per identificare i confini dell'intervallo. Ed è ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Gestore del livello di regolazione delle curve che manipola le curve |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Gestore del livello di regolazione delle curve che manipola la mappa dei pixel |
| [CurvesManager](./curvesmanager/) | Classe base per gestire CurvResource |
| [CurvResource](./curvresource/) | Classe CurvResource. Livello di regolazione della risorsa delle curve 1 byte - 0 se si utilizzano curve, 1 se si utilizzano pixel sulla mappa se 0 then: 2 byte - breve. Il valore predefinito è 1 4 byte - int. Utilizzato solo l'ultimo byte per bit. Il primo bit è per 1 canale, il quarto bit per 4 canali ad esempio 2 byte - conteggio punti breve 4 byte * conteggio punto - punti della curva 2 breve: prima posizione, seconda altezza 4 byte - parola "Crv " 2 byte - breve predefinito è 4 per Curves 4 byte - int. L'impostazione predefinita è 1 4 byte - conteggio punti 4 byte * conteggio punti - punti della curva 2 breve: prima posizione, seconda altezza 0-4 byte - L'inizio deve essere piegato per quattro se 1 quindi: 2 byte - breve. Il valore predefinito è 1 4 byte - int. Utilizzato solo l'ultimo byte. Un canale è in un bit. Il primo bit è per 1 canale, il quarto bit per 4 canali, ad esempio 256 * conteggio dei canali modificati - valori ordinati del canale nell'intervallo 0 - 255 4 byte - parola "Crv " 2 byte - breve. L'impostazione predefinita è 3 per i pixel sulla mappa 4 byte - int Channel count (2 + 256) byte - short 2 per l'indice del canale, 256 è il valore ordinato del canale nell'intervallo 0 - 255 |
| [CustResource](./custresource/) | Class CustResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [ExpaResource](./exparesource/) | Classe ExpaResource. Risorsa del livello di regolazione dell'esposizione |
| [FillLayerResource](./filllayerresource/) | Classe base per le risorse del livello di riempimento |
| [FilterEffectMaskData](./filtereffectmaskdata/) | La classe di dati della maschera del filtro. |
| [FXidResource](./fxidresource/) | La risorsa Effetti filtro contiene canali, una maschera utente e una maschera foglio per il filtro intelligente. |
| [FxrpResource](./fxrpresource/) | Classe FxrpResource. Il punto di riferimento di layer |
| [GdFlResource](./gdflresource/) | Class GdFlResource. Questa risorsa contiene informazioni sulla fusione di elementi tagliati. |
| [Hue2Resource](./hue2resource/) | Classe Hue2Resource. Risorsa del livello di regolazione dell'esposizione |
| [InfxResource](./infxresource/) | Class InfxResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [IopaResource](./ioparesource/) | Class IopaResource. Questa risorsa contiene informazioni sulla proprietà fill opacity dallo stile layer form |
| [KnkoResource](./knkoresource/) | Class KnkoResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [LayerSectionResource](./layersectionresource/) | La risorsa sezione layer. |
| [LclrResource](./lclrresource/) | Class LclrResource. Questa risorsa contiene informazioni sul colore del livello nell'elenco dei livelli è PS. Sono solo |
| [LevelChannel](./levelchannel/) | Classe per lavorare con i canali in Levels Adjustment Layer |
| [LevlResource](./levlresource/) | Class LevlResource. Risorsa del livello di regolazione dell'esposizione |
| [Lfx2Resource](./lfx2resource/) | Risorsa Lfx2 (risorsa effetti) |
| [LiFdDataSource](./lifddatasource/) | Definisce la classe di origine dati liFD nel file PSD che contiene informazioni su un file incorporato. Fa parte dell'API di manipolazione del formato file PSD che aiuta a modificare i file Adobe® Photoshop® |
| [LiFeDataSource](./lifedatasource/) | Definisce la classe LnkeDataSource che contiene informazioni sul file collegato esterno. Fa parte dell'API di manipolazione del formato file PSD che aiuta a modificare i file Adobe® Photoshop® |
| [LinkDataSource](./linkdatasource/) | Definisce la classe LinkDataSource che contiene informazioni su un file collegato o una risorsa nel file PSD. |
| [LinkResource](./linkresource/) | Definisce la classe LinkResource che contiene informazioni sui file collegati o incorporati nell'immagine in formato PSD. La risorsa collegamento può contenere diversi[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) istanze a cui possono accedere gli indicizzatori in qualsiasi classe derivata. |
| [Lnk2Resource](./lnk2resource/) | Definisce la classe che contiene informazioni sui file incorporati nell'immagine in formato PSD. La risorsa di collegamento può contenere diversi[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) istanze a cui può accedere l'indicizzatore. |
| [Lnk3Resource](./lnk3resource/) | Definisce la classe che contiene informazioni su un file incorporato nel formato PSD a 32 bit per immagine del canale. La risorsa di collegamento può contenere diverse[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) istanze a cui è possibile accedere dall'indicizzatore. |
| [LnkeResource](./lnkeresource/) | Definisce la classe LnkeResource che contiene informazioni su risorse o file collegati esterni nell'immagine in formato PSD. La risorsa di collegamento può contenere diversi[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) istanze a cui è possibile accedere dall'indicizzatore. Questa è una parte dell'API di manipolazione del formato file PSD che aiuta a modificare i file Adobe® Photoshop® in modo programmatico |
| [LnsrResource](./lnsrresource/) | Classe lnsrResource. |
| [Lr16Resource](./lr16resource/) | La risorsa lr32. |
| [Lr32Resource](./lr32resource/) | La risorsa lr32. |
| [LspfResource](./lspfresource/) | Impostazioni protette dal livello |
| [LuniResource](./luniresource/) | Nome livello risorsa |
| [LyidResource](./lyidresource/) | Classe LyidResource. |
| [MixrResource](./mixrresource/) | Classe MixrResource. Risorsa del livello di regolazione del mixer dei canali |
| [MlstResource](./mlstresource/) | La risorsa mlst. Questa classe, tra le altre cose, contiene informazioni sulla posizione del livello sulla timeline. |
| [NvrtResource](./nvrtresource/) | Classe NvrtResource. Risorsa di Inverti livello di regolazione. |
| [OSTypeStructure](./ostypestructure/) | Rappresenta la struttura del tipo di sistema operativo. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | Rappresenta il[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) registro delle risorse. |
| [PattResource](./pattresource/) | Classe PattResource. Risorsa con pattern data |
| [PattResourceData](./pattresourcedata/) | La classe per cui archiviare i dati del modello[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/) risorsa. |
| [PhflResource](./phflresource/) | Classe PhflResource. Risorsa del livello di regolazione dell'esposizione 2 versione ( = 3 ) o ( = 2 ) 12 4 byte ciascuno per il colore XYZ (solo nella versione 3) 10 2 byte di spazio colore seguito da 4 * 2 byte di componente colore (solo nella versione 2) 4 Densità 1 Mantieni luminosità |
| [PhflResourceVersion2](./phflresourceversion2/) | Classe PhflResource. Risorsa del livello di regolazione dell'esposizione 2 versione ( = 3 ) o ( = 2 ) 12 4 byte ciascuno per il colore XYZ (solo nella versione 3) 10 2 byte di spazio colore seguito da 4 * 2 byte di componente colore (solo nella versione 2) 4 Densità 1 Mantieni luminosità |
| [PhflResourceVersion3](./phflresourceversion3/) | Classe PhflResource. Risorsa del livello di regolazione dell'esposizione 2 versione ( = 3 ) o ( = 2 ) 12 4 byte ciascuno per il colore XYZ (solo nella versione 3) 10 2 byte di spazio colore seguito da 4 * 2 byte di componente colore (solo nella versione 2) 4 Densità 1 Mantieni luminosità |
| [PlacedResource](./placedresource/) | Definisce la classe PlacedResource che contiene informazioni comuni su un livello posizionato o un livello oggetto avanzato nel file PSD. Viene utilizzato per supportare i livelli oggetto avanzato nelle immagini di Adobe® Photoshop®. |
| [PlLdResource](./plldresource/) | Definisce la classe PlLdResource che contiene informazioni su un livello posizionato nel file PSD. Viene utilizzato per supportare i livelli di oggetti intelligenti nelle immagini di Adobe® Photoshop®. È stato sostituito da SoLdResource in Adobe® Photoshop® CS3 |
| [PostResource](./postresource/) | Classe PostResource. Posterizza le impostazioni del livello. |
| [PtFlResource](./ptflresource/) | Classe PtFlResource. Contiene i dati del livello di riempimento a motivo. |
| [ShmdResource](./shmdresource/) | Classe ShmdResource. Impostazioni metadati |
| [SmartObjectResource](./smartobjectresource/) | Definisce la classe SmartObjectResource che contiene informazioni su un livello oggetto avanzato in un file PSD. È la classe base per le risorse Sold and Sole utilizzata per supportare i livelli oggetto avanzato nelle immagini Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator/) | Definisce la classe SmartResourceCreator che può creare risorse PlLd, SoLd e SoLe. Viene utilizzato per supportare i livelli di oggetti intelligenti nelle immagini di Adobe® Photoshop®. |
| [SoCoResource](./socoresource/) | Class SoCoResource. Questa risorsa contiene informazioni sui livelli di riempimento colore |
| [SoLdResource](./soldresource/) | Definisce la classe SoLdResource che contiene informazioni su un livello oggetto avanzato in un file PSD. Viene utilizzato per supportare i livelli oggetto avanzato nelle immagini di Adobe® Photoshop®. |
| [SoLeResource](./soleresource/) | Definisce la classe SoLeResource che contiene informazioni su un livello di oggetti avanzati in un file PSD. Viene utilizzato per supportare i livelli di oggetti avanzati con collegamenti a file esterni nelle immagini di Adobe® Photoshop®. |
| [Txt2Resource](./txt2resource/) | Classe risorsa Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo/) | Contiene informazioni sul carattere dello strumento di testo. |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | Le informazioni sullo strumento testo. Per versione PSD superiore o uguale alla 6.0. |
| [TypeToolInfoResource](./typetoolinforesource/) | Le informazioni sullo strumento testo. Per versione PSD inferiore a 6.0. |
| [TypeToolLineInfo](./typetoollineinfo/) | Digitare informazioni linea utensile. |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | Digita le informazioni sullo stile dello strumento. |
| [UnknownResource](./unknownresource/) | La risorsa sconosciuta. |
| [VectorPathDataResource](./vectorpathdataresource/) | Class VectorPathDataResource. Questa risorsa contiene informazioni sulla maschera di livello vettoriale |
| [VibAResource](./vibaresource/) | Risorsa VibA. |
| [VmskResource](./vmskresource/) | Class VmskResource. Questa risorsa contiene informazioni sulla maschera di livello vettoriale |
| [VogkResource](./vogkresource/) | La risorsa dei dati di origine vettoriale. |
| [VsmsResource](./vsmsresource/) | Class VsmsResource. Questa risorsa contiene informazioni sulla maschera di livello vettoriale |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | Il[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) caricatore di risorse. |
| [IPlacedLayerResource](./iplacedlayerresource/) | Definisce l'interfaccia IPlacedLayerResource che contiene informazioni su un livello posizionato nel file PSD. È un'interfaccia di markup utilizzata per designare le risorse PlLd, Sold e Sole nelle immagini Adobe® Photoshop®. È utilizzata per supportare i livelli di oggetti intelligenti in le immagini di Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | Definisce l'interfaccia ISmartObjectLayerResource che contiene informazioni su una risorsa di livello oggetto avanzato nel file PSD. È anche un'interfaccia di markup utilizzata per designare le risorse Venduto e Unico nelle immagini Adobe® Photoshop®. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [LayerLockType](./layerlocktype/) | Opzioni di blocco livello |
| [LayerSectionSubtype](./layersectionsubtype/) | Il sottotipo di sezione |
| [LayerSectionType](./layersectiontype/) | Il tipo di sezione del livello |
| [LinkDataSourceType](./linkdatasourcetype/) | Definisce l'enumerazione LinkDataSourceType per le origini dati nella risorsa collegamento PSD. |
| [LnsrResourceType](./lnsrresourcetype/) | Scoperta di possibili tipi di risorsa Lnsr |
| [PlacedLayerType](./placedlayertype/) | Definisce l'enumerazione PlacedLayerType per la risorsa PlLd del livello posizionato. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Possibili colori dell'impostazione del colore del foglio. È il colore decorativo dell'interfaccia utente del livello nell'elenco dei livelli in PS |


