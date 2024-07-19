---
title: Graphics Class
type: docs
weight: 1490
url: /python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initializes a new instance of the [Graphics](/psd/python-net/aspose.psd/graphics/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Gets or sets the clip region. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Gets or sets the compositing quality. |
| dpi_x | float | r | Gets the horizontal resolution of this Aspose.PSD.Graphics. |
| dpi_y | float | r | Gets the vertical resolution of this Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Gets the image. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Gets or sets the interpolation mode. |
| is_in_begin_update_call | bool | r | Gets a value indicating whether graphics is in BeginUpdate call state. |
| page_scale | float | r/w | Gets or sets the scaling between world units and page units for this Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Gets or sets the unit of measure used for page coordinates in this Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Gets or sets image options, used to create paintable vactor images to draw. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Gets or sets the smoothing mode. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Gets or sets the text rendering hint. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Gets or sets a copy of the geometric world transformation for this [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| begin_update() | Starts caching of the following graphics operations. The graphics effects applied afterwards will not be applied immediately instead the EndUpdate will cause applying all the effects at once. |
| [clear(color)](#clear_color_1) | Clears the graphics surface using the specified color. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Draws an arc representing a portion of an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Draws an arc representing a portion of an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Draws a Bézier spline defined by four [PointF](/psd/python-net/aspose.psd/pointf/) structures. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Draws a Bézier spline defined by four [PointF](/psd/python-net/aspose.psd/pointf/) structures. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Draws a Bézier spline defined by four ordered pairs of coordinates that represent points. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Draws a series of Bézier splines from an array of [Point](/psd/python-net/aspose.psd/point/) structures. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Draws a series of Bézier splines from an array of [Point](/psd/python-net/aspose.psd/point/) structures. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Draws a closed cardinal spline defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Draws a closed cardinal spline defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Draws a closed cardinal spline defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Draws a closed cardinal spline defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode. |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. The drawing begins offset from the beginning of the array.<br/>            This method uses a default tension of 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Draws an ellipse defined by a bounding [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Draws an ellipse defined by a bounding [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/), using its original physical size, at the specified location. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/), using its original physical size, at the specified location. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/), using its original physical size, at the specified location. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/), using its original physical size, at the specified location. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Draws a specified image using its original physical size at a specified location. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Draws a specified image using its original physical size at a specified location. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Draws the specified image using its original physical size at the location specified by a coordinate pair. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Draws a specified image using its original physical size at a specified location. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Draws a line connecting two [Point](/psd/python-net/aspose.psd/point/) structures. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Draws a line connecting two [Point](/psd/python-net/aspose.psd/point/) structures. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Draws a line connecting the two points specified by the coordinate pairs. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Draws a line connecting the two points specified by the coordinate pairs. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Draws a series of line segments that connect an array of [Point](/psd/python-net/aspose.psd/point/) structures. |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Draws a series of line segments that connect an array of [Point](/psd/python-net/aspose.psd/point/) structures. |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Draws a [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Draws a pie shape defined by an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure and two radial lines. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Draws a pie shape defined by an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure and two radial lines. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Draws a polygon defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Draws a polygon defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Draws a rectangle specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Draws a rectangle specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Draws a rectangle specified by a coordinate pair, a width, and a height. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Draws a series of rectangles specified by [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structures. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Draws a series of rectangles specified by [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structures. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Draws the specified text string in the specified rectangle with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Draws the specified text string in the specified rectangle with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects using the formatting attributes of the specified [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Draws the specified text string at the specified location with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Draws the specified text string at the specified location with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects using the formatting attributes of the specified [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Draws the specified text string at the specified location with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Draws the specified text string at the specified location with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects using the formatting attributes of the specified [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | Finishes caching of the graphics operations started after BeginUpdate was called. The preceding graphics operations will be applied at once when calling this method. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode and tension. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode and tension. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Fills the interior of a [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure and two radial lines. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure and two radial lines. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Fills the interior of a polygon defined by an array of points specified by [PointF](/psd/python-net/aspose.psd/pointf/) structures and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Fills the interior of a polygon defined by an array of points specified by [PointF](/psd/python-net/aspose.psd/pointf/) structures and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Fills the interior of a polygon defined by an array of points specified by [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Fills the interior of a polygon defined by an array of points specified by [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Fills the interior of a rectangle specified by a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Fills the interior of a rectangle specified by a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Fills the interior of a rectangle specified by a pair of coordinates, a width and a height. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Fills the interiors of a series of rectangles specified by [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Fills the interiors of a series of rectangles specified by [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures. |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Fills the interior of a [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [Graphics](/psd/python-net/aspose.psd/graphics/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) by prepending the specified [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [Graphics](/psd/python-net/aspose.psd/graphics/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) in the specified order. |
| reset_transform() | Resets the [Graphics.transform](/psd/python-net/aspose.psd/graphics/) property to identity. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Rotates the local geometric transform by the specified amount in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Scales the local geometric transform by the specified amounts in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Translates the local geometric transform by the specified dimensions in the specified order. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initializes a new instance of the [Graphics](/psd/python-net/aspose.psd/graphics/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The source image. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Clears the graphics surface using the specified color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | The color to clear the graphics surface by. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the arc. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that defines the boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the <paramref name="startAngle" /> parameter to ending point of the arc. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the arc. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that defines the boundaries of the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the <paramref name="startAngle" /> parameter to ending point of the arc. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the arc. |
| x | float | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | float | Width of the rectangle that defines the ellipse. |
| height | float | Height of the rectangle that defines the ellipse. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | float | Angle in degrees measured clockwise from the <paramref name="startAngle" /> parameter to ending point of the arc. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws an arc representing a portion of an ellipse specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the arc. |
| x | int | The x-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the rectangle that defines the ellipse. |
| width | int | Width of the rectangle that defines the ellipse. |
| height | int | Height of the rectangle that defines the ellipse. |
| start_angle | int | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweep_angle | int | Angle in degrees measured clockwise from the <paramref name="startAngle" /> parameter to ending point of the arc. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Draws a Bézier spline defined by four [PointF](/psd/python-net/aspose.psd/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the curve. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the starting point of the curve. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the first control point for the curve. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the second control point for the curve. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the ending point of the curve. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Draws a Bézier spline defined by four [PointF](/psd/python-net/aspose.psd/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the curve. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the starting point of the curve. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the first control point for the curve. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the second control point for the curve. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the ending point of the curve. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Draws a Bézier spline defined by four ordered pairs of coordinates that represent points.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the curve. |
| x1 | float | The x-coordinate of the starting point of the curve. |
| y1 | float | The y-coordinate of the starting point of the curve. |
| x2 | float | The x-coordinate of the first control point of the curve. |
| y2 | float | The y-coordinate of the first control point of the curve. |
| x3 | float | The x-coordinate of the second control point of the curve. |
| y3 | float | The y-coordinate of the second control point of the curve. |
| x4 | float | The x-coordinate of the ending point of the curve. |
| y4 | float | The y-coordinate of the ending point of the curve. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Draws a series of Bézier splines from an array of [Point](/psd/python-net/aspose.psd/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the curve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [Point](/psd/python-net/aspose.psd/point/) structures that represent the points that determine the curve. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Draws a series of Bézier splines from an array of [Point](/psd/python-net/aspose.psd/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the curve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [Point](/psd/python-net/aspose.psd/point/) structures that represent the points that determine the curve. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Draws a closed cardinal spline defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Draws a closed cardinal spline defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Draws a closed cardinal spline defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Draws a closed cardinal spline defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. This method uses a default [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. The drawing begins offset from the beginning of the array.<br/>            This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| offset | int | Offset from the first element in the array of the <paramref name="points" /> parameter to the starting point in the curve. |
| number_of_segments | int | Number of segments after the starting point to include in the curve. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| offset | int | Offset from the first element in the array of the <paramref name="points" /> parameter to the starting point in the curve. |
| number_of_segments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension. The drawing begins offset from the beginning of the array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| offset | int | Offset from the first element in the array of the <paramref name="points" /> parameter to the starting point in the curve. |
| number_of_segments | int | Number of segments after the starting point to include in the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represent the points that define the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Draws a cardinal spline through a specified array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using a specified tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and height of the curve. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represent the points that define the curve. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Draws an ellipse defined by a bounding [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the ellipse. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that defines the boundaries of the ellipse. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Draws an ellipse defined by a bounding [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the ellipse. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that defines the boundaries of the ellipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the ellipse. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Draws an ellipse defined by a bounding rectangle specified by a pair of coordinates, a height, and a width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the ellipse. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to draw. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array of three PointF structures that define a parallelogram. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to draw. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of three PointF structures that define a parallelogram. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to draw. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The source rectangle. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to draw. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The source rectangle. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to draw. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The source rectangle. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The units of measure. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to draw. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The source rectangle. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The units of measure. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to draw. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array of three PointF structures that define a parallelogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The source rectangle. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The units of measure. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | The image attributes. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Draws the specified portion of the specified <paramref name="image" /> at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to draw. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of three PointF structures that define a parallelogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The source rectangle. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The units of measure. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | The image attributes. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the upper-left corner of the drawn image. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| point | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that represents the upper-left corner of the drawn image. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that specifies the location and size of the drawn image. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that specifies the location and size of the drawn image. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The graphics unit. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The graphics unit. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The graphics unit. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | The image attributes. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The destination rectangle. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The graphics unit. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | The image attributes. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rect source. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rect destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The graphics unit. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The rect source. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The rect destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The graphics unit. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rect source. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rect destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The graphics unit. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | The image attributes. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The rect source. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The rect destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | The graphics unit. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | The image attributes. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/), using its original physical size, at the specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| x | float | The x-coordinate of the upper-left corner of the drawn image. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |
| width | float | Width of the drawn image. |
| height | float | Height of the drawn image. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Draws the specified [Graphics.image](/psd/python-net/aspose.psd/graphics/) at the specified location and with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | Width of the drawn image. |
| height | int | Height of the drawn image. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Draws a specified image using its original physical size at a specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structure that specifies the upper-left corner of the drawn image. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Draws a specified image using its original physical size at a specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) that specifies the upper-left corner of the drawn image. The X and Y properties of the rectangle specify the upper-left corner. The Width and Height properties are ignored. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Draws the specified image using its original physical size at the location specified by a coordinate pair.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Draws a specified image using its original physical size at a specified location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| x | int | The x-coordinate of the upper-left corner of the drawn image. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| width | int | The parameter is not used. |
| height | int | The parameter is not used. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Draws the specified image without scaling and clips it, if necessary, to fit in the specified rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | The image to draw with. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [Rectangle](/psd/python-net/aspose.psd/rectangle/) in which to draw the image. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Draws a line connecting two [Point](/psd/python-net/aspose.psd/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the line. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structure that represents the first point to connect. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structure that represents the second point to connect. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Draws a line connecting two [Point](/psd/python-net/aspose.psd/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the line. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) structure that represents the first point to connect. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) structure that represents the second point to connect. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the line. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Draws a line connecting the two points specified by the coordinate pairs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the line. |
| x1 | float | The x-coordinate of the first point. |
| y1 | float | The y-coordinate of the first point. |
| x2 | float | The x-coordinate of the second point. |
| y2 | float | The y-coordinate of the second point. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Draws a series of line segments that connect an array of [Point](/psd/python-net/aspose.psd/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the line segments. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [Point](/psd/python-net/aspose.psd/point/) structures that represent the points to connect. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Draws a series of line segments that connect an array of [Point](/psd/python-net/aspose.psd/point/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the line segments. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [Point](/psd/python-net/aspose.psd/point/) structures that represent the points to connect. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Draws a [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the path. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) to draw. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the pie shape. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the <paramref name="startAngle" /> parameter to the second side of the pie shape. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the pie shape. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the <paramref name="startAngle" /> parameter to the second side of the pie shape. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the pie shape. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | float | Angle measured in degrees clockwise from the <paramref name="startAngle" /> parameter to the second side of the pie shape. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Draws a pie shape defined by an ellipse specified by a coordinate pair, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the pie shape. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie shape comes. |
| start_angle | int | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweep_angle | int | Angle measured in degrees clockwise from the <paramref name="startAngle" /> parameter to the second side of the pie shape. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Draws a polygon defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the polygon. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represent the vertices of the polygon. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Draws a polygon defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the polygon. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represent the vertices of the polygon. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Draws a rectangle specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | A [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the rectangle. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the rectangle to draw. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Draws a rectangle specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | A [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the rectangle. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the rectangle to draw. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | A [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the rectangle. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | float | The width of the rectangle to draw. |
| height | float | The height of the rectangle to draw. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Draws a rectangle specified by a coordinate pair, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | A [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the rectangle. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Draws a series of rectangles specified by [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array of [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structures that represent the rectangles to draw. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Draws a series of rectangles specified by [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) that determines the color, width, and style of the outlines of the rectangles. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array of [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structures that represent the rectangles to draw. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Draws the specified text string in the specified rectangle with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) that defines the text format of the string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the color and texture of the drawn text. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that specifies the location of the drawn text. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Draws the specified text string in the specified rectangle with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects using the formatting attributes of the specified [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) that defines the text format of the string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the color and texture of the drawn text. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that specifies the location of the drawn text. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Draws the specified text string at the specified location with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) that defines the text format of the string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the color and texture of the drawn text. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that specifies the upper-left corner of the drawn text. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Draws the specified text string at the specified location with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects using the formatting attributes of the specified [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) that defines the text format of the string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the color and texture of the drawn text. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure that specifies the upper-left corner of the drawn text. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Draws the specified text string at the specified location with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) that defines the text format of the string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Draws the specified text string at the specified location with the specified [Brush](/psd/python-net/aspose.psd/brush/) and [Font](/psd/python-net/aspose.psd/font/) objects using the formatting attributes of the specified [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | String to draw. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) that defines the text format of the string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the color and texture of the drawn text. |
| x | float | The x-coordinate of the upper-left corner of the drawn text. |
| y | float | The y-coordinate of the upper-left corner of the drawn text. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures. This method uses a default tension of 0.5 and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Member of the [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeration that determines how the curve is filled. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode. This method uses a default tension of 0.5.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Member of the [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeration that determines how the curve is filled. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode and tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | A [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Member of the [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Fills the interior of a closed cardinal spline curve defined by an array of [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode and tension.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | A [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that define the spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Member of the [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeration that determines how the curve is filled. |
| tension | float | Value greater than or equal to 0.0F that specifies the tension of the curve. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | float | Width of the bounding rectangle that defines the ellipse. |
| height | float | Height of the bounding rectangle that defines the ellipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Fills the interior of an ellipse defined by a bounding rectangle specified by a pair of coordinates, a width, and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse. |
| width | int | Width of the bounding rectangle that defines the ellipse. |
| height | int | Height of the bounding rectangle that defines the ellipse. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Fills the interior of a [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) that represents the path to fill. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the <paramref name="startAngle" /> parameter to the second side of the pie section. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that represents the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the <paramref name="startAngle" /> parameter to the second side of the pie section. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | float | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | float | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | float | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | float | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | float | Angle in degrees measured clockwise from the <paramref name="startAngle" /> parameter to the second side of the pie section. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Fills the interior of a pie section defined by an ellipse specified by a pair of coordinates, a width, a height, and two radial lines.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| y | int | The y-coordinate of the upper-left corner of the bounding rectangle that defines the ellipse from which the pie section comes. |
| width | int | Width of the bounding rectangle that defines the ellipse from which the pie section comes. |
| height | int | Height of the bounding rectangle that defines the ellipse from which the pie section comes. |
| start_angle | int | Angle in degrees measured clockwise from the x-axis to the first side of the pie section. |
| sweep_angle | int | Angle in degrees measured clockwise from the <paramref name="startAngle" /> parameter to the second side of the pie section. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/psd/python-net/aspose.psd/pointf/) structures and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represent the vertices of the polygon to fill. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/psd/python-net/aspose.psd/pointf/) structures and [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represent the vertices of the polygon to fill. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represent the vertices of the polygon to fill. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Member of the [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeration that determines the style of the fill. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Fills the interior of a polygon defined by an array of points specified by [PointF](/psd/python-net/aspose.psd/pointf/) structures using the specified fill mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represent the vertices of the polygon to fill. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Member of the [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeration that determines the style of the fill. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Fills the interior of a rectangle specified by a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that represents the rectangle to fill. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Fills the interior of a rectangle specified by a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that represents the rectangle to fill. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| x | float | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | float | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | float | Width of the rectangle to fill. |
| height | float | Height of the rectangle to fill. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Fills the interior of a rectangle specified by a pair of coordinates, a width and a height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to fill. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to fill. |
| width | int | Width of the rectangle to fill. |
| height | int | Height of the rectangle to fill. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Fills the interiors of a series of rectangles specified by [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array of [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures that represent the rectangles to fill. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Fills the interiors of a series of rectangles specified by [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array of [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures that represent the rectangles to fill. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Fills the interior of a [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) that determines the characteristics of the fill. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) that represents the area to fill. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [Graphics](/psd/python-net/aspose.psd/graphics/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) by prepending the specified [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) by which to multiply the geometric transform. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [Graphics](/psd/python-net/aspose.psd/graphics/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) by which to multiply the geometric transform. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies in which order to multiply the two matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | The order (prepend or append) in which to apply the translation. |

