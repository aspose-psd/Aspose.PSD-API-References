---
title: "InitialFillRuleRecord.InitialFillRuleRecord"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής InitialFillRuleRecord. Δημιουργεί ένα νέο αντικείμενο της κλάσης InitialFillRuleRecord"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.core.vectorpaths/initialfillrulerecord/initialfillrulerecord/
---
{{< psd/tize >}}
## InitialFillRuleRecord() {#constructor}

Δημιουργεί ένα νέο αντικείμενο της κλάσης [`InitialFillRuleRecord`](../).

```csharp
public InitialFillRuleRecord()
```

### Δείτε επίσης

* class [InitialFillRuleRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## InitialFillRuleRecord(bool) {#constructor_1}

Δημιουργεί ένα νέο αντικείμενο της κλάσης [`InitialFillRuleRecord`](../).

```csharp
public InitialFillRuleRecord(bool isFillStartsWithAllPixels)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isFillStartsWithAllPixels | Boolean | Η γεμιστική αρχίζει με όλα τα pixel. |

## Παραδείγματα

Το παρακάτω παράδειγμα κώδικα παρέχει κλάσεις για τη διαχείριση των αντικειμένων διαδρομής διανύσματος και δείχνει πώς να χρησιμοποιήσετε αυτές τις κλάσεις.

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
/// Η κλάση που παρέχει λειτουργία μεταξύ <see cref="Layer"/> και <see cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Δημιουργεί την παρουσία <see cref="VectorPath"/> με βάση τους πόρους από το στρώμα εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το στρώμα psd.</param>
    /// <returns>την <see cref="VectorPath"/> παρουσία με βάση τους πόρους από το στρώμα εισόδου.</returns>
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
    /// Ενημερώνει τους πόρους του στρώματος εισόδου από την παρουσία <see cref="VectorPath"/>, ή αντικαθιστά με νέο πόρο διαδρομής και ενημερώνει.
    /// </summary>
    /// <param name="psdLayer">Το στρώμα psd.</param>
    /// <param name="vectorPath">Η διαδρομή διανύσματος.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
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
    /// Αφαιρεί τα δεδομένα διαδρομής διανύσματος από το στρώμα εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το στρώμα psd.</param>
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
    /// Ενημερώνει τα δεδομένα πόρων από την παρουσία <see cref="VectorPath"/>.
    /// </summary>
    /// <param name="pathResource">Ο πόρος διαδρομής.</param>
    /// <param name="vogkResource">Ο πόρος δεδομένων προέλευσης διανύσματος.</param>
    /// <param name="socoResource">Ο πόρος στερεού χρώματος.</param>
    /// <param name="vectorPath">Η διαδρομή διανύσματος.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
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
    /// Αντικαθιστά τους πόρους στο στρώμα με ενημερωμένους ή νέους.
    /// </summary>
    /// <param name="psdLayer">Το στρώμα psd.</param>
    /// <param name="pathResource">Ο πόρος διαδρομής.</param>
    /// <param name="vogkResource">Ο πόρος δεδομένων προέλευσης διανύσματος.</param>
    /// <param name="socoResource">Ο πόρος στερεού χρώματος.</param>
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
    /// Βρίσκει τον πόρο <see cref="VectorPathDataResource"/> στα πόρους του στρώματος εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το στρώμα psd.</param>
    /// <param name="createIfNotExist">Εάν ο πόρος δεν υπάρχει, τότε για <see cref="true"/> δημιουργεί νέο πόρο, διαφορετικά επιστρέφει <see cref="null"/>.</param>
    /// <returns>Τον πόρο <see cref="VectorPathDataResource"/>.</returns>
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
    /// Βρίσκει τον πόρο <see cref="VogkResource"/> στα πόρους του στρώματος εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το στρώμα psd.</param>
    /// <param name="createIfNotExist">Εάν ο πόρος δεν υπάρχει, τότε για <see cref="true"/> δημιουργεί νέο πόρο, διαφορετικά επιστρέφει <see cref="null"/>.</param>
    /// <returns>Τον πόρο <see cref="VogkResource"/>.</returns>
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
    /// Βρίσκει τον πόρο <see cref="SoCoResource"/> στα πόρους του στρώματος εισόδου.
    /// </summary>
    /// <param name="psdLayer">Το στρώμα psd.</param>
    /// <param name="createIfNotExist">Εάν ο πόρος δεν υπάρχει, τότε για <see cref="true"/> δημιουργεί νέο πόρο, διαφορετικά επιστρέφει <see cref="null"/>.</param>
    /// <returns>Τον πόρο <see cref="SoCoResource"/>.</returns>
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
    /// Επικυρώνει το στρώμα για εργασία με την κλάση <see cref="VectorDataProvider"/>.
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
    /// Αρχικοποιεί μια νέα παρουσία της κλάσης <see cref="BezierKnot" /> βασισμένη στην <see cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="anchorPoint">Το σημείο αγκύρωσης.</param>
    /// <param name="controlPoint1">Το πρώτο σημείο ελέγχου.</param>
    /// <param name="controlPoint2">Το δεύτερο σημείο ελέγχου.</param>
    /// <param name="isLinked">Η τιμή που υποδεικνύει αν αυτός ο κόμβος είναι συνδεδεμένος.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία της κλάσης <see cref="BezierKnot" /> βασισμένη στην <see cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord">Το <see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία της κλάσης <see cref="BezierKnot" /> βασισμένη στην <see cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="anchorPoint">Το σημείο που θα είναι αγκύρωση και σημεία ελέγχου.</param>
    /// <param name="isLinked">Η τιμή που υποδεικνύει αν αυτός ο κόμβος είναι συνδεδεμένος.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι συνδεδεμένη.
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
    /// Δημιουργεί την παρουσία της <see cref="BezierKnotRecord"/> βασισμένη σε αυτήν την παρουσία.
    /// </summary>
    /// <param name="isClosed">Υποδεικνύει αν αυτός ο κόμβος βρίσκεται σε κλειστό σχήμα.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
    /// <returns>Η παρουσία της <see cref="BezierKnotRecord"/> βασισμένη σε αυτήν την παρουσία.</returns>
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
    /// Μετατοπίζει τα σημεία αυτού του κόμβου κατά τις εισαγόμενες τιμές.
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
    /// Μετατρέπει τις τιμές σημείων από πόρο σε κανονικές.
    /// </summary>
    /// <param name="point">Το σημείο με τιμές από πόρο.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
    /// <returns>Το μετατρεπόμενο σε κανονικό σημείο.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Μετατρέπει τις κανονικές τιμές σημείου σε σημείο πόρου.
    /// </summary>
    /// <param name=\"point\">Το σημείο.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
    /// <returns>Το σημείο με τιμές για τον πόρο.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Η μορφή από τους κόμβους της καμπύλης Bezier.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία της κλάσης <see cref=\"PathShape\" />.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία της κλάσης <see cref=\"PathShape\" /> βασισμένη στα στοιχεία του <see cref=\"VectorPathRecord\"/>.
    /// </summary>
    /// <param name=\"lengthRecord\">Η εγγραφή μήκους.</param>
    /// <param name=\"bezierKnotRecords\">Οι εγγραφές κόμβων Bezier.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
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
    /// <value>
    ///   <c>true</c> εάν αυτή η παρουσία είναι κλειστή· διαφορετικά, <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει τις λειτουργίες διαδρομής (Λογικές λειτουργίες).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής στο επίπεδο.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Λαμβάνει τα σημεία της καμπύλης Bezier.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Δημιουργεί τις εγγραφές <see cref=\"VectorPathRecord\"/> βασισμένες σε αυτήν την παρουσία.
    /// </summary>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
    /// <returns>Επιστρέφει ένα <see cref=\"LengthRecord\"/> και ένα <see cref=\"BezierKnotRecord\"/> για κάθε σημείο σε αυτήν την παρουσία.</returns>
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
    /// Αρχικοποιεί τιμές βασισμένες στις εισερχόμενες εγγραφές.
    /// </summary>
    /// <param name=\"bezierKnotRecords\">Οι εγγραφές κόμβων Bezier.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
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
/// Η κλάση που περιέχει διανυσματικές διαδρομές.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Αρχικοποιεί μια νέα παρουσία της κλάσης <see cref=\"VectorPath\" /> βασισμένη στο <see cref=\"VectorPathDataResource\"/>.
    /// </summary>
    /// <param name=\"vectorPathDataResource\">Ο πόρος δεδομένων διανυσματικής διαδρομής.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η γέμιση ξεκινά με όλα τα pixel.
    /// </summary>
    /// <value>
    /// Η γέμιση ξεκινά με όλα τα pixel.
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Λαμβάνει τα διανυσματικά σχήματα.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει το χρώμα γεμίσματος της διανυσματικής διαδρομής.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει την έκδοση.
    /// </summary>
    /// <value>
    /// Η έκδοση.
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι απενεργοποιημένη.
    /// </summary>
    /// <value>
    ///   <c>true</c> εάν αυτή η παρουσία είναι απενεργοποιημένη· διαφορετικά, <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία δεν είναι συνδεδεμένη.
    /// </summary>
    /// <value>
    ///   <c>true</c> εάν αυτή η παρουσία δεν είναι συνδεδεμένη· διαφορετικά, <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ανεστραμμένη.
    /// </summary>
    /// <value>
    ///   <c>true</c> εάν αυτή η παρουσία είναι ανεστραμμένη· διαφορετικά, <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Αρχικοποιεί τιμές βάσει του εισερχόμενου πόρου <see cref=\"VectorPathDataResource\"/>.
    /// </summary>
    /// <param name=\"resource\">Ο πόρος δεδομένων διανυσματικής διαδρομής.</param>
    /// <param name="imageSize">Το μέγεθος εικόνας για τη διόρθωση μετατροπής συντεταγμένων σημείων.</param>
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

* class [InitialFillRuleRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## InitialFillRuleRecord(byte[]) {#constructor_2}

Δημιουργεί ένα νέο αντικείμενο της κλάσης [`InitialFillRuleRecord`](../).

```csharp
public InitialFillRuleRecord(byte[] data)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | Byte[] | Τα δεδομένα της εγγραφής. |

### Δείτε επίσης

* class [InitialFillRuleRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


