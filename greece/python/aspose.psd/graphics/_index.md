---
title: "Κλάση Graphics"
type: docs
weight: 1550
url: /el/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Λαμβάνει ή ορίζει την περιοχή αποκοπής. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Λαμβάνει ή ορίζει την ποιότητα σύνθεσης. |
| dpi_x | float | r | Λαμβάνει την οριζόντια ανάλυση αυτού του Aspose.PSD.Graphics. |
| dpi_y | float | r | Λαμβάνει την κάθετη ανάλυση αυτού του Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Λαμβάνει την εικόνα. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Λαμβάνει ή ορίζει τη λειτουργία παρεμβολής. |
| is_in_begin_update_call | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν το graphics βρίσκεται σε κατάσταση κλήσης BeginUpdate. |
| page_scale | float | r/w | Λαμβάνει ή ορίζει την κλίμακα μεταξύ των μονάδων κόσμου και των μονάδων σελίδας για αυτό το Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Λαμβάνει ή ορίζει τη μονάδα μέτρησης που χρησιμοποιείται για τις συντεταγμένες σελίδας σε αυτό το Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Λαμβάνει ή ορίζει τις επιλογές εικόνας, που χρησιμοποιούνται για τη δημιουργία ζωγραφίσιμων vactor εικόνων για σχεδίαση. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Λαμβάνει ή ορίζει τη λειτουργία εξομάλυνσης. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Λαμβάνει ή ορίζει τη συμβουλή απόδοσης κειμένου. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Λαμβάνει ή ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού κόσμου για αυτό το [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| begin_update() | Ξεκινά την προσωρινή αποθήκευση των παρακάτω λειτουργιών graphics. Τα εφέ graphics που εφαρμόζονται μετά δεν θα εφαρμοστούν αμέσως· αντίθετα, το EndUpdate θα προκαλέσει την εφαρμογή όλων των εφέ ταυτόχρονα. |
| [clear(color)](#clear_color_1) | Καθαρίζει την επιφάνεια graphics χρησιμοποιώντας το καθορισμένο χρώμα. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερα διατεταγμένα ζεύγη συντεταγμένων που αντιπροσωπεύουν σημεία. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών [Point](/psd/python-net/aspose.psd/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών [Point](/psd/python-net/aspose.psd/point/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Σχεδιάζει μια κλειστή καρδινάλια καμπύλη που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Σχεδιάζει μια κλειστή καρδινάλια καμπύλη που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Σχεδιάζει μια κλειστή καρδινάλια καμπύλη που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Σχεδιάζει μια κλειστή καρδινάλια καμπύλη που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Η σχεδίαση αρχίζει με μετατόπιση από την αρχή του πίνακα.<br/>            Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. Η σχεδίαση αρχίζει με μετατόπιση από την αρχή του πίνακα. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. Η σχεδίαση αρχίζει με μετατόπιση από την αρχή του πίνακα. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Σχεδιάζει μια έλλειψη που ορίζεται από ένα περιβάλλον [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Σχεδιάζει μια έλλειψη που ορίζεται από ένα περιβάλλον [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Σχεδιάζει μια έλλειψη που ορίζεται από ένα περιβάλλον ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Σχεδιάζει μια έλλειψη που ορίζεται από ένα περιβάλλον ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Σχεδιάζει την καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος στην θέση που καθορίζεται από ένα ζεύγος συντεταγμένων. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Σχεδιάζει την καθορισμένη εικόνα χωρίς κλιμάκωση και την περικόπτει, εάν χρειάζεται, ώστε να ταιριάζει στο καθορισμένο ορθογώνιο. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Σχεδιάζει μια γραμμή που συνδέει δύο δομές [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Σχεδιάζει μια γραμμή που συνδέει δύο δομές [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών [Point](/psd/python-net/aspose.psd/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών [Point](/psd/python-net/aspose.psd/point/). |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Σχεδιάζει ένα [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) και δύο ακτινικές γραμμές. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) και δύο ακτινικές γραμμές. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Σχεδιάζει τη καθορισμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/). |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στο συγκεκριμένο ορθογώνιο με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας τις ιδιότητες μορφοποίησης του συγκεκριμένου [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/). |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας τις ιδιότητες μορφοποίησης του συγκεκριμένου [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/). |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας τις ιδιότητες μορφοποίησης του συγκεκριμένου [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | Ολοκληρώνει την προσωρινή αποθήκευση των λειτουργιών γραφικών που ξεκίνησαν μετά την κλήση του BeginUpdate. Οι προηγούμενες λειτουργίες γραφικών θα εφαρμοστούν αμέσως κατά την κλήση αυτής της μεθόδου. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και τη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και τη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος και τάση. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος και τάση. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιβάλλον ορθογώνιο καθορισμένο από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιβάλλον ορθογώνιο καθορισμένο από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιβάλλον ορθογώνιο καθορισμένο από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιβάλλον ορθογώνιο καθορισμένο από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Γεμίζει το εσωτερικό ενός [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα καθορισμένο από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) και δύο ακτινικές γραμμές. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα καθορισμένο από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) και δύο ακτινικές γραμμές. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα καθορισμένο από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα καθορισμένο από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων καθορισμένων από δομές [PointF](/psd/python-net/aspose.psd/pointf/) και τη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων καθορισμένων από δομές [PointF](/psd/python-net/aspose.psd/pointf/) και τη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων καθορισμένων από δομές [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων καθορισμένων από δομές [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από δομές [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από δομές [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Γεμίζει το εσωτερικό ενός [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Πολλαπλασιάζει το [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τη τοπική γεωμετρική μετασχηματισμό αυτού του [Graphics](/psd/python-net/aspose.psd/graphics/) με το καθορισμένο [Matrix](/psd/python-net/aspose.psd/matrix/) προσθέτοντας στην αρχή το καθορισμένο [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Πολλαπλασιάζει το [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τη τοπική γεωμετρική μετασχηματισμό αυτού του [Graphics](/psd/python-net/aspose.psd/graphics/) με το καθορισμένο [Matrix](/psd/python-net/aspose.psd/matrix/) με τη συγκεκριμένη σειρά. |
| reset_transform() | Επαναφέρει την ιδιότητα [Graphics.transform](/psd/python-net/aspose.psd/graphics/) στην ταυτότητα. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με την καθορισμένη σειρά. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις με την καθορισμένη σειρά. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα προέλευσης. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Καθαρίζει την επιφάνεια graphics χρησιμοποιώντας το καθορισμένο χρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Το χρώμα με το οποίο θα καθαριστεί η επιφάνεια γραφικών. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του τόξου. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που ορίζει τα όρια της έλλειψης. |
| start_angle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα x έως το σημείο εκκίνησης του τόξου. |
| sweep_angle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> έως το σημείο λήξης του τόξου. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του τόξου. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που ορίζει τα όρια της έλλειψης. |
| start_angle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα x έως το σημείο εκκίνησης του τόξου. |
| sweep_angle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> έως το σημείο λήξης του τόξου. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του τόξου. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη. |
| width | float | Το πλάτος του ορθογωνίου που ορίζει την έλλειψη. |
| height | float | Το ύψος του ορθογωνίου που ορίζει την έλλειψη. |
| start_angle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα x έως το σημείο εκκίνησης του τόξου. |
| sweep_angle | float | Γωνία σε μοίρες που μετριέται δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> έως το σημείο λήξης του τόξου. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Σχεδιάζει ένα τόξο που αντιπροσωπεύει ένα τμήμα έλλειψης που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του τόξου. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη. |
| width | int | Το πλάτος του ορθογωνίου που ορίζει την έλλειψη. |
| height | int | Το ύψος του ορθογωνίου που ορίζει την έλλειψη. |
| start_angle | int | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα x έως το σημείο εκκίνησης του τόξου. |
| sweep_angle | int | Γωνία σε μοίρες που μετριέται δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> έως το σημείο λήξης του τόξου. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το σημείο εκκίνησης της καμπύλης. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το πρώτο σημείο ελέγχου για την καμπύλη. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το δεύτερο σημείο ελέγχου για την καμπύλη. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το σημείο λήξης της καμπύλης. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερις δομές [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το σημείο εκκίνησης της καμπύλης. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το πρώτο σημείο ελέγχου για την καμπύλη. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το δεύτερο σημείο ελέγχου για την καμπύλη. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει το σημείο λήξης της καμπύλης. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Σχεδιάζει μια καμπύλη Bézier που ορίζεται από τέσσερα διατεταγμένα ζεύγη συντεταγμένων που αντιπροσωπεύουν σημεία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| x1 | float | Η συντεταγμένη x του σημείου εκκίνησης της καμπύλης. |
| y1 | float | Η συντεταγμένη y του σημείου εκκίνησης της καμπύλης. |
| x2 | float | Η συντεταγμένη x του πρώτου σημείου ελέγχου της καμπύλης. |
| y2 | float | Η συντεταγμένη y του πρώτου σημείου ελέγχου της καμπύλης. |
| x3 | float | Η συντεταγμένη x του δεύτερου σημείου ελέγχου της καμπύλης. |
| y3 | float | Η συντεταγμένη y του δεύτερου σημείου ελέγχου της καμπύλης. |
| x4 | float | Η συντεταγμένη x του τελικού σημείου της καμπύλης. |
| y4 | float | Η συντεταγμένη y του τελικού σημείου της καμπύλης. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύουν τα σημεία που καθορίζουν την καμπύλη. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Σχεδιάζει μια σειρά από καμπύλες Bézier από έναν πίνακα δομών [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της καμπύλης. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύουν τα σημεία που καθορίζουν την καμπύλη. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Σχεδιάζει μια κλειστή καρδινάλια καμπύλη που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Σχεδιάζει μια κλειστή καρδινάλια καμπύλη που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Σχεδιάζει μια κλειστή καρδινάλια καμπύλη που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Σχεδιάζει μια κλειστή καρδινάλια καμπύλη που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Η σχεδίαση αρχίζει με μετατόπιση από την αρχή του πίνακα.<br/>            Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| offset | int | Μετατόπιση από το πρώτο στοιχείο στον πίνακα της παραμέτρου <paramref name="points" /> προς το αρχικό σημείο στην καμπύλη. |
| number_of_segments | int | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. Η σχεδίαση αρχίζει με μετατόπιση από την αρχή του πίνακα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| offset | int | Μετατόπιση από το πρώτο στοιχείο στον πίνακα της παραμέτρου <paramref name="points" /> προς το αρχικό σημείο στην καμπύλη. |
| number_of_segments | int | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση. Η σχεδίαση αρχίζει με μετατόπιση από την αρχή του πίνακα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| offset | int | Μετατόπιση από το πρώτο στοιχείο στον πίνακα της παραμέτρου <paramref name="points" /> προς το αρχικό σημείο στην καμπύλη. |
| number_of_segments | int | Αριθμός τμημάτων μετά το αρχικό σημείο που θα συμπεριληφθούν στην καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύουν τα σημεία που ορίζουν την καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Σχεδιάζει μια καρδινάλια καμπύλη μέσω ενός καθορισμένου πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας καθορισμένη τάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το ύψος της καμπύλης. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύουν τα σημεία που ορίζουν την καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Σχεδιάζει μια έλλειψη που ορίζεται από ένα περιβάλλον [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της έλλειψης. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που ορίζει τα όρια της έλλειψης. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Σχεδιάζει μια έλλειψη που ορίζεται από ένα περιβάλλον [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της έλλειψης. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που ορίζει τα όρια της έλλειψης. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Σχεδιάζει μια έλλειψη που ορίζεται από ένα περιβάλλον ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της έλλειψης. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| width | float | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| height | float | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Σχεδιάζει μια έλλειψη που ορίζεται από ένα περιβάλλον ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα ύψος και ένα πλάτος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της έλλειψης. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| width | int | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| height | int | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα για σχεδίαση. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας τριών δομών PointF που ορίζουν ένα παραλληλόγραμμο. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα για σχεδίαση. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας τριών δομών PointF που ορίζουν ένα παραλληλόγραμμο. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα για σχεδίαση. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας τριών δομών PointF που ορίζουν ένα παραλληλόγραμμο. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το πηγαίο ορθογώνιο. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα για σχεδίαση. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας τριών δομών PointF που ορίζουν ένα παραλληλόγραμμο. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το πηγαίο ορθογώνιο. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα για σχεδίαση. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας τριών δομών PointF που ορίζουν ένα παραλληλόγραμμο. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το πηγαίο ορθογώνιο. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Οι μονάδες μέτρησης. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα για σχεδίαση. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας τριών δομών PointF που ορίζουν ένα παραλληλόγραμμο. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το πηγαίο ορθογώνιο. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Οι μονάδες μέτρησης. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα για σχεδίαση. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας τριών δομών PointF που ορίζουν ένα παραλληλόγραμμο. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το πηγαίο ορθογώνιο. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Οι μονάδες μέτρησης. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Σχεδιάζει το καθορισμένο τμήμα της καθορισμένης <paramref name="image" /> στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα για σχεδίαση. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας τριών δομών PointF που ορίζουν ένα παραλληλόγραμμο. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το πηγαίο ορθογώνιο. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Οι μονάδες μέτρησης. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει την επάνω αριστερή γωνία της σχεδιασμένης εικόνας. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| point | [Point](/psd/python-net/aspose.psd/point) | Δομή [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύει την επάνω αριστερή γωνία της σχεδιασμένης εικόνας. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που καθορίζει τη θέση και το μέγεθος της σχεδιασμένης εικόνας. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που καθορίζει τη θέση και το μέγεθος της σχεδιασμένης εικόνας. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το τελικό ορθογώνιο. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Η μονάδα γραφικών. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το τελικό ορθογώνιο. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Η μονάδα γραφικών. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το τελικό ορθογώνιο. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Η μονάδα γραφικών. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Το τελικό ορθογώνιο. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Η μονάδα γραφικών. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Η πηγή rect. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ο προορισμός rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Η μονάδα γραφικών. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Η πηγή rect. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ο προορισμός rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Η μονάδα γραφικών. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Η πηγή rect. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ο προορισμός rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Η μονάδα γραφικών. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Η πηγή rect. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ο προορισμός rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Η μονάδα γραφικών. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Τα χαρακτηριστικά της εικόνας. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | float | Η x-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | float | Η y-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/), χρησιμοποιώντας το αρχικό φυσικό του μέγεθος, στην καθορισμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | int | Η x-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | int | Η y-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | float | Η x-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | float | Η y-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| width | float | Πλάτος της σχεδιασμένης εικόνας. |
| height | float | Ύψος της σχεδιασμένης εικόνας. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Σχεδιάζει το καθορισμένο [Graphics.image](/psd/python-net/aspose.psd/graphics/) στην καθορισμένη θέση και με το καθορισμένο μέγεθος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | int | Η x-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | int | Η y-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| width | int | Πλάτος της σχεδιασμένης εικόνας. |
| height | int | Ύψος της σχεδιασμένης εικόνας. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| point | [Point](/psd/python-net/aspose.psd/point) | Δομή [Point](/psd/python-net/aspose.psd/point/) που καθορίζει την επάνω αριστερή γωνία της σχεδιασμένης εικόνας. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το [Rectangle](/psd/python-net/aspose.psd/rectangle/) που καθορίζει την επάνω αριστερή γωνία της σχεδιασμένης εικόνας. Οι ιδιότητες X και Y του rectangle καθορίζουν την επάνω αριστερή γωνία. Οι ιδιότητες Width και Height αγνοούνται. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Σχεδιάζει την καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος στην θέση που καθορίζεται από ένα ζεύγος συντεταγμένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | int | Η x-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | int | Η y-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Σχεδιάζει μια καθορισμένη εικόνα χρησιμοποιώντας το αρχικό φυσικό της μέγεθος σε μια καθορισμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| x | int | Η x-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| y | int | Η y-συντεταγμένη της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας. |
| width | int | Η παράμετρος δεν χρησιμοποιείται. |
| height | int | Η παράμετρος δεν χρησιμοποιείται. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Σχεδιάζει την καθορισμένη εικόνα χωρίς κλιμάκωση και την περικόπτει, εάν χρειάζεται, ώστε να ταιριάζει στο καθορισμένο ορθογώνιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα με την οποία θα σχεδιαστεί. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το [Rectangle](/psd/python-net/aspose.psd/rectangle/) στο οποίο θα σχεδιαστεί η εικόνα. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Σχεδιάζει μια γραμμή που συνδέει δύο δομές [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της γραμμής. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Δομή [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει το πρώτο σημείο προς σύνδεση. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Δομή [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει το δεύτερο σημείο προς σύνδεση. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Σχεδιάζει μια γραμμή που συνδέει δύο δομές [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της γραμμής. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Δομή [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει το πρώτο σημείο προς σύνδεση. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Δομή [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύει το δεύτερο σημείο προς σύνδεση. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της γραμμής. |
| x1 | int | Η x-συντεταγμένη του πρώτου σημείου. |
| y1 | int | Η y-συντεταγμένη του πρώτου σημείου. |
| x2 | int | Η x-συντεταγμένη του δεύτερου σημείου. |
| y2 | int | Η y-συντεταγμένη του δεύτερου σημείου. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Σχεδιάζει μια γραμμή που συνδέει τα δύο σημεία που καθορίζονται από τα ζεύγη συντεταγμένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της γραμμής. |
| x1 | float | Η x-συντεταγμένη του πρώτου σημείου. |
| y1 | float | Η y-συντεταγμένη του πρώτου σημείου. |
| x2 | float | Η x-συντεταγμένη του δεύτερου σημείου. |
| y2 | float | Η y-συντεταγμένη του δεύτερου σημείου. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των τμημάτων γραμμής. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύουν τα σημεία προς σύνδεση. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Σχεδιάζει μια σειρά από τμήματα γραμμής που συνδέουν έναν πίνακα δομών [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των τμημάτων γραμμής. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [Point](/psd/python-net/aspose.psd/point/) που αντιπροσωπεύουν τα σημεία προς σύνδεση. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Σχεδιάζει ένα [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της διαδρομής. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Το [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) για σχεδίαση. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) και δύο ακτινικές γραμμές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του σχήματος πίτας. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το ορθογώνιο περιβάλλον που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| start_angle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x μέχρι την πρώτη πλευρά του σχήματος πίτας. |
| sweep_angle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> μέχρι τη δεύτερη πλευρά του σχήματος πίτας. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) και δύο ακτινικές γραμμές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του σχήματος πίτας. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το ορθογώνιο περιβάλλον που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| start_angle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x μέχρι την πρώτη πλευρά του σχήματος πίτας. |
| sweep_angle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> μέχρι τη δεύτερη πλευρά του σχήματος πίτας. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του σχήματος πίτας. |
| x | float | Η x-συντεταγμένη της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| y | float | Η y-συντεταγμένη της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| width | float | Το πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| height | float | Το ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| start_angle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x μέχρι την πρώτη πλευρά του σχήματος πίτας. |
| sweep_angle | float | Γωνία μετρημένη σε μοίρες δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> μέχρι τη δεύτερη πλευρά του σχήματος πίτας. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Σχεδιάζει ένα σχήμα πίτας που ορίζεται από μια έλλειψη που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Το [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του σχήματος πίτας. |
| x | int | Η x-συντεταγμένη της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| y | int | Η y-συντεταγμένη της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| width | int | Το πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| height | int | Το ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το σχήμα πίτας. |
| start_angle | int | Γωνία μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x μέχρι την πρώτη πλευρά του σχήματος πίτας. |
| sweep_angle | int | Γωνία μετρημένη σε μοίρες δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> μέχρι τη δεύτερη πλευρά του σχήματος πίτας. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του πολυγώνου. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας των δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύουν τις κορυφές του πολυγώνου. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Σχεδιάζει ένα πολύγωνο που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του πολυγώνου. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας των δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύουν τις κορυφές του πολυγώνου. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ένα [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του ορθογωνίου. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Μία [RectangleF](/psd/python-net/aspose.psd/rectanglef/) δομή που αντιπροσωπεύει το ορθογώνιο προς σχεδίαση. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Σχεδιάζει ένα ορθογώνιο που καθορίζεται από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ένα [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του ορθογωνίου. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Μία [RectangleF](/psd/python-net/aspose.psd/rectanglef/) δομή που αντιπροσωπεύει το ορθογώνιο προς σχεδίαση. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ένα [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του ορθογωνίου. |
| x | float | Η x-συντεταγμένη της επάνω αριστερής γωνίας του ορθογωνίου προς σχεδίαση. |
| y | float | Η y-συντεταγμένη της επάνω αριστερής γωνίας του ορθογωνίου προς σχεδίαση. |
| width | float | Το πλάτος του ορθογωνίου προς σχεδίαση. |
| height | float | Το ύψος του ορθογωνίου προς σχεδίαση. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Σχεδιάζει ένα ορθογώνιο που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ένα [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ του ορθογωνίου. |
| x | int | Η x-συντεταγμένη της επάνω αριστερής γωνίας του ορθογωνίου προς σχεδίαση. |
| y | int | Η y-συντεταγμένη της επάνω αριστερής γωνίας του ορθογωνίου προς σχεδίαση. |
| width | int | Το πλάτος του ορθογωνίου προς σχεδίαση. |
| height | int | Το ύψος του ορθογωνίου προς σχεδίαση. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των περιγραμμάτων των ορθογωνίων. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Πίνακας των δομών [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύουν τα ορθογώνια προς σχεδίαση. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των περιγραμμάτων των ορθογωνίων. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Πίνακας των δομών [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύουν τα ορθογώνια προς σχεδίαση. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Σχεδιάζει τη καθορισμένη συμβολοσειρά κειμένου στο καθορισμένο ορθογώνιο με τα καθορισμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| s | string | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στο συγκεκριμένο ορθογώνιο με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας τις ιδιότητες μορφοποίησης του συγκεκριμένου [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| s | string | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) δομή που καθορίζει τη θέση του σχεδιασμένου κειμένου. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) που καθορίζει τις ιδιότητες μορφοποίησης, όπως το διάστιχο και την ευθυγράμμιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| s | string | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) δομή που καθορίζει την επάνω αριστερή γωνία του σχεδιασμένου κειμένου. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας τις ιδιότητες μορφοποίησης του συγκεκριμένου [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| s | string | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) δομή που καθορίζει την επάνω αριστερή γωνία του σχεδιασμένου κειμένου. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) που καθορίζει τις ιδιότητες μορφοποίησης, όπως το διάστιχο και την ευθυγράμμιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| s | string | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | float | Η x-συντεταγμένη της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | float | Η y-συντεταγμένη της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Σχεδιάζει τη συγκεκριμένη συμβολοσειρά κειμένου στην καθορισμένη θέση με τα συγκεκριμένα αντικείμενα [Brush](/psd/python-net/aspose.psd/brush/) και [Font](/psd/python-net/aspose.psd/font/) χρησιμοποιώντας τις ιδιότητες μορφοποίησης του συγκεκριμένου [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| s | string | Συμβολοσειρά προς σχεδίαση. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) που ορίζει τη μορφή κειμένου της συμβολοσειράς. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει το χρώμα και την υφή του σχεδιασμένου κειμένου. |
| x | float | Η x-συντεταγμένη της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| y | float | Η y-συντεταγμένη της επάνω αριστερής γωνίας του σχεδιασμένου κειμένου. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) που καθορίζει τις ιδιότητες μορφοποίησης, όπως το διάστιχο και την ευθυγράμμιση, που εφαρμόζονται στο σχεδιασμένο κείμενο. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και τη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/). Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5 και τη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Μέλος της απαρίθμησης [FillMode](/psd/python-net/aspose.psd/fillmode/) που καθορίζει πώς γεμίζεται η καμπύλη. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος. Αυτή η μέθοδος χρησιμοποιεί προεπιλεγμένη τάση 0.5.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Μέλος της απαρίθμησης [FillMode](/psd/python-net/aspose.psd/fillmode/) που καθορίζει πώς γεμίζεται η καμπύλη. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος και τάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Ένα [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Μέλος της απαρίθμησης [FillMode](/psd/python-net/aspose.psd/fillmode/) που καθορίζει πώς γεμίζεται η καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Γεμίζει το εσωτερικό μιας κλειστής καρδιακής καμπύλης spline που ορίζεται από έναν πίνακα δομών [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος και τάση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Ένα [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που ορίζουν τη σπλάιν. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Μέλος της απαρίθμησης [FillMode](/psd/python-net/aspose.psd/fillmode/) που καθορίζει πώς γεμίζεται η καμπύλη. |
| τάση | float | Τιμή μεγαλύτερη ή ίση με 0.0F που καθορίζει την τάση της καμπύλης. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιβάλλον ορθογώνιο καθορισμένο από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το περιβάλλον ορθογώνιο που ορίζει την έλλειψη. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιβάλλον ορθογώνιο καθορισμένο από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) που αντιπροσωπεύει το περιβάλλον ορθογώνιο που ορίζει την έλλειψη. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιβάλλον ορθογώνιο καθορισμένο από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| width | float | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| height | float | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Γεμίζει το εσωτερικό ενός έλλειψα που ορίζεται από ένα περιβάλλον ορθογώνιο καθορισμένο από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| width | int | Πλάτος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |
| height | int | Ύψος του περιοριστικού ορθογωνίου που ορίζει την έλλειψη. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Γεμίζει το εσωτερικό ενός [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) που αντιπροσωπεύει τη διαδρομή προς γέμισμα. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα καθορισμένο από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) και δύο ακτινικές γραμμές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύει το περιβάλλον ορθογώνιο που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| start_angle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα x μέχρι την πρώτη πλευρά του τμήματος πίτας. |
| sweep_angle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> μέχρι τη δεύτερη πλευρά του τμήματος πίτας. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα καθορισμένο από μια δομή [RectangleF](/psd/python-net/aspose.psd/rectanglef/) και δύο ακτινικές γραμμές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύει το περιβάλλον ορθογώνιο που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| start_angle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα x μέχρι την πρώτη πλευρά του τμήματος πίτας. |
| sweep_angle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> μέχρι τη δεύτερη πλευρά του τμήματος πίτας. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα καθορισμένο από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | float | Η συντεταγμένη x του επάνω αριστερού γωνίας του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| y | float | Η συντεταγμένη y του επάνω αριστερού γωνίας του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| width | float | Πλάτος του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| height | float | Ύψος του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| start_angle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα x μέχρι την πρώτη πλευρά του τμήματος πίτας. |
| sweep_angle | float | Γωνία σε μοίρες που μετράται δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> μέχρι τη δεύτερη πλευρά του τμήματος πίτας. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Γεμίζει το εσωτερικό ενός τμήματος πίτας που ορίζεται από ένα έλλειψα καθορισμένο από ένα ζεύγος συντεταγμένων, ένα πλάτος, ένα ύψος και δύο ακτινικές γραμμές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | int | Η συντεταγμένη x του επάνω αριστερού γωνίας του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| y | int | Η συντεταγμένη y του επάνω αριστερού γωνίας του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| width | int | Πλάτος του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| height | int | Ύψος του περιβάλλοντος ορθογωνίου που ορίζει την έλλειψη από την οποία προέρχεται το τμήμα πίτας. |
| start_angle | int | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα x μέχρι την πρώτη πλευρά του τμήματος πίτας. |
| sweep_angle | int | Γωνία σε μοίρες που μετράται δεξιόστροφα από την παράμετρο <paramref name="startAngle" /> μέχρι τη δεύτερη πλευρά του τμήματος πίτας. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων καθορισμένων από δομές [PointF](/psd/python-net/aspose.psd/pointf/) και τη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύουν τις κορυφές του πολυγώνου προς γέμισμα. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων καθορισμένων από δομές [PointF](/psd/python-net/aspose.psd/pointf/) και τη λειτουργία γεμίσματος [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύουν τις κορυφές του πολυγώνου προς γέμισμα. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων καθορισμένων από δομές [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύουν τις κορυφές του πολυγώνου προς γέμισμα. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Μέλος της απαρίθμησης [FillMode](/psd/python-net/aspose.psd/fillmode/) που καθορίζει το στυλ του γεμίσματος. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Γεμίζει το εσωτερικό ενός πολυγώνου που ορίζεται από έναν πίνακα σημείων καθορισμένων από δομές [PointF](/psd/python-net/aspose.psd/pointf/) χρησιμοποιώντας τη συγκεκριμένη λειτουργία γεμίσματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Πίνακας δομών [PointF](/psd/python-net/aspose.psd/pointf/) που αντιπροσωπεύουν τις κορυφές του πολυγώνου προς γέμισμα. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Μέλος της απαρίθμησης [FillMode](/psd/python-net/aspose.psd/fillmode/) που καθορίζει το στυλ του γεμίσματος. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύει το ορθογώνιο προς γέμισμα. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από μια δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Δομή [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύει το ορθογώνιο προς γέμισμα. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | float | Η συντεταγμένη x του επάνω αριστερού γωνίας του ορθογωνίου προς γέμισμα. |
| y | float | Η συντεταγμένη y του επάνω αριστερού γωνίας του ορθογωνίου προς γέμισμα. |
| width | float | Πλάτος του ορθογωνίου προς γέμισμα. |
| height | float | Ύψος του ορθογωνίου προς γέμισμα. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Γεμίζει το εσωτερικό ενός ορθογωνίου που καθορίζεται από ένα ζεύγος συντεταγμένων, ένα πλάτος και ένα ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| x | int | Η συντεταγμένη x του επάνω αριστερού γωνίας του ορθογωνίου προς γέμισμα. |
| y | int | Η συντεταγμένη y του επάνω αριστερού γωνίας του ορθογωνίου προς γέμισμα. |
| width | int | Πλάτος του ορθογωνίου προς γέμισμα. |
| height | int | Ύψος του ορθογωνίου προς γέμισμα. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από δομές [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Πίνακας δομών [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύουν τα ορθογώνια προς γέμισμα. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Γεμίζει τα εσωτερικά μιας σειράς ορθογωνίων που καθορίζονται από δομές [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Πίνακας δομών [Rectangle](/psd/python-net/aspose.psd/rectangle/) που αντιπροσωπεύουν τα ορθογώνια προς γέμισμα. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Γεμίζει το εσωτερικό ενός [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) που καθορίζει τα χαρακτηριστικά του γεμίσματος. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) που αντιπροσωπεύει την περιοχή προς γέμισμα. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Πολλαπλασιάζει το [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τη τοπική γεωμετρική μετασχηματισμό αυτού του [Graphics](/psd/python-net/aspose.psd/graphics/) με το καθορισμένο [Matrix](/psd/python-net/aspose.psd/matrix/) προσθέτοντας στην αρχή το καθορισμένο [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο [Matrix](/psd/python-net/aspose.psd/matrix/) με τον οποίο πολλαπλασιάζεται ο γεωμετρικός μετασχηματισμός. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Πολλαπλασιάζει το [Matrix](/psd/python-net/aspose.psd/matrix/) που αντιπροσωπεύει τη τοπική γεωμετρική μετασχηματισμό αυτού του [Graphics](/psd/python-net/aspose.psd/graphics/) με το καθορισμένο [Matrix](/psd/python-net/aspose.psd/matrix/) με τη συγκεκριμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Ο [Matrix](/psd/python-net/aspose.psd/matrix/) με τον οποίο πολλαπλασιάζεται ο γεωμετρικός μετασχηματισμός. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ένα [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) που καθορίζει με ποια σειρά να πολλαπλασιαστούν οι δύο πίνακες. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γωνία | float | Η γωνία περιστροφής. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με την καθορισμένη σειρά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γωνία | float | Η γωνία περιστροφής. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ένα [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) που καθορίζει αν θα προσαρτηθεί ή θα προστεθεί ο πίνακας περιστροφής. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Μετατοπίζει τον τοπικό γεωμετρικό μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει τη μετάφραση στον μετασχηματισμό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στο y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


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

