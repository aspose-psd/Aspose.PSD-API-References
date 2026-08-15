---
title: "Graphics 클래스"
type: docs
weight: 1550
url: /ko/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | [Graphics](/psd/python-net/aspose.psd/graphics/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | 클립 영역을 가져오거나 설정합니다. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | 합성 품질을 가져오거나 설정합니다. |
| dpi_x | float | r | 이 Aspose.PSD.Graphics의 가로 해상도를 가져옵니다. |
| dpi_y | float | r | 이 Aspose.PSD.Graphics의 수직 해상도를 가져옵니다. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | 이미지를 가져옵니다. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | 보간 모드를 가져오거나 설정합니다. |
| is_in_begin_update_call | bool | r | 그래픽이 BeginUpdate 호출 상태에 있는지 여부를 나타내는 값을 가져옵니다. |
| page_scale | float | r/w | 이 Aspose.PSD.Graphics에 대한 세계 단위와 페이지 단위 사이의 스케일을 가져오거나 설정합니다. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | 이 Aspose.PSD.Graphics에서 페이지 좌표에 사용되는 측정 단위를 가져오거나 설정합니다. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | 그리기용 페인팅 가능한 벡터 이미지를 만들 때 사용되는 이미지 옵션을 가져오거나 설정합니다. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | 스무딩 모드를 가져오거나 설정합니다. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | 텍스트 렌더링 힌트를 가져오거나 설정합니다. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | 이 [Graphics](/psd/python-net/aspose.psd/graphics/)에 대한 기하학적 세계 변환의 복사본을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| begin_update() | 다음 그래픽 작업에 대한 캐싱을 시작합니다. 이후 적용되는 그래픽 효과는 즉시 적용되지 않고 EndUpdate가 호출될 때 한 번에 모두 적용됩니다. |
| [clear(color)](#clear_color_1) | 지정된 색상을 사용하여 그래픽 표면을 지웁니다. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | 좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | 좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | 네 개의 [PointF](/psd/python-net/aspose.psd/pointf/) 구조로 정의된 베지어 스플라인을 그립니다. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | 네 개의 [PointF](/psd/python-net/aspose.psd/pointf/) 구조로 정의된 베지어 스플라인을 그립니다. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | 점을 나타내는 네 개의 순서쌍 좌표로 정의된 베지어 스플라인을 그립니다. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | [Point](/psd/python-net/aspose.psd/point/) 구조 배열에서 베지어 스플라인 시리즈를 그립니다. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | [Point](/psd/python-net/aspose.psd/point/) 구조 배열에서 베지어 스플라인 시리즈를 그립니다. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인을 지정된 텐션을 사용하여 그립니다. 이 메서드는 기본 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인을 지정된 텐션을 사용하여 그립니다. 이 메서드는 기본 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다. |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5를 사용합니다. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5를 사용합니다. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작점에서 오프셋을 두고 시작됩니다.<br/>            이 메서드는 기본 텐션 0.5를 사용합니다. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | 지정된 텐션을 사용하여 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작점에서 오프셋을 두고 시작됩니다. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | 지정된 텐션을 사용하여 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작점에서 오프셋을 두고 시작됩니다. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | 지정된 텐션을 사용하여 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | 지정된 텐션을 사용하여 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | 경계 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 로 정의된 타원을 그립니다. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | 경계 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 로 정의된 타원을 그립니다. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | 좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | 좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | 지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | 지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | 지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | 지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | 지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | 지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | 지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | 지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | 지정된 위치에 원본 물리적 크기를 사용하여 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | 지정된 위치에 원본 물리적 크기를 사용하여 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | 지정된 위치에 원본 물리적 크기를 사용하여 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | 지정된 위치에 원본 물리적 크기를 사용하여 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | 지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | 지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | 지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | 좌표 쌍으로 지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | 지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | 지정된 이미지를 스케일링하지 않고 그리며, 필요에 따라 지정된 사각형에 맞게 클리핑합니다. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | 두 개의 [Point](/psd/python-net/aspose.psd/point/) 구조를 연결하는 선을 그립니다. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | 두 개의 [Point](/psd/python-net/aspose.psd/point/) 구조를 연결하는 선을 그립니다. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | 좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | 좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | [Point](/psd/python-net/aspose.psd/point/) 구조 배열을 연결하는 일련의 선분을 그립니다. |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | [Point](/psd/python-net/aspose.psd/point/) 구조 배열을 연결하는 일련의 선분을 그립니다. |
| [draw_path(pen, path)](#draw_path_pen_path_61) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)을 그립니다. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 다각형을 그립니다. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 다각형을 그립니다. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 사각형을 그립니다. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 사각형을 그립니다. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | 좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | 좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에 의해 지정된 일련의 사각형을 그립니다. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에 의해 지정된 일련의 사각형을 그립니다. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 사각형에 지정된 텍스트 문자열을 그립니다. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | 지정된 [StringFormat](/psd/python-net/aspose.psd/stringformat/)의 서식 속성을 사용하여 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 사각형에 지정된 텍스트 문자열을 그립니다. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | 지정된 위치에 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 텍스트 문자열을 그립니다. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | 지정된 [StringFormat](/psd/python-net/aspose.psd/stringformat/)의 서식 속성을 사용하여 지정된 위치에 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 텍스트 문자열을 그립니다. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | 지정된 위치에 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 텍스트 문자열을 그립니다. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | 지정된 [StringFormat](/psd/python-net/aspose.psd/stringformat/)의 서식 속성을 사용하여 지정된 위치에 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 텍스트 문자열을 그립니다. |
| end_update() | BeginUpdate가 호출된 후 시작된 그래픽 작업의 캐시를 완료합니다. 이전 그래픽 작업은 이 메서드를 호출할 때 한 번에 적용됩니다. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 지정된 채우기 모드를 사용하여 채웁니다. 이 메서드는 기본 텐션 0.5를 사용합니다. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 지정된 채우기 모드를 사용하여 채웁니다. 이 메서드는 기본 텐션 0.5를 사용합니다. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | 지정된 채우기 모드와 장력을 사용하여 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | 지정된 채우기 모드와 장력을 사용하여 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | 좌표 쌍, 너비 및 높이로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | 좌표 쌍, 너비 및 높이로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 내부를 채웁니다. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조로 지정된 점 배열과 지정된 채우기 모드를 사용하여 정의된 다각형의 내부를 채웁니다. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조로 지정된 점 배열과 지정된 채우기 모드를 사용하여 정의된 다각형의 내부를 채웁니다. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 지정된 사각형의 내부를 채웁니다. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 지정된 사각형의 내부를 채웁니다. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | 좌표 쌍, 너비 및 높이로 지정된 사각형의 내부를 채웁니다. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | 좌표 쌍, 너비 및 높이로 지정된 사각형의 내부를 채웁니다. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 지정된 일련의 사각형들의 내부를 채웁니다. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 지정된 일련의 사각형들의 내부를 채웁니다. |
| [fill_region(brush, region)](#fill_region_brush_region_105) | [Region](/psd/python-net/aspose.psd/region/)의 내부를 채웁니다. |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | 이 [Graphics](/psd/python-net/aspose.psd/graphics/)의 로컬 기하 변환을 나타내는 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 앞에 추가하여 곱합니다. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | 이 [Graphics](/psd/python-net/aspose.psd/graphics/)의 로컬 기하 변환을 나타내는 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 순서대로 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 곱합니다. |
| reset_transform() | [Graphics.transform](/psd/python-net/aspose.psd/graphics/) 속성을 항등 행렬로 재설정합니다. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | 지정된 양만큼 로컬 기하 변환을 회전시킵니다. 이 메서드는 회전을 변환 앞에 추가합니다. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 회전시킵니다. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | 지정된 양큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | 지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

[Graphics](/psd/python-net/aspose.psd/graphics/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 소스 이미지입니다. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

지정된 색상을 사용하여 그래픽 표면을 지웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 그래픽 표면을 지우는 색상입니다. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 타원의 일부를 나타내는 호를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 호의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 타원의 경계를 정의하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |
| start_angle | float | 시계 방향으로 x축에서 호의 시작점까지 측정한 각도(도)입니다. |
| sweep_angle | float | <paramref name="startAngle" /> 매개변수에서 호의 끝점까지 시계 방향으로 측정한 각도(도)입니다. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 타원의 일부를 나타내는 호를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 호의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 타원의 경계를 정의하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |
| start_angle | float | 시계 방향으로 x축에서 호의 시작점까지 측정한 각도(도)입니다. |
| sweep_angle | float | <paramref name="startAngle" /> 매개변수에서 호의 끝점까지 시계 방향으로 측정한 각도(도)입니다. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 호의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| x | float | 타원을 정의하는 사각형의 왼쪽 위 모서리의 x좌표입니다. |
| y | float | 타원을 정의하는 사각형의 왼쪽 위 모서리의 y좌표입니다. |
| width | float | 타원을 정의하는 사각형의 너비입니다. |
| 높이 | float | 타원을 정의하는 사각형의 높이입니다. |
| start_angle | float | 시계 방향으로 x축에서 호의 시작점까지 측정한 각도(도)입니다. |
| sweep_angle | float | <paramref name="startAngle" /> 매개변수에서 호의 끝점까지 시계 방향으로 측정한 각도(도)입니다. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 호의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| x | int | 타원을 정의하는 사각형의 왼쪽 위 모서리의 x좌표입니다. |
| y | int | 타원을 정의하는 사각형의 왼쪽 위 모서리의 y좌표입니다. |
| width | int | 타원을 정의하는 사각형의 너비입니다. |
| 높이 | int | 타원을 정의하는 사각형의 높이입니다. |
| start_angle | int | 시계 방향으로 x축에서 호의 시작점까지 측정한 각도(도)입니다. |
| sweep_angle | int | <paramref name="startAngle" /> 매개변수에서 호의 끝점까지 시계 방향으로 측정한 각도(도)입니다. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

네 개의 [PointF](/psd/python-net/aspose.psd/pointf/) 구조로 정의된 베지어 스플라인을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조는 곡선의 시작점을 나타냅니다. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조는 곡선의 첫 번째 제어점을 나타냅니다. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조는 곡선의 두 번째 제어점을 나타냅니다. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조는 곡선의 끝점을 나타냅니다. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

네 개의 [PointF](/psd/python-net/aspose.psd/pointf/) 구조로 정의된 베지어 스플라인을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조는 곡선의 시작점을 나타냅니다. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조는 곡선의 첫 번째 제어점을 나타냅니다. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조는 곡선의 두 번째 제어점을 나타냅니다. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조는 곡선의 끝점을 나타냅니다. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

점을 나타내는 네 개의 순서쌍 좌표로 정의된 베지어 스플라인을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| x1 | float | 곡선 시작점의 x좌표. |
| y1 | float | 곡선 시작점의 y좌표. |
| x2 | float | 곡선 첫 번째 제어점의 x좌표. |
| y2 | float | 곡선 첫 번째 제어점의 y좌표. |
| x3 | float | 곡선 두 번째 제어점의 x좌표. |
| y3 | float | 곡선 두 번째 제어점의 y좌표. |
| x4 | float | 곡선 끝점의 x좌표. |
| y4 | float | 곡선 끝점의 y좌표. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

[Point](/psd/python-net/aspose.psd/point/) 구조 배열에서 베지어 스플라인 시리즈를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) 구조체 배열은 곡선을 결정하는 점들을 나타냅니다. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

[Point](/psd/python-net/aspose.psd/point/) 구조 배열에서 베지어 스플라인 시리즈를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 스타일을 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) 구조체 배열은 곡선을 결정하는 점들을 나타냅니다. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인을 지정된 텐션을 사용하여 그립니다. 이 메서드는 기본 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| 텐션 | float | 곡선의 장력을 지정하는 0.0F 이상 값. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인을 지정된 텐션을 사용하여 그립니다. 이 메서드는 기본 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| 텐션 | float | 곡선의 장력을 지정하는 0.0F 이상 값. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작점에서 오프셋을 두고 시작됩니다.<br/>            이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| offset | int | 곡선의 시작점까지 <paramref name="points" /> 매개변수 배열의 첫 번째 요소로부터의 오프셋. |
| number_of_segments | int | 곡선에 포함할 시작점 이후의 세그먼트 수. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

지정된 텐션을 사용하여 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작점에서 오프셋을 두고 시작됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| offset | int | 곡선의 시작점까지 <paramref name="points" /> 매개변수 배열의 첫 번째 요소로부터의 오프셋. |
| number_of_segments | int | 곡선에 포함할 시작점 이후의 세그먼트 수. |
| 텐션 | float | 곡선의 장력을 지정하는 0.0F 이상 값. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

지정된 텐션을 사용하여 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작점에서 오프셋을 두고 시작됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| offset | int | 곡선의 시작점까지 <paramref name="points" /> 매개변수 배열의 첫 번째 요소로부터의 오프셋. |
| number_of_segments | int | 곡선에 포함할 시작점 이후의 세그먼트 수. |
| 텐션 | float | 곡선의 장력을 지정하는 0.0F 이상 값. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

지정된 텐션을 사용하여 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 곡선을 정의하는 점들을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열. |
| 텐션 | float | 곡선의 장력을 지정하는 0.0F 이상 값. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

지정된 텐션을 사용하여 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열을 통해 카디널 스플라인을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) 곡선의 색상, 너비 및 높이를 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 곡선을 정의하는 점들을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열. |
| 텐션 | float | 곡선의 장력을 지정하는 0.0F 이상 값. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

경계 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 로 정의된 타원을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 타원의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 타원의 경계를 정의하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

경계 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 로 정의된 타원을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 타원의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 타원의 경계를 정의하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 타원의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/). |
| x | float | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | float | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표. |
| width | float | 타원을 정의하는 경계 사각형의 너비. |
| 높이 | float | 타원을 정의하는 경계 사각형의 높이. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 타원의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/). |
| x | int | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | int | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표. |
| width | int | 타원을 정의하는 경계 사각형의 너비. |
| 높이 | int | 타원을 정의하는 경계 사각형의 높이. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 소스 사각형. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 소스 사각형. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 소스 사각형. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 측정 단위. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 소스 사각형. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 측정 단위. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 소스 사각형. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 측정 단위. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 이미지 속성. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

