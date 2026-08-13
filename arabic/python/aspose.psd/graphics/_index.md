---
title: "فئة Graphics"
type: docs
weight: 1550
url: /ar/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | ينشئ مثيلاً جديدًا لفئة [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | يحصل أو يضبط منطقة القص. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | يحصل أو يضبط جودة التركيب. |
| dpi_x | float | r | يحصل على الدقة الأفقية لهذا Aspose.PSD.Graphics. |
| dpi_y | float | r | يحصل على الدقة العمودية لهذا Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | يحصل على الصورة. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | يحصل أو يضبط وضع الاستيفاء. |
| is_in_begin_update_call | bool | r | يحصل على قيمة تشير إلى ما إذا كانت الرسومات في حالة استدعاء BeginUpdate. |
| page_scale | float | r/w | يحصل أو يضبط التحجيم بين وحدات العالم ووحدات الصفحة لهذا Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | يحصل أو يضبط وحدة القياس المستخدمة لإحداثيات الصفحة في هذا Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | يحصل أو يضبط خيارات الصورة، المستخدمة لإنشاء صور متجهة قابلة للطلاء للرسم. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | يحصل أو يضبط وضع التنعيم. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | يحصل أو يضبط تلميح عرض النص. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | يحصل أو يضبط نسخة من التحويل الهندسي العالمي لهذا [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| begin_update() | يبدأ تخزين مؤقت للعمليات الرسومية التالية. لن تُطبق تأثيرات الرسومات التي تُطبق لاحقًا فورًا؛ بدلاً من ذلك سيؤدي EndUpdate إلى تطبيق جميع التأثيرات مرة واحدة. |
| [clear(color)](#clear_color_1) | يمسح سطح الرسومات باستخدام اللون المحدد. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | يرسم منحنى بيزير محدد بأربع بنى [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | يرسم منحنى بيزير محدد بأربع بنى [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | يرسم منحنى بيزير محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | يرسم سلسلة من منحنيات بيزير من مصفوفة من بنى [Point](/psd/python-net/aspose.psd/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | يرسم سلسلة من منحنيات بيزير من مصفوفة من بنى [Point](/psd/python-net/aspose.psd/point/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 و وضع تعبئة [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 و وضع تعبئة [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). يبدأ الرسم مع إزاحة من بداية المصفوفة.<br/>            تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. يبدأ الرسم مع إزاحة من بداية المصفوفة. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. يبدأ الرسم مع إزاحة من بداية المصفوفة. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | يرسم إهليلجًا يُحدَّد بواسطة [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الحدية. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | يرسم إهليلجًا يُحدَّد بواسطة [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الحدية. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | يرسم إهليلجًا يُحدَّد بواسطة مستطيل حدّي محدد بزوج من الإحداثيات، والارتفاع، والعرض. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | يرسم إهليلجًا يُحدَّد بواسطة مستطيل حدّي محدد بزوج من الإحداثيات، والارتفاع، والعرض. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | يرسم الصورة المحددة باستخدام حجمها الفيزيائي الأصلي في الموقع المحدد بواسطة زوج من الإحداثيات. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | يرسم الصورة المحددة دون تغيير الحجم ويقصها، إذا لزم الأمر، لتناسب المستطيل المحدد. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | يرسم خطًا يربط بين هيكلي [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | يرسم خطًا يربط بين هيكلي [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [Point](/psd/python-net/aspose.psd/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [Point](/psd/python-net/aspose.psd/point/). |
| [draw_path(pen, path)](#draw_path_pen_path_61) | يرسم [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | يرسم شكل فطيرة معرفًا بإهليلج محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) وخطين شعاعيين. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | يرسم شكل فطيرة معرفًا بإهليلج محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) وخطين شعاعيين. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | يرسم شكل فطيرة معرفًا بإهليلج محدد بواسطة زوج من الإحداثيات، العرض، الارتفاع، وخطين شعاعيين. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | يرسم شكل فطيرة معرفًا بإهليلج محدد بواسطة زوج من الإحداثيات، العرض، الارتفاع، وخطين شعاعيين. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | يرسم مضلعًا معرفًا بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | يرسم مضلعًا معرفًا بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | يرسم مستطيلًا محددًا بهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | يرسم مستطيلًا محددًا بهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | يرسم مستطيلًا محددًا بواسطة زوج من الإحداثيات، العرض، والارتفاع. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | يرسم مستطيلًا محددًا بواسطة زوج من الإحداثيات، العرض، والارتفاع. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | يرسم سلسلة من المستطيلات المحددة بواسطة هياكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | يرسم سلسلة من المستطيلات المحددة بواسطة هياكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/) المحددة. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/) مع خصائص التنسيق الخاصة بـ [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/). |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/) مع خصائص التنسيق الخاصة بـ [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/). |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/) مع خصائص التنسيق الخاصة بـ [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | ينهي تخزين عمليات الرسومات المؤقتة التي بدأت بعد استدعاء BeginUpdate. سيتم تطبيق عمليات الرسومات السابقة مرة واحدة عند استدعاء هذه الطريقة. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 و وضع تعبئة [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 و وضع تعبئة [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد والتوتر. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد والتوتر. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | يملأ داخل إهليلج معرف بمستطيل محيط محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | يملأ داخل إهليلج معرف بمستطيل محيط محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | يملأ داخل إهليلج معرف بمستطيل محيط محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | يملأ داخل إهليلج معرف بمستطيل محيط محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | يملأ داخل [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) وخطين شعاعيين. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) وخطين شعاعيين. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع، وخطين شعاعيين. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع، وخطين شعاعيين. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [PointF](/psd/python-net/aspose.psd/pointf/) و[FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [PointF](/psd/python-net/aspose.psd/pointf/) و[FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | يملأ داخل مستطيل محدد بواسطة هيكل [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | يملأ داخل مستطيل محدد بواسطة هيكل [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | يملأ داخل مجموعة من المستطيلات المحددة بواسطة هياكل [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | يملأ داخل مجموعة من المستطيلات المحددة بواسطة هياكل [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_region(brush, region)](#fill_region_brush_region_105) | يملأ داخل [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | يضرب [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [Graphics](/psd/python-net/aspose.psd/graphics/) بالمصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) المحددة عن طريق إلحاق المصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) المحددة في البداية. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | يضرب [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [Graphics](/psd/python-net/aspose.psd/graphics/) بالمصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) المحددة بالترتيب المحدد. |
| reset_transform() | يعيد تعيين خاصية [Graphics.transform](/psd/python-net/aspose.psd/graphics/) إلى الهوية. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | يدور التحويل الهندسي المحلي بالمقدار المحدد. تضيف هذه الطريقة الدوران إلى التحويل في البداية. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة التكبير إلى التحويل في البداية. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تضيف هذه الطريقة الإزاحة إلى التحويل في البداية. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

ينشئ مثيلاً جديدًا لفئة [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | صورة المصدر. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

يمسح سطح الرسومات باستخدام اللون المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | اللون المستخدم لمسح سطح الرسومات. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هيكل يحدد حدود الإهليلج. |
| start_angle | float | الزاوية بالدرجات تقاس باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweep_angle | float | الزاوية بالدرجات تقاس باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى نقطة النهاية للقوس. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هيكل يحدد حدود الإهليلج. |
| start_angle | float | الزاوية بالدرجات تقاس باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweep_angle | float | الزاوية بالدرجات تقاس باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى نقطة النهاية للقوس. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| x | float | الإحداثي x للزاوية العلوية اليسرى للمستطيل الذي يحدد الإهليلج. |
| y | float | الإحداثي y للزاوية العلوية اليسرى للمستطيل الذي يحدد الإهليلج. |
| width | float | عرض المستطيل الذي يحدد الإهليلج. |
| الارتفاع | float | ارتفاع المستطيل الذي يحدد الإهليلج. |
| start_angle | float | الزاوية بالدرجات تقاس باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweep_angle | float | الزاوية بالدرجات تقاس باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى نقطة النهاية للقوس. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للقوس. |
| x | int | الإحداثي x للزاوية العلوية اليسرى للمستطيل الذي يحدد الإهليلج. |
| y | int | الإحداثي y للزاوية العلوية اليسرى للمستطيل الذي يحدد الإهليلج. |
| width | int | عرض المستطيل الذي يحدد الإهليلج. |
| الارتفاع | int | ارتفاع المستطيل الذي يحدد الإهليلج. |
| start_angle | int | الزاوية بالدرجات تقاس باتجاه عقارب الساعة من محور x إلى نقطة البداية للقوس. |
| sweep_angle | int | الزاوية بالدرجات تقاس باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى نقطة النهاية للقوس. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

يرسم منحنى بيزير محدد بأربع بنى [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) هيكل يمثل نقطة البداية للمنحنى. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) هيكل يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) هيكل يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) هيكل يمثل نقطة النهاية للمنحنى. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

يرسم منحنى بيزير محدد بأربع بنى [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) هيكل يمثل نقطة البداية للمنحنى. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) هيكل يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) هيكل يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) هيكل يمثل نقطة النهاية للمنحنى. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

