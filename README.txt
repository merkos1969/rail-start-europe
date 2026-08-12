RAIL START EUROPE — Beta 1.90

FIX: SVILENGRAD ↔ VARNA NO LONGER OPENS GENERIC BOX

Στην Beta 1.89 το Svilengrad → Varna δεν είχε date-specific ticket snapshot,
οπότε έπεφτε στο απλό generic πλαίσιο.

Στην Beta 1.90:
• Αν υπάρχει ticket snapshot της συγκεκριμένης ημερομηνίας → εμφανίζεται αυτό.
• Αν δεν υπάρχει snapshot αλλά υπάρχει επίσημο δημοσιευμένο BDZ timetable →
  εμφανίζεται λίστα τύπου bileti.bdz.bg.
• Αν δεν υπάρχει τίποτα από τα δύο → generic + live BDZ.

PUBLISHED BDZ FALLBACK

Svilengrad → Varna
• 06:05 → 12:32 · 6ω27 · ICF 1612
  Svilengrad → Dimitrovgrad → Stara Zagora → Varna
• 08:25 → 17:31 · 9ω06 · REG 10140
  Svilengrad → Dimitrovgrad → Stara Zagora → Karnobat → Varna
• 11:55 → 19:13 · 7ω18 · REG 10142
  Svilengrad → Parvomaj → Varna

Varna → Svilengrad
• 08:55 → 16:53 · 7ω58 · ICF 8650
• 16:55 → 00:05 · 7ω10 · ICF 8632
• 21:40 → 11:45 · 14ω05 · ICF 2626
• 23:45 → 07:56 · 8ω11 · ICF 8656

Σημείωση:
Αυτά είναι επίσημα δημοσιευμένα δρομολόγια BDZ, όχι ticket-system snapshot
για κάθε επιλεγμένη ημερομηνία. Η εφαρμογή το γράφει καθαρά και ζητά live
επιβεβαίωση πριν την αγορά.

Beta 1.90
