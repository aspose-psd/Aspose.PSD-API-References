---
title: "aspose.psd"
type: docs
weight: 10
url: /fr/python-net/aspose.psd/
---


Le module est le cœur des modules imbriqués et les objets les plus basiques utilisés pour le traitement d'Aspose.PSD.

## **Classes**
| **Classe** | **Description** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | Définit un motif de fusion. Cette classe ne peut pas être héritée. |
| [Brush](/psd/python-net/aspose.psd/brush/) | La classe de base du pinceau. |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | Contient les informations de version de la build actuelle. |
| [Cache](/psd/python-net/aspose.psd/cache/) | Contient les paramètres du cache. |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | La couleur CMYK du pixel. |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | Méthodes d'aide pour travailler avec la couleur CMYK présentée comme une valeur entière signée de 32 bits.<br/>            Fournit une API similaire à la structure [CmykColor](/psd/python-net/aspose.psd/cmykcolor/).<br/>            Elle est plus légère car la couleur CMYK est présentée simplement comme un Int32 plutôt que comme une structure avec des champs internes.<br/>            Veuillez privilégier l'utilisation des méthodes statiques de cette classe lorsque cela est possible au lieu de la structure obsolète<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |
| [Color](/psd/python-net/aspose.psd/color/) | La couleur du pixel. |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | Définit des tableaux de couleurs et de positions utilisés pour interpoler le mélange de couleurs dans un dégradé multicolore. Cette classe ne peut pas être héritée. |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | Définit une carte pour la conversion des couleurs. Plusieurs méthodes de la classe [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) ajustent les couleurs de l'image en utilisant une table de remappage des couleurs, qui est un tableau de structures [ColorMap](/psd/python-net/aspose.psd/colormap/). Non héritable. |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | Définit une matrice 5 x 5 qui contient les coordonnées de l'espace RGBA. Plusieurs méthodes de la classe [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) ajustent les couleurs de l'image en utilisant une matrice de couleurs. Cette classe ne peut pas être héritée. |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | Définit un tableau de couleurs constituant une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héritable. |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | Classe d'aide pour la manipulation des palettes de couleurs. |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | Convertit les couleurs vers et depuis les structures GDI+ Color. Cette classe ne peut pas être héritée. |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | Encapsule un embout de ligne personnalisé défini par l'utilisateur. |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | Le conteneur de flux de données. |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | Représente un objet jetable. |
| [Figure](/psd/python-net/aspose.psd/figure/) | La figure. Un conteneur pour les formes. |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | Assistant pour le traitement des flux de fichiers. |
| [Font](/psd/python-net/aspose.psd/font/) | Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style. Cette classe ne peut pas être héritée. |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | Paramètres de police du rendu des formats vectoriels PSD généraux. |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | Représente les graphiques selon le moteur graphique utilisé dans l'assembly actuel. |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée. |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | Le processeur de tampon avancé. |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | Le processeur de tampon. |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | Le convertisseur de couleur. |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | L'interface de palette de couleurs. |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | Le créateur d'image. |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | Le descripteur du créateur d'image spécifiant les propriétés du créateur. Le descripteur du créateur est utilisé pour surmonter<br/>            la nécessité de contenir chaque instance de créateur d'image en mémoire et les problèmes de multithreading. |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | Le descripteur d'image. Contient les propriétés de base et les méthodes pour tous les autres types de descripteurs d'image. |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | L'exportateur d'image. Peut exporter des données du format interne Aspose.PSD vers un format de données spécifié. |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | Représente le descripteur de l'exportateur d'image. Le descripteur de l'exportateur est utilisé pour surmonter la nécessité de contenir chaque instance d'exportateur<br/>            en mémoire et les problèmes de multithreading. |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | Le chargeur d'image. |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | Le descripteur du chargeur d'image spécifiant les propriétés du chargeur. Le descripteur du chargeur est utilisé pour surmonter<br/>            la nécessité de contenir chaque instance de chargeur d'image en mémoire et les problèmes de multithreading. |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | Le convertisseur de couleur pour les formats d'image indexés. |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | Représente l'interface pour les objets avec des clés. |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | Représente un objet avec des limites. |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | Représente une forme ordonnée. Une forme ordonnée est un ensemble continu de points ayant un point de départ et un point d'arrivée.<br/>            L'ensemble continu de points connecté selon une règle spécifique. |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | Conforme aux pixels ARGB 32 bits chargés partiellement. |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | Le chargeur de pixels ARGB 64 bits. |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | Conforme aux pixels chargés partiellement. |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | Le chargeur de données partielles. |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | La palette de couleurs pasd |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | Le chargeur de pixels ARGB 32 bits de l'image raster. |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | Le chargeur de pixels de l'image raster. |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | Le chargeur de données brutes de l'image raster. |
| [Image](/psd/python-net/aspose.psd/image/) | L'image est la classe de base pour tous les types d'images. |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | Un objet [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) contient des informations sur la façon dont les couleurs des bitmap et des métafichiers sont manipulées pendant le rendu. Un objet [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) maintient plusieurs paramètres d'ajustement des couleurs, y compris les matrices d'ajustement des couleurs, les matrices d'ajustement en niveaux de gris, les valeurs de correction gamma, les tables de correspondance des couleurs et les valeurs de seuil de couleur. Pendant le rendu, les couleurs peuvent être corrigées, assombries, éclaircies et supprimées. Pour appliquer de telles manipulations, initialisez un objet [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) et transmettez le chemin de cet objet [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) (ainsi que le chemin d'une [Image](/psd/python-net/aspose.psd/image/)) à la méthode DrawImage. |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | Représente le registre des créateurs d'image. |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | Représente le registre des exportateurs d'image. |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | Représente le registre des chargeurs d'image. |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | Les options de base de l'image. |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | Classe des paramètres de redimensionnement d'image |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | Classe pour représenter une séquence d'éléments |
| [License](/psd/python-net/aspose.psd/license/) | Fournit des méthodes pour licencier le composant. |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | Représente les options de chargement. |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | Remplace la matrice GDI+. |
| [Metered](/psd/python-net/aspose.psd/metered/) | Fournit des méthodes pour définir la clé mesurée. |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | Représente un dictionnaire non générique. |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | Liste non générique d'objets |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | L'objet ayant des limites. |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | Cache pour les polices OpenType installées dans le système. |
| [Pen](/psd/python-net/aspose.psd/pen/) | Définit un objet utilisé pour dessiner des lignes, des courbes et des figures. |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | Le format des données de pixel. C'est un objet immuable. |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | La classe pour stocker les données de pixels d'image et ses limites. |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | Exception pour la licence du plugin |
| [Point](/psd/python-net/aspose.psd/point/) | Représente une paire ordonnée de coordonnées x et y entières qui définit un point dans un plan à deux dimensions. |
| [PointF](/psd/python-net/aspose.psd/pointf/) | Représente une paire ordonnée de coordonnées x et y à virgule flottante qui définit un point dans un plan à deux dimensions. |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | Représente une image raster prenant en charge les opérations graphiques raster. Cette image met en cache les données de pixel lorsque nécessaire. |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | Représente une image raster prenant en charge les opérations graphiques raster. |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | Les paramètres des données brutes |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle. |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle. |
| [Region](/psd/python-net/aspose.psd/region/) | Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée. |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | Le paramètre de résolution pour les options d'enregistrement d'image. |
| [Shape](/psd/python-net/aspose.psd/shape/) | La forme. Un ensemble continu de points connectés selon une règle spécifique. |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | Représente un segment de forme. Un segment est une ligne ou une courbe reliant deux points. |
| [Size](/psd/python-net/aspose.psd/size/) | Représente la taille. |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | Stocke une paire ordonnée de nombres à virgule flottante, généralement la largeur et la hauteur d'un rectangle. |
| [Source](/psd/python-net/aspose.psd/source/) | La source est utilisée pour contenir toutes les informations pertinentes pour un tuyau d'objet. |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | Représente un conteneur de flux fractionné qui contient le flux et fournit des routines de traitement du flux. |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | Représente un conteneur de flux qui contient le flux et fournit des routines de traitement du flux. |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | Encapsule les informations de mise en page du texte (telles que l'alignement, l'orientation et les tabulations) les manipulations d'affichage (telles que l'insertion de points de suspension et la substitution de chiffres nationaux) et les fonctionnalités OpenType. Cette classe ne peut pas être héritée. |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | L'objet prenant en charge la transparence. |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | L'image vectorielle est la classe de base pour tous les types d'images vectorielles. |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | Spécifie le type de cache à utiliser. |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | Représente le jeu de caractères utilisé. |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | Spécifie quels objets utilisent les informations d'ajustement des couleurs. |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | Spécifie les canaux individuels dans l'espace colorimétrique CMJN (cyan, magenta, jaune, noir). Cette énumération est utilisée par les méthodes SetOutputChannel. |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | Méthode de comparaison de couleur pour ajuster au voisin le plus proche |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | Spécifie les types d'images et de couleurs qui seront affectés par les paramètres d'ajustement des couleurs et des niveaux de gris d'un [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | Méthodes de quantification des couleurs |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | Spécifie le niveau de qualité à utiliser lors du compositing. |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | Spécifie le type de forme graphique à utiliser aux deux extrémités de chaque tiret dans une ligne pointillée. |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | Spécifie le style des lignes pointillées dessinées avec un objet [Pen](/psd/python-net/aspose.psd/pen/). |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | Le mode de récupération des données. |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | Méthode de tramage. |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | Les méthodes de tramage utilisées pour contrôler la conversion des couleurs. |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | L'un des formats de fichier PSD pris en charge. |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | Spécifie comment l'intérieur d'un chemin fermé est rempli. |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | Spécifie les informations de style appliquées au texte. |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | Spécifie l'unité de mesure des données fournies. |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | Spécifie les différents motifs disponibles pour les objets [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/). |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | Spécifie le type d'affichage des préfixes de raccourci clavier liés au texte. |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | Filtres d'image à utiliser |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | L'énumération [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou pivotées. |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | Spécifie les couleurs système connues. |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | Spécifie les styles de terminaison disponibles avec lesquels un objet [Pen](/psd/python-net/aspose.psd/pen/) peut terminer une ligne. |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | Spécifie comment joindre des segments de ligne ou de courbe consécutifs dans une figure (sous‑chemin) contenue dans un objet [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | Spécifie l'ordre des opérations de transformation de matrice. |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | Spécifie le niveau de conformité PDF du fichier de sortie. |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | Spécifie l'alignement d'un objet [Pen](/psd/python-net/aspose.psd/pen/) par rapport à la ligne théorique de largeur nulle. |
| [PenType](/psd/python-net/aspose.psd/pentype/) | Spécifie le type de remplissage qu'un objet [Pen](/psd/python-net/aspose.psd/pen/) utilise pour remplir les lignes. |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | La signification réelle du format des données pixel. |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | Spécifie le type de redimensionnement. |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | Énumération d'unité de résolution. |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | Spécifie de combien une image est pivotée et l'axe utilisé pour la retourner. |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | Fournit les champs qui représentent les points de référence dans [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) pour la recherche. |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | Spécifie si le lissage (antialiasing) est appliqué aux lignes et courbes ainsi qu'aux bords des zones remplies. |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | Spécifie l'alignement d'une chaîne de texte par rapport à son rectangle de mise en page. |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | L'énumération spécifie comment substituer les chiffres dans une chaîne selon la locale ou la langue de l'utilisateur. |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | Spécifie les informations d'affichage et de mise en page pour les chaînes de texte. |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | Spécifie comment tronquer les caractères d'une chaîne qui ne tient pas complètement dans une forme de mise en page. |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | Spécifie la qualité du rendu du texte. |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | Spécifie le type de transformation de déformation appliquée. |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | Spécifie comment une texture ou un dégradé est répété lorsqu'il est plus petit que la zone à remplir. |