지정된 위치와 지정된 크기로 지정된 <paramref name="image" />의 지정된 부분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 소스 사각형. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 측정 단위. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 이미지 속성. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

지정된 위치에 원본 물리적 크기를 사용하여 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 그려진 이미지의 왼쪽 위 모서리를 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

지정된 위치에 원본 물리적 크기를 사용하여 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| point | [Point](/psd/python-net/aspose.psd/point) | 그려진 이미지의 왼쪽 위 모서리를 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 그려진 이미지의 위치와 크기를 지정하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 그려진 이미지의 위치와 크기를 지정하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 사각형. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 그래픽 단위. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 대상 사각형. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 그래픽 단위. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 사각형. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 그래픽 단위. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 이미지 속성. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 대상 사각형. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 그래픽 단위. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 이미지 속성. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 원본 rect. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 그래픽 단위. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 원본 rect. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 대상 rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 그래픽 단위. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 원본 rect. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 대상 rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 그래픽 단위. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 이미지 속성. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 원본 rect. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 대상 rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 그래픽 단위. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 이미지 속성. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

지정된 위치에 원본 물리적 크기를 사용하여 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| x | float | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | float | 그려진 이미지의 왼쪽 위 모서리의 y 좌표. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

지정된 위치에 원본 물리적 크기를 사용하여 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | int | 그려진 이미지의 왼쪽 위 모서리의 y 좌표. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| x | float | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | float | 그려진 이미지의 왼쪽 위 모서리의 y 좌표. |
| width | float | 그려진 이미지의 너비. |
| 높이 | float | 그려진 이미지의 높이. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

