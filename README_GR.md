# Ordinox Desk Lite

[English](README.md) · [Ελληνικά](README_GR.md)

**Local-first εφαρμογή Windows για διαχείριση πελατών και επιχειρησιακών πληροφοριών, με έμφαση σε οπτικά καταστήματα.**

Το Ordinox Desk Lite είναι desktop εφαρμογή σχεδιασμένη για οπτικά καταστήματα και μικρές επιχειρήσεις οπτικών που χρειάζονται έναν πρακτικό τρόπο να διαχειρίζονται πελάτες, οπτικές συνταγές, ιστορικό επισκέψεων, υπηρεσίες, έσοδα και τοπικά επαγγελματικά δεδομένα από ένα ενιαίο περιβάλλον.

Το project αναπτύχθηκε ως εστιασμένο desktop business tool με έμφαση στην απλότητα, τη γρήγορη πρόσβαση σε πληροφορίες πελατών και την αξιόπιστη τοπική λειτουργία χωρίς ανάγκη για remote backend.

Η εφαρμογή είναι σχεδιασμένη για **Windows PCs και Windows tablets** και μπορεί να διατίθεται με **Αγγλικό και Ελληνικό περιβάλλον**.

---

## Tech Stack

- **Tauri 2** — desktop application framework και Windows packaging
- **Rust** — native Tauri application layer
- **Vanilla JavaScript** — application logic και state management
- **HTML5** — δομή εφαρμογής
- **CSS3** — custom user interface
- **WebView localStorage** — τοπική αποθήκευση δεδομένων
- **JSON** — backup και data import/export
- **CSV / spreadsheet-compatible exports**
- **Windows desktop packaging** — standalone εφαρμογή και installer

Το Ordinox Desk Lite είναι σχεδιασμένο ως **local-first application**.

Η βασική business logic υλοποιείται σε JavaScript, ενώ το Tauri παρέχει το native Windows desktop environment και το packaging layer.

Για την κανονική λειτουργία δεν απαιτείται remote backend ή external database server.

---

## Παρουσίαση εφαρμογής

### Διαχείριση Πελατών

![Ordinox Desk Lite Clients](assets/screenshots/clients.png)

Η εφαρμογή περιλαμβάνει οργανωμένη ροή πελατολογίου με:

- Δημιουργία νέου πελάτη
- Επεξεργασία πελάτη
- Αναζήτηση
- Οργανωμένη λίστα
- Γρήγορη πρόσβαση σε αρχεία πελατών
- Σχετικές πληροφορίες πελάτη
- Ιστορικό επισκέψεων και υπηρεσιών

---

### Διαχείριση Οπτικής Συνταγής

![Ordinox Desk Lite Client Prescription](assets/screenshots/client-prescription.png)

Κάθε πελάτης μπορεί να έχει αποθηκευμένες πληροφορίες οπτικής συνταγής μέσα στο αρχείο του.

Η εφαρμογή υποστηρίζει δομημένα δεδομένα όπως:

- SPH
- CYL
- AXE
- PD
- ADD
- Ημερομηνίες συνταγών
- Πληροφορίες σχετικές με γυαλιά
- Πληροφορίες σχετικές με φακούς επαφής

Στόχος είναι οι σημαντικές οπτικές πληροφορίες να βρίσκονται μαζί με τα γενικά στοιχεία και το ιστορικό του πελάτη.

---

### Ιστορικό Επισκέψεων

![Ordinox Desk Lite Visit History](assets/screenshots/visit-history.png)

Η δραστηριότητα του πελάτη οργανώνεται μέσω ξεχωριστού ιστορικού επισκέψεων.

Έτσι ο χρήστης μπορεί να ανατρέχει σε προηγούμενα ραντεβού, υπηρεσίες και σημειώσεις χωρίς να βασίζεται σε εξωτερικά spreadsheets ή ξεχωριστά έγγραφα.

---

### Διαχείριση Εσόδων

![Ordinox Desk Lite Revenue](assets/screenshots/revenue.png)

Το Ordinox Desk Lite περιλαμβάνει εργαλεία παρακολούθησης και επισκόπησης πληροφοριών σχετικών με τα έσοδα.

Η εφαρμογή μπορεί να οργανώνει οικονομικά στοιχεία που συνδέονται με υπηρεσίες και δραστηριότητα πελατών και να παρέχει export λειτουργίες για περαιτέρω χρήση ή reporting.

---

### Υπηρεσίες

![Ordinox Desk Lite Services](assets/screenshots/services.png)

Η εφαρμογή περιλαμβάνει διαχείριση υπηρεσιών ώστε οι συχνά χρησιμοποιούμενες υπηρεσίες να οργανώνονται και να επαναχρησιμοποιούνται μέσα στη ροή πελατών.

Αυτό μειώνει την επαναλαμβανόμενη καταχώριση και βοηθά στη συνέπεια των πληροφοριών.

---

### Backup & Import

![Ordinox Desk Lite Backup and Import](assets/screenshots/backup-import.png)

Η φορητότητα και η ανάκτηση δεδομένων είναι ενσωματωμένες στην εφαρμογή.

Περιλαμβάνονται:

- Local data backup
- JSON export
- Data import
- Backup restoration
- Validation εισαγόμενων δεδομένων
- Recovery αποθηκευμένων πληροφοριών

Έτσι ο χρήστης μπορεί να διατηρεί αντίγραφα των δεδομένων του ανεξάρτητα από την εγκατάσταση της εφαρμογής.

---

## Ροή εργασίας οπτικής επιχείρησης

Το Ordinox Desk Lite σχεδιάστηκε γύρω από μια πρακτική ροή εργασίας οπτικού καταστήματος.

