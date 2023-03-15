---
title: Class VmskResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VmskResource τάξη. Κλάση VmskResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με το διανυσματικό στρώμα mask
type: docs
weight: 3360
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---
## VmskResource class

Κλάση VmskResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με το διανυσματικό στρώμα mask

```csharp
public class VmskResource : VectorPathDataResource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [VmskResource](vmskresource/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`VmskResource` τάξη. |
| [VmskResource](vmskresource/#constructor_1)(byte[]) | Αρχικοποιεί μια νέα παρουσία του`VmskResource` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι απενεργοποιημένη. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ανεστραμμένη. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία δεν είναι συνδεδεμένη. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vmskresource/key/) { get; } | Λαμβάνει το κλειδί πόρων επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε byte. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | Λαμβάνει ή ορίζει τις εγγραφές διαδρομής. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | Λαμβάνει την έκδοση psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | Παίρνει την υπογραφή. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vmskresource/typetoolkey/) | Το κλειδί πληροφοριών εργαλείου τύπου. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει την υποστήριξη της φόρτωσης πόρων VmskResource. Πώς λειτουργεί η επεξεργασία των μονοπατιών.

```csharp
[C#]

[Test]
public void TestPsdNet106()
{
    string sourceFileName = "Rectangle.psd";
    string exportPath = "Rectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVmskResource(im);
        // ΑΝΑΓΝΩΣΗ
        if (resource.IsDisabled != false ||
         resource.IsInverted != false ||
         resource.IsNotLinked != false ||
         resource.Paths.Length != 7 ||
         resource.Paths[0].Type != VectorPathType.PathFillRuleRecord ||
         resource.Paths[1].Type != VectorPathType.InitialFillRuleRecord ||
         resource.Paths[2].Type != VectorPathType.ClosedSubpathLengthRecord ||
         resource.Paths[3].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
         resource.Paths[4].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
         resource.Paths[5].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
         resource.Paths[6].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked)
        {
            throw new Exception("VmskResource was read wrong");
        }
        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];
        // Ο κανόνας πλήρωσης διαδρομής δεν περιέχει πρόσθετες πληροφορίες
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
         initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
         initialFillRule.IsFillStartsWithAllPixels != false ||
         subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
         subpathLength.IsClosed != true ||
         subpathLength.IsOpen != false)
        {
            throw new Exception("VmskResource paths were read wrong");
        }
        // Επεξεργασία
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039797, 10905190);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VmskResource GetVmskResource(PsdImage image)
{
    var layer = image.Layers[1];
    VmskResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VmskResource)
        {
            resource = (VmskResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VmskResource not found");
    }
    return resource;
}
```

### Δείτε επίσης

* class [VectorPathDataResource](../vectorpathdataresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