지정된 위치와 지정된 크기로 지정된 [Graphics.image](/psd/python-net/aspose.psd/graphics/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | int | 그려진 이미지의 왼쪽 위 모서리의 y 좌표. |
| width | int | 그려진 이미지의 너비. |
| 높이 | int | 그려진 이미지의 높이. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) 구조는 그려진 이미지의 왼쪽 위 모서리를 지정합니다. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 은 그려진 이미지의 왼쪽 위 모서리를 지정합니다. 사각형의 X 및 Y 속성은 왼쪽 위 모서리를 지정합니다. Width 및 Height 속성은 무시됩니다. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

좌표 쌍으로 지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | int | 그려진 이미지의 왼쪽 위 모서리의 y 좌표. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

지정된 위치에 원본 물리적 크기를 사용하여 지정된 이미지를 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | int | 그려진 이미지의 왼쪽 위 모서리의 y 좌표. |
| width | int | 매개변수가 사용되지 않습니다. |
| 높이 | int | 매개변수가 사용되지 않습니다. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

지정된 이미지를 스케일링하지 않고 그리며, 필요에 따라 지정된 사각형에 맞게 클리핑합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 그릴 이미지. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 이미지를 그릴 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 입니다. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

두 개의 [Point](/psd/python-net/aspose.psd/point/) 구조를 연결하는 선을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 선의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | 연결할 첫 번째 점을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조입니다. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | 연결할 두 번째 점을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조입니다. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

