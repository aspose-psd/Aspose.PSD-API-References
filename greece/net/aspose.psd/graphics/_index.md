---
title: Class Graphics
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Graphics τάξη. Αντιπροσωπεύει τα γραφικά σύμφωνα με τη μηχανή γραφικών που χρησιμοποιείται στην τρέχουσα διάταξη.
type: docs
weight: 4310
url: /el/net/aspose.psd/graphics/
---
## Graphics class

Αντιπροσωπεύει τα γραφικά σύμφωνα με τη μηχανή γραφικών που χρησιμοποιείται στην τρέχουσα διάταξη.

```csharp
public sealed class Graphics
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Graphics](graphics/)(Image) | Αρχικοποιεί μια νέα παρουσία του`Graphics` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Λαμβάνει ή ορίζει την περιοχή του κλιπ. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Λαμβάνει ή ρυθμίζει την ποιότητα σύνθεσης. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Λαμβάνει την οριζόντια ανάλυση αυτού του Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Λαμβάνει την κατακόρυφη ανάλυση αυτού του Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Λαμβάνει την εικόνα. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία παρεμβολής. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα γραφικά βρίσκονται σε κατάσταση κλήσης BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Λαμβάνει ή ορίζει την κλίμακα μεταξύ των παγκόσμιων μονάδων και των μονάδων σελίδας για αυτό το Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Λαμβάνει ή ορίζει τη μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το Aspose.PSD.Graphics. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία εξομάλυνσης. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη απόδοσης κειμένου. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Λαμβάνει ή ορίζει ένα αντίγραφο του μετασχηματισμού του γεωμετρικού κόσμου για αυτό`Graphics` . |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Ξεκινά την προσωρινή αποθήκευση των ακόλουθων λειτουργιών γραφικών. Τα εφέ γραφικών που εφαρμόστηκαν στη συνέχεια δεν θα εφαρμοστούν αμέσως, αλλά το EndUpdate θα προκαλέσει την εφαρμογή όλων των εφέ ταυτόχρονα. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Καθαρίζει την επιφάνεια γραφικών χρησιμοποιώντας το καθορισμένο χρώμα. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα μιας έλλειψης που καθορίζεται από ένα[`Rectangle`](../rectangle/)δομή. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα μιας έλλειψης που καθορίζεται από ένα[`RectangleF`](../rectanglef/)δομή. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα μιας έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα μιας έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Σχεδιάζει μια spline Bézier που ορίζεται από τέσσερα[`Point`](../point/) δομές. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Σχεδιάζει μια spline Bézier που ορίζεται από τέσσερα[`PointF`](../pointf/) δομές. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Σχεδιάζει μια spline Bézier που ορίζεται από τέσσερα διατεταγμένα ζεύγη συντεταγμένων που αντιπροσωπεύουν σημεία. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Σχεδιάζει μια σειρά γραμμών Bézier από έναν πίνακα[`PointF`](../pointf/) δομές. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Σχεδιάζει μια σειρά γραμμών Bézier από έναν πίνακα[`Point`](../point/) δομές. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Σχεδιάζει μια κλειστή βασική spline που ορίζεται από έναν πίνακα[`PointF`](../pointf/) δομές. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5 καιAlternate λειτουργία πλήρωσης. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Σχεδιάζει μια κλειστή βασική spline που ορίζεται από έναν πίνακα[`Point`](../point/) δομές. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5 καιAlternate λειτουργία πλήρωσης. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Σχεδιάζει μια κλειστή βασική spline που ορίζεται από έναν πίνακα[`PointF`](../pointf/) κατασκευές που χρησιμοποιούν μια καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλογήAlternate λειτουργία πλήρωσης. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Σχεδιάζει μια κλειστή βασική spline που ορίζεται από έναν πίνακα[`Point`](../point/) κατασκευές που χρησιμοποιούν μια καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλογήAlternate λειτουργία πλήρωσης. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`PointF`](../pointf/) δομές. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`Point`](../point/) δομές. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`PointF`](../pointf/) δομές που χρησιμοποιούν μια καθορισμένη τάση. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`Point`](../point/) δομές που χρησιμοποιούν μια καθορισμένη τάση. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`PointF`](../pointf/) δομές. Το σχέδιο αρχίζει με μετατόπιση από την αρχή του πίνακα. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`PointF`](../pointf/) κατασκευές που χρησιμοποιούν μια καθορισμένη τάση. Το σχέδιο αρχίζει με μετατόπιση από την αρχή του πίνακα. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Σχεδιάζει έναν βασικό spline μέσα από έναν καθορισμένο πίνακα[`Point`](../point/) δομές που χρησιμοποιούν μια καθορισμένη τάση. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Σχεδιάζει μια έλλειψη που καθορίζεται από ένα όριο[`Rectangle`](../rectangle/)δομή. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Σχεδιάζει μια έλλειψη που ορίζεται από ένα όριο[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Σχεδιάζει μια έλλειψη που ορίζεται από ένα οριοθετημένο ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Σχεδιάζει μια έλλειψη που ορίζεται από ένα οριοθετημένο ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Σχεδιάζει το καθορισμένο[`Image`](./image/) , χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη τοποθεσία. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Σχεδιάζει το καθορισμένο[`Image`](./image/) , χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη τοποθεσία. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Σχεδιάζει το καθορισμένο τμήμα του καθορισμένου*image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Σχεδιάζει το καθορισμένο τμήμα του καθορισμένου*image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Σχεδιάζει το καθορισμένο[`Image`](./image/) , χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη τοποθεσία. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Σχεδιάζει την καθορισμένη εικόνα, χρησιμοποιώντας το αρχικό της φυσικό μέγεθος, στη θέση που καθορίζεται από ένα ζεύγος συντεταγμένων. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Σχεδιάζει το καθορισμένο τμήμα του καθορισμένου*image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Σχεδιάζει το καθορισμένο τμήμα του καθορισμένου*image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Σχεδιάζει το καθορισμένο τμήμα του καθορισμένου*image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Σχεδιάζει το καθορισμένο τμήμα του καθορισμένου*image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο τμήμα του καθορισμένου*image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο τμήμα του καθορισμένου*image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο[`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη τοποθεσία. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη τοποθεσία. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Σχεδιάζει την καθορισμένη εικόνα χρησιμοποιώντας το αρχικό της φυσικό μέγεθος στη θέση που καθορίζεται από ένα ζεύγος συντεταγμένων. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη τοποθεσία. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Σχεδιάζει την καθορισμένη εικόνα χωρίς κλιμάκωση και την κόβει, εάν χρειάζεται, για να χωρέσει στο καθορισμένο ορθογώνιο. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Σχεδιάζει μια γραμμή που συνδέει δύο[`Point`](../point/) δομές. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Σχεδιάζει μια γραμμή που συνδέει δύο[`PointF`](../pointf/) δομές. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα[`PointF`](../pointf/) δομές. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα[`Point`](../point/) δομές. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Ζωγραφίζει α[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από το α[`Rectangle`](../rectangle/) δομή και δύο ακτινικές γραμμές. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από το α[`RectangleF`](../rectanglef/) δομή και δύο ακτινικές γραμμές. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα[`PointF`](../pointf/) δομές. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα[`Point`](../point/) δομές. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από το α[`Rectangle`](../rectangle/)δομή. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από το α[`RectangleF`](../rectanglef/)δομή. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από[`RectangleF`](../rectanglef/) δομές. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από[`Rectangle`](../rectangle/) δομές. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένη[`Brush`](../brush/) και[`Font`](../font/) αντικείμενα. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με το καθορισμένο[`Brush`](../brush/) και[`Font`](../font/) αντικείμενα. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένη[`Brush`](../brush/) και[`Font`](../font/) αντικείμενα. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένη[`Brush`](../brush/) και[`Font`](../font/) αντικείμενα που χρησιμοποιούν τα χαρακτηριστικά μορφοποίησης του καθορισμένου[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με το καθορισμένο[`Brush`](../brush/) και[`Font`](../font/) αντικείμενα που χρησιμοποιούν τα χαρακτηριστικά μορφοποίησης του καθορισμένου[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Σχεδιάζει την καθορισμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με την καθορισμένη[`Brush`](../brush/) και[`Font`](../font/) αντικείμενα που χρησιμοποιούν τα χαρακτηριστικά μορφοποίησης του καθορισμένου[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Ολοκληρώνει την προσωρινή αποθήκευση των λειτουργιών γραφικών που ξεκίνησαν μετά την κλήση του BeginUpdate. Οι προηγούμενες λειτουργίες γραφικών θα εφαρμοστούν ταυτόχρονα κατά την κλήση αυτής της μεθόδου. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Γεμίζει το εσωτερικό μιας κλειστής καμπύλης βασικού spline που ορίζεται από έναν πίνακα[`PointF`](../pointf/) δομές. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5 καιAlternate λειτουργία πλήρωσης. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Γεμίζει το εσωτερικό μιας κλειστής καμπύλης βασικού spline που ορίζεται από έναν πίνακα[`Point`](../point/) δομές. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5 καιAlternate λειτουργία πλήρωσης. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Γεμίζει το εσωτερικό μιας κλειστής καμπύλης βασικού spline που ορίζεται από έναν πίνακα[`PointF`](../pointf/) δομές που χρησιμοποιούν την καθορισμένη λειτουργία πλήρωσης. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Γεμίζει το εσωτερικό μιας κλειστής καμπύλης βασικού spline που ορίζεται από έναν πίνακα[`Point`](../point/) δομές που χρησιμοποιούν την καθορισμένη λειτουργία πλήρωσης. Αυτή η μέθοδος χρησιμοποιεί μια προεπιλεγμένη τάση 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Γεμίζει το εσωτερικό μιας κλειστής καμπύλης βασικού spline που ορίζεται από έναν πίνακα[`PointF`](../pointf/) δομές που χρησιμοποιούν τον καθορισμένο τρόπο πλήρωσης και τάση. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Γεμίζει το εσωτερικό μιας κλειστής καμπύλης βασικού spline που ορίζεται από έναν πίνακα[`Point`](../point/) δομές που χρησιμοποιούν τον καθορισμένο τρόπο πλήρωσης και τάση. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Γεμίζει το εσωτερικό μιας έλλειψης που ορίζεται από ένα οριοθετημένο ορθογώνιο που καθορίζεται από ένα[`Rectangle`](../rectangle/)δομή. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Γεμίζει το εσωτερικό μιας έλλειψης που ορίζεται από ένα οριοθετημένο ορθογώνιο που καθορίζεται από ένα[`RectangleF`](../rectanglef/)δομή. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Γεμίζει το εσωτερικό μιας έλλειψης που ορίζεται από ένα οριοθετημένο ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Γεμίζει το εσωτερικό μιας έλλειψης που ορίζεται από ένα οριοθετημένο ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Γεμίζει το εσωτερικό του α[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα[`RectangleF`](../rectanglef/) δομή και δύο ακτινικές γραμμές. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα[`RectangleF`](../rectanglef/) δομή και δύο ακτινικές γραμμές. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζεται από[`PointF`](../pointf/) δομές καιAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζεται από[`Point`](../point/) δομές καιAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζεται από[`PointF`](../pointf/) δομές που χρησιμοποιούν την καθορισμένη λειτουργία πλήρωσης. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζεται από[`Point`](../point/) δομές που χρησιμοποιούν την καθορισμένη λειτουργία πλήρωσης. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από το α[`Rectangle`](../rectangle/)δομή. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από το α[`RectangleF`](../rectanglef/)δομή. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Γεμίζει το εσωτερικό μιας σειράς ορθογωνίων που καθορίζονται από[`RectangleF`](../rectanglef/) δομές. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Γεμίζει το εσωτερικό μιας σειράς ορθογωνίων που καθορίζονται από[`Rectangle`](../rectangle/) δομές. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Γεμίζει το εσωτερικό του α[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Πολλαπλασιάζει το[`Matrix`](../matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού`Graphics` από τα καθορισμένα[`Matrix`](../matrix/) με την προετοιμασία του καθορισμένου[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Πολλαπλασιάζει το[`Matrix`](../matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού`Graphics` από τα καθορισμένα[`Matrix`](../matrix/) με την καθορισμένη σειρά. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Επαναφέρει το[`Transform`](./transform/) ιδιοκτησία στην ταυτότητα. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προϋποθέτει την περιστροφή στον μετασχηματισμό. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσαρτά τον πίνακα κλιμάκωσης στον μετασχηματισμό. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με την καθορισμένη σειρά. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προϋποθέτει τη μετάφραση στον μετασχηματισμό. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |

### Παραδείγματα

Αυτό το παράδειγμα χρησιμοποιεί την κλάση Graphics για τη δημιουργία πρωτόγονων σχημάτων στην επιφάνεια της εικόνας. Για την επίδειξη της λειτουργίας, το παράδειγμα δημιουργεί μια νέα εικόνα σε μορφή PSD και σχεδιάζει πρωτόγονα σχήματα στην επιφάνεια της εικόνας χρησιμοποιώντας μεθόδους Draw που εκτίθενται από την κλάση Graphics και στη συνέχεια την εξάγει σε μορφή αρχείου PSD.

```csharp
[C#]

//Δημιουργία μιας παρουσίας εικόνας 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργία και προετοιμασία μιας παρουσίας της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Διαγραφή επιφάνειας γραφικών
    graphics.Clear(Color.Wheat);

    //Σχεδιάστε ένα τόξο καθορίζοντας το αντικείμενο Pen να έχει μαύρο χρώμα, 
    //α Ορθογώνιο που περιβάλλει το τόξο, τη γωνία έναρξης και τη γωνία σάρωσης
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Σχεδιάστε ένα Bezier καθορίζοντας το αντικείμενο Pen να έχει μπλε χρώμα και συντεταγμένα σημεία.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Σχεδιάστε μια καμπύλη καθορίζοντας το αντικείμενο Pen να έχει πράσινο χρώμα και έναν πίνακα σημείων
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Σχεδιάστε μια έλλειψη χρησιμοποιώντας το αντικείμενο στυλό και ένα ορθογώνιο που το περιβάλλει
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //ΖΩΓΡΑΦΙΣΕ μια γραμμη 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Σχεδιάστε ένα τμήμα πίτας
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Σχεδιάστε ένα πολύγωνο καθορίζοντας το αντικείμενο Pen να έχει κόκκινο χρώμα και έναν πίνακα σημείων
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Σχεδιάστε ένα ορθογώνιο
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Δημιουργήστε ένα αντικείμενο SolidBrush και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Σχεδιάστε μια συμβολοσειρά χρησιμοποιώντας το αντικείμενο SolidBrush και τη γραμματοσειρά, σε συγκεκριμένο σημείο
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Δημιουργήστε μια παρουσία του PngOptions και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // αποθήκευση όλων των αλλαγών.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


