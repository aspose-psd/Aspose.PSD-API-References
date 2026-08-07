---
title: "Graphics"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά τα γραφικά σύμφωνα με τη μηχανή γραφικών που χρησιμοποιείται στην τρέχουσα συναρμολόγηση"
type: docs
weight: 49
url: /el/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Αναπαριστά τα γραφικά σύμφωνα με τη μηχανή γραφικών που χρησιμοποιείται στην τρέχουσα συναρμολόγηση
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  Graphics  . |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Λαμβάνει τον συντελεστή μεγέθους του στυλ έντονου κειμένου |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Λαμβάνει τον συντελεστή μεγέθους του στυλ πλάγιου κειμένου |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Εφαρμόζει το εφέ. |
| [beginUpdate()](#beginUpdate--) | Ξεκινά την προσωρινή αποθήκευση των παρακάτω λειτουργιών γραφικών. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Καθαρίζει την επιφάνεια γραφικών χρησιμοποιώντας το καθορισμένο χρώμα. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή  Rectangle . |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή  RectangleF . |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές  Point . |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές  PointF . |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερα ζεύγη διατεταγμένων συντεταγμένων που αντιπροσωπεύουν σημεία. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών  PointF . |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών  Point . |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Σχεδιάζει μια κλειστή καρδιακή καμπύλη που ορίζεται από έναν πίνακα δομών  PointF . |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Σχεδιάζει μια κλειστή καρδιακή καμπύλη που ορίζεται από έναν πίνακα δομών  PointF  χρησιμοποιώντας μια καθορισμένη τάση. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Σχεδιάζει μια κλειστή καρδιακή καμπύλη που ορίζεται από έναν πίνακα δομών  Point . |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Σχεδιάζει μια κλειστή καρδιακή καμπύλη που ορίζεται από έναν πίνακα δομών  Point  χρησιμοποιώντας μια καθορισμένη τάση. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  PointF . |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  PointF  χρησιμοποιώντας μια καθορισμένη τάση. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  PointF . |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  PointF  χρησιμοποιώντας μια καθορισμένη τάση. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  Point . |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  Point  χρησιμοποιώντας μια καθορισμένη τάση. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  Point  χρησιμοποιώντας μια καθορισμένη τάση. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Σχεδιάζει μια έλλειψη που καθορίζεται από μια περιβάλλουσα δομή  Rectangle . |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα  RectangleF . |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα ορθογώνια που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα ορθογώνια που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Σχεδιάζει την καθορισμένη  Image , χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην καθορισμένη θέση. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Σχεδιάζει την καθορισμένη  Image , χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην καθορισμένη θέση. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Σχεδιάζει την καθορισμένη  Image , χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην καθορισμένη θέση. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Σχεδιάζει την καθορισμένη εικόνα, χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην θέση που καθορίζεται από ένα ζεύγος συντεταγμένων. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Σχεδιάζει την καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος στην θέση που καθορίζεται από ένα ζεύγος συντεταγμένων. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Σχεδιάζει την καθορισμένη εικόνα χωρίς κλιμάκωση και την περικόπτει, εάν είναι απαραίτητο, ώστε να ταιριάζει στο καθορισμένο ορθογώνιο. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Σχεδιάζει μια γραμμή που συνδέει δύο δομές  Point . |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Σχεδιάζει μια γραμμή που συνδέει δύο δομές  PointF . |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών  PointF . |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών  Point  . |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Σχεδιάζει ένα  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή  Rectangle  και δύο ακτινικές γραμμές. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή  RectangleF  και δύο ακτινικές γραμμές. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών  PointF  . |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών  Point  . |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή  Rectangle  . |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή  RectangleF  . |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές  RectangleF  . |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές  Rectangle  . |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font . |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font  χρησιμοποιώντας τις ιδιότητες μορφοποίησης του καθορισμένου  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font . |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font  χρησιμοποιώντας τις ιδιότητες μορφοποίησης του καθορισμένου  com.aspose.psd.stringFormat . |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font . |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font  χρησιμοποιώντας τις ιδιότητες μορφοποίησης του καθορισμένου  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου με τρόπο συμβατό με το Adobe στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font  χρησιμοποιώντας τις ιδιότητες μορφοποίησης του καθορισμένου  com.aspose.psd.stringFormat . |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου με τρόπο συμβατό με το Adobe στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font . |
| [endUpdate()](#endUpdate--) | Ολοκληρώνει την προσωρινή αποθήκευση των λειτουργιών γραφικών που ξεκίνησαν μετά την κλήση του BeginUpdate. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Γεμίζει το εσωτερικό ενός κλειστού καρδινάλου καμπύλου spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.PointF  . |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Γεμίζει το εσωτερικό ενός κλειστού καρδινάλου καμπύλου spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.PointF  χρησιμοποιώντας τη καθορισμένη λειτουργία γεμίσματος. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Γεμίζει το εσωτερικό ενός κλειστού καρδινάλου καμπύλου spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.PointF  χρησιμοποιώντας τη καθορισμένη λειτουργία γεμίσματος και τάση. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Γεμίζει το εσωτερικό ενός κλειστού καρδινάλου καμπύλου spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.Point  . |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Γεμίζει το εσωτερικό ενός κλειστού καρδινάλου καμπύλου spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.Point  χρησιμοποιώντας τη καθορισμένη λειτουργία γεμίσματος. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Γεμίζει το εσωτερικό ενός κλειστού καρδινάλου καμπύλου spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.Point  χρησιμοποιώντας τη καθορισμένη λειτουργία γεμίσματος και τάση. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από μια  com.aspose.psd.Rectangle  δομή. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από μια  com.aspose.psd.RectangleF  δομή. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, και ένα ύψος. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, και ένα ύψος. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Γεμίζει το εσωτερικό ενός  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από μια  com.aspose.psd.RectangleF  δομή και δύο ακτινικές γραμμές. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από μια  com.aspose.psd.RectangleF  δομή και δύο ακτινικές γραμμές. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από  com.aspose.psd.PointF  δομές και  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από  com.aspose.psd.PointF  δομές χρησιμοποιώντας την καθορισμένη λειτουργία γεμίσματος. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από  com.aspose.psd.Point  δομές και  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από  com.aspose.psd.Point  δομές χρησιμοποιώντας την καθορισμένη λειτουργία γεμίσματος. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια  Rectangle  δομή. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια  RectangleF  δομή. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από  RectangleF  δομές. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από  Rectangle  δομές. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Γεμίζει το εσωτερικό ενός  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Λαμβάνει ή ορίζει την περιοχή αποκοπής. |
| [getCompositingQuality()](#getCompositingQuality--) | Λαμβάνει ή ορίζει την ποιότητα σύνθεσης. |
| [getDpiX()](#getDpiX--) | Λαμβάνει την οριζόντια ανάλυση αυτού του com.aspose.psd.graphics. |
| [getDpiY()](#getDpiY--) | Λαμβάνει την κάθετη ανάλυση αυτού του com.aspose.psd.graphics. |
| [getImage()](#getImage--) | Λαμβάνει την εικόνα. |
| [getInterpolationMode()](#getInterpolationMode--) | Λαμβάνει ή ορίζει τη λειτουργία παρεμβολής. |
| [getPageScale()](#getPageScale--) | Λαμβάνει ή ορίζει την κλίμακα μεταξύ των μονάδων κόσμου και των μονάδων σελίδας για αυτό το com.aspose.psd.graphics. |
| [getPageUnit()](#getPageUnit--) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το com.aspose.psd.graphics. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Λαμβάνει ή ορίζει τις επιλογές εικόνας, που χρησιμοποιούνται για τη δημιουργία ζωγραφίσιμων διανυσματικών εικόνων για σχεδίαση. |
| [getSmoothingMode()](#getSmoothingMode--) | Λαμβάνει ή ορίζει τη λειτουργία εξομάλυνσης. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Λαμβάνει ή ορίζει τη συμβουλή απόδοσης κειμένου. |
| [getTransform()](#getTransform--) | Λαμβάνει ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού κόσμου για αυτό το  com.aspose.psd.graphics . |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Λαμβάνει μια τιμή που υποδεικνύει εάν τα γραφικά βρίσκονται στην κατάσταση κλήσης BeginUpdate. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Μετρά τη συμβολοσειρά χρησιμοποιώντας την κλάση [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Μετρά τη συμβολοσειρά. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Μετρά τη συγκεκριμένη συμβολοσειρά κειμένου με τα καθορισμένα παραμέτρους |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Πολλαπλασιάζει το  com.aspose.psd.Matrix  που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του  com.aspose.psd.Graphics  με το καθορισμένο  com.aspose.psd.Matrix  προσθέτοντας στην αρχή το καθορισμένο  com.aspose.psd.matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Πολλαπλασιάζει το  com.aspose.psd.Matrix  που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του  com.aspose.psd.Graphics  με το καθορισμένο  com.aspose.psd.Matrix  με τη καθορισμένη σειρά. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Επαναφέρει την ιδιότητα  com.aspose.psd.graphics.Transform  στην ταυτότητα. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με τη συγκεκριμένη σειρά. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με τη συγκεκριμένη σειρά. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Λαμβάνει ή ορίζει την περιοχή αποκοπής. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Λαμβάνει ή ορίζει την ποιότητα σύνθεσης. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Λαμβάνει ή ορίζει τη λειτουργία παρεμβολής. |
| [setPageScale(float value)](#setPageScale-float-) | Λαμβάνει ή ορίζει την κλίμακα μεταξύ των μονάδων κόσμου και των μονάδων σελίδας για αυτό το com.aspose.psd.graphics. |
| [setPageUnit(int value)](#setPageUnit-int-) | Λαμβάνει ή ορίζει τη μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το com.aspose.psd.graphics. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Λαμβάνει ή ορίζει τις επιλογές εικόνας, που χρησιμοποιούνται για τη δημιουργία ζωγραφίσιμων διανυσματικών εικόνων για σχεδίαση. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Λαμβάνει ή ορίζει τη λειτουργία εξομάλυνσης. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Λαμβάνει ή ορίζει τη συμβουλή απόδοσης κειμένου. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Λαμβάνει ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού κόσμου για αυτό το  com.aspose.psd.graphics . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις με τη καθορισμένη σειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  Graphics  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η πηγαία εικόνα. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Λαμβάνει τον συντελεστή μεγέθους του στυλ έντονου κειμένου

Χρήση μαγικών αριθμών επειδή το GDI παρέχει πάντα μέτρηση μόνο για το κανονικό στυλ.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Λαμβάνει τον συντελεστή μεγέθους του στυλ πλάγιου κειμένου

Χρήση μαγικών αριθμών επειδή το GDI παρέχει πάντα μέτρηση μόνο για το κανονικό στυλ.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Εφαρμόζει το εφέ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εφέ | com.aspose.internal.IEffect | Το εφέ προς εφαρμογή. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Ξεκινά την προσωρινή αποθήκευση των παρακάτω λειτουργιών γραφικών. Τα εφέ γραφικών που θα εφαρμοστούν μετά δεν θα εφαρμοστούν αμέσως· αντίθετα, το EndUpdate θα προκαλέσει την εφαρμογή όλων των εφέ ταυτόχρονα.

Σημειώστε ότι τα εφέ μετά την κλήση του BeginUpdate δεν θα εφαρμοστούν εάν δεν κληθεί το EndUpdate.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Καθαρίζει την επιφάνεια γραφικών χρησιμοποιώντας το καθορισμένο χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Το χρώμα με το οποίο θα καθαριστεί η επιφάνεια γραφικών. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή  Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Δομή RectangleF  που ορίζει τα όρια της έλλειψης. |
| startAngle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα x μέχρι το σημείο έναρξης της καμπύλης. |
| sweepAngle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από την παράμετρο  startAngle  μέχρι το σημείο λήξης της καμπύλης. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή  RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Δομή RectangleF  που ορίζει τα όρια της έλλειψης. |
| startAngle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα x μέχρι το σημείο έναρξης της καμπύλης. |
| sweepAngle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από την παράμετρο  startAngle  μέχρι το σημείο λήξης της καμπύλης. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη. |
| πλάτος | float | Πλάτος του ορθογωνίου που ορίζει την έλλειψη. |
| ύψος | float | Ύψος του ορθογωνίου που ορίζει την έλλειψη. |
| startAngle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα x μέχρι το σημείο έναρξης της καμπύλης. |
| sweepAngle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από την παράμετρο  startAngle  μέχρι το σημείο λήξης της καμπύλης. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη. |
| πλάτος | int | Πλάτος του ορθογωνίου που ορίζει την έλλειψη. |
| ύψος | int | Ύψος του ορθογωνίου που ορίζει την έλλειψη. |
| startAngle | int | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα x μέχρι το σημείο έναρξης της καμπύλης. |
| sweepAngle | int | Γωνία σε μοίρες που μετράται δεξιόστροφα από την παράμετρο  startAngle  μέχρι το σημείο λήξης της καμπύλης. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές  Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Δομή Pen  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| pt1 | [Point](../../com.aspose.psd/point) | Δομή Point  που αντιπροσωπεύει το σημείο εκκίνησης της καμπύλης. |
| pt2 | [Point](../../com.aspose.psd/point) | Δομή Point  που αντιπροσωπεύει το πρώτο σημείο ελέγχου για την καμπύλη. |
| pt3 | [Point](../../com.aspose.psd/point) | Δομή Point  που αντιπροσωπεύει το δεύτερο σημείο ελέγχου για την καμπύλη. |
| pt4 | [Point](../../com.aspose.psd/point) | Δομή Point  που αντιπροσωπεύει το σημείο λήξης της καμπύλης. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές  PointF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | Δομή PointF  που αντιπροσωπεύει το σημείο εκκίνησης της καμπύλης. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | Δομή PointF  που αντιπροσωπεύει το πρώτο σημείο ελέγχου για την καμπύλη. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | Δομή PointF  που αντιπροσωπεύει το δεύτερο σημείο ελέγχου για την καμπύλη. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | Δομή PointF  που αντιπροσωπεύει το σημείο λήξης της καμπύλης. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερα ζεύγη διατεταγμένων συντεταγμένων που αντιπροσωπεύουν σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| x1 | float | Η συντεταγμένη x του σημείου εκκίνησης της καμπύλης. |
| y1 | float | Η συντεταγμένη y του σημείου εκκίνησης της καμπύλης. |
| x2 | float | Η συντεταγμένη x του πρώτου σημείου ελέγχου της καμπύλης. |
| y2 | float | Η συντεταγμένη y του πρώτου σημείου ελέγχου της καμπύλης. |
| x3 | float | Η συντεταγμένη x του δεύτερου σημείου ελέγχου της καμπύλης. |
| y3 | float | Η συντεταγμένη y του δεύτερου σημείου ελέγχου της καμπύλης. |
| x4 | float | Η συντεταγμένη x του τελικού σημείου της καμπύλης. |
| y4 | float | Η συντεταγμένη y του τελικού σημείου της καμπύλης. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών  PointF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας από δομές  PointF  που αντιπροσωπεύουν τα σημεία που καθορίζουν την καμπύλη. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών  Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας από δομές  Point  που αντιπροσωπεύουν τα σημεία που καθορίζουν την καμπύλη. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Σχεδιάζει μια κλειστή καρδινάλια spline που ορίζεται από έναν πίνακα δομών  PointF . Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και  FillMode.Alternate  λειτουργία γεμίσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας από δομές  PointF  που ορίζουν τη spline. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Σχεδιάζει μια κλειστή καρδινάλια spline που ορίζεται από έναν πίνακα δομών  PointF  χρησιμοποιώντας καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη  FillMode.Alternate  λειτουργία γεμίσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας από δομές  PointF  που ορίζουν τη spline. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Σχεδιάζει μια κλειστή καρδινάλια spline που ορίζεται από έναν πίνακα δομών  Point . Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και  FillMode.Alternate  λειτουργία γεμίσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας από δομές  Point  που ορίζουν τη spline. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Σχεδιάζει μια κλειστή καρδινάλια spline που ορίζεται από έναν πίνακα δομών  Point  χρησιμοποιώντας καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη  FillMode.Alternate  λειτουργία γεμίσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας από δομές  Point  που ορίζουν τη spline. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Σχεδιάζει μια καρδινάλια spline μέσω ενός καθορισμένου πίνακα δομών  PointF . Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας από δομές  PointF  που ορίζουν τη spline. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  PointF  χρησιμοποιώντας μια καθορισμένη τάση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας από δομές  PointF  που αντιπροσωπεύουν τα σημεία που ορίζουν την καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Σχεδιάζει μια καρδινάλια spline μέσω ενός καθορισμένου πίνακα δομών  PointF . Η σχεδίαση αρχίζει με μετατόπιση από την αρχή του πίνακα. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας από δομές  PointF  που ορίζουν τη spline. |
| μετατόπιση | int | Μετατόπιση από το πρώτο στοιχείο στον πίνακα της παραμέτρου  points  προς το αρχικό σημείο στην καμπύλη. |
| numberOfSegments | int | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Σχεδιάζει μια καρδινάλια spline μέσω ενός καθορισμένου πίνακα δομών  PointF  χρησιμοποιώντας καθορισμένη τάση. Η σχεδίαση αρχίζει με μετατόπιση από την αρχή του πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας από δομές  PointF  που ορίζουν τη spline. |
| μετατόπιση | int | Μετατόπιση από το πρώτο στοιχείο στον πίνακα της παραμέτρου  points  προς το αρχικό σημείο στην καμπύλη. |
| numberOfSegments | int | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας από δομές  Point  που ορίζουν τη spline. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  Point  χρησιμοποιώντας μια καθορισμένη τάση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας από δομές  Point  που ορίζουν τη spline. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Σχεδιάζει μια καρδιακή καμπύλη μέσω ενός καθορισμένου πίνακα δομών  Point  χρησιμοποιώντας μια καθορισμένη τάση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας από δομές  Point  που ορίζουν τη spline. |
| μετατόπιση | int | Μετατόπιση από το πρώτο στοιχείο στον πίνακα της παραμέτρου  points  προς το αρχικό σημείο στην καμπύλη. |
| numberOfSegments | int | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Σχεδιάζει μια έλλειψη που καθορίζεται από μια περιβάλλουσα δομή  Rectangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το στυλ της έλλειψης. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Δομή Rectangle  που ορίζει τα όρια της έλλειψης. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα  RectangleF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το στυλ της έλλειψης. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Δομή RectangleF  που ορίζει τα όρια της έλλειψης. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα ορθογώνια που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το στυλ της έλλειψης. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| πλάτος | float | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| ύψος | float | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Σχεδιάζει μια έλλειψη που ορίζεται από μια περιβάλλουσα ορθογώνια που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Στυλό  που καθορίζει το χρώμα, το πλάτος και το στυλ της έλλειψης. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| πλάτος | int | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| ύψος | int | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Σχεδιάζει την καθορισμένη  Image , χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην καθορισμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| point | [Point](../../com.aspose.psd/point) | Δομή Point που αντιπροσωπεύει τη θέση της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Σχεδιάζει την καθορισμένη  Image , χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην καθορισμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| point | [PointF](../../com.aspose.psd/pointf) | Δομή PointF που αντιπροσωπεύει την επάνω αριστερή γωνία της σχεδιασμένης εικόνας. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς σχεδίαση. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας τριών δομών PointF που ορίζουν παραλληλόγραμμο. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς σχεδίαση. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας τριών δομών PointF που ορίζουν παραλληλόγραμμο. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Το πηγαίο ορθογώνιο. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς σχεδίαση. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας τριών δομών PointF που ορίζουν παραλληλόγραμμο. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Το πηγαίο ορθογώνιο. |
| srcUnit | int | Οι μονάδες μέτρησης. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς σχεδίαση. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας τριών δομών PointF που ορίζουν παραλληλόγραμμο. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Το πηγαίο ορθογώνιο. |
| srcUnit | int | Οι μονάδες μέτρησης. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς σχεδίαση. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Πίνακας τριών δομών PointF που ορίζουν παραλληλόγραμμο. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς σχεδίαση. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Πίνακας τριών δομών PointF που ορίζουν παραλληλόγραμμο. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Το πηγαίο ορθογώνιο. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς σχεδίαση. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Πίνακας τριών δομών PointF που ορίζουν παραλληλόγραμμο. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Το πηγαίο ορθογώνιο. |
| srcUnit | int | Οι μονάδες μέτρησης. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης  image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Η εικόνα προς σχεδίαση. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Πίνακας τριών δομών PointF που ορίζουν παραλληλόγραμμο. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Το πηγαίο ορθογώνιο. |
| srcUnit | int | Οι μονάδες μέτρησης. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Δομή Rectangle που καθορίζει τη θέση και το μέγεθος της σχεδιασμένης εικόνας. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Το rect προέλευσης. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Το rect προορισμού. |
| graphicsUnit | int | Η μονάδα γραφικών. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Το rect προέλευσης. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Το rect προορισμού. |
| graphicsUnit | int | Η μονάδα γραφικών. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο προορισμού. |
| graphicsUnit | int | Η μονάδα γραφικών. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο προορισμού. |
| graphicsUnit | int | Η μονάδα γραφικών. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Δομή RectangleF που καθορίζει τη θέση και το μέγεθος της σχεδιασμένης εικόνας. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Το rect προέλευσης. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Το rect προορισμού. |
| graphicsUnit | int | Η μονάδα γραφικών. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Το πηγαίο ορθογώνιο. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Το ορθογώνιο προορισμού. |
| graphicsUnit | int | Η μονάδα γραφικών προς χρήση. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας προς χρήση. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Το ορθογώνιο προορισμού. |
| graphicsUnit | int | Η μονάδα γραφικών. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Το ορθογώνιο προορισμού στο οποίο θα σχεδιαστεί. |
| graphicsUnit | int | Η μονάδα γραφικών. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Σχεδιάζει την καθορισμένη  Image , χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην καθορισμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| πλάτος | float | Πλάτος της σχεδιασμένης εικόνας. |
| ύψος | float | Ύψος της σχεδιασμένης εικόνας. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Σχεδιάζει την καθορισμένη εικόνα, χρησιμοποιώντας το αρχικό φυσικό της μέγεθος, στην θέση που καθορίζεται από ένα ζεύγος συντεταγμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Σχεδιάζει την καθορισμένη  Image  στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| πλάτος | int | Πλάτος της σχεδιασμένης εικόνας. |
| ύψος | int | Ύψος της σχεδιασμένης εικόνας. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| point | [Point](../../com.aspose.psd/point) | Δομή Point που καθορίζει την επάνω αριστερή γωνία της σχεδιασμένης εικόνας. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle που καθορίζει την επάνω αριστερή γωνία της σχεδιασμένης εικόνας. Οι ιδιότητες X και Y του rectangle καθορίζουν την επάνω αριστερή γωνία. Οι ιδιότητες Width και Height αγνοούνται. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Σχεδιάζει την καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος στην θέση που καθορίζεται από ένα ζεύγος συντεταγμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| πλάτος | int | Η παράμετρος δεν χρησιμοποιείται. |
| ύψος | int | Η παράμετρος δεν χρησιμοποιείται. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Σχεδιάζει την καθορισμένη εικόνα χωρίς κλιμάκωση και την περικόπτει, εάν είναι απαραίτητο, ώστε να ταιριάζει στο καθορισμένο ορθογώνιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Το Rectangle στο οποίο θα σχεδιαστεί η εικόνα. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Σχεδιάζει μια γραμμή που συνδέει δύο δομές  Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ της γραμμής. |
| point1 | [Point](../../com.aspose.psd/point) | Δομή Point που αντιπροσωπεύει το πρώτο σημείο για σύνδεση. |
| point2 | [Point](../../com.aspose.psd/point) | Δομή Point που αντιπροσωπεύει το δεύτερο σημείο για σύνδεση. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Σχεδιάζει μια γραμμή που συνδέει δύο δομές  PointF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ της γραμμής. |
| point1 | [PointF](../../com.aspose.psd/pointf) | Δομή PointF που αντιπροσωπεύει το πρώτο σημείο για σύνδεση. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Δομή PointF που αντιπροσωπεύει το δεύτερο σημείο για σύνδεση. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ της γραμμής. |
| x1 | float | Η συντεταγμένη x του πρώτου σημείου. |
| y1 | float | Η συντεταγμένη y του πρώτου σημείου. |
| x2 | float | Η συντεταγμένη x του δεύτερου σημείου. |
| y2 | float | Η συντεταγμένη y του δεύτερου σημείου. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ της γραμμής. |
| x1 | int | Η συντεταγμένη x του πρώτου σημείου. |
| y1 | int | Η συντεταγμένη y του πρώτου σημείου. |
| x2 | int | Η συντεταγμένη x του δεύτερου σημείου. |
| y2 | int | Η συντεταγμένη y του δεύτερου σημείου. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών  PointF .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ των τμημάτων της γραμμής. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας δομών PointF που αντιπροσωπεύουν τα σημεία για σύνδεση. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών  Point  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ των τμημάτων της γραμμής. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας δομών Point που αντιπροσωπεύουν τα σημεία για σύνδεση. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Σχεδιάζει ένα  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen που καθορίζει το χρώμα, το πλάτος και το στυλ της διαδρομής. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath για σχεδίαση. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή  Rectangle  και δύο ακτινικές γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του σχήματος πίτας. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Δομή Rectangle που αντιπροσωπεύει το περιοριστικό ορθογώνιο που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| startAngle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x έως την πρώτη πλευρά του σχήματος πίτας. |
| sweepAngle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από την παράμετρο startAngle έως τη δεύτερη πλευρά του σχήματος πίτας. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή  RectangleF  και δύο ακτινικές γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του σχήματος πίτας. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Δομή RectangleF που αντιπροσωπεύει το περιοριστικό ορθογώνιο που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| startAngle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x έως την πρώτη πλευρά του σχήματος πίτας. |
| sweepAngle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από την παράμετρο startAngle έως τη δεύτερη πλευρά του σχήματος πίτας. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του σχήματος πίτας. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| πλάτος | float | Το πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| ύψος | float | Το ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| startAngle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x έως την πρώτη πλευρά του σχήματος πίτας. |
| sweepAngle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από την παράμετρο startAngle έως τη δεύτερη πλευρά του σχήματος πίτας. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του σχήματος πίτας. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| πλάτος | int | Το πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| ύψος | int | Το ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| startAngle | int | Γωνία μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x έως την πρώτη πλευρά του σχήματος πίτας. |
| sweepAngle | int | Γωνία μετρημένη σε μοίρες δεξιόστροφα από την παράμετρο startAngle έως τη δεύτερη πλευρά του σχήματος πίτας. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών  PointF  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Το Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του πολύγωνου. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας των δομών PointF που αντιπροσωπεύουν τις κορυφές του πολύγωνου. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών  Point  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Το Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του πολύγωνου. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας των δομών Point που αντιπροσωπεύουν τις κορυφές του πολύγωνου. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή  Rectangle  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ένα Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του ορθογωνίου. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Μια δομή Rectangle που αντιπροσωπεύει το ορθογώνιο προς σχεδίαση. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή  RectangleF  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ένα Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του ορθογωνίου. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Μια δομή RectangleF που αντιπροσωπεύει το ορθογώνιο προς σχεδίαση. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ένα Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του ορθογωνίου. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου προς σχεδίαση. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου προς σχεδίαση. |
| πλάτος | float | Το πλάτος του ορθογωνίου προς σχεδίαση. |
| ύψος | float | Το ύψος του ορθογωνίου προς σχεδίαση. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Το Pen που καθορίζει το χρώμα, το πλάτος και το στυλ του ορθογωνίου. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου προς σχεδίαση. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου προς σχεδίαση. |
| πλάτος | int | Το πλάτος του ορθογωνίου προς σχεδίαση. |
| ύψος | int | Το ύψος του ορθογωνίου προς σχεδίαση. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές  RectangleF  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Το Pen που καθορίζει το χρώμα, το πλάτος και το στυλ των περιγραμμάτων των ορθογωνίων. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Πίνακας των δομών RectangleF που αντιπροσωπεύουν τα ορθογώνια προς σχεδίαση. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές  Rectangle  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Το Pen που καθορίζει το χρώμα, το πλάτος και το στυλ των περιγραμμάτων των ορθογωνίων. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Πίνακας των δομών Rectangle που αντιπροσωπεύουν τα ορθογώνια προς σχεδίαση. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | java.lang.String | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](../../com.aspose.psd/font) | Το com.aspose.psd.Font που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](../../com.aspose.psd/brush) | Το com.aspose.psd.Brush που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| point | [PointF](../../com.aspose.psd/pointf) | Η δομή com.aspose.psd.PointF που καθορίζει την επάνω αριστερή γωνία του σχεδιασμένου κειμένου. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font  χρησιμοποιώντας τις ιδιότητες μορφοποίησης του καθορισμένου  com.aspose.psd.stringFormat .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | java.lang.String | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](../../com.aspose.psd/font) | Το com.aspose.psd.Font που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](../../com.aspose.psd/brush) | Το com.aspose.psd.Brush που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| point | [PointF](../../com.aspose.psd/pointf) | Η δομή com.aspose.psd.PointF που καθορίζει την επάνω αριστερή γωνία του σχεδιασμένου κειμένου. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Το com.aspose.psd.StringFormat που καθορίζει τις ιδιότητες μορφοποίησης, όπως το διάστιχο και την ευθυγράμμιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | java.lang.String | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](../../com.aspose.psd/font) | Το com.aspose.psd.Font που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](../../com.aspose.psd/brush) | Το com.aspose.psd.Brush που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font  χρησιμοποιώντας τις ιδιότητες μορφοποίησης του καθορισμένου  com.aspose.psd.stringFormat .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | java.lang.String | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](../../com.aspose.psd/font) | Το com.aspose.psd.Font που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](../../com.aspose.psd/brush) | Το com.aspose.psd.Brush που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Το com.aspose.psd.StringFormat που καθορίζει τις ιδιότητες μορφοποίησης, όπως το διάστιχο και την ευθυγράμμιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | java.lang.String | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](../../com.aspose.psd/font) | Το com.aspose.psd.Font που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](../../com.aspose.psd/brush) | Το com.aspose.psd.Brush που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font  χρησιμοποιώντας τις ιδιότητες μορφοποίησης του καθορισμένου  com.aspose.psd.stringFormat .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | java.lang.String | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](../../com.aspose.psd/font) | Το com.aspose.psd.Font που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](../../com.aspose.psd/brush) | Το com.aspose.psd.Brush που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Το com.aspose.psd.StringFormat που καθορίζει τις ιδιότητες μορφοποίησης, όπως το διάστιχο και την ευθυγράμμιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου με τρόπο συμβατό με το Adobe στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font  χρησιμοποιώντας τις ιδιότητες μορφοποίησης του καθορισμένου  com.aspose.psd.stringFormat .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | java.lang.String | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](../../com.aspose.psd/font) | Το com.aspose.psd.Font που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](../../com.aspose.psd/brush) | Το com.aspose.psd.Brush που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Το com.aspose.psd.StringFormat που καθορίζει τις ιδιότητες μορφοποίησης, όπως το διάστιχο και την ευθυγράμμιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου με τρόπο συμβατό με το Adobe στην καθορισμένη θέση με τα καθορισμένα αντικείμενα  com.aspose.psd.Brush  και  com.aspose.psd.Font .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | java.lang.String | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](../../com.aspose.psd/font) | Το com.aspose.psd.Font που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](../../com.aspose.psd/brush) | Το com.aspose.psd.Brush που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Ολοκληρώνει την προσωρινή αποθήκευση των λειτουργιών γραφικών που ξεκίνησαν μετά την κλήση του BeginUpdate. Οι προηγούμενες λειτουργίες γραφικών θα εφαρμοστούν αμέσως κατά την κλήση αυτής της μεθόδου.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.PointF . Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5 και λειτουργία γεμίσματος  FillMode.Alternate .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας δομών  com.aspose.psd.PointF  που ορίζουν το spline. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.PointF  χρησιμοποιώντας την καθορισμένη λειτουργία γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας δομών  com.aspose.psd.PointF  που ορίζουν το spline. |
| λειτουργία γεμίσματος | int | Μέλος της απαρίθμησης  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζεται η καμπύλη. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Γεμίζει το εσωτερικό ενός κλειστού καρδινάλου καμπύλου spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.PointF  χρησιμοποιώντας τη καθορισμένη λειτουργία γεμίσματος και τάση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Ένα  com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Πίνακας δομών  com.aspose.psd.PointF  που ορίζουν το spline. |
| λειτουργία γεμίσματος | int | Μέλος της απαρίθμησης  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζεται η καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.Point . Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5 και λειτουργία γεμίσματος  FillMode.Alternate .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας δομών  com.aspose.psd.Point  που ορίζουν το spline. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Γεμίζει το εσωτερικό μιας κλειστής καρδινάλιας καμπύλης spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.Point  χρησιμοποιώντας την καθορισμένη λειτουργία γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0,5.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας δομών  com.aspose.psd.Point  που ορίζουν το spline. |
| λειτουργία γεμίσματος | int | Μέλος της απαρίθμησης  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζεται η καμπύλη. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Γεμίζει το εσωτερικό ενός κλειστού καρδινάλου καμπύλου spline που ορίζεται από έναν πίνακα δομών  com.aspose.psd.Point  χρησιμοποιώντας τη καθορισμένη λειτουργία γεμίσματος και τάση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point\[\]](../../com.aspose.psd/point) | Πίνακας δομών  com.aspose.psd.Point  που ορίζουν το spline. |
| λειτουργία γεμίσματος | int | Μέλος της απαρίθμησης  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζεται η καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από μια  com.aspose.psd.Rectangle  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle  δομή που αντιπροσωπεύει το περιοριστικό ορθογώνιο που ορίζει την έλλειψη. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από μια  com.aspose.psd.RectangleF  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  δομή που αντιπροσωπεύει το περιοριστικό ορθογώνιο που ορίζει την έλλειψη. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, και ένα ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| πλάτος | float | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| ύψος | float | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιοριστικό ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, και ένα ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| πλάτος | int | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| ύψος | int | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Γεμίζει το εσωτερικό ενός  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath  που αντιπροσωπεύει τη διαδρομή προς γέμισμα. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από μια  com.aspose.psd.RectangleF  δομή και δύο ακτινικές γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle  δομή που αντιπροσωπεύει το περιοριστικό ορθογώνιο που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| startAngle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα x έως την πρώτη πλευρά του τμήματος πίτας. |
| sweepAngle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από την παράμετρο  startAngle  έως τη δεύτερη πλευρά του τμήματος πίτας. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από μια  com.aspose.psd.RectangleF  δομή και δύο ακτινικές γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  δομή που αντιπροσωπεύει το περιοριστικό ορθογώνιο που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| startAngle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα x έως την πρώτη πλευρά του τμήματος πίτας. |
| sweepAngle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από την παράμετρο  startAngle  έως τη δεύτερη πλευρά του τμήματος πίτας. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| πλάτος | float | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| ύψος | float | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| startAngle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα x έως την πρώτη πλευρά του τμήματος πίτας. |
| sweepAngle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από την παράμετρο  startAngle  έως τη δεύτερη πλευρά του τμήματος πίτας. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| πλάτος | int | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| ύψος | int | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| startAngle | int | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα x έως την πρώτη πλευρά του τμήματος πίτας. |
| sweepAngle | int | Γωνία σε μοίρες που μετριέται δεξιόστροφα από την παράμετρο  startAngle  έως τη δεύτερη πλευρά του τμήματος πίτας. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από  com.aspose.psd.PointF  δομές και  FillMode.Alternate .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Σειρά από δομές  com.aspose.psd.PointF  που αντιπροσωπεύουν τις κορυφές του πολυγώνου προς γέμισμα. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από  com.aspose.psd.PointF  δομές χρησιμοποιώντας την καθορισμένη λειτουργία γεμίσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Σειρά από δομές  com.aspose.psd.PointF  που αντιπροσωπεύουν τις κορυφές του πολυγώνου προς γέμισμα. |
| fillMode | int | Μέλος της απαρίθμησης  com.aspose.psd.FillMode  που καθορίζει το στυλ του γεμίσματος. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από  com.aspose.psd.Point  δομές και  FillMode.Alternate .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point\[\]](../../com.aspose.psd/point) | Σειρά από δομές  com.aspose.psd.Point  που αντιπροσωπεύουν τις κορυφές του πολυγώνου προς γέμισμα. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων που καθορίζονται από  com.aspose.psd.Point  δομές χρησιμοποιώντας την καθορισμένη λειτουργία γεμίσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point\[\]](../../com.aspose.psd/point) | Σειρά από δομές  com.aspose.psd.Point  που αντιπροσωπεύουν τις κορυφές του πολυγώνου προς γέμισμα. |
| fillMode | int | Μέλος της απαρίθμησης  com.aspose.psd.FillMode  που καθορίζει το στυλ του γεμίσματος. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια  Rectangle  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Πινέλο  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Δομή Rectangle  που αντιπροσωπεύει το ορθογώνιο προς γέμισμα. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια  RectangleF  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Πινέλο  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Δομή RectangleF  που αντιπροσωπεύει το ορθογώνιο προς γέμισμα. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Πινέλο  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | float | Η συντεταγμένη x του επάνω αριστερού γωνιακού σημείου του ορθογωνίου προς γέμισμα. |
| y | float | Η συντεταγμένη y του επάνω αριστερού γωνιακού σημείου του ορθογωνίου προς γέμισμα. |
| πλάτος | float | Πλάτος του ορθογωνίου προς γέμισμα. |
| ύψος | float | Ύψος του ορθογωνίου προς γέμισμα. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Πινέλο  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | int | Η συντεταγμένη x του επάνω αριστερού γωνιακού σημείου του ορθογωνίου προς γέμισμα. |
| y | int | Η συντεταγμένη y του επάνω αριστερού γωνιακού σημείου του ορθογωνίου προς γέμισμα. |
| πλάτος | int | Πλάτος του ορθογωνίου προς γέμισμα. |
| ύψος | int | Ύψος του ορθογωνίου προς γέμισμα. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από  RectangleF  δομές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Πινέλο  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Σειρά από δομές  Rectangle  που αντιπροσωπεύουν τα ορθογώνια προς γέμισμα. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από  Rectangle  δομές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Πινέλο  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Σειρά από δομές  Rectangle  που αντιπροσωπεύουν τα ορθογώνια προς γέμισμα. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Γεμίζει το εσωτερικό ενός  com.aspose.psd.region .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region  που αντιπροσωπεύει την περιοχή προς γέμισμα. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


