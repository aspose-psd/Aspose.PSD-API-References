---
title: "Aspose.PSD"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "L'espace de noms est le cœur des espaces de noms imbriqués et des objets les plus basiques utilisés pour le traitement d'Aspose.PSD."
type: docs
weight: 10
url: /fr/net/aspose.psd/
---
{{< psd/tize >}}
L'espace de noms est le cœur des espaces de noms imbriqués et les objets les plus fondamentaux utilisés pour le traitement d'Aspose.PSD.

## Classes

| Classe | Description |
| --- | --- |
| [AggregateException](./aggregateexception/) | Regroupe plusieurs exceptions. |
| [Blend](./blend/) | Définit un motif de mélange. Cette classe ne peut pas être héritée. |
| [Brush](./brush/) | La classe de brosse de base. |
| [BuildVersionInfo](./buildversioninfo/) | Contient les informations de version de la build actuelle. |
| [Cache](./cache/) | Contient les paramètres du cache. |
| [CmykColorHelper](./cmykcolorhelper/) | Méthodes d'assistance pour travailler avec la couleur CMYK présentée comme une valeur entière signée de 32 bits. Fournit une API similaire à la structure [`CmykColor`](../aspose.psd/cmykcolor/). Elle est plus légère car la couleur CMYK est présentée simplement comme un Int32 plutôt que comme une structure avec des champs internes. Veuillez privilégier l'utilisation des méthodes statiques de cette classe lorsque cela est possible plutôt que la structure [`CmykColor`](../aspose.psd/cmykcolor/) obsolète. |
| [ColorBlend](./colorblend/) | Définit des tableaux de couleurs et de positions utilisés pour interpoler le mélange de couleurs dans un dégradé multicolore. Cette classe ne peut pas être héritée. |
| [ColorMap](./colormap/) | Définit une table de correspondance pour la conversion des couleurs. Plusieurs méthodes de la classe [`ImageAttributes`](../aspose.psd/imageattributes/) ajustent les couleurs de l'image en utilisant une table de remappage des couleurs, qui est un tableau de structures [`ColorMap`](../aspose.psd/colormap/). Non héritable. |
| [ColorMatrix](./colormatrix/) | Définit une matrice 5 x 5 qui contient les coordonnées de l'espace RGBA. Plusieurs méthodes de la classe [`ImageAttributes`](../aspose.psd/imageattributes/) ajustent les couleurs de l'image en utilisant une matrice de couleurs. Cette classe ne peut pas être héritée. |
| [ColorPalette](./colorpalette/) | Définit un tableau de couleurs constituant une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héritable. |
| [ColorPaletteHelper](./colorpalettehelper/) | Classe d'assistance pour la manipulation des palettes de couleurs. |
| [ColorTranslator](./colortranslator/) | Traduit les couleurs vers et depuis les structures GDI+ Color. Cette classe ne peut pas être héritée. |
| [CompositeException](./compositeexception/) | L'exception composite |
| [CustomLineCap](./customlinecap/) | Encapsule un bouchon de ligne personnalisé défini par l'utilisateur. |
| [DataStreamSupporter](./datastreamsupporter/) | Le conteneur de flux de données. |
| [DisposableObject](./disposableobject/) | Représente un objet jetable. |
| [Figure](./figure/) | La figure. Un conteneur pour les formes. |
| [FileStreamContainer](./filestreamcontainer/) | Assistant pour le traitement des flux de fichiers. |
| [Font](./font/) | Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style. Cette classe ne peut pas être héritée. |
| [FontSettings](./fontsettings/) | Paramètres de police du rendu des formats vectoriels PSD généraux. |
| [Graphics](./graphics/) | Représente les graphiques selon le moteur graphique utilisé dans l'assembly actuel. |
| [GraphicsPath](./graphicspath/) | Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée. |
| [Image](./image/) | L'image est la classe de base pour tous les types d'images. |
| [ImageAttributes](./imageattributes/) | Un objet [`ImageAttributes`](../aspose.psd/imageattributes/) contient des informations sur la façon dont les couleurs des bitmap et des métafichiers sont manipulées pendant le rendu. Un objet [`ImageAttributes`](../aspose.psd/imageattributes/) maintient plusieurs paramètres d'ajustement des couleurs, incluant les matrices d'ajustement des couleurs, les matrices d'ajustement en niveaux de gris, les valeurs de correction gamma, les tables de correspondance des couleurs et les valeurs de seuil de couleur. Pendant le rendu, les couleurs peuvent être corrigées, assombries, éclaircies et supprimées. Pour appliquer de telles manipulations, initialisez un objet [`ImageAttributes`](../aspose.psd/imageattributes/) et transmettez le chemin de cet objet [`ImageAttributes`](../aspose.psd/imageattributes/) (ainsi que le chemin d'une [`Image`](../aspose.psd/image/)) à la méthode DrawImage. |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | Représente le registre des créateurs d'images. |
| [ImageExportersRegistry](./imageexportersregistry/) | Représente le registre des exportateurs d'images. |
| [ImageLoadersRegistry](./imageloadersregistry/) | Représente le registre des chargeurs d'images. |
| [ImageOptionsBase](./imageoptionsbase/) | Les options de base de l'image. |
| [ImageResizeSettings](./imageresizesettings/) | Classe des paramètres de redimensionnement d'image |
| [IntRange](./intrange/) | Classe pour représenter une séquence d'éléments |
| [License](./license/) | Fournit des méthodes pour licencier le composant. |
| [LoadOptions](./loadoptions/) | Représente les options de chargement. |
| [Matrix](./matrix/) | Remplace la matrice GDI+. |
| [Metered](./metered/) | Fournit des méthodes pour définir la clé mesurée. |
| [NonGenericDictionary](./nongenericdictionary/) | Représente un dictionnaire non générique. |
| [NonGenericList](./nongenericlist/) | Liste non générique d'objets |
| [ObjectWithBounds](./objectwithbounds/) | L'objet ayant des limites. |
| [OpenTypeFontsCache](./opentypefontscache/) | Cache pour les polices OpenType installées dans le système. |
| [Pen](./pen/) | Définit un objet utilisé pour dessiner des lignes, des courbes et des figures. |
| [PixelDataFormat](./pixeldataformat/) | Le format des données de pixel. C'est un objet immuable. |
| [PixelsData](./pixelsdata/) | La classe permettant de stocker les données des pixels d’image et leurs limites. |
| [PluginLicenseException](./pluginlicenseexception/) | Exception pour la licence du plugin |
| [ProgressEventHandler](./progresseventhandler/) | Référence de fonction de gestionnaire d’événement de progression |
| [RasterCachedImage](./rastercachedimage/) | Représente une image raster prenant en charge les opérations graphiques raster. Cette image met en cache les données de pixel lorsque nécessaire. |
| [RasterImage](./rasterimage/) | Représente une image raster prenant en charge les opérations graphiques raster. |
| [RawDataSettings](./rawdatasettings/) | Les paramètres des données brutes |
| [Region](./region/) | Décrit l’intérieur d’une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée. |
| [ResolutionSetting](./resolutionsetting/) | Le paramètre de résolution pour les options d’enregistrement d’image. |
| [Shape](./shape/) | La forme. Un ensemble continu de points connectés selon une règle spécifique. |
| [ShapeSegment](./shapesegment/) | Représente un segment de forme. Un segment est une ligne ou une courbe reliant deux points. |
| [Source](./source/) | La source est utilisée pour contenir toutes les informations pertinentes pour un pipeline d’objet. |
| [SplitStreamContainer](./splitstreamcontainer/) | Représente un conteneur de flux fractionné qui contient le flux et fournit des routines de traitement du flux. |
| [StreamContainer](./streamcontainer/) | Représente un conteneur de flux qui contient le flux et fournit des routines de traitement du flux. |
| [StringFormat](./stringformat/) | Encapsule les informations de mise en page du texte (telles que l’alignement, l’orientation et les tabulations), les manipulations d’affichage (telles que l’insertion d’ellipse et la substitution de chiffres nationaux) et les fonctionnalités OpenType. Cette classe ne peut pas être héritée. |
| [TransparencySupporter](./transparencysupporter/) | L’objet prenant en charge la transparence. |
| [VectorImage](./vectorimage/) | L’image vectorielle est la classe de base pour tous les types d’images vectorielles. |
## Structures