يرسم منحنى بيزير محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| x1 | float | الإحداثي x لنقطة البداية للمنحنى. |
| y1 | float | الإحداثي y لنقطة البداية للمنحنى. |
| x2 | float | الإحداثي x لنقطة التحكم الأولى للمنحنى. |
| y2 | float | الإحداثي y لنقطة التحكم الأولى للمنحنى. |
| x3 | float | الإحداثي x لنقطة التحكم الثانية للمنحنى. |
| y3 | float | الإحداثي y لنقطة التحكم الثانية للمنحنى. |
| x4 | float | الإحداثي السيني لنقطة النهاية للمنحنى. |
| y4 | float | الإحداثي الصادي لنقطة النهاية للمنحنى. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

يرسم سلسلة من منحنيات بيزير من مصفوفة من بنى [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [Point](/psd/python-net/aspose.psd/point/) التي تمثل النقاط التي تحدد المنحنى. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

يرسم سلسلة من منحنيات بيزير من مصفوفة من بنى [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [Point](/psd/python-net/aspose.psd/point/) التي تمثل النقاط التي تحدد المنحنى. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 و وضع تعبئة [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5 و وضع تعبئة [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| الشد | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

يرسم منحنى كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. تستخدم هذه الطريقة وضع تعبئة افتراضي [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| الشد | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). يبدأ الرسم مع إزاحة من بداية المصفوفة.<br/>            تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| offset | int | الإزاحة من العنصر الأول في المصفوفة للمعامل <paramref name="points" /> إلى نقطة البدء في المنحنى. |
| number_of_segments | int | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. يبدأ الرسم مع إزاحة من بداية المصفوفة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| offset | int | الإزاحة من العنصر الأول في المصفوفة للمعامل <paramref name="points" /> إلى نقطة البدء في المنحنى. |
| number_of_segments | int | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |
| الشد | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد. يبدأ الرسم مع إزاحة من بداية المصفوفة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| offset | int | الإزاحة من العنصر الأول في المصفوفة للمعامل <paramref name="points" /> إلى نقطة البدء في المنحنى. |
| number_of_segments | int | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |
| الشد | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل النقاط التي تُعرّف المنحنى. |
| الشد | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

يرسم منحنى كاردينال عبر مصفوفة محددة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام توتر محدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل النقاط التي تُعرّف المنحنى. |
| الشد | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

يرسم إهليلجًا يُحدَّد بواسطة [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الحدية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هيكل يحدد حدود الإهليلج. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

يرسم إهليلجًا يُحدَّد بواسطة [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الحدية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هيكل يحدد حدود الإهليلج. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

يرسم إهليلجًا يُحدَّد بواسطة مستطيل حدّي محدد بزوج من الإحداثيات، والارتفاع، والعرض.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| الارتفاع | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

يرسم إهليلجًا يُحدَّد بواسطة مستطيل حدّي محدد بزوج من الإحداثيات، والارتفاع، والعرض.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) التي تحدد اللون والعرض والنمط للقطع الناقص. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| الارتفاع | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم رسمها. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من ثلاث هياكل PointF التي تُعرّف متوازي أضلاع. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم رسمها. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من ثلاث هياكل PointF التي تُعرّف متوازي أضلاع. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم رسمها. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من ثلاث هياكل PointF التي تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المصدر. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم رسمها. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من ثلاث هياكل PointF التي تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل المصدر. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم رسمها. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من ثلاث هياكل PointF التي تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدات القياس. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم رسمها. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من ثلاث هياكل PointF التي تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدات القياس. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم رسمها. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من ثلاث هياكل PointF التي تُعرّف متوازي أضلاع. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدات القياس. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | خصائص الصورة. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

يرسم الجزء المحدد من <paramref name="image" /> المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم رسمها. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من ثلاث هياكل PointF التي تُعرّف متوازي أضلاع. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل المصدر. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدات القياس. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | خصائص الصورة. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | هيكل [PointF](/psd/python-net/aspose.psd/pointf/) الذي يمثل الزاوية العليا اليسرى للصورة المرسومة. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| point | [Point](/psd/python-net/aspose.psd/point) | هيكل [PointF](/psd/python-net/aspose.psd/pointf/) الذي يمثل الزاوية العليا اليسرى للصورة المرسومة. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يحدد موقع وحجم الصورة المرسومة. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يحدد موقع وحجم الصورة المرسومة. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدة الرسومات. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدة الرسومات. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | خصائص الصورة. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل الوجهة. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | خصائص الصورة. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مصدر المستطيل. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدة الرسومات. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | مصدر المستطيل. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدة الرسومات. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مصدر المستطيل. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | خصائص الصورة. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | مصدر المستطيل. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | وجهة المستطيل. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | وحدة الرسومات. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | خصائص الصورة. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| x | float | الإحداثي س للزاوية العليا اليسرى للصورة المرسومة. |
| y | float | الإحداثي ص للزاوية العليا اليسرى للصورة المرسومة. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد، باستخدام حجمه الفيزيائي الأصلي، في الموقع المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي س للزاوية العليا اليسرى للصورة المرسومة. |
| y | int | الإحداثي ص للزاوية العليا اليسرى للصورة المرسومة. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| x | float | الإحداثي س للزاوية العليا اليسرى للصورة المرسومة. |
| y | float | الإحداثي ص للزاوية العليا اليسرى للصورة المرسومة. |
| width | float | عرض الصورة المرسومة. |
| الارتفاع | float | ارتفاع الصورة المرسومة. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

يرسم [Graphics.image](/psd/python-net/aspose.psd/graphics/) المحدد في الموقع المحدد وبالحجم المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي س للزاوية العليا اليسرى للصورة المرسومة. |
| y | int | الإحداثي ص للزاوية العليا اليسرى للصورة المرسومة. |
| width | int | عرض الصورة المرسومة. |
| الارتفاع | int | ارتفاع الصورة المرسومة. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) هيكل يحدد الزاوية العليا اليسرى للصورة المرسومة. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) الذي يحدد الزاوية العليا اليسرى للصورة المرسومة. خصائص X و Y للمستطيل تحدد الزاوية العليا اليسرى. يتم تجاهل خصائص العرض والارتفاع. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

يرسم الصورة المحددة باستخدام حجمها الفيزيائي الأصلي في الموقع المحدد بواسطة زوج من الإحداثيات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي س للزاوية العليا اليسرى للصورة المرسومة. |
| y | int | الإحداثي ص للزاوية العليا اليسرى للصورة المرسومة. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

يرسم صورة محددة باستخدام حجمها الفيزيائي الأصلي في موقع محدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| x | int | الإحداثي س للزاوية العليا اليسرى للصورة المرسومة. |
| y | int | الإحداثي ص للزاوية العليا اليسرى للصورة المرسومة. |
| width | int | المعامل غير مستخدم. |
| الارتفاع | int | المعامل غير مستخدم. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

يرسم الصورة المحددة دون تغيير الحجم ويقصها، إذا لزم الأمر، لتناسب المستطيل المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | الصورة التي سيتم الرسم بها. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل [Rectangle](/psd/python-net/aspose.psd/rectangle/) الذي يتم رسم الصورة فيه. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

يرسم خطًا يربط بين هيكلي [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للخط. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) هيكل يمثل النقطة الأولى للاتصال. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) هيكل يمثل النقطة الثانية للاتصال. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

يرسم خطًا يربط بين هيكلي [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للخط. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) هيكل يمثل النقطة الأولى للاتصال. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) هيكل يمثل النقطة الثانية للاتصال. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للخط. |
| x1 | int | الإحداثي س للنقطة الأولى. |
| y1 | int | الإحداثي ص للنقطة الأولى. |
| x2 | int | الإحداثي س للنقطة الثانية. |
| y2 | int | الإحداثي ص للنقطة الثانية. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

يرسم خطًا يربط النقطتين المحددتين بواسطة أزواج الإحداثيات.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للخط. |
| x1 | float | الإحداثي س للنقطة الأولى. |
| y1 | float | الإحداثي ص للنقطة الأولى. |
| x2 | float | الإحداثي س للنقطة الثانية. |
| y2 | float | الإحداثي ص للنقطة الثانية. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط لقطاعات الخط. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [Point](/psd/python-net/aspose.psd/point/) التي تمثل النقاط للاتصال. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط لقطاعات الخط. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [Point](/psd/python-net/aspose.psd/point/) التي تمثل النقاط للاتصال. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

يرسم [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للمسار. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) للرسم. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

يرسم شكل فطيرة معرفًا بإهليلج محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هيكل يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من محور س إلى الجانب الأول لشكل الفطيرة. |
| sweep_angle | float | الزاوية المقاسة بالدرجات باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

يرسم شكل فطيرة معرفًا بإهليلج محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) هيكل يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من محور س إلى الجانب الأول لشكل الفطيرة. |
| sweep_angle | float | الزاوية المقاسة بالدرجات باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم شكل فطيرة معرفًا بإهليلج محدد بواسطة زوج من الإحداثيات، العرض، الارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| الارتفاع | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | float | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من محور س إلى الجانب الأول لشكل الفطيرة. |
| sweep_angle | float | الزاوية المقاسة بالدرجات باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

