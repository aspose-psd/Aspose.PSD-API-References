---
title: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "L'espace de noms contient les entités du format de fichier PSD contenues dans les calques"
type: docs
weight: 300
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/
---
{{< psd/tize >}}
L'espace de noms contient les entités du format de fichier PSD contenues dans les calques.

## Classes

| Classe | Description |
| --- | --- |
| [AbddResource](./abddresource/) | Les données d'information du plan de travail. |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | Classe de base pour les ressources de calque de réglage |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | La section contenant les données animées. |
| [ArtBResource](./artbresource/) | Les données d'information du plan de travail pour [`Resources`](../aspose.psd.fileformats.psd.layers/layer/resources/). |
| [ArtDResource](./artdresource/) | Les données d'information du plan de travail pour [`GlobalLayerResources`](../aspose.psd.fileformats.psd/psdimage/globallayerresources/). |
| [BaseArtboardInfoResource](./baseartboardinforesource/) | Ressource de données d'information du plan de travail. |
| [BaseFxResource](./basefxresource/) | Ressource d'effets de base |
| [BaseLayerSectionResource](./baselayersectionresource/) | Classe de base pour les ressources de section de calque |
| [BlncResource](./blncresource/) | La classe BlncResource est une ressource du calque de réglage de couleur. |
| [BlwhResource](./blwhresource/) | La classe BlwhResource est une ressource du calque de réglage noir et blanc. |
| [BooleanResource](./booleanresource/) | Classe BooleanResource. C'est une pseudo‑ressource. Photoshop ne l'a pas |
| [BritResource](./britresource/) | Classe BritResource. Ressource du calque de réglage Luminosité/Contraste |
| [CgEdResource](./cgedresource/) | Classe CgEdResource. Données supplémentaires du générateur de contenu (Photoshop CS5) |
| [ClassID](./classid/) | L'objet PSD Class ID. |
| [ClblResource](./clblresource/) | Classe ClblResource. Cette ressource contient des informations sur le mélange de l'élément découpé. |
| [CmlsResource](./cmlsresource/) | Classe CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) possède 6 plages de couleurs où vous pouvez modifier les paramètres HSV. Chaque plage possède 4 points clés pour identifier les bordures de la plage. Et c'est ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Gestionnaire du calque de réglage Courbes qui manipule les courbes |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Gestionnaire du calque de réglage Courbes qui manipule la carte des pixels |
| [CurvesManager](./curvesmanager/) | Classe de base pour gérer CurvResource |
| [CurvResource](./curvresource/) | Classe CurvResource. Ressource du calque de réglage Courbes 1 octet - 0 si utilisation des courbes, 1 si utilisation des pixels sur la carte ; si 0 alors : 2 octets - short. Valeur par défaut 1. 4 octets - int. Utilisé uniquement le dernier octet par bit. Le premier bit correspond à 1 canal, le quatrième bit à 4 canaux, par exemple 2 octets - short nombre de points. 4 octets * nombre de points - points de la courbe. 2 short : première position, deuxième hauteur. 4 octets - mot "Crv ". 2 octets - short valeur par défaut 4 pour les Courbes. 4 octets - int. Valeur par défaut 1. 4 octets - nombre de points. 4 octets * nombre de points - points de la courbe. 2 short : première position, deuxième hauteur. 0-4 octets - En-tête pour être plié pour quatre si 1 alors : 2 octets - short. Valeur par défaut 1. 4 octets - int. Utilisé uniquement le dernier octet. Un canal est dans un bit. Le premier bit pour 1 canal, le quatrième bit pour 4 canaux, par exemple 256 * nombre de canaux modifiés - valeurs ordonnées du canal dans la plage 0 - 255 4 octets - mot "Crv " 2 octets - short. Valeur par défaut 3 pour les pixels sur la carte 4 octets - int Nombre de canaux (2 + 256) octets - short 2 pour l'index du canal, 256 sont les valeurs ordonnées du canal dans la plage 0 - 255 |
| [CustResource](./custresource/) | Classe CustResource. Cette ressource contient des informations sur le mélange de l'élément découpé. |
| [ExpaResource](./exparesource/) | Classe ExpaResource. Ressource du calque d'ajustement d'exposition |
| [FillLayerResource](./filllayerresource/) | Classe de base pour les ressources de calque de remplissage. |
| [FilterEffectMaskData](./filtereffectmaskdata/) | La classe de données du masque de filtre. |
| [FXidResource](./fxidresource/) | La ressource d'effets de filtre contient des canaux, un masque utilisateur et un masque de feuille pour le filtre intelligent. |
| [FxrpResource](./fxrpresource/) | Classe FxrpResource. Le point de référence du calque |
| [GdFlResource](./gdflresource/) | Classe GdFlResource. Cette ressource contient des informations sur le mélange d'un élément découpé. |
| [GrdmResource](./grdmresource/) | Classe GrdmResource. Contient des informations sur le calque Gradient-Map. |
| [Hue2Resource](./hue2resource/) | Classe Hue2Resource. Ressource du calque d'ajustement d'exposition |
| [IfxsResource](./ifxsresource/) | Ressource Ifxs (ressource d'effets de calque de groupe) |
| [ImfxResource](./imfxresource/) | Ressource Imfx (ressource multi-effets) |
| [InfxResource](./infxresource/) | Classe InfxResource. Cette ressource contient des informations sur le mélange d'un élément découpé. |
| [IopaResource](./ioparesource/) | Classe IopaResource. Cette ressource contient des informations sur la propriété d'opacité de remplissage du formulaire de style du calque |
| [KnkoResource](./knkoresource/) | Classe KnkoResource. Cette ressource contient des informations sur le mélange d'un élément découpé. |
| [LayerSectionResource](./layersectionresource/) | La ressource de section de calque. |
| [LclrResource](./lclrresource/) | Classe LclrResource. Cette ressource contient des informations sur la couleur du calque dans la liste des calques de PS. C’est uniquement |
| [LevelChannel](./levelchannel/) | Classe pour travailler avec les canaux dans le calque d'ajustement des niveaux |
| [LevlResource](./levlresource/) | Classe LevlResource. Ressource du calque d'ajustement d'exposition |
| [Lfx2Resource](./lfx2resource/) | Ressource Lfx2 (ressource d'effets réguliers) |
| [LiFdDataSource](./lifddatasource/) | Définit la classe de source de données liFD dans le fichier PSD qui contient des informations sur un fichier intégré. Cela fait partie de l'API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop®. |
| [LiFeDataSource](./lifedatasource/) | Définit la classe LnkeDataSource qui contient des informations sur un fichier lié externe. Cela fait partie de l'API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop®. |
| [LinkDataSource](./linkdatasource/) | Définit la classe LinkDataSource qui contient des informations sur un fichier lié ou un actif dans le fichier PSD. |
| [LinkResource](./linkresource/) | Définit la classe LinkResource qui contient des informations sur les fichiers liés ou intégrés dans l'image au format PSD. La ressource de lien peut contenir plusieurs [`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) instances qui peuvent être accessibles via des indexeurs dans toute classe dérivée. |
| [LmskResource](./lmskresource/) | La ressource LMsk. |
| [Lnk2Resource](./lnk2resource/) | Définit la classe qui contient des informations sur les fichiers intégrés dans l'image au format PSD. La ressource de lien peut contenir plusieurs [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances qui peuvent être accessibles via l'indexeur. |
| [Lnk3Resource](./lnk3resource/) | Définit la classe qui contient des informations sur un fichier intégré dans l'image au format PSD 32 bits par canal. La ressource de lien peut contenir plusieurs [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances qui peuvent être accessibles via l'indexeur. |
| [LnkeResource](./lnkeresource/) | Définit la classe LnkeResource qui contient des informations sur les fichiers ou ressources externes liés dans l’image au format PSD. La ressource de lien peut contenir plusieurs instances [`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) qui peuvent être accessibles via l’indexeur. Il s’agit d’une partie de l’API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop® de manière programmatique. |
| [LnsrResource](./lnsrresource/) | Classe lnsrResource. |
| [Lr16Resource](./lr16resource/) | La ressource lr16. |
| [Lr32Resource](./lr32resource/) | La ressource lr32. |
| [LrXxResource](./lrxxresource/) | La ressource lrXX. |
| [LsdkResource](./lsdkresource/) | La ressource de calque lsdk (ressource de section de calque imbriquée). |
| [LspfResource](./lspfresource/) | Paramètres protégés du calque |
| [LuniResource](./luniresource/) | Ressource du nom du calque |
| [LyidResource](./lyidresource/) | Classe LyidResource. |
| [LyvrResource](./lyvrresource/) | La ressource représentant la version Photoshop du calque. |
| [MixrResource](./mixrresource/) | Classe MixrResource. Ressource du calque de réglage du mélangeur de canaux |
| [MlstResource](./mlstresource/) | La ressource mlst. Cette classe, entre autres, contient des informations sur la position du calque sur la chronologie. |
| [NvrtResource](./nvrtresource/) | Classe NvrtResource. Ressource du calque de réglage d’inversion. |
| [OSTypeStructure](./ostypestructure/) | Représente la structure de type OS. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | Représente le registre des ressources [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [PathShape](./pathshape/) | La figure des nœuds de la courbe de Bézier. |
| [PattResource](./pattresource/) | Classe PattResource. Ressource avec des données de motif |
| [PattResourceData](./pattresourcedata/) | La classe pour stocker les données de motif pour la ressource [`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PhflResource](./phflresource/) | Classe PhflResource. Ressource du calque de réglage d’exposition Version 2 ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 2 octets espace colorimétrique suivi de 4 * 2 octets composante couleur (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité |
| [PhflResourceVersion2](./phflresourceversion2/) | Classe PhflResource. Ressource du calque de réglage d’exposition Version 2 ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 2 octets espace colorimétrique suivi de 4 * 2 octets composante couleur (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité |
| [PhflResourceVersion3](./phflresourceversion3/) | Classe PhflResource. Ressource du calque de réglage d’exposition Version 2 ( = 3 ) ou ( = 2 ) 12 4 octets chacun pour la couleur XYZ (uniquement dans la version 3) 10 2 octets espace colorimétrique suivi de 4 * 2 octets composante couleur (uniquement dans la version 2) 4 Densité 1 Préserver la luminosité |
| [PlacedResource](./placedresource/) | Définit la classe PlacedResource qui contient des informations communes sur un calque placé ou un calque d’objet dynamique dans le fichier PSD. Elle est utilisée pour prendre en charge les calques d’objets dynamiques dans les images Adobe® Photoshop®. |
| [PlLdResource](./plldresource/) | Définit la classe PlLdResource qui contient des informations sur un calque placé dans le fichier PSD. Elle est utilisée pour prendre en charge les calques d’objets dynamiques dans les images Adobe® Photoshop®. Elle a été remplacée par SoLdResource dans Adobe® Photoshop® CS3. |
| [PostResource](./postresource/) | Classe PostResource. Paramètres de posterisation du calque. |
| [PtFlResource](./ptflresource/) | Classe PtFlResource. Contient les données du calque de remplissage de motif. |
| [ShmdResource](./shmdresource/) | Classe ShmdResource. Paramètres des métadonnées |
| [SmartObjectResource](./smartobjectresource/) | Définit la classe SmartObjectResource qui contient des informations sur un calque d’objet dynamique dans un fichier PSD. C’est la classe de base pour les ressources Sold et Sole qui est utilisée pour prendre en charge les calques d’objets dynamiques dans les images Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator/) | Définit la classe SmartResourceCreator qui peut créer les ressources PlLd, SoLd et SoLe. Elle est utilisée pour prendre en charge les calques d’objets intelligents dans les images Adobe® Photoshop®. |
| [SoCoResource](./socoresource/) | Classe SoCoResource. Cette ressource contient des informations sur les calques de remplissage de couleur. |
| [SoLdResource](./soldresource/) | Définit la classe SoLdResource qui contient des informations sur un calque d’objet intelligent dans un fichier PSD. Elle est utilisée pour prendre en charge les calques d’objets intelligents dans les images Adobe® Photoshop®. |
| [SoLeResource](./soleresource/) | Définit la classe SoLeResource qui contient des informations sur un calque d’objet intelligent dans un fichier PSD. Elle est utilisée pour prendre en charge les calques d’objets intelligents avec des liens de fichiers externes dans les images Adobe® Photoshop®. |
| [Txt2Resource](./txt2resource/) | Classe de ressource Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo/) | Contient des informations sur la police de l’outil de texte. |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | Les informations de l’outil de texte. Pour les versions PSD supérieures ou égales à 6.0. |
| [TypeToolInfoResource](./typetoolinforesource/) | Les informations de l’outil de texte. Pour les versions PSD inférieures à 6.0. |
| [TypeToolLineInfo](./typetoollineinfo/) | Informations de ligne de l’outil de texte. |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | Informations de style de l’outil de texte. |
| [UnknownResource](./unknownresource/) | La ressource inconnue. |
| [VectorPath](./vectorpath/) | La classe qui contient les chemins vectoriels. |
| [VectorPathDataResource](./vectorpathdataresource/) | Classe VectorPathDataResource. Cette ressource contient des informations sur le masque de calque vectoriel. |
| [VibAResource](./vibaresource/) | Ressource VibA. |
| [VmskResource](./vmskresource/) | Classe VmskResource. Cette ressource contient des informations sur le masque de calque vectoriel. |
| [VogkResource](./vogkresource/) | La ressource de données d’origine vectorielle. |
| [VsmsResource](./vsmsresource/) | Classe VsmsResource. Cette ressource contient des informations sur le masque de calque vectoriel. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | Le chargeur de ressource [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [IPath](./ipath/) | L’interface décrit l’ensemble des chemins présents dans un calque de forme. |
| [IPathShape](./ipathshape/) | La forme à partir des nœuds de la courbe de Bézier. |
| [IPlacedLayerResource](./iplacedlayerresource/) | Définit l’interface IPlacedLayerResource qui contient des informations sur un calque placé dans le fichier PSD. C’est une interface de balisage utilisée pour désigner les ressources PlLd, Sold et Sole dans les images Adobe® Photoshop®. Elle est utilisée pour prendre en charge les calques d’objets intelligents dans les images Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | Définit l’interface ISmartObjectLayerResource qui contient des informations sur une ressource de calque d’objet intelligent dans le fichier PSD. C’est également une interface de balisage utilisée pour désigner les ressources Sold et Sole dans les images Adobe® Photoshop®. |
## Énumération

| Énumération | Description |
| --- | --- |
| [LayerLockType](./layerlocktype/) | Options de verrouillage du calque |
| [LayerSectionSubtype](./layersectionsubtype/) | Le sous-type de section |
| [LayerSectionType](./layersectiontype/) | Le type de section du calque |
| [LinkDataSourceType](./linkdatasourcetype/) | Définit l'énumération LinkDataSourceType pour les sources de données dans la ressource de lien PSD. |
| [LnsrResourceType](./lnsrresourcetype/) | Types de ressources Lnsr possibles découverts |
| [PlacedLayerType](./placedlayertype/) | Définit l'énumération PlacedLayerType pour la ressource de calque placé PlLd. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Couleurs possibles du paramètre de couleur de la feuille. C'est la couleur décorative de l'interface utilisateur du calque dans la liste des calques dans PS. |


