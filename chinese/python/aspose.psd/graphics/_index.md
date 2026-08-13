---
title: "Graphics Class"
type: docs
weight: 1550
url: /zh/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | 初始化 [Graphics](/psd/python-net/aspose.psd/graphics/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | 获取或设置剪裁区域。 |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | 获取或设置合成质量。 |
| dpi_x | float | r | 获取此 Aspose.PSD.Graphics 的水平分辨率。 |
| dpi_y | float | r | 获取此 Aspose.PSD.Graphics 的垂直分辨率。 |
| image | [Image](/psd/python-net/aspose.psd/image) | r | 获取图像。 |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | 获取或设置插值模式。 |
| is_in_begin_update_call | bool | r | 获取一个值，指示 graphics 是否处于 BeginUpdate 调用状态。 |
| page_scale | float | 读/写 | 获取或设置此 Aspose.PSD.Graphics 的世界单位与页面单位之间的缩放比例。 |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | 获取或设置此 Aspose.PSD.Graphics 中页面坐标使用的计量单位。 |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | 获取或设置图像选项，用于创建可绘制的矢量图像。 |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | 获取或设置平滑模式。 |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | 获取或设置文本呈现提示。 |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | 获取或设置此 [Graphics](/psd/python-net/aspose.psd/graphics/) 的几何世界变换的副本。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| begin_update() | 开始缓存后续的图形操作。随后应用的图形效果不会立即生效，而是等到 EndUpdate 时一次性应用所有效果。 |
| [clear(color)](#clear_color_1) | 使用指定的颜色清除图形表面。 |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | 绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆的一段弧线。 |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | 绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆的一段弧线。 |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | 绘制由一对坐标、宽度和高度指定的椭圆的一段弧线。 |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | 绘制由一对坐标、宽度和高度指定的椭圆的一段弧线。 |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | 绘制由四个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构定义的贝塞尔样条曲线。 |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | 绘制由四个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构定义的贝塞尔样条曲线。 |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | 绘制由四对有序坐标点定义的贝塞尔样条曲线。 |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | 从 [Point](/psd/python-net/aspose.psd/point/) 结构数组绘制一系列贝塞尔样条曲线。 |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | 从 [Point](/psd/python-net/aspose.psd/point/) 结构数组绘制一系列贝塞尔样条曲线。 |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | 绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。 |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | 绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。 |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | 绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。 |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | 绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。 |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | 绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线。此方法使用默认张力 0.5。 |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | 绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线。此方法使用默认张力 0.5。 |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | 绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线。绘制从数组开头偏移位置开始。<br/>            此方法使用默认张力 0.5。 |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | 绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线，使用指定的张力。绘制从数组开头偏移位置开始。 |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | 绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线，使用指定的张力。绘制从数组开头偏移位置开始。 |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | 绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线，使用指定的张力。 |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | 绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线，使用指定的张力。 |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | 绘制由边界 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 定义的椭圆。 |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | 绘制由边界 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 定义的椭圆。 |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | 绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。 |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | 在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。 |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | 在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。 |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | 在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。 |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | 在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。 |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | 在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。 |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | 在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。 |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | 在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。 |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | 在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。 |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | 在指定位置绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)，使用其原始物理尺寸。 |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | 在指定位置绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)，使用其原始物理尺寸。 |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | 在指定位置绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)，使用其原始物理尺寸。 |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | 在指定位置绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)，使用其原始物理尺寸。 |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | 在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。 |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | 在指定位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | 在指定位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | 在由坐标对指定的位置，使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | 在指定位置使用其原始物理尺寸绘制指定的图像。 |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | 绘制指定的图像而不进行缩放，并在必要时将其裁剪以适应指定的矩形。 |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | 绘制连接两个 [Point](/psd/python-net/aspose.psd/point/) 结构的直线。 |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | 绘制连接两个 [Point](/psd/python-net/aspose.psd/point/) 结构的直线。 |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | 绘制连接由坐标对指定的两点的直线。 |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | 绘制连接由坐标对指定的两点的直线。 |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | 绘制一系列连接 [Point](/psd/python-net/aspose.psd/point/) 结构数组的线段。 |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | 绘制一系列连接 [Point](/psd/python-net/aspose.psd/point/) 结构数组的线段。 |
| [draw_path(pen, path)](#draw_path_pen_path_61) | 绘制一个 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | 绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。 |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | 绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。 |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | 绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。 |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | 绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的多边形。 |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | 绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的多边形。 |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | 绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的矩形。 |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | 绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的矩形。 |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | 绘制由坐标对、宽度和高度指定的矩形。 |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | 绘制一系列由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的矩形。 |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | 绘制一系列由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的矩形。 |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | 在指定的矩形中使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象绘制指定的文本字符串。 |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | 在指定的矩形中使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象，并使用指定的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 的格式属性绘制指定的文本字符串。 |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | 在指定位置使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象绘制指定的文本字符串。 |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | 在指定位置使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象，并使用指定的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 的格式属性绘制指定的文本字符串。 |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | 在指定位置使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象绘制指定的文本字符串。 |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | 在指定位置使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象，并使用指定的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 的格式属性绘制指定的文本字符串。 |
| end_update() | 完成在调用 BeginUpdate 后开始的图形操作的缓存。调用此方法时，之前的图形操作将一次性应用。 |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | 填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。 |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | 填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。 |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | 使用指定的填充模式填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。 |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | 使用指定的填充模式填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。 |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | 使用指定的填充模式和张力，填充由一组 [PointF](/psd/python-net/aspose.psd/pointf/) 结构定义的闭合基数样条曲线的内部。 |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | 使用指定的填充模式和张力，填充由一组 [PointF](/psd/python-net/aspose.psd/pointf/) 结构定义的闭合基数样条曲线的内部。 |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | 填充由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的边界矩形定义的椭圆的内部。 |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | 填充由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的边界矩形定义的椭圆的内部。 |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | 填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。 |
| [fill_path(brush, path)](#fill_path_brush_path_90) | 填充 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的内部。 |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | 填充由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆和两条径向线定义的扇形的内部。 |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | 填充由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆和两条径向线定义的扇形的内部。 |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | 填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的扇形的内部。 |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | 填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的扇形的内部。 |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | 填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构指定的点数组和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 定义的多边形的内部。 |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | 填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构指定的点数组和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 定义的多边形的内部。 |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | 使用指定的填充模式，填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构指定的点数组定义的多边形的内部。 |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | 使用指定的填充模式，填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构指定的点数组定义的多边形的内部。 |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | 填充由 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构指定的矩形的内部。 |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | 填充由 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构指定的矩形的内部。 |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | 填充由一对坐标、宽度和高度指定的矩形的内部。 |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | 填充由 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构指定的一系列矩形的内部。 |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | 填充由 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构指定的一系列矩形的内部。 |
| [fill_region(brush, region)](#fill_region_brush_region_105) | 填充 [Region](/psd/python-net/aspose.psd/region/) 的内部。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | 通过在前面添加指定的 [Matrix](/psd/python-net/aspose.psd/matrix/)，将表示此 [Graphics](/psd/python-net/aspose.psd/graphics/) 本地几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 相乘。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | 按照指定顺序，将表示此 [Graphics](/psd/python-net/aspose.psd/graphics/) 本地几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 相乘。 |
| reset_transform() | 将 [Graphics.transform](/psd/python-net/aspose.psd/graphics/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_108) | 按指定的量旋转局部几何变换。此方法将在变换前置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | 按指定的量并按照指定顺序旋转局部几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | 按指定的比例缩放局部几何变换。此方法将在变换前置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | 按指定的比例并按照指定顺序缩放局部几何变换。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | 按指定的尺寸平移局部几何变换。此方法将在变换前置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | 按指定的尺寸并按照指定顺序平移局部几何变换。 |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

初始化 [Graphics](/psd/python-net/aspose.psd/graphics/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 源图像。 |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

使用指定的颜色清除图形表面。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 用于清除图形表面的颜色。 |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆的一段弧线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 决定弧线颜色、宽度和样式的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 定义椭圆边界的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| start_angle | float | 以度为单位的角度，顺时针从 x 轴测量到弧线起始点。 |
| sweep_angle | float | 以度为单位的角度，顺时针从 <paramref name=\"startAngle\" /> 参数测量到弧线结束点。 |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆的一段弧线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 决定弧线颜色、宽度和样式的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 定义椭圆边界的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| start_angle | float | 以度为单位的角度，顺时针从 x 轴测量到弧线起始点。 |
| sweep_angle | float | 以度为单位的角度，顺时针从 <paramref name=\"startAngle\" /> 参数测量到弧线结束点。 |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制由一对坐标、宽度和高度指定的椭圆的一段弧线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 决定弧线颜色、宽度和样式的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| x | float | 定义椭圆的矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的矩形的宽度。 |
| height | float | 定义椭圆的矩形的高度。 |
| start_angle | float | 以度为单位的角度，顺时针从 x 轴测量到弧线起始点。 |
| sweep_angle | float | 以度为单位的角度，顺时针从 <paramref name=\"startAngle\" /> 参数测量到弧线结束点。 |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制由一对坐标、宽度和高度指定的椭圆的一段弧线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 决定弧线颜色、宽度和样式的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| x | int | 定义椭圆的矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的矩形的宽度。 |
| height | int | 定义椭圆的矩形的高度。 |
| start_angle | int | 以度为单位的角度，顺时针从 x 轴测量到弧线起始点。 |
| sweep_angle | int | 以度为单位的角度，顺时针从 <paramref name=\"startAngle\" /> 参数测量到弧线结束点。 |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

绘制由四个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构定义的贝塞尔样条曲线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和样式。 |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 结构，表示曲线的起始点。 |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 结构，表示曲线的第一个控制点。 |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 结构，表示曲线的第二个控制点。 |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 结构，表示曲线的结束点。 |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

绘制由四个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构定义的贝塞尔样条曲线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和样式。 |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 结构，表示曲线的起始点。 |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 结构，表示曲线的第一个控制点。 |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 结构，表示曲线的第二个控制点。 |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 结构，表示曲线的结束点。 |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

绘制由四对有序坐标点定义的贝塞尔样条曲线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和样式。 |
| x1 | float | 曲线起始点的 x 坐标。 |
| y1 | float | 曲线起始点的 y 坐标。 |
| x2 | float | 曲线第一个控制点的 x 坐标。 |
| y2 | float | 曲线第一个控制点的 y 坐标。 |
| x3 | float | 曲线第二个控制点的 x 坐标。 |
| y3 | float | 曲线第二个控制点的 y 坐标。 |
| x4 | float | 曲线结束点的 x 坐标。 |
| y4 | float | 曲线结束点的 y 坐标。 |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

从 [Point](/psd/python-net/aspose.psd/point/) 结构数组绘制一系列贝塞尔样条曲线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和样式。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 表示决定曲线的点的 [Point](/psd/python-net/aspose.psd/point/) 结构数组。 |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

从 [Point](/psd/python-net/aspose.psd/point/) 结构数组绘制一系列贝塞尔样条曲线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和样式。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 表示决定曲线的点的 [Point](/psd/python-net/aspose.psd/point/) 结构数组。 |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线，使用指定的张力。此方法使用默认的 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线。绘制从数组开头偏移位置开始。<br/>            此方法使用默认张力 0.5。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| offset | int | 从 <paramref name="points" /> 参数数组的第一个元素到曲线起始点的偏移量。 |
| number_of_segments | int | 起始点之后要包含在曲线中的段数。 |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线，使用指定的张力。绘制从数组开头偏移位置开始。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| offset | int | 从 <paramref name="points" /> 参数数组的第一个元素到曲线起始点的偏移量。 |
| number_of_segments | int | 起始点之后要包含在曲线中的段数。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线，使用指定的张力。绘制从数组开头偏移位置开始。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| offset | int | 从 <paramref name="points" /> 参数数组的第一个元素到曲线起始点的偏移量。 |
| number_of_segments | int | 起始点之后要包含在曲线中的段数。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线，使用指定的张力。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 表示定义曲线的点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

绘制通过指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组的基数样条曲线，使用指定的张力。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 确定曲线的颜色、宽度和高度。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 表示定义曲线的点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

绘制由边界 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 定义的椭圆。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 决定椭圆颜色、宽度和样式的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 定义椭圆边界的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

绘制由边界 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 定义的椭圆。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 决定椭圆颜色、宽度和样式的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 定义椭圆边界的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 决定椭圆颜色、宽度和样式的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| x | float | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的边界矩形的宽度。 |
| height | float | 定义椭圆的边界矩形的高度。 |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

绘制由一对坐标、一个高度和一个宽度指定的边界矩形定义的椭圆。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 决定椭圆颜色、宽度和样式的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| x | int | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的边界矩形的宽度。 |
| height | int | 定义椭圆的边界矩形的高度。 |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要绘制的图像。 |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 定义平行四边形的三个 PointF 结构的数组。 |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要绘制的图像。 |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 定义平行四边形的三个 PointF 结构的数组。 |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要绘制的图像。 |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 定义平行四边形的三个 PointF 结构的数组。 |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 源矩形。 |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要绘制的图像。 |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 定义平行四边形的三个 PointF 结构的数组。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 源矩形。 |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要绘制的图像。 |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 定义平行四边形的三个 PointF 结构的数组。 |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 源矩形。 |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 度量单位。 |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要绘制的图像。 |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 定义平行四边形的三个 PointF 结构的数组。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 源矩形。 |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 度量单位。 |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要绘制的图像。 |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 定义平行四边形的三个 PointF 结构的数组。 |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 源矩形。 |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 度量单位。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 图像属性。 |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

在指定位置并使用指定大小绘制指定的 <paramref name=\"image\" /> 的指定部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要绘制的图像。 |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 定义平行四边形的三个 PointF 结构的数组。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 源矩形。 |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 度量单位。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 图像属性。 |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

在指定位置绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 表示绘制图像左上角的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构。 |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

在指定位置绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| point | [Point](/psd/python-net/aspose.psd/point) | 表示绘制图像左上角的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构。 |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 指定绘制图像位置和大小的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 指定绘制图像位置和大小的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 图形单位。 |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 图形单位。 |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 图形单位。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 图像属性。 |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 目标矩形。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 图形单位。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 图像属性。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形源。 |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形目标。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 图形单位。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形源。 |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形目标。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 图形单位。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形源。 |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形目标。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 图形单位。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 图像属性。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形源。 |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形目标。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 图形单位。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 图像属性。 |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

在指定位置绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| x | float | 绘制图像左上角的 x 坐标。 |
| y | float | 绘制图像左上角的 y 坐标。 |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

在指定位置绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)，使用其原始物理尺寸。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| x | float | 绘制图像左上角的 x 坐标。 |
| y | float | 绘制图像左上角的 y 坐标。 |
| width | float | 绘制图像的宽度。 |
| height | float | 绘制图像的高度。 |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

在指定位置并使用指定大小绘制指定的 [Graphics.image](/psd/python-net/aspose.psd/graphics/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |
| width | int | 绘制图像的宽度。 |
| height | int | 绘制图像的高度。 |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

在指定位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) 结构，指定绘制图像的左上角。 |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

在指定位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 指定绘制图像的左上角。矩形的 X 和 Y 属性指定左上角。Width 和 Height 属性将被忽略。 |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

在由坐标对指定的位置，使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

在指定位置使用其原始物理尺寸绘制指定的图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| x | int | 绘制图像左上角的 x 坐标。 |
| y | int | 绘制图像左上角的 y 坐标。 |
| width | int | 该参数未使用。 |
| height | int | 该参数未使用。 |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

绘制指定的图像而不进行缩放，并在必要时将其裁剪以适应指定的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 要使用的绘制图像。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于绘制图像的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

绘制连接两个 [Point](/psd/python-net/aspose.psd/point/) 结构的直线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定线条的颜色、宽度和样式。 |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) 结构，表示要连接的第一个点。 |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) 结构，表示要连接的第二个点。 |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

绘制连接两个 [Point](/psd/python-net/aspose.psd/point/) 结构的直线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定线条的颜色、宽度和样式。 |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) 结构，表示要连接的第一个点。 |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) 结构，表示要连接的第二个点。 |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

绘制连接由坐标对指定的两点的直线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定线条的颜色、宽度和样式。 |
| x1 | int | 第一个点的 x 坐标。 |
| y1 | int | 第一个点的 y 坐标。 |
| x2 | int | 第二个点的 x 坐标。 |
| y2 | int | 第二个点的 y 坐标。 |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

绘制连接由坐标对指定的两点的直线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定线条的颜色、宽度和样式。 |
| x1 | float | 第一个点的 x 坐标。 |
| y1 | float | 第一个点的 y 坐标。 |
| x2 | float | 第二个点的 x 坐标。 |
| y2 | float | 第二个点的 y 坐标。 |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

绘制一系列连接 [Point](/psd/python-net/aspose.psd/point/) 结构数组的线段。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定线段的颜色、宽度和样式。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 表示要连接的点的 [Point](/psd/python-net/aspose.psd/point/) 结构数组。 |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

绘制一系列连接 [Point](/psd/python-net/aspose.psd/point/) 结构数组的线段。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定线段的颜色、宽度和样式。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 表示要连接的点的 [Point](/psd/python-net/aspose.psd/point/) 结构数组。 |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

绘制一个 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定路径的颜色、宽度和样式。 |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 用于绘制的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定饼形的颜色、宽度和样式。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构，表示定义饼形所在椭圆的外接矩形。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 <paramref name=\"startAngle\" /> 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定饼形的颜色、宽度和样式。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构，表示定义饼形所在椭圆的外接矩形。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 <paramref name=\"startAngle\" /> 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定饼形的颜色、宽度和样式。 |
| x | float | 定义饼形所在椭圆的外接矩形左上角的 x 坐标。 |
| y | float | 定义饼形所在椭圆的外接矩形左上角的 y 坐标。 |
| width | float | 定义饼形所在椭圆的外接矩形的宽度。 |
| height | float | 定义饼形所在椭圆的外接矩形的高度。 |
| start_angle | float | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | float | 从 <paramref name=\"startAngle\" /> 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定饼形的颜色、宽度和样式。 |
| x | int | 定义饼形所在椭圆的外接矩形左上角的 x 坐标。 |
| y | int | 定义饼形所在椭圆的外接矩形左上角的 y 坐标。 |
| width | int | 定义饼形所在椭圆的外接矩形的宽度。 |
| height | int | 定义饼形所在椭圆的外接矩形的高度。 |
| start_angle | int | 从 x 轴顺时针测量到饼形第一边的角度（以度为单位）。 |
| sweep_angle | int | 从 <paramref name=\"startAngle\" /> 参数顺时针测量到饼形第二边的角度（以度为单位）。 |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的多边形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定多边形的颜色、宽度和样式。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 表示多边形顶点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

绘制由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的多边形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 用于确定多边形的颜色、宽度和样式。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 表示多边形顶点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于确定矩形的颜色、宽度和样式的[Pen](/psd/python-net/aspose.psd/pen/)。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 用于表示要绘制的矩形的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构。 |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

绘制由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于确定矩形的颜色、宽度和样式的[Pen](/psd/python-net/aspose.psd/pen/)。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于表示要绘制的矩形的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构。 |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

绘制由坐标对、宽度和高度指定的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于确定矩形的颜色、宽度和样式的[Pen](/psd/python-net/aspose.psd/pen/)。 |
| x | float | 要绘制的矩形左上角的 x 坐标。 |
| y | float | 要绘制的矩形左上角的 y 坐标。 |
| width | float | 要绘制的矩形的宽度。 |
| height | float | 要绘制的矩形的高度。 |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

绘制由坐标对、宽度和高度指定的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于确定矩形的颜色、宽度和样式的[Pen](/psd/python-net/aspose.psd/pen/)。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| width | int | 要绘制的矩形的宽度。 |
| height | int | 要绘制的矩形的高度。 |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

绘制一系列由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于确定矩形轮廓的颜色、宽度和样式的[Pen](/psd/python-net/aspose.psd/pen/)。 |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | 表示要绘制的矩形的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构数组。 |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

绘制一系列由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于确定矩形轮廓的颜色、宽度和样式的[Pen](/psd/python-net/aspose.psd/pen/)。 |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | 表示要绘制的矩形的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构数组。 |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

在指定的矩形中使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象绘制指定的文本字符串。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| s | 字符串 | 要绘制的字符串。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 定义字符串文本格式的[Font](/psd/python-net/aspose.psd/font/)。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定已绘制文本的颜色和纹理的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 指定已绘制文本位置的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构。 |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

在指定的矩形中使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象，并使用指定的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 的格式属性绘制指定的文本字符串。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| s | 字符串 | 要绘制的字符串。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 定义字符串文本格式的[Font](/psd/python-net/aspose.psd/font/)。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定已绘制文本的颜色和纹理的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 指定已绘制文本位置的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构。 |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 指定已绘制文本的格式属性（例如行间距和对齐方式）的[StringFormat](/psd/python-net/aspose.psd/stringformat/)。 |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

在指定位置使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象绘制指定的文本字符串。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| s | 字符串 | 要绘制的字符串。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 定义字符串文本格式的[Font](/psd/python-net/aspose.psd/font/)。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定已绘制文本的颜色和纹理的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 指定已绘制文本左上角的[PointF](/psd/python-net/aspose.psd/pointf/)结构。 |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

在指定位置使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象，并使用指定的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 的格式属性绘制指定的文本字符串。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| s | 字符串 | 要绘制的字符串。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 定义字符串文本格式的[Font](/psd/python-net/aspose.psd/font/)。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定已绘制文本的颜色和纹理的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 指定已绘制文本左上角的[PointF](/psd/python-net/aspose.psd/pointf/)结构。 |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 指定已绘制文本的格式属性（例如行间距和对齐方式）的[StringFormat](/psd/python-net/aspose.psd/stringformat/)。 |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

在指定位置使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象绘制指定的文本字符串。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| s | 字符串 | 要绘制的字符串。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 定义字符串文本格式的[Font](/psd/python-net/aspose.psd/font/)。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定已绘制文本的颜色和纹理的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| x | float | 已绘制文本左上角的 x 坐标。 |
| y | float | 已绘制文本左上角的 y 坐标。 |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

在指定位置使用指定的 [Brush](/psd/python-net/aspose.psd/brush/) 和 [Font](/psd/python-net/aspose.psd/font/) 对象，并使用指定的 [StringFormat](/psd/python-net/aspose.psd/stringformat/) 的格式属性绘制指定的文本字符串。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| s | 字符串 | 要绘制的字符串。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 定义字符串文本格式的[Font](/psd/python-net/aspose.psd/font/)。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定已绘制文本的颜色和纹理的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| x | float | 已绘制文本左上角的 x 坐标。 |
| y | float | 已绘制文本左上角的 y 坐标。 |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 指定已绘制文本的格式属性（例如行间距和对齐方式）的[StringFormat](/psd/python-net/aspose.psd/stringformat/)。 |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5 和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 填充模式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

使用指定的填充模式填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 决定曲线填充方式的[FillMode](/psd/python-net/aspose.psd/fillmode/)枚举成员。 |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

使用指定的填充模式填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组定义的闭合基数样条曲线的内部。此方法使用默认张力 0.5。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 决定曲线填充方式的[FillMode](/psd/python-net/aspose.psd/fillmode/)枚举成员。 |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

使用指定的填充模式和张力，填充由一组 [PointF](/psd/python-net/aspose.psd/pointf/) 结构定义的闭合基数样条曲线的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 用于确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 决定曲线填充方式的[FillMode](/psd/python-net/aspose.psd/fillmode/)枚举成员。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

使用指定的填充模式和张力，填充由一组 [PointF](/psd/python-net/aspose.psd/pointf/) 结构定义的闭合基数样条曲线的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 用于确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 用于定义样条的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 决定曲线填充方式的[FillMode](/psd/python-net/aspose.psd/fillmode/)枚举成员。 |
| 张力 | float | 指定曲线张力的值，必须大于或等于 0.0F。 |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

填充由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的边界矩形定义的椭圆的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示定义椭圆的外接矩形的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构。 |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

填充由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的边界矩形定义的椭圆的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 表示定义椭圆的外接矩形的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构。 |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| x | float | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义椭圆的边界矩形的宽度。 |
| height | float | 定义椭圆的边界矩形的高度。 |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的边界矩形定义的椭圆的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| x | int | 定义椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义椭圆的边界矩形的宽度。 |
| height | int | 定义椭圆的边界矩形的高度。 |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

填充 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 表示要填充的路径的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

填充由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆和两条径向线定义的扇形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 表示定义饼块来源椭圆的外接矩形的[Rectangle](/psd/python-net/aspose.psd/rectangle/)结构。 |
| start_angle | float | 从 x 轴顺时针测量到饼块第一边的角度（度）。 |
| sweep_angle | float | 从 <paramref name="startAngle" /> 参数顺时针测量到饼块第二边的角度（度）。 |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

填充由 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构指定的椭圆和两条径向线定义的扇形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示定义饼块来源椭圆的外接矩形的[Rectangle](/psd/python-net/aspose.psd/rectangle/)结构。 |
| start_angle | float | 从 x 轴顺时针测量到饼块第一边的角度（度）。 |
| sweep_angle | float | 从 <paramref name="startAngle" /> 参数顺时针测量到饼块第二边的角度（度）。 |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的扇形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| x | float | 定义饼图部分所在椭圆的边界矩形左上角的 x 坐标。 |
| y | float | 定义饼图部分所在椭圆的边界矩形左上角的 y 坐标。 |
| width | float | 定义饼图部分所在椭圆的边界矩形的宽度。 |
| height | float | 定义饼图部分所在椭圆的边界矩形的高度。 |
| start_angle | float | 从 x 轴顺时针测量到饼块第一边的角度（度）。 |
| sweep_angle | float | 从 <paramref name="startAngle" /> 参数顺时针测量到饼块第二边的角度（度）。 |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

填充由一对坐标、宽度、高度和两条径向线指定的椭圆定义的扇形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| x | int | 定义饼图部分所在椭圆的边界矩形左上角的 x 坐标。 |
| y | int | 定义饼图部分所在椭圆的边界矩形左上角的 y 坐标。 |
| width | int | 定义饼图部分所在椭圆的边界矩形的宽度。 |
| height | int | 定义饼图部分所在椭圆的边界矩形的高度。 |
| start_angle | int | 从 x 轴顺时针测量到饼块第一边的角度（度）。 |
| sweep_angle | int | 从 <paramref name="startAngle" /> 参数顺时针测量到饼块第二边的角度（度）。 |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构指定的点数组和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 定义的多边形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 表示要填充多边形顶点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构指定的点数组和 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 定义的多边形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 表示要填充多边形顶点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

使用指定的填充模式，填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构指定的点数组定义的多边形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 表示要填充多边形顶点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | [FillMode](/psd/python-net/aspose.psd/fillmode/) 枚举的成员，用于确定填充样式。 |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

使用指定的填充模式，填充由 [PointF](/psd/python-net/aspose.psd/pointf/) 结构指定的点数组定义的多边形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 表示要填充多边形顶点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | [FillMode](/psd/python-net/aspose.psd/fillmode/) 枚举的成员，用于确定填充样式。 |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

填充由 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构指定的矩形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 表示要填充矩形的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。 |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

填充由 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构指定的矩形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示要填充矩形的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。 |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的矩形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| x | float | 要填充矩形左上角的 x 坐标。 |
| y | float | 要填充矩形左上角的 y 坐标。 |
| width | float | 要填充矩形的宽度。 |
| height | float | 要填充矩形的高度。 |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

填充由一对坐标、宽度和高度指定的矩形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| x | int | 要填充矩形左上角的 x 坐标。 |
| y | int | 要填充矩形左上角的 y 坐标。 |
| width | int | 要填充矩形的宽度。 |
| height | int | 要填充矩形的高度。 |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

填充由 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构指定的一系列矩形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | 表示要填充矩形的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构数组。 |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

填充由 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构指定的一系列矩形的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | 表示要填充矩形的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构数组。 |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

填充 [Region](/psd/python-net/aspose.psd/region/) 的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 确定填充特性的[Brush](/psd/python-net/aspose.psd/brush/)。 |
| region | [Region](/psd/python-net/aspose.psd/region) | 表示要填充区域的 [Region](/psd/python-net/aspose.psd/region/)。 |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

通过在前面添加指定的 [Matrix](/psd/python-net/aspose.psd/matrix/)，将表示此 [Graphics](/psd/python-net/aspose.psd/graphics/) 本地几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 相乘。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于乘以几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

按照指定顺序，将表示此 [Graphics](/psd/python-net/aspose.psd/graphics/) 本地几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 相乘。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于乘以几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定两个矩阵相乘顺序的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

按指定的量旋转局部几何变换。此方法将在变换前置旋转。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

按指定的量并按照指定顺序旋转局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定是追加还是前置旋转矩阵的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

按指定的比例缩放局部几何变换。此方法将在变换前置缩放矩阵。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

按指定的比例并按照指定顺序缩放局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定是追加还是前置缩放矩阵的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移局部几何变换。此方法将在变换前置平移。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

按指定的尺寸并按照指定顺序平移局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 应用平移的顺序（前置或后置）。 |