يرسم شكل فطيرة معرفًا بإهليلج محدد بواسطة زوج من الإحداثيات، العرض، الارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| الارتفاع | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| start_angle | int | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من محور س إلى الجانب الأول لشكل الفطيرة. |
| sweep_angle | int | الزاوية المقاسة بالدرجات باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى الجانب الثاني من شكل الفطيرة. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

يرسم مضلعًا معرفًا بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للمضلع. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل رؤوس المضلع. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

يرسم مضلعًا معرفًا بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط للمضلع. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل رؤوس المضلع. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

يرسم مستطيلًا محددًا بهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen] يحدد اللون والعرض والنمط للمستطيل. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يمثل المستطيل الذي سيتم رسمه. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

يرسم مستطيلًا محددًا بهيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen] يحدد اللون والعرض والنمط للمستطيل. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) يمثل المستطيل الذي سيتم رسمه. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

يرسم مستطيلًا محددًا بواسطة زوج من الإحداثيات، العرض، والارتفاع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen] يحدد اللون والعرض والنمط للمستطيل. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل الذي سيتم رسمه. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل الذي سيتم رسمه. |
| width | float | عرض المستطيل الذي سيتم رسمه. |
| الارتفاع | float | ارتفاع المستطيل الذي سيتم رسمه. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

