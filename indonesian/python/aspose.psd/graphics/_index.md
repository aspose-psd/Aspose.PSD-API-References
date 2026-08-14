---
title: "Kelas Graphics"
type: docs
weight: 1550
url: /id/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Menginisialisasi instance baru dari kelas [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Mendapatkan atau mengatur wilayah klip. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Mendapatkan atau mengatur kualitas komposit. |
| dpi_x | float | r | Mendapatkan resolusi horizontal dari Aspose.PSD.Graphics ini. |
| dpi_y | float | r | Mendapatkan resolusi vertikal dari Aspose.PSD.Graphics ini. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Mendapatkan gambar. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Mendapatkan atau mengatur mode interpolasi. |
| is_in_begin_update_call | bool | r | Mendapatkan nilai yang menunjukkan apakah graphics berada dalam keadaan pemanggilan BeginUpdate. |
| page_scale | float | r/w | Mendapatkan atau mengatur skala antara satuan dunia dan satuan halaman untuk Aspose.PSD.Graphics ini. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Mendapatkan atau mengatur satuan ukuran yang digunakan untuk koordinat halaman dalam Aspose.PSD.Graphics ini. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Mendapatkan atau mengatur opsi gambar, yang digunakan untuk membuat gambar vektor yang dapat digambar. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Mendapatkan atau mengatur mode penghalusan. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Mendapatkan atau mengatur petunjuk rendering teks. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Mendapatkan atau mengatur salinan transformasi dunia geometris untuk [Graphics](/psd/python-net/aspose.psd/graphics/) ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| begin_update() | Memulai caching operasi grafik berikut. Efek grafik yang diterapkan setelahnya tidak akan diterapkan secara langsung; sebaliknya EndUpdate akan menyebabkan penerapan semua efek sekaligus. |
| [clear(color)](#clear_color_1) | Membersihkan permukaan grafik menggunakan warna yang ditentukan. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Menggambar spline Bézier yang didefinisikan oleh empat struktur [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Menggambar spline Bézier yang didefinisikan oleh empat struktur [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Menggambar spline Bézier yang didefinisikan oleh empat pasang terurut koordinat yang mewakili titik. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Menggambar serangkaian spline Bézier dari array struktur [Point](/psd/python-net/aspose.psd/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Menggambar serangkaian spline Bézier dari array struktur [Point](/psd/python-net/aspose.psd/point/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) . Metode ini menggunakan ketegangan default 0,5 dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) . |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) . Metode ini menggunakan ketegangan default 0,5 dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) . |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan ketegangan yang ditentukan. Metode ini menggunakan mode isi default [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) . |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan ketegangan yang ditentukan. Metode ini menggunakan mode isi default [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) . |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan. Metode ini menggunakan ketegangan default 0,5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan. Metode ini menggunakan ketegangan default 0,5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan. Gambar dimulai dengan offset dari awal array.<br/>            Metode ini menggunakan ketegangan default 0,5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menggunakan ketegangan yang ditentukan. Gambar dimulai dengan offset dari awal array. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menggunakan ketegangan yang ditentukan. Gambar dimulai dengan offset dari awal array. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menggunakan ketegangan yang ditentukan. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menggunakan ketegangan yang ditentukan. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Menggambar elips yang didefinisikan oleh [RectangleF](/psd/python-net/aspose.psd/rectanglef/) pembatas. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Menggambar elips yang didefinisikan oleh [RectangleF](/psd/python-net/aspose.psd/rectanglef/) pembatas. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Menggambar elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Menggambar elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan oleh sepasang koordinat. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Menggambar gambar yang ditentukan tanpa skala dan memotongnya, jika diperlukan, agar sesuai dengan persegi panjang yang ditentukan. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Menggambar garis yang menghubungkan dua struktur [Point](/psd/python-net/aspose.psd/point/) . |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Menggambar garis yang menghubungkan dua struktur [Point](/psd/python-net/aspose.psd/point/) . |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Menggambar serangkaian segmen garis yang menghubungkan array struktur [Point](/psd/python-net/aspose.psd/point/) . |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Menggambar serangkaian segmen garis yang menghubungkan array struktur [Point](/psd/python-net/aspose.psd/point/) . |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Menggambar [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) , dan dua garis radial. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) , dan dua garis radial. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Menggambar poligon yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) . |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Menggambar poligon yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) . |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Menggambar persegi panjang yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) . |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Menggambar persegi panjang yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) . |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Menggambar persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Menggambar persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Menggambar serangkaian persegi panjang yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) . |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Menggambar serangkaian persegi panjang yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) . |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) yang ditentukan. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) menggunakan atribut pemformatan dari [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) . |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) menggunakan atribut pemformatan dari [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) . |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) menggunakan atribut pemformatan dari [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | Menyelesaikan penyimpanan cache operasi grafik yang dimulai setelah BeginUpdate dipanggil. Operasi grafik sebelumnya akan diterapkan sekaligus saat memanggil metode ini. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/). Metode ini menggunakan ketegangan default 0.5 dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/). Metode ini menggunakan ketegangan default 0.5 dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi yang ditentukan. Metode ini menggunakan ketegangan default 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi yang ditentukan. Metode ini menggunakan ketegangan default 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi dan ketegangan yang ditentukan. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi dan ketegangan yang ditentukan. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Mengisi interior elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Mengisi interior elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Mengisi interior elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Mengisi interior elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Mengisi interior [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Mengisi interior bagian pai yang didefinisikan oleh elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dan dua garis radial. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Mengisi interior bagian pai yang didefinisikan oleh elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dan dua garis radial. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Mengisi interior bagian pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Mengisi interior bagian pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Mengisi interior poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [PointF](/psd/python-net/aspose.psd/pointf/) dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Mengisi interior poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [PointF](/psd/python-net/aspose.psd/pointf/) dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Mengisi interior poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi yang ditentukan. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Mengisi interior poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi yang ditentukan. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Mengisi interior persegi panjang yang ditentukan oleh struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Mengisi interior persegi panjang yang ditentukan oleh struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Mengisi interior persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Mengisi interior persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Mengisi interior serangkaian persegi panjang yang ditentukan oleh struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Mengisi interior serangkaian persegi panjang yang ditentukan oleh struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Mengisi interior [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [Graphics](/psd/python-net/aspose.psd/graphics/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dengan menambahkan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan di depan. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [Graphics](/psd/python-net/aspose.psd/graphics/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dalam urutan yang ditentukan. |
| reset_transform() | Mengatur ulang properti [Graphics.transform](/psd/python-net/aspose.psd/graphics/) ke identitas. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan dalam urutan yang ditentukan. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Menginisialisasi instance baru dari kelas [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar sumber. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Membersihkan permukaan grafik menggunakan warna yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Warna untuk membersihkan permukaan grafik. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya busur. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur yang mendefinisikan batas-batas elips. |
| start_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke titik awal busur. |
| sweep_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter <paramref name="startAngle" /> ke titik akhir busur. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya busur. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur yang mendefinisikan batas-batas elips. |
| start_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke titik awal busur. |
| sweep_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter <paramref name="startAngle" /> ke titik akhir busur. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya busur. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang mendefinisikan elips. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang mendefinisikan elips. |
| width | float | Lebar persegi panjang yang mendefinisikan elips. |
| tinggi | float | Tinggi persegi panjang yang mendefinisikan elips. |
| start_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke titik awal busur. |
| sweep_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter <paramref name="startAngle" /> ke titik akhir busur. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya busur. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang mendefinisikan elips. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang mendefinisikan elips. |
| width | int | Lebar persegi panjang yang mendefinisikan elips. |
| tinggi | int | Tinggi persegi panjang yang mendefinisikan elips. |
| start_angle | int | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke titik awal busur. |
| sweep_angle | int | Sudut dalam derajat yang diukur searah jarum jam dari parameter <paramref name="startAngle" /> ke titik akhir busur. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Menggambar spline Bézier yang didefinisikan oleh empat struktur [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya kurva. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur yang merepresentasikan titik awal kurva. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur yang merepresentasikan titik kontrol pertama untuk kurva. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur yang merepresentasikan titik kontrol kedua untuk kurva. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur yang merepresentasikan titik akhir kurva. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Menggambar spline Bézier yang didefinisikan oleh empat struktur [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya kurva. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur yang merepresentasikan titik awal kurva. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur yang merepresentasikan titik kontrol pertama untuk kurva. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur yang merepresentasikan titik kontrol kedua untuk kurva. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) struktur yang merepresentasikan titik akhir kurva. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Menggambar spline Bézier yang didefinisikan oleh empat pasang terurut koordinat yang mewakili titik.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya kurva. |
| x1 | float | Koordinat x dari titik awal kurva. |
| y1 | float | Koordinat y dari titik awal kurva. |
| x2 | float | Koordinat x dari titik kontrol pertama kurva. |
| y2 | float | Koordinat y dari titik kontrol pertama kurva. |
| x3 | float | Koordinat x dari titik kontrol kedua kurva. |
| y3 | float | Koordinat y dari titik kontrol kedua kurva. |
| x4 | float | Koordinat x dari titik akhir kurva. |
| y4 | float | Koordinat y dari titik akhir kurva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Menggambar serangkaian spline Bézier dari array struktur [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya kurva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [Point](/psd/python-net/aspose.psd/point/) yang mewakili titik-titik yang menentukan kurva. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Menggambar serangkaian spline Bézier dari array struktur [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya kurva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [Point](/psd/python-net/aspose.psd/point/) yang mewakili titik-titik yang menentukan kurva. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) . Metode ini menggunakan ketegangan default 0,5 dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) . Metode ini menggunakan ketegangan default 0,5 dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan ketegangan yang ditentukan. Metode ini menggunakan mode isi default [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| tegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan ketegangan yang ditentukan. Metode ini menggunakan mode isi default [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| tegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan. Metode ini menggunakan ketegangan default 0,5.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan. Metode ini menggunakan ketegangan default 0,5.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan. Gambar dimulai dengan offset dari awal array.<br/>            Metode ini menggunakan ketegangan default 0,5.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| offset | int | Offset dari elemen pertama dalam array parameter <paramref name="points" /> ke titik awal pada kurva. |
| number_of_segments | int | Jumlah segmen setelah titik awal yang termasuk dalam kurva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menggunakan ketegangan yang ditentukan. Gambar dimulai dengan offset dari awal array.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| offset | int | Offset dari elemen pertama dalam array parameter <paramref name="points" /> ke titik awal pada kurva. |
| number_of_segments | int | Jumlah segmen setelah titik awal yang termasuk dalam kurva. |
| tegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menggunakan ketegangan yang ditentukan. Gambar dimulai dengan offset dari awal array.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| offset | int | Offset dari elemen pertama dalam array parameter <paramref name="points" /> ke titik awal pada kurva. |
| number_of_segments | int | Jumlah segmen setelah titik awal yang termasuk dalam kurva. |
| tegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menggunakan ketegangan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik yang mendefinisikan kurva. |
| tegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Menggambar spline kardinal melalui array [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan menggunakan ketegangan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik yang mendefinisikan kurva. |
| tegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Menggambar elips yang didefinisikan oleh [RectangleF](/psd/python-net/aspose.psd/rectanglef/) pembatas.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya elips. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur yang mendefinisikan batas-batas elips. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Menggambar elips yang didefinisikan oleh [RectangleF](/psd/python-net/aspose.psd/rectanglef/) pembatas.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya elips. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur yang mendefinisikan batas-batas elips. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Menggambar elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya elips. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| width | float | Lebar persegi panjang pembatas yang mendefinisikan elips. |
| tinggi | float | Tinggi persegi panjang pembatas yang mendefinisikan elips. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Menggambar elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya elips. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| width | int | Lebar persegi panjang pembatas yang mendefinisikan elips. |
| tinggi | int | Tinggi persegi panjang pembatas yang mendefinisikan elips. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari tiga struktur PointF yang mendefinisikan sebuah paralelogram. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari tiga struktur PointF yang mendefinisikan sebuah paralelogram. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang sumber. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang sumber. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang sumber. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Satuan ukuran. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang sumber. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Satuan ukuran. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang sumber. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Satuan ukuran. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Atribut gambar. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Menggambar bagian yang ditentukan dari <paramref name="image" /> yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang sumber. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Satuan ukuran. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Atribut gambar. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili sudut kiri atas gambar yang digambar. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| point | [Point](/psd/python-net/aspose.psd/point) | Struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili sudut kiri atas gambar yang digambar. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang menentukan lokasi dan ukuran gambar yang digambar. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang menentukan lokasi dan ukuran gambar yang digambar. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang tujuan. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Unit grafis. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang tujuan. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Unit grafis. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang tujuan. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Unit grafis. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Atribut gambar. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang tujuan. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Unit grafis. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Atribut gambar. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sumber rect. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Tujuan rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Unit grafis. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sumber rect. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Tujuan rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Unit grafis. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sumber rect. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Tujuan rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Unit grafis. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Atribut gambar. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sumber rect. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Tujuan rect. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Unit grafis. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Atribut gambar. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | float | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | float | Koordinat y dari sudut kiri atas gambar yang digambar. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | int | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | int | Koordinat y dari sudut kiri atas gambar yang digambar. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | float | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | float | Koordinat y dari sudut kiri atas gambar yang digambar. |
| width | float | Lebar gambar yang digambar. |
| tinggi | float | Tinggi gambar yang digambar. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Menggambar [Graphics.image](/psd/python-net/aspose.psd/graphics/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | int | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | int | Koordinat y dari sudut kiri atas gambar yang digambar. |
| width | int | Lebar gambar yang digambar. |
| tinggi | int | Tinggi gambar yang digambar. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struktur yang menentukan sudut kiri atas gambar yang digambar. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang menentukan sudut kiri atas gambar yang digambar. Properti X dan Y dari rectangle menentukan sudut kiri atas. Properti Width dan Height diabaikan. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan oleh sepasang koordinat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | int | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | int | Koordinat y dari sudut kiri atas gambar yang digambar. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | int | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | int | Koordinat y dari sudut kiri atas gambar yang digambar. |
| width | int | Parameter tidak digunakan. |
| tinggi | int | Parameter tidak digunakan. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Menggambar gambar yang ditentukan tanpa skala dan memotongnya, jika diperlukan, agar sesuai dengan persegi panjang yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang digunakan untuk menggambar gambar. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Menggambar garis yang menghubungkan dua struktur [Point](/psd/python-net/aspose.psd/point/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya garis. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struktur yang mewakili titik pertama yang akan dihubungkan. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) struktur yang mewakili titik kedua yang akan dihubungkan. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Menggambar garis yang menghubungkan dua struktur [Point](/psd/python-net/aspose.psd/point/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya garis. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) struktur yang mewakili titik pertama yang akan dihubungkan. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) struktur yang mewakili titik kedua yang akan dihubungkan. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya garis. |
| x1 | int | Koordinat x dari titik pertama. |
| y1 | int | Koordinat y dari titik pertama. |
| x2 | int | Koordinat x dari titik kedua. |
| y2 | int | Koordinat y dari titik kedua. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya garis. |
| x1 | float | Koordinat x dari titik pertama. |
| y1 | float | Koordinat y dari titik pertama. |
| x2 | float | Koordinat x dari titik kedua. |
| y2 | float | Koordinat y dari titik kedua. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Menggambar serangkaian segmen garis yang menghubungkan array struktur [Point](/psd/python-net/aspose.psd/point/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya segmen garis. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [Point](/psd/python-net/aspose.psd/point/) yang mewakili titik-titik yang akan dihubungkan. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Menggambar serangkaian segmen garis yang menghubungkan array struktur [Point](/psd/python-net/aspose.psd/point/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya segmen garis. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [Point](/psd/python-net/aspose.psd/point/) yang mewakili titik-titik yang akan dihubungkan. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Menggambar [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya jalur. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) untuk digambar. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) , dan dua garis radial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya bentuk pai. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur yang mewakili persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| start_angle | float | Sudut yang diukur dalam derajat searah jarum jam dari sumbu x ke sisi pertama bentuk pai. |
| sweep_angle | float | Sudut diukur dalam derajat searah jarum jam dari parameter <paramref name="startAngle" /> ke sisi kedua bentuk pai. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) , dan dua garis radial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya bentuk pai. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur yang mewakili persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| start_angle | float | Sudut yang diukur dalam derajat searah jarum jam dari sumbu x ke sisi pertama bentuk pai. |
| sweep_angle | float | Sudut diukur dalam derajat searah jarum jam dari parameter <paramref name="startAngle" /> ke sisi kedua bentuk pai. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya bentuk pai. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| width | float | Lebar persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| tinggi | float | Tinggi persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| start_angle | float | Sudut yang diukur dalam derajat searah jarum jam dari sumbu x ke sisi pertama bentuk pai. |
| sweep_angle | float | Sudut diukur dalam derajat searah jarum jam dari parameter <paramref name="startAngle" /> ke sisi kedua bentuk pai. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya bentuk pai. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| width | int | Lebar persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| tinggi | int | Tinggi persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| start_angle | int | Sudut yang diukur dalam derajat searah jarum jam dari sumbu x ke sisi pertama bentuk pai. |
| sweep_angle | int | Sudut diukur dalam derajat searah jarum jam dari parameter <paramref name="startAngle" /> ke sisi kedua bentuk pai. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Menggambar poligon yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya poligon. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik‑titik sudut poligon. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Menggambar poligon yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya poligon. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik‑titik sudut poligon. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Menggambar persegi panjang yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Sebuah [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya persegi panjang. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang akan digambar. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Menggambar persegi panjang yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Sebuah [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya persegi panjang. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang akan digambar. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Menggambar persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Sebuah [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya persegi panjang. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang akan digambar. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang akan digambar. |
| width | float | Lebar persegi panjang yang akan digambar. |
| tinggi | float | Tinggi persegi panjang yang akan digambar. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Menggambar persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Sebuah [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya persegi panjang. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang akan digambar. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang akan digambar. |
| width | int | Lebar persegi panjang yang akan digambar. |
| tinggi | int | Tinggi persegi panjang yang akan digambar. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Menggambar serangkaian persegi panjang yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya garis tepi persegi panjang. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang akan digambar. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Menggambar serangkaian persegi panjang yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) yang menentukan warna, lebar, dan gaya garis tepi persegi panjang. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang akan digambar. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| s | string | String yang akan digambar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) yang mendefinisikan format teks dari string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan warna dan tekstur teks yang digambar. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang menentukan lokasi teks yang digambar. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) menggunakan atribut pemformatan dari [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| s | string | String yang akan digambar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) yang mendefinisikan format teks dari string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan warna dan tekstur teks yang digambar. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang menentukan lokasi teks yang digambar. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| s | string | String yang akan digambar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) yang mendefinisikan format teks dari string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan warna dan tekstur teks yang digambar. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang menentukan sudut kiri atas teks yang digambar. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) menggunakan atribut pemformatan dari [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| s | string | String yang akan digambar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) yang mendefinisikan format teks dari string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan warna dan tekstur teks yang digambar. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang menentukan sudut kiri atas teks yang digambar. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| s | string | String yang akan digambar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) yang mendefinisikan format teks dari string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan warna dan tekstur teks yang digambar. |
| x | float | Koordinat x dari sudut kiri atas teks yang digambar. |
| y | float | Koordinat y dari sudut kiri atas teks yang digambar. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [Brush](/psd/python-net/aspose.psd/brush/) dan [Font](/psd/python-net/aspose.psd/font/) menggunakan atribut pemformatan dari [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| s | string | String yang akan digambar. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) yang mendefinisikan format teks dari string. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan warna dan tekstur teks yang digambar. |
| x | float | Koordinat x dari sudut kiri atas teks yang digambar. |
| y | float | Koordinat y dari sudut kiri atas teks yang digambar. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/). Metode ini menggunakan ketegangan default 0.5 dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/). Metode ini menggunakan ketegangan default 0.5 dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi yang ditentukan. Metode ini menggunakan ketegangan default 0.5.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Anggota enumerasi [FillMode](/psd/python-net/aspose.psd/fillmode/) yang menentukan bagaimana kurva diisi. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi yang ditentukan. Metode ini menggunakan ketegangan default 0.5.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Anggota enumerasi [FillMode](/psd/python-net/aspose.psd/fillmode/) yang menentukan bagaimana kurva diisi. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi dan ketegangan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Sebuah [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik pengisian. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Anggota enumerasi [FillMode](/psd/python-net/aspose.psd/fillmode/) yang menentukan bagaimana kurva diisi. |
| tegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi dan ketegangan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Sebuah [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik pengisian. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array dari struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mendefinisikan spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Anggota enumerasi [FillMode](/psd/python-net/aspose.psd/fillmode/) yang menentukan bagaimana kurva diisi. |
| tegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Mengisi interior elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang pembatas yang mendefinisikan elips. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Mengisi interior elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang pembatas yang mendefinisikan elips. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Mengisi interior elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| width | float | Lebar persegi panjang pembatas yang mendefinisikan elips. |
| tinggi | float | Tinggi persegi panjang pembatas yang mendefinisikan elips. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Mengisi interior elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| width | int | Lebar persegi panjang pembatas yang mendefinisikan elips. |
| tinggi | int | Tinggi persegi panjang pembatas yang mendefinisikan elips. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Mengisi interior [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mewakili jalur untuk diisi. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Mengisi interior bagian pai yang didefinisikan oleh elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dan dua garis radial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang mewakili persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| start_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke sisi pertama bagian pai. |
| sweep_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter <paramref name="startAngle" /> ke sisi kedua bagian pai. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Mengisi interior bagian pai yang didefinisikan oleh elips yang ditentukan oleh struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dan dua garis radial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang mewakili persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| start_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke sisi pertama bagian pai. |
| sweep_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter <paramref name="startAngle" /> ke sisi kedua bagian pai. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Mengisi interior bagian pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| width | float | Lebar persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| tinggi | float | Tinggi persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| start_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke sisi pertama bagian pai. |
| sweep_angle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter <paramref name="startAngle" /> ke sisi kedua bagian pai. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Mengisi interior bagian pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| width | int | Lebar persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| tinggi | int | Tinggi persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| start_angle | int | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke sisi pertama bagian pai. |
| sweep_angle | int | Sudut dalam derajat yang diukur searah jarum jam dari parameter <paramref name="startAngle" /> ke sisi kedua bagian pai. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Mengisi interior poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [PointF](/psd/python-net/aspose.psd/pointf/) dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik sudut poligon untuk diisi. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Mengisi interior poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [PointF](/psd/python-net/aspose.psd/pointf/) dan mode isi [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik sudut poligon untuk diisi. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Mengisi interior poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik sudut poligon untuk diisi. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Anggota enumerasi [FillMode](/psd/python-net/aspose.psd/fillmode/) yang menentukan gaya pengisian. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Mengisi interior poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [PointF](/psd/python-net/aspose.psd/pointf/) menggunakan mode isi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Array struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik sudut poligon untuk diisi. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Anggota enumerasi [FillMode](/psd/python-net/aspose.psd/fillmode/) yang menentukan gaya pengisian. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Mengisi interior persegi panjang yang ditentukan oleh struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang mewakili persegi panjang yang akan diisi. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Mengisi interior persegi panjang yang ditentukan oleh struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang mewakili persegi panjang yang akan diisi. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Mengisi interior persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang akan diisi. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang akan diisi. |
| width | float | Lebar persegi panjang yang akan diisi. |
| tinggi | float | Tinggi persegi panjang yang akan diisi. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Mengisi interior persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang akan diisi. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang akan diisi. |
| width | int | Lebar persegi panjang yang akan diisi. |
| tinggi | int | Tinggi persegi panjang yang akan diisi. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Mengisi interior serangkaian persegi panjang yang ditentukan oleh struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Array struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang mewakili persegi panjang-panjang yang akan diisi. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Mengisi interior serangkaian persegi panjang yang ditentukan oleh struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Array struktur [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang mewakili persegi panjang-panjang yang akan diisi. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Mengisi interior [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) yang menentukan karakteristik isian. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) yang mewakili area yang akan diisi. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [Graphics](/psd/python-net/aspose.psd/graphics/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dengan menambahkan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan di depan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mengalikan transformasi geometrik. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [Graphics](/psd/python-net/aspose.psd/graphics/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mengalikan transformasi geometrik. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan urutan pengalian kedua matriks. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan apakah akan menambahkan atau menyisipkan matriks rotasi. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu x. |
| sy | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu x. |
| sy | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan apakah akan menambahkan atau menyisipkan matriks skala. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan (menambahkan di depan atau di belakang) untuk menerapkan translasi. |

