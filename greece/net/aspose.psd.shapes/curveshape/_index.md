---
title: "Κλάση CurveShape"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Η κλάση Aspose.PSD.Shapes.CurveShape. Αντιπροσωπεύει ένα σχήμα καμπυλωτής spline."
type: docs
weight: 5980
url: /el/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

Αναπαριστά ένα σχήμα καμπυλωτής καμπύλης.

```csharp
public sealed class CurveShape : PolygonShape
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `CurveShape`. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `CurveShape`. Η προεπιλεγμένη τάση 0.5 χρησιμοποιείται. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `CurveShape`. Η προεπιλεγμένη τάση 0.5 χρησιμοποιείται. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Αρχικοποιεί μια νέα παρουσία της κλάσης `CurveShape`. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `CurveShape`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Λαμβάνει τα όρια του αντικειμένου. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Λαμβάνει το κέντρο του σχήματος. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Λαμβάνει το τελικό σημείο του σχήματος. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα έχει τμήματα. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το σχήμα είναι κλειστό. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Λαμβάνει ή ορίζει τα σημεία της καμπύλης. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Λαμβάνει τα τμήματα του σχήματος. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Λαμβάνει το αρχικό σημείο του σχήματος. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Λαμβάνει ή ορίζει την τάση της καμπύλης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Λαμβάνει τα όρια του αντικειμένου. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Λαμβάνει τα όρια του αντικειμένου. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |

### Δείτε επίσης

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