두 개의 [Point](/psd/python-net/aspose.psd/point/) 구조를 연결하는 선을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 선의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | 연결할 첫 번째 점을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조입니다. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | 연결할 두 번째 점을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조입니다. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 선의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| x1 | int | 첫 번째 점의 x 좌표입니다. |
| y1 | int | 첫 번째 점의 y 좌표입니다. |
| x2 | int | 두 번째 점의 x 좌표입니다. |
| y2 | int | 두 번째 점의 y 좌표입니다. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 선의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| x1 | float | 첫 번째 점의 x 좌표입니다. |
| y1 | float | 첫 번째 점의 y 좌표입니다. |
| x2 | float | 두 번째 점의 x 좌표입니다. |
| y2 | float | 두 번째 점의 y 좌표입니다. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

[Point](/psd/python-net/aspose.psd/point/) 구조 배열을 연결하는 일련의 선분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 선분의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 연결할 점들을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조의 배열입니다. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

[Point](/psd/python-net/aspose.psd/point/) 구조 배열을 연결하는 일련의 선분을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 선분의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 연결할 점들을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조의 배열입니다. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 경로의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 그릴 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 입니다. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 파이 모양의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 파이 모양이 나오는 타원을 정의하는 경계 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |
| start_angle | float | x축에서 파이 모양의 첫 번째 변까지 시계 방향으로 측정한 각도(도)입니다. |
| sweep_angle | float | <paramref name="startAngle" /> 매개변수에서 파이 모양의 두 번째 변까지 시계 방향으로 측정한 각도(도)입니다. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 파이 모양의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 파이 모양이 나오는 타원을 정의하는 경계 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |
| start_angle | float | x축에서 파이 모양의 첫 번째 변까지 시계 방향으로 측정한 각도(도)입니다. |
| sweep_angle | float | <paramref name="startAngle" /> 매개변수에서 파이 모양의 두 번째 변까지 시계 방향으로 측정한 각도(도)입니다. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 파이 모양의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| x | float | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | float | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| width | float | 파이 모양이 나오는 경계 사각형의 너비입니다. |
| 높이 | float | 파이 모양이 나오는 경계 사각형의 높이입니다. |
| start_angle | float | x축에서 파이 모양의 첫 번째 변까지 시계 방향으로 측정한 각도(도)입니다. |
| sweep_angle | float | <paramref name="startAngle" /> 매개변수에서 파이 모양의 두 번째 변까지 시계 방향으로 측정한 각도(도)입니다. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 파이 모양의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| x | int | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | int | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| width | int | 파이 모양이 나오는 경계 사각형의 너비입니다. |
| 높이 | int | 파이 모양이 나오는 경계 사각형의 높이입니다. |
| start_angle | int | x축에서 파이 모양의 첫 번째 변까지 시계 방향으로 측정한 각도(도)입니다. |
| sweep_angle | int | <paramref name="startAngle" /> 매개변수에서 파이 모양의 두 번째 변까지 시계 방향으로 측정한 각도(도)입니다. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 다각형을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 폴리곤의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 폴리곤의 정점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조의 배열입니다. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 다각형을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 폴리곤의 색상, 두께 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/) 입니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 폴리곤의 정점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조의 배열입니다. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 사각형을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 사각형의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 그릴 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 사각형을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 사각형의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 그릴 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 사각형의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/). |
| x | float | 그릴 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | float | 그릴 사각형의 왼쪽 위 모서리의 y 좌표. |
| width | float | 그릴 사각형의 너비. |
| 높이 | float | 그릴 사각형의 높이. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 사각형의 색상, 너비 및 스타일을 결정하는 [Pen](/psd/python-net/aspose.psd/pen/). |
| x | int | 그릴 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | int | 그릴 사각형의 왼쪽 위 모서리의 y 좌표. |
| width | int | 그릴 사각형의 너비. |
| 높이 | int | 그릴 사각형의 높이. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에 의해 지정된 일련의 사각형을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/)은(는) 사각형 윤곽선의 색상, 너비 및 스타일을 결정합니다. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | 그릴 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체 배열. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에 의해 지정된 일련의 사각형을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/)은(는) 사각형 윤곽선의 색상, 너비 및 스타일을 결정합니다. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | 그릴 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체 배열. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 사각형에 지정된 텍스트 문자열을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| s | 문자열 | 그릴 문자열. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/)은(는) 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 그려진 텍스트의 색상과 질감을 결정합니다. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 그려진 텍스트의 위치를 지정하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

