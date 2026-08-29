---
title: "Graphics Sınıfı"
type: docs
weight: 1550
url: /tr/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Yeni bir [Graphics](/psd/python-net/aspose.psd/graphics/) sınıfı örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Kırpma bölgesini alır veya ayarlar. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Bileşim kalitesini alır veya ayarlar. |
| dpi_x | float | r | Bu Aspose.PSD.Graphics nesnesinin yatay çözünürlüğünü alır. |
| dpi_y | float | r | Bu Aspose.PSD.Graphics nesnesinin dikey çözünürlüğünü alır. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Görüntüyü alır. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Enterpolasyon modunu alır veya ayarlar. |
| is_in_begin_update_call | bool | r | Grafiğin BeginUpdate çağrı durumunda olup olmadığını gösteren bir değeri alır. |
| page_scale | float | r/w | Bu Aspose.PSD.Graphics için dünya birimleri ile sayfa birimleri arasındaki ölçeklemeyi alır veya ayarlar. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Bu Aspose.PSD.Graphics içindeki sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Görsel seçeneklerini alır veya ayarlar, çizim için boyanabilir vektör görüntüleri oluşturmakta kullanılır. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Yumuşatma modunu alır veya ayarlar. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Metin renderleme ipucunu alır veya ayarlar. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Bu [Graphics](/psd/python-net/aspose.psd/graphics/) için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| begin_update() | Aşağıdaki grafik işlemlerinin önbelleğe alınmasını başlatır. Sonrasında uygulanan grafik efektleri hemen uygulanmaz, bunun yerine EndUpdate tüm efektlerin bir kerede uygulanmasını sağlar. |
| [clear(color)](#clear_color_1) | Belirtilen rengi kullanarak grafik yüzeyini temizler. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Dört [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan bir Bézier eğrisi çizer. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Dört [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan bir Bézier eğrisi çizer. |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Nokta temsil eden dört sıralı koordinat çiftine göre tanımlanan bir Bézier eğrisi çizer. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Bir dizi [Point](/psd/python-net/aspose.psd/point/) yapısından Bézier eğrileri serisi çizer. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Bir dizi [Point](/psd/python-net/aspose.psd/point/) yapısından Bézier eğrileri serisi çizer. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. Bu yöntem, varsayılan 0.5 gerilimini ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. Bu yöntem, varsayılan 0.5 gerilimini ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Belirli bir gerilim kullanarak, bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. Bu yöntem, varsayılan [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma modunu kullanır. |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Belirli bir gerilim kullanarak, bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. Bu yöntem, varsayılan [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma modunu kullanır. |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem, varsayılan 0.5 gerilimini kullanır. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem, varsayılan 0.5 gerilimini kullanır. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başlangıcından bir offset ile başlar.<br/>            Bu yöntem, varsayılan 0.5 gerilimini kullanır. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Belirli bir gerilim kullanarak, belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başlangıcından bir offset ile başlar. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Belirli bir gerilim kullanarak, belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başlangıcından bir offset ile başlar. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Belirli bir gerilim kullanarak, belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Belirli bir gerilim kullanarak, belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Sınırlayıcı bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) tarafından tanımlanan bir elips çizer. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Sınırlayıcı bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) tarafından tanımlanan bir elips çizer. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Bir koordinat çifti, bir yükseklik ve bir genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Bir koordinat çifti, bir yükseklik ve bir genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Belirtilen resmi, özgün fiziksel boyutunu kullanarak, bir koordinat çifti ile belirtilen konumda çizer. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Belirtilen resmi ölçeklendirmeden çizer ve gerekirse, belirtilen dikdörtgene sığması için kırpar. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | İki [Point](/psd/python-net/aspose.psd/point/) yapısını bağlayan bir çizgi çizer. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | İki [Point](/psd/python-net/aspose.psd/point/) yapısını bağlayan bir çizgi çizer. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Bir dizi [Point](/psd/python-net/aspose.psd/point/) yapısını bağlayan bir dizi çizgi segmenti çizer. |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Bir dizi [Point](/psd/python-net/aspose.psd/point/) yapısını bağlayan bir dizi çizgi segmenti çizer. |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) çizer. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Bir koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Bir koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan bir çokgen çizer. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan bir çokgen çizer. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Bir dizi [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile belirtilen bir dizi dikdörtgen çizer. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Bir dizi [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile belirtilen bir dizi dikdörtgen çizer. |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Belirtilen metin dizesini, belirtilen dikdörtgende, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesneleriyle çizer. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Belirtilen metin dizesini, belirtilen dikdörtgende, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak, belirtilen [StringFormat](/psd/python-net/aspose.psd/stringformat/) biçimlendirme öznitelikleriyle çizer. |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Belirtilen metin dizesini, belirtilen konumda, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak çizer. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Belirtilen metin dizesini, belirtilen konumda, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak, belirtilen [StringFormat](/psd/python-net/aspose.psd/stringformat/) biçimlendirme öznitelikleriyle çizer. |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Belirtilen metin dizesini, belirtilen konumda, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak çizer. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Belirtilen metin dizesini, belirtilen konumda, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak, belirtilen [StringFormat](/psd/python-net/aspose.psd/stringformat/) biçimlendirme öznitelikleriyle çizer. |
| end_update() | BeginUpdate çağrıldıktan sonra başlatılan grafik işlemlerinin önbelleğe alınmasını sonlandırır. Önceki grafik işlemleri bu yöntem çağrıldığında bir kerede uygulanır. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma kipini kullanır. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma kipini kullanır. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nesnesinin içini doldurur. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir pasta diliminin içini doldurur. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir pasta diliminin içini doldurur. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir pasta diliminin içini doldurur. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir pasta diliminin içini doldurur. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı ile belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı ile belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Bir [Region](/psd/python-net/aspose.psd/region/) nesnesinin içini doldurur. |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Bu [Graphics](/psd/python-net/aspose.psd/graphics/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/psd/python-net/aspose.psd/matrix/) öğesini, belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile ön ekleyerek çarpar. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Bu [Graphics](/psd/python-net/aspose.psd/graphics/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/psd/python-net/aspose.psd/matrix/) öğesini, belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile belirtilen sırada çarpar. |
| reset_transform() | [Graphics.transform](/psd/python-net/aspose.psd/graphics/) özelliğini birim (identity) haline getirir. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem dönüşüme rotasyonu ön ekler. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Yerel geometrik dönüşümü belirtilen miktarlarda ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Yerel geometrik dönüşümü belirtilen miktarlarda, belirtilen sırada ölçeklendirir. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Yerel geometrik dönüşümü belirtilen boyutlarda taşır. Bu yöntem dönüşüme taşıma işlemini ön ekler. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada taşır. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Yeni bir [Graphics](/psd/python-net/aspose.psd/graphics/) sınıfı örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Kaynak görüntü. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Belirtilen rengi kullanarak grafik yüzeyini temizler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Grafik yüzeyini temizlemek için kullanılacak renk. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Kemerin renk, genişlik ve stilini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı elipsin sınırlarını tanımlar. |
| start_angle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | Derece cinsinden açı, <paramref name=\"startAngle\" /> parametresinden yay son noktasına doğru saat yönünde ölçülür. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı tarafından belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Kemerin renk, genişlik ve stilini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı elipsin sınırlarını tanımlar. |
| start_angle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | Derece cinsinden açı, <paramref name=\"startAngle\" /> parametresinden yay son noktasına doğru saat yönünde ölçülür. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Kemerin renk, genişlik ve stilini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| x | float | Elipsi tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan dikdörtgenin genişliği. |
| yükseklik | float | Elipsi tanımlayan dikdörtgenin yüksekliği. |
| start_angle | float | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | float | Derece cinsinden açı, <paramref name=\"startAngle\" /> parametresinden yay son noktasına doğru saat yönünde ölçülür. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Kemerin renk, genişlik ve stilini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| x | int | Elipsi tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan dikdörtgenin genişliği. |
| yükseklik | int | Elipsi tanımlayan dikdörtgenin yüksekliği. |
| start_angle | int | X ekseninden yay başlangıç noktasına doğru saat yönünde ölçülen açı (derece). |
| sweep_angle | int | Derece cinsinden açı, <paramref name=\"startAngle\" /> parametresinden yay son noktasına doğru saat yönünde ölçülür. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dört [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan bir Bézier eğrisi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) eğrinin renk, genişlik ve stilini belirler. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, eğrinin başlangıç noktasını temsil eder. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, eğri için birinci kontrol noktasını temsil eder. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, eğri için ikinci kontrol noktasını temsil eder. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, eğrinin bitiş noktasını temsil eder. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dört [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan bir Bézier eğrisi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) eğrinin renk, genişlik ve stilini belirler. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, eğrinin başlangıç noktasını temsil eder. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, eğri için birinci kontrol noktasını temsil eder. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, eğri için ikinci kontrol noktasını temsil eder. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) yapısı, eğrinin bitiş noktasını temsil eder. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Nokta temsil eden dört sıralı koordinat çiftine göre tanımlanan bir Bézier eğrisi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) eğrinin renk, genişlik ve stilini belirler. |
| x1 | float | Eğrinin başlangıç noktasının x koordinatı. |
| y1 | float | Eğrinin başlangıç noktasının y koordinatı. |
| x2 | float | Eğrinin birinci kontrol noktasının x koordinatı. |
| y2 | float | Eğrinin birinci kontrol noktasının y koordinatı. |
| x3 | float | Eğrinin ikinci kontrol noktasının x koordinatı. |
| y3 | float | Eğrinin ikinci kontrol noktasının y koordinatı. |
| x4 | float | Eğrinin bitiş noktasının x koordinatı. |
| y4 | float | Eğrinin bitiş noktasının y koordinatı. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Bir dizi [Point](/psd/python-net/aspose.psd/point/) yapısından Bézier eğrileri serisi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) eğrinin renk, genişlik ve stilini belirler. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Eğriyi belirleyen noktaları temsil eden [Point](/psd/python-net/aspose.psd/point/) yapıların dizisi. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Bir dizi [Point](/psd/python-net/aspose.psd/point/) yapısından Bézier eğrileri serisi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) eğrinin renk, genişlik ve stilini belirler. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Eğriyi belirleyen noktaları temsil eden [Point](/psd/python-net/aspose.psd/point/) yapıların dizisi. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. Bu yöntem, varsayılan 0.5 gerilimini ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. Bu yöntem, varsayılan 0.5 gerilimini ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Belirli bir gerilim kullanarak, bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. Bu yöntem, varsayılan [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Belirli bir gerilim kullanarak, bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. Bu yöntem, varsayılan [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma modunu kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem, varsayılan 0.5 gerilimini kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Bu yöntem, varsayılan 0.5 gerilimini kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başlangıcından bir offset ile başlar.<br/>            Bu yöntem, varsayılan 0.5 gerilimini kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| offset | int | <paramref name="points" /> parametresinin dizi içindeki ilk öğesinden eğrinin başlangıç noktasına olan offset. |
| number_of_segments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Belirli bir gerilim kullanarak, belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başlangıcından bir offset ile başlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| offset | int | <paramref name="points" /> parametresinin dizi içindeki ilk öğesinden eğrinin başlangıç noktasına olan offset. |
| number_of_segments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Belirli bir gerilim kullanarak, belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer. Çizim, dizinin başlangıcından bir offset ile başlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| offset | int | <paramref name="points" /> parametresinin dizi içindeki ilk öğesinden eğrinin başlangıç noktasına olan offset. |
| number_of_segments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Belirli bir gerilim kullanarak, belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Eğriyi tanımlayan noktaları temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Belirli bir gerilim kullanarak, belirtilen bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı üzerinden bir kardinal spline çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Eğriyi tanımlayan noktaları temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Sınırlayıcı bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı elipsin sınırlarını tanımlar. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Sınırlayıcı bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı elipsin sınırlarını tanımlar. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Bir koordinat çifti, bir yükseklik ve bir genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| x | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| yükseklik | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Bir koordinat çifti, bir yükseklik ve bir genişlik ile belirtilen sınırlayıcı bir dikdörtgen tarafından tanımlanan bir elips çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Elipsin renk, genişlik ve stilini belirleyen [Pen](/psd/python-net/aspose.psd/pen/). |
| x | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| yükseklik | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Çizilecek görüntü. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Çizilecek görüntü. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Çizilecek görüntü. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Kaynak dikdörtgen. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Çizilecek görüntü. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Kaynak dikdörtgen. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Çizilecek görüntü. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Ölçü birimleri. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Çizilecek görüntü. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Ölçü birimleri. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Çizilecek görüntü. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Ölçü birimleri. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Belirtilen <paramref name="image" /> öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Çizilecek görüntü. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Kaynak dikdörtgen. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Ölçü birimleri. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Çizilen görüntünün sol üst köşesini temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapısı. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| point | [Point](/psd/python-net/aspose.psd/point) | Çizilen görüntünün sol üst köşesini temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapısı. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Çizilen görüntünün konumunu ve boyutunu belirten [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Çizilen görüntünün konumunu ve boyutunu belirten [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafik birimi. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafik birimi. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafik birimi. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Hedef dikdörtgen. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafik birimi. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Dikdörtgen kaynağı. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Dikdörtgen hedefi. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafik birimi. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dikdörtgen kaynağı. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dikdörtgen hedefi. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafik birimi. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Dikdörtgen kaynağı. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Dikdörtgen hedefi. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafik birimi. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dikdörtgen kaynağı. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dikdörtgen hedefi. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Grafik birimi. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| x | float | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | float | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| x | float | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | float | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | float | Çizilen görüntünün genişliği. |
| yükseklik | float | Çizilen görüntünün yüksekliği. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Belirtilen [Graphics.image](/psd/python-net/aspose.psd/graphics/)'i, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | int | Çizilen görüntünün genişliği. |
| yükseklik | int | Çizilen görüntünün yüksekliği. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) yapısı, çizilen görüntünün sol üst köşesini belirtir. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) çizilen görüntünün sol üst köşesini belirtir. Dikdörtgenin X ve Y özellikleri sol üst köşeyi tanımlar. Genişlik ve Yükseklik özellikleri göz ardı edilir. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Belirtilen resmi, özgün fiziksel boyutunu kullanarak, bir koordinat çifti ile belirtilen konumda çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | int | Parametre kullanılmaz. |
| yükseklik | int | Parametre kullanılmaz. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Belirtilen resmi ölçeklendirmeden çizer ve gerekirse, belirtilen dikdörtgene sığması için kırpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Üzerine çizilecek görüntü. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Görüntünün çizileceği [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

İki [Point](/psd/python-net/aspose.psd/point/) yapısını bağlayan bir çizgi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) bağlanacak ilk noktayı temsil eden yapı. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) bağlanacak ikinci noktayı temsil eden yapı. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

İki [Point](/psd/python-net/aspose.psd/point/) yapısını bağlayan bir çizgi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) bağlanacak ilk noktayı temsil eden yapı. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) bağlanacak ikinci noktayı temsil eden yapı. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| x1 | int | İlk noktanın x koordinatı. |
| y1 | int | İlk noktanın y koordinatı. |
| x2 | int | İkinci noktanın x koordinatı. |
| y2 | int | İkinci noktanın y koordinatı. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) çizginin rengini, genişliğini ve stilini belirler. |
| x1 | float | İlk noktanın x koordinatı. |
| y1 | float | İlk noktanın y koordinatı. |
| x2 | float | İkinci noktanın x koordinatı. |
| y2 | float | İkinci noktanın y koordinatı. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Bir dizi [Point](/psd/python-net/aspose.psd/point/) yapısını bağlayan bir dizi çizgi segmenti çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) çizgi segmentlerinin rengini, genişliğini ve stilini belirler. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Bağlanacak noktaları temsil eden [Point](/psd/python-net/aspose.psd/point/) yapı dizisi. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Bir dizi [Point](/psd/python-net/aspose.psd/point/) yapısını bağlayan bir dizi çizgi segmenti çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) çizgi segmentlerinin rengini, genişliğini ve stilini belirler. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Bağlanacak noktaları temsil eden [Point](/psd/python-net/aspose.psd/point/) yapı dizisi. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yolun rengini, genişliğini ve stilini belirler. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Çizmek için [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) pasta şeklinin rengini, genişliğini ve stilini belirler. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | X ekseninden pasta şeklinin ilk kenarına doğru saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | Açı, <paramref name="startAngle" /> parametresinden saat yönünde derece cinsinden ölçülerek pasta şeklinin ikinci kenarına kadar ölçülür. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) pasta şeklinin rengini, genişliğini ve stilini belirler. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden yapı. |
| start_angle | float | X ekseninden pasta şeklinin ilk kenarına doğru saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | Açı, <paramref name="startAngle" /> parametresinden saat yönünde derece cinsinden ölçülerek pasta şeklinin ikinci kenarına kadar ölçülür. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Bir koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) pasta şeklinin rengini, genişliğini ve stilini belirler. |
| x | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| yükseklik | float | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | float | X ekseninden pasta şeklinin ilk kenarına doğru saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | float | Açı, <paramref name="startAngle" /> parametresinden saat yönünde derece cinsinden ölçülerek pasta şeklinin ikinci kenarına kadar ölçülür. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Bir koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) pasta şeklinin rengini, genişliğini ve stilini belirler. |
| x | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| yükseklik | int | Pasta şeklinin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | int | X ekseninden pasta şeklinin ilk kenarına doğru saat yönünde derece cinsinden ölçülen açı. |
| sweep_angle | int | Açı, <paramref name="startAngle" /> parametresinden saat yönünde derece cinsinden ölçülerek pasta şeklinin ikinci kenarına kadar ölçülür. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan bir çokgen çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) çokgenin rengini, genişliğini ve stilini belirler. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) yapılarını içeren dizi, çokgenin köşe noktalarını temsil eder. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan bir çokgen çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) çokgenin rengini, genişliğini ve stilini belirler. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) yapılarını içeren dizi, çokgenin köşe noktalarını temsil eder. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Dikdörtgenin renk, genişlik ve stilini belirleyen bir [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Çizilecek dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Dikdörtgenin renk, genişlik ve stilini belirleyen bir [Pen](/psd/python-net/aspose.psd/pen/). |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Çizilecek dikdörtgeni temsil eden bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Dikdörtgenin renk, genişlik ve stilini belirleyen bir [Pen](/psd/python-net/aspose.psd/pen/). |
| x | float | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Çizilecek dikdörtgenin genişliği. |
| yükseklik | float | Çizilecek dikdörtgenin yüksekliği. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Bir koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Dikdörtgenin renk, genişlik ve stilini belirleyen bir [Pen](/psd/python-net/aspose.psd/pen/). |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Çizilecek dikdörtgenin genişliği. |
| yükseklik | int | Çizilecek dikdörtgenin yüksekliği. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Bir dizi [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile belirtilen bir dizi dikdörtgen çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) dikdörtgenlerin kenar hatlarının renk, genişlik ve stilini belirler. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapılarını içeren dizi, çizilecek dikdörtgenleri temsil eder. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Bir dizi [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ile belirtilen bir dizi dikdörtgen çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) dikdörtgenlerin kenar hatlarının renk, genişlik ve stilini belirler. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapılarını içeren dizi, çizilecek dikdörtgenleri temsil eder. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Belirtilen metin dizesini, belirtilen dikdörtgende, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesneleriyle çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) çizilen metnin renk ve dokusunu belirler. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) çizilen metnin konumunu belirten yapı. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Belirtilen metin dizesini, belirtilen dikdörtgende, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak, belirtilen [StringFormat](/psd/python-net/aspose.psd/stringformat/) biçimlendirme öznitelikleriyle çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) çizilen metnin renk ve dokusunu belirler. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) çizilen metnin konumunu belirten yapı. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirler. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Belirtilen metin dizesini, belirtilen konumda, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) çizilen metnin renk ve dokusunu belirler. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) çizilen metnin sol üst köşesini belirten yapı. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Belirtilen metin dizesini, belirtilen konumda, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak, belirtilen [StringFormat](/psd/python-net/aspose.psd/stringformat/) biçimlendirme öznitelikleriyle çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) çizilen metnin renk ve dokusunu belirler. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) çizilen metnin sol üst köşesini belirten yapı. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirler. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Belirtilen metin dizesini, belirtilen konumda, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) çizilen metnin renk ve dokusunu belirler. |
| x | float | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | float | Çizilen metnin sol üst köşesinin y koordinatı. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Belirtilen metin dizesini, belirtilen konumda, belirtilen [Brush](/psd/python-net/aspose.psd/brush/) ve [Font](/psd/python-net/aspose.psd/font/) nesnelerini kullanarak, belirtilen [StringFormat](/psd/python-net/aspose.psd/stringformat/) biçimlendirme öznitelikleriyle çizer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| s | string | Çizilecek dize. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) dizenin metin biçimini tanımlar. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) çizilen metnin renk ve dokusunu belirler. |
| x | float | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | float | Çizilen metnin sol üst köşesinin y koordinatı. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirler. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma kipini kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilim ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) doldurma kipini kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/psd/python-net/aspose.psd/fillmode/) enum üyesi. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipini kullanarak doldurur. Bu yöntem varsayılan 0,5 gerilim kullanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/psd/python-net/aspose.psd/fillmode/) enum üyesi. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Dolgunun özelliklerini belirleyen bir [Brush](/psd/python-net/aspose.psd/brush/). |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/psd/python-net/aspose.psd/fillmode/) enum üyesi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından tanımlanan kapalı kardinal spline eğrisinin içini belirtilen doldurma kipi ve gerilimi kullanarak doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Dolgunun özelliklerini belirleyen bir [Brush](/psd/python-net/aspose.psd/brush/). |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Spline'ı tanımlayan [PointF](/psd/python-net/aspose.psd/pointf/) yapıların dizisi. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Eğrinin nasıl doldurulacağını belirleyen [FillMode](/psd/python-net/aspose.psd/fillmode/) enum üyesi. |
| gerilim | float | Eğrinin gerilimini belirten 0.0F'ye eşit veya daha büyük değer. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı, elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eder. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı tarafından belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı, elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eder. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| x | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| yükseklik | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| x | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| yükseklik | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nesnesinin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Doldurulacak yolu temsil eden [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir pasta diliminin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı, dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eder. |
| start_angle | float | Dilimin birinci kenarına x ekseninden saat yönünde ölçülen açı (derece cinsinden). |
| sweep_angle | float | <paramref name="startAngle" /> parametresinden dilimin ikinci kenarına saat yönünde ölçülen açı (derece cinsinden). |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Bir [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yapısı ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir pasta diliminin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı, dilim bölümünün geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eder. |
| start_angle | float | Dilimin birinci kenarına x ekseninden saat yönünde ölçülen açı (derece cinsinden). |
| sweep_angle | float | <paramref name="startAngle" /> parametresinden dilimin ikinci kenarına saat yönünde ölçülen açı (derece cinsinden). |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir pasta diliminin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| x | float | Dilimin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Dilimin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Dilimin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| yükseklik | float | Dilimin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | float | Dilimin birinci kenarına x ekseninden saat yönünde ölçülen açı (derece cinsinden). |
| sweep_angle | float | <paramref name="startAngle" /> parametresinden dilimin ikinci kenarına saat yönünde ölçülen açı (derece cinsinden). |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Koordinat çifti, genişlik, yükseklik ve iki radyal çizgiyle belirtilen elips tarafından tanımlanan bir pasta diliminin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| x | int | Dilimin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Dilimin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Dilimin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| yükseklik | int | Dilimin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| start_angle | int | Dilimin birinci kenarına x ekseninden saat yönünde ölçülen açı (derece cinsinden). |
| sweep_angle | int | <paramref name="startAngle" /> parametresinden dilimin ikinci kenarına saat yönünde ölçülen açı (derece cinsinden). |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Doldurulacak çokgenin köşe noktalarını temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapı dizisi. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı ve [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) ile belirtilen noktalarla tanımlanan bir çokgenin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Doldurulacak çokgenin köşe noktalarını temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapı dizisi. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Doldurulacak çokgenin köşe noktalarını temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapı dizisi. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Dolgunun stilini belirleyen [FillMode](/psd/python-net/aspose.psd/fillmode/) enum üyesi. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Bir dizi [PointF](/psd/python-net/aspose.psd/pointf/) yapısı tarafından belirtilen noktalarla tanımlanan bir çokgenin içini belirtilen doldurma kipini kullanarak doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Doldurulacak çokgenin köşe noktalarını temsil eden [PointF](/psd/python-net/aspose.psd/pointf/) yapı dizisi. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Dolgunun stilini belirleyen [FillMode](/psd/python-net/aspose.psd/fillmode/) enum üyesi. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı, doldurulacak dikdörtgeni temsil eder. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Bir [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapısı, doldurulacak dikdörtgeni temsil eder. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| x | float | Doldurulacak dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Doldurulacak dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Doldurulacak dikdörtgenin genişliği. |
| yükseklik | float | Doldurulacak dikdörtgenin yüksekliği. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Koordinat çifti, genişlik ve yükseklik ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| x | int | Doldurulacak dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Doldurulacak dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Doldurulacak dikdörtgenin genişliği. |
| yükseklik | int | Doldurulacak dikdörtgenin yüksekliği. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Doldurulacak dikdörtgenleri temsil eden [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapı dizisi. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Doldurulacak dikdörtgenleri temsil eden [Rectangle](/psd/python-net/aspose.psd/rectangle/) yapı dizisi. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Bir [Region](/psd/python-net/aspose.psd/region/) nesnesinin içini doldurur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) dolgunun özelliklerini belirler. |
| region | [Region](/psd/python-net/aspose.psd/region) | Doldurulacak alanı temsil eden [Region](/psd/python-net/aspose.psd/region/). |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Bu [Graphics](/psd/python-net/aspose.psd/graphics/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/psd/python-net/aspose.psd/matrix/) öğesini, belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile ön ekleyerek çarpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/psd/python-net/aspose.psd/matrix/). |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Bu [Graphics](/psd/python-net/aspose.psd/graphics/) nesnesinin yerel geometrik dönüşümünü temsil eden [Matrix](/psd/python-net/aspose.psd/matrix/) öğesini, belirtilen [Matrix](/psd/python-net/aspose.psd/matrix/) ile belirtilen sırada çarpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Geometrik dönüşümü çarpmak için kullanılacak [Matrix](/psd/python-net/aspose.psd/matrix/). |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | İki matrisi hangi sırada çarpacağını belirten bir [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/). |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem dönüşüme rotasyonu ön ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Rotasyon açısı. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Yerel geometrik dönüşümü belirtilen miktarda, belirtilen sırada döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Rotasyon açısı. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Rotasyon matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/). |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Yerel geometrik dönüşümü belirtilen miktarlarda ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönünde ölçeklenecek miktarı. |
| sy | float | Dönüşümün y ekseni yönünde ölçeklenecek miktarı. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Yerel geometrik dönüşümü belirtilen miktarlarda, belirtilen sırada ölçeklendirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sx | float | Dönüşümün x ekseni yönünde ölçeklenecek miktarı. |
| sy | float | Dönüşümün y ekseni yönünde ölçeklenecek miktarı. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ölçekleme matrisini ekleyecek mi yoksa ön ekleyecek mi olduğunu belirten bir [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Yerel geometrik dönüşümü belirtilen boyutlarda taşır. Bu yöntem dönüşüme taşıma işlemini ön ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x yönündeki taşıma değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Yerel geometrik dönüşümü belirtilen boyutlarda, belirtilen sırada taşır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dx | float | x yönündeki taşıma değeri. |
| dy | float | y eksenindeki çevirinin değeri. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Çevirinin uygulanacağı sıra (başına ekleme veya sona ekleme). |

