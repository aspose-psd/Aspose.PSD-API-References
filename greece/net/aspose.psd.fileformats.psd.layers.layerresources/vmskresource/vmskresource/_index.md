---
title: VmskResource.VmskResource
second_title: Aspose.PSD για Αναφορά API .NET
description: VmskResource κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουVmskResource τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
## VmskResource(byte[]) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`VmskResource`](../) τάξη.

```csharp
public VmskResource(byte[] data)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | Byte[] | Τα δεδομένα των πόρων. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Μη έγκυρη τιμή πόρου Vmsk |

### Δείτε επίσης

* class [VmskResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* συνέλευση [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`VmskResource`](../) τάξη.

```csharp
public VmskResource()
```

### Παραδείγματα

Το ακόλουθο παράδειγμα κώδικα παρέχει κλάσεις για τον χειρισμό των αντικειμένων διανυσματικής διαδρομής και δείχνει πώς να χρησιμοποιήσετε αυτές τις κλάσεις.

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
/// Η κλάση που παρέχει εργασία μεταξύ <δείτε cref="Layer"/> και <δείτε cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Δημιουργεί το <δείτε cref="VectorPath"/> παράδειγμα που βασίζεται σε πόρους από το επίπεδο εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το επίπεδο psd.</param>
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
    /// Ενημερώνει τους πόρους του επιπέδου εισόδου από το <δείτε cref="VectorPath"/> παράδειγμα, ή αντικαταστήστε με νέο πόρο διαδρομής και ενημερώσεις.
    /// </summary>
    /// <param name="psdLayer">Το επίπεδο psd.</param>
    /// <param name="vectorPath">Η διανυσματική διαδρομή.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
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
    /// Αφαιρεί τα δεδομένα διανυσματικής διαδρομής από το επίπεδο εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το επίπεδο psd.</param>
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
    /// Ενημερώνει δεδομένα πόρων από <δείτε cref="VectorPath"/> παράδειγμα.
    /// </summary>
    /// <param name="pathResource">Ο πόρος της διαδρομής.</param>
    /// <param name="vogkResource">Ο διανυσματικός πόρος δεδομένων προέλευσης.</param>
    /// <param name="socoResource">Ο πόρος συμπαγούς χρώματος.</param>
    /// <param name="vectorPath">Η διανυσματική διαδρομή.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
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
    /// Αντικαθιστά πόρους σε επίπεδο με ενημερωμένους ή νέους.
    /// </summary>
    /// <param name="psdLayer">Το επίπεδο psd.</param>
    /// <param name="pathResource">Ο πόρος της διαδρομής.</param>
    /// <param name="vogkResource">Ο διανυσματικός πόρος δεδομένων προέλευσης.</param>
    /// <param name="socoResource">Ο πόρος συμπαγούς χρώματος.</param>
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
    /// Βρίσκει το <δείτε cref="VectorPathDataResource"/> πόρος στους πόρους του επιπέδου εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το επίπεδο psd.</param>
    /// <param name="createIfNotExist">Εάν δεν υπάρχει πόρος, τότε για <δείτε cref="true"/> δημιουργεί έναν νέο πόρο, διαφορετικά επιστρέψτε <δείτε cref="null"/>.</param>
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
    /// Βρίσκει το <δείτε cref="VogkResource"/> πόρος στους πόρους του επιπέδου εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το επίπεδο psd.</param>
    /// <param name="createIfNotExist">Εάν δεν υπάρχει πόρος, τότε για <δείτε cref="true"/> δημιουργεί έναν νέο πόρο, διαφορετικά επιστρέψτε <δείτε cref="null"/>.</param>
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
    /// Βρίσκει το <δείτε cref="SoCoResource"/> πόρος στους πόρους του επιπέδου εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το επίπεδο psd.</param>
    /// <param name="createIfNotExist">Εάν δεν υπάρχει πόρος, τότε για <δείτε cref="true"/> δημιουργεί έναν νέο πόρο, διαφορετικά επιστρέψτε <δείτε cref="null"/>.</param>
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
    /// Επικυρώνει το επίπεδο για εργασία με <δείτε cref="VectorDataProvider"/> τάξη.
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
/// Ο κόμβος καμπύλης Bezier, περιέχει ένα σημείο αγκύρωσης και δύο σημεία ελέγχου.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Αναλογία εικόνας προς σημείο διαδρομής.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία του <δείτε cref="BezierKnot" /> τάξη.
    /// </summary>
    /// <param name="anchorPoint">Το σημείο αγκύρωσης.</param>
    /// <param name="controlPoint1">Το πρώτο σημείο ελέγχου.</param>
    /// <param name="controlPoint2">Το δεύτερο σημείο ελέγχου.</param>
    /// <param name="isLinked">Η τιμή που υποδεικνύει εάν αυτός ο κόμπος είναι συνδεδεμένος.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία του <δείτε cref="BezierKnot" /> τάξη βασισμένη στο <δείτε cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord">Το <δείτε cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία του <δείτε cref="BezierKnot" /> τάξη.
    /// </summary>
    /// <param name="anchorPoint">Το σημείο που πρέπει να είναι σημεία αγκύρωσης και ελέγχου.</param>
    /// <param name="isLinked">Η τιμή που υποδεικνύει εάν αυτός ο κόμπος είναι συνδεδεμένος.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι συνδεδεμένη.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει το πρώτο σημείο ελέγχου.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει το σημείο αγκύρωσης.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει το δεύτερο σημείο ελέγχου.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Δημιουργεί την παρουσία του <δείτε cref="BezierKnotRecord"/> με βάση αυτή την περίπτωση.
    /// </summary>
    /// <param name="isClosed">Δείχνει εάν αυτός ο κόμπος έχει κλειστό σχήμα.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
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
    /// Μετατοπίζει τα σημεία αυτού του κόμβου κατά τιμές εισόδου.
    /// </summary>
    /// <param name="xOffset">Η μετατόπιση x.</param>
    /// <param name="yOffset">Η μετατόπιση y.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Μετατρέπει τις τιμές των σημείων από πόρο σε κανονικό.
    /// </summary>
    /// <param name="point">Το σημείο με τιμές από τον πόρο.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Μετατρέπει τις κανονικές τιμές σημείων σε σημείο πόρων.
    /// </summary>
    /// <param name="point">Το σημείο.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Το σχήμα από τους κόμβους της καμπύλης Bezier.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία του <δείτε cref="PathShape" /> τάξη.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία του <δείτε cref="PathShape" /> τάξη βασισμένη σε <δείτε cref="VectorPathRecord"/>'s.
    /// </summary>
    /// <param name="lengthRecord">Η εγγραφή μήκους.</param>
    /// <param name="bezierKnotRecords">Η εγγραφή του κόμβου bezier.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κλειστή.
    /// </summary>
    /// <τιμή>
    /// <c>true</c> εάν αυτή η περίπτωση είναι κλειστή. διαφορετικά, <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει τις λειτουργίες διαδρομής (Λειτουργίες Boolean).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής σε επίπεδο.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Λαμβάνει τα σημεία της καμπύλης Bezier.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Δημιουργεί το <δείτε cref="VectorPathRecord"/> εγγραφές που βασίζονται σε αυτήν την περίπτωση.
    /// </summary>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
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
    /// Αρχικοποιεί τιμές που βασίζονται σε εγγραφές εισόδου.
    /// </summary>
    /// <param name="bezierKnotRecords">Η εγγραφή του κόμβου bezier.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
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
/// Η κλάση που περιέχει διανυσματικά μονοπάτια.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία του <δείτε cref="VectorPath" /> τάξη βασισμένη στο <δείτε cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">Ο πόρος δεδομένων διανυσματικής διαδρομής.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το γέμισμα ξεκινά με όλα τα pixel.
    /// </summary>
    /// <τιμή>
    /// Το is fill ξεκινά με όλα τα pixel.
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Παίρνει τα διανυσματικά σχήματα.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει το χρώμα πλήρωσης της διανυσματικής διαδρομής.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει την έκδοση.
    /// </summary>
    /// <τιμή>
    /// Η έκδοση.
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι απενεργοποιημένη.
    /// </summary>
    /// <τιμή>
    /// <c>true</c> εάν αυτή η περίπτωση είναι απενεργοποιημένη. διαφορετικά, <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία δεν είναι συνδεδεμένη.
    /// </summary>
    /// <τιμή>
    /// <c>true</c> εάν αυτή η περίπτωση δεν είναι συνδεδεμένη. διαφορετικά, <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ανεστραμμένη.
    /// </summary>
    /// <τιμή>
    /// <c>true</c> αν αυτή η περίπτωση είναι ανεστραμμένη. διαφορετικά, <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Αρχικοποιεί τιμές με βάση την είσοδο <δείτε cref="VectorPathDataResource"/> πόρος.
    /// </summary>
    /// <param name="resource">Ο πόρος δεδομένων διανυσματικής διαδρομής.</param>
    /// <param name="imageSize">Το μέγεθος της εικόνας για τη διόρθωση των συντεταγμένων του σημείου μετατροπής.</param>
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

### Δείτε επίσης

* class [VmskResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* συνέλευση [Aspose.PSD](../../../)


