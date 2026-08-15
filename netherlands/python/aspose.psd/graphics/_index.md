---
title: "Graphics-klasse"
type: docs
weight: 1550
url: /nl/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initialiseert een nieuw exemplaar van de klasse [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Haalt op of stelt de clipregio in. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Haalt op of stelt de compositie‑kwaliteit in. |
| dpi_x | float | r | Haalt de horizontale resolutie van deze Aspose.PSD.Graphics op. |
| dpi_y | float | r | Haalt de verticale resolutie van deze Aspose.PSD.Graphics op. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Haalt de afbeelding op. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Haalt de interpolatiemodus op of stelt deze in. |
| is_in_begin_update_call | bool | r | Haalt een waarde op die aangeeft of graphics zich in de BeginUpdate‑aanroepstatus bevindt. |
| page_scale | float | r/w | Haalt op of stelt de schaal tussen wereld‑eenheden en pagina‑eenheden voor deze Aspose.PSD.Graphics in. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Haalt op of stelt de meeteenheid in die wordt gebruikt voor paginacoördinaten in deze Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Haalt op of stelt afbeeldingsopties in, gebruikt om schilderbare vector‑afbeeldingen te maken om te tekenen. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Geeft of stelt de anti-aliasingmodus in. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Haalt of stelt de hint voor tekstweergave in. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Haalt op of stelt een kopie van de geometrische wereldtransformatie voor deze [Graphics](/psd/python-net/aspose.psd/graphics/) in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| begin_update() | Start de caching van de volgende graphics‑bewerkingen. De graphics‑effecten die daarna worden toegepast, worden niet onmiddellijk toegepast; in plaats daarvan zorgt EndUpdate ervoor dat alle effecten in één keer worden toegepast. |
| [clear(color)](#clear_color_1) | Wist het graphics‑oppervlak met de opgegeven kleur. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-structuur. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-structuur. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een paar coördinaten, een breedte en een hoogte. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Tekent een Bézier‑spline gedefinieerd door vier [PointF](/psd/python-net/aspose.psd/pointf/)-structuren. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Tekent een Bézier‑spline gedefinieerd door vier [PointF](/psd/python-net/aspose.psd/pointf/)-structuren. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Tekent een Bézier‑spline gedefinieerd door vier geordende paren coördinaten die punten vertegenwoordigen. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Tekent een reeks Bézier‑splines uit een array van [Point](/psd/python-net/aspose.psd/point/)-structuren. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Tekent een reeks Bézier‑splines uit een array van [Point](/psd/python-net/aspose.psd/point/)-structuren. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Tekent een gesloten kardinale spline gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0.5 en [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Tekent een gesloten kardinale spline gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0.5 en [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Tekent een gesloten kardinale spline gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. Deze methode gebruikt een standaard [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Tekent een gesloten kardinale spline gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. Deze methode gebruikt een standaard [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus. |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Het tekenen begint met een offset vanaf het begin van de array.<br/>            Deze methode gebruikt een standaard spanning van 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. Het tekenen begint met een offset vanaf het begin van de array. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. Het tekenen begint met een offset vanaf het begin van de array. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Tekent een ellips gedefinieerd door een begrenzende [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Tekent een ellips gedefinieerd door een begrenzende [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/), met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/), met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/), met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/), met de oorspronkelijke fysieke grootte, op de opgegeven locatie. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Tekent de opgegeven afbeelding met de oorspronkelijke fysieke grootte op de locatie gespecificeerd door een coördinatenpaar. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Tekent de opgegeven afbeelding zonder schalen en knipt deze, indien nodig, bij om te passen in de opgegeven rechthoek. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Tekent een lijn die twee [Point](/psd/python-net/aspose.psd/point/) structuren verbindt. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Tekent een lijn die twee [Point](/psd/python-net/aspose.psd/point/) structuren verbindt. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Tekent een lijn die de twee punten verbindt die gespecificeerd zijn door de coördinatenparen. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Tekent een lijn die de twee punten verbindt die gespecificeerd zijn door de coördinatenparen. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Tekent een reeks lijnsegmenten die een array van [Point](/psd/python-net/aspose.psd/point/) structuren verbinden. |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Tekent een reeks lijnsegmenten die een array van [Point](/psd/python-net/aspose.psd/point/) structuren verbinden. |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Tekent een [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur en twee radiale lijnen. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur en twee radiale lijnen. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Tekent een veelhoek gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Tekent een veelhoek gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Tekent een rechthoek gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Tekent een rechthoek gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Tekent een reeks rechthoeken gespecificeerd door [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuren. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Tekent een reeks rechthoeken gespecificeerd door [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuren. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Tekent de opgegeven tekstreeks in de opgegeven rechthoek met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Tekent de opgegeven tekenreeks in het opgegeven rechthoek met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten, gebruikmakend van de opmaak‑attributen van de opgegeven [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten, gebruikmakend van de opmaak‑attributen van de opgegeven [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten, gebruikmakend van de opmaak‑attributen van de opgegeven [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | Rondt het cachen van de grafische bewerkingen af die zijn gestart nadat BeginUpdate is aangeroepen. De voorgaande grafische bewerkingen worden in één keer toegepast bij het aanroepen van deze methode. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0,5 en de [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0,5 en de [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus. Deze methode gebruikt een standaard spanning van 0,5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus. Deze methode gebruikt een standaard spanning van 0,5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus en spanning. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus en spanning. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Vult het binnenste van een ellips, gedefinieerd door een begrenzende rechthoek opgegeven door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Vult het binnenste van een ellips, gedefinieerd door een begrenzende rechthoek opgegeven door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Vult het binnenste van een ellips, gedefinieerd door een begrenzende rechthoek opgegeven door een paar coördinaten, een breedte en een hoogte. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Vult het binnenste van een ellips, gedefinieerd door een begrenzende rechthoek opgegeven door een paar coördinaten, een breedte en een hoogte. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Vult het binnenste van een [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Vult het binnenste van een taartsegment, gedefinieerd door een ellips opgegeven door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur en twee radiale lijnen. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Vult het binnenste van een taartsegment, gedefinieerd door een ellips opgegeven door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur en twee radiale lijnen. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Vult het binnenste van een taartsegment, gedefinieerd door een ellips opgegeven door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Vult het binnenste van een taartsegment, gedefinieerd door een ellips opgegeven door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Vult het binnenste van een veelhoek, gedefinieerd door een array van punten opgegeven door [PointF](/psd/python-net/aspose.psd/pointf/) structuren en [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Vult het binnenste van een veelhoek, gedefinieerd door een array van punten opgegeven door [PointF](/psd/python-net/aspose.psd/pointf/) structuren en [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Vult het binnenste van een veelhoek, gedefinieerd door een array van punten opgegeven door [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Vult het binnenste van een veelhoek, gedefinieerd door een array van punten opgegeven door [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Vult het binnenste van een rechthoek, opgegeven door een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Vult het binnenste van een rechthoek, opgegeven door een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Vult het binnenste van een rechthoek, opgegeven door een paar coördinaten, een breedte en een hoogte. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Vult het binnenste van een rechthoek, opgegeven door een paar coördinaten, een breedte en een hoogte. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Vult de binnenkanten van een reeks rechthoeken, opgegeven door [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Vult de binnenkanten van een reeks rechthoeken, opgegeven door [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren. |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Vult het binnenste van een [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [Graphics](/psd/python-net/aspose.psd/graphics/) vertegenwoordigt met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) door de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) voor te voegen. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [Graphics](/psd/python-net/aspose.psd/graphics/) vertegenwoordigt met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) in de opgegeven volgorde. |
| reset_transform() | Stelt de [Graphics.transform](/psd/python-net/aspose.psd/graphics/) eigenschap in op de identiteit. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode plaatst de rotatie vóór de transformatie. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Schaalt de lokale geometrische transformatie met de opgegeven waarden. Deze methode plaatst de schaalmatrix vóór de transformatie. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Schaalt de lokale geometrische transformatie met de opgegeven waarden in de opgegeven volgorde. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initialiseert een nieuw exemplaar van de klasse [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De bronafbeelding. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Wist het graphics‑oppervlak met de opgegeven kleur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | De kleur waarmee het grafische oppervlak wordt gewist. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de boog bepaalt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de grenzen van de ellips definieert. |
| start_angle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot het startpunt van de boog. |
| sweep_angle | float | Hoek in graden gemeten met de klok mee vanaf de <paramref name="startAngle" /> parameter tot het eindpunt van de boog. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/)-structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de boog bepaalt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de grenzen van de ellips definieert. |
| start_angle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot het startpunt van de boog. |
| sweep_angle | float | Hoek in graden gemeten met de klok mee vanaf de <paramref name="startAngle" /> parameter tot het eindpunt van de boog. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een paar coördinaten, een breedte en een hoogte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de boog bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert. |
| y | float | De y-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert. |
| width | float | Breedte van de rechthoek die de ellips definieert. |
| hoogte | float | Hoogte van de rechthoek die de ellips definieert. |
| start_angle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot het startpunt van de boog. |
| sweep_angle | float | Hoek in graden gemeten met de klok mee vanaf de <paramref name="startAngle" /> parameter tot het eindpunt van de boog. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Tekent een boog die een deel van een ellips weergeeft, gespecificeerd door een paar coördinaten, een breedte en een hoogte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de boog bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert. |
| y | int | De y-coördinaat van de linkerbovenhoek van de rechthoek die de ellips definieert. |
| width | int | Breedte van de rechthoek die de ellips definieert. |
| hoogte | int | Hoogte van de rechthoek die de ellips definieert. |
| start_angle | int | Hoek in graden gemeten met de klok mee vanaf de x-as tot het startpunt van de boog. |
| sweep_angle | int | Hoek in graden gemeten met de klok mee vanaf de <paramref name="startAngle" /> parameter tot het eindpunt van de boog. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Tekent een Bézier‑spline gedefinieerd door vier [PointF](/psd/python-net/aspose.psd/pointf/)-structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de curve bepaalt. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die het startpunt van de curve vertegenwoordigt. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die het eerste controlepunt voor de curve vertegenwoordigt. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die het tweede controlepunt voor de curve vertegenwoordigt. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die het eindpunt van de curve vertegenwoordigt. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Tekent een Bézier‑spline gedefinieerd door vier [PointF](/psd/python-net/aspose.psd/pointf/)-structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de curve bepaalt. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die het startpunt van de curve vertegenwoordigt. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die het eerste controlepunt voor de curve vertegenwoordigt. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die het tweede controlepunt voor de curve vertegenwoordigt. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die het eindpunt van de curve vertegenwoordigt. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Tekent een Bézier‑spline gedefinieerd door vier geordende paren coördinaten die punten vertegenwoordigen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de curve bepaalt. |
| x1 | float | De x-coördinaat van het startpunt van de curve. |
| y1 | float | De y-coördinaat van het startpunt van de curve. |
| x2 | float | De x-coördinaat van het eerste controlepunt van de curve. |
| y2 | float | De y-coördinaat van het eerste controlepunt van de curve. |
| x3 | float | De x-coördinaat van het tweede controlepunt van de curve. |
| y3 | float | De y-coördinaat van het tweede controlepunt van de curve. |
| x4 | float | De x-coördinaat van het eindpunt van de curve. |
| y4 | float | De y-coördinaat van het eindpunt van de curve. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Tekent een reeks Bézier‑splines uit een array van [Point](/psd/python-net/aspose.psd/point/)-structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de curve bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [Point](/psd/python-net/aspose.psd/point/) structuren die de punten vertegenwoordigen die de curve bepalen. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Tekent een reeks Bézier‑splines uit een array van [Point](/psd/python-net/aspose.psd/point/)-structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de curve bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [Point](/psd/python-net/aspose.psd/point/) structuren die de punten vertegenwoordigen die de curve bepalen. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Tekent een gesloten kardinale spline gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0.5 en [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Tekent een gesloten kardinale spline gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0.5 en [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Tekent een gesloten kardinale spline gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. Deze methode gebruikt een standaard [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Tekent een gesloten kardinale spline gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. Deze methode gebruikt een standaard [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0.5.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0.5.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Het tekenen begint met een offset vanaf het begin van de array.<br/>            Deze methode gebruikt een standaard spanning van 0.5.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| offset | int | Offset vanaf het eerste element in de array van de <paramref name="points" /> parameter naar het startpunt in de curve. |
| number_of_segments | int | Aantal segmenten na het startpunt die in de curve moeten worden opgenomen. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. Het tekenen begint met een offset vanaf het begin van de array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| offset | int | Offset vanaf het eerste element in de array van de <paramref name="points" /> parameter naar het startpunt in de curve. |
| number_of_segments | int | Aantal segmenten na het startpunt die in de curve moeten worden opgenomen. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning. Het tekenen begint met een offset vanaf het begin van de array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| offset | int | Offset vanaf het eerste element in de array van de <paramref name="points" /> parameter naar het startpunt in de curve. |
| number_of_segments | int | Aantal segmenten na het startpunt die in de curve moeten worden opgenomen. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de punten vertegenwoordigen die de curve definiëren. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Tekent een kardinale spline door een opgegeven array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren met een opgegeven spanning.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en hoogte van de curve bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de punten vertegenwoordigen die de curve definiëren. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Tekent een ellips gedefinieerd door een begrenzende [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de ellips bepaalt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de grenzen van de ellips definieert. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Tekent een ellips gedefinieerd door een begrenzende [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de ellips bepaalt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de grenzen van de ellips definieert. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de ellips bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de omvattende rechthoek die de ellips definieert. |
| y | float | De y-coördinaat van de linkerbovenhoek van de omvattende rechthoek die de ellips definieert. |
| width | float | Breedte van de omvattende rechthoek die de ellips definieert. |
| hoogte | float | Hoogte van de omvattende rechthoek die de ellips definieert. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Tekent een ellips gedefinieerd door een begrenzende rechthoek gespecificeerd door een paar coördinaten, een hoogte en een breedte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de ellips bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de omvattende rechthoek die de ellips definieert. |
| y | int | De y-coördinaat van de linkerbovenhoek van de omvattende rechthoek die de ellips definieert. |
| width | int | Breedte van de omvattende rechthoek die de ellips definieert. |
| hoogte | int | Hoogte van de omvattende rechthoek die de ellips definieert. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te tekenen. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array van drie PointF structuren die een parallellogram definiëren. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te tekenen. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van drie PointF structuren die een parallellogram definiëren. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te tekenen. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array van drie PointF structuren die een parallellogram definiëren. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bronrechthoek. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te tekenen. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van drie PointF structuren die een parallellogram definiëren. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bronrechthoek. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te tekenen. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array van drie PointF structuren die een parallellogram definiëren. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bronrechthoek. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De meeteenheden. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te tekenen. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van drie PointF structuren die een parallellogram definiëren. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bronrechthoek. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De meeteenheden. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te tekenen. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array van drie PointF structuren die een parallellogram definiëren. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bronrechthoek. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De meeteenheden. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Tekent het opgegeven gedeelte van de opgegeven <paramref name="image" /> op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te tekenen. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van drie PointF structuren die een parallellogram definiëren. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bronrechthoek. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De meeteenheden. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/), met de oorspronkelijke fysieke grootte, op de opgegeven locatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die de linkerbovenhoek van de getekende afbeelding vertegenwoordigt. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/), met de oorspronkelijke fysieke grootte, op de opgegeven locatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| point | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die de linkerbovenhoek van de getekende afbeelding vertegenwoordigt. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de locatie en grootte van de getekende afbeelding specificeert. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de locatie en grootte van de getekende afbeelding specificeert. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bestemmingsrechthoek. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De grafische eenheid. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bestemmingsrechthoek. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De grafische eenheid. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bestemmingsrechthoek. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De grafische eenheid. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bestemmingsrechthoek. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De grafische eenheid. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bronrechthoek. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bestemmingsrechthoek. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De grafische eenheid. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bronrechthoek. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bestemmingsrechthoek. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De grafische eenheid. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bronrechthoek. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bestemmingsrechthoek. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De grafische eenheid. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bronrechthoek. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De bestemmingsrechthoek. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | De grafische eenheid. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | De afbeeldingseigenschappen. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/), met de oorspronkelijke fysieke grootte, op de opgegeven locatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/), met de oorspronkelijke fysieke grootte, op de opgegeven locatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | int | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | int | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| width | float | Breedte van de getekende afbeelding. |
| hoogte | float | Hoogte van de getekende afbeelding. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Tekent de opgegeven [Graphics.image](/psd/python-net/aspose.psd/graphics/) op de opgegeven locatie en met de opgegeven grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | int | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | int | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| width | int | Breedte van de getekende afbeelding. |
| hoogte | int | Hoogte van de getekende afbeelding. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structuur die de linkerbovenhoek van de getekende afbeelding specificeert. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) die de linkerbovenhoek van de getekende afbeelding specificeert. De X- en Y-eigenschappen van de rechthoek geven de linkerbovenhoek aan. De Width- en Height-eigenschappen worden genegeerd. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Tekent de opgegeven afbeelding met de oorspronkelijke fysieke grootte op de locatie gespecificeerd door een coördinatenpaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | int | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | int | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Tekent een opgegeven afbeelding met de oorspronkelijke fysieke grootte op een opgegeven locatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| x | int | De x-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| y | int | De y-coördinaat van de linkerbovenhoek van de getekende afbeelding. |
| width | int | De parameter wordt niet gebruikt. |
| hoogte | int | De parameter wordt niet gebruikt. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Tekent de opgegeven afbeelding zonder schalen en knipt deze, indien nodig, bij om te passen in de opgegeven rechthoek.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om mee te tekenen. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [Rectangle](/psd/python-net/aspose.psd/rectangle/) waarin de afbeelding moet worden getekend. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Tekent een lijn die twee [Point](/psd/python-net/aspose.psd/point/) structuren verbindt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de lijn bepaalt. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structuur die het eerste te verbinden punt vertegenwoordigt. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structuur die het tweede te verbinden punt vertegenwoordigt. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Tekent een lijn die twee [Point](/psd/python-net/aspose.psd/point/) structuren verbindt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de lijn bepaalt. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) structuur die het eerste te verbinden punt vertegenwoordigt. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) structuur die het tweede te verbinden punt vertegenwoordigt. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Tekent een lijn die de twee punten verbindt die gespecificeerd zijn door de coördinatenparen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de lijn bepaalt. |
| x1 | int | De x-coördinaat van het eerste punt. |
| y1 | int | De y-coördinaat van het eerste punt. |
| x2 | int | De x-coördinaat van het tweede punt. |
| y2 | int | De y-coördinaat van het tweede punt. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Tekent een lijn die de twee punten verbindt die gespecificeerd zijn door de coördinatenparen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de lijn bepaalt. |
| x1 | float | De x-coördinaat van het eerste punt. |
| y1 | float | De y-coördinaat van het eerste punt. |
| x2 | float | De x-coördinaat van het tweede punt. |
| y2 | float | De y-coördinaat van het tweede punt. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Tekent een reeks lijnsegmenten die een array van [Point](/psd/python-net/aspose.psd/point/) structuren verbinden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de lijnsegmenten bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [Point](/psd/python-net/aspose.psd/point/) structuren die de te verbinden punten vertegenwoordigen. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Tekent een reeks lijnsegmenten die een array van [Point](/psd/python-net/aspose.psd/point/) structuren verbinden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de lijnsegmenten bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [Point](/psd/python-net/aspose.psd/point/) structuren die de te verbinden punten vertegenwoordigen. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Tekent een [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van het pad bepaalt. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) om te tekenen. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur en twee radiale lijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de taartvorm bepaalt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek vertegenwoordigt die de ellips definieert waaruit de taartvorm ontstaat. |
| start_angle | float | Hoek gemeten in graden met de klok mee vanaf de x-as tot de eerste zijde van de taartvorm. |
| sweep_angle | float | Hoek gemeten in graden met de klok mee vanaf de <paramref name="startAngle" /> parameter tot de tweede zijde van de taartvorm. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur en twee radiale lijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de taartvorm bepaalt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek vertegenwoordigt die de ellips definieert waaruit de taartvorm ontstaat. |
| start_angle | float | Hoek gemeten in graden met de klok mee vanaf de x-as tot de eerste zijde van de taartvorm. |
| sweep_angle | float | Hoek gemeten in graden met de klok mee vanaf de <paramref name="startAngle" /> parameter tot de tweede zijde van de taartvorm. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de taartvorm bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| y | float | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| width | float | Breedte van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| hoogte | float | Hoogte van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| start_angle | float | Hoek gemeten in graden met de klok mee vanaf de x-as tot de eerste zijde van de taartvorm. |
| sweep_angle | float | Hoek gemeten in graden met de klok mee vanaf de <paramref name="startAngle" /> parameter tot de tweede zijde van de taartvorm. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Tekent een taartvorm gedefinieerd door een ellips gespecificeerd door een coördinatenpaar, een breedte, een hoogte en twee radiale lijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de taartvorm bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| y | int | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| width | int | Breedte van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| hoogte | int | Hoogte van de begrenzende rechthoek die de ellips definieert waaruit de taartvorm ontstaat. |
| start_angle | int | Hoek gemeten in graden met de klok mee vanaf de x-as tot de eerste zijde van de taartvorm. |
| sweep_angle | int | Hoek gemeten in graden met de klok mee vanaf de <paramref name="startAngle" /> parameter tot de tweede zijde van de taartvorm. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Tekent een veelhoek gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van het veelhoek bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de hoekpunten van de veelhoek weergeven. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Tekent een veelhoek gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van het veelhoek bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de hoekpunten van de veelhoek weergeven. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Tekent een rechthoek gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Een [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de rechthoek bepaalt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de te tekenen rechthoek weergeeft. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Tekent een rechthoek gespecificeerd door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Een [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de rechthoek bepaalt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de te tekenen rechthoek weergeeft. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Een [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de rechthoek bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de te tekenen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te tekenen rechthoek. |
| width | float | De breedte van de te tekenen rechthoek. |
| hoogte | float | De hoogte van de te tekenen rechthoek. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Tekent een rechthoek gespecificeerd door een coördinatenpaar, een breedte en een hoogte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Een [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de rechthoek bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de te tekenen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te tekenen rechthoek. |
| width | int | De breedte van de te tekenen rechthoek. |
| hoogte | int | De hoogte van de te tekenen rechthoek. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Tekent een reeks rechthoeken gespecificeerd door [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de contouren van de rechthoeken bepaalt. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array van [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuren die de te tekenen rechthoeken weergeven. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Tekent een reeks rechthoeken gespecificeerd door [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) die de kleur, breedte en stijl van de contouren van de rechthoeken bepaalt. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array van [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuren die de te tekenen rechthoeken weergeven. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Tekent de opgegeven tekstreeks in de opgegeven rechthoek met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| s | string | String om te tekenen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) die het tekstformaat van de string definieert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de locatie van de getekende tekst specificeert. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Tekent de opgegeven tekenreeks in het opgegeven rechthoek met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten, gebruikmakend van de opmaak‑attributen van de opgegeven [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| s | string | String om te tekenen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) die het tekstformaat van de string definieert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de locatie van de getekende tekst specificeert. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) die opmaakkenmerken specificeert, zoals regelafstand en uitlijning, die op de getekende tekst worden toegepast. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| s | string | String om te tekenen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) die het tekstformaat van de string definieert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die de linkerbovenhoek van de getekende tekst specificeert. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten, gebruikmakend van de opmaak‑attributen van de opgegeven [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| s | string | String om te tekenen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) die het tekstformaat van de string definieert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structuur die de linkerbovenhoek van de getekende tekst specificeert. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) die opmaakkenmerken specificeert, zoals regelafstand en uitlijning, die op de getekende tekst worden toegepast. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| s | string | String om te tekenen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) die het tekstformaat van de string definieert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende tekst. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende tekst. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven [Brush](/psd/python-net/aspose.psd/brush/) en [Font](/psd/python-net/aspose.psd/font/) objecten, gebruikmakend van de opmaak‑attributen van de opgegeven [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| s | string | String om te tekenen. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) die het tekstformaat van de string definieert. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de getekende tekst. |
| y | float | De y-coördinaat van de linkerbovenhoek van de getekende tekst. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) die opmaakkenmerken specificeert, zoals regelafstand en uitlijning, die op de getekende tekst worden toegepast. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0,5 en de [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren. Deze methode gebruikt een standaard spanning van 0,5 en de [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) vulmodus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus. Deze methode gebruikt een standaard spanning van 0,5.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Lid van de [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeratie die bepaalt hoe de curve wordt gevuld. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus. Deze methode gebruikt een standaard spanning van 0,5.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Lid van de [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeratie die bepaalt hoe de curve wordt gevuld. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus en spanning.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Een [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Lid van de [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeratie die bepaalt hoe de curve wordt gevuld. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Vult het binnenste van een gesloten kardinale spline‑curve, gedefinieerd door een array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus en spanning.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Een [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de spline definiëren. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Lid van de [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeratie die bepaalt hoe de curve wordt gevuld. |
| spanning | float | Waarde groter dan of gelijk aan 0.0F die de spanning van de curve specificeert. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Vult het binnenste van een ellips, gedefinieerd door een begrenzende rechthoek opgegeven door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek vertegenwoordigt die de ellips definieert. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Vult het binnenste van een ellips, gedefinieerd door een begrenzende rechthoek opgegeven door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de begrenzende rechthoek vertegenwoordigt die de ellips definieert. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Vult het binnenste van een ellips, gedefinieerd door een begrenzende rechthoek opgegeven door een paar coördinaten, een breedte en een hoogte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de omvattende rechthoek die de ellips definieert. |
| y | float | De y-coördinaat van de linkerbovenhoek van de omvattende rechthoek die de ellips definieert. |
| width | float | Breedte van de omvattende rechthoek die de ellips definieert. |
| hoogte | float | Hoogte van de omvattende rechthoek die de ellips definieert. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Vult het binnenste van een ellips, gedefinieerd door een begrenzende rechthoek opgegeven door een paar coördinaten, een breedte en een hoogte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de omvattende rechthoek die de ellips definieert. |
| y | int | De y-coördinaat van de linkerbovenhoek van de omvattende rechthoek die de ellips definieert. |
| width | int | Breedte van de omvattende rechthoek die de ellips definieert. |
| hoogte | int | Hoogte van de omvattende rechthoek die de ellips definieert. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Vult het binnenste van een [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) die het pad vertegenwoordigt dat moet worden gevuld. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Vult het binnenste van een taartsegment, gedefinieerd door een ellips opgegeven door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur en twee radiale lijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur die de begrenzende rechthoek vertegenwoordigt die de ellips definieert waaruit het taartsegment komt. |
| start_angle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot de eerste zijde van het taartsegment. |
| sweep_angle | float | Hoek in graden gemeten met de klok mee vanaf de <paramref name="startAngle" /> parameter tot de tweede zijde van het taartsegment. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Vult het binnenste van een taartsegment, gedefinieerd door een ellips opgegeven door een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur en twee radiale lijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur die de begrenzende rechthoek vertegenwoordigt die de ellips definieert waaruit het taartsegment komt. |
| start_angle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot de eerste zijde van het taartsegment. |
| sweep_angle | float | Hoek in graden gemeten met de klok mee vanaf de <paramref name="startAngle" /> parameter tot de tweede zijde van het taartsegment. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Vult het binnenste van een taartsegment, gedefinieerd door een ellips opgegeven door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| y | float | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| width | float | Breedte van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| hoogte | float | Hoogte van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| start_angle | float | Hoek in graden gemeten met de klok mee vanaf de x-as tot de eerste zijde van het taartsegment. |
| sweep_angle | float | Hoek in graden gemeten met de klok mee vanaf de <paramref name="startAngle" /> parameter tot de tweede zijde van het taartsegment. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Vult het binnenste van een taartsegment, gedefinieerd door een ellips opgegeven door een paar coördinaten, een breedte, een hoogte en twee radiale lijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| y | int | De y-coördinaat van de linkerbovenhoek van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| width | int | Breedte van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| hoogte | int | Hoogte van de begrenzende rechthoek die de ellips definieert waaruit het taartsegment komt. |
| start_angle | int | Hoek in graden gemeten met de klok mee vanaf de x-as tot de eerste zijde van het taartsegment. |
| sweep_angle | int | Hoek in graden gemeten met de klok mee vanaf de <paramref name="startAngle" /> parameter tot de tweede zijde van het taartsegment. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Vult het binnenste van een veelhoek, gedefinieerd door een array van punten opgegeven door [PointF](/psd/python-net/aspose.psd/pointf/) structuren en [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de hoekpunten van de te vullen veelhoek vertegenwoordigen. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Vult het binnenste van een veelhoek, gedefinieerd door een array van punten opgegeven door [PointF](/psd/python-net/aspose.psd/pointf/) structuren en [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de hoekpunten van de te vullen veelhoek vertegenwoordigen. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Vult het binnenste van een veelhoek, gedefinieerd door een array van punten opgegeven door [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de hoekpunten van de te vullen veelhoek vertegenwoordigen. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Lid van de [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeratie die de stijl van de vulling bepaalt. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Vult het binnenste van een veelhoek, gedefinieerd door een array van punten opgegeven door [PointF](/psd/python-net/aspose.psd/pointf/) structuren, met de opgegeven vulmodus.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array van [PointF](/psd/python-net/aspose.psd/pointf/) structuren die de hoekpunten van de te vullen veelhoek vertegenwoordigen. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Lid van de [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeratie die de stijl van de vulling bepaalt. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Vult het binnenste van een rechthoek, opgegeven door een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur die de te vullen rechthoek vertegenwoordigt. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Vult het binnenste van een rechthoek, opgegeven door een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur die de te vullen rechthoek vertegenwoordigt. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Vult het binnenste van een rechthoek, opgegeven door een paar coördinaten, een breedte en een hoogte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| x | float | De x-coördinaat van de linkerbovenhoek van de te vullen rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de te vullen rechthoek. |
| width | float | Breedte van de te vullen rechthoek. |
| hoogte | float | Hoogte van de te vullen rechthoek. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Vult het binnenste van een rechthoek, opgegeven door een paar coördinaten, een breedte en een hoogte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| x | int | De x-coördinaat van de linkerbovenhoek van de te vullen rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de te vullen rechthoek. |
| width | int | Breedte van de te vullen rechthoek. |
| hoogte | int | Hoogte van de te vullen rechthoek. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Vult de binnenkanten van een reeks rechthoeken, opgegeven door [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array van [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren die de te vullen rechthoeken vertegenwoordigen. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Vult de binnenkanten van een reeks rechthoeken, opgegeven door [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array van [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren die de te vullen rechthoeken vertegenwoordigen. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Vult het binnenste van een [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) die de kenmerken van de vulling bepaalt. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) die het gebied vertegenwoordigt dat moet worden gevuld. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [Graphics](/psd/python-net/aspose.psd/graphics/) vertegenwoordigt met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) door de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) voor te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee de geometrische transformatie moet worden vermenigvuldigd. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Vermenigvuldigt de [Matrix](/psd/python-net/aspose.psd/matrix/) die de lokale geometrische transformatie van deze [Graphics](/psd/python-net/aspose.psd/graphics/) vertegenwoordigt met de opgegeven [Matrix](/psd/python-net/aspose.psd/matrix/) in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De [Matrix](/psd/python-net/aspose.psd/matrix/) waarmee de geometrische transformatie moet worden vermenigvuldigd. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert in welke volgorde de twee matrices moeten worden vermenigvuldigd. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid. Deze methode plaatst de rotatie vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Roteert de lokale geometrische transformatie met de opgegeven hoeveelheid in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert of de rotatiematrix moet worden toegevoegd of vooraf moet worden geplaatst. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Schaalt de lokale geometrische transformatie met de opgegeven waarden. Deze methode plaatst de schaalmatrix vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De hoeveelheid waarmee de transformatie langs de x-as moet worden geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie langs de y-as moet worden geschaald. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Schaalt de lokale geometrische transformatie met de opgegeven waarden in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sx | float | De hoeveelheid waarmee de transformatie langs de x-as moet worden geschaald. |
| sy | float | De hoeveelheid waarmee de transformatie langs de y-as moet worden geschaald. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Een [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) die specificeert of de schaalmatrix moet worden toegevoegd of vooraf moet worden geplaatst. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen. Deze methode plaatst de translatie vóór de transformatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Vertaalt de lokale geometrische transformatie met de opgegeven afmetingen in de opgegeven volgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | float | De waarde van de translatie in x. |
| dy | float | De waarde van de translatie in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | De volgorde (voorgaan of toevoegen) waarin de translatie moet worden toegepast. |

