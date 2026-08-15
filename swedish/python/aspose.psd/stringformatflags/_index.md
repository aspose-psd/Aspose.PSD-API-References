---
title: "StringFormatFlags‑enumeration"
type: docs
weight: 6300
url: /sv/python-net/aspose.psd/stringformatflags/
---

Anger visnings- och layoutinformation för textsträngar.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormatFlags

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Medlemsnamn** | **Beskrivning** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Text visas från höger till vänster. |
| DIRECTION_VERTICAL | Text är vertikalt justerad. |
| DISPLAY_FORMAT_CONTROL | Kontrolltecken, såsom vänster‑till‑höger‑markören, visas i utdata med en representativ glyf. |
| EXACT_ALIGNMENT | Den exakta justeringen, korrekt utfyllnad GDI+ |
| FIT_BLACK_BOX | Delar av tecken får överskjuta strängens layout‑rektangel. Som standard omplaceras tecken för att undvika någon överskjutning. |
| LINE_LIMIT | Endast hela rader läggs ut i formateringsrektangeln. Som standard fortsätter layouten tills slutet av texten, eller tills inga fler rader är synliga på grund av beskärning, vad som än inträffar först.<br/>            Observera att standardinställningarna tillåter den sista raden att delvis döljas av en formateringsrektangel som inte är ett helt multipel av radens höjd. För att säkerställa att endast hela rader syns,<br/>            ange detta värde och var noga med att tillhandahålla en formateringsrektangel som är minst lika hög som höjden på en rad. |
| MEASURE_TRAILING_SPACES | Inkluderar efterföljande blanksteg i slutet av varje rad. Som standard exkluderar den avgränsningsrektangel som returneras av MeasureString‑metoden blanksteget i slutet av varje rad. Ställ in detta flagg för att inkludera det blanksteget i mätningen. |
| NO_CLIP | Överhängande delar av glyfer och oinsvept text som når utanför formateringsrektangeln får visas. Som standard klipps all text och glyfdelar som når utanför formateringsrektangeln. |
| NO_FONT_FALLBACK | Reserv till alternativa typsnitt för tecken som inte stöds i det begärda typsnittet är inaktiverat. Eventuella saknade tecken visas med typsnittets saknade glyf, vanligtvis en öppen ruta. |
| NO_WRAP | Textbrytning mellan rader vid formatering inom en rektangel är inaktiverad. Denna flagga antas när en punkt skickas istället för en rektangel, eller när den angivna rektangeln har en noll linjelängd. |
