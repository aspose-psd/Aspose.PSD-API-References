---
title: "Classe Graphics"
type: docs
weight: 1550
url: /it/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Inizializza una nuova istanza della classe [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Ottiene o imposta la regione di ritaglio. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Ottiene o imposta la qualità di composizione. |
| dpi_x | float | r | Ottiene la risoluzione orizzontale di questo Aspose.PSD.Graphics. |
| dpi_y | float | r | Ottiene la risoluzione verticale di questo Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Ottiene l'immagine. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Ottiene o imposta la modalità di interpolazione. |
| is_in_begin_update_call | bool | r | Ottiene un valore che indica se la grafica è nello stato di chiamata BeginUpdate. |
| page_scale | float | r/w | Ottiene o imposta la scala tra unità del mondo e unità di pagina per questo Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Ottiene o imposta l'unità di misura usata per le coordinate di pagina in questo Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Ottiene o imposta le opzioni immagine, usate per creare immagini vettoriali dipingibili da disegnare. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Ottiene o imposta la modalità di smussatura. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Ottiene o imposta il suggerimento di rendering del testo. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Ottiene o imposta una copia della trasformazione geometrica del mondo per questo [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| begin_update() | Avvia la memorizzazione nella cache delle seguenti operazioni grafiche. Gli effetti grafici applicati successivamente non saranno applicati immediatamente; invece, EndUpdate causerà l'applicazione di tutti gli effetti in una volta. |
| [clear(color)](#clear_color_1) | Cancella la superficie grafica usando il colore specificato. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Disegna una spline Bézier definita da quattro strutture [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Disegna una spline Bézier definita da quattro strutture [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Disegna una spline Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Disegna una serie di spline Bézier da un array di strutture [Point](/psd/python-net/aspose.psd/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Disegna una serie di spline Bézier da un array di strutture [Point](/psd/python-net/aspose.psd/point/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Disegna una spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Disegna una spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Disegna una spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Disegna una spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Il disegno inizia con uno scostamento dall'inizio dell'array.<br/>            Questo metodo utilizza una tensione predefinita di 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno scostamento dall'inizio dell'array. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno scostamento dall'inizio dell'array. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Disegna un'ellisse definita da un rettangolo di delimitazione [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Disegna un'ellisse definita da un rettangolo di delimitazione [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Disegna l'immagine specificata usando la sua dimensione fisica originale nella posizione specificata da una coppia di coordinate. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Disegna l'immagine specificata senza ridimensionamento e la ritaglia, se necessario, per adattarla al rettangolo specificato. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Disegna una linea che collega due strutture [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Disegna una linea che collega due strutture [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Disegna una linea che collega i due punti specificati dalle coppie di coordinate. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Disegna una serie di segmenti di linea che collegano un array di strutture [Point](/psd/python-net/aspose.psd/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Disegna una serie di segmenti di linea che collegano un array di strutture [Point](/psd/python-net/aspose.psd/point/). |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Disegna un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) e due linee radiali. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) e due linee radiali. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Disegna un poligono definito da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Disegna un poligono definito da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Disegna un rettangolo specificato da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Disegna un rettangolo specificato da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Disegna una serie di rettangoli specificati da strutture [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Disegna una serie di rettangoli specificati da strutture [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/psd/python-net/aspose.psd/stringformat/) specificato. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Disegna la stringa di testo specificata alla posizione specificata con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Disegna la stringa di testo specificata alla posizione specificata con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/psd/python-net/aspose.psd/stringformat/) specificato. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Disegna la stringa di testo specificata alla posizione specificata con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Disegna la stringa di testo specificata alla posizione specificata con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/psd/python-net/aspose.psd/stringformat/) specificato. |
| end_update() | Termina la memorizzazione nella cache delle operazioni grafiche avviate dopo la chiamata a BeginUpdate. Le operazioni grafiche precedenti verranno applicate immediatamente quando si chiama questo metodo. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento e la tensione specificate. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento e la tensione specificate. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Riempie l'interno di un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) e due linee radiali. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) e due linee radiali. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/psd/python-net/aspose.psd/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/psd/python-net/aspose.psd/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento specificata. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento specificata. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Riempie l'interno di un rettangolo specificato da una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Riempie l'interno di un rettangolo specificato da una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Riempie gli interni di una serie di rettangoli specificati da strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Riempie gli interni di una serie di rettangoli specificati da strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Riempie l'interno di un [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Moltiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) che rappresenta la trasformazione geometrica locale di questo [Graphics](/psd/python-net/aspose.psd/graphics/) per la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata, anteponendo la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Moltiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) che rappresenta la trasformazione geometrica locale di questo [Graphics](/psd/python-net/aspose.psd/graphics/) per la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata, nell'ordine specificato. |
| reset_transform() | Reimposta la proprietà [Graphics.transform](/psd/python-net/aspose.psd/graphics/) all'identità. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Ruota la trasformazione geometrica locale dell'importo specificato. Questo metodo antepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Ruota la trasformazione geometrica locale dell'importo specificato nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Scala la trasformazione geometrica locale degli importi specificati. Questo metodo antepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Scala la trasformazione geometrica locale degli importi specificati nell'ordine specificato. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Inizializza una nuova istanza della classe [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine di origine. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Cancella la superficie grafica usando il colore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Il colore con cui cancellare la superficie grafica. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che definisce i confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro <paramref name="startAngle" /> al punto finale dell'arco. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che definisce i confini dell'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro <paramref name="startAngle" /> al punto finale dell'arco. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| width | float | Larghezza del rettangolo che definisce l'ellisse. |
| altezza | float | Altezza del rettangolo che definisce l'ellisse. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro <paramref name="startAngle" /> al punto finale dell'arco. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna un arco che rappresenta una porzione di un'ellisse specificata da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dell'arco. |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo che definisce l'ellisse. |
| width | int | Larghezza del rettangolo che definisce l'ellisse. |
| altezza | int | Altezza del rettangolo che definisce l'ellisse. |
| start_angle | int | Angolo in gradi misurato in senso orario dall'asse x al punto di partenza dell'arco. |
| sweep_angle | int | Angolo in gradi misurato in senso orario dal parametro <paramref name="startAngle" /> al punto finale dell'arco. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Disegna una spline Bézier definita da quattro strutture [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della curva. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che rappresenta il punto di partenza della curva. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che rappresenta il primo punto di controllo della curva. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che rappresenta il secondo punto di controllo della curva. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che rappresenta il punto finale della curva. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Disegna una spline Bézier definita da quattro strutture [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della curva. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che rappresenta il punto di partenza della curva. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che rappresenta il primo punto di controllo della curva. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che rappresenta il secondo punto di controllo della curva. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che rappresenta il punto finale della curva. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Disegna una spline Bézier definita da quattro coppie ordinate di coordinate che rappresentano punti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della curva. |
| x1 | float | La coordinata x del punto di partenza della curva. |
| y1 | float | La coordinata y del punto di partenza della curva. |
| x2 | float | La coordinata x del primo punto di controllo della curva. |
| y2 | float | La coordinata y del primo punto di controllo della curva. |
| x3 | float | La coordinata x del secondo punto di controllo della curva. |
| y3 | float | La coordinata y del secondo punto di controllo della curva. |
| x4 | float | La coordinata x del punto finale della curva. |
| y4 | float | La coordinata y del punto finale della curva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Disegna una serie di spline Bézier da un array di strutture [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [Point](/psd/python-net/aspose.psd/point/) che rappresentano i punti che determinano la curva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Disegna una serie di spline Bézier da un array di strutture [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [Point](/psd/python-net/aspose.psd/point/) che rappresentano i punti che determinano la curva. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Disegna una spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Disegna una spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Disegna una spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Disegna una spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. Questo metodo utilizza la modalità di riempimento predefinita [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Il disegno inizia con uno scostamento dall'inizio dell'array.<br/>            Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| offset | int | Offset dal primo elemento nell'array del parametro <paramref name="points" /> al punto di partenza della curva. |
| number_of_segments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno scostamento dall'inizio dell'array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| offset | int | Offset dal primo elemento nell'array del parametro <paramref name="points" /> al punto di partenza della curva. |
| number_of_segments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata. Il disegno inizia con uno scostamento dall'inizio dell'array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| offset | int | Offset dal primo elemento nell'array del parametro <paramref name="points" /> al punto di partenza della curva. |
| number_of_segments | int | Numero di segmenti dopo il punto di partenza da includere nella curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che definiscono la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Disegna una spline cardinale attraverso un array specificato di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando una tensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e l'altezza della curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che definiscono la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Disegna un'ellisse definita da un rettangolo di delimitazione [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che definisce i confini dell'ellisse. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Disegna un'ellisse definita da un rettangolo di delimitazione [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che definisce i confini dell'ellisse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| altezza | float | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Disegna un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, un'altezza e una larghezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dell'ellisse. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| altezza | int | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da disegnare. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array di tre strutture PointF che definiscono un parallelogramma. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da disegnare. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di tre strutture PointF che definiscono un parallelogramma. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da disegnare. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di origine. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da disegnare. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di origine. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da disegnare. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Le unità di misura. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da disegnare. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Le unità di misura. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da disegnare. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Le unità di misura. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Disegna la porzione specificata dell'elemento <paramref name=\"image\" /> specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da disegnare. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di tre strutture PointF che definiscono un parallelogramma. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di origine. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Le unità di misura. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Struttura [PointF](/psd/python-net/aspose.psd/pointf/) che rappresenta l'angolo in alto a sinistra dell'immagine disegnata. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| point | [Point](/psd/python-net/aspose.psd/point) | Struttura [PointF](/psd/python-net/aspose.psd/pointf/) che rappresenta l'angolo in alto a sinistra dell'immagine disegnata. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che specifica la posizione e le dimensioni dell'immagine disegnata. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che specifica la posizione e le dimensioni dell'immagine disegnata. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unità grafica. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unità grafica. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unità grafica. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unità grafica. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di origine. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unità grafica. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di origine. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unità grafica. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di origine. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unità grafica. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di origine. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo di destinazione. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unità grafica. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Gli attributi dell'immagine. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| x | float | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | float | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato, usando la sua dimensione fisica originale, nella posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| x | float | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | float | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |
| width | float | Larghezza dell'immagine disegnata. |
| altezza | float | Altezza dell'immagine disegnata. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Disegna l'[Graphics.image](/psd/python-net/aspose.psd/graphics/) specificato nella posizione specificata e con le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |
| width | int | Larghezza dell'immagine disegnata. |
| altezza | int | Altezza dell'immagine disegnata. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struttura che specifica l'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) che specifica l'angolo superiore sinistro dell'immagine disegnata. Le proprietà X e Y del rettangolo specificano l'angolo superiore sinistro. Le proprietà Width e Height sono ignorate. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Disegna l'immagine specificata usando la sua dimensione fisica originale nella posizione specificata da una coppia di coordinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Disegna un'immagine specificata usando la sua dimensione fisica originale in una posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| x | int | La coordinata x dell'angolo superiore sinistro dell'immagine disegnata. |
| y | int | La coordinata y dell'angolo superiore sinistro dell'immagine disegnata. |
| width | int | Il parametro non è utilizzato. |
| altezza | int | Il parametro non è utilizzato. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Disegna l'immagine specificata senza ridimensionamento e la ritaglia, se necessario, per adattarla al rettangolo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'immagine con cui disegnare. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il [Rectangle](/psd/python-net/aspose.psd/rectangle/) in cui disegnare l'immagine. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Disegna una linea che collega due strutture [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della linea. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struttura che rappresenta il primo punto da collegare. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struttura che rappresenta il secondo punto da collegare. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Disegna una linea che collega due strutture [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della linea. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) struttura che rappresenta il primo punto da collegare. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) struttura che rappresenta il secondo punto da collegare. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Disegna una linea che collega i due punti specificati dalle coppie di coordinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della linea. |
| x1 | int | La coordinata x del primo punto. |
| y1 | int | La coordinata y del primo punto. |
| x2 | int | La coordinata x del secondo punto. |
| y2 | int | La coordinata y del secondo punto. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Disegna una linea che collega i due punti specificati dalle coppie di coordinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della linea. |
| x1 | float | La coordinata x del primo punto. |
| y1 | float | La coordinata y del primo punto. |
| x2 | float | La coordinata x del secondo punto. |
| y2 | float | La coordinata y del secondo punto. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Disegna una serie di segmenti di linea che collegano un array di strutture [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [Point](/psd/python-net/aspose.psd/point/) che rappresentano i punti da collegare. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Disegna una serie di segmenti di linea che collegano un array di strutture [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dei segmenti di linea. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [Point](/psd/python-net/aspose.psd/point/) che rappresentano i punti da collegare. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Disegna un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile del percorso. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) da disegnare. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro <paramref name="startAngle" /> al secondo lato della forma a torta. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro <paramref name="startAngle" /> al secondo lato della forma a torta. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| altezza | float | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | float | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | float | Angolo misurato in gradi in senso orario dal parametro <paramref name="startAngle" /> al secondo lato della forma a torta. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Disegna una forma a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile della forma a torta. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| altezza | int | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la forma a torta. |
| start_angle | int | Angolo misurato in gradi in senso orario dall'asse x al primo lato della forma a torta. |
| sweep_angle | int | Angolo misurato in gradi in senso orario dal parametro <paramref name="startAngle" /> al secondo lato della forma a torta. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Disegna un poligono definito da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile del poligono. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i vertici del poligono. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Disegna un poligono definito da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile del poligono. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i vertici del poligono. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Disegna un rettangolo specificato da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che rappresenta il rettangolo da disegnare. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Disegna un rettangolo specificato da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che rappresenta il rettangolo da disegnare. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | float | La larghezza del rettangolo da disegnare. |
| altezza | float | L'altezza del rettangolo da disegnare. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Disegna un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile del rettangolo. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo da disegnare. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo da disegnare. |
| width | int | La larghezza del rettangolo da disegnare. |
| altezza | int | L'altezza del rettangolo da disegnare. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Disegna una serie di rettangoli specificati da strutture [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array di strutture [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresentano i rettangoli da disegnare. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Disegna una serie di rettangoli specificati da strutture [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) che determina il colore, la larghezza e lo stile dei contorni dei rettangoli. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array di strutture [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresentano i rettangoli da disegnare. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina il colore e la trama del testo disegnato. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che specifica la posizione del testo disegnato. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Disegna la stringa di testo specificata nel rettangolo specificato con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/psd/python-net/aspose.psd/stringformat/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina il colore e la trama del testo disegnato. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struttura che specifica la posizione del testo disegnato. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Disegna la stringa di testo specificata alla posizione specificata con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina il colore e la trama del testo disegnato. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che specifica l'angolo in alto a sinistra del testo disegnato. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Disegna la stringa di testo specificata alla posizione specificata con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/psd/python-net/aspose.psd/stringformat/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina il colore e la trama del testo disegnato. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struttura che specifica l'angolo in alto a sinistra del testo disegnato. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Disegna la stringa di testo specificata alla posizione specificata con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina il colore e la trama del testo disegnato. |
| x | float | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | float | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Disegna la stringa di testo specificata alla posizione specificata con gli oggetti [Brush](/psd/python-net/aspose.psd/brush/) e [Font](/psd/python-net/aspose.psd/font/) specificati, utilizzando gli attributi di formattazione del [StringFormat](/psd/python-net/aspose.psd/stringformat/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Stringa da disegnare. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) che definisce il formato del testo della stringa. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina il colore e la trama del testo disegnato. |
| x | float | La coordinata x dell'angolo in alto a sinistra del testo disegnato. |
| y | float | La coordinata y dell'angolo in alto a sinistra del testo disegnato. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/). Questo metodo utilizza una tensione predefinita di 0.5 e la modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membro dell'enumerazione [FillMode](/psd/python-net/aspose.psd/fillmode/) che determina come viene riempita la curva. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento specificata. Questo metodo utilizza una tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membro dell'enumerazione [FillMode](/psd/python-net/aspose.psd/fillmode/) che determina come viene riempita la curva. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento e la tensione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membro dell'enumerazione [FillMode](/psd/python-net/aspose.psd/fillmode/) che determina come viene riempita la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Riempie l'interno di una curva spline cardinale chiusa definita da un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento e la tensione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono lo spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membro dell'enumerazione [FillMode](/psd/python-net/aspose.psd/fillmode/) che determina come viene riempita la curva. |
| tensione | float | Valore maggiore o uguale a 0.0F che specifica la tensione della curva. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | float | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| altezza | float | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Riempie l'interno di un'ellisse definita da un rettangolo di delimitazione specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| y | int | La coordinata y dell'angolo in alto a sinistra del rettangolo di delimitazione che definisce l'ellisse. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse. |
| altezza | int | Altezza del rettangolo di delimitazione che definisce l'ellisse. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Riempie l'interno di un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che rappresenta il percorso da riempire. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro <paramref name=\"startAngle\" /> al secondo lato della sezione a torta. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresenta il rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro <paramref name=\"startAngle\" /> al secondo lato della sezione a torta. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| width | float | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| altezza | float | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | float | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | float | Angolo in gradi misurato in senso orario dal parametro <paramref name=\"startAngle\" /> al secondo lato della sezione a torta. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Riempie l'interno di una sezione a torta definita da un'ellisse specificata da una coppia di coordinate, una larghezza, un'altezza e due linee radiali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| width | int | Larghezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| altezza | int | Altezza del rettangolo di delimitazione che definisce l'ellisse da cui proviene la sezione a torta. |
| start_angle | int | Angolo in gradi misurato in senso orario dall'asse x al primo lato della sezione a torta. |
| sweep_angle | int | Angolo in gradi misurato in senso orario dal parametro <paramref name=\"startAngle\" /> al secondo lato della sezione a torta. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/psd/python-net/aspose.psd/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i vertici del poligono da riempire. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/psd/python-net/aspose.psd/pointf/) e dalla modalità di riempimento [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i vertici del poligono da riempire. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i vertici del poligono da riempire. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membro dell'enumerazione [FillMode](/psd/python-net/aspose.psd/fillmode/) che determina lo stile del riempimento. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Riempie l'interno di un poligono definito da un array di punti specificati da strutture [PointF](/psd/python-net/aspose.psd/pointf/) utilizzando la modalità di riempimento specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i vertici del poligono da riempire. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membro dell'enumerazione [FillMode](/psd/python-net/aspose.psd/fillmode/) che determina lo stile del riempimento. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Riempie l'interno di un rettangolo specificato da una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresenta il rettangolo da riempire. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Riempie l'interno di un rettangolo specificato da una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresenta il rettangolo da riempire. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo da riempire. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo da riempire. |
| width | float | Larghezza del rettangolo da riempire. |
| altezza | float | Altezza del rettangolo da riempire. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Riempie l'interno di un rettangolo specificato da una coppia di coordinate, una larghezza e un'altezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo da riempire. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo da riempire. |
| width | int | Larghezza del rettangolo da riempire. |
| altezza | int | Altezza del rettangolo da riempire. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Riempie gli interni di una serie di rettangoli specificati da strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array di strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresentano i rettangoli da riempire. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Riempie gli interni di una serie di rettangoli specificati da strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array di strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresentano i rettangoli da riempire. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Riempie l'interno di un [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) che determina le caratteristiche del riempimento. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) che rappresenta l'area da riempire. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Moltiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) che rappresenta la trasformazione geometrica locale di questo [Graphics](/psd/python-net/aspose.psd/graphics/) per la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata, anteponendo la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) con cui moltiplicare la trasformazione geometrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Moltiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) che rappresenta la trasformazione geometrica locale di questo [Graphics](/psd/python-net/aspose.psd/graphics/) per la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata, nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) con cui moltiplicare la trasformazione geometrica. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) che specifica in quale ordine moltiplicare le due matrici. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale dell'importo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale dell'importo specificato nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo di rotazione. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) che specifica se aggiungere o anteporre la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale degli importi specificati. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | La quantità con cui scalare la trasformazione nella direzione dell'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Scala la trasformazione geometrica locale degli importi specificati nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | La quantità con cui scalare la trasformazione nella direzione dell'asse y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) che specifica se aggiungere o anteporre la matrice di scala. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traduzione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traduzione in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordine (anteporre o aggiungere) con cui applicare la traduzione. |

