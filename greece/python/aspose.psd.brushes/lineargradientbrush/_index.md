---
title: "Κλάση LinearGradientBrush"
type: docs
weight: 20
url: /el/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με προεπιλεγμένες παραμέτρους.<br/>            Το αρχικό χρώμα είναι μαύρο, το τελικό χρώμα είναι λευκό, η γωνία είναι 45 μοίρες και το ορθογώνιο βρίσκεται στο (0,0) με μέγεθος (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με τα καθορισμένα σημεία και χρώματα. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με τα καθορισμένα σημεία και χρώματα. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) βασισμένο σε ένα ορθογώνιο, τα αρχικά και τελικά χρώματα, και μια γωνία προσανατολισμού. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) βασισμένο σε ένα ορθογώνιο, τα αρχικά και τελικά χρώματα, και μια γωνία προσανατολισμού. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) βασισμένο σε ένα ορθογώνιο, τα αρχικά και τελικά χρώματα, και μια γωνία προσανατολισμού. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) βασισμένο σε ένα ορθογώνιο, τα αρχικά και τελικά χρώματα, και μια γωνία προσανατολισμού. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| γωνία | float | r/w | Λαμβάνει ή ορίζει τη γωνία του gradient. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Λαμβάνει ή ορίζει ένα [Blend](/psd/python-net/aspose.psd/blend/) που καθορίζει θέσεις και παράγοντες που ορίζουν μια προσαρμοσμένη εσθίαση για τη διαβάθμιση. |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει το τελικό χρώμα της διαβάθμισης. |
| gamma_correction | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν η διόρθωση γάμμα είναι ενεργοποιημένη για αυτό το [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Λαμβάνει ή ορίζει ένα [ColorBlend](/psd/python-net/aspose.psd/colorblend/) που ορίζει ένα πολυχρωματικό γραμμικό gradient. |
| is_angle_scalable | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) αλλάζει κατά τη διάρκεια των μετασχηματισμών με αυτό το [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Λαμβάνει μια τιμή που υποδεικνύει αν οι μετασχηματισμοί άλλαξαν με κάποιον τρόπο. Για παράδειγμα ορίζοντας τη μήτρα μετασχηματισμού ή<br/>            καλώντας οποιαδήποτε από τις μεθόδους που τροποποιούν τη μήτρα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με παλαιότερες εκδόσεις του GDI+. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει τα αρχικά και τελικά χρώματα της διαβάθμισης. |
| opacity | float | r/w | Λαμβάνει ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Λαμβάνει ή ορίζει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία του gradient. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει το αρχικό χρώμα της διαβάθμισης. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Λαμβάνει ή ορίζει ένα αντίγραφο του [Matrix](/psd/python-net/aspose.psd/matrix/) που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Λαμβάνει ή ορίζει μια απαρίθμηση του [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Πολλαπλασιάζει τη [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/) προσθέτοντας στην αρχή την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Πολλαπλασιάζει τη [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/) σε καθορισμένη σειρά. |
| reset_transform() | Επαναφέρει την ιδιότητα [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) σε ταυτοτική. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με την καθορισμένη σειρά. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Δημιουργεί μια γραμμική διαβάθμιση με κεντρικό χρώμα και γραμμική εσθίαση προς ένα ενιαίο χρώμα και στις δύο άκρες. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Δημιουργεί μια γραμμική διαβάθμιση με κεντρικό χρώμα και γραμμική εσθίαση προς ένα ενιαίο χρώμα και στις δύο άκρες. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Δημιουργεί εσθίαση διαβάθμισης βασισμένη σε καμπύλη σε σχήμα καμπάνας. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Δημιουργεί εσθίαση διαβάθμισης βασισμένη σε καμπύλη σε σχήμα καμπάνας. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με προεπιλεγμένες παραμέτρους.<br/>            Το αρχικό χρώμα είναι μαύρο, το τελικό χρώμα είναι λευκό, η γωνία είναι 45 μοίρες και το ορθογώνιο βρίσκεται στο (0,0) με μέγεθος (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με τα καθορισμένα σημεία και χρώματα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Μια δομή [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει το αρχικό σημείο του γραμμικού διαβάθμισης. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Μια δομή [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει το τελικό σημείο του γραμμικού διαβάθμισης. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το αρχικό χρώμα της γραμμικής διαβάθμισης. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το τελικό χρώμα της γραμμικής διαβάθμισης. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με τα καθορισμένα σημεία και χρώματα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Μια δομή [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει το αρχικό σημείο του γραμμικού διαβάθμισης. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Μια δομή [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει το τελικό σημείο του γραμμικού διαβάθμισης. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το αρχικό χρώμα της γραμμικής διαβάθμισης. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το τελικό χρώμα της γραμμικής διαβάθμισης. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) βασισμένο σε ένα ορθογώνιο, τα αρχικά και τελικά χρώματα, και μια γωνία προσανατολισμού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που καθορίζει τα όρια του γραμμικού διαβάθμισης. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το αρχικό χρώμα για τη διαβάθμιση. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| γωνία | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού του διαβάθμισης. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) βασισμένο σε ένα ορθογώνιο, τα αρχικά και τελικά χρώματα, και μια γωνία προσανατολισμού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που καθορίζει τα όρια του γραμμικού διαβάθμισης. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το αρχικό χρώμα για τη διαβάθμιση. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| γωνία | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού του διαβάθμισης. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) βασισμένο σε ένα ορθογώνιο, τα αρχικά και τελικά χρώματα, και μια γωνία προσανατολισμού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που καθορίζει τα όρια του γραμμικού διαβάθμισης. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το αρχικό χρώμα για τη διαβάθμιση. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| γωνία | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού του διαβάθμισης. |
| is_angle_scalable | bool | εάν οριστεί σε <c>true</c> η γωνία αλλάζει κατά τις μετασχηματισμούς με αυτό το [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) βασισμένο σε ένα ορθογώνιο, τα αρχικά και τελικά χρώματα, και μια γωνία προσανατολισμού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που καθορίζει τα όρια του γραμμικού διαβάθμισης. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το αρχικό χρώμα για τη διαβάθμιση. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Μια δομή [Color](/psd/python-net/aspose.psd/color/) που αντιπροσωπεύει το τελικό χρώμα για τη διαβάθμιση. |
| γωνία | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού του διαβάθμισης. |
| is_angle_scalable | bool | εάν οριστεί σε <c>true</c> η γωνία αλλάζει κατά τις μετασχηματισμούς με αυτό το [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Ένα νέο [Brush](/psd/python-net/aspose.psd/brush/) που είναι το βαθύ αντίγραφο αυτής της παρουσίας [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Πολλαπλασιάζει τη [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/) προσθέτοντας στην αρχή την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο [Matrix](/psd/python-net/aspose.psd/matrix/) με τον οποίο πολλαπλασιάζεται ο γεωμετρικός μετασχηματισμός. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Πολλαπλασιάζει τη [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) με την καθορισμένη [Matrix](/psd/python-net/aspose.psd/matrix/) σε καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο [Matrix](/psd/python-net/aspose.psd/matrix/) με τον οποίο πολλαπλασιάζεται ο γεωμετρικός μετασχηματισμός. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ένα [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) που καθορίζει με ποια σειρά να πολλαπλασιαστούν οι δύο πίνακες. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γωνία | float | Η γωνία περιστροφής. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γωνία | float | Η γωνία περιστροφής. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ένα [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί ο πίνακας περιστροφής. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με την καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ένα [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί ο πίνακας κλιμάκωσης. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Δημιουργεί μια γραμμική διαβάθμιση με κεντρικό χρώμα και γραμμική εσθίαση προς ένα ενιαίο χρώμα και στις δύο άκρες.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| εστία | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο της διαβάθμισης (το σημείο όπου η διαβάθμιση αποτελείται μόνο από το τελικό χρώμα). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Δημιουργεί μια γραμμική διαβάθμιση με κεντρικό χρώμα και γραμμική εσθίαση προς ένα ενιαίο χρώμα και στις δύο άκρες.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| εστία | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο της διαβάθμισης (το σημείο όπου η διαβάθμιση αποτελείται μόνο από το τελικό χρώμα). |
| scale | float | Μια τιμή από 0 έως 1 που καθορίζει πόσο γρήγορα τα χρώματα μειώνονται από το αρχικό χρώμα προς το <paramref name="focus" /> (τελικό χρώμα) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Δημιουργεί εσθίαση διαβάθμισης βασισμένη σε καμπύλη σε σχήμα καμπάνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| εστία | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο της διαβάθμισης (το σημείο όπου το αρχικό και το τελικό χρώμα αναμειγνύονται εξίσου). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Δημιουργεί εσθίαση διαβάθμισης βασισμένη σε καμπύλη σε σχήμα καμπάνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| εστία | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο της διαβάθμισης (το σημείο όπου η διαβάθμιση αποτελείται μόνο από το τελικό χρώμα). |
| scale | float | Μια τιμή από 0 έως 1 που καθορίζει πόσο γρήγορα τα χρώματα μειώνονται από το <paramref name="focus" />. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στο y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με την καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στο y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Η σειρά (prepend ή append) με την οποία να εφαρμόσετε τη μετάφραση. |