Ένα τυπικό workflow μπορεί να περιλαμβάνει:

1. Δημιουργία ή εντοπισμό πελάτη
2. Έλεγχο υπαρχόντων στοιχείων
3. Καταχώριση οπτικής συνταγής
4. Προσθήκη νέας επίσκεψης ή υπηρεσίας
5. Έλεγχο προηγούμενου ιστορικού
6. Παρακολούθηση σχετικών εσόδων
7. Export ή backup των αποθηκευμένων πληροφοριών

Στόχος είναι όλα αυτά να συγκεντρώνονται σε ένα εστιασμένο desktop περιβάλλον.

---

## Local-First Αρχιτεκτονική

Το Ordinox Desk Lite λειτουργεί τοπικά στον Windows υπολογιστή του χρήστη.

Για την κανονική χρήση:

- Δεν απαιτείται remote backend
- Δεν απαιτείται cloud database
- Τα δεδομένα αποθηκεύονται τοπικά
- Ο χρήστης μπορεί να δημιουργεί backup files
- Υπάρχει restore/import workflow
- Δεν απαιτείται συνεχής σύνδεση στο Internet

---

## Windows Desktop Application

Το Ordinox Desk Lite λειτουργεί ως standalone Windows εφαρμογή μέσω **Tauri 2**.

Το project περιλαμβάνει ρυθμίσεις για:

- Native Windows execution
- Application identity και branding
- Application icons
- Release builds
- Windows packaging
- Installer generation

Το interface και η βασική business logic υλοποιούνται με HTML, CSS και Vanilla JavaScript, ενώ το Tauri παρέχει το desktop runtime και το packaging environment.

---

## Data Export

Η εφαρμογή περιλαμβάνει δυνατότητες εξαγωγής επαγγελματικών πληροφοριών σε πρακτικές μορφές.

Ανάλογα με τη ροή εργασίας, μπορούν να εξαχθούν:

- Client-related data
- Revenue information
- Spreadsheet-compatible αρχεία
- Printable / PDF-ready output
- JSON backup files

---

## Προσέγγιση Ανάπτυξης

Το Ordinox Desk Lite αναπτύχθηκε σταδιακά.

Η διαδικασία περιλαμβάνει:

1. Κατανόηση της απαιτούμενης επαγγελματικής ροής
2. Σχεδιασμό της κατάλληλης λειτουργίας
3. Υλοποίηση της αλλαγής
4. Έλεγχο του επηρεαζόμενου κώδικα
5. Εκτέλεση και δοκιμή της εφαρμογής
6. Έλεγχο για regressions
7. Βελτίωση του interface όπου χρειάζεται
8. Αποφυγή άσχετων αλλαγών

---

## AI-Assisted Development

AI-assisted development εργαλεία αποτελούν σημαντικό μέρος του workflow μου, ιδιαίτερα το **OpenAI Codex**.

Χρησιμοποιούνται για:

- Ανάλυση υπάρχοντος κώδικα
- Feature implementation
- Debugging
- Διερεύνηση bugs
- Code refinement
- Έλεγχο πιθανών side effects
- Διερεύνηση εναλλακτικών υλοποιήσεων
- Testing και validation

Οι αλλαγές ελέγχονται και δοκιμάζονται σταδιακά και δεν εφαρμόζονται μηχανικά.

---

## Τι αποκόμισα από το project

Η ανάπτυξη του Ordinox Desk Lite μου έδωσε πρακτική εμπειρία σε:

- Desktop application development
- Σχεδιασμό εξειδικευμένου business workflow
- Client data management
- Optical prescription data structures
- Application state management
- Local data persistence
- HTML, CSS και Vanilla JavaScript
- UI/UX refinement
- Search και filtering workflows
- Debugging και troubleshooting
- Data validation
- Backup και restore functionality
- Data export workflows
- Tauri configuration
- Windows packaging
- Installer preparation
- AI-assisted software development
- Iterative product development

---

## Δομή Project

Η εφαρμογή χρησιμοποιεί web-based frontend μέσα σε Tauri desktop environment.

Το project οργανώνεται γύρω από:

- HTML για τη δομή της εφαρμογής
- CSS για το custom interface
- JavaScript για application logic και state
- Tauri configuration για το desktop environment
- Rust/Tauri bootstrap code για το native application shell
- Local storage για application data
- JSON-based backup και import workflows

Η πλειονότητα της business logic υλοποιείται σε JavaScript.

---

## Test Data & Privacy

Όλα τα ονόματα, τηλέφωνα, οπτικές συνταγές, επισκέψεις και λοιπά προσωπικά στοιχεία που εμφανίζονται στα screenshots είναι **φανταστικά test/demo δεδομένα**.

Δεν αντιστοιχούν σε πραγματικούς πελάτες ή πρόσωπα.

Δεν περιλαμβάνονται πραγματικά δεδομένα πελατών σε αυτό το portfolio repository.

---

## Source Code

Ο πλήρης production source code του Ordinox Desk Lite διατηρείται ιδιωτικός.

Αυτό το repository λειτουργεί ως **project showcase και portfolio παρουσίαση**, με documentation και οπτικό υλικό της εφαρμογής.

Ο πλήρης πηγαίος κώδικας δεν περιλαμβάνεται σε αυτό το δημόσιο showcase repository.

---

## Κατάσταση Project

**Λειτουργικό προσωπικό software project.**

Το Ordinox Desk Lite είναι λειτουργική Windows desktop εφαρμογή με έμφαση στη διαχείριση πελατών και επιχειρησιακών πληροφοριών για οπτικά καταστήματα.
