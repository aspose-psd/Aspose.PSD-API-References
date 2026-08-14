---
title: "Κλάση PathGradientBrush"
type: docs
weight: 50
url: /el/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τη συγκεκριμένη διαδρομή. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τα συγκεκριμένα σημεία. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τα συγκεκριμένα σημεία. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τα συγκεκριμένα σημεία και τη λειτουργία περιτύλιξης. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τα συγκεκριμένα σημεία και τη λειτουργία περιτύλιξης. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Λαμβάνει ή ορίζει ένα [Blend](/psd/python-net/aspose.psd/blend/) που καθορίζει θέσεις και παράγοντες που ορίζουν μια προσαρμοσμένη εσθίαση για τη διαβάθμιση. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει το χρώμα στο κέντρο της διαβάθμισης διαδρομής. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Λαμβάνει ή ορίζει το σημείο εστίασης για την πτώση της διαβάθμισης. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Λαμβάνει τη διαδρομή γραφικών πάνω στην οποία χτίστηκε αυτό το brush. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Λαμβάνει ή ορίζει ένα [ColorBlend](/psd/python-net/aspose.psd/colorblend/) που ορίζει ένα πολυχρωματικό γραμμικό gradient. |
| is_transform_changed | bool | r | Λαμβάνει μια τιμή που υποδεικνύει αν οι μετασχηματισμοί άλλαξαν με κάποιον τρόπο. Για παράδειγμα ορίζοντας τη μήτρα μετασχηματισμού ή<br/>            καλώντας οποιαδήποτε από τις μεθόδους που τροποποιούν τη μήτρα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με παλαιότερες εκδόσεις του GDI+. |
| opacity | float | r/w | Λαμβάνει ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Λαμβάνει τα σημεία διαδρομής πάνω στην οποία χτίστηκε αυτό το brush. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική ελάττωση προς ένα περιβάλλον χρώμα. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική ελάττωση προς κάθε περιβάλλον χρώμα. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Δημιουργεί μια πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από ένα χρώμα στο άλλο βασίζεται σε καμπύλη σχήματος καμπάνας. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Δημιουργεί μια πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από ένα χρώμα στο άλλο βασίζεται σε καμπύλη σχήματος καμπάνας. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τη συγκεκριμένη διαδρομή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) που ορίζει την περιοχή που γεμίζει αυτό το [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τα συγκεκριμένα σημεία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ένας πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τα συγκεκριμένα σημεία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Ένας πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τα συγκεκριμένα σημεία και τη λειτουργία περιτύλιξης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Ένας πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ένα [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που καθορίζει πώς τα γεμίσματα που σχεδιάζονται με αυτό το [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) τοποθετούνται σε πλακίδια. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) με τα συγκεκριμένα σημεία και τη λειτουργία περιτύλιξης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Ένας πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ένα [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που καθορίζει πώς τα γεμίσματα που σχεδιάζονται με αυτό το [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) τοποθετούνται σε πλακίδια. |

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

Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική ελάττωση προς ένα περιβάλλον χρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| εστία | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτινικής από το κέντρο της διαδρομής μέχρι το όριό της, το κεντρικό χρώμα θα είναι στη μέγιστη ένταση του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Δημιουργεί μια διαβάθμιση με κεντρικό χρώμα και γραμμική ελάττωση προς κάθε περιβάλλον χρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| εστία | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτινικής από το κέντρο της διαδρομής μέχρι το όριό της, το κεντρικό χρώμα θα είναι στη μέγιστη ένταση του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |
| scale | float | Μια τιμή από 0 έως 1 που καθορίζει τη μέγιστη ένταση του κεντρικού χρώματος που αναμειγνύεται με το χρώμα του ορίου. Μια τιμή 1 προκαλεί τη μέγιστη δυνατή ένταση του κεντρικού χρώματος, και είναι η προεπιλεγμένη τιμή. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Δημιουργεί μια πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από ένα χρώμα στο άλλο βασίζεται σε καμπύλη σχήματος καμπάνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| εστία | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτινικής από το κέντρο της διαδρομής μέχρι το όριό της, το κεντρικό χρώμα θα είναι στη μέγιστη ένταση του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Δημιουργεί μια πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από ένα χρώμα στο άλλο βασίζεται σε καμπύλη σχήματος καμπάνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| εστία | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτινικής από το κέντρο της διαδρομής μέχρι το όριό της, το κεντρικό χρώμα θα είναι στη μέγιστη ένταση του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |
| scale | float | Μια τιμή από 0 έως 1 που καθορίζει τη μέγιστη ένταση του κεντρικού χρώματος που αναμειγνύεται με το χρώμα του ορίου. Μια τιμή 1 προκαλεί τη μέγιστη δυνατή ένταση του κεντρικού χρώματος, και είναι η προεπιλεγμένη τιμή. |

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

