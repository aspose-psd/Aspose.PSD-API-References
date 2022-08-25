---
title: VsmsResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Initialise une nouvelle instance duVsmsResourceaspose.psd.fileformats.psd.layers.layerresources/vsmsresource classe.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/vsmsresource/
---
## VsmsResource(byte[]) {#constructor_1}

Initialise une nouvelle instance du[`VsmsResource`](../../vsmsresource) classe.

```csharp
public VsmsResource(byte[] data)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| data | Byte[] | Les données de ressources. |

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception) | Valeur de ressource Vsms non valide |

### Voir également

* class [VsmsResource](../../vsmsresource)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vsmsresource)
* Assemblée [Aspose.PSD](../../../)

---

## VsmsResource() {#constructor}

Initialise une nouvelle instance du[`VsmsResource`](../../vsmsresource) classe.

```csharp
public VsmsResource()
```

### Exemples

L'exemple de code suivant fournit des classes pour manipuler les objets de chemin vectoriel et montre comment utiliser ces classes.

```csharp
[C#]

public void CreatingVectorPathExample(string outputPsd = "outputPsd.psd")
{
    using (var psdImage = (PsdImage)Image.Create(new PsdOptions() { Source = new StreamSource(new MemoryStream()), }, 500, 500))
    {
        FillLayer layer = FillLayer.CreateInstance(FillType.Color);
        psdImage.AddLayer(layer);

        VectorPath vectorPath = VectorDataProvider.CreateVectorPathForLayer(layer);
        vectorPath.FillColor = Color.IndianRed;
        PathShape shape = new PathShape();
        shape.Points.Add(new BezierKnot(new PointF(50, 150), true));
        shape.Points.Add(new BezierKnot(new PointF(100, 200), true));
        shape.Points.Add(new BezierKnot(new PointF(0, 200), true));
        vectorPath.Shapes.Add(shape);
        VectorDataProvider.UpdateLayerFromVectorPath(layer, vectorPath, true);

        psdImage.Save(outputPsd);
    }
}

#region Vector path editor (Here placed classes for edit vector paths).

/// <summary>
/// La classe qui fournit le travail entre <voir cref="Layer"/> et <voir cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Crée le <voir cref="VectorPath"/> instance basée sur les ressources de la couche d'entrée.
    /// </summary>
    /// <param name="psdLayer">La couche psd.</param>
    /// <returns>the <see cref="VectorPath"/> instance based on resources from input layer.</returns>
    public static VectorPath CreateVectorPathForLayer(Layer psdLayer)
    {
        ValidateLayer(psdLayer);

        Size imageSize = psdLayer.Container.Size;

        VectorPathDataResource pathResource = FindVectorPathDataResource(psdLayer, true);
        SoCoResource socoResource = FindSoCoResource(psdLayer, true);
        VectorPath vectorPath = new VectorPath(pathResource, imageSize);
        if (socoResource != null)
        {
            vectorPath.FillColor = socoResource.Color;
        }

        return vectorPath;
    }

    /// <summary>
    /// Met à jour les ressources de la couche d'entrée à partir de <voir cref="VectorPath"/> instance, ou remplacer par une nouvelle ressource de chemin et des mises à jour.
    /// </summary>
    /// <param name="psdLayer">La couche psd.</param>
    /// <param name="vectorPath">Le chemin vectoriel.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    public static void UpdateLayerFromVectorPath(Layer psdLayer, VectorPath vectorPath, bool createIfNotExist = false)
    {
        ValidateLayer(psdLayer);

        VectorPathDataResource pathResource = FindVectorPathDataResource(psdLayer, createIfNotExist);
        VogkResource vogkResource = FindVogkResource(psdLayer, createIfNotExist);
        SoCoResource socoResource = FindSoCoResource(psdLayer, createIfNotExist);

        Size imageSize = psdLayer.Container.Size;
        UpdateResources(pathResource, vogkResource, socoResource, vectorPath, imageSize);

        ReplaceVectorPathDataResourceInLayer(psdLayer, pathResource, vogkResource, socoResource);
    }

    /// <summary>
    /// Supprime les données de chemin vectoriel de la couche d'entrée.
    /// </summary>
    /// <param name="psdLayer">La couche psd.</param>
    public static void RemoveVectorPathDataFromLayer(Layer psdLayer)
    {
        List<LayerResource> oldResources = new List<LayerResource>(psdLayer.Resources);
        List<LayerResource> newResources = new List<LayerResource>();
        for (int i = 0; i < oldResources.Count; i++)
        {
            LayerResource resource = oldResources[i];

            if (resource is VectorPathDataResource || resource is VogkResource || resource is SoCoResource)
            {
                continue;
            }
            else
            {
                newResources.Add(resource);
            }
        }

        psdLayer.Resources = newResources.ToArray();
    }

    /// <summary>
    /// Met à jour les données des ressources depuis <voir cref="VectorPath"/> exemple.
    /// </summary>
    /// <param name="pathResource">La ressource de chemin.</param>
    /// <param name="vogkResource">La ressource de données d'origine vectorielle.</param>
    /// <param name="socoResource">La ressource de couleur unie.</param>
    /// <param name="vectorPath">Le chemin vectoriel.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    private static void UpdateResources(VectorPathDataResource pathResource, VogkResource vogkResource, SoCoResource socoResource, VectorPath vectorPath, Size imageSize)
    {
        pathResource.Version = vectorPath.Version;
        pathResource.IsNotLinked = vectorPath.IsNotLinked;
        pathResource.IsDisabled = vectorPath.IsDisabled;
        pathResource.IsInverted = vectorPath.IsInverted;

        List<VectorShapeOriginSettings> originSettings = new List<VectorShapeOriginSettings>();
        List<VectorPathRecord> path = new List<VectorPathRecord>();
        path.Add(new PathFillRuleRecord(null));
        path.Add(new InitialFillRuleRecord(vectorPath.IsFillStartsWithAllPixels));
        for (ushort i = 0; i < vectorPath.Shapes.Count; i++)
        {
            PathShape shape = vectorPath.Shapes[i];
            shape.ShapeIndex = i;
            path.AddRange(shape.ToVectorPathRecords(imageSize));
            originSettings.Add(new VectorShapeOriginSettings() { IsShapeInvalidated = true, OriginIndex = i });
        }

        pathResource.Paths = path.ToArray();
        vogkResource.ShapeOriginSettings = originSettings.ToArray();

        socoResource.Color = vectorPath.FillColor;
    }

    /// <summary>
    /// Remplace les ressources de la couche par des mises à jour ou des nouvelles.
    /// </summary>
    /// <param name="psdLayer">La couche psd.</param>
    /// <param name="pathResource">La ressource de chemin.</param>
    /// <param name="vogkResource">La ressource de données d'origine vectorielle.</param>
    /// <param name="socoResource">La ressource de couleur unie.</param>
    private static void ReplaceVectorPathDataResourceInLayer(Layer psdLayer, VectorPathDataResource pathResource, VogkResource vogkResource, SoCoResource socoResource)
    {
        bool pathResourceExist = false;
        bool vogkResourceExist = false;
        bool socoResourceExist = false;

        List<LayerResource> resources = new List<LayerResource>(psdLayer.Resources);
        for (int i = 0; i < resources.Count; i++)
        {
            LayerResource resource = resources[i];
            if (resource is VectorPathDataResource)
            {
                resources[i] = pathResource;
                pathResourceExist = true;
            }
            else if (resource is VogkResource)
            {
                resources[i] = vogkResource;
                vogkResourceExist = true;
            }
            else if (resource is SoCoResource)
            {
                resources[i] = socoResource;
                socoResourceExist = true;
            }
        }

        if (!pathResourceExist)
        {
            resources.Add(pathResource);
        }

        if (!vogkResourceExist)
        {
            resources.Add(vogkResource);
        }

        if (!socoResourceExist)
        {
            resources.Add(socoResource);
        }

        psdLayer.Resources = resources.ToArray();
    }

    /// <summary>
    /// Trouve le <voir cref="VectorPathDataResource"/> ressource dans les ressources de la couche d'entrée.
    /// </summary>
    /// <param name="psdLayer">La couche psd.</param>
    /// <param name="createIfNotExist">Si la ressource n'existe pas, alors pour <voir cref="true"/> crée une nouvelle ressource, sinon renvoie <voir cref="null"/>.</param>
    /// <returns>The <see cref="VectorPathDataResource"/> resource.</returns>
    private static VectorPathDataResource FindVectorPathDataResource(Layer psdLayer, bool createIfNotExist = false)
    {
        VectorPathDataResource pathResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is VectorPathDataResource)
            {
                pathResource = (VectorPathDataResource)resource;
                break;
            }
        }

        if (createIfNotExist && pathResource == null)
        {
            pathResource = new VmskResource();
        }

        return pathResource;
    }

    /// <summary>
    /// Trouve le <voir cref="VogkResource"/> ressource dans les ressources de la couche d'entrée.
    /// </summary>
    /// <param name="psdLayer">La couche psd.</param>
    /// <param name="createIfNotExist">Si la ressource n'existe pas, alors pour <voir cref="true"/> crée une nouvelle ressource, sinon renvoie <voir cref="null"/>.</param>
    /// <returns>The <see cref="VogkResource"/> resource.</returns>
    private static VogkResource FindVogkResource(Layer psdLayer, bool createIfNotExist = false)
    {
        VogkResource vogkResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is VogkResource)
            {
                vogkResource = (VogkResource)resource;
                break;
            }
        }

        if (createIfNotExist && vogkResource == null)
        {
            vogkResource = new VogkResource();
        }

        return vogkResource;
    }

    /// <summary>
    /// Trouve le <voir cref="SoCoResource"/> ressource dans les ressources de la couche d'entrée.
    /// </summary>
    /// <param name="psdLayer">La couche psd.</param>
    /// <param name="createIfNotExist">Si la ressource n'existe pas, alors pour <voir cref="true"/> crée une nouvelle ressource, sinon renvoie <voir cref="null"/>.</param>
    /// <returns>The <see cref="SoCoResource"/> resource.</returns>
    private static SoCoResource FindSoCoResource(Layer psdLayer, bool createIfNotExist = false)
    {
        SoCoResource socoResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is SoCoResource)
            {
                socoResource = (SoCoResource)resource;
                break;
            }
        }

        if (createIfNotExist && socoResource == null)
        {
            socoResource = new SoCoResource();
        }

        return socoResource;
    }

    /// <summary>
    /// Valide la couche à utiliser <voir cref="VectorDataProvider"/> classer.
    /// </summary>
    /// <param name="layer"></param>
    /// <exception cref="ArgumentNullException"></exception>
    private static void ValidateLayer(Layer layer)
    {
        if (layer == null)
        {
            throw new ArgumentNullException("The layer is NULL.");
        }

        if (layer.Container == null || layer.Container.Size.IsEmpty)
        {
            throw new ArgumentNullException("The layer should have a Container with no empty size.");
        }
    }
}

