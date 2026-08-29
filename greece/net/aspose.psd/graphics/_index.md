---
title: "Κλάση Graphics"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Graphics. Αντιπροσωπεύει τα γραφικά σύμφωνα με τη μηχανή γραφικών που χρησιμοποιείται στην τρέχουσα συναρμολόγηση."
type: docs
weight: 4780
url: /el/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Αναπαριστά τα γραφικά σύμφωνα με τη μηχανή γραφικών που χρησιμοποιείται στην τρέχουσα συναρμολόγηση.

```csharp
public sealed class Graphics
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Graphics](graphics/)(Image) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Graphics`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Ανακτά ή ορίζει την περιοχή αποκοπής. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Ανακτά ή ορίζει την ποιότητα σύνθεσης. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Ανακτά την οριζόντια ανάλυση αυτού του Aspose.PSD.Graphics. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Ανακτά την κάθετη ανάλυση αυτού του Aspose.PSD.Graphics. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Ανακτά την εικόνα. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία παρεμβολής. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Ανακτά μια τιμή που υποδεικνύει εάν τα γραφικά βρίσκονται σε κατάσταση κλήσης BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Ανακτά ή ορίζει την κλίμακα μεταξύ μονάδων κόσμου και μονάδων σελίδας για αυτό το Aspose.PSD.Graphics. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Ανακτά ή ορίζει τη μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το Aspose.PSD.Graphics. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Ανακτά ή ορίζει επιλογές εικόνας, που χρησιμοποιούνται για τη δημιουργία σχεδιάσιμων διανυσματικών εικόνων για σχεδίαση. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία εξομάλυνσης. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Λαμβάνει ή ορίζει τη συμβουλή απόδοσης κειμένου. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Ανακτά ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού κόσμου για αυτό το `Graphics`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Ξεκινά την προσωρινή αποθήκευση των παρακάτω λειτουργιών γραφικών. Τα εφέ γραφικών που εφαρμόζονται μετά δεν θα εφαρμοστούν αμέσως· αντί αυτού, το EndUpdate θα προκαλέσει την εφαρμογή όλων των εφέ ταυτόχρονα. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Καθαρίζει την επιφάνεια γραφικών χρησιμοποιώντας το καθορισμένο χρώμα. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή [`Rectangle`](../rectangle/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή [`RectangleF`](../rectanglef/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές [`Point`](../point/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές [`PointF`](../pointf/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερα διατεταγμένα ζεύγη συντεταγμένων που αντιπροσωπεύουν σημεία. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών [`PointF`](../pointf/). |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών [`Point`](../point/). |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Σχεδιάζει μια κλειστή καρδιακή καμπύλη που ορίζεται από έναν πίνακα δομών [`PointF`](../pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5 και εναλλακτικό τρόπο γεμίσματος. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Σχεδιάζει μια κλειστή καρδιακή καμπύλη που ορίζεται από έναν πίνακα δομών [`Point`](../point/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5 και εναλλακτικό τρόπο γεμίσματος. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Σχεδιάζει μια κλειστή καρδιακή καμπύλη που ορίζεται από έναν πίνακα δομών [`PointF`](../pointf/) χρησιμοποιώντας καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένο εναλλακτικό τρόπο γεμίσματος. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Σχεδιάζει μια κλειστή καρδιακή καμπύλη που ορίζεται από έναν πίνακα δομών [`Point`](../point/) χρησιμοποιώντας καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένο εναλλακτικό τρόπο γεμίσματος. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`PointF`](../pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`Point`](../point/). |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`PointF`](../pointf/) χρησιμοποιώντας καθορισμένη τάση. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`Point`](../point/) χρησιμοποιώντας καθορισμένη τάση. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`PointF`](../pointf/). Η σχεδίαση ξεκινά με μετατόπιση από την αρχή του πίνακα. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`PointF`](../pointf/) χρησιμοποιώντας καθορισμένη τάση. Η σχεδίαση ξεκινά με μετατόπιση από την αρχή του πίνακα. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών [`Point`](../point/) χρησιμοποιώντας καθορισμένη τάση. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Σχεδιάζει μια έλλειψη που καθορίζεται από μια περιβάλλουσα δομή [`Rectangle`](../rectangle/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα δομή [`RectangleF`](../rectanglef/). |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα ορθογώνια περιοχή που καθορίζεται από ένα ζεύγος συντεταγμένων, ύψος και πλάτος. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα ορθογώνια περιοχή που καθορίζεται από ένα ζεύγος συντεταγμένων, ύψος και πλάτος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Σχεδιάζει το καθορισμένο [`Image`](./image/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Σχεδιάζει το καθορισμένο [`Image`](./image/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης *image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης *image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Σχεδιάζει το καθορισμένο [`Image`](./image/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Σχεδιάζει την καθορισμένη εικόνα, χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην τοποθεσία που καθορίζεται από ένα ζεύγος συντεταγμένων. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης *image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης *image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης *image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης *image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης *image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης *image* στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Σχεδιάζει το καθορισμένο [`Image`](./image/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Σχεδιάζει την καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος στην τοποθεσία που καθορίζεται από ένα ζεύγος συντεταγμένων. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Σχεδιάζει την καθορισμένη εικόνα χωρίς κλιμάκωση και την περικόπτει, εάν είναι απαραίτητο, ώστε να χωράει στο καθορισμένο ορθογώνιο. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Σχεδιάζει μια γραμμή που συνδέει δύο δομές [`Point`](../point/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Σχεδιάζει μια γραμμή που συνδέει δύο δομές [`PointF`](../pointf/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών [`PointF`](../pointf/). |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών [`Point`](../point/). |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Σχεδιάζει ένα [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή [`Rectangle`](../rectangle/) και δύο ακτινικές γραμμές. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή [`RectangleF`](../rectanglef/) και δύο ακτινικές γραμμές. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, πλάτος, ύψος και δύο ακτινικές γραμμές. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, πλάτος, ύψος και δύο ακτινικές γραμμές. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών [`PointF`](../pointf/). |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών [`Point`](../point/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή [`Rectangle`](../rectangle/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή [`RectangleF`](../rectanglef/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, πλάτος και ύψος. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, πλάτος και ύψος. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές [`RectangleF`](../rectanglef/). |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές [`Rectangle`](../rectangle/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα [`Brush`](../brush/) και [`Font`](../font/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα [`Brush`](../brush/) και [`Font`](../font/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα [`Brush`](../brush/) και [`Font`](../font/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα [`Brush`](../brush/) και [`Font`](../font/) χρησιμοποιώντας τα χαρακτηριστικά μορφοποίησης του καθορισμένου [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα [`Brush`](../brush/) και [`Font`](../font/) χρησιμοποιώντας τα χαρακτηριστικά μορφοποίησης του καθορισμένου [`StringFormat`](../stringformat/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα [`Brush`](../brush/) και [`Font`](../font/) χρησιμοποιώντας τα χαρακτηριστικά μορφοποίησης του καθορισμένου [`StringFormat`](../stringformat/). |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Ολοκληρώνει την προσωρινή αποθήκευση των λειτουργιών γραφικών που ξεκίνησαν μετά την κλήση του BeginUpdate. Οι προηγούμενες λειτουργίες γραφικών θα εφαρμοστούν αμέσως κατά την κλήση αυτής της μεθόδου. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`PointF`](../pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και εναλλακτικό τρόπο γεμίσματος. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`Point`](../point/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και εναλλακτικό τρόπο γεμίσματος. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`PointF`](../pointf/) χρησιμοποιώντας τον καθορισμένο τρόπο γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`Point`](../point/) χρησιμοποιώντας τον καθορισμένο τρόπο γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`PointF`](../pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος και την τάση. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών [`Point`](../point/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος και την τάση. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από μια δομή [`Rectangle`](../rectangle/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από μια δομή [`RectangleF`](../rectanglef/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Γεμίζει το εσωτερικό ενός [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από μια δομή [`RectangleF`](../rectanglef/) και δύο ακτινικές γραμμές. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από μια δομή [`RectangleF`](../rectanglef/) και δύο ακτινικές γραμμές. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από δομές [`PointF`](../pointf/) και Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από δομές [`Point`](../point/) και Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από δομές [`PointF`](../pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από δομές [`Point`](../point/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια δομή [`Rectangle`](../rectangle/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια δομή [`RectangleF`](../rectanglef/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από δομές [`RectangleF`](../rectanglef/). |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από δομές [`Rectangle`](../rectangle/). |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Γεμίζει το εσωτερικό ενός [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Πολλαπλασιάζει το [`Matrix`](../matrix/) που αντιπροσωπεύει τη τοπική γεωμετρική μετατροπή αυτού του `Graphics` με το καθορισμένο [`Matrix`](../matrix/) προσθέτοντας το καθορισμένο [`Matrix`](../matrix/) στην αρχή. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Πολλαπλασιάζει το [`Matrix`](../matrix/) που αντιπροσωπεύει τη τοπική γεωμετρική μετατροπή αυτού του `Graphics` με το καθορισμένο [`Matrix`](../matrix/) με τη συγκεκριμένη σειρά. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Επαναφέρει την ιδιότητα [`Transform`](./transform/) στην ταυτότητα. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό στην αρχή. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με τη συγκεκριμένη σειρά. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα μεγέθη. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό στην αρχή. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα μεγέθη με τη συγκεκριμένη σειρά. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό στην αρχή. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με τη συγκεκριμένη σειρά. |

## Παραδείγματα

Αυτό το παράδειγμα χρησιμοποιεί την κλάση Graphics για τη δημιουργία πρωτόγονων σχημάτων στην επιφάνεια Image. Για να επιδείξει τη λειτουργία, το παράδειγμα δημιουργεί ένα νέο Image σε μορφή PSD και σχεδιάζει πρωτόγονα σχήματα στην επιφάνεια Image χρησιμοποιώντας τις μεθόδους Draw που εκτίθενται από την κλάση Graphics, στη συνέχεια το εξάγει σε μορφή αρχείου PSD.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργήστε και αρχικοποιήστε ένα στιγμιότυπο της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίστε την επιφάνεια Graphics
    graphics.Clear(Color.Wheat);

    //Σχεδιάστε ένα τόξο καθορίζοντας το αντικείμενο Pen με χρώμα Μαύρο, 
    //ένα Rectangle που περιβάλλει το τόξο, η γωνία έναρξης και η γωνία σάρωσης
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Σχεδιάστε μια καμπύλη Bezier καθορίζοντας το αντικείμενο Pen με χρώμα Μπλε και σημεία συντεταγμένων.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Σχεδιάστε μια Καμπύλη καθορίζοντας το αντικείμενο Pen με χρώμα Πράσινο και έναν πίνακα σημείων
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Σχεδιάστε μια Έλλειψη χρησιμοποιώντας το αντικείμενο Pen και ένα περιβάλλον Rectangle
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Σχεδιάστε μια Γραμμή 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Σχεδιάστε ένα τμήμα Πίτας
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Σχεδιάστε ένα Πολύγωνο καθορίζοντας το αντικείμενο Pen με χρώμα Κόκκινο και έναν πίνακα σημείων
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Σχεδιάστε ένα Rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Δημιουργήστε ένα αντικείμενο SolidBrush και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Σχεδιάστε ένα String χρησιμοποιώντας το αντικείμενο SolidBrush και τη Font, σε συγκεκριμένο Point
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Δημιουργήστε ένα στιγμιότυπο του PngOptions και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // αποθηκεύστε όλες τις αλλαγές.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


