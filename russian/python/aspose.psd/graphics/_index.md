---
title: "Класс Graphics"
type: docs
weight: 1550
url: /ru/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Инициализирует новый экземпляр класса [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Получает или задает область обрезки. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Получает или задает качество композитинга. |
| dpi_x | float | r | Получает горизонтальное разрешение этого Aspose.PSD.Graphics. |
| dpi_y | float | r | Получает вертикальное разрешение этого Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Получает изображение. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Получает или задает режим интерполяции. |
| is_in_begin_update_call | bool | r | Получает значение, указывающее, находится ли графика в состоянии вызова BeginUpdate. |
| page_scale | float | r/w | Получает или задает масштабирование между мировыми единицами и единицами страницы для этого Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Получает или задает единицу измерения, используемую для координат страницы в этом Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Получает или задает параметры изображения, используемые для создания рисуемых векторных изображений. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Получает или задает режим сглаживания. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Получает или задает подсказку рендеринга текста. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Получает или задает копию геометрического мирового преобразования для этого [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| begin_update() | Начинает кэширование последующих графических операций. Применяемые после этого графические эффекты не будут применяться немедленно; вместо этого вызов EndUpdate применит все эффекты одновременно. |
| [clear(color)](#clear_color_1) | Очищает графическую поверхность с использованием указанного цвета. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Рисует сплайн Безье, определённый четырьмя структурами [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Рисует сплайн Безье, определённый четырьмя структурами [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Рисует сплайн Безье, определённый четырьмя упорядоченными парами координат, представляющими точки. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Рисует серию сплайнов Безье из массива структур [Point](/psd/python-net/aspose.psd/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Рисует серию сплайнов Безье из массива структур [Point](/psd/python-net/aspose.psd/point/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. Этот метод использует режим заливки по умолчанию [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. Этот метод использует режим заливки по умолчанию [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/). Рисование начинается со смещения от начала массива.<br/>            Этот метод использует напряжение по умолчанию 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. Рисование начинается со смещения от начала массива. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. Рисование начинается со смещения от начала массива. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Рисует эллипс, определённый ограничивающим [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Рисует эллипс, определённый ограничивающим [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/), используя его оригинальный физический размер, в указанном месте. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Рисует указанное изображение, используя его оригинальный физический размер, в месте, заданном парой координат. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Рисует указанное изображение без масштабирования и обрезает его при необходимости, чтобы поместить в указанный прямоугольник. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Рисует линию, соединяющую две структуры [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Рисует линию, соединяющую две структуры [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Рисует линию, соединяющую две точки, указанные парами координат. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Рисует серию отрезков, соединяющих массив структур [Point](/psd/python-net/aspose.psd/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Рисует серию отрезков, соединяющих массив структур [Point](/psd/python-net/aspose.psd/point/). |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Рисует [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Рисует форму сектора, определённую эллипсом, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/) и двумя радиальными линиями. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Рисует форму сектора, определённую эллипсом, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/) и двумя радиальными линиями. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Рисует форму сектора, определённую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Рисует форму сектора, определённую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Рисует многоугольник, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Рисует многоугольник, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Рисует прямоугольник, заданный структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Рисует прямоугольник, заданный структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Рисует серию прямоугольников, заданных структурами [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Рисует серию прямоугольников, заданных структурами [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Рисует указанную строку текста в указанном прямоугольнике с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/). |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Рисует указанную строку текста в указанном прямоугольнике с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/), используя атрибуты форматирования указанного [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Рисует указанную строку текста в указанном месте с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/). |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Рисует указанную строку текста в указанном месте с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/), используя атрибуты форматирования указанного [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Рисует указанную строку текста в указанном месте с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/). |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Рисует указанную строку текста в указанном месте с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/), используя атрибуты форматирования указанного [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | Завершает кэширование графических операций, начатое после вызова BeginUpdate. Предшествующие графические операции будут применены сразу при вызове этого метода. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0,5 и режим заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0,5 и режим заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки. Этот метод использует напряжение по умолчанию 0,5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки. Этот метод использует напряжение по умолчанию 0,5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки и напряжение. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки и напряжение. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Заполняет внутреннюю часть [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/) и двумя радиальными линиями. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/) и двумя радиальными линиями. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, заданных структурами [PointF](/psd/python-net/aspose.psd/pointf/) и режимом заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, заданных структурами [PointF](/psd/python-net/aspose.psd/pointf/) и режимом заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, заданных структурами [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Заполняет внутреннюю часть многоугольника, определенного массивом точек, заданных структурами [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Заполняет внутреннюю часть прямоугольника, заданного структурой [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Заполняет внутреннюю часть прямоугольника, заданного структурой [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Заполняет внутренние части серии прямоугольников, заданных структурами [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Заполняет внутренние части серии прямоугольников, заданных структурами [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Заполняет внутреннюю часть [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [Graphics](/psd/python-net/aspose.psd/graphics/), на указанный [Matrix](/psd/python-net/aspose.psd/matrix/), предварительно добавляя указанный [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [Graphics](/psd/python-net/aspose.psd/graphics/), на указанный [Matrix](/psd/python-net/aspose.psd/matrix/) в указанном порядке. |
| reset_transform() | Сбрасывает свойство [Graphics.transform](/psd/python-net/aspose.psd/graphics/) к единичному преобразованию. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Масштабирует локальное геометрическое преобразование на указанные значения. Этот метод добавляет матрицу масштабирования в начало преобразования. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Масштабирует локальное геометрическое преобразование на указанные значения в указанном порядке. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Инициализирует новый экземпляр класса [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Исходное изображение. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Очищает графическую поверхность с использованием указанного цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Цвет, которым очищается графическая поверхность. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) , определяющий цвет, ширину и стиль дуги. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) структура, определяющая границы эллипса. |
| start_angle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра <paramref name="startAngle" /> до конечной точки дуги. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) , определяющий цвет, ширину и стиль дуги. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) структура, определяющая границы эллипса. |
| start_angle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра <paramref name="startAngle" /> до конечной точки дуги. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) , определяющий цвет, ширину и стиль дуги. |
| x | float | Координата x верхнего левого угла прямоугольника, определяющего эллипс. |
| y | float | Координата y верхнего левого угла прямоугольника, определяющего эллипс. |
| width | float | Ширина прямоугольника, определяющего эллипс. |
| height | float | Высота прямоугольника, определяющего эллипс. |
| start_angle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра <paramref name="startAngle" /> до конечной точки дуги. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) , определяющий цвет, ширину и стиль дуги. |
| x | int | Координата x верхнего левого угла прямоугольника, определяющего эллипс. |
| y | int | Координата y верхнего левого угла прямоугольника, определяющего эллипс. |
| width | int | Ширина прямоугольника, определяющего эллипс. |
| height | int | Высота прямоугольника, определяющего эллипс. |
| start_angle | int | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweep_angle | int | Угол в градусах, измеряемый по часовой стрелке от параметра <paramref name="startAngle" /> до конечной точки дуги. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Рисует сплайн Безье, определённый четырьмя структурами [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль кривой. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) структура, представляющая начальную точку кривой. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) структура, представляющая первую управляющую точку кривой. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) структура, представляющая вторую управляющую точку кривой. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) структура, представляющая конечную точку кривой. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Рисует сплайн Безье, определённый четырьмя структурами [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль кривой. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) структура, представляющая начальную точку кривой. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) структура, представляющая первую управляющую точку кривой. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) структура, представляющая вторую управляющую точку кривой. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) структура, представляющая конечную точку кривой. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Рисует сплайн Безье, определённый четырьмя упорядоченными парами координат, представляющими точки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль кривой. |
| x1 | float | Координата x начальной точки кривой. |
| y1 | float | Координата y начальной точки кривой. |
| x2 | float | Координата x первой управляющей точки кривой. |
| y2 | float | Координата y первой управляющей точки кривой. |
| x3 | float | Координата x второй управляющей точки кривой. |
| y3 | float | Координата y второй управляющей точки кривой. |
| x4 | float | Координата x конечной точки кривой. |
| y4 | float | Координата y конечной точки кривой. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Рисует серию сплайнов Безье из массива структур [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль кривой. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [Point](/psd/python-net/aspose.psd/point/), представляющих точки, определяющие кривую. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Рисует серию сплайнов Безье из массива структур [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль кривой. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [Point](/psd/python-net/aspose.psd/point/), представляющих точки, определяющие кривую. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0.5 и режим заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. Этот метод использует режим заливки по умолчанию [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Рисует замкнутый кардинальный сплайн, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. Этот метод использует режим заливки по умолчанию [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/). Рисование начинается со смещения от начала массива.<br/>            Этот метод использует напряжение по умолчанию 0.5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| offset | int | Смещение от первого элемента массива параметра <paramref name="points" /> к начальной точке кривой. |
| number_of_segments | int | Количество сегментов после начальной точки, включаемых в кривую. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. Рисование начинается со смещения от начала массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| offset | int | Смещение от первого элемента массива параметра <paramref name="points" /> к начальной точке кривой. |
| number_of_segments | int | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение. Рисование начинается со смещения от начала массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| offset | int | Смещение от первого элемента массива параметра <paramref name="points" /> к начальной точке кривой. |
| number_of_segments | int | Количество сегментов после начальной точки, включаемых в кривую. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, определяющие кривую. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Рисует кардинальный сплайн через указанный массив структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанное напряжение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и высоту кривой. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих точки, определяющие кривую. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Рисует эллипс, определённый ограничивающим [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и стиль эллипса. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) структура, определяющая границы эллипса. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Рисует эллипс, определённый ограничивающим [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и стиль эллипса. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) структура, определяющая границы эллипса. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и стиль эллипса. |
| x | float | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | float | Координата y левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Рисует эллипс, определённый ограничивающим прямоугольником, заданным парой координат, высотой и шириной.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/), определяющий цвет, ширину и стиль эллипса. |
| x | int | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | int | Координата y левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для отрисовки. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Массив из трёх структур PointF, определяющих параллелограмм. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для отрисовки. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив из трёх структур PointF, определяющих параллелограмм. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для отрисовки. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Исходный прямоугольник. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для отрисовки. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Исходный прямоугольник. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для отрисовки. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Единицы измерения. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для отрисовки. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Единицы измерения. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для отрисовки. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Единицы измерения. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Атрибуты изображения. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Рисует указанную часть указанного <paramref name=\"image\" /> в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для отрисовки. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив из трёх структур PointF, определяющих параллелограмм. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Исходный прямоугольник. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Единицы измерения. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Атрибуты изображения. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Структура [PointF](/psd/python-net/aspose.psd/pointf/), представляющая левый верхний угол отрисованного изображения. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| point | [Point](/psd/python-net/aspose.psd/point) | Структура [PointF](/psd/python-net/aspose.psd/pointf/), представляющая левый верхний угол отрисованного изображения. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), определяющая положение и размер отрисованного изображения. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), определяющая положение и размер отрисованного изображения. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Графический блок. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Графический блок. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Графический блок. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Атрибуты изображения. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Прямоугольник назначения. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Графический блок. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Атрибуты изображения. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Исходный прямоугольник. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Целевой прямоугольник. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Графический блок. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Исходный прямоугольник. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Целевой прямоугольник. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Графический блок. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Исходный прямоугольник. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Целевой прямоугольник. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Графический блок. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Атрибуты изображения. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Исходный прямоугольник. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Целевой прямоугольник. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Графический блок. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Атрибуты изображения. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| x | float | Координата X верхнего левого угла нарисованного изображения. |
| y | float | Координата Y верхнего левого угла нарисованного изображения. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/), используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата X верхнего левого угла нарисованного изображения. |
| y | int | Координата Y верхнего левого угла нарисованного изображения. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| x | float | Координата X верхнего левого угла нарисованного изображения. |
| y | float | Координата Y верхнего левого угла нарисованного изображения. |
| width | float | Ширина нарисованного изображения. |
| height | float | Высота нарисованного изображения. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Рисует указанное [Graphics.image](/psd/python-net/aspose.psd/graphics/) в указанном месте и с указанным размером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата X верхнего левого угла нарисованного изображения. |
| y | int | Координата Y верхнего левого угла нарисованного изображения. |
| width | int | Ширина нарисованного изображения. |
| height | int | Высота нарисованного изображения. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) структура, указывающая верхний левый угол нарисованного изображения. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) указывает верхний левый угол нарисованного изображения. Свойства X и Y прямоугольника указывают верхний левый угол. Свойства Width и Height игнорируются. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в месте, заданном парой координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата X верхнего левого угла нарисованного изображения. |
| y | int | Координата Y верхнего левого угла нарисованного изображения. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| x | int | Координата X верхнего левого угла нарисованного изображения. |
| y | int | Координата Y верхнего левого угла нарисованного изображения. |
| width | int | Параметр не используется. |
| height | int | Параметр не используется. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Рисует указанное изображение без масштабирования и обрезает его при необходимости, чтобы поместить в указанный прямоугольник.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Изображение, с которым выполнять отрисовку. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/), в котором следует нарисовать изображение. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Рисует линию, соединяющую две структуры [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль линии. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) структура, представляющая первую точку для соединения. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) структура, представляющая вторую точку для соединения. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Рисует линию, соединяющую две структуры [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль линии. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) структура, представляющая первую точку для соединения. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) структура, представляющая вторую точку для соединения. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Рисует линию, соединяющую две точки, указанные парами координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль линии. |
| x1 | int | Координата X первой точки. |
| y1 | int | Координата Y первой точки. |
| x2 | int | Координата X второй точки. |
| y2 | int | Координата Y второй точки. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Рисует линию, соединяющую две точки, указанные парами координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль линии. |
| x1 | float | Координата X первой точки. |
| y1 | float | Координата Y первой точки. |
| x2 | float | Координата X второй точки. |
| y2 | float | Координата Y второй точки. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Рисует серию отрезков, соединяющих массив структур [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль сегментов линии. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [Point](/psd/python-net/aspose.psd/point/), представляющих точки для соединения. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Рисует серию отрезков, соединяющих массив структур [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль сегментов линии. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [Point](/psd/python-net/aspose.psd/point/), представляющих точки для соединения. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Рисует [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль пути. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) для рисования. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Рисует форму сектора, определённую эллипсом, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль формы сектора. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого формируется сектор. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X до первой стороны сектора. |
| sweep_angle | float | Угол измеряется в градусах по часовой стрелке от параметра <paramref name="startAngle" /> до второй стороны формы пирога. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Рисует форму сектора, определённую эллипсом, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль формы сектора. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого формируется сектор. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X до первой стороны сектора. |
| sweep_angle | float | Угол измеряется в градусах по часовой стрелке от параметра <paramref name="startAngle" /> до второй стороны формы пирога. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует форму сектора, определённую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль формы сектора. |
| x | float | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется форма пирога. |
| y | float | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется форма пирога. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| start_angle | float | Угол, измеряемый в градусах по часовой стрелке от оси X до первой стороны сектора. |
| sweep_angle | float | Угол измеряется в градусах по часовой стрелке от параметра <paramref name="startAngle" /> до второй стороны формы пирога. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Рисует форму сектора, определённую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль формы сектора. |
| x | int | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется форма пирога. |
| y | int | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого формируется форма пирога. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся форма пирога. |
| start_angle | int | Угол, измеряемый в градусах по часовой стрелке от оси X до первой стороны сектора. |
| sweep_angle | int | Угол измеряется в градусах по часовой стрелке от параметра <paramref name="startAngle" /> до второй стороны формы пирога. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Рисует многоугольник, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль многоугольника. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих вершины многоугольника. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Рисует многоугольник, определённый массивом структур [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль многоугольника. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих вершины многоугольника. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Рисует прямоугольник, заданный структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Объект [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль прямоугольника. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Объект [RectangleF](/psd/python-net/aspose.psd/rectanglef/) представляет прямоугольник для рисования. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Рисует прямоугольник, заданный структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Объект [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль прямоугольника. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Объект [RectangleF](/psd/python-net/aspose.psd/rectanglef/) представляет прямоугольник для рисования. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Рисует прямоугольник, заданный парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Объект [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль прямоугольника. |
| x | float | Координата x верхнего левого угла прямоугольника для рисования. |
| y | float | Координата y верхнего левого угла прямоугольника для рисования. |
| width | float | Ширина прямоугольника для рисования. |
| height | float | Высота прямоугольника для рисования. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Рисует прямоугольник, заданный парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Объект [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль прямоугольника. |
| x | int | Координата x верхнего левого угла прямоугольника для рисования. |
| y | int | Координата y верхнего левого угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Рисует серию прямоугольников, заданных структурами [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Массив структур [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющих прямоугольники для рисования. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Рисует серию прямоугольников, заданных структурами [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) определяет цвет, ширину и стиль контуров прямоугольников. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Массив структур [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющих прямоугольники для рисования. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Рисует указанную строку текста в указанном прямоугольнике с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) определяет формат текста строки. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет цвет и текстуру нарисованного текста. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) указывает расположение нарисованного текста. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Рисует указанную строку текста в указанном прямоугольнике с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/), используя атрибуты форматирования указанного [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) определяет формат текста строки. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет цвет и текстуру нарисованного текста. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) указывает расположение нарисованного текста. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) задаёт атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Рисует указанную строку текста в указанном месте с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) определяет формат текста строки. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет цвет и текстуру нарисованного текста. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) указывает верхний левый угол нарисованного текста. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Рисует указанную строку текста в указанном месте с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/), используя атрибуты форматирования указанного [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) определяет формат текста строки. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет цвет и текстуру нарисованного текста. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) указывает верхний левый угол нарисованного текста. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) задаёт атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Рисует указанную строку текста в указанном месте с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) определяет формат текста строки. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет цвет и текстуру нарисованного текста. |
| x | float | Координата x верхнего левого угла нарисованного текста. |
| y | float | Координата y верхнего левого угла нарисованного текста. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Рисует указанную строку текста в указанном месте с указанными объектами [Brush](/psd/python-net/aspose.psd/brush/) и [Font](/psd/python-net/aspose.psd/font/), используя атрибуты форматирования указанного [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Строка для рисования. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) определяет формат текста строки. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет цвет и текстуру нарисованного текста. |
| x | float | Координата x верхнего левого угла нарисованного текста. |
| y | float | Координата y верхнего левого угла нарисованного текста. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) задаёт атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0,5 и режим заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/). Этот метод использует напряжение по умолчанию 0,5 и режим заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки. Этот метод использует напряжение по умолчанию 0,5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Элемент перечисления [FillMode](/psd/python-net/aspose.psd/fillmode/), определяющего, как заполняется кривая. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки. Этот метод использует напряжение по умолчанию 0,5.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Элемент перечисления [FillMode](/psd/python-net/aspose.psd/fillmode/), определяющего, как заполняется кривая. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки и напряжение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Объект [Brush](/psd/python-net/aspose.psd/brush/), определяющий характеристики заливки. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Элемент перечисления [FillMode](/psd/python-net/aspose.psd/fillmode/), определяющего, как заполняется кривая. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Заполняет внутреннюю часть замкнутой кардинальной сплайн‑кривой, определенной массивом структур [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки и напряжение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Объект [Brush](/psd/python-net/aspose.psd/brush/), определяющий характеристики заливки. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), определяющих сплайн. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Элемент перечисления [FillMode](/psd/python-net/aspose.psd/fillmode/), определяющего, как заполняется кривая. |
| натяжение | float | Значение, большее или равное 0.0F, указывающее натяжение кривой. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая ограничивающий прямоугольник, определяющий эллипс. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [RectangleF](/psd/python-net/aspose.psd/rectanglef/), представляющая ограничивающий прямоугольник, определяющий эллипс. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| x | float | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | float | Координата y левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Заполняет внутреннюю часть эллипса, определенного ограничивающим прямоугольником, заданным парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| x | int | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| y | int | Координата y левого верхнего угла ограничивающего прямоугольника, определяющего эллипс. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Заполняет внутреннюю часть [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/), представляющий путь для заполнения. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор. |
| start_angle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра <paramref name=\"startAngle\" /> до второй стороны сектора. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным структурой [RectangleF](/psd/python-net/aspose.psd/rectanglef/) и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющая ограничивающий прямоугольник, определяющий эллипс, из которого берётся сектор. |
| start_angle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра <paramref name=\"startAngle\" /> до второй стороны сектора. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| x | float | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор. |
| y | float | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор. |
| width | float | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор. |
| height | float | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор. |
| start_angle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | float | Угол в градусах, измеряемый по часовой стрелке от параметра <paramref name=\"startAngle\" /> до второй стороны сектора. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Заполняет внутреннюю часть сектора пирога, определенного эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| x | int | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор. |
| y | int | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор. |
| width | int | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор. |
| height | int | Высота ограничивающего прямоугольника, определяющего эллипс, из которого берётся сектор. |
| start_angle | int | Угол в градусах, измеряемый по часовой стрелке от оси x до первой стороны сектора. |
| sweep_angle | int | Угол в градусах, измеряемый по часовой стрелке от параметра <paramref name=\"startAngle\" /> до второй стороны сектора. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, заданных структурами [PointF](/psd/python-net/aspose.psd/pointf/) и режимом заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих вершины полигона для заполнения. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, заданных структурами [PointF](/psd/python-net/aspose.psd/pointf/) и режимом заливки [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих вершины полигона для заполнения. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, заданных структурами [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих вершины полигона для заполнения. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Элемент перечисления [FillMode](/psd/python-net/aspose.psd/fillmode/), определяющего стиль заливки. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Заполняет внутреннюю часть многоугольника, определенного массивом точек, заданных структурами [PointF](/psd/python-net/aspose.psd/pointf/), используя указанный режим заливки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Массив структур [PointF](/psd/python-net/aspose.psd/pointf/), представляющих вершины полигона для заполнения. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Элемент перечисления [FillMode](/psd/python-net/aspose.psd/fillmode/), определяющего стиль заливки. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Заполняет внутреннюю часть прямоугольника, заданного структурой [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Структура [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющая прямоугольник для заполнения. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Заполняет внутреннюю часть прямоугольника, заданного структурой [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Структура [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющая прямоугольник для заполнения. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| x | float | Координата x верхнего левого угла прямоугольника для заполнения. |
| y | float | Координата y верхнего левого угла прямоугольника для заполнения. |
| width | float | Ширина прямоугольника для заполнения. |
| height | float | Высота прямоугольника для заполнения. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| x | int | Координата x верхнего левого угла прямоугольника для заполнения. |
| y | int | Координата y верхнего левого угла прямоугольника для заполнения. |
| width | int | Ширина прямоугольника для заполнения. |
| height | int | Высота прямоугольника для заполнения. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Заполняет внутренние части серии прямоугольников, заданных структурами [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Массив структур [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющих прямоугольники для заполнения. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Заполняет внутренние части серии прямоугольников, заданных структурами [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Массив структур [Rectangle](/psd/python-net/aspose.psd/rectangle/), представляющих прямоугольники для заполнения. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Заполняет внутреннюю часть [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) определяет характеристики заливки. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/), представляющий область для заполнения. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [Graphics](/psd/python-net/aspose.psd/graphics/), на указанный [Matrix](/psd/python-net/aspose.psd/matrix/), предварительно добавляя указанный [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/), используемая для умножения геометрического преобразования. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Умножает [Matrix](/psd/python-net/aspose.psd/matrix/), представляющую локальное геометрическое преобразование этого [Graphics](/psd/python-net/aspose.psd/graphics/), на указанный [Matrix](/psd/python-net/aspose.psd/matrix/) в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/), используемая для умножения геометрического преобразования. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий порядок умножения двух матриц. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий, добавлять ли матрицу вращения в конец или в начало. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Масштабирует локальное геометрическое преобразование на указанные значения. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Масштабирует локальное геометрическое преобразование на указанные значения в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sx | float | Величина масштабирования преобразования по оси x. |
| sy | float | Величина масштабирования преобразования по оси y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/), определяющий, добавлять ли матрицу масштабирования в конец или в начало. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Смещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Порядок (добавление в начало или в конец), в котором применять трансляцию. |