Λαμβάνει ή ορίζει την περιοχή αποκοπής.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Λαμβάνει ή ορίζει την ποιότητα σύνθεσης.

**Returns:**
int - Η ποιότητα σύνθεσης.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Λαμβάνει την οριζόντια ανάλυση αυτού του com.aspose.psd.graphics.

**Returns:**
float - Η τιμή, σε κουκκίδες ανά ίντσα, για την οριζόντια ανάλυση που υποστηρίζεται από αυτό το com.aspose.psd.graphics.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Λαμβάνει την κάθετη ανάλυση αυτού του com.aspose.psd.graphics.

**Returns:**
float - Η τιμή, σε κουκκίδες ανά ίντσα, για την κάθετη ανάλυση που υποστηρίζεται από αυτό το com.aspose.psd.graphics.
### getImage() {#getImage--}
```
public Image getImage()
```


Λαμβάνει την εικόνα.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Λαμβάνει ή ορίζει τη λειτουργία παρεμβολής.

**Returns:**
int - Η λειτουργία παρεμβολής.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Λαμβάνει ή ορίζει την κλίμακα μεταξύ των μονάδων κόσμου και των μονάδων σελίδας για αυτό το com.aspose.psd.graphics.

**Returns:**
float - Η κλίμακα μεταξύ μονάδων κόσμου και μονάδων σελίδας για αυτό το com.aspose.psd.graphics.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το com.aspose.psd.graphics.

