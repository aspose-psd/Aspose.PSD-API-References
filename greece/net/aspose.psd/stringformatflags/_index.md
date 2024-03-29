---
title: Enum StringFormatFlags
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.StringFormatFlags αρίθμηση. Καθορίζει τις πληροφορίες εμφάνισης και διάταξης για συμβολοσειρές κειμένου.
type: docs
weight: 5680
url: /el/net/aspose.psd/stringformatflags/
---
## StringFormatFlags enumeration

Καθορίζει τις πληροφορίες εμφάνισης και διάταξης για συμβολοσειρές κειμένου.

```csharp
[Flags]
public enum StringFormatFlags
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Το κείμενο εμφανίζεται από δεξιά προς τα αριστερά. |
| DirectionVertical | `2` | Το κείμενο είναι κάθετα στοιχισμένο. |
| FitBlackBox | `4` | Επιτρέπεται σε μέρη χαρακτήρων να προεξέχουν από το ορθογώνιο διάταξης της συμβολοσειράς. Από προεπιλογή, οι χαρακτήρες επανατοποθετούνται για να αποφευχθεί τυχόν προεξοχή. |
| DisplayFormatControl | `20` | Οι χαρακτήρες ελέγχου, όπως το σημάδι από αριστερά προς τα δεξιά εμφανίζονται στην έξοδο με αντιπροσωπευτικό γλυφό. |
| NoFontFallback | `400` | Η εναλλακτική σε εναλλακτικές γραμματοσειρές για χαρακτήρες που δεν υποστηρίζονται στη γραμματοσειρά που ζητήθηκε είναι απενεργοποιημένη. Τυχόν χαρακτήρες που λείπουν εμφανίζονται με τις γραμματοσειρές που λείπουν γλυφά, συνήθως ένα ανοιχτό τετράγωνο. |
| MeasureTrailingSpaces | `800` | Περιλαμβάνει τον χώρο μετάδοσης στο τέλος κάθε γραμμής. Από προεπιλογή, το ορθογώνιο ορίου που επιστρέφεται από τη μέθοδο MeasureString εξαιρεί το διάστημα στο τέλος κάθε γραμμής. Ορίστε αυτήν τη σημαία ώστε να περιλαμβάνει αυτό το διάστημα στη μέτρηση. |
| NoWrap | `1000` | Η αναδίπλωση κειμένου μεταξύ γραμμών κατά τη μορφοποίηση σε ένα ορθογώνιο είναι απενεργοποιημένη. Αυτή η σημαία υπονοείται όταν περνά ένα σημείο αντί για ένα ορθογώνιο ή όταν το καθορισμένο ορθογώνιο έχει μηδενικό μήκος γραμμής. |
| LineLimit | `2000` | Μόνο ολόκληρες γραμμές διατάσσονται στο ορθογώνιο μορφοποίησης. Από προεπιλογή, η διάταξη συνεχίζεται μέχρι το τέλος του κειμένου ή έως ότου δεν είναι ορατές άλλες γραμμές ως αποτέλεσμα της αποκοπής, όποιο συμβεί πρώτο. Σημειώστε ότι οι προεπιλεγμένες ρυθμίσεις επιτρέπουν την μερική απόκρυψη της τελευταίας γραμμής από ένα ορθογώνιο μορφοποίησης που δεν είναι ολόκληρο πολλαπλάσιο του ύψους της γραμμής. Για να βεβαιωθείτε ότι εμφανίζονται μόνο ολόκληρες γραμμές, καθορίστε αυτήν την τιμή και προσέξτε να παρέχετε ένα ορθογώνιο μορφοποίησης ύψους τουλάχιστον όσο το ύψος μιας γραμμής. |
| NoClip | `4000` | Επιτρέπεται η εμφάνιση προεξέχοντων τμημάτων γλυφών και μη τυλιγμένου κειμένου που φτάνουν έξω από το ορθογώνιο μορφοποίησης. Από προεπιλογή, όλα τα μέρη κειμένου και γλυφών που φτάνουν έξω από το ορθογώνιο μορφοποίησης έχουν περικοπεί. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


