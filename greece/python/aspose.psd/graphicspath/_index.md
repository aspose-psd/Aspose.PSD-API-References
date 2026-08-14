---
title: "Κλάση GraphicsPath"
type: docs
weight: 1570
url: /el/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Αρχικοποιεί μια νέα παρουσία της κλάσης [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Λαμβάνει ή ορίζει τα όρια του αντικειμένου. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Λαμβάνει τα σχήματα διαδρομής. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Λαμβάνει ή ορίζει μια απαρίθμηση [FillMode](/psd/python-net/aspose.psd/fillmode/) που καθορίζει πώς γεμίζουν τα εσωτερικά των σχημάτων σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Προσθέτει ένα νέο σχήμα. |
| [add_figures(figures)](#add_figures_figures_2) | Προσθέτει νέα σχήματα. |
| [add_path(adding_path)](#add_path_adding_path_3) | Προσθέτει στο τέλος το καθορισμένο [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) σε αυτή τη διαδρομή. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Προσθέτει στο τέλος το καθορισμένο [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) σε αυτή τη διαδρομή. |
| [deep_clone()](#deep_clone__5) | Εκτελεί ένα βαθύ κλώνο αυτής της διαδρομής γραφικών. |
| flatten() | Μετατρέπει κάθε καμπύλη σε αυτή τη διαδρομή σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| [flatten(matrix)](#flatten_matrix_6) | Εφαρμόζει τον καθορισμένο μετασχηματισμό και στη συνέχεια μετατρέπει κάθε καμπύλη σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Μετατρέπει κάθε καμπύλη σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Λαμβάνει τα όρια του αντικειμένου. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Λαμβάνει τα όρια του αντικειμένου. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/) και χρησιμοποιώντας το καθορισμένο [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/) και χρησιμοποιώντας το καθορισμένο [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/) και χρησιμοποιώντας το καθορισμένο [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/) και χρησιμοποιώντας το καθορισμένο [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(point)](#is_visible_point_18) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) στην ορατή περιοχή αποκοπής του καθορισμένου [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) στην ορατή περιοχή αποκοπής του καθορισμένου [Graphics](/psd/python-net/aspose.psd/graphics/). |
| [remove_figure(figure)](#remove_figure_figure_26) | Αφαιρεί ένα σχήμα. |
| [remove_figures(figures)](#remove_figures_figures_27) | Αφαιρεί σχήματα. |
| reset() | Αδειάζει τη διαδρομή γραφικών και ορίζει το [FillMode](/psd/python-net/aspose.psd/fillmode/) σε [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Αντιστρέφει τη σειρά των σχημάτων, μορφών και σημείων σε κάθε μορφή αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [transform(transform)](#transform_transform_28) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | Προσθέτει ένα επιπλέον περίγραμμα στη διαδρομή. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Προσθέτει ένα επιπλέον περίγραμμα στο [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Αντικαθιστά αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) με καμπύλες που περιβάλλουν την περιοχή που γεμίζει όταν αυτή η διαδρομή σχεδιάζεται με το καθορισμένο Pen. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Τα σχήματα για αρχικοποίηση. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Τα σχήματα για αρχικοποίηση. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Η λειτουργία γεμίσματος. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Η λειτουργία γεμίσματος. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Προσθέτει ένα νέο σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Το σχήμα προς προσθήκη. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Προσθέτει νέα σχήματα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Τα σχήματα προς προσθήκη. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Προσθέτει στο τέλος το καθορισμένο [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) σε αυτή τη διαδρομή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) για προσθήκη. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Προσθέτει στο τέλος το καθορισμένο [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) σε αυτή τη διαδρομή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) για προσθήκη. |
| σύνδεση | bool | Μια λογική τιμή που καθορίζει εάν το πρώτο σχήμα στη προστιθέμενη διαδρομή αποτελεί μέρος του τελευταίου σχήματος σε αυτή τη διαδρομή. Μια τιμή true καθορίζει ότι το πρώτο σχήμα στη προστιθέμενη διαδρομή αποτελεί μέρος του τελευταίου σχήματος σε αυτή τη διαδρομή. Μια τιμή false καθορίζει ότι το πρώτο σχήμα στη προστιθέμενη διαδρομή είναι ξεχωριστό από το τελευταίο σχήμα σε αυτή τη διαδρομή. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Εκτελεί ένα βαθύ κλώνο αυτής της διαδρομής γραφικών.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ένα πλήρες αντίγραφο της διαδρομής γραφικών. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Εφαρμόζει τον καθορισμένο μετασχηματισμό και στη συνέχεια μετατρέπει κάθε καμπύλη σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ένας [Matrix](/psd/python-net/aspose.psd/matrix/) με τον οποίο να μετασχηματιστεί αυτή η [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) πριν την εξομάλυνση. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Μετατρέπει κάθε καμπύλη σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ένας [Matrix](/psd/python-net/aspose.psd/matrix/) με τον οποίο να μετασχηματιστεί αυτή η [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) πριν την εξομάλυνση. |
| επίπεδο | float | Καθορίζει το μέγιστο επιτρεπόμενο σφάλμα μεταξύ της καμπύλης και της εξομαλυνμένης προσέγγισής της. Μια τιμή 0,25 είναι η προεπιλογή. Η μείωση της τιμής flatness θα αυξήσει τον αριθμό των τμημάτων γραμμής στην προσέγγιση. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο πίνακας που θα εφαρμοστεί πριν από τα όρια θα υπολογιστεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Τα εκτιμώμενα όρια του αντικειμένου. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο πίνακας που θα εφαρμοστεί πριν από τα όρια θα υπολογιστεί. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το στυλό που θα χρησιμοποιηθεί για το αντικείμενο. Αυτό μπορεί να επηρεάσει το μέγεθος των ορίων του αντικειμένου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Τα εκτιμώμενα όρια του αντικειμένου. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Ένα [PointF](/psd/python-net/aspose.psd/pointf/) που καθορίζει τη θέση για δοκιμή. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτής της [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/); διαφορετικά, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Ένα [PointF](/psd/python-net/aspose.psd/pointf/) που καθορίζει τη θέση για δοκιμή. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτής της [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/); διαφορετικά, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/) και χρησιμοποιώντας το καθορισμένο [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Ένα [PointF](/psd/python-net/aspose.psd/pointf/) που καθορίζει τη θέση για δοκιμή. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) για δοκιμή. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Το [Graphics](/psd/python-net/aspose.psd/graphics/) για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται (κάτω) στο περίγραμμα αυτής της [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όπως σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/); διαφορετικά, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/) και χρησιμοποιώντας το καθορισμένο [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Ένα [PointF](/psd/python-net/aspose.psd/pointf/) που καθορίζει τη θέση για δοκιμή. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) για δοκιμή. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Το [Graphics](/psd/python-net/aspose.psd/graphics/) για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται (κάτω) στο περίγραμμα αυτής της [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όπως σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/); διαφορετικά, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτής της [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/); διαφορετικά, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτής της [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/); διαφορετικά, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/) και χρησιμοποιώντας το καθορισμένο [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) για δοκιμή. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Το [Graphics](/psd/python-net/aspose.psd/graphics/) για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται (κάτω) στο περίγραμμα αυτής της [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όπως σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/); διαφορετικά, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όταν σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/) και χρησιμοποιώντας το καθορισμένο [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) για δοκιμή. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Το [Graphics](/psd/python-net/aspose.psd/graphics/) για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται (κάτω) στο περίγραμμα αυτής της [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) όπως σχεδιάζεται με το καθορισμένο [Pen](/psd/python-net/aspose.psd/pen/); διαφορετικά, false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Ένα [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το σημείο για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); διαφορετικά, false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Ένα [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το σημείο για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); διαφορετικά, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Ένα [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το σημείο για δοκιμή. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Το [Graphics](/psd/python-net/aspose.psd/graphics/) για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό· διαφορετικά, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Ένα [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το σημείο για δοκιμή. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Το [Graphics](/psd/python-net/aspose.psd/graphics/) για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό· διαφορετικά, false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); διαφορετικά, false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); διαφορετικά, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) στην ορατή περιοχή αποκοπής του καθορισμένου [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Το [Graphics](/psd/python-net/aspose.psd/graphics/) για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); διαφορετικά, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) στην ορατή περιοχή αποκοπής του καθορισμένου [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Το [Graphics](/psd/python-net/aspose.psd/graphics/) για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτή τη [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); διαφορετικά, false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Αφαιρεί ένα σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | Το σχήμα για αφαίρεση. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Αφαιρεί σχήματα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Τα σχήματα για αφαίρεση. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο μετασχηματισμός που θα εφαρμοστεί. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ένας πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από <paramref name=\"srcRect\" />. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ένα [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται σε παραλληλόγραμμο που ορίζεται από <paramref name=\"destPoints\" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ένας πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από <paramref name=\"srcRect\" />. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ένα [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται σε παραλληλόγραμμο που ορίζεται από <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ένας [Matrix](/psd/python-net/aspose.psd/matrix/) που καθορίζει γεωμετρικό μετασχηματισμό προς εφαρμογή στη διαδρομή. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ένας πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από <paramref name=\"srcRect\" />. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ένα [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται σε παραλληλόγραμμο που ορίζεται από <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ένας [Matrix](/psd/python-net/aspose.psd/matrix/) που καθορίζει γεωμετρικό μετασχηματισμό προς εφαρμογή στη διαδρομή. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Μια απαρίθμηση [WarpMode](/psd/python-net/aspose.psd/warpmode/) που καθορίζει εάν αυτή η λειτουργία παραμόρφωσης χρησιμοποιεί προοπτική ή διγραμμικό τρόπο. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ένας πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από <paramref name=\"srcRect\" />. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ένα [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται σε παραλληλόγραμμο που ορίζεται από <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ένας [Matrix](/psd/python-net/aspose.psd/matrix/) που καθορίζει γεωμετρικό μετασχηματισμό προς εφαρμογή στη διαδρομή. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Μια απαρίθμηση [WarpMode](/psd/python-net/aspose.psd/warpmode/) που καθορίζει εάν αυτή η λειτουργία παραμόρφωσης χρησιμοποιεί προοπτική ή διγραμμικό τρόπο. |
| flatness | float | Μια τιμή από 0 έως 1 που καθορίζει πόσο επίπεδη είναι η τελική διαδρομή. Για περισσότερες πληροφορίες, δείτε τις μεθόδους [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) . |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Προσθέτει ένα επιπλέον περίγραμμα στη διαδρομή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ένα [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το πλάτος μεταξύ του αρχικού περιγράμματος της διαδρομής και του νέου περιγράμματος που δημιουργεί αυτή η μέθοδος. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Προσθέτει ένα επιπλέον περίγραμμα στο [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ένα [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το πλάτος μεταξύ του αρχικού περιγράμματος της διαδρομής και του νέου περιγράμματος που δημιουργεί αυτή η μέθοδος. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ένας [Matrix](/psd/python-net/aspose.psd/matrix/) που καθορίζει έναν μετασχηματισμό προς εφαρμογή στη διαδρομή πριν το διεύρυνση. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Αντικαθιστά αυτό το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) με καμπύλες που περιβάλλουν την περιοχή που γεμίζει όταν αυτή η διαδρομή σχεδιάζεται με το καθορισμένο Pen.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ένα [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το πλάτος μεταξύ του αρχικού περιγράμματος της διαδρομής και του νέου περιγράμματος που δημιουργεί αυτή η μέθοδος. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ένας [Matrix](/psd/python-net/aspose.psd/matrix/) που καθορίζει έναν μετασχηματισμό προς εφαρμογή στη διαδρομή πριν το διεύρυνση. |
| επίπεδο | float | Μια τιμή που καθορίζει την ομαλότητα των καμπυλών. |

