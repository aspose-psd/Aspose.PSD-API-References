---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Référence de l'API Aspose.PSD pour .NET
description: Lespace de noms contient des entités de format de fichier PSD contenues dans des couches.
type: docs
weight: 270
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/
---
L'espace de noms contient des entités de format de fichier PSD contenues dans des couches.

## Des classes

| Classer | La description |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource) | Classe de base pour les ressources de la couche d'ajustements |
| [AnimatedDataSectionStructure](./animateddatasectionstructure) | La section avec des données animées. |
| [BlncResource](./blncresource) | La classe BlncResource est une ressource de Color Adjustment Layer. |
| [BlwhResource](./blwhresource) | La classe BlwhResource est une ressource du calque de réglage noir et blanc. |
| [BooleanResource](./booleanresource) | Classe BooleanResource. C'est une pseudo ressource. Photoshop ne l'a pas |
| [BritResource](./britresource) | Classe BritResource. Ressource de la couche de réglage de la luminosité/du contraste |
| [CgEdResource](./cgedresource) | Classe CgEdResource. Données supplémentaires du générateur de contenu (Photoshop CS5) |
| [ClassID](./classid) | L'objet ID de classe PSD. |
| [ClblResource](./clblresource) | Classe ClblResource. Cette ressource contient des informations sur le mélange d'éléments tronqués. |
| [CmlsResource](./cmlsresource) | Classe CmlsResource. |
| [ColorRangeHsl](./colorrangehsl) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource) dispose de 6 gammes de couleurs où vous pouvez modifier les paramètres HSV. Chaque gamme a 4 points clés pour identifier les limites de la gamme. Et c'est ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager) | Gestionnaire pour le calque de réglage des courbes qui manipule les courbes |
| [CurvesDiscreteManager](./curvesdiscretemanager) | Gestionnaire pour le calque de réglage des courbes qui manipule la carte des pixels |
| [CurvesManager](./curvesmanager) | Classe de base pour gérer CurvResource |
| [CurvResource](./curvresource) | Classe CurvResource. Ressource d'ajustement des courbes Layer 1 octet - 0 si utilise des courbes, 1 si utilise des pixels sur la carte si 0 alors : 2 octets - court. La valeur par défaut est 1 4 octets - int. Utilisé uniquement dernier octet par bit. Le premier bit est pour 1 canal, le quatrième bit pour 4 canaux par exemple 2 octets - nombre de points courts 4 octets * nombre de points - points de la courbe 2 court : première position, deuxième hauteur 4 octets - mot "Crv" 2 octets - court par défaut est 4 pour Curves 4 octets - int. La valeur par défaut est 1 4 octets - nombre de points 4 octets * nombre de points - points de la courbe 2 court : première position, deuxième hauteur 0-4 octets - Interlignage à plier pour quatre si 1 alors : 2 octets - court. La valeur par défaut est 1 4 octets - int. Utilisé uniquement le dernier octet. Un canal est dans un bit. Le premier bit est pour 1 canal, le quatrième bit pour 4 canaux par exemple 256 * nombre de canaux modifiés - valeurs ordonnées du canal dans la plage 0 - 255 4 octets - mot "Crv " 2 octets - court. La valeur par défaut est 3 pour les pixels sur map 4 octets - int Nombre de canaux (2 + 256) octets - court 2 pour l'index de canal, 256 correspond aux valeurs ordonnées du canal dans la plage 0 - 255 |
| [CustResource](./custresource) | Classe CustResource. Cette ressource contient des informations sur le mélange d'éléments tronqués. |
| [ExpaResource](./exparesource) | Classe ExpaResource. Ressource de la couche de réglage de l'exposition |
| [FillLayerResource](./filllayerresource) | Classe de base pour les ressources de couche de remplissage |
| [FilterEffectMaskData](./filtereffectmaskdata) | La classe de données du masque de filtre. |
| [FXidResource](./fxidresource) | La ressource Filter Effects contient des canaux, un masque utilisateur et un masque de feuille pour le filtre intelligent. |
| [FxrpResource](./fxrpresource) | Classe FxrpResource. Le point de référence de la couche |
| [GdFlResource](./gdflresource) | Classe GdFlResource. Cette ressource contient des informations sur le mélange d'éléments tronqués. |
| [Hue2Resource](./hue2resource) | Classe Hue2Resource. Ressource de la couche de réglage de l'exposition |
| [InfxResource](./infxresource) | Class InfxResource. Cette ressource contient des informations sur le mélange d'éléments tronqués. |
| [IopaResource](./ioparesource) | Class IopaResource. Cette ressource contient des informations sur la propriété d'opacité de remplissage du style de calque form |
| [KnkoResource](./knkoresource) | Class KnkoResource. Cette ressource contient des informations sur le mélange d'éléments tronqués. |
| [LayerSectionResource](./layersectionresource) | La ressource de section de couche. |
| [LclrResource](./lclrresource) | Classe LclrResource. Cette ressource contient des informations sur la couleur du calque dans la liste des calques est PS. C'est seulement |
| [LevelChannel](./levelchannel) | Classe pour travailler avec les canaux dans la couche de réglage des niveaux |
| [LevlResource](./levlresource) | Classe LevlResource. Ressource de la couche de réglage de l'exposition |
| [Lfx2Resource](./lfx2resource) | ressource Lfx2 (ressource d'effets) |
| [LiFdDataSource](./lifddatasource) | Définit la classe de source de données liFD dans le fichier PSD qui contient des informations sur un fichier intégré. Ceci fait partie de l'API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop® |
| [LiFeDataSource](./lifedatasource) | Définit la classe LnkeDataSource qui contient des informations sur le fichier lié externe. Ceci fait partie de l'API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop® |
| [LinkDataSource](./linkdatasource) | Définit la classe LinkDataSource qui contient des informations sur un fichier lié ou un actif dans le fichier PSD. |
| [LinkResource](./linkresource) | Définit la classe LinkResource qui contient des informations sur les fichiers liés ou intégrés dans l'image au format PSD. La ressource de lien peut contenir plusieurs[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) instances accessibles par les indexeurs dans n'importe quelle classe dérivée. |
| [Lnk2Resource](./lnk2resource) | Définit la classe qui contient des informations sur les fichiers intégrés dans l'image au format PSD. La ressource de lien peut contenir plusieurs[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource) instances accessibles par l'indexeur. |
| [Lnk3Resource](./lnk3resource) | Définit la classe qui contient des informations sur un fichier embarqué au format PSD 32 bits par canal image. La ressource lien peut contenir plusieurs[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource) instances accessibles par indexer. |
| [LnkeResource](./lnkeresource) | Définit la classe LnkeResource qui contient des informations sur les fichiers ou actifs externes liés dans l'image au format PSD. La ressource de lien peut contenir plusieurs[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource) instances accessibles par l'indexeur. Il s'agit d'une partie de l'API de manipulation du format de fichier PSD qui permet de modifier les fichiers Adobe® Photoshop® par programmation |
| [LnsrResource](./lnsrresource) | Classe lnsrResource. |
| [Lr16Resource](./lr16resource) | La ressource lr32. |
| [Lr32Resource](./lr32resource) | La ressource lr32. |
| [LspfResource](./lspfresource) | Paramètres protégés par calque |
| [LuniResource](./luniresource) | Nom de la couche ressource |
| [LyidResource](./lyidresource) | Classe LyidResource. |
| [MixrResource](./mixrresource) | Classe MixrResource. Ressource de Channel Mixer Adjustment Layer |
| [MlstResource](./mlstresource) | La ressource mlst. Cette classe, entre autres, contient des informations sur la position du calque sur la timeline. |
| [NvrtResource](./nvrtresource) | Classe NvrtResource. Ressource du calque d'ajustement inversé. |
| [OSTypeStructure](./ostypestructure) | Représente la structure du type de système d'exploitation. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry) | Représente le[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) registre des ressources. |
| [PattResource](./pattresource) | Classe PattResource. Ressource avec modèle data |
| [PattResourceData](./pattresourcedata) | La classe pour stocker les données de modèle pour[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource) ressource. |
| [PhflResource](./phflresource) | Classe PhflResource. Ressource de la couche de réglage de l'exposition 2 Version ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 espace colorimétrique de 2 octets suivi d'un composant de couleur 4 * 2 octets (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité |
| [PhflResourceVersion2](./phflresourceversion2) | Classe PhflResource. Ressource de la couche de réglage de l'exposition 2 Version ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 espace colorimétrique de 2 octets suivi d'un composant de couleur 4 * 2 octets (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité |
| [PhflResourceVersion3](./phflresourceversion3) | Classe PhflResource. Ressource de la couche de réglage de l'exposition 2 Version ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 espace colorimétrique de 2 octets suivi d'un composant de couleur 4 * 2 octets (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité |
| [PlacedResource](./placedresource) | Définit la classe PlacedResource qui contient des informations communes sur un calque placé ou un calque d'objet intelligent dans le fichier PSD. Est utilisé pour prendre en charge les calques d'objet intelligent dans les images Adobe® Photoshop®. |
| [PlLdResource](./plldresource) | Définit la classe PlLdResource qui contient des informations sur un calque placé dans le fichier PSD. Est utilisé pour prendre en charge les calques d'objets intelligents dans les images Adobe® Photoshop®. Il a été remplacé par SoLdResource dans Adobe® Photoshop® CS3 |
| [PtFlResource](./ptflresource) | Classe PtFlResource. Contient des données de calque de remplissage de motif. |
| [ShmdResource](./shmdresource) | Classe ShmdResource. Paramètres de métadonnées |
| [SmartObjectResource](./smartobjectresource) | Définit la classe SmartObjectResource qui contient des informations sur un calque d'objet intelligent dans un fichier PSD. Il s'agit de la classe de base pour les ressources Sold et Sole qui est utilisée pour prendre en charge les calques d'objet intelligent dans les images Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator) | Définit la classe SmartResourceCreator qui peut créer des ressources PlLd, SoLd et SoLe. Est utilisé pour prendre en charge les calques d'objets intelligents dans les images Adobe® Photoshop®. |
| [SoCoResource](./socoresource) | Classe SoCoResource. Cette ressource contient des informations sur les calques de remplissage de couleur |
| [SoLdResource](./soldresource) | Définit la classe SoLdResource qui contient des informations sur un calque d'objet intelligent dans un fichier PSD. Est utilisé pour prendre en charge les calques d'objet intelligent dans les images Adobe® Photoshop®. |
| [SoLeResource](./soleresource) | Définit la classe SoLeResource qui contient des informations sur un calque d'objet intelligent dans un fichier PSD. Est utilisé pour prendre en charge les calques d'objet intelligent avec des liens de fichiers externes dans les images Adobe® Photoshop®. |
| [Txt2Resource](./txt2resource) | classe de ressources Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo) | Contient des informations sur la police de l'outil de texte. |
| [TypeToolInfo6Resource](./typetoolinfo6resource) | Les informations sur l'outil de type. Pour la version PSD supérieure ou égale à la 6.0. |
| [TypeToolInfoResource](./typetoolinforesource) | Les informations sur l'outil de type. Pour la version PSD inférieure à 6.0. |
| [TypeToolLineInfo](./typetoollineinfo) | Saisissez les informations sur la ligne d'outil. |
| [TypeToolStyleInfo](./typetoolstyleinfo) | Saisissez les informations de style d'outil. |
| [UnknownResource](./unknownresource) | La ressource inconnue. |
| [VectorPathDataResource](./vectorpathdataresource) | Classe VectorPathDataResource. Cette ressource contient des informations sur le masque de calque vectoriel |
| [VibAResource](./vibaresource) | Ressource VibA. |
| [VmskResource](./vmskresource) | Classe VmskResource. Cette ressource contient des informations sur le masque de couche vectorielle |
| [VogkResource](./vogkresource) | La ressource de données d'origine vectorielle. |
| [VsmsResource](./vsmsresource) | Classe VsmsResource. Cette ressource contient des informations sur le masque de couche vectorielle |
## Interfaces

| Interface | La description |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader) | Le[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) chargeur de ressources. |
| [IPlacedLayerResource](./iplacedlayerresource) | Définit l'interface IPlacedLayerResource qui contient des informations sur un calque placé dans le fichier PSD. Is est une interface de balisage utilisée pour désigner les ressources PlLd, Sold et Sole dans les images Adobe® Photoshop®. Is est utilisé pour prendre en charge les calques d'objets intelligents dans les images Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource) | Définit l'interface ISmartObjectLayerResource qui contient des informations sur une ressource de couche d'objet intelligent dans le fichier PSD. Est également une interface de balisage utilisée pour désigner les ressources Vendu et Sole dans les images Adobe® Photoshop®. |
## Énumération

| Énumération | La description |
| --- | --- |
| [LayerLockType](./layerlocktype) | Options de verrouillage de calque |
| [LayerSectionSubtype](./layersectionsubtype) | Le sous-type de section |
| [LayerSectionType](./layersectiontype) | Le type de section de couche |
| [LinkDataSourceType](./linkdatasourcetype) | Définit l'énumération LinkDataSourceType pour les sources de données dans la ressource de lien PSD. |
| [LnsrResourceType](./lnsrresourcetype) | Types de ressources Lnsr possibles découverts |
| [PlacedLayerType](./placedlayertype) | Définit l'énumération PlacedLayerType pour la ressource PlLd de la couche placée. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum) | Couleurs possibles du paramètre de couleur de feuille. C'est la couleur décorative de l'interface utilisateur du calque dans la liste des calques dans PS |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
