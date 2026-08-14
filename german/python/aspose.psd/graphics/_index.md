---
title: "Graphics-Klasse"
type: docs
weight: 1550
url: /de/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initialisiert eine neue Instanz der [Graphics](/psd/python-net/aspose.psd/graphics/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Liest oder setzt den Clip‑Bereich. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Liest oder setzt die Kompositierungsqualität. |
| dpi_x | float | r | Liest die horizontale Auflösung dieses Aspose.PSD.Graphics. |
| dpi_y | float | r | Liest die vertikale Auflösung dieses Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Liest das Bild. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Liest oder setzt den Interpolationsmodus. |
| is_in_begin_update_call | bool | r | Liest einen Wert, der angibt, ob die Grafik sich im BeginUpdate‑Aufrufzustand befindet. |
| page_scale | float | r/w | Liest oder setzt die Skalierung zwischen Welteinheiten und Seiteneinheiten für dieses Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Liest oder setzt die Maßeinheit, die für Seitenkoordinaten in diesem Aspose.PSD.Graphics verwendet wird. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Liest oder setzt die Bildoptionen, die zum Erstellen von zeichnungsfähigen Vektor‑Bildern verwendet werden. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Ruft den Glättungsmodus ab oder legt ihn fest. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Ruft den Textdarstellungshinweis ab oder legt ihn fest. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Liest oder setzt eine Kopie der geometrischen Welttransformation für dieses [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| begin_update() | Startet das Zwischenspeichern der folgenden Grafikoperationen. Die anschließend angewendeten Grafikeffekte werden nicht sofort angewendet; stattdessen bewirkt EndUpdate, dass alle Effekte auf einmal angewendet werden. |
| [clear(color)](#clear_color_1) | Löscht die Grafikfläche mit der angegebenen Farbe. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Zeichnet eine Bézier‑Kurve, definiert durch vier geordnete Koordinatenpaare, die Punkte darstellen. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/psd/python-net/aspose.psd/point/)-Strukturen. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/psd/python-net/aspose.psd/point/)-Strukturen. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)-Füllmodus. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)-Füllmodus. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑[FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)-Füllmodus. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑[FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)-Füllmodus. |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays.<br/>            Diese Methode verwendet eine Standardspannung von 0,5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Zeichnet eine Ellipse, die durch ein begrenzendes [RectangleF](/psd/python-net/aspose.psd/rectanglef/) definiert ist. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Zeichnet eine Ellipse, die durch ein begrenzendes [RectangleF](/psd/python-net/aspose.psd/rectanglef/) definiert ist. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Zeichnet eine Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Höhe und eine Breite. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Zeichnet eine Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Höhe und eine Breite. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer angegebenen Position. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer angegebenen Position. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Zeichnet das angegebene Bild unter Verwendung seiner ursprünglichen physischen Größe an der durch ein Koordinatenpaar angegebenen Position. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer angegebenen Position. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Zeichnet das angegebene Bild ohne Skalierung und schneidet es, falls nötig, zu, um in das angegebene Rechteck zu passen. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Zeichnet eine Linie, die zwei [Point](/psd/python-net/aspose.psd/point/) Strukturen verbindet. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Zeichnet eine Linie, die zwei [Point](/psd/python-net/aspose.psd/point/) Strukturen verbindet. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von [Point](/psd/python-net/aspose.psd/point/) Strukturen verbinden. |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Zeichnet eine Reihe von Liniensegmenten, die ein Array von [Point](/psd/python-net/aspose.psd/point/) Strukturen verbinden. |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Zeichnet einen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, angegeben durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur und zwei Radiallinien. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, angegeben durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur und zwei Radiallinien. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Zeichnet ein Polygon, das durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Zeichnet ein Polygon, das durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Zeichnet ein Rechteck, das durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur angegeben ist. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Zeichnet ein Rechteck, das durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur angegeben ist. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Strukturen angegeben sind. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Strukturen angegeben sind. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten unter Verwendung der Formatierungsattribute des angegebenen [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten unter Verwendung der Formatierungsattribute des angegebenen [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten unter Verwendung der Formatierungsattribute des angegebenen [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | Beendet das Zwischenspeichern der Grafikoperationen, die nach dem Aufruf von BeginUpdate gestartet wurden. Die vorherigen Grafikoperationen werden beim Aufruf dieser Methode sofort angewendet. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0,5 und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) Füllmodus. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0,5 und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) Füllmodus. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur angegeben wird. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur angegeben wird. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Füllt das Innere eines [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur und zwei Radiallinien angegeben wird. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur und zwei Radiallinien angegeben wird. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben wird. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben wird. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Füllt das Innere eines Polygons, das durch ein Array von Punkten definiert ist, die durch [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen angegeben werden, und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Füllt das Innere eines Polygons, das durch ein Array von Punkten definiert ist, die durch [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen angegeben werden, und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Füllt das Innere eines Polygons, das durch ein Array von Punkten definiert ist, die durch [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen angegeben werden, unter Verwendung des angegebenen Füllmodus. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Füllt das Innere eines Polygons, das durch ein Array von Punkten definiert ist, die durch [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen angegeben werden, unter Verwendung des angegebenen Füllmodus. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Füllt das Innere eines Rechtecks, das durch eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur angegeben wird. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Füllt das Innere eines Rechtecks, das durch eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur angegeben wird. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Füllt das Innere eines Rechtecks, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Füllt das Innere eines Rechtecks, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Füllt die Innenbereiche einer Reihe von Rechtecken, die durch [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen angegeben werden. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Füllt die Innenbereiche einer Reihe von Rechtecken, die durch [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen angegeben werden. |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Füllt das Innere einer [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Multipliziert die [Matrix](/psd/python-net/aspose.psd/matrix/), die die lokale geometrische Transformation dieses [Graphics](/psd/python-net/aspose.psd/graphics/) darstellt, mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/), indem die angegebene [Matrix](/psd/python-net/aspose.psd/matrix/) vorangestellt wird. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Multipliziert die [Matrix](/psd/python-net/aspose.psd/matrix/), die die lokale geometrische Transformation dieses [Graphics](/psd/python-net/aspose.psd/graphics/) darstellt, mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/) in der angegebenen Reihenfolge. |
| reset_transform() | Setzt die [Graphics.transform](/psd/python-net/aspose.psd/graphics/) Eigenschaft auf die Identität zurück. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs‑Matrix der Transformation voran. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initialisiert eine neue Instanz der [Graphics](/psd/python-net/aspose.psd/graphics/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Quellbild. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Löscht die Grafikfläche mit der angegebenen Farbe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Die Farbe, mit der die Grafikfläche gelöscht wird. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom <paramref name="startAngle" /> Parameter zum Endpunkt des Bogens. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom <paramref name="startAngle" /> Parameter zum Endpunkt des Bogens. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| x | float | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| width | float | Breite des Rechtecks, das die Ellipse definiert. |
| height | float | Höhe des Rechtecks, das die Ellipse definiert. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom <paramref name="startAngle" /> Parameter zum Endpunkt des Bogens. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, angegeben durch ein Koordinatenpaar, eine Breite und eine Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil des Bogens. |
| x | int | Die x-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert. |
| width | int | Breite des Rechtecks, das die Ellipse definiert. |
| height | int | Höhe des Rechtecks, das die Ellipse definiert. |
| start_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweep_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom <paramref name="startAngle" /> Parameter zum Endpunkt des Bogens. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die den Endpunkt der Kurve darstellt. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Zeichnet eine Bézier‑Kurve, definiert durch vier [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die den Startpunkt der Kurve darstellt. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die den ersten Kontrollpunkt für die Kurve darstellt. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die den zweiten Kontrollpunkt für die Kurve darstellt. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die den Endpunkt der Kurve darstellt. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Zeichnet eine Bézier‑Kurve, definiert durch vier geordnete Koordinatenpaare, die Punkte darstellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| x1 | float | Die x-Koordinate des Startpunkts der Kurve. |
| y1 | float | Die y-Koordinate des Startpunkts der Kurve. |
| x2 | float | Die x-Koordinate des ersten Kontrollpunkts der Kurve. |
| y2 | float | Die y-Koordinate des ersten Kontrollpunkts der Kurve. |
| x3 | float | Die x-Koordinate des zweiten Kontrollpunkts der Kurve. |
| y3 | float | Die y-Koordinate des zweiten Kontrollpunkts der Kurve. |
| x4 | float | Die x-Koordinate des Endpunkts der Kurve. |
| y4 | float | Die y-Koordinate des Endpunkts der Kurve. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/psd/python-net/aspose.psd/point/)-Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [Point](/psd/python-net/aspose.psd/point/) Strukturen, die die Punkte darstellen, die die Kurve bestimmen. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Zeichnet eine Reihe von Bézier‑Kurven aus einem Array von [Point](/psd/python-net/aspose.psd/point/)-Strukturen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Kurve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [Point](/psd/python-net/aspose.psd/point/) Strukturen, die die Punkte darstellen, die die Kurve bestimmen. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)-Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5 und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)-Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑[FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)-Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Zeichnet eine geschlossene Kardinal‑Spline, definiert durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen unter Verwendung einer angegebenen Spannung. Diese Methode verwendet den Standard‑[FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)-Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Zeichnet eine Kardinal‑Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/)-Strukturen. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays.<br/>            Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| offset | int | Versatz vom ersten Element im Array des <paramref name="points" /> Parameters zum Startpunkt der Kurve. |
| number_of_segments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| offset | int | Versatz vom ersten Element im Array des <paramref name="points" /> Parameters zum Startpunkt der Kurve. |
| number_of_segments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen unter Verwendung einer angegebenen Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| offset | int | Versatz vom ersten Element im Array des <paramref name="points" /> Parameters zum Startpunkt der Kurve. |
| number_of_segments | int | Anzahl der Segmente nach dem Startpunkt, die in die Kurve einbezogen werden. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen unter Verwendung einer angegebenen Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Zeichnet eine kardinale Spline durch ein angegebenes Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen unter Verwendung einer angegebenen Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und Höhe der Kurve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Zeichnet eine Ellipse, die durch ein begrenzendes [RectangleF](/psd/python-net/aspose.psd/rectanglef/) definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Zeichnet eine Ellipse, die durch ein begrenzendes [RectangleF](/psd/python-net/aspose.psd/rectanglef/) definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die die Grenzen der Ellipse definiert. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Zeichnet eine Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Höhe und eine Breite.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Zeichnet eine Ellipse, die durch ein begrenzendes Rechteck definiert ist, angegeben durch ein Koordinatenpaar, eine Höhe und eine Breite.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Ellipse. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das zu zeichnende Bild. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array von drei PointF Strukturen, die ein Parallelogramm definieren. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das zu zeichnende Bild. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von drei PointF Strukturen, die ein Parallelogramm definieren. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das zu zeichnende Bild. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array von drei PointF Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Quellrechteck. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das zu zeichnende Bild. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von drei PointF Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Quellrechteck. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das zu zeichnende Bild. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array von drei PointF Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Maßeinheiten. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das zu zeichnende Bild. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von drei PointF Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Maßeinheiten. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das zu zeichnende Bild. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array von drei PointF Strukturen, die ein Parallelogramm definieren. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Maßeinheiten. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Die Bildeigenschaften. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Zeichnet den angegebenen Teil des angegebenen <paramref name="image" /> an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das zu zeichnende Bild. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von drei PointF Strukturen, die ein Parallelogramm definieren. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Quellrechteck. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Maßeinheiten. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Die Bildeigenschaften. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die die obere linke Ecke des gezeichneten Bildes darstellt. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| point | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die die obere linke Ecke des gezeichneten Bildes darstellt. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die den Ort und die Größe des gezeichneten Bildes angibt. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die den Ort und die Größe des gezeichneten Bildes angibt. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Grafikeinheit. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Grafikeinheit. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Die Bildeigenschaften. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Die Bildeigenschaften. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Quellrechteck. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Grafikeinheit. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Quellrechteck. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Grafikeinheit. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Quellrechteck. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Die Bildeigenschaften. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Quellrechteck. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Zielrechteck. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Die Grafikeinheit. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Die Bildeigenschaften. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | float | Die x‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | float | Die y‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/), unter Verwendung seiner ursprünglichen physischen Größe, an der angegebenen Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | float | Die x‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | float | Die y‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| width | float | Breite des gezeichneten Bildes. |
| height | float | Höhe des gezeichneten Bildes. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Zeichnet das angegebene [Graphics.image](/psd/python-net/aspose.psd/graphics/) an der angegebenen Position und mit der angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| width | int | Breite des gezeichneten Bildes. |
| height | int | Höhe des gezeichneten Bildes. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer angegebenen Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) Struktur, die die obere linke Ecke des gezeichneten Bildes angibt. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer angegebenen Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) gibt die obere linke Ecke des gezeichneten Bildes an. Die X‑ und Y‑Eigenschaften des Rechtecks geben die obere linke Ecke an. Die Width‑ und Height‑Eigenschaften werden ignoriert. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Zeichnet das angegebene Bild unter Verwendung seiner ursprünglichen physischen Größe an der durch ein Koordinatenpaar angegebenen Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Zeichnet ein angegebenes Bild unter Verwendung seiner ursprünglichen physischen Größe an einer angegebenen Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| x | int | Die x‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| y | int | Die y‑Koordinate der oberen linken Ecke des gezeichneten Bildes. |
| width | int | Der Parameter wird nicht verwendet. |
| height | int | Der Parameter wird nicht verwendet. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Zeichnet das angegebene Bild ohne Skalierung und schneidet es, falls nötig, zu, um in das angegebene Rechteck zu passen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Das Bild, mit dem gezeichnet wird. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das [Rectangle](/psd/python-net/aspose.psd/rectangle/) in dem das Bild gezeichnet wird. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Zeichnet eine Linie, die zwei [Point](/psd/python-net/aspose.psd/point/) Strukturen verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Linie. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) Struktur, die den ersten zu verbindenden Punkt darstellt. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) Struktur, die den zweiten zu verbindenden Punkt darstellt. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Zeichnet eine Linie, die zwei [Point](/psd/python-net/aspose.psd/point/) Strukturen verbindet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Linie. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) Struktur, die den ersten zu verbindenden Punkt darstellt. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) Struktur, die den zweiten zu verbindenden Punkt darstellt. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Linie. |
| x1 | int | Die x‑Koordinate des ersten Punktes. |
| y1 | int | Die y‑Koordinate des ersten Punktes. |
| x2 | int | Die x‑Koordinate des zweiten Punktes. |
| y2 | int | Die y‑Koordinate des zweiten Punktes. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Zeichnet eine Linie, die die beiden Punkte verbindet, die durch die Koordinatenpaare angegeben sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Linie. |
| x1 | float | Die x‑Koordinate des ersten Punktes. |
| y1 | float | Die y‑Koordinate des ersten Punktes. |
| x2 | float | Die x‑Koordinate des zweiten Punktes. |
| y2 | float | Die y‑Koordinate des zweiten Punktes. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Zeichnet eine Reihe von Liniensegmenten, die ein Array von [Point](/psd/python-net/aspose.psd/point/) Strukturen verbinden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [Point](/psd/python-net/aspose.psd/point/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Zeichnet eine Reihe von Liniensegmenten, die ein Array von [Point](/psd/python-net/aspose.psd/point/) Strukturen verbinden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) bestimmt die Farbe, Breite und den Stil der Liniensegmente. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [Point](/psd/python-net/aspose.psd/point/) Strukturen, die die zu verbindenden Punkte darstellen. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Zeichnet einen [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil des Pfads bestimmt. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) zum Zeichnen. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, angegeben durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil der Tortenform bestimmt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das Begrenzungsrechteck repräsentiert, das die Ellipse definiert, aus der die Tortenform entsteht. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Tortenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter <paramref name="startAngle" /> zur zweiten Seite der Tortenform. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, angegeben durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil der Tortenform bestimmt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das Begrenzungsrechteck repräsentiert, das die Ellipse definiert, aus der die Tortenform entsteht. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Tortenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter <paramref name="startAngle" /> zur zweiten Seite der Tortenform. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil der Tortenform bestimmt. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Tortenform entsteht. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Tortenform entsteht. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Tortenform entsteht. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Tortenform entsteht. |
| start_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Tortenform. |
| sweep_angle | float | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter <paramref name="startAngle" /> zur zweiten Seite der Tortenform. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Zeichnet eine Tortenform, die durch eine Ellipse definiert ist, angegeben durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil der Tortenform bestimmt. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Tortenform entsteht. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Tortenform entsteht. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Tortenform entsteht. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der die Tortenform entsteht. |
| start_angle | int | Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse zur ersten Seite der Tortenform. |
| sweep_angle | int | Winkel, gemessen in Grad im Uhrzeigersinn vom Parameter <paramref name="startAngle" /> zur zweiten Seite der Tortenform. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Zeichnet ein Polygon, das durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil des Polygons bestimmt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Eckpunkte des Polygons darstellen. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Zeichnet ein Polygon, das durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil des Polygons bestimmt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Eckpunkte des Polygons darstellen. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Zeichnet ein Rechteck, das durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ein [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil des Rechtecks bestimmt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das zu zeichnende Rechteck darstellt. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Zeichnet ein Rechteck, das durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ein [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil des Rechtecks bestimmt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das zu zeichnende Rechteck darstellt. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ein [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil des Rechtecks bestimmt. |
| x | float | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | float | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | float | Die Breite des zu zeichnenden Rechtecks. |
| height | float | Die Höhe des zu zeichnenden Rechtecks. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Zeichnet ein Rechteck, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Ein [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil des Rechtecks bestimmt. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| width | int | Die Breite des zu zeichnenden Rechtecks. |
| height | int | Die Höhe des zu zeichnenden Rechtecks. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Strukturen angegeben sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil der Umrisse der Rechtecke bestimmt. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array von [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Zeichnet eine Reihe von Rechtecken, die durch [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Strukturen angegeben sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) der die Farbe, Breite und den Stil der Umrisse der Rechtecke bestimmt. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array von [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Strukturen, die die zu zeichnenden Rechtecke darstellen. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) der das Textformat der Zeichenkette definiert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die den Ort des gezeichneten Textes angibt. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten unter Verwendung der Formatierungsattribute des angegebenen [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) der das Textformat der Zeichenkette definiert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die den Ort des gezeichneten Textes angibt. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) die Formatierungsattribute festlegt, wie Zeilenabstand und Ausrichtung, die auf den gezeichneten Text angewendet werden. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) der das Textformat der Zeichenkette definiert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten unter Verwendung der Formatierungsattribute des angegebenen [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) der das Textformat der Zeichenkette definiert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) die Formatierungsattribute festlegt, wie Zeilenabstand und Ausrichtung, die auf den gezeichneten Text angewendet werden. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) der das Textformat der Zeichenkette definiert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | float | Die y‑Koordinate der oberen linken Ecke des gezeichneten Textes. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Zeichnet die angegebene Textzeichenfolge am angegebenen Ort mit den angegebenen [Brush](/psd/python-net/aspose.psd/brush/) und [Font](/psd/python-net/aspose.psd/font/) Objekten unter Verwendung der Formatierungsattribute des angegebenen [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| s | string | Zeichenkette zum Zeichnen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) der das Textformat der Zeichenkette definiert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | float | Die y‑Koordinate der oberen linken Ecke des gezeichneten Textes. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) die Formatierungsattribute festlegt, wie Zeilenabstand und Ausrichtung, die auf den gezeichneten Text angewendet werden. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0,5 und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist. Diese Methode verwendet eine Standardspannung von 0,5 und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Mitglied der [FillMode](/psd/python-net/aspose.psd/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus. Diese Methode verwendet eine Standardspannung von 0,5.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Mitglied der [FillMode](/psd/python-net/aspose.psd/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Ein [Brush](/psd/python-net/aspose.psd/brush/) der die Eigenschaften der Füllung bestimmt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Mitglied der [FillMode](/psd/python-net/aspose.psd/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Füllt das Innere einer geschlossenen Kardinal-Spline-Kurve, die durch ein Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen definiert ist, unter Verwendung des angegebenen Füllmodus und der Spannung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Ein [Brush](/psd/python-net/aspose.psd/brush/) der die Eigenschaften der Füllung bestimmt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Spline definieren. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Mitglied der [FillMode](/psd/python-net/aspose.psd/fillmode/) Aufzählung, die bestimmt, wie die Kurve gefüllt wird. |
| Spannung | float | Wert größer oder gleich 0,0F, der die Spannung der Kurve angibt. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| x | float | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | float | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Füllt das Innere einer Ellipse, die durch ein Begrenzungsrechteck definiert ist, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| x | int | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| y | int | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Füllt das Innere eines [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) die den Pfad zum Füllen darstellt. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur und zwei Radiallinien angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x‑Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom <paramref name="startAngle" />‑Parameter zur zweiten Seite des Kuchenstücks. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur und zwei Radiallinien angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x‑Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom <paramref name="startAngle" />‑Parameter zur zweiten Seite des Kuchenstücks. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| y | float | Die y‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| width | float | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| height | float | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| start_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x‑Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom <paramref name="startAngle" />‑Parameter zur zweiten Seite des Kuchenstücks. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Füllt das Innere eines Kuchenabschnitts, der durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei Radiallinien angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| x | int | Die x‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| y | int | Die y‑Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| width | int | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| height | int | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der das Kuchenstück stammt. |
| start_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der x‑Achse zur ersten Seite des Kuchenstücks. |
| sweep_angle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom <paramref name="startAngle" />‑Parameter zur zweiten Seite des Kuchenstücks. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Füllt das Innere eines Polygons, das durch ein Array von Punkten definiert ist, die durch [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen angegeben werden, und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Eckpunkte des zu füllenden Polygons darstellen. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Füllt das Innere eines Polygons, das durch ein Array von Punkten definiert ist, die durch [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen angegeben werden, und den [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Eckpunkte des zu füllenden Polygons darstellen. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Füllt das Innere eines Polygons, das durch ein Array von Punkten definiert ist, die durch [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen angegeben werden, unter Verwendung des angegebenen Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Eckpunkte des zu füllenden Polygons darstellen. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Mitglied der [FillMode](/psd/python-net/aspose.psd/fillmode/) Aufzählung, die den Stil der Füllung bestimmt. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Füllt das Innere eines Polygons, das durch ein Array von Punkten definiert ist, die durch [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen angegeben werden, unter Verwendung des angegebenen Füllmodus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array von [PointF](/psd/python-net/aspose.psd/pointf/) Strukturen, die die Eckpunkte des zu füllenden Polygons darstellen. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Mitglied der [FillMode](/psd/python-net/aspose.psd/fillmode/) Aufzählung, die den Stil der Füllung bestimmt. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Füllt das Innere eines Rechtecks, das durch eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, die das zu füllende Rechteck darstellt. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Füllt das Innere eines Rechtecks, das durch eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, die das zu füllende Rechteck darstellt. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Füllt das Innere eines Rechtecks, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| x | float | Die x‑Koordinate der oberen linken Ecke des zu füllenden Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des zu füllenden Rechtecks. |
| width | float | Breite des zu füllenden Rechtecks. |
| height | float | Höhe des zu füllenden Rechtecks. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Füllt das Innere eines Rechtecks, das durch ein Koordinatenpaar, eine Breite und eine Höhe angegeben wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| x | int | Die x‑Koordinate der oberen linken Ecke des zu füllenden Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des zu füllenden Rechtecks. |
| width | int | Breite des zu füllenden Rechtecks. |
| height | int | Höhe des zu füllenden Rechtecks. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Füllt die Innenbereiche einer Reihe von Rechtecken, die durch [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen angegeben werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array von [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen, die die zu füllenden Rechtecke darstellen. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Füllt die Innenbereiche einer Reihe von Rechtecken, die durch [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen angegeben werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array von [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen, die die zu füllenden Rechtecke darstellen. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Füllt das Innere einer [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die die Eigenschaften der Füllung bestimmt. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) die den zu füllenden Bereich darstellt. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Multipliziert die [Matrix](/psd/python-net/aspose.psd/matrix/), die die lokale geometrische Transformation dieses [Graphics](/psd/python-net/aspose.psd/graphics/) darstellt, mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/), indem die angegebene [Matrix](/psd/python-net/aspose.psd/matrix/) vorangestellt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die [Matrix](/psd/python-net/aspose.psd/matrix/), mit der die geometrische Transformation multipliziert wird. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Multipliziert die [Matrix](/psd/python-net/aspose.psd/matrix/), die die lokale geometrische Transformation dieses [Graphics](/psd/python-net/aspose.psd/graphics/) darstellt, mit der angegebenen [Matrix](/psd/python-net/aspose.psd/matrix/) in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die [Matrix](/psd/python-net/aspose.psd/matrix/), mit der die geometrische Transformation multipliziert wird. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ein [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), der angibt, in welcher Reihenfolge die beiden Matrizen zu multiplizieren sind. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag. Diese Methode fügt die Rotation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Dreht die lokale geometrische Transformation um den angegebenen Betrag in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ein [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), der angibt, ob die Rotationsmatrix angehängt oder vorangestellt werden soll. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte. Diese Methode fügt die Skalierungs‑Matrix der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y‑Richtung skaliert wird. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Skaliert die lokale geometrische Transformation um die angegebenen Werte in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sx | float | Der Betrag, um den die Transformation in x‑Richtung skaliert wird. |
| sy | float | Der Betrag, um den die Transformation in y‑Richtung skaliert wird. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ein [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), der angibt, ob die Skalierungs‑Matrix angehängt oder vorangestellt werden soll. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen. Diese Methode fügt die Translation der Transformation voran.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | float | Der Wert der Verschiebung in x. |
| dy | float | Der Wert der Verschiebung in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Die Reihenfolge (voranstellen oder anhängen), in der die Verschiebung angewendet wird. |