**Returns:**
int - Η μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το com.aspose.psd.graphics.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Λαμβάνει ή ορίζει τις επιλογές εικόνας, που χρησιμοποιούνται για τη δημιουργία ζωγραφίσιμων διανυσματικών εικόνων για σχεδίαση.

Τιμή: Οι επιλογές εικόνας, που χρησιμοποιούνται για τη δημιουργία ζωγραφίσιμων διανυσματικών εικόνων για σχεδίαση.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Λαμβάνει ή ορίζει τη λειτουργία εξομάλυνσης.

**Returns:**
int - Η λειτουργία εξομάλυνσης.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Λαμβάνει ή ορίζει τη συμβουλή απόδοσης κειμένου.

**Returns:**
int - Η υπόδειξη απόδοσης κειμένου.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Λαμβάνει ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού κόσμου για αυτό το  com.aspose.psd.graphics .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν τα γραφικά βρίσκονται στην κατάσταση κλήσης BeginUpdate.

**Returns:**
boolean -  True  εάν το graphics βρίσκεται σε κατάσταση κλήσης BeginUpdate· διαφορετικά,  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Μετρά τη συμβολοσειρά χρησιμοποιώντας την κλάση [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | Η γραμματοσειρά. |
| κείμενο | java.lang.String | Το κείμενο. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Μετρά τη συμβολοσειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Η γραμματοσειρά. |
|  | κείμενο | java.lang.String | Το κείμενο. |

--------------------

Το αποτέλεσμα GDI είναι σχεδόν πάντα μη έγκυρο για πλάγιες (Italic) και συχνά μη έγκυρο για έντονες (Bold) μορφές. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Μετρά τη συγκεκριμένη συμβολοσειρά κειμένου με τα καθορισμένα παραμέτρους

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Το κείμενο για μέτρηση. |
| font | [Font](../../com.aspose.psd/font) | Η γραμματοσειρά για μέτρηση. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | Η περιοχή διάταξης. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Η μορφή συμβολοσειράς. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Η λήψη της ιδιωτικής κρυφής μνήμης γραμματοσειράς. |
| useMagicNumbersForStyles | boolean | αν οριστεί σε  true  [χρησιμοποιήστε μαγικούς αριθμούς για στυλ]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Πολλαπλασιάζει το  com.aspose.psd.Matrix  που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του  com.aspose.psd.Graphics  με το καθορισμένο  com.aspose.psd.Matrix  προσθέτοντας στην αρχή το καθορισμένο  com.aspose.psd.matrix .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η  com.aspose.psd.Matrix  με την οποία πολλαπλασιάζεται ο γεωμετρικός μετασχηματισμός. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Πολλαπλασιάζει το  com.aspose.psd.Matrix  που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του  com.aspose.psd.Graphics  με το καθορισμένο  com.aspose.psd.Matrix  με τη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η  com.aspose.psd.Matrix  με την οποία πολλαπλασιάζεται ο γεωμετρικός μετασχηματισμός. |
| order | int | Ένα  com.aspose.psd.MatrixOrder  που καθορίζει σε ποια σειρά να πολλαπλασιαστούν οι δύο πίνακες. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Επαναφέρει την ιδιότητα  com.aspose.psd.graphics.Transform  στην ταυτότητα.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Περιστρέφει τη τοπική γεωμετρική μετατροπή κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής. |
| order | int | Ένα  com.aspose.psd.MatrixOrder  που καθορίζει αν θα προσαρτηθεί ή θα προταθεί ο πίνακας περιστροφής. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Κλιμακώνει τη τοπική γεωμετρική μετατροπή με τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει στην αρχή τον πίνακα κλιμάκωσης στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |
| order | int | Ένα  com.aspose.psd.MatrixOrder  που καθορίζει αν θα προσαρτηθεί ή θα προταθεί ο πίνακας κλιμάκωσης. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Λαμβάνει ή ορίζει την περιοχή αποκοπής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | Η περιοχή αποκοπής. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Λαμβάνει ή ορίζει την ποιότητα σύνθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η ποιότητα σύνθεσης. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Λαμβάνει ή ορίζει τη λειτουργία παρεμβολής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η λειτουργία παρεμβολής. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Λαμβάνει ή ορίζει την κλίμακα μεταξύ των μονάδων κόσμου και των μονάδων σελίδας για αυτό το com.aspose.psd.graphics.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η κλιμάκωση μεταξύ μονάδων κόσμου και μονάδων σελίδας για αυτό το com.aspose.psd.graphics. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Λαμβάνει ή ορίζει τη μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το com.aspose.psd.graphics.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το com.aspose.psd.graphics. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Λαμβάνει ή ορίζει τις επιλογές εικόνας, που χρησιμοποιούνται για τη δημιουργία ζωγραφίσιμων διανυσματικών εικόνων για σχεδίαση.

Τιμή: Οι επιλογές εικόνας, που χρησιμοποιούνται για τη δημιουργία ζωγραφίσιμων διανυσματικών εικόνων για σχεδίαση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Λαμβάνει ή ορίζει τη λειτουργία εξομάλυνσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η λειτουργία εξομάλυνσης. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Λαμβάνει ή ορίζει τη συμβουλή απόδοσης κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η υπόδειξη απόδοσης κειμένου. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Λαμβάνει ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού κόσμου για αυτό το  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Ένα αντίγραφο του  com.aspose.psd.Matrix  που αντιπροσωπεύει τον γεωμετρικό μετασχηματισμό κόσμου για αυτό το  com.aspose.psd.graphics . |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Μεταφράζει τη τοπική γεωμετρική μετατροπή με τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει στην αρχή τη μετάφραση στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις με τη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |
| order | int | Η σειρά (προσθήκη στην αρχή ή προσθήκη στο τέλος) με την οποία εφαρμόζεται η μετάφραση. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