지정된 [StringFormat](/psd/python-net/aspose.psd/stringformat/)의 서식 속성을 사용하여 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 사각형에 지정된 텍스트 문자열을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| s | 문자열 | 그릴 문자열. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/)은(는) 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 그려진 텍스트의 색상과 질감을 결정합니다. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 그려진 텍스트의 위치를 지정하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정하는 [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

지정된 위치에 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 텍스트 문자열을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| s | 문자열 | 그릴 문자열. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/)은(는) 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 그려진 텍스트의 색상과 질감을 결정합니다. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 그려진 텍스트의 왼쪽 위 모서리를 지정하는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

지정된 [StringFormat](/psd/python-net/aspose.psd/stringformat/)의 서식 속성을 사용하여 지정된 위치에 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 텍스트 문자열을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| s | 문자열 | 그릴 문자열. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/)은(는) 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 그려진 텍스트의 색상과 질감을 결정합니다. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 그려진 텍스트의 왼쪽 위 모서리를 지정하는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정하는 [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

지정된 위치에 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 텍스트 문자열을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| s | 문자열 | 그릴 문자열. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/)은(는) 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 그려진 텍스트의 색상과 질감을 결정합니다. |
| x | float | 그려진 텍스트의 왼쪽 위 모서리의 x 좌표. |
| y | float | 그려진 텍스트의 왼쪽 위 모서리의 y 좌표. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

