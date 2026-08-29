---
title: "Classe Graphics"
type: docs
weight: 1550
url: /fr/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | Initialise une nouvelle instance de la classe [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | Obtient ou définit la région de découpage. |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | Obtient ou définit la qualité de composition. |
| dpi_x | float | r | Obtient la résolution horizontale de cet Aspose.PSD.Graphics. |
| dpi_y | float | r | Obtient la résolution verticale de cet Aspose.PSD.Graphics. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Obtient l'image. |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | Obtient ou définit le mode d'interpolation. |
| is_in_begin_update_call | bool | r | Obtient une valeur indiquant si le graphique est dans l'état d'appel BeginUpdate. |
| page_scale | float | r/w | Obtient ou définit l'échelle entre les unités du monde et les unités de page pour cet Aspose.PSD.Graphics. |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | Obtient ou définit l'unité de mesure utilisée pour les coordonnées de page dans cet Aspose.PSD.Graphics. |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | Obtient ou définit les options d'image, utilisées pour créer des images vectorielles peintables à dessiner. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Obtient ou définit le mode d'anticrénelage. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Obtient ou définit l'indice de rendu du texte. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Obtient ou définit une copie de la transformation géométrique du monde pour ce [Graphics](/psd/python-net/aspose.psd/graphics/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| begin_update() | Commence la mise en cache des opérations graphiques suivantes. Les effets graphiques appliqués ensuite ne seront pas appliqués immédiatement ; au lieu de cela, l'End Update provoquera l'application de tous les effets en une fois. |
| [clear(color)](#clear_color_1) | Efface la surface graphique en utilisant la couleur spécifiée. |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur. |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | Dessine une spline de Bézier définie par quatre structures [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | Dessine une spline de Bézier définie par quatre structures [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points. |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/psd/python-net/aspose.psd/point/). |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/psd/python-net/aspose.psd/point/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | Dessine une spline cardinale fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | Dessine une spline cardinale fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | Dessine une spline cardinale fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage par défaut [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | Dessine une spline cardinale fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage par défaut [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0,5. |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0,5. |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/). Le dessin commence avec un décalage par rapport au début du tableau.<br/>            Cette méthode utilise une tension par défaut de 0,5. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. Le dessin commence avec un décalage par rapport au début du tableau. |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. Le dessin commence avec un décalage par rapport au début du tableau. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | Dessine une ellipse définie par un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) englobant. |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | Dessine une ellipse définie par un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) englobant. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié, en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié, en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié, en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié, en utilisant sa taille physique d'origine, à l'emplacement spécifié. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée. |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | Dessine l'image spécifiée en utilisant sa taille physique d'origine à l'emplacement spécifié par une paire de coordonnées. |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié. |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | Dessine l'image spécifiée sans mise à l'échelle et la découpe, si nécessaire, pour l'adapter au rectangle spécifié. |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | Dessine une ligne reliant deux structures [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | Dessine une ligne reliant deux structures [Point](/psd/python-net/aspose.psd/point/). |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées. |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | Dessine une série de segments de ligne qui relient un tableau de structures [Point](/psd/python-net/aspose.psd/point/). |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | Dessine une série de segments de ligne qui relient un tableau de structures [Point](/psd/python-net/aspose.psd/point/). |
| [draw_path(pen, path)](#draw_path_pen_path_61) | Dessine un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) et deux lignes radiales. |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) et deux lignes radiales. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | Dessine un polygone défini par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | Dessine un polygone défini par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | Dessine un rectangle spécifié par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | Dessine un rectangle spécifié par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | Dessine une série de rectangles spécifiés par des structures [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | Dessine une série de rectangles spécifiés par des structures [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés. |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés. |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés. |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/psd/python-net/aspose.psd/stringformat/). |
| end_update() | Termine la mise en cache des opérations graphiques démarrées après l'appel de BeginUpdate. Les opérations graphiques précédentes seront appliquées immédiatement lors de l'appel de cette méthode. |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0.5 et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0.5 et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0.5. |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0.5. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage et la tension spécifiés. |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage et la tension spécifiés. |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_path(brush, path)](#fill_path_brush_path_90) | Remplit l'intérieur d'un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) et deux lignes radiales. |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) et deux lignes radiales. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales. |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/psd/python-net/aspose.psd/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/psd/python-net/aspose.psd/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage spécifié. |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage spécifié. |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | Remplit l'intérieur d'un rectangle spécifié par une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | Remplit l'intérieur d'un rectangle spécifié par une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur. |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | Remplit les intérieurs d'une série de rectangles spécifiés par des structures [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | Remplit les intérieurs d'une série de rectangles spécifiés par des structures [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [fill_region(brush, region)](#fill_region_brush_region_105) | Remplit l'intérieur d'une [Region](/psd/python-net/aspose.psd/region/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | Multiplie la [Matrix](/psd/python-net/aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [Graphics](/psd/python-net/aspose.psd/graphics/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée en préfixant la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | Multiplie la [Matrix](/psd/python-net/aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [Graphics](/psd/python-net/aspose.psd/graphics/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée dans l'ordre spécifié. |
| reset_transform() | Réinitialise la propriété [Graphics.transform](/psd/python-net/aspose.psd/graphics/) à l'identité. |
| [rotate_transform(angle)](#rotate_transform_angle_108) | Fait pivoter la transformation géométrique locale du montant spécifié. Cette méthode préfixe la rotation à la transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | Fait pivoter la transformation géométrique locale du montant spécifié dans l'ordre spécifié. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | Met à l'échelle la transformation géométrique locale des valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | Met à l'échelle la transformation géométrique locale des valeurs spécifiées dans l'ordre spécifié. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | Translater la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | Translater la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié. |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

Initialise une nouvelle instance de la classe [Graphics](/psd/python-net/aspose.psd/graphics/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image source. |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

Efface la surface graphique en utilisant la couleur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | La couleur utilisée pour effacer la surface graphique. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure qui définit les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir de l'axe des x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du paramètre <paramref name="startAngle" /> jusqu'au point final de l'arc. |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure qui définit les limites de l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir de l'axe des x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du paramètre <paramref name="startAngle" /> jusqu'au point final de l'arc. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | float | Largeur du rectangle qui définit l'ellipse. |
| hauteur | float | Hauteur du rectangle qui définit l'ellipse. |
| start_angle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir de l'axe des x jusqu'au point de départ de l'arc. |
| sweep_angle | float | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du paramètre <paramref name="startAngle" /> jusqu'au point final de l'arc. |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine un arc représentant une partie d'une ellipse spécifiée par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de l'arc. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle qui définit l'ellipse. |
| width | int | Largeur du rectangle qui définit l'ellipse. |
| hauteur | int | Hauteur du rectangle qui définit l'ellipse. |
| start_angle | int | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir de l'axe des x jusqu'au point de départ de l'arc. |
| sweep_angle | int | Angle en degrés mesuré dans le sens des aiguilles d'une montre à partir du paramètre <paramref name="startAngle" /> jusqu'au point final de l'arc. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dessine une spline de Bézier définie par quatre structures [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure qui représente le point de départ de la courbe. |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure qui représente le premier point de contrôle de la courbe. |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) structure qui représente le point final de la courbe. |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

Dessine une spline de Bézier définie par quatre structures [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure qui représente le point de départ de la courbe. |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure qui représente le premier point de contrôle de la courbe. |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure qui représente le deuxième point de contrôle de la courbe. |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) structure qui représente le point final de la courbe. |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

Dessine une spline de Bézier définie par quatre paires ordonnées de coordonnées représentant des points.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| x1 | float | La coordonnée x du point de départ de la courbe. |
| y1 | float | La coordonnée y du point de départ de la courbe. |
| x2 | float | La coordonnée x du premier point de contrôle de la courbe. |
| y2 | float | La coordonnée y du premier point de contrôle de la courbe. |
| x3 | float | La coordonnée x du deuxième point de contrôle de la courbe. |
| y3 | float | La coordonnée y du deuxième point de contrôle de la courbe. |
| x4 | float | La coordonnée x du point final de la courbe. |
| y4 | float | La coordonnée y du point final de la courbe. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [Point](/psd/python-net/aspose.psd/point/) qui représentent les points qui déterminent la courbe. |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

Dessine une série de splines de Bézier à partir d'un tableau de structures [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la courbe. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [Point](/psd/python-net/aspose.psd/point/) qui représentent les points qui déterminent la courbe. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

Dessine une spline cardinale fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

Dessine une spline cardinale fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0,5 et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

Dessine une spline cardinale fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage par défaut [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

Dessine une spline cardinale fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. Cette méthode utilise le mode de remplissage par défaut [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/). Le dessin commence avec un décalage par rapport au début du tableau.<br/>            Cette méthode utilise une tension par défaut de 0,5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| offset | int | Décalage du premier élément du tableau du paramètre <paramref name="points" /> au point de départ de la courbe. |
| number_of_segments | int | Nombre de segments après le point de départ à inclure dans la courbe. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. Le dessin commence avec un décalage par rapport au début du tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| offset | int | Décalage du premier élément du tableau du paramètre <paramref name="points" /> au point de départ de la courbe. |
| number_of_segments | int | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée. Le dessin commence avec un décalage par rapport au début du tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| offset | int | Décalage du premier élément du tableau du paramètre <paramref name="points" /> au point de départ de la courbe. |
| number_of_segments | int | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représentent les points qui définissent la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

Dessine une spline cardinale à travers un tableau spécifié de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant une tension spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représentent les points qui définissent la courbe. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

Dessine une ellipse définie par un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure qui définit les limites de l'ellipse. |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

Dessine une ellipse définie par un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) englobant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure qui définit les limites de l'ellipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse. |
| hauteur | float | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

Dessine une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une hauteur et une largeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de l'ellipse. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse. |
| hauteur | int | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à dessiner. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de trois structures PointF qui définissent un parallélogramme. |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à dessiner. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de trois structures PointF qui définissent un parallélogramme. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à dessiner. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle source. |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à dessiner. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle source. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à dessiner. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle source. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Les unités de mesure. |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à dessiner. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle source. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Les unités de mesure. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à dessiner. |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle source. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Les unités de mesure. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Les attributs de l'image. |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

Dessine la portion spécifiée de l<paramref name="image" /> spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à dessiner. |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de trois structures PointF qui définissent un parallélogramme. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle source. |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Les unités de mesure. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Les attributs de l'image. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié, en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Structure [PointF](/psd/python-net/aspose.psd/pointf/) qui représente le coin supérieur gauche de l'image dessinée. |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié, en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| point | [Point](/psd/python-net/aspose.psd/point) | Structure [PointF](/psd/python-net/aspose.psd/pointf/) qui représente le coin supérieur gauche de l'image dessinée. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie l'emplacement et la taille de l'image dessinée. |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie l'emplacement et la taille de l'image dessinée. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unité graphique. |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unité graphique. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unité graphique. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Les attributs de l'image. |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unité graphique. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Les attributs de l'image. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle source. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unité graphique. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle source. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unité graphique. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle source. |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unité graphique. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Les attributs de l'image. |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle source. |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle de destination. |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | L'unité graphique. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Les attributs de l'image. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié, en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| x | float | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | float | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié, en utilisant sa taille physique d'origine, à l'emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| x | float | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | float | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| width | float | Largeur de l'image dessinée. |
| hauteur | float | Hauteur de l'image dessinée. |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

Dessine l[Graphics.image](/psd/python-net/aspose.psd/graphics/) spécifié à l'emplacement indiqué et avec la taille spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| width | int | Largeur de l'image dessinée. |
| hauteur | int | Hauteur de l'image dessinée. |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structure qui spécifie le coin supérieur gauche de l'image dessinée. |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui spécifie le coin supérieur gauche de l'image dessinée. Les propriétés X et Y du rectangle spécifient le coin supérieur gauche. Les propriétés Width et Height sont ignorées. |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

Dessine l'image spécifiée en utilisant sa taille physique d'origine à l'emplacement spécifié par une paire de coordonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

Dessine une image spécifiée en utilisant sa taille physique d'origine à un emplacement spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| x | int | La coordonnée x du coin supérieur gauche de l'image dessinée. |
| y | int | La coordonnée y du coin supérieur gauche de l'image dessinée. |
| width | int | Le paramètre n'est pas utilisé. |
| hauteur | int | Le paramètre n'est pas utilisé. |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

Dessine l'image spécifiée sans mise à l'échelle et la découpe, si nécessaire, pour l'adapter au rectangle spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | L'image avec laquelle dessiner. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le [Rectangle](/psd/python-net/aspose.psd/rectangle/) dans lequel dessiner l'image. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

Dessine une ligne reliant deux structures [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structure qui représente le premier point à connecter. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) structure qui représente le deuxième point à connecter. |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

Dessine une ligne reliant deux structures [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) structure qui représente le premier point à connecter. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) structure qui représente le deuxième point à connecter. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | int | La coordonnée x du premier point. |
| y1 | int | La coordonnée y du premier point. |
| x2 | int | La coordonnée x du deuxième point. |
| y2 | int | La coordonnée y du deuxième point. |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

Dessine une ligne reliant les deux points spécifiés par les paires de coordonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la ligne. |
| x1 | float | La coordonnée x du premier point. |
| y1 | float | La coordonnée y du premier point. |
| x2 | float | La coordonnée x du deuxième point. |
| y2 | float | La coordonnée y du deuxième point. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

Dessine une série de segments de ligne qui relient un tableau de structures [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [Point](/psd/python-net/aspose.psd/point/) qui représentent les points à connecter. |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

Dessine une série de segments de ligne qui relient un tableau de structures [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style des segments de ligne. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [Point](/psd/python-net/aspose.psd/point/) qui représentent les points à connecter. |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

Dessine un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style du chemin. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) à dessiner. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire depuis le paramètre <paramref name="startAngle" /> jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure qui représente le rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire depuis le paramètre <paramref name="startAngle" /> jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| hauteur | float | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | float | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | float | Angle mesuré en degrés dans le sens horaire depuis le paramètre <paramref name="startAngle" /> jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

Dessine une forme de secteur définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style de la forme de secteur. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| hauteur | int | Hauteur du rectangle englobant qui définit l'ellipse dont provient la forme de secteur. |
| start_angle | int | Angle mesuré en degrés dans le sens horaire depuis l'axe x jusqu'au premier côté de la forme de secteur. |
| sweep_angle | int | Angle mesuré en degrés dans le sens horaire depuis le paramètre <paramref name="startAngle" /> jusqu'au deuxième côté de la forme de secteur. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

Dessine un polygone défini par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style du polygone. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représentent les sommets du polygone. |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

Dessine un polygone défini par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style du polygone. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représentent les sommets du polygone. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

Dessine un rectangle spécifié par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle à dessiner. |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

Dessine un rectangle spécifié par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle à dessiner. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | float | La largeur du rectangle à dessiner. |
| hauteur | float | La hauteur du rectangle à dessiner. |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

Dessine un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Un [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style du rectangle. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à dessiner. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à dessiner. |
| width | int | La largeur du rectangle à dessiner. |
| hauteur | int | La hauteur du rectangle à dessiner. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

Dessine une série de rectangles spécifiés par des structures [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Tableau de structures [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représentent les rectangles à dessiner. |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

Dessine une série de rectangles spécifiés par des structures [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Tableau de structures [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représentent les rectangles à dessiner. |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | chaîne | Chaîne à dessiner. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine la couleur et la texture du texte dessiné. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie l'emplacement du texte dessiné. |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | chaîne | Chaîne à dessiner. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine la couleur et la texture du texte dessiné. |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui spécifie l'emplacement du texte dessiné. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) qui spécifie les attributs de mise en forme, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | chaîne | Chaîne à dessiner. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Structure [PointF](/psd/python-net/aspose.psd/pointf/) qui spécifie le coin supérieur gauche du texte dessiné. |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | chaîne | Chaîne à dessiner. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Structure [PointF](/psd/python-net/aspose.psd/pointf/) qui spécifie le coin supérieur gauche du texte dessiné. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) qui spécifie les attributs de mise en forme, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | chaîne | Chaîne à dessiner. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | float | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | float | La coordonnée y du coin supérieur gauche du texte dessiné. |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [Brush](/psd/python-net/aspose.psd/brush/) et [Font](/psd/python-net/aspose.psd/font/) spécifiés en utilisant les attributs de formatage du [StringFormat](/psd/python-net/aspose.psd/stringformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | chaîne | Chaîne à dessiner. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) qui définit le format du texte de la chaîne. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | float | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | float | La coordonnée y du coin supérieur gauche du texte dessiné. |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) qui spécifie les attributs de mise en forme, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0.5 et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/). Cette méthode utilise une tension par défaut de 0.5 et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0.5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membre de l'énumération [FillMode](/psd/python-net/aspose.psd/fillmode/) qui détermine comment la courbe est remplie. |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage spécifié. Cette méthode utilise une tension par défaut de 0.5.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membre de l'énumération [FillMode](/psd/python-net/aspose.psd/fillmode/) qui détermine comment la courbe est remplie. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage et la tension spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membre de l'énumération [FillMode](/psd/python-net/aspose.psd/fillmode/) qui détermine comment la courbe est remplie. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

Remplit l'intérieur d'une courbe spline cardinal fermée définie par un tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage et la tension spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui définissent la spline. |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membre de l'énumération [FillMode](/psd/python-net/aspose.psd/fillmode/) qui détermine comment la courbe est remplie. |
| tension | float | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) qui représente le rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse. |
| hauteur | float | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

Remplit l'intérieur d'une ellipse définie par un rectangle englobant spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse. |
| hauteur | int | Hauteur du rectangle englobant qui définit l'ellipse. |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

Remplit l'intérieur d'un [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui représente le chemin à remplir. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représente le rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre <paramref name=\"startAngle\" /> jusqu'au deuxième côté de la section de tarte. |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une structure [RectangleF](/psd/python-net/aspose.psd/rectanglef/) et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représente le rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre <paramref name=\"startAngle\" /> jusqu'au deuxième côté de la section de tarte. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| width | float | Largeur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| hauteur | float | Hauteur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| start_angle | float | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | float | Angle en degrés mesuré dans le sens horaire à partir du paramètre <paramref name=\"startAngle\" /> jusqu'au deuxième côté de la section de tarte. |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

Remplit l'intérieur d'une part de tarte définie par une ellipse spécifiée par une paire de coordonnées, une largeur, une hauteur et deux lignes radiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| width | int | Largeur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| hauteur | int | Hauteur du rectangle englobant qui définit l'ellipse dont provient la section de tarte. |
| start_angle | int | Angle en degrés mesuré dans le sens horaire à partir de l'axe x jusqu'au premier côté de la section de tarte. |
| sweep_angle | int | Angle en degrés mesuré dans le sens horaire à partir du paramètre <paramref name=\"startAngle\" /> jusqu'au deuxième côté de la section de tarte. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/psd/python-net/aspose.psd/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représentent les sommets du polygone à remplir. |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/psd/python-net/aspose.psd/pointf/) et le mode de remplissage [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représentent les sommets du polygone à remplir. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représentent les sommets du polygone à remplir. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membre de l'énumération [FillMode](/psd/python-net/aspose.psd/fillmode/) qui détermine le style du remplissage. |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

Remplit l'intérieur d'un polygone défini par un tableau de points spécifiés par des structures [PointF](/psd/python-net/aspose.psd/pointf/) en utilisant le mode de remplissage spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Tableau de structures [PointF](/psd/python-net/aspose.psd/pointf/) qui représentent les sommets du polygone à remplir. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | Membre de l'énumération [FillMode](/psd/python-net/aspose.psd/fillmode/) qui détermine le style du remplissage. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

Remplit l'intérieur d'un rectangle spécifié par une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représente le rectangle à remplir. |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

Remplit l'intérieur d'un rectangle spécifié par une structure [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Structure [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représente le rectangle à remplir. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| x | float | La coordonnée x du coin supérieur gauche du rectangle à remplir. |
| y | float | La coordonnée y du coin supérieur gauche du rectangle à remplir. |
| width | float | Largeur du rectangle à remplir. |
| hauteur | float | Hauteur du rectangle à remplir. |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

Remplit l'intérieur d'un rectangle spécifié par une paire de coordonnées, une largeur et une hauteur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| x | int | La coordonnée x du coin supérieur gauche du rectangle à remplir. |
| y | int | La coordonnée y du coin supérieur gauche du rectangle à remplir. |
| width | int | Largeur du rectangle à remplir. |
| hauteur | int | Hauteur du rectangle à remplir. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

Remplit les intérieurs d'une série de rectangles spécifiés par des structures [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | Tableau de structures [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représentent les rectangles à remplir. |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

Remplit les intérieurs d'une série de rectangles spécifiés par des structures [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | Tableau de structures [Rectangle](/psd/python-net/aspose.psd/rectangle/) qui représentent les rectangles à remplir. |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

Remplit l'intérieur d'une [Region](/psd/python-net/aspose.psd/region/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) qui détermine les caractéristiques du remplissage. |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) qui représente la zone à remplir. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

Multiplie la [Matrix](/psd/python-net/aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [Graphics](/psd/python-net/aspose.psd/graphics/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée en préfixant la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) par laquelle multiplier la transformation géométrique. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

Multiplie la [Matrix](/psd/python-net/aspose.psd/matrix/) qui représente la transformation géométrique locale de ce [Graphics](/psd/python-net/aspose.psd/graphics/) par la [Matrix](/psd/python-net/aspose.psd/matrix/) spécifiée dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) par laquelle multiplier la transformation géométrique. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) qui spécifie dans quel ordre multiplier les deux matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

Fait pivoter la transformation géométrique locale du montant spécifié. Cette méthode préfixe la rotation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

Fait pivoter la transformation géométrique locale du montant spécifié dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice de rotation. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

Met à l'échelle la transformation géométrique locale des valeurs spécifiées. Cette méthode préfixe la matrice d'échelle à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

Met à l'échelle la transformation géométrique locale des valeurs spécifiées dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sx | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe x. |
| sy | float | La quantité par laquelle mettre à l'échelle la transformation dans la direction de l'axe y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) qui spécifie s'il faut ajouter ou préfixer la matrice d'échelle. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

Translater la transformation géométrique locale des dimensions spécifiées. Cette méthode préfixe la translation à la transformation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la traduction en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

Translater la transformation géométrique locale des dimensions spécifiées dans l'ordre spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dx | float | La valeur de la translation en x. |
| dy | float | La valeur de la traduction en y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordre (préfixer ou ajouter) dans lequel appliquer la traduction. |

