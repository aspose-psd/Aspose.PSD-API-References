---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Lo spazio dei nomi contiene entità in formato file PSD contenute nei livelli.
type: docs
weight: 270
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/
---
Lo spazio dei nomi contiene entità in formato file PSD contenute nei livelli.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource) | Classe base per le risorse del livello di adeguamento |
| [AnimatedDataSectionStructure](./animateddatasectionstructure) | La sezione con i dati animati. |
| [BlncResource](./blncresource) | La classe BlncResource è una risorsa del livello di regolazione del colore. |
| [BlwhResource](./blwhresource) | La classe BlwhResource è una risorsa del livello di regolazione del bianco e nero. |
| [BooleanResource](./booleanresource) | Classe BooleanResource. È una pseudo risorsa. Photoshop non ce l'ha |
| [BritResource](./britresource) | Classe BritResource. Risorsa del livello di regolazione della luminosità/contrasto |
| [CgEdResource](./cgedresource) | Classe CgEdResource. Dati aggiuntivi del generatore di contenuti (Photoshop CS5) |
| [ClassID](./classid) | L'oggetto ID classe PSD. |
| [ClblResource](./clblresource) | Classe ClblResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [CmlsResource](./cmlsresource) | Classe CmlsResource. |
| [ColorRangeHsl](./colorrangehsl) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource) dispone di 6 gamme di colori in cui è possibile modificare i parametri HSV. Ogni intervallo ha 4 punti chiave per identificare i confini dell'intervallo. Ed è ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager) | Manager per il livello di regolazione delle curve che manipola le curve |
| [CurvesDiscreteManager](./curvesdiscretemanager) | Manager per il livello di regolazione delle curve che manipola la mappa dei pixel |
| [CurvesManager](./curvesmanager) | Classe base per gestire CurvResource |
| [CurvResource](./curvresource) | Classe CurvResource. Risorsa di regolazione delle curve Layer 1 byte - 0 se si usano le curve, 1 se si usano pixel su map se 0 allora: 2 byte - short. Il valore predefinito è 1 4 byte - int. Utilizzato solo l'ultimo byte per bit. Il primo bit è per 1 canale, il quarto bit per 4 canali ad esempio 2 byte - conteggio punti brevi 4 byte * conteggio punto - punti curva 2 breve: prima posizione, seconda altezza 4 byte - parola "Crv " 2 byte - short predefinito è 4 per Curves 4 byte - int. Il valore predefinito è 1 4 byte - conteggio punti 4 byte * conteggio punti - punti della curva 2 corti: prima posizione, seconda altezza 0-4 byte - Porta ad essere piegato per quattro se 1 quindi: 2 byte - breve. Il valore predefinito è 1 4 byte - int. Utilizzato solo l'ultimo byte. Un canale è in un bit. Il primo bit è per 1 canale, il quarto bit per 4 canali ad esempio 256 * conteggio dei canali modificati - valori ordinati del canale nell'intervallo 0 - 255 4 byte - parola "Crv " 2 byte - breve. Il valore predefinito è 3 per i pixel su map 4 byte - int Channel count (2 + 256) byte - short 2 per l'indice del canale, 256 sono valori ordinati del canale nell'intervallo 0 - 255 |
| [CustResource](./custresource) | Classe CustResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [ExpaResource](./exparesource) | Classe ExpaResource. Risorsa del livello di regolazione dell'esposizione |
| [FillLayerResource](./filllayerresource) | Classe base per le risorse del livello di riempimento |
| [FilterEffectMaskData](./filtereffectmaskdata) | La classe di dati della maschera del filtro. |
| [FXidResource](./fxidresource) | La risorsa Effetti filtro contiene canali, una maschera utente e una maschera foglio per il filtro intelligente. |
| [FxrpResource](./fxrpresource) | Classe FxrpResource. Il punto di riferimento di layer |
| [GdFlResource](./gdflresource) | Classe GdFlResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [Hue2Resource](./hue2resource) | Classe Hue2Resource. Risorsa del livello di regolazione dell'esposizione |
| [InfxResource](./infxresource) | Classe InfxResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [IopaResource](./ioparesource) | Classe IopaResource. Questa risorsa contiene informazioni sulla proprietà dell'opacità del riempimento dal modulo dello stile del livello |
| [KnkoResource](./knkoresource) | Classe KnkoResource. Questa risorsa contiene informazioni sulla fusione di elementi ritagliati. |
| [LayerSectionResource](./layersectionresource) | La risorsa della sezione del livello. |
| [LclrResource](./lclrresource) | Classe LclrResource. Questa risorsa contiene informazioni sul colore del livello nell'elenco dei livelli è PS. È solo |
| [LevelChannel](./levelchannel) | Classe per lavorare con i canali nel livello di regolazione dei livelli |
| [LevlResource](./levlresource) | Classe LevlResource. Risorsa del livello di regolazione dell'esposizione |
| [Lfx2Resource](./lfx2resource) | Risorsa Lfx2 (risorsa effetti) |
| [LiFdDataSource](./lifddatasource) | Definisce la classe dell'origine dati liFD nel file PSD che contiene informazioni su un file incorporato. Fa parte dell'API di manipolazione del formato file PSD che aiuta a modificare i file Adobe® Photoshop® |
| [LiFeDataSource](./lifedatasource) | Definisce la classe LnkeDataSource che contiene informazioni sul file collegato esterno. Fa parte dell'API di manipolazione del formato file PSD che aiuta a modificare i file Adobe® Photoshop® |
| [LinkDataSource](./linkdatasource) | Definisce la classe LinkDataSource che contiene informazioni su un file collegato o una risorsa nel file PSD. |
| [LinkResource](./linkresource) | Definisce la classe LinkResource che contiene informazioni sui file collegati o incorporati nell'immagine in formato PSD. La risorsa collegamento può contenere diversi[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) istanze a cui possono accedere gli indicizzatori in qualsiasi classe derivata. |
| [Lnk2Resource](./lnk2resource) | Definisce la classe che contiene informazioni sui file incorporati nell'immagine in formato PSD. La risorsa di collegamento può contenere diversi[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource) istanze a cui è possibile accedere dall'indicizzatore. |
| [Lnk3Resource](./lnk3resource) | Definisce la classe che contiene informazioni su un file incorporato nel formato PSD a 32 bit per immagine di canale. La risorsa di collegamento può contenere diversi[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource) istanze a cui è possibile accedere dall'indicizzatore. |
| [LnkeResource](./lnkeresource) | Definisce la classe LnkeResource che contiene informazioni su file o risorse collegati esterni nell'immagine in formato PSD. La risorsa di collegamento può contenere diversi[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource) istanze a cui è possibile accedere dall'indicizzatore. Questa è una parte dell'API di manipolazione del formato file PSD che aiuta a modificare i file Adobe® Photoshop® a livello di codice |
| [LnsrResource](./lnsrresource) | Classe lnsrResource. |
| [Lr16Resource](./lr16resource) | La risorsa lr32. |
| [Lr32Resource](./lr32resource) | La risorsa lr32. |
| [LspfResource](./lspfresource) | Impostazioni di protezione del livello |
| [LuniResource](./luniresource) | Risorsa nome livello |
| [LyidResource](./lyidresource) | Classe LyidResource. |
| [MixrResource](./mixrresource) | Classe MixrResource. Risorsa del livello di regolazione del mixer dei canali |
| [MlstResource](./mlstresource) | La risorsa mlst. Questa classe, tra le altre cose, contiene informazioni sulla posizione del livello sulla timeline. |
| [NvrtResource](./nvrtresource) | Classe NvrtResource. Risorsa di Inverti livello di regolazione. |
| [OSTypeStructure](./ostypestructure) | Rappresenta la struttura del tipo di sistema operativo. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry) | Rappresenta il[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) registro risorse. |
| [PattResource](./pattresource) | Classe PattResource. Risorsa con dati modello |
| [PattResourceData](./pattresourcedata) | La classe per cui archiviare i dati del modello[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource) risorsa. |
| [PhflResource](./phflresource) | Classe PhflResource. Risorsa del livello di regolazione dell'esposizione 2 Versione ( = 3 ) o ( = 2 ) 12 4 byte ciascuno per colore XYZ (solo nella versione 3) 10 2 byte di spazio colore seguito da 4 * 2 byte componente colore (solo nella versione 2) 4 Densità 1 Mantieni luminosità |
| [PhflResourceVersion2](./phflresourceversion2) | Classe PhflResource. Risorsa del livello di regolazione dell'esposizione 2 Versione ( = 3 ) o ( = 2 ) 12 4 byte ciascuno per colore XYZ (solo nella versione 3) 10 2 byte di spazio colore seguito da 4 * 2 byte componente colore (solo nella versione 2) 4 Densità 1 Mantieni luminosità |
| [PhflResourceVersion3](./phflresourceversion3) | Classe PhflResource. Risorsa del livello di regolazione dell'esposizione 2 Versione ( = 3 ) o ( = 2 ) 12 4 byte ciascuno per colore XYZ (solo nella versione 3) 10 2 byte di spazio colore seguito da 4 * 2 byte componente colore (solo nella versione 2) 4 Densità 1 Mantieni luminosità |
| [PlacedResource](./placedresource) | Definisce la classe PlacedResource che contiene informazioni comuni su un livello posizionato o un livello oggetto avanzato nel file PSD. Viene utilizzato per supportare i livelli oggetto intelligente nelle immagini di Adobe® Photoshop®. |
| [PlLdResource](./plldresource) | Definisce la classe PlLdResource che contiene informazioni su un livello inserito nel file PSD. Viene utilizzato per supportare i livelli di oggetti intelligenti nelle immagini di Adobe® Photoshop®. È stato sostituito da SoLdResource in Adobe® Photoshop® CS3 |
| [PtFlResource](./ptflresource) | Classe PtFlResource. Contiene i dati del livello di riempimento pattern. |
| [ShmdResource](./shmdresource) | Classe ShmdResource. Impostazioni dei metadati |
| [SmartObjectResource](./smartobjectresource) | Definisce la classe SmartObjectResource che contiene informazioni su un livello di oggetti intelligenti in un file PSD. Is è la classe base per le risorse Sold e Sole utilizzata per supportare i livelli di oggetti intelligenti nelle immagini di Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator) | Definisce la classe SmartResourceCreator che può creare risorse PlLd, SoLd e SoLe. Viene utilizzato per supportare i livelli di oggetti intelligenti nelle immagini di Adobe® Photoshop®. |
| [SoCoResource](./socoresource) | Classe SoCoResource. Questa risorsa contiene informazioni sui livelli di riempimento colore |
| [SoLdResource](./soldresource) | Definisce la classe SoLdResource che contiene informazioni su un livello di oggetti intelligenti in un file PSD. Viene utilizzato per supportare i livelli di oggetti intelligenti nelle immagini di Adobe® Photoshop®. |
| [SoLeResource](./soleresource) | Definisce la classe SoLeResource che contiene informazioni su un livello di oggetti intelligenti in un file PSD. Viene utilizzato per supportare livelli di oggetti intelligenti con collegamenti a file esterni nelle immagini di Adobe® Photoshop®. |
| [Txt2Resource](./txt2resource) | Classe risorsa Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo) | Contiene informazioni sul tipo di carattere dello strumento. |
| [TypeToolInfo6Resource](./typetoolinfo6resource) | Il tipo di informazioni sull'utensile. Per la versione PSD superiore o uguale alla 6.0. |
| [TypeToolInfoResource](./typetoolinforesource) | Il tipo di informazioni sull'utensile. Per la versione PSD inferiore a 6.0. |
| [TypeToolLineInfo](./typetoollineinfo) | Digita info linea utensile. |
| [TypeToolStyleInfo](./typetoolstyleinfo) | Digitare le informazioni sullo stile dello strumento. |
| [UnknownResource](./unknownresource) | La risorsa sconosciuta. |
| [VectorPathDataResource](./vectorpathdataresource) | Classe VectorPathDataResource. Questa risorsa contiene informazioni sulla maschera di livello vettoriale |
| [VibAResource](./vibaresource) | Risorsa VibA. |
| [VmskResource](./vmskresource) | Classe VmskResource. Questa risorsa contiene informazioni sulla maschera di livello vettoriale |
| [VogkResource](./vogkresource) | La risorsa dei dati di origine del vettore. |
| [VsmsResource](./vsmsresource) | Classe VsmsResource. Questa risorsa contiene informazioni sulla maschera di livello vettoriale |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader) | Il[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) caricatore di risorse. |
| [IPlacedLayerResource](./iplacedlayerresource) | Definisce l'interfaccia IPlacedLayerResource che contiene informazioni su un livello inserito nel file PSD. Is è un'interfaccia di markup utilizzata per designare le risorse PlLd, Venduto e Sole nelle immagini di Adobe® Photoshop®. Is viene utilizzato per supportare i livelli di oggetti intelligenti in le immagini di Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource) | Definisce l'interfaccia ISmartObjectLayerResource che contiene informazioni su una risorsa del livello di oggetti intelligenti nel file PSD. È anche un'interfaccia di markup utilizzata per designare sia le risorse vendute che quelle esclusive nelle immagini di Adobe® Photoshop®. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [LayerLockType](./layerlocktype) | Opzioni di blocco dei livelli |
| [LayerSectionSubtype](./layersectionsubtype) | Il sottotipo di sezione |
| [LayerSectionType](./layersectiontype) | Il tipo di sezione del livello |
| [LinkDataSourceType](./linkdatasourcetype) | Definisce l'enumerazione LinkDataSourceType per le origini dati nella risorsa di collegamento PSD. |
| [LnsrResourceType](./lnsrresourcetype) | Possibili tipi di risorse Lnsr scoperti |
| [PlacedLayerType](./placedlayertype) | Definisce l'enumerazione PlacedLayerType per la risorsa PlLd del livello posizionato. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum) | Possibili colori dell'impostazione del colore del foglio. È il colore decorativo dell'interfaccia utente del livello nell'elenco dei livelli in PS |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