지정된 [StringFormat](/psd/python-net/aspose.psd/stringformat/)의 서식 속성을 사용하여 지정된 위치에 지정된 [Brush](/psd/python-net/aspose.psd/brush/) 및 [Font](/psd/python-net/aspose.psd/font/) 객체와 함께 지정된 텍스트 문자열을 그립니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| s | 문자열 | 그릴 문자열. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/)은(는) 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 그려진 텍스트의 색상과 질감을 결정합니다. |
| x | float | 그려진 텍스트의 왼쪽 위 모서리의 x 좌표. |
| y | float | 그려진 텍스트의 왼쪽 위 모서리의 y 좌표. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정하는 [StringFormat](/psd/python-net/aspose.psd/stringformat/). |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 채우기 모드를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 지정된 채우기 모드를 사용하여 채웁니다. 이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | [FillMode](/psd/python-net/aspose.psd/fillmode/) 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열에 의해 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 지정된 채우기 모드를 사용하여 채웁니다. 이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | [FillMode](/psd/python-net/aspose.psd/fillmode/) 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

지정된 채우기 모드와 장력을 사용하여 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 채우기의 특성을 결정하는 [Brush](/psd/python-net/aspose.psd/brush/). |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | [FillMode](/psd/python-net/aspose.psd/fillmode/) 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |
| 텐션 | float | 곡선의 장력을 지정하는 0.0F 이상 값. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