/// <summary>
/// Le noeud courbe de Bézier, il contient un point d'ancrage et deux points de contrôle.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Rapport image/point de chemin.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Initialise une nouvelle instance de <see cref="BezierKnot" /> classer.
    /// </summary>
    /// <param name="anchorPoint">Le point d'ancrage.</param>
    /// <param name="controlPoint1">Le premier point de contrôle.</param>
    /// <param name="controlPoint2">LE deuxième point de contrôle.</param>
    /// <param name="isLinked">La valeur indiquant si ce nœud est lié.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Initialise une nouvelle instance de <see cref="BezierKnot" /> classe basée sur <voir cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord">Le <voir cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Initialise une nouvelle instance de <see cref="BezierKnot" /> classer.
    /// </summary>
    /// <param name="anchorPoint">Le point d'ancrage et les points de contrôle.</param>
    /// <param name="isLinked">La valeur indiquant si ce nœud est lié.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Obtient ou définit une valeur indiquant si cette instance est liée.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Obtient ou définit le premier point de contrôle.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Obtient ou définit le point d'ancrage.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Obtient ou définit le deuxième point de contrôle.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Crée l'instance de <voir cref="BezierKnotRecord"/> basé sur cette instance.
    /// </summary>
    /// <param name="isClosed">Indique si ce nœud est de forme fermée.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    /// <returns>The instance of <see cref="BezierKnotRecord"/> based on this instance.</returns>
    public BezierKnotRecord ToBezierKnotRecord(bool isClosed, Size imageSize)
    {
        BezierKnotRecord record = new BezierKnotRecord();
        record.Points = new Point[]
        {
            PointFToResourcePoint(this.ControlPoint1, imageSize),
            PointFToResourcePoint(this.AnchorPoint, imageSize),
            PointFToResourcePoint(this.ControlPoint2, imageSize),
        };
        record.IsLinked = this.IsLinked;
        record.IsClosed = isClosed;

        return record;
    }

    /// <summary>
    /// Décale ce point de nœud par les valeurs d'entrée.
    /// </summary>
    /// <param name="xOffset">Le décalage x.</param>
    /// <param name="yOffset">Le décalage y.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Convertit les valeurs de point de ressource en normal.
    /// </summary>
    /// <param name="point">Le point avec les valeurs de la ressource.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Convertit les valeurs de point normales en point de ressource.
    /// </summary>
    /// <param name="point">Le point.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// La figure des nœuds de la courbe de Bézier.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Initialise une nouvelle instance de <see cref="PathShape" /> classer.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Initialise une nouvelle instance de <see cref="PathShape" /> classe basée sur <voir cref="VectorPathRecord"/>'s.
    /// </summary>
    /// <param name="lengthRecord">L'enregistrement de longueur.</param>
    /// <param name="bezierKnotRecords">Les enregistrements du nœud de Bézier.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Obtient ou définit une valeur indiquant si cette instance est fermée.
    /// </summary>
    /// <valeur>
    /// <c>vrai</c> si cette instance est fermée ; sinon, <c>faux</c>.
    /// </valeur>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Obtient ou définit les opérations de chemin (opérations booléennes).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Obtient ou définit l'index de la forme du chemin actuel dans le calque.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Obtient les points de la courbe de Bézier.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Crée le <voir cref="VectorPathRecord"/> enregistrements basés sur cette instance.
    /// </summary>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    /// <returns>Returns one <see cref="LengthRecord"/> and <see cref="BezierKnotRecord"/> for each point in this instance.</returns>
    public IEnumerable<VectorPathRecord> ToVectorPathRecords(Size imageSize)
    {
        List<VectorPathRecord> shapeRecords = new List<VectorPathRecord>();

        LengthRecord lengthRecord = new LengthRecord();
        lengthRecord.IsClosed = this.IsClosed;
        lengthRecord.BezierKnotRecordsCount = this.Points.Count;
        lengthRecord.PathOperations = this.PathOperations;
        lengthRecord.ShapeIndex = this.ShapeIndex;
        shapeRecords.Add(lengthRecord);

        foreach (var bezierKnot in this.Points)
        {
            shapeRecords.Add(bezierKnot.ToBezierKnotRecord(this.IsClosed, imageSize));
        }

        return shapeRecords;
    }

    /// <summary>
    /// Initialise une valeur basée sur les enregistrements d'entrée.
    /// </summary>
    /// <param name="bezierKnotRecords">Les enregistrements du nœud de Bézier.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    private void InitFromResources(IEnumerable<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    {
        List<BezierKnot> newPoints = new List<BezierKnot>();

        foreach (var record in bezierKnotRecords)
        {
            newPoints.Add(new BezierKnot(record, imageSize));
        }

        this.Points = newPoints;
    }
}

