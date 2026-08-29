---
title: "Graphics‑klass"
type: docs
weight: 1550
url: /sv/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initierar en ny instans av klassen [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Hämtar eller anger klippområdet. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Hämtar eller anger kompositkvaliteten. |
| dpi_x | float | r | Hämtar den horisontella upplösningen för denna Aspose.PSD.Graphics. |
| dpi_y | float | r | Hämtar den vertikala upplösningen för denna Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Hämtar bilden. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Hämtar eller anger interpolationsläget. |
| is_in_begin_update_call | bool | r | Hämtar ett värde som indikerar om grafik är i BeginUpdate‑anropstillstånd. |
| page_scale | float | r/w | Hämtar eller anger skalningen mellan värdenheter och sid‑enheter för denna Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Hämtar eller anger måttenheten som används för sidkoordinater i denna Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Hämtar eller anger bildalternativ som används för att skapa målbara vactor-bilder att rita. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Hämtar eller anger utjämningsläget. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Hämtar eller anger ett tips för textåtergivning. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Hämtar eller anger en kopia av den geometriska världstransformationen för detta [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| begin_update() | Startar cachning av följande grafikoperationer. Grafikeffekterna som tillämpas därefter kommer inte att tillämpas omedelbart, utan EndUpdate kommer att orsaka att alla effekter tillämpas på en gång. |
| [clear(color)](#clear_color_1) | Rensar grafikytan med den angivna färgen. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Ritar en Bézier-spline definierad av fyra [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Ritar en Bézier-spline definierad av fyra [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Ritar en Bézier-spline definierad av fyra ordnade koordinatpar som representerar punkter. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Ritar en serie av Bézier-splines från en matris av [Point](/psd/python-net/aspose.psd/point/) strukturer. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Ritar en serie av Bézier-splines från en matris av [Point](/psd/python-net/aspose.psd/point/) strukturer. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Ritar en sluten kardinal-spline definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och fyllningsläget [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Ritar en sluten kardinal-spline definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och fyllningsläget [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Ritar en sluten kardinal-spline definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. Denna metod använder standardfyllningsläget [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Ritar en sluten kardinal-spline definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. Denna metod använder standardfyllningsläget [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Ritningen börjar förskjuten från början av matrisen.<br/>            Denna metod använder en standardspänning på 0,5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. Ritningen börjar förskjuten från början av matrisen. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. Ritningen börjar förskjuten från början av matrisen. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Ritar en ellips definierad av en avgränsande [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Ritar en ellips definierad av en avgränsande [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Ritar en ellips definierad av en avgränsande rektangel specificerad av ett koordinatpar, en höjd och en bredd. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Ritar en ellips definierad av en avgränsande rektangel specificerad av ett koordinatpar, en höjd och en bredd. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/), med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/), med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/), med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/), med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Ritar den specificerade bilden med dess ursprungliga fysiska storlek på den plats som specificeras av ett koordinatpar. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Ritar den specificerade bilden utan skalning och beskär den, om nödvändigt, för att passa i den specificerade rektangeln. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Ritar en linje som förbinder två [Point](/psd/python-net/aspose.psd/point/) strukturer. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Ritar en linje som förbinder två [Point](/psd/python-net/aspose.psd/point/) strukturer. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Ritar en linje som förbinder de två punkterna som anges av koordinatparen. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Ritar en linje som förbinder de två punkterna som anges av koordinatparen. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Ritar en serie linjesegment som förbinder en matris av [Point](/psd/python-net/aspose.psd/point/) strukturer. |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Ritar en serie linjesegment som förbinder en matris av [Point](/psd/python-net/aspose.psd/point/) strukturer. |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Ritar en [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Ritar en pajform definierad av en ellips som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur och två radiala linjer. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Ritar en pajform definierad av en ellips som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur och två radiala linjer. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Ritar en pajform definierad av en ellips som anges av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Ritar en pajform definierad av en ellips som anges av ett koordinatpar, en bredd, en höjd och två radiala linjer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Ritar en polygon definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Ritar en polygon definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Ritar en rektangel som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Ritar en rektangel som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Ritar en rektangel som anges av ett koordinatpar, en bredd och en höjd. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Ritar en rektangel som anges av ett koordinatpar, en bredd och en höjd. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Ritar en serie rektanglar som anges av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturer. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Ritar en serie rektanglar som anges av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturer. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten med hjälp av formateringsattributen för den angivna [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten med hjälp av formateringsattributen för den angivna [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten med hjälp av formateringsattributen för den angivna [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | Avslutar cachning av grafikoperationerna som startades efter att BeginUpdate anropades. De föregående grafikoperationerna kommer att tillämpas på en gång när denna metod anropas. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fyllningsläge. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fyllningsläge. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget och spänningen. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget och spänningen. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Fyller insidan av en ellips definierad av en avgränsande rektangel som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Fyller insidan av en ellips definierad av en avgränsande rektangel som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Fyller insidan av en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en bredd och en höjd. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Fyller insidan av en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en bredd och en höjd. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Fyller insidan av en [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Fyller insidan av en pajsektion definierad av en ellips som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur och två radiala linjer. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Fyller insidan av en pajsektion definierad av en ellips som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur och två radiala linjer. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Fyller interiören av en pajsektion som definieras av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Fyller interiören av en pajsektion som definieras av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Fyller interiören av en polygon som definieras av en array av punkter specificerade av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer och [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Fyller interiören av en polygon som definieras av en array av punkter specificerade av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer och [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Fyller interiören av en polygon som definieras av en array av punkter specificerade av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Fyller interiören av en polygon som definieras av en array av punkter specificerade av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Fyller interiören av en rektangel som specificeras av en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Fyller interiören av en rektangel som specificeras av en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Fyller interiören av en rektangel som specificeras av ett par koordinater, en bredd och en höjd. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Fyller interiören av en rektangel som specificeras av ett par koordinater, en bredd och en höjd. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Fyller interiörerna av en serie rektanglar som specificeras av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Fyller interiörerna av en serie rektanglar som specificeras av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer. |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Fyller interiören av ett [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformen för denna [Graphics](/psd/python-net/aspose.psd/graphics/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) genom att föregå den angivna [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformen för denna [Graphics](/psd/python-net/aspose.psd/graphics/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer egenskapen [Graphics.transform](/psd/python-net/aspose.psd/graphics/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Rotera den lokala geometriska transformationen med den angivna mängden. Denna metod föregår rotationen till transformationen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod föregår skalningsmatrisen till transformationen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod föregår översättningen till transformationen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initierar en ny instans av klassen [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Källbilden. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Rensar grafikytan med den angivna färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Färgen som används för att rensa grafikytan. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för bågen. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som definierar ellipsens gränser. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern <paramref name=\"startAngle\" /> till slutpunkten för bågen. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för bågen. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som definierar ellipsens gränser. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern <paramref name=\"startAngle\" /> till slutpunkten för bågen. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för bågen. |
| x | float | X-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| y | float | Y-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| width | float | Bredden på rektangeln som definierar ellipsen. |
| height | float | Höjden på rektangeln som definierar ellipsen. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweep_angle | float | Vinkel i grader mätt medurs från parametern <paramref name=\"startAngle\" /> till slutpunkten för bågen. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en båge som representerar en del av en ellips specificerad av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för bågen. |
| x | int | X-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| y | int | Y-koordinaten för rektangelns övre vänstra hörn som definierar ellipsen. |
| width | int | Bredden på rektangeln som definierar ellipsen. |
| height | int | Höjden på rektangeln som definierar ellipsen. |
| start_angle | int | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweep_angle | int | Vinkel i grader mätt medurs från parametern <paramref name=\"startAngle\" /> till slutpunkten för bågen. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Ritar en Bézier-spline definierad av fyra [PointF](/psd/python-net/aspose.psd/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för kurvan. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar kurvans startpunkt. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar den första kontrollpunkten för kurvan. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar den andra kontrollpunkten för kurvan. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar kurvans slutpunkt. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Ritar en Bézier-spline definierad av fyra [PointF](/psd/python-net/aspose.psd/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för kurvan. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar kurvans startpunkt. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar den första kontrollpunkten för kurvan. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar den andra kontrollpunkten för kurvan. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar kurvans slutpunkt. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Ritar en Bézier-spline definierad av fyra ordnade koordinatpar som representerar punkter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för kurvan. |
| x1 | float | X-koordinaten för startpunkten på kurvan. |
| y1 | float | Y-koordinaten för startpunkten på kurvan. |
| x2 | float | X-koordinaten för den första styrpunkten på kurvan. |
| y2 | float | Y-koordinaten för den första styrpunkten på kurvan. |
| x3 | float | X-koordinaten för den andra styrpunkten på kurvan. |
| y3 | float | Y-koordinaten för den andra styrpunkten på kurvan. |
| x4 | float | X-koordinaten för slutpunkten på kurvan. |
| y4 | float | Y-koordinaten för slutpunkten på kurvan. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Ritar en serie av Bézier-splines från en matris av [Point](/psd/python-net/aspose.psd/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för kurvan. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [Point](/psd/python-net/aspose.psd/point/) strukturer som representerar de punkter som bestämmer kurvan. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Ritar en serie av Bézier-splines från en matris av [Point](/psd/python-net/aspose.psd/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för kurvan. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [Point](/psd/python-net/aspose.psd/point/) strukturer som representerar de punkter som bestämmer kurvan. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Ritar en sluten kardinal-spline definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och fyllningsläget [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Ritar en sluten kardinal-spline definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och fyllningsläget [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Ritar en sluten kardinal-spline definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. Denna metod använder standardfyllningsläget [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| spänning | float | Värde större än eller lika med 0,0F som anger spänningen i kurvan. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Ritar en sluten kardinal-spline definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. Denna metod använder standardfyllningsläget [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| spänning | float | Värde större än eller lika med 0,0F som anger spänningen i kurvan. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Ritningen börjar förskjuten från början av matrisen.<br/>            Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| offset | int | Offset från det första elementet i arrayen av <paramref name="points" />-parametern till startpunkten i kurvan. |
| number_of_segments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. Ritningen börjar förskjuten från början av matrisen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| offset | int | Offset från det första elementet i arrayen av <paramref name="points" />-parametern till startpunkten i kurvan. |
| number_of_segments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| spänning | float | Värde större än eller lika med 0,0F som anger spänningen i kurvan. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning. Ritningen börjar förskjuten från början av matrisen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| offset | int | Offset från det första elementet i arrayen av <paramref name="points" />-parametern till startpunkten i kurvan. |
| number_of_segments | int | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| spänning | float | Värde större än eller lika med 0,0F som anger spänningen i kurvan. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar de punkter som definierar kurvan. |
| spänning | float | Värde större än eller lika med 0,0F som anger spänningen i kurvan. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Ritar en kardinal-spline genom en specificerad matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med en angiven spänning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och höjd på kurvan. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar de punkter som definierar kurvan. |
| spänning | float | Värde större än eller lika med 0,0F som anger spänningen i kurvan. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Ritar en ellips definierad av en avgränsande [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för ellipsen. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som definierar ellipsens gränser. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Ritar en ellips definierad av en avgränsande [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för ellipsen. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som definierar ellipsens gränser. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Ritar en ellips definierad av en avgränsande rektangel specificerad av ett koordinatpar, en höjd och en bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för ellipsen. |
| x | float | X-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| width | float | Bredden på den avgränsande rektangeln som definierar ellipsen. |
| height | float | Höjden på den avgränsande rektangeln som definierar ellipsen. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Ritar en ellips definierad av en avgränsande rektangel specificerad av ett koordinatpar, en höjd och en bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för ellipsen. |
| x | int | X-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| width | int | Bredden på den avgränsande rektangeln som definierar ellipsen. |
| height | int | Höjden på den avgränsande rektangeln som definierar ellipsen. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska ritas. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array av tre PointF-strukturer som definierar ett parallellogram. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska ritas. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av tre PointF-strukturer som definierar ett parallellogram. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska ritas. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Källrektangeln. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska ritas. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Källrektangeln. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska ritas. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Källrektangeln. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Måttenheterna. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska ritas. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Källrektangeln. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Måttenheterna. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska ritas. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Källrektangeln. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Måttenheterna. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Bildattributen. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Ritar den angivna delen av den specificerade <paramref name="image" /> på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska ritas. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av tre PointF-strukturer som definierar ett parallellogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Källrektangeln. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Måttenheterna. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Bildattributen. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/), med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/), med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| point | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som representerar det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som specificerar platsen och storleken på den ritade bilden. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som specificerar platsen och storleken på den ritade bilden. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafikenheten. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafikenheten. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafikenheten. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Bildattributen. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Destinationsrektangeln. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafikenheten. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Bildattributen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rect-källan. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafikenheten. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Rect-källan. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafikenheten. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rect-källan. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafikenheten. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Bildattributen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Rect-källan. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Rect-destinationen. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafikenheten. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Bildattributen. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/), med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/), med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| width | float | Bredden på den ritade bilden. |
| height | float | Höjden på den ritade bilden. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Ritar den specificerade [Graphics.image](/psd/python-net/aspose.psd/graphics/) på den angivna platsen och med den angivna storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| width | int | Bredden på den ritade bilden. |
| height | int | Höjden på den ritade bilden. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struktur som specificerar det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) som specificerar det övre vänstra hörnet av den ritade bilden. X- och Y-egenskaperna för rektangeln specificerar det övre vänstra hörnet. Width- och Height-egenskaperna ignoreras. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Ritar den specificerade bilden med dess ursprungliga fysiska storlek på den plats som specificeras av ett koordinatpar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en specificerad plats.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| x | int | X-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den ritade bilden. |
| width | int | Parametern används inte. |
| height | int | Parametern används inte. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Ritar den specificerade bilden utan skalning och beskär den, om nödvändigt, för att passa i den specificerade rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Bilden att rita med. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [Rectangle](/psd/python-net/aspose.psd/rectangle/) i vilken bilden ska ritas. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Ritar en linje som förbinder två [Point](/psd/python-net/aspose.psd/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struktur som representerar den första punkten att ansluta. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struktur som representerar den andra punkten att ansluta. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Ritar en linje som förbinder två [Point](/psd/python-net/aspose.psd/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) struktur som representerar den första punkten att ansluta. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) struktur som representerar den andra punkten att ansluta. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Ritar en linje som förbinder de två punkterna som anges av koordinatparen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| x1 | int | X-koordinaten för den första punkten. |
| y1 | int | Y-koordinaten för den första punkten. |
| x2 | int | X-koordinaten för den andra punkten. |
| y2 | int | Y-koordinaten för den andra punkten. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Ritar en linje som förbinder de två punkterna som anges av koordinatparen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färgen, bredden och stilen på linjen. |
| x1 | float | X-koordinaten för den första punkten. |
| y1 | float | Y-koordinaten för den första punkten. |
| x2 | float | X-koordinaten för den andra punkten. |
| y2 | float | Y-koordinaten för den andra punkten. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Ritar en serie linjesegment som förbinder en matris av [Point](/psd/python-net/aspose.psd/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för linjesegmenten. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [Point](/psd/python-net/aspose.psd/point/) strukturer som representerar punkterna att ansluta. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Ritar en serie linjesegment som förbinder en matris av [Point](/psd/python-net/aspose.psd/point/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för linjesegmenten. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [Point](/psd/python-net/aspose.psd/point/) strukturer som representerar punkterna att ansluta. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Ritar en [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för vägen. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) att rita. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för pajformen. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från <paramref name="startAngle" />-parametern till den andra sidan av pajformen. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för pajformen. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från <paramref name="startAngle" />-parametern till den andra sidan av pajformen. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips som anges av ett koordinatpar, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för pajformen. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| height | float | Höjden på den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| start_angle | float | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | float | Vinkel mätt i grader medurs från <paramref name="startAngle" />-parametern till den andra sidan av pajformen. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Ritar en pajform definierad av en ellips som anges av ett koordinatpar, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för pajformen. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| height | int | Höjden på den omgivande rektangeln som definierar ellipsen som pajformen härrör från. |
| start_angle | int | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweep_angle | int | Vinkel mätt i grader medurs från <paramref name="startAngle" />-parametern till den andra sidan av pajformen. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Ritar en polygon definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för polygonen. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar polygonens hörn. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Ritar en polygon definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för polygonen. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar polygonens hörn. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Ritar en rektangel som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | En [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar rektangeln att rita. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Ritar en rektangel som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | En [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar rektangeln att rita. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Ritar en rektangel som anges av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | En [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln att rita. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln att rita. |
| width | float | Bredden på rektangeln att rita. |
| height | float | Höjden på rektangeln som ska ritas. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Ritar en rektangel som anges av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | En [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färg, bredd och stil för rektangeln. |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln att rita. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln att rita. |
| width | int | Bredden på rektangeln att rita. |
| height | int | Höjden på rektangeln som ska ritas. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Ritar en serie rektanglar som anges av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färgen, bredden och stilen på rektanglarnas konturer. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturer som representerar rektanglarna som ska ritas. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Ritar en serie rektanglar som anges av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) som bestämmer färgen, bredden och stilen på rektanglarnas konturer. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturer som representerar rektanglarna som ska ritas. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) som definierar textformatet för strängen. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer färgen och texturen på den ritade texten. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som specificerar platsen för den ritade texten. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Ritar den angivna textsträngen i den angivna rektangeln med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten med hjälp av formateringsattributen för den angivna [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) som definierar textformatet för strängen. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer färgen och texturen på den ritade texten. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som specificerar platsen för den ritade texten. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) som definierar textformatet för strängen. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer färgen och texturen på den ritade texten. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som specificerar det övre vänstra hörnet av den ritade texten. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten med hjälp av formateringsattributen för den angivna [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) som definierar textformatet för strängen. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer färgen och texturen på den ritade texten. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur som specificerar det övre vänstra hörnet av den ritade texten. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) som definierar textformatet för strängen. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer färgen och texturen på den ritade texten. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Ritar den angivna textsträngen på den angivna platsen med de angivna [Brush](/psd/python-net/aspose.psd/brush/) och [Font](/psd/python-net/aspose.psd/font/) objekten med hjälp av formateringsattributen för den angivna [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Sträng att rita. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) som definierar textformatet för strängen. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer färgen och texturen på den ritade texten. |
| x | float | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) som specificerar formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer. Denna metod använder en standardspänning på 0,5 och [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fyllningsläge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Medlem av [FillMode](/psd/python-net/aspose.psd/fillmode/) uppräkning som bestämmer hur kurvan fylls. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget. Denna metod använder en standardspänning på 0,5.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Medlem av [FillMode](/psd/python-net/aspose.psd/fillmode/) uppräkning som bestämmer hur kurvan fylls. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget och spänningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | En [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Medlem av [FillMode](/psd/python-net/aspose.psd/fillmode/) uppräkning som bestämmer hur kurvan fylls. |
| spänning | float | Värde större än eller lika med 0,0F som anger spänningen i kurvan. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Fyller insidan av en sluten kardinal spline-kurva definierad av en matris av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget och spänningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | En [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som definierar spline:n. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Medlem av [FillMode](/psd/python-net/aspose.psd/fillmode/) uppräkning som bestämmer hur kurvan fylls. |
| spänning | float | Värde större än eller lika med 0,0F som anger spänningen i kurvan. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Fyller insidan av en ellips definierad av en avgränsande rektangel som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Fyller insidan av en ellips definierad av en avgränsande rektangel som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar den omgivande rektangeln som definierar ellipsen. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Fyller insidan av en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| width | float | Bredden på den avgränsande rektangeln som definierar ellipsen. |
| height | float | Höjden på den avgränsande rektangeln som definierar ellipsen. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Fyller insidan av en ellips definierad av en avgränsande rektangel som anges av ett koordinatpar, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen. |
| width | int | Bredden på den avgränsande rektangeln som definierar ellipsen. |
| height | int | Höjden på den avgränsande rektangeln som definierar ellipsen. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Fyller insidan av en [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) som representerar vägen att fylla. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fyller insidan av en pajsektion definierad av en ellips som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som representerar den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från <paramref name="startAngle" />-parametern till den andra sidan av pajsektionen. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fyller insidan av en pajsektion definierad av en ellips som anges av en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som representerar den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från <paramref name="startAngle" />-parametern till den andra sidan av pajsektionen. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fyller interiören av en pajsektion som definieras av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| y | float | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| width | float | Bredden på den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| height | float | Höjden på den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| start_angle | float | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | float | Vinkel i grader mätt medurs från <paramref name="startAngle" />-parametern till den andra sidan av pajsektionen. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fyller interiören av en pajsektion som definieras av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiala linjer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| y | int | Y-koordinaten för det övre vänstra hörnet av den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| width | int | Bredden på den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| height | int | Höjden på den omgivande rektangeln som definierar ellipsen som pajsektionen kommer från. |
| start_angle | int | Vinkel i grader mätt medurs från x-axeln till den första sidan av pajsektionen. |
| sweep_angle | int | Vinkel i grader mätt medurs från <paramref name="startAngle" />-parametern till den andra sidan av pajsektionen. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Fyller interiören av en polygon som definieras av en array av punkter specificerade av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer och [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar polygonens hörn att fylla. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Fyller interiören av en polygon som definieras av en array av punkter specificerade av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer och [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar polygonens hörn att fylla. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Fyller interiören av en polygon som definieras av en array av punkter specificerade av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar polygonens hörn att fylla. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Medlem av [FillMode](/psd/python-net/aspose.psd/fillmode/)‑enumerationen som bestämmer fyllningsstilen. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Fyller interiören av en polygon som definieras av en array av punkter specificerade av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer med det angivna fyllningsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar polygonens hörn att fylla. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Medlem av [FillMode](/psd/python-net/aspose.psd/fillmode/)‑enumerationen som bestämmer fyllningsstilen. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Fyller interiören av en rektangel som specificeras av en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som representerar rektangeln att fylla. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Fyller interiören av en rektangel som specificeras av en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som representerar rektangeln att fylla. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Fyller interiören av en rektangel som specificeras av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| x | float | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| y | float | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| width | float | Bredden på rektangeln som ska fyllas. |
| height | float | Höjden på rektangeln som ska fyllas. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Fyller interiören av en rektangel som specificeras av ett par koordinater, en bredd och en höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| x | int | X‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| y | int | Y‑koordinaten för det övre vänstra hörnet av rektangeln som ska fyllas. |
| width | int | Bredden på rektangeln som ska fyllas. |
| height | int | Höjden på rektangeln som ska fyllas. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Fyller interiörerna av en serie rektanglar som specificeras av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer som representerar rektanglarna att fylla. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Fyller interiörerna av en serie rektanglar som specificeras av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer som representerar rektanglarna att fylla. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Fyller interiören av ett [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) som bestämmer fyllningens egenskaper. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) som representerar området att fylla. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformen för denna [Graphics](/psd/python-net/aspose.psd/graphics/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) genom att föregå den angivna [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Den [Matrix](/psd/python-net/aspose.psd/matrix/) som används för att multiplicera den geometriska transformen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformen för denna [Graphics](/psd/python-net/aspose.psd/graphics/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Den [Matrix](/psd/python-net/aspose.psd/matrix/) som används för att multiplicera den geometriska transformen. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Rotera den lokala geometriska transformationen med den angivna mängden. Denna metod föregår rotationen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln för rotationen. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln för rotationen. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod föregår skalningsmatrisen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden med vilken transformen ska skalas i x-axelns riktning. |
| sy | float | Mängden med vilken transformen ska skalas i y-axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden med vilken transformen ska skalas i x-axelns riktning. |
| sy | float | Mängden med vilken transformen ska skalas i y-axelns riktning. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar om skalningsmatrisen ska läggas till i slutet eller i början. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod föregår översättningen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ordningen (infoga före eller efter) i vilken translationen ska tillämpas. |