지정된 채우기 모드와 장력을 사용하여 [PointF](/psd/python-net/aspose.psd/pointf/) 구조 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 채우기의 특성을 결정하는 [Brush](/psd/python-net/aspose.psd/brush/). |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열은 스플라인을 정의합니다. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | [FillMode](/psd/python-net/aspose.psd/fillmode/) 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |
| 텐션 | float | 곡선의 장력을 지정하는 0.0F 이상 값. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 타원을 정의하는 경계 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 타원을 정의하는 경계 사각형을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

좌표 쌍, 너비 및 높이로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| x | float | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | float | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표. |
| width | float | 타원을 정의하는 경계 사각형의 너비. |
| 높이 | float | 타원을 정의하는 경계 사각형의 높이. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

좌표 쌍, 너비 및 높이로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| x | int | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | int | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표. |
| width | int | 타원을 정의하는 경계 사각형의 너비. |
| 높이 | int | 타원을 정의하는 경계 사각형의 높이. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 채우기 경로를 나타내는 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 파이 조각이 나오는 타원을 정의하는 경계 사각형을 나타내는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조체. |
| start_angle | float | 파이 조각의 첫 번째 변까지 x축에서 시계 방향으로 측정한 각도(도). |
| sweep_angle | float | 파이 조각의 두 번째 변까지 <paramref name="startAngle" /> 매개변수에서 시계 방향으로 측정한 각도(도). |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 파이 조각이 나오는 타원을 정의하는 경계 사각형을 나타내는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조체. |
| start_angle | float | 파이 조각의 첫 번째 변까지 x축에서 시계 방향으로 측정한 각도(도). |
| sweep_angle | float | 파이 조각의 두 번째 변까지 <paramref name="startAngle" /> 매개변수에서 시계 방향으로 측정한 각도(도). |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| x | float | 파이 조각이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x좌표. |
| y | float | 파이 조각이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y좌표. |
| width | float | 파이 조각이 나오는 타원을 정의하는 경계 사각형의 너비. |
| 높이 | float | 파이 조각이 나오는 타원을 정의하는 경계 사각형의 높이. |
| start_angle | float | 파이 조각의 첫 번째 변까지 x축에서 시계 방향으로 측정한 각도(도). |
| sweep_angle | float | 파이 조각의 두 번째 변까지 <paramref name="startAngle" /> 매개변수에서 시계 방향으로 측정한 각도(도). |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| x | int | 파이 조각이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x좌표. |
| y | int | 파이 조각이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y좌표. |
| width | int | 파이 조각이 나오는 타원을 정의하는 경계 사각형의 너비. |
| 높이 | int | 파이 조각이 나오는 타원을 정의하는 경계 사각형의 높이. |
| start_angle | int | 파이 조각의 첫 번째 변까지 x축에서 시계 방향으로 측정한 각도(도). |
| sweep_angle | int | 파이 조각의 두 번째 변까지 <paramref name="startAngle" /> 매개변수에서 시계 방향으로 측정한 각도(도). |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 채우기 위한 다각형의 정점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조와 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 채우기 위한 다각형의 정점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조로 지정된 점 배열과 지정된 채우기 모드를 사용하여 정의된 다각형의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 채우기 위한 다각형의 정점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 채우기 스타일을 결정하는 [FillMode](/psd/python-net/aspose.psd/fillmode/) 열거형의 멤버. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 구조로 지정된 점 배열과 지정된 채우기 모드를 사용하여 정의된 다각형의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 채우기 위한 다각형의 정점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 배열. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 채우기 스타일을 결정하는 [FillMode](/psd/python-net/aspose.psd/fillmode/) 열거형의 멤버. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 지정된 사각형의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 채우기 사각형을 나타내는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조체. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 지정된 사각형의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 채우기 사각형을 나타내는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조체. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

