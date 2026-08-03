RAIL START EUROPE — GITHUB PAGES / PWA

ΠΕΡΙΕΧΟΜΕΝΑ
- index.html: κύρια εφαρμογή
- manifest.webmanifest: στοιχεία εγκατάστασης PWA
- sw.js: offline cache και ενημερώσεις
- offline.html: σελίδα χωρίς σύνδεση
- favicon.ico: favicon browser
- icons/: εικονίδια Android, iPhone και maskable

ΑΝΕΒΑΣΜΑ ΣΤΟ GITHUB
1. Δημιούργησε νέο repository ή άνοιξε το υπάρχον.
2. Ανέβασε ΟΛΑ τα αρχεία και τον φάκελο icons στη ρίζα του repository.
3. Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: main, Folder: /(root), Save.
6. Άνοιξε τη διεύθυνση GitHub Pages μέσω HTTPS.

ΕΓΚΑΤΑΣΤΑΣΗ
- Android/Chrome: μενού browser > Εγκατάσταση εφαρμογής ή το κουμπί στο πλαϊνό μενού.
- iPhone/Safari: Κοινή χρήση > Προσθήκη στην οθόνη αφετηρίας.

ΣΗΜΑΝΤΙΚΟ
Το service worker λειτουργεί μόνο σε HTTPS ή localhost. Μετά από νέα έκδοση, άλλαξε το CACHE_NAME στο sw.js για άμεση ανανέωση της cache.