| Structure | Description |
| --- | --- |
| [CmykColor](./cmykcolor/) | La couleur CMYK du pixel. |
| [Color](./color/) | La couleur du pixel. |
| [Point](./point/) | Représente une paire ordonnée de coordonnées x et y entières qui définit un point dans un plan bidimensionnel. |
| [PointF](./pointf/) | Représente une paire ordonnée de coordonnées x et y à virgule flottante qui définit un point dans un plan bidimensionnel. |
| [Rectangle](./rectangle/) | Stocke un ensemble de quatre entiers qui représentent la position et la taille d’un rectangle. |
| [RectangleF](./rectanglef/) | Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle. |
| [Size](./size/) | Représente la taille. |
| [SizeF](./sizef/) | Stocke une paire ordonnée de nombres à virgule flottante, généralement la largeur et la hauteur d'un rectangle. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | Le processeur de tampon avancé. |
| [IBufferProcessor](./ibufferprocessor/) | Le processeur de tampon. |
| [IColorConverter](./icolorconverter/) | Le convertisseur de couleur. |
| [IColorPalette](./icolorpalette/) | L'interface de palette de couleur. |
| [IImageCreator](./iimagecreator/) | Le créateur d'image. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | Le descripteur du créateur d'image spécifiant les propriétés du créateur. Le descripteur du créateur est utilisé pour surmonter la nécessité de contenir chaque instance du créateur d'image en mémoire et les problèmes de multithreading. |
| [IImageDescriptor](./iimagedescriptor/) | Le descripteur d'image. Contient les propriétés et méthodes de base pour tous les autres types de descripteurs d'image. |
| [IImageExporter](./iimageexporter/) | L'exportateur d'image. Peut exporter des données du format interne Aspose.PSD vers un format de données spécifié. |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | Représente le descripteur de l'exportateur d'image. Le descripteur de l'exportateur est utilisé pour surmonter la nécessité de contenir chaque instance de l'exportateur en mémoire et les problèmes de multithreading. |
| [IImageLoader](./iimageloader/) | Le chargeur d'image. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | Le descripteur du chargeur d'image spécifiant les propriétés du chargeur. Le descripteur du chargeur est utilisé pour surmonter la nécessité de contenir chaque instance du chargeur d'image en mémoire et les problèmes de multithreading. |
| [IIndexedColorConverter](./iindexedcolorconverter/) | Le convertisseur de couleur pour les formats d'image indexés. |
| [IKeyedObject](./ikeyedobject/) | Représente l'interface pour les objets avec des clés. |
| [IObjectWithBounds](./iobjectwithbounds/) | Représente un objet avec des limites. |
| [IOrderedShape](./iorderedshape/) | Représente une forme ordonnée. Une forme ordonnée est un ensemble continu de points ayant un point de départ et un point d'arrivée. L'ensemble continu de points est connecté selon une règle spécifique. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | Conforme aux pixels ARGB 32 bits chargés partiellement. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | Le chargeur de pixels ARGB 64 bits. |
| [IPartialPixelLoader](./ipartialpixelloader/) | Conforme aux pixels chargés partiellement. |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | Le chargeur de données partielles. |
| [IPsdColorPalette](./ipsdcolorpalette/) | La palette de couleur pasd |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | Le chargeur de pixels ARGB 32 bits d'image raster. |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | Le chargeur de pixels d'image raster. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | Le chargeur de données brutes d'image raster. |
## Énumération