/// <summary>
/// La classe qui contient les chemins vectoriels.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Initialise une nouvelle instance de <voir cref="VectorPath" /> classe basée sur <voir cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">La ressource de données de chemin vectoriel.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Obtient ou définit une valeur indiquant si le remplissage commence par tous les pixels.
    /// </summary>
    /// <valeur>
    /// Le remplissage commence avec tous les pixels.
    /// </valeur>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Obtient les formes vectorielles.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Obtient ou définit la couleur de remplissage du chemin vectoriel.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Obtient ou définit la version.
    /// </summary>
    /// <valeur>
    /// La version.
    /// </valeur>
    public int Version { get; set; }

    /// <summary>
    /// Obtient ou définit une valeur indiquant si cette instance est désactivée.
    /// </summary>
    /// <valeur>
    /// <c>vrai</c> si cette instance est désactivée ; sinon, <c>faux</c>.
    /// </valeur>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Obtient ou définit une valeur indiquant si cette instance n'est pas liée.
    /// </summary>
    /// <valeur>
    /// <c>vrai</c> si cette instance n'est pas liée ; sinon, <c>faux</c>.
    /// </valeur>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Obtient ou définit une valeur indiquant si cette instance est inversée.
    /// </summary>
    /// <valeur>
    /// <c>vrai</c> si cette instance est inversée ; sinon, <c>faux</c>.
    /// </valeur>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Initialise une valeur basée sur l'entrée <voir cref="VectorPathDataResource"/> Ressource.
    /// </summary>
    /// <param name="resource">La ressource de données de chemin vectoriel.</param>
    /// <param name="imageSize">La taille de l'image pour corriger les coordonnées du point de conversion.</param>
    private void InitFromResource(VectorPathDataResource resource, Size imageSize)
    {
        List<PathShape> newShapes = new List<PathShape>();
        InitialFillRuleRecord initialFillRuleRecord = null;
        LengthRecord lengthRecord = null;
        List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

        foreach (var pathRecord in resource.Paths)
        {
            if (pathRecord is LengthRecord)
            {
                if (bezierKnotRecords.Count > 0)
                {
                    newShapes.Add(new PathShape(lengthRecord, bezierKnotRecords, imageSize));
                    lengthRecord = null;
                    bezierKnotRecords.Clear();
                }

                lengthRecord = (LengthRecord)pathRecord;
            }
            else if (pathRecord is BezierKnotRecord)
            {
                bezierKnotRecords.Add((BezierKnotRecord)pathRecord);
            }
            else if (pathRecord is InitialFillRuleRecord)
            {
                initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            }
        }

        if (bezierKnotRecords.Count > 0)
        {
            newShapes.Add(new PathShape(lengthRecord, bezierKnotRecords, imageSize));
            lengthRecord = null;
            bezierKnotRecords.Clear();
        }

        this.IsFillStartsWithAllPixels = initialFillRuleRecord != null ? initialFillRuleRecord.IsFillStartsWithAllPixels : false;
        this.Shapes = newShapes;

        this.Version = resource.Version;
        this.IsNotLinked = resource.IsNotLinked;
        this.IsDisabled = resource.IsDisabled;
        this.IsInverted = resource.IsInverted;
    }
}

#endregion
```

### Voir également

* class [VsmsResource](../../vsmsresource)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vsmsresource)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