좌표 쌍, 너비 및 높이로 지정된 사각형의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| x | float | 채우기 사각형의 왼쪽 위 모서리의 x좌표. |
| y | float | 채우기 사각형의 왼쪽 위 모서리의 y좌표. |
| width | float | 채우기 사각형의 너비. |
| 높이 | float | 채우기 사각형의 높이. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

좌표 쌍, 너비 및 높이로 지정된 사각형의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| x | int | 채우기 사각형의 왼쪽 위 모서리의 x좌표. |
| y | int | 채우기 사각형의 왼쪽 위 모서리의 y좌표. |
| width | int | 채우기 사각형의 너비. |
| 높이 | int | 채우기 사각형의 높이. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 지정된 일련의 사각형들의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | 채우기 사각형들을 나타내는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조체 배열. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 지정된 일련의 사각형들의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | 채우기 사각형들을 나타내는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조체 배열. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

[Region](/psd/python-net/aspose.psd/region/)의 내부를 채웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/)은(는) 채우기의 특성을 결정합니다. |
| region | [Region](/psd/python-net/aspose.psd/region) | 채우기 영역을 나타내는 [Region](/psd/python-net/aspose.psd/region/). |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

이 [Graphics](/psd/python-net/aspose.psd/graphics/)의 로컬 기하 변환을 나타내는 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 앞에 추가하여 곱합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 기하 변환에 곱할 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

이 [Graphics](/psd/python-net/aspose.psd/graphics/)의 로컬 기하 변환을 나타내는 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 순서대로 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 곱합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 기하 변환에 곱할 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 두 행렬을 곱할 순서를 지정하는 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)입니다. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

지정된 양만큼 로컬 기하 변환을 회전시킵니다. 이 메서드는 회전을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도입니다. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

지정된 순서대로 지정된 양만큼 로컬 기하 변환을 회전시킵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도입니다. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 회전 행렬을 추가할지 앞에 삽입할지를 지정하는 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)입니다. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

지정된 양큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| sx | float | x축 방향으로 변환을 스케일링할 양입니다. |
| sy | float | y축 방향으로 변환을 스케일링할 양입니다. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| sx | float | x축 방향으로 변환을 스케일링할 양입니다. |
| sy | float | y축 방향으로 변환을 스케일링할 양입니다. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 스케일링 행렬을 추가할지 앞에 삽입할지를 지정하는 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)입니다. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | float | x축에서 평행 이동 값입니다. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | float | x축에서 평행 이동 값입니다. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | The order (prepend or append) in which to apply the translation. |