يرسم مستطيلًا محددًا بواسطة زوج من الإحداثيات، العرض، والارتفاع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | قلم [Pen] يحدد اللون والعرض والنمط للمستطيل. |
| x | int | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل الذي سيتم رسمه. |
| y | int | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل الذي سيتم رسمه. |
| width | int | عرض المستطيل الذي سيتم رسمه. |
| الارتفاع | int | ارتفاع المستطيل الذي سيتم رسمه. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

يرسم سلسلة من المستطيلات المحددة بواسطة هياكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | مصفوفة من هياكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) التي تمثل المستطيلات التي سيتم رسمها. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

يرسم سلسلة من المستطيلات المحددة بواسطة هياكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | مصفوفة من هياكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) التي تمثل المستطيلات التي سيتم رسمها. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/) المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| s | string | النص الذي سيتم رسمه. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يحدد موقع النص المرسوم. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/) مع خصائص التنسيق الخاصة بـ [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| s | string | النص الذي سيتم رسمه. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يحدد موقع النص المرسوم. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| s | string | النص الذي سيتم رسمه. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | هيكل [PointF](/psd/python-net/aspose.psd/pointf/) الذي يحدد الزاوية العلوية اليسرى للنص المرسوم. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/) مع خصائص التنسيق الخاصة بـ [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| s | string | النص الذي سيتم رسمه. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | هيكل [PointF](/psd/python-net/aspose.psd/pointf/) الذي يحدد الزاوية العلوية اليسرى للنص المرسوم. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| s | string | النص الذي سيتم رسمه. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للنص المرسوم. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للنص المرسوم. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

يرسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [Brush](/psd/python-net/aspose.psd/brush/) و[Font](/psd/python-net/aspose.psd/font/) مع خصائص التنسيق الخاصة بـ [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| s | string | النص الذي سيتم رسمه. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| x | float | الإحداثي السيني للزاوية العلوية اليسرى للنص المرسوم. |
| y | float | الإحداثي الصادي للزاوية العلوية اليسرى للنص المرسوم. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 و وضع تعبئة [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/). يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5 و وضع تعبئة [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | عضو في تعداد [FillMode](/psd/python-net/aspose.psd/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد. يستخدم هذا الأسلوب توترًا افتراضيًا قدره 0.5.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | عضو في تعداد [FillMode](/psd/python-net/aspose.psd/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد والتوتر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | أداة [Brush](/psd/python-net/aspose.psd/brush/) التي تحدد خصائص التعبئة. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | عضو في تعداد [FillMode](/psd/python-net/aspose.psd/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |
| الشد | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

يملأ داخل منحنى سبلين كاردينال مغلق معرف بمصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد والتوتر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | أداة [Brush](/psd/python-net/aspose.psd/brush/) التي تحدد خصائص التعبئة. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تُعرّف المنحنى الانسيابي. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | عضو في تعداد [FillMode](/psd/python-net/aspose.psd/fillmode/) الذي يحدد كيفية تعبئة المنحنى. |
| الشد | float | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

يملأ داخل إهليلج معرف بمستطيل محيط محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

يملأ داخل إهليلج معرف بمستطيل محيط محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

يملأ داخل إهليلج معرف بمستطيل محيط محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| الارتفاع | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

يملأ داخل إهليلج معرف بمستطيل محيط محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| y | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| الارتفاع | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

يملأ داخل [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) الذي يمثل المسار للتعبئة. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [Rectangle](/psd/python-net/aspose.psd/rectangle/) الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول من قطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى الجانب الثاني من قطاع الفطيرة. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة هيكل [RectangleF](/psd/python-net/aspose.psd/rectanglef/) وخطين شعاعيين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [Rectangle](/psd/python-net/aspose.psd/rectangle/) الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول من قطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى الجانب الثاني من قطاع الفطيرة. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي x للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | float | الإحداثي y للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| width | float | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| الارتفاع | float | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| start_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول من قطاع الفطيرة. |
| sweep_angle | float | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى الجانب الثاني من قطاع الفطيرة. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

يملأ داخل قطاع فطيرة معرف بإهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع، وخطين شعاعيين.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي x للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | int | الإحداثي y للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| width | int | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| الارتفاع | int | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| start_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول من قطاع الفطيرة. |
| sweep_angle | int | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل <paramref name="startAngle" /> إلى الجانب الثاني من قطاع الفطيرة. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [PointF](/psd/python-net/aspose.psd/pointf/) و[FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل رؤوس المضلع للتعبئة. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [PointF](/psd/python-net/aspose.psd/pointf/) و[FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل رؤوس المضلع للتعبئة. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل رؤوس المضلع للتعبئة. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | عضو في تعداد [FillMode](/psd/python-net/aspose.psd/fillmode/) الذي يحدد نمط التعبئة. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

يملأ داخل مضلع معرف بمصفوفة من النقاط المحددة بهياكل [PointF](/psd/python-net/aspose.psd/pointf/) باستخدام وضع التعبئة المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | مصفوفة من هياكل [PointF](/psd/python-net/aspose.psd/pointf/) التي تمثل رؤوس المضلع للتعبئة. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | عضو في تعداد [FillMode](/psd/python-net/aspose.psd/fillmode/) الذي يحدد نمط التعبئة. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

يملأ داخل مستطيل محدد بواسطة هيكل [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | هيكل [Rectangle](/psd/python-net/aspose.psd/rectangle/) الذي يمثل المستطيل المراد تعبئته. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

يملأ داخل مستطيل محدد بواسطة هيكل [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | هيكل [Rectangle](/psd/python-net/aspose.psd/rectangle/) الذي يمثل المستطيل المراد تعبئته. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| x | float | الإحداثي x للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| y | float | الإحداثي y للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| width | float | عرض المستطيل المراد تعبئته. |
| الارتفاع | float | ارتفاع المستطيل المراد تعبئته. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

يملأ داخل مستطيل محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| x | int | الإحداثي x للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| y | int | الإحداثي y للزاوية العلوية اليسرى للمستطيل المراد تعبئته. |
| width | int | عرض المستطيل المراد تعبئته. |
| الارتفاع | int | ارتفاع المستطيل المراد تعبئته. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

يملأ داخل مجموعة من المستطيلات المحددة بواسطة هياكل [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | مصفوفة من هياكل [Rectangle](/psd/python-net/aspose.psd/rectangle/) التي تمثل المستطيلات المراد تعبئتها. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

يملأ داخل مجموعة من المستطيلات المحددة بواسطة هياكل [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | مصفوفة من هياكل [Rectangle](/psd/python-net/aspose.psd/rectangle/) التي تمثل المستطيلات المراد تعبئتها. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

يملأ داخل [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) الذي يحدد خصائص التعبئة. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) الذي يمثل المنطقة المراد تعبئتها. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

يضرب [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [Graphics](/psd/python-net/aspose.psd/graphics/) بالمصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) المحددة عن طريق إلحاق المصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) المحددة في البداية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) التي يُضرب بها التحويل الهندسي. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

يضرب [Matrix](/psd/python-net/aspose.psd/matrix/) الذي يمثل التحويل الهندسي المحلي لهذا [Graphics](/psd/python-net/aspose.psd/graphics/) بالمصفوفة [Matrix](/psd/python-net/aspose.psd/matrix/) المحددة بالترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) التي يُضرب بها التحويل الهندسي. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) يحدد الترتيب الذي تُضرب فيه المصفوفتان. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد. تضيف هذه الطريقة الدوران إلى التحويل في البداية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | زاوية الدوران. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

يدور التحويل الهندسي المحلي بالمقدار المحدد وفقًا للترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| الزاوية | float | زاوية الدوران. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) يحدد ما إذا كان يجب إلحاق أو إلحاق مسبق لمصفوفة الدوران. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة. تضيف هذه الطريقة مصفوفة التكبير إلى التحويل في البداية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| sx | float | القيمة التي يُكَبَّر بها التحويل في اتجاه المحور السيني. |
| sy | float | القيمة التي يُكَبَّر بها التحويل في اتجاه المحور الصادي. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

يقوم بتكبير التحويل الهندسي المحلي بالمقادير المحددة وفقًا للترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| sx | float | القيمة التي يُكَبَّر بها التحويل في اتجاه المحور السيني. |
| sy | float | القيمة التي يُكَبَّر بها التحويل في اتجاه المحور الصادي. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) يحدد ما إذا كان يجب إلحاق أو إلحاق مسبق لمصفوفة التكبير. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تضيف هذه الطريقة الإزاحة إلى التحويل في البداية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في الاتجاه السيني. |
| dy | float | قيمة الترجمة في y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

ينقل التحويل الهندسي المحلي بالأبعاد المحددة وفقًا للترتيب المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dx | float | قيمة الإزاحة في الاتجاه السيني. |
| dy | float | قيمة الترجمة في y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | الترتيب (إضافة مسبقة أو لاحقة) الذي يتم به تطبيق الترجمة. |

