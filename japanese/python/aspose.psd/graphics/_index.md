---
title: "Graphics クラス"
type: docs
weight: 1550
url: /ja/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | [Graphics](/psd/python-net/aspose.psd/graphics/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | クリップ領域を取得または設定します。 |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | 合成品質を取得または設定します。 |
| dpi_x | float | r | この Aspose.PSD.Graphics の水平解像度を取得します。 |
| dpi_y | float | r | この Aspose.PSD.Graphics の垂直解像度を取得します。 |
| image | [Image](/psd/python-net/aspose.psd/image) | r | 画像を取得します。 |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | 補間モードを取得または設定します。 |
| is_in_begin_update_call | bool | r | グラフィックスが BeginUpdate 呼び出し状態にあるかどうかを示す値を取得します。 |
| page_scale | float | r/w | この Aspose.PSD.Graphics のワールド単位とページ単位間のスケーリングを取得または設定します。 |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | この Aspose.PSD.Graphics でページ座標に使用される測定単位を取得または設定します。 |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | 描画用のペイント可能なベクター画像を作成するために使用される画像オプションを取得または設定します。 |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | スムージングモードを取得または設定します。 |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | テキストのレンダリングヒントを取得または設定します。 |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | この [Graphics](/psd/python-net/aspose.psd/graphics/) の幾何学的ワールド変換のコピーを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| begin_update() | 以下のグラフィック操作のキャッシュを開始します。その後に適用されるグラフィック効果はすぐには適用されず、代わりに EndUpdate がすべての効果を一度に適用します。 |
| [clear(color)](#clear_color_1) | 指定された色を使用してグラフィックサーフェスをクリアします。 |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された楕円の一部を表す弧を描画します。 |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された楕円の一部を表す弧を描画します。 |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | 座標のペア、幅、高さで指定された楕円の一部を表す弧を描画します。 |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | 座標のペア、幅、高さで指定された楕円の一部を表す弧を描画します。 |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | 4 つの [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義されたベジエスプラインを描画します。 |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | 4 つの [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義されたベジエスプラインを描画します。 |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | 点を表す 4 つの順序付けられた座標ペアで定義されたベジエスプラインを描画します。 |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | [Point](/psd/python-net/aspose.psd/point/) 構造体の配列からベジエスプラインの系列を描画します。 |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | [Point](/psd/python-net/aspose.psd/point/) 構造体の配列からベジエスプラインの系列を描画します。 |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りモードを使用します。 |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りモードを使用します。 |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプラインを、指定されたテンションで描画します。このメソッドはデフォルトの [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りモードを使用します。 |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプラインを、指定されたテンションで描画します。このメソッドはデフォルトの [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りモードを使用します。 |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | 指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | 指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | 指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。<br/>            このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | 指定されたテンションを使用して、指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。 |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | 指定されたテンションを使用して、指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。 |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | 指定されたテンションを使用して、指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。 |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | 指定されたテンションを使用して、指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。 |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | 境界となる [RectangleF](/psd/python-net/aspose.psd/rectanglef/) で定義された楕円を描画します。 |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | 境界となる [RectangleF](/psd/python-net/aspose.psd/rectanglef/) で定義された楕円を描画します。 |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | 座標のペアと高さ、幅で指定された境界矩形により定義された楕円を描画します。 |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | 座標のペアと高さ、幅で指定された境界矩形により定義された楕円を描画します。 |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | 指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | 指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | 指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | 指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | 指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | 指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | 指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | 指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、元の物理サイズのままで、指定された位置に描画します。 |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、元の物理サイズのままで、指定された位置に描画します。 |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、元の物理サイズのままで、指定された位置に描画します。 |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、元の物理サイズのままで、指定された位置に描画します。 |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | 指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。 |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | 指定された画像を元の物理サイズで、指定された位置に描画します。 |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | 指定された画像を元の物理サイズで、指定された位置に描画します。 |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | 指定された画像を元の物理サイズで、座標のペアで指定された位置に描画します。 |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | 指定された画像を元の物理サイズで、指定された位置に描画します。 |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | 指定された画像をスケーリングせずに描画し、必要に応じて指定された矩形に収まるようにクリップします。 |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | 2つの [Point](/psd/python-net/aspose.psd/point/) 構造体を結ぶ線を描画します。 |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | 2つの [Point](/psd/python-net/aspose.psd/point/) 構造体を結ぶ線を描画します。 |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | 座標のペアで指定された2点を結ぶ線を描画します。 |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | 座標のペアで指定された2点を結ぶ線を描画します。 |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | 配列の [Point](/psd/python-net/aspose.psd/point/) 構造体を結ぶ一連の線分を描画します。 |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | 配列の [Point](/psd/python-net/aspose.psd/point/) 構造体を結ぶ一連の線分を描画します。 |
| [draw_path(pen, path)](#draw_path_pen_path_61) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) を描画します。 |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体と2本の放射線で指定された楕円により定義された円弧形を描画します。 |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体と2本の放射線で指定された楕円により定義された円弧形を描画します。 |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | 座標のペア、幅、高さ、そして2本の放射線で指定された楕円により定義された円弧形を描画します。 |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | 座標のペア、幅、高さ、そして2本の放射線で指定された楕円により定義された円弧形を描画します。 |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された多角形を描画します。 |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された多角形を描画します。 |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された矩形を描画します。 |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された矩形を描画します。 |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | 座標のペア、幅、高さで指定された矩形を描画します。 |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | 座標のペア、幅、高さで指定された矩形を描画します。 |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された一連の矩形を描画します。 |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された一連の矩形を描画します。 |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | 指定された矩形内に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用して、指定されたテキスト文字列を描画します。 |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | 指定された矩形内に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用し、指定された [StringFormat](/psd/python-net/aspose.psd/stringformat/) の書式属性を適用して、指定されたテキスト文字列を描画します。 |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | 指定された位置に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用して、指定されたテキスト文字列を描画します。 |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | 指定された位置に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用し、指定された [StringFormat](/psd/python-net/aspose.psd/stringformat/) の書式属性を適用して、指定されたテキスト文字列を描画します。 |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | 指定された位置に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用して、指定されたテキスト文字列を描画します。 |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | 指定された位置に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用し、指定された [StringFormat](/psd/python-net/aspose.psd/stringformat/) の書式属性を適用して、指定されたテキスト文字列を描画します。 |
| end_update() | BeginUpdate が呼び出された後に開始されたグラフィック操作のキャッシュを終了します。このメソッドを呼び出すと、直前のグラフィック操作が一度に適用されます。 |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りつぶしモードを使用します。 |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りつぶしモードを使用します。 |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードで塗りつぶします。このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | 配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードで塗りつぶします。このメソッドはデフォルトのテンション 0.5 を使用します。 |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | 指定された塗りつぶしモードとテンションを使用して、[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。 |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | 指定された塗りつぶしモードとテンションを使用して、[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。 |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。 |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。 |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | 座標のペア、幅、および高さで指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。 |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | 座標のペア、幅、および高さで指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。 |
| [fill_path(brush, path)](#fill_path_brush_path_90) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の内部を塗りつぶします。 |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された楕円と2 本の放射線で定義されたパイセクションの内部を塗りつぶします。 |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された楕円と2 本の放射線で定義されたパイセクションの内部を塗りつぶします。 |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | 座標のペア、幅、高さ、および2 本の放射線で指定された楕円で定義されたパイセクションの内部を塗りつぶします。 |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | 座標のペア、幅、高さ、および2 本の放射線で指定された楕円で定義されたパイセクションの内部を塗りつぶします。 |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で指定された点の配列と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) を使用して定義された多角形の内部を塗りつぶします。 |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で指定された点の配列と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) を使用して定義された多角形の内部を塗りつぶします。 |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で指定された点の配列と指定された塗りつぶしモードを使用して定義された多角形の内部を塗りつぶします。 |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で指定された点の配列と指定された塗りつぶしモードを使用して定義された多角形の内部を塗りつぶします。 |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体で指定された矩形の内部を塗りつぶします。 |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体で指定された矩形の内部を塗りつぶします。 |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | 座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。 |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | 座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。 |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体で指定された一連の矩形の内部を塗りつぶします。 |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体で指定された一連の矩形の内部を塗りつぶします。 |
| [fill_region(brush, region)](#fill_region_brush_region_105) | [Region](/psd/python-net/aspose.psd/region/) の内部を塗りつぶします。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | この [Graphics](/psd/python-net/aspose.psd/graphics/) のローカル幾何変換を表す [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された [Matrix](/psd/python-net/aspose.psd/matrix/) を前置して乗算します。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | この [Graphics](/psd/python-net/aspose.psd/graphics/) のローカル幾何変換を表す [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された順序で指定された [Matrix](/psd/python-net/aspose.psd/matrix/) を乗算します。 |
| reset_transform() | [Graphics.transform](/psd/python-net/aspose.psd/graphics/) プロパティを単位行列にリセットします。 |
| [rotate_transform(angle)](#rotate_transform_angle_108) | ローカル幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に前置します。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | ローカル幾何変換を指定された量だけ、指定された順序で回転させます。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | ローカル幾何変換を指定された量だけ拡大縮小します。このメソッドはスケーリング行列を変換の先頭に前置します。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | ローカル幾何変換を指定された量だけ、指定された順序で拡大縮小します。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に前置します。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | ローカル幾何変換を指定された寸法だけ、指定された順序で平行移動します。 |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

[Graphics](/psd/python-net/aspose.psd/graphics/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | ソース画像です。 |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

指定された色を使用してグラフィックサーフェスをクリアします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | グラフィックスサーフェスをクリアする色です。 |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された楕円の一部を表す弧を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 円弧の色、幅、スタイルを決定する [Pen](/psd/python-net/aspose.psd/pen/)。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 楕円の境界を定義する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |
| start_angle | float | x 軸から円弧の開始点まで時計回りに測定された角度（度）です。 |
| sweep_angle | float | <paramref name=\"startAngle\" /> パラメータから円弧の終了点まで時計回りに測定された角度（度）です。 |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された楕円の一部を表す弧を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 円弧の色、幅、スタイルを決定する [Pen](/psd/python-net/aspose.psd/pen/)。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 楕円の境界を定義する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |
| start_angle | float | x 軸から円弧の開始点まで時計回りに測定された角度（度）です。 |
| sweep_angle | float | <paramref name=\"startAngle\" /> パラメータから円弧の終了点まで時計回りに測定された角度（度）です。 |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

座標のペア、幅、高さで指定された楕円の一部を表す弧を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 円弧の色、幅、スタイルを決定する [Pen](/psd/python-net/aspose.psd/pen/)。 |
| x | float | 楕円を定義する矩形の左上隅の x 座標です。 |
| y | float | 楕円を定義する矩形の左上隅の y 座標です。 |
| width | float | 楕円を定義する矩形の幅です。 |
| 高さ | float | 楕円を定義する矩形の高さです。 |
| start_angle | float | x 軸から円弧の開始点まで時計回りに測定された角度（度）です。 |
| sweep_angle | float | <paramref name=\"startAngle\" /> パラメータから円弧の終了点まで時計回りに測定された角度（度）です。 |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

座標のペア、幅、高さで指定された楕円の一部を表す弧を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 円弧の色、幅、スタイルを決定する [Pen](/psd/python-net/aspose.psd/pen/)。 |
| x | int | 楕円を定義する矩形の左上隅の x 座標です。 |
| y | int | 楕円を定義する矩形の左上隅の y 座標です。 |
| width | int | 楕円を定義する矩形の幅です。 |
| 高さ | int | 楕円を定義する矩形の高さです。 |
| start_angle | int | x 軸から円弧の開始点まで時計回りに測定された角度（度）です。 |
| sweep_angle | int | <paramref name=\"startAngle\" /> パラメータから円弧の終了点まで時計回りに測定された角度（度）です。 |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

4 つの [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義されたベジエスプラインを描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、スタイルを決定します。 |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体は曲線の開始点を表します。 |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体は曲線の最初の制御点を表します。 |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体は曲線の第2制御点を表します。 |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体は曲線の終了点を表します。 |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

4 つの [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義されたベジエスプラインを描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、スタイルを決定します。 |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体は曲線の開始点を表します。 |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体は曲線の最初の制御点を表します。 |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体は曲線の第2制御点を表します。 |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体は曲線の終了点を表します。 |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

点を表す 4 つの順序付けられた座標ペアで定義されたベジエスプラインを描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、スタイルを決定します。 |
| x1 | float | 曲線の開始点のX座標。 |
| y1 | float | 曲線の開始点のY座標。 |
| x2 | float | 曲線の最初の制御点のX座標。 |
| y2 | float | 曲線の最初の制御点のY座標。 |
| x3 | float | 曲線の第2制御点のX座標。 |
| y3 | float | 曲線の第2制御点のY座標。 |
| x4 | float | 曲線の終了点のX座標。 |
| y4 | float | 曲線の終了点のY座標。 |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

[Point](/psd/python-net/aspose.psd/point/) 構造体の配列からベジエスプラインの系列を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、スタイルを決定します。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 曲線を決定する点を表す[Point](/psd/python-net/aspose.psd/point/) 構造体の配列。 |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

[Point](/psd/python-net/aspose.psd/point/) 構造体の配列からベジエスプラインの系列を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、スタイルを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 曲線を決定する点を表す[Point](/psd/python-net/aspose.psd/point/) 構造体の配列。 |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りモードを使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りモードを使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプラインを、指定されたテンションで描画します。このメソッドはデフォルトの [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りモードを使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| テンション | float | 0.0F以上の値で、曲線のテンションを指定します。 |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプラインを、指定されたテンションで描画します。このメソッドはデフォルトの [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りモードを使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| テンション | float | 0.0F以上の値で、曲線のテンションを指定します。 |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。<br/>            このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| offset | int | 曲線の開始点まで、<paramref name="points" /> パラメータの配列の最初の要素からのオフセットです。 |
| number_of_segments | int | 曲線に含める、開始点の後のセグメント数です。 |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

指定されたテンションを使用して、指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| offset | int | 曲線の開始点まで、<paramref name="points" /> パラメータの配列の最初の要素からのオフセットです。 |
| number_of_segments | int | 曲線に含める、開始点の後のセグメント数です。 |
| テンション | float | 0.0F以上の値で、曲線のテンションを指定します。 |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

指定されたテンションを使用して、指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。描画は配列の先頭からオフセットして開始されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| offset | int | 曲線の開始点まで、<paramref name="points" /> パラメータの配列の最初の要素からのオフセットです。 |
| number_of_segments | int | 曲線に含める、開始点の後のセグメント数です。 |
| テンション | float | 0.0F以上の値で、曲線のテンションを指定します。 |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

指定されたテンションを使用して、指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 曲線を定義する点を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |
| テンション | float | 0.0F以上の値で、曲線のテンションを指定します。 |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

指定されたテンションを使用して、指定された配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を通るカーディナルスプラインを描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は曲線の色、幅、高さを決定します。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 曲線を定義する点を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |
| テンション | float | 0.0F以上の値で、曲線のテンションを指定します。 |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

境界となる [RectangleF](/psd/python-net/aspose.psd/rectanglef/) で定義された楕円を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 楕円の色、幅、スタイルを決定する [Pen](/psd/python-net/aspose.psd/pen/) です。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 楕円の境界を定義する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

境界となる [RectangleF](/psd/python-net/aspose.psd/rectanglef/) で定義された楕円を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 楕円の色、幅、スタイルを決定する [Pen](/psd/python-net/aspose.psd/pen/) です。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 楕円の境界を定義する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

座標のペアと高さ、幅で指定された境界矩形により定義された楕円を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 楕円の色、幅、スタイルを決定する [Pen](/psd/python-net/aspose.psd/pen/) です。 |
| x | float | 楕円を定義する外接矩形の左上隅の x 座標です。 |
| y | float | 楕円を定義する外接矩形の左上隅の y 座標です。 |
| width | float | 楕円を定義する外接矩形の幅です。 |
| 高さ | float | 楕円を定義する外接矩形の高さです。 |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

座標のペアと高さ、幅で指定された境界矩形により定義された楕円を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 楕円の色、幅、スタイルを決定する [Pen](/psd/python-net/aspose.psd/pen/) です。 |
| x | int | 楕円を定義する外接矩形の左上隅の x 座標です。 |
| y | int | 楕円を定義する外接矩形の左上隅の y 座標です。 |
| width | int | 楕円を定義する外接矩形の幅です。 |
| 高さ | int | 楕円を定義する外接矩形の高さです。 |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 描画する画像です。 |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 平行四辺形を定義する 3 つの PointF 構造体の配列です。 |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 描画する画像です。 |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 平行四辺形を定義する 3 つの PointF 構造体の配列です。 |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 描画する画像です。 |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 平行四辺形を定義する 3 つの PointF 構造体の配列です。 |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ソース矩形です。 |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 描画する画像です。 |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 平行四辺形を定義する 3 つの PointF 構造体の配列です。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | ソース矩形です。 |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 描画する画像です。 |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 平行四辺形を定義する 3 つの PointF 構造体の配列です。 |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ソース矩形です。 |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 測定単位です。 |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 描画する画像です。 |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 平行四辺形を定義する 3 つの PointF 構造体の配列です。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | ソース矩形です。 |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 測定単位です。 |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 描画する画像です。 |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | 平行四辺形を定義する 3 つの PointF 構造体の配列です。 |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ソース矩形です。 |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 測定単位です。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 画像属性です。 |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

指定された <paramref name="image" /> の指定された部分を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 描画する画像です。 |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 平行四辺形を定義する 3 つの PointF 構造体の配列です。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | ソース矩形です。 |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | 測定単位です。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 画像属性です。 |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 描画された画像の左上隅を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体です。 |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| point | [Point](/psd/python-net/aspose.psd/point) | 描画された画像の左上隅を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体です。 |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 描画された画像の位置とサイズを指定する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体です。 |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 描画された画像の位置とサイズを指定する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体です。 |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 宛先矩形です。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | グラフィックス単位です。 |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 宛先矩形です。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | グラフィックス単位です。 |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 宛先矩形です。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | グラフィックス単位です。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 画像属性です。 |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 宛先矩形です。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | グラフィックス単位です。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 画像属性です。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形ソースです。 |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形宛先です。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | グラフィックス単位です。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形ソースです。 |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形宛先です。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | グラフィックス単位です。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形ソースです。 |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形宛先です。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | グラフィックス単位です。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 画像属性です。 |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形ソースです。 |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形宛先です。 |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | グラフィックス単位です。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 画像属性です。 |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| x | float | 描画された画像の左上隅の x 座標です。 |
| y | float | 描画された画像の左上隅の y 座標です。 |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、元の物理サイズのままで、指定された位置に描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| x | int | 描画された画像の左上隅の x 座標です。 |
| y | int | 描画された画像の左上隅の y 座標です。 |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| x | float | 描画された画像の左上隅の x 座標です。 |
| y | float | 描画された画像の左上隅の y 座標です。 |
| width | float | 描画された画像の幅です。 |
| 高さ | float | 描画された画像の高さです。 |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

指定された [Graphics.image](/psd/python-net/aspose.psd/graphics/) を、指定された位置と指定されたサイズで描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| x | int | 描画された画像の左上隅の x 座標です。 |
| y | int | 描画された画像の左上隅の y 座標です。 |
| width | int | 描画された画像の幅です。 |
| 高さ | int | 描画された画像の高さです。 |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

指定された画像を元の物理サイズで、指定された位置に描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) 構造体で、描画された画像の左上隅を指定します。 |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

指定された画像を元の物理サイズで、指定された位置に描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) は描画された画像の左上隅を指定します。矩形の X および Y プロパティが左上隅を指定し、Width と Height プロパティは無視されます。 |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

指定された画像を元の物理サイズで、座標のペアで指定された位置に描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| x | int | 描画された画像の左上隅の x 座標です。 |
| y | int | 描画された画像の左上隅の y 座標です。 |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

指定された画像を元の物理サイズで、指定された位置に描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| x | int | 描画された画像の左上隅の x 座標です。 |
| y | int | 描画された画像の左上隅の y 座標です。 |
| width | int | このパラメーターは使用されません。 |
| 高さ | int | このパラメーターは使用されません。 |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

指定された画像をスケーリングせずに描画し、必要に応じて指定された矩形に収まるようにクリップします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | 描画に使用する画像です。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 画像を描画する [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

2つの [Point](/psd/python-net/aspose.psd/point/) 構造体を結ぶ線を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は線の色、幅、スタイルを決定します。 |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) 構造体で、接続する最初の点を表します。 |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) 構造体で、接続する2番目の点を表します。 |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

2つの [Point](/psd/python-net/aspose.psd/point/) 構造体を結ぶ線を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は線の色、幅、スタイルを決定します。 |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) 構造体で、接続する最初の点を表します。 |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) 構造体で、接続する2番目の点を表します。 |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

座標のペアで指定された2点を結ぶ線を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は線の色、幅、スタイルを決定します。 |
| x1 | int | 最初の点の x 座標。 |
| y1 | int | 最初の点の y 座標。 |
| x2 | int | 2番目の点の x 座標。 |
| y2 | int | 2番目の点の y 座標。 |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

座標のペアで指定された2点を結ぶ線を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は線の色、幅、スタイルを決定します。 |
| x1 | float | 最初の点の x 座標。 |
| y1 | float | 最初の点の y 座標。 |
| x2 | float | 2番目の点の x 座標。 |
| y2 | float | 2番目の点の y 座標。 |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

配列の [Point](/psd/python-net/aspose.psd/point/) 構造体を結ぶ一連の線分を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は線分の色、幅、スタイルを決定します。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 接続する点を表す [Point](/psd/python-net/aspose.psd/point/) 構造体の配列。 |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

配列の [Point](/psd/python-net/aspose.psd/point/) 構造体を結ぶ一連の線分を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) は線分の色、幅、スタイルを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 接続する点を表す [Point](/psd/python-net/aspose.psd/point/) 構造体の配列。 |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) はパスの色、幅、スタイルを決定します。 |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 描画する [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体と2本の放射線で指定された楕円により定義された円弧形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) はパイ形状の色、幅、スタイルを決定します。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で、パイ形状の元になる楕円を定義する外接矩形を表します。 |
| start_angle | float | パイ形状の最初の辺まで、x 軸から時計回りに測定した角度（度）です。 |
| sweep_angle | float | パイ形状の2番目の辺まで、<paramref name=\"startAngle\" /> パラメーターから時計回りに測定した角度（度）です。 |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体と2本の放射線で指定された楕円により定義された円弧形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) はパイ形状の色、幅、スタイルを決定します。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で、パイ形状の元になる楕円を定義する外接矩形を表します。 |
| start_angle | float | パイ形状の最初の辺まで、x 軸から時計回りに測定した角度（度）です。 |
| sweep_angle | float | パイ形状の2番目の辺まで、<paramref name=\"startAngle\" /> パラメーターから時計回りに測定した角度（度）です。 |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

座標のペア、幅、高さ、そして2本の放射線で指定された楕円により定義された円弧形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) はパイ形状の色、幅、スタイルを決定します。 |
| x | float | パイ形状の元になる楕円を定義する外接矩形の左上隅の x 座標。 |
| y | float | パイ形状の元になる楕円を定義する外接矩形の左上隅の y 座標。 |
| width | float | パイ形状の元になる楕円を定義する外接矩形の幅。 |
| 高さ | float | パイ形状の元になる楕円を定義する外接矩形の高さ。 |
| start_angle | float | パイ形状の最初の辺まで、x 軸から時計回りに測定した角度（度）です。 |
| sweep_angle | float | パイ形状の2番目の辺まで、<paramref name=\"startAngle\" /> パラメーターから時計回りに測定した角度（度）です。 |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

座標のペア、幅、高さ、そして2本の放射線で指定された楕円により定義された円弧形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) はパイ形状の色、幅、スタイルを決定します。 |
| x | int | パイ形状の元になる楕円を定義する外接矩形の左上隅の x 座標。 |
| y | int | パイ形状の元になる楕円を定義する外接矩形の左上隅の y 座標。 |
| width | int | パイ形状の元になる楕円を定義する外接矩形の幅。 |
| 高さ | int | パイ形状の元になる楕円を定義する外接矩形の高さ。 |
| start_angle | int | パイ形状の最初の辺まで、x 軸から時計回りに測定した角度（度）です。 |
| sweep_angle | int | パイ形状の2番目の辺まで、<paramref name=\"startAngle\" /> パラメーターから時計回りに測定した角度（度）です。 |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された多角形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) はポリゴンの色、幅、スタイルを決定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | ポリゴンの頂点を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された多角形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) はポリゴンの色、幅、スタイルを決定します。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | ポリゴンの頂点を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された矩形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 矩形の色、幅、スタイルを決定する[Pen](/psd/python-net/aspose.psd/pen/)です。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 描画する矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された矩形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 矩形の色、幅、スタイルを決定する[Pen](/psd/python-net/aspose.psd/pen/)です。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 描画する矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

座標のペア、幅、高さで指定された矩形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 矩形の色、幅、スタイルを決定する[Pen](/psd/python-net/aspose.psd/pen/)です。 |
| x | float | 描画する矩形の左上隅のX座標です。 |
| y | float | 描画する矩形の左上隅のY座標です。 |
| width | float | 描画する矩形の幅です。 |
| 高さ | float | 描画する矩形の高さです。 |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

座標のペア、幅、高さで指定された矩形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 矩形の色、幅、スタイルを決定する[Pen](/psd/python-net/aspose.psd/pen/)です。 |
| x | int | 描画する矩形の左上隅のX座標です。 |
| y | int | 描画する矩形の左上隅のY座標です。 |
| width | int | 描画する矩形の幅です。 |
| 高さ | int | 描画する矩形の高さです。 |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された一連の矩形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 矩形の輪郭の色、幅、スタイルを決定する[Pen](/psd/python-net/aspose.psd/pen/)です。 |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | 描画する矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の配列です。 |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された一連の矩形を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 矩形の輪郭の色、幅、スタイルを決定する[Pen](/psd/python-net/aspose.psd/pen/)です。 |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | 描画する矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の配列です。 |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

指定された矩形内に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用して、指定されたテキスト文字列を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| s | string | 描画する文字列です。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 文字列のテキスト形式を定義する[Font](/psd/python-net/aspose.psd/font/)です。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 描画されたテキストの色とテクスチャを決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 描画されたテキストの位置を指定する[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

指定された矩形内に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用し、指定された [StringFormat](/psd/python-net/aspose.psd/stringformat/) の書式属性を適用して、指定されたテキスト文字列を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| s | string | 描画する文字列です。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 文字列のテキスト形式を定義する[Font](/psd/python-net/aspose.psd/font/)です。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 描画されたテキストの色とテクスチャを決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 描画されたテキストの位置を指定する[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 描画されたテキストに適用される行間や配置などの書式属性を指定する[StringFormat](/psd/python-net/aspose.psd/stringformat/)です。 |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

指定された位置に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用して、指定されたテキスト文字列を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| s | string | 描画する文字列です。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 文字列のテキスト形式を定義する[Font](/psd/python-net/aspose.psd/font/)です。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 描画されたテキストの色とテクスチャを決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 描画されたテキストの左上隅を指定する[PointF](/psd/python-net/aspose.psd/pointf/)構造体です。 |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

指定された位置に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用し、指定された [StringFormat](/psd/python-net/aspose.psd/stringformat/) の書式属性を適用して、指定されたテキスト文字列を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| s | string | 描画する文字列です。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 文字列のテキスト形式を定義する[Font](/psd/python-net/aspose.psd/font/)です。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 描画されたテキストの色とテクスチャを決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 描画されたテキストの左上隅を指定する[PointF](/psd/python-net/aspose.psd/pointf/)構造体です。 |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 描画されたテキストに適用される行間や配置などの書式属性を指定する[StringFormat](/psd/python-net/aspose.psd/stringformat/)です。 |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

指定された位置に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用して、指定されたテキスト文字列を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| s | string | 描画する文字列です。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 文字列のテキスト形式を定義する[Font](/psd/python-net/aspose.psd/font/)です。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 描画されたテキストの色とテクスチャを決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| x | float | 描画されたテキストの左上隅のX座標です。 |
| y | float | 描画されたテキストの左上隅のY座標です。 |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

指定された位置に、指定された [Brush](/psd/python-net/aspose.psd/brush/) と [Font](/psd/python-net/aspose.psd/font/) オブジェクトを使用し、指定された [StringFormat](/psd/python-net/aspose.psd/stringformat/) の書式属性を適用して、指定されたテキスト文字列を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| s | string | 描画する文字列です。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 文字列のテキスト形式を定義する[Font](/psd/python-net/aspose.psd/font/)です。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 描画されたテキストの色とテクスチャを決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| x | float | 描画されたテキストの左上隅のX座標です。 |
| y | float | 描画されたテキストの左上隅のY座標です。 |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 描画されたテキストに適用される行間や配置などの書式属性を指定する[StringFormat](/psd/python-net/aspose.psd/stringformat/)です。 |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りつぶしモードを使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトのテンション 0.5 と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) 塗りつぶしモードを使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードで塗りつぶします。このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 曲線の塗りつぶし方法を決定する[FillMode](/psd/python-net/aspose.psd/fillmode/)列挙体のメンバーです。 |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

配列の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードで塗りつぶします。このメソッドはデフォルトのテンション 0.5 を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 曲線の塗りつぶし方法を決定する[FillMode](/psd/python-net/aspose.psd/fillmode/)列挙体のメンバーです。 |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

指定された塗りつぶしモードとテンションを使用して、[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 曲線の塗りつぶし方法を決定する[FillMode](/psd/python-net/aspose.psd/fillmode/)列挙体のメンバーです。 |
| テンション | float | 0.0F以上の値で、曲線のテンションを指定します。 |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

指定された塗りつぶしモードとテンションを使用して、[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | スプラインを定義する[PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。 |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 曲線の塗りつぶし方法を決定する[FillMode](/psd/python-net/aspose.psd/fillmode/)列挙体のメンバーです。 |
| テンション | float | 0.0F以上の値で、曲線のテンションを指定します。 |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 楕円を定義する外接矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 楕円を定義する外接矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

座標のペア、幅、および高さで指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| x | float | 楕円を定義する外接矩形の左上隅の x 座標です。 |
| y | float | 楕円を定義する外接矩形の左上隅の y 座標です。 |
| width | float | 楕円を定義する外接矩形の幅です。 |
| 高さ | float | 楕円を定義する外接矩形の高さです。 |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

座標のペア、幅、および高さで指定されたバウンディング矩形によって定義された楕円の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| x | int | 楕円を定義する外接矩形の左上隅の x 座標です。 |
| y | int | 楕円を定義する外接矩形の左上隅の y 座標です。 |
| width | int | 楕円を定義する外接矩形の幅です。 |
| 高さ | int | 楕円を定義する外接矩形の高さです。 |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 塗りつぶすパスを表す[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)です。 |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された楕円と2 本の放射線で定義されたパイセクションの内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | パイセクションの元になる楕円を定義する外接矩形を表す[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造体です。 |
| start_angle | float | パイセクションの第一辺まで、x軸から時計回りに測定した角度（度）です。 |
| sweep_angle | float | パイセクションの第二辺まで、<paramref name=\"startAngle\" /> パラメータから時計回りに測定した角度（度）です。 |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体で指定された楕円と2 本の放射線で定義されたパイセクションの内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | パイセクションの元になる楕円を定義する外接矩形を表す[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造体です。 |
| start_angle | float | パイセクションの第一辺まで、x軸から時計回りに測定した角度（度）です。 |
| sweep_angle | float | パイセクションの第二辺まで、<paramref name=\"startAngle\" /> パラメータから時計回りに測定した角度（度）です。 |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

座標のペア、幅、高さ、および2 本の放射線で指定された楕円で定義されたパイセクションの内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| x | float | パイ セクションの元になる楕円を定義する外接矩形の左上隅の x 座標です。 |
| y | float | パイ セクションの元になる楕円を定義する外接矩形の左上隅の y 座標です。 |
| width | float | パイ セクションの元になる楕円を定義する外接矩形の幅です。 |
| 高さ | float | パイ セクションの元になる楕円を定義する外接矩形の高さです。 |
| start_angle | float | パイセクションの第一辺まで、x軸から時計回りに測定した角度（度）です。 |
| sweep_angle | float | パイセクションの第二辺まで、<paramref name=\"startAngle\" /> パラメータから時計回りに測定した角度（度）です。 |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

座標のペア、幅、高さ、および2 本の放射線で指定された楕円で定義されたパイセクションの内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| x | int | パイ セクションの元になる楕円を定義する外接矩形の左上隅の x 座標です。 |
| y | int | パイ セクションの元になる楕円を定義する外接矩形の左上隅の y 座標です。 |
| width | int | パイ セクションの元になる楕円を定義する外接矩形の幅です。 |
| 高さ | int | パイ セクションの元になる楕円を定義する外接矩形の高さです。 |
| start_angle | int | パイセクションの第一辺まで、x軸から時計回りに測定した角度（度）です。 |
| sweep_angle | int | パイセクションの第二辺まで、<paramref name=\"startAngle\" /> パラメータから時計回りに測定した角度（度）です。 |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 構造体で指定された点の配列と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) を使用して定義された多角形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 塗りつぶすポリゴンの頂点を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 構造体で指定された点の配列と [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) を使用して定義された多角形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 塗りつぶすポリゴンの頂点を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 構造体で指定された点の配列と指定された塗りつぶしモードを使用して定義された多角形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 塗りつぶすポリゴンの頂点を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 塗りつぶしのスタイルを決定する [FillMode](/psd/python-net/aspose.psd/fillmode/) 列挙体のメンバーです。 |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

[PointF](/psd/python-net/aspose.psd/pointf/) 構造体で指定された点の配列と指定された塗りつぶしモードを使用して定義された多角形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 塗りつぶすポリゴンの頂点を表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 塗りつぶしのスタイルを決定する [FillMode](/psd/python-net/aspose.psd/fillmode/) 列挙体のメンバーです。 |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体で指定された矩形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 塗りつぶす矩形を表す [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体です。 |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体で指定された矩形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 塗りつぶす矩形を表す [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体です。 |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| x | float | 塗りつぶす矩形の左上隅の x 座標です。 |
| y | float | 塗りつぶす矩形の左上隅の y 座標です。 |
| width | float | 塗りつぶす矩形の幅です。 |
| 高さ | float | 塗りつぶす矩形の高さです。 |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

座標のペア、幅、および高さで指定された矩形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| x | int | 塗りつぶす矩形の左上隅の x 座標です。 |
| y | int | 塗りつぶす矩形の左上隅の y 座標です。 |
| width | int | 塗りつぶす矩形の幅です。 |
| 高さ | int | 塗りつぶす矩形の高さです。 |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体で指定された一連の矩形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | 塗りつぶす矩形を表す [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の配列です。 |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

[Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体で指定された一連の矩形の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | 塗りつぶす矩形を表す [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の配列です。 |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

[Region](/psd/python-net/aspose.psd/region/) の内部を塗りつぶします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 塗りつぶしの特性を決定する[Brush](/psd/python-net/aspose.psd/brush/)です。 |
| region | [Region](/psd/python-net/aspose.psd/region) | 塗りつぶす領域を表す [Region](/psd/python-net/aspose.psd/region/) です。 |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

この [Graphics](/psd/python-net/aspose.psd/graphics/) のローカル幾何変換を表す [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された [Matrix](/psd/python-net/aspose.psd/matrix/) を前置して乗算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 幾何変換に掛けるための [Matrix](/psd/python-net/aspose.psd/matrix/) です。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

この [Graphics](/psd/python-net/aspose.psd/graphics/) のローカル幾何変換を表す [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された順序で指定された [Matrix](/psd/python-net/aspose.psd/matrix/) を乗算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 幾何変換に掛けるための [Matrix](/psd/python-net/aspose.psd/matrix/) です。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 2 つの行列を掛け合わせる順序を指定する [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) です。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

ローカル幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に前置します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度です。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

ローカル幾何変換を指定された量だけ、指定された順序で回転させます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度です。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 回転行列を付加するか前置するかを指定する [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) です。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

ローカル幾何変換を指定された量だけ拡大縮小します。このメソッドはスケーリング行列を変換の先頭に前置します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| sx | float | x 軸方向に変換を拡大縮小する量です。 |
| sy | float | y 軸方向に変換を拡大縮小する量です。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

ローカル幾何変換を指定された量だけ、指定された順序で拡大縮小します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| sx | float | x 軸方向に変換を拡大縮小する量です。 |
| sy | float | y 軸方向に変換を拡大縮小する量です。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | スケーリング行列を付加するか前置するかを指定する [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) です。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に前置します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 軸における変換の値。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

ローカル幾何変換を指定された寸法だけ、指定された順序で平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 軸における変換の値。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 変換を適用する順序（前置または後置）。 |