| Énumération | Description |
| --- | --- |
| [CacheType](./cachetype/) | Spécifie le type de cache à utiliser. |
| [CharacterSet](./characterset/) | Représente le jeu de caractères utilisé. |
| [ColorAdjustType](./coloradjusttype/) | Spécifie quels objets utilisent les informations d'ajustement des couleurs. |
| [ColorChannelFlag](./colorchannelflag/) | Spécifie les canaux individuels dans l'espace colorimétrique CMYK (cyan, magenta, jaune, noir). Cette énumération est utilisée par les méthodes SetOutputChannel. |
| [ColorCompareMethod](./colorcomparemethod/) | Méthode de comparaison des couleurs pour ajuster au voisin le plus proche |
| [ColorMatrixFlag](./colormatrixflag/) | Spécifie les types d'images et de couleurs qui seront affectés par les paramètres d'ajustement des couleurs et des niveaux de gris d'un [`ImageAttributes`](../aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](./colorquantizationmethod/) | Méthodes de quantification des couleurs |
| [CompositingQuality](./compositingquality/) | Spécifie le niveau de qualité à utiliser lors du compositing. |
| [DashCap](./dashcap/) | Spécifie le type de forme graphique à utiliser aux deux extrémités de chaque tiret dans une ligne pointillée. |
| [DashStyle](./dashstyle/) | Spécifie le style des lignes pointillées dessinées avec un objet [`Pen`](../aspose.psd/pen/). |
| [DataRecoveryMode](./datarecoverymode/) | Le mode de récupération des données. |
| [DitheringMethod](./ditheringmethod/) | Méthode de tramage. |
| [DitheringMethods](./ditheringmethods/) | Les méthodes de tramage utilisées pour contrôler la conversion des couleurs. |
| [FileFormat](./fileformat/) | L'un des formats de fichier PSD pris en charge. |
| [FillMode](./fillmode/) | Spécifie comment l'intérieur d'un chemin fermé est rempli. |
| [FontStyle](./fontstyle/) | Spécifie les informations de style appliquées au texte. |
| [GraphicsUnit](./graphicsunit/) | Spécifie l'unité de mesure des données fournies. |
| [HatchStyle](./hatchstyle/) | Spécifie les différents motifs disponibles pour les objets [`HatchBrush`](../aspose.psd.brushes/hatchbrush/). |
| [HotkeyPrefix](./hotkeyprefix/) | Spécifie le type d'affichage des préfixes de raccourcis clavier liés au texte. |
| [ImageFilterType](./imagefiltertype/) | Filtres d'image à utiliser |
| [InterpolationMode](./interpolationmode/) | L'énumération [`InterpolationMode`](../aspose.psd/interpolationmode/) spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou pivotées. |
| [KnownColor](./knowncolor/) | Spécifie les couleurs système connues. |
| [LineCap](./linecap/) | Spécifie les styles de terminaison disponibles avec lesquels un objet [`Pen`](../aspose.psd/pen/) peut terminer une ligne. |
| [LineJoin](./linejoin/) | Spécifie comment joindre les segments de ligne ou de courbe consécutifs dans une figure (sous-chemin) contenue dans un objet [`GraphicsPath`](../aspose.psd/graphicspath/). |
| [MatrixOrder](./matrixorder/) | Spécifie l'ordre des opérations de transformation de matrice. |
| [PdfComplianceVersion](./pdfcomplianceversion/) | Spécifie le niveau de conformité PDF du fichier de sortie. |
| [PenAlignment](./penalignment/) | Spécifie l'alignement d'un objet [`Pen`](../aspose.psd/pen/) par rapport à la ligne théorique à largeur nulle. |
| [PenType](./pentype/) | Spécifie le type de remplissage qu'un objet [`Pen`](../aspose.psd/pen/) utilise pour remplir les lignes. |
| [PixelFormat](./pixelformat/) | La signification réelle du format des données pixel. |
| [ResizeType](./resizetype/) | Spécifie le type de redimensionnement. |
| [ResolutionUnit](./resolutionunit/) | Énumération de l'unité de résolution. |
| [RotateFlipType](./rotatefliptype/) | Spécifie de combien une image est pivotée et l'axe utilisé pour la retourner. |
| [SeekOrigin](./seekorigin/) | Fournit les champs qui représentent les points de référence dans [`StreamContainer`](../aspose.psd/streamcontainer/) pour la recherche. |
| [SmoothingMode](./smoothingmode/) | Spécifie si le lissage (antialiasing) est appliqué aux lignes et courbes ainsi qu'aux bords des zones remplies. |
| [StringAlignment](./stringalignment/) | Spécifie l'alignement d'une chaîne de texte par rapport à son rectangle de mise en page. |
| [StringDigitSubstitute](./stringdigitsubstitute/) | L'énumération spécifie comment substituer les chiffres dans une chaîne selon la locale ou la langue de l'utilisateur. |
| [StringFormatFlags](./stringformatflags/) | Spécifie les informations d'affichage et de mise en page pour les chaînes de texte. |
| [StringTrimming](./stringtrimming/) | Spécifie comment tronquer les caractères d'une chaîne qui ne tient pas complètement dans une forme de mise en page. |
| [TextRenderingHint](./textrenderinghint/) | Spécifie la qualité du rendu du texte. |
| [WarpMode](./warpmode/) | Spécifie le type de transformation de déformation appliquée. |
| [WrapMode](./wrapmode/) | Spécifie comment une texture ou un dégradé est répété lorsqu'il est plus petit que la zone à remplir. |


