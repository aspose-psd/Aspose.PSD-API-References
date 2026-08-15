---
title: "Clase Graphics"
type: docs
weight: 1550
url: /es/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Inicializa una nueva instancia de la clase [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Obtiene o establece la región de recorte. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Obtiene o establece la calidad de composición. |
| dpi_x | float | r | Obtiene la resolución horizontal de este Aspose.PSD.Graphics. |
| dpi_y | float | r | Obtiene la resolución vertical de este Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Obtiene la imagen. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Obtiene o establece el modo de interpolación. |
| is_in_begin_update_call | bool | r | Obtiene un valor que indica si graphics está en estado de llamada BeginUpdate. |
| page_scale | float | r/w | Obtiene o establece la escala entre unidades del mundo y unidades de página para este Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Obtiene o establece la unidad de medida utilizada para las coordenadas de página en este Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Obtiene o establece las opciones de imagen, utilizadas para crear imágenes vectoriales pintables para dibujar. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Obtiene o establece el modo de suavizado. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Obtiene o establece la sugerencia de renderizado de texto. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Obtiene o establece una copia de la transformación geométrica del mundo para este [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| begin_update() | Inicia el almacenamiento en caché de las siguientes operaciones gráficas. Los efectos gráficos aplicados después no se aplicarán inmediatamente; en su lugar, EndUpdate provocará la aplicación de todos los efectos de una vez. |
| [clear(color)](#clear_color_1) | Borra la superficie gráfica usando el color especificado. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Dibuja una spline Bézier definida por cuatro estructuras [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Dibuja una spline Bézier definida por cuatro estructuras [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Dibuja una spline Bézier definida por cuatro pares ordenados de coordenadas que representan puntos. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/psd/python-net/aspose.psd/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/psd/python-net/aspose.psd/point/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método utiliza una tensión predeterminada de 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método utiliza una tensión predeterminada de 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). El dibujo comienza desplazado desde el inicio de la matriz.<br/>            Este método utiliza una tensión predeterminada de 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Dibuja una elipse definida por un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) delimitador. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Dibuja una elipse definida por un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) delimitador. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada por un par de coordenadas. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Dibuja la imagen especificada sin escalar y la recorta, si es necesario, para ajustarla al rectángulo especificado. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Dibuja una línea que conecta dos estructuras [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Dibuja una línea que conecta dos estructuras [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [Point](/psd/python-net/aspose.psd/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [Point](/psd/python-net/aspose.psd/point/). |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Dibuja un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) y dos líneas radiales. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) y dos líneas radiales. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Dibuja un polígono definido por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Dibuja un polígono definido por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Dibuja un rectángulo especificado por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Dibuja un rectángulo especificado por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) especificados. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) usando los atributos de formato del [StringFormat](/psd/python-net/aspose.psd/stringformat/) especificado. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) especificados. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) usando los atributos de formato del [StringFormat](/psd/python-net/aspose.psd/stringformat/) especificado. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) especificados. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) usando los atributos de formato del [StringFormat](/psd/python-net/aspose.psd/stringformat/) especificado. |
| end_update() | Finaliza el almacenamiento en caché de las operaciones gráficas iniciadas después de que se llamó a BeginUpdate. Las operaciones gráficas precedentes se aplicarán de una vez al llamar a este método. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método usa una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método usa una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno especificado. Este método usa una tensión predeterminada de 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno especificado. Este método usa una tensión predeterminada de 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno y la tensión especificados. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno y la tensión especificados. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Rellena el interior de un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Rellena el interior de una sección de pastel definida por una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) y dos líneas radiales. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Rellena el interior de una sección de pastel definida por una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) y dos líneas radiales. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Rellena el interior de una sección de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Rellena el interior de una sección de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [PointF](/psd/python-net/aspose.psd/pointf/) y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [PointF](/psd/python-net/aspose.psd/pointf/) y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno especificado. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno especificado. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Rellena el interior de un rectángulo especificado por una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Rellena el interior de un rectángulo especificado por una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Rellena los interiores de una serie de rectángulos especificados por estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Rellena los interiores de una serie de rectángulos especificados por estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Rellena el interior de una [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Multiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) que representa la transformación geométrica local de este [Graphics](/psd/python-net/aspose.psd/graphics/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada, anteponiendo la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Multiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) que representa la transformación geométrica local de este [Graphics](/psd/python-net/aspose.psd/graphics/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada en el orden especificado. |
| reset_transform() | Restablece la propiedad [Graphics.transform](/psd/python-net/aspose.psd/graphics/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Rota la transformación geométrica local en la cantidad especificada en el orden especificado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Escala la transformación geométrica local en las cantidades especificadas en el orden especificado. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Traslada la transformación geométrica local en las dimensiones especificadas en el orden especificado. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Inicializa una nueva instancia de la clase [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen de origen. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Borra la superficie gráfica usando el color especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | El color para borrar la superficie gráfica. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del arco. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que define los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el punto final del arco. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del arco. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que define los límites de la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el punto final del arco. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del arco. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| width | float | Ancho del rectángulo que define la elipse. |
| altura | float | Altura del rectángulo que define la elipse. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el punto final del arco. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del arco. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| width | int | Ancho del rectángulo que define la elipse. |
| altura | int | Altura del rectángulo que define la elipse. |
| start_angle | int | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweep_angle | int | Ángulo en grados medido en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el punto final del arco. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dibuja una spline Bézier definida por cuatro estructuras [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la curva. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que representa el punto inicial de la curva. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que representa el primer punto de control de la curva. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que representa el segundo punto de control de la curva. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que representa el punto final de la curva. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dibuja una spline Bézier definida por cuatro estructuras [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la curva. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que representa el punto inicial de la curva. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que representa el primer punto de control de la curva. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que representa el segundo punto de control de la curva. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que representa el punto final de la curva. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Dibuja una spline Bézier definida por cuatro pares ordenados de coordenadas que representan puntos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la curva. |
| x1 | float | La coordenada x del punto inicial de la curva. |
| y1 | float | La coordenada y del punto inicial de la curva. |
| x2 | float | La coordenada x del primer punto de control de la curva. |
| y2 | float | La coordenada y del primer punto de control de la curva. |
| x3 | float | La coordenada x del segundo punto de control de la curva. |
| y3 | float | La coordenada y del segundo punto de control de la curva. |
| x4 | float | La coordenada x del punto final de la curva. |
| y4 | float | La coordenada y del punto final de la curva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [Point](/psd/python-net/aspose.psd/point/) que representan los puntos que determinan la curva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Dibuja una serie de splines Bézier a partir de una matriz de estructuras [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [Point](/psd/python-net/aspose.psd/point/) que representan los puntos que determinan la curva. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método utiliza una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Dibuja una spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. Este método utiliza el modo de relleno predeterminado [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). El dibujo comienza desplazado desde el inicio de la matriz.<br/>            Este método utiliza una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en la matriz del parámetro <paramref name="points" /> al punto inicial en la curva. |
| number_of_segments | int | Número de segmentos después del punto inicial que se incluyen en la curva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en la matriz del parámetro <paramref name="points" /> al punto inicial en la curva. |
| number_of_segments | int | Número de segmentos después del punto inicial que se incluyen en la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada. El dibujo comienza desplazado desde el inicio de la matriz.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| offset | int | Desplazamiento desde el primer elemento en la matriz del parámetro <paramref name="points" /> al punto inicial en la curva. |
| number_of_segments | int | Número de segmentos después del punto inicial que se incluyen en la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representan los puntos que definen la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Dibuja una spline cardinal a través de una matriz especificada de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando una tensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y la altura de la curva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representan los puntos que definen la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Dibuja una elipse definida por un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la elipse. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que define los límites de la elipse. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Dibuja una elipse definida por un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) delimitador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la elipse. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que define los límites de la elipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la elipse. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | float | Ancho del rectángulo delimitador que define la elipse. |
| altura | float | Altura del rectángulo delimitador que define la elipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Dibuja una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, una altura y un ancho.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la elipse. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | int | Ancho del rectángulo delimitador que define la elipse. |
| altura | int | Altura del rectángulo delimitador que define la elipse. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a dibujar. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de tres estructuras PointF que definen un paralelogramo. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a dibujar. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de tres estructuras PointF que definen un paralelogramo. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a dibujar. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de origen. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a dibujar. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo de origen. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a dibujar. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Las unidades de medida. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a dibujar. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Las unidades de medida. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a dibujar. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Las unidades de medida. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Los atributos de la imagen. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dibuja la porción especificada del <paramref name=\"image\" /> especificado en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a dibujar. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de tres estructuras PointF que definen un paralelogramo. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo de origen. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Las unidades de medida. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Los atributos de la imagen. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Estructura [PointF](/psd/python-net/aspose.psd/pointf/) que representa la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| point | [Point](/psd/python-net/aspose.psd/point) | Estructura [PointF](/psd/python-net/aspose.psd/pointf/) que representa la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que especifica la ubicación y el tamaño de la imagen dibujada. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que especifica la ubicación y el tamaño de la imagen dibujada. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | La unidad de gráficos. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | La unidad de gráficos. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | La unidad de gráficos. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Los atributos de la imagen. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El rectángulo de destino. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | La unidad de gráficos. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Los atributos de la imagen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El origen del rectángulo. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El destino del rectángulo. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | La unidad de gráficos. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El origen del rectángulo. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El destino del rectángulo. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | La unidad de gráficos. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El origen del rectángulo. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El destino del rectángulo. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | La unidad de gráficos. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Los atributos de la imagen. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El origen del rectángulo. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | El destino del rectángulo. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | La unidad de gráficos. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Los atributos de la imagen. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| x | float | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | float | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada, usando su tamaño físico original, en la ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| x | float | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | float | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| width | float | Ancho de la imagen dibujada. |
| altura | float | Altura de la imagen dibujada. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Dibuja la [Graphics.image](/psd/python-net/aspose.psd/graphics/) especificada en la ubicación especificada y con el tamaño especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| width | int | Ancho de la imagen dibujada. |
| altura | int | Altura de la imagen dibujada. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) estructura que especifica la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) que especifica la esquina superior izquierda de la imagen dibujada. Las propiedades X y Y del rectángulo especifican la esquina superior izquierda. Las propiedades Ancho y Altura se ignoran. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Dibuja la imagen especificada usando su tamaño físico original en la ubicación especificada por un par de coordenadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Dibuja una imagen especificada usando su tamaño físico original en una ubicación especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| x | int | La coordenada x de la esquina superior izquierda de la imagen dibujada. |
| y | int | La coordenada y de la esquina superior izquierda de la imagen dibujada. |
| width | int | El parámetro no se utiliza. |
| altura | int | El parámetro no se utiliza. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Dibuja la imagen especificada sin escalar y la recorta, si es necesario, para ajustarla al rectángulo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | La imagen con la que dibujar. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El [Rectangle](/psd/python-net/aspose.psd/rectangle/) en el que dibujar la imagen. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Dibuja una línea que conecta dos estructuras [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la línea. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) estructura que representa el primer punto a conectar. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) estructura que representa el segundo punto a conectar. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Dibuja una línea que conecta dos estructuras [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la línea. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) estructura que representa el primer punto a conectar. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) estructura que representa el segundo punto a conectar. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la línea. |
| x1 | int | La coordenada x del primer punto. |
| y1 | int | La coordenada y del primer punto. |
| x2 | int | La coordenada x del segundo punto. |
| y2 | int | La coordenada y del segundo punto. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dibuja una línea que conecta los dos puntos especificados por los pares de coordenadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la línea. |
| x1 | float | La coordenada x del primer punto. |
| y1 | float | La coordenada y del primer punto. |
| x2 | float | La coordenada x del segundo punto. |
| y2 | float | La coordenada y del segundo punto. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [Point](/psd/python-net/aspose.psd/point/) que representan los puntos a conectar. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [Point](/psd/python-net/aspose.psd/point/) que representan los puntos a conectar. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Dibuja un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la ruta. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) para dibujar. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el segundo lado de la forma de pastel. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que representa el rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el segundo lado de la forma de pastel. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| width | float | Ancho del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| altura | float | Altura del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | float | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | float | Ángulo medido en grados en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el segundo lado de la forma de pastel. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dibuja una forma de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de la forma de pastel. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| width | int | Ancho del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| altura | int | Altura del rectángulo delimitador que define la elipse de la cual proviene la forma de pastel. |
| start_angle | int | Ángulo medido en grados en sentido horario desde el eje x hasta el primer lado de la forma de pastel. |
| sweep_angle | int | Ángulo medido en grados en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el segundo lado de la forma de pastel. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Dibuja un polígono definido por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del polígono. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de [PointF](/psd/python-net/aspose.psd/pointf/) estructuras que representan los vértices del polígono. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Dibuja un polígono definido por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del polígono. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de [PointF](/psd/python-net/aspose.psd/pointf/) estructuras que representan los vértices del polígono. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Dibuja un rectángulo especificado por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que representa el rectángulo a dibujar. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Dibuja un rectángulo especificado por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que representa el rectángulo a dibujar. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | float | El ancho del rectángulo a dibujar. |
| altura | float | La altura del rectángulo a dibujar. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dibuja un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo del rectángulo. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a dibujar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a dibujar. |
| width | int | El ancho del rectángulo a dibujar. |
| altura | int | La altura del rectángulo a dibujar. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Matriz de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructuras que representan los rectángulos a dibujar. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Dibuja una serie de rectángulos especificados por estructuras [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) que determina el color, el ancho y el estilo de los contornos de los rectángulos. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Matriz de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructuras que representan los rectángulos a dibujar. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina el color y la textura del texto dibujado. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que especifica la ubicación del texto dibujado. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Dibuja la cadena de texto especificada en el rectángulo especificado con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) usando los atributos de formato del [StringFormat](/psd/python-net/aspose.psd/stringformat/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina el color y la textura del texto dibujado. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) estructura que especifica la ubicación del texto dibujado. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina el color y la textura del texto dibujado. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que especifica la esquina superior izquierda del texto dibujado. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) usando los atributos de formato del [StringFormat](/psd/python-net/aspose.psd/stringformat/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina el color y la textura del texto dibujado. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) estructura que especifica la esquina superior izquierda del texto dibujado. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina el color y la textura del texto dibujado. |
| x | float | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | float | La coordenada y de la esquina superior izquierda del texto dibujado. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Dibuja la cadena de texto especificada en la ubicación especificada con los objetos [Brush](/psd/python-net/aspose.psd/brush/) y [Font](/psd/python-net/aspose.psd/font/) usando los atributos de formato del [StringFormat](/psd/python-net/aspose.psd/stringformat/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | Cadena a dibujar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) que define el formato de texto de la cadena. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina el color y la textura del texto dibujado. |
| x | float | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | float | La coordenada y de la esquina superior izquierda del texto dibujado. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) que especifica atributos de formato, como el interlineado y la alineación, que se aplican al texto dibujado. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método usa una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/). Este método usa una tensión predeterminada de 0.5 y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno especificado. Este método usa una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Miembro de la enumeración [FillMode](/psd/python-net/aspose.psd/fillmode/) que determina cómo se rellena la curva. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno especificado. Este método usa una tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Miembro de la enumeración [FillMode](/psd/python-net/aspose.psd/fillmode/) que determina cómo se rellena la curva. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno y la tensión especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Miembro de la enumeración [FillMode](/psd/python-net/aspose.psd/fillmode/) que determina cómo se rellena la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Rellena el interior de una curva spline cardinal cerrada definida por una matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno y la tensión especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que definen la spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Miembro de la enumeración [FillMode](/psd/python-net/aspose.psd/fillmode/) que determina cómo se rellena la curva. |
| tensión | float | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa el rectángulo delimitador que define la elipse. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) que representa el rectángulo delimitador que define la elipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | float | Ancho del rectángulo delimitador que define la elipse. |
| altura | float | Altura del rectángulo delimitador que define la elipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Rellena el interior de una elipse definida por un rectángulo delimitador especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse. |
| width | int | Ancho del rectángulo delimitador que define la elipse. |
| altura | int | Altura del rectángulo delimitador que define la elipse. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Rellena el interior de un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que representa la ruta a rellenar. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Rellena el interior de una sección de pastel definida por una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el segundo lado de la sección de pastel. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Rellena el interior de una sección de pastel definida por una elipse especificada por una estructura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el segundo lado de la sección de pastel. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Rellena el interior de una sección de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| width | float | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| altura | float | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | float | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | float | Ángulo en grados medido en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el segundo lado de la sección de pastel. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Rellena el interior de una sección de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| width | int | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| altura | int | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| start_angle | int | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado de la sección de pastel. |
| sweep_angle | int | Ángulo en grados medido en sentido horario desde el parámetro <paramref name="startAngle" /> hasta el segundo lado de la sección de pastel. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [PointF](/psd/python-net/aspose.psd/pointf/) y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representan los vértices del polígono a rellenar. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [PointF](/psd/python-net/aspose.psd/pointf/) y el modo de relleno [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representan los vértices del polígono a rellenar. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representan los vértices del polígono a rellenar. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Miembro de la enumeración [FillMode](/psd/python-net/aspose.psd/fillmode/) que determina el estilo del relleno. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Rellena el interior de un polígono definido por una matriz de puntos especificados por estructuras [PointF](/psd/python-net/aspose.psd/pointf/) usando el modo de relleno especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Matriz de estructuras [PointF](/psd/python-net/aspose.psd/pointf/) que representan los vértices del polígono a rellenar. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Miembro de la enumeración [FillMode](/psd/python-net/aspose.psd/fillmode/) que determina el estilo del relleno. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Rellena el interior de un rectángulo especificado por una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representa el rectángulo a rellenar. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Rellena el interior de un rectángulo especificado por una estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Estructura [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representa el rectángulo a rellenar. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| x | float | La coordenada x de la esquina superior izquierda del rectángulo a rellenar. |
| y | float | La coordenada y de la esquina superior izquierda del rectángulo a rellenar. |
| width | float | Ancho del rectángulo a rellenar. |
| altura | float | Altura del rectángulo a rellenar. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Rellena el interior de un rectángulo especificado por un par de coordenadas, un ancho y una altura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| x | int | La coordenada x de la esquina superior izquierda del rectángulo a rellenar. |
| y | int | La coordenada y de la esquina superior izquierda del rectángulo a rellenar. |
| width | int | Ancho del rectángulo a rellenar. |
| altura | int | Altura del rectángulo a rellenar. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Rellena los interiores de una serie de rectángulos especificados por estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Matriz de estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representan los rectángulos a rellenar. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Rellena los interiores de una serie de rectángulos especificados por estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Matriz de estructuras [Rectangle](/psd/python-net/aspose.psd/rectangle/) que representan los rectángulos a rellenar. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Rellena el interior de una [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) que determina las características del relleno. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) que representa el área a rellenar. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Multiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) que representa la transformación geométrica local de este [Graphics](/psd/python-net/aspose.psd/graphics/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada, anteponiendo la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) por la cual multiplicar la transformación geométrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Multiplica la [Matrix](/psd/python-net/aspose.psd/matrix/) que representa la transformación geométrica local de este [Graphics](/psd/python-net/aspose.psd/graphics/) por la [Matrix](/psd/python-net/aspose.psd/matrix/) especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) por la cual multiplicar la transformación geométrica. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) que especifica en qué orden multiplicar las dos matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local en la cantidad especificada. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local en la cantidad especificada en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) que especifica si se debe anexar o anteponer la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local en las cantidades especificadas. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Escala la transformación geométrica local en las cantidades especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | La cantidad por la cual escalar la transformación en la dirección del eje x. |
| sy | float | La cantidad por la cual escalar la transformación en la dirección del eje y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) que especifica si se debe anexar o anteponer la matriz de escala. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local en las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traducción en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Traslada la transformación geométrica local en las dimensiones especificadas en el orden especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traducción en y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | El orden (anteponer o anexar) en el que aplicar la traducción. |

