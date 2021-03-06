![logo](https://github.com/robotics-4-all/Announcements/blob/master/Capture.PNG?raw=true)
# Διαθέσιμες διπλωματικές ISSEL περιόδου Νοεμβρίου 2020

Παρακάτω μπορείτε να βρείτε τα νέα θέματα διπλωματικών (Νοέμβριος 2020) της Ομάδας Ευφυών Συστημάτων και Τεχνολογίας Λογισμικού. Οι φοιτητές που ενδιαφέρονται για διπλωματική εργασία παρακαλούνται να συμπληρώσουν [τη φόρμα έκφρασης ενδιαφέροντος](https://issel.ee.auth.gr/diathesimes-diplwmatikes/%cf%86%cf%8c%cf%81%ce%bc%ce%b1-%ce%ad%ce%ba%cf%86%cf%81%ce%b1%cf%83%ce%b7%cf%82-%ce%b5%ce%bd%ce%b4%ce%b9%ce%b1%cf%86%ce%ad%cf%81%ce%bf%ce%bd%cf%84%ce%bf%cf%82/) έως και τις 22/11. Μπορείτε να βρείτε ένα αρχείο με παρουσίαση των διπλωματικών στον σύνδεσμο: [Link](https://www.dropbox.com/s/lwe0tsxb0dtz9c6/ISSEL%20Theses%202020-Autumn.pdf?dl=0)
Τέλος, βρείτε σχετικές ερωτήσεις σχετικά με τη διαδικασία επιλογής και τις απαιτήσεις στον παρακάτω σύνδεσμο: [Link](https://issel.ee.auth.gr/sixnes-erwtiseis/).

Περιεχόμενα:
- [SoftEng-Autumn20-1: Ανάπτυξη βιβλιοθήκης μεταπρογραμματισμού Python για επαλήθευση κατά την εκτέλεση (A Python Metaprogramming Library for Runtime Verification)](#softeng-autumn20-1)
- [SoftEng-Autumn20-2: Ανάλυση σφαλμάτων κώδικα με βάση το γράφο κλήσεων συναρτήσεων](#softeng-autumn20-2)
- [SoftEng-Autumn20-3: Εφαρμογή τεχνικών εξόρυξης δεδομένων για την αυτοματοποιημένη διόρθωση σφαλμάτων](#softeng-autumn20-3)
- [SoftEng-Autumn20-4: Βελτίωση του ρυθμού μετατροπών ηλεκτρονικών καταστημάτων με τεχνικές δυναμικής τιμολόγησης](#softeng-autumn20-4)
- [SoftEng-Autumn20-5: Τεχνικές εξατομικευμένης αναζήτησης σε ηλεκτρονικά καταστήματα](#softeng-autumn20-5)
- [SoftEng-Autumn20-6: Κατανόηση και κατηγοριοποίηση του περιεχομένου κειμένου με χρήση αλγορίθμων deep learning](#softeng-autumn20-6)
- [SoftEng-Autumn20-7: Ανάπτυξη συστήματος Συνεχούς Επόπτευσης Ποιότητας Πηγαίου Κώδικα (Code Quality Assistant)](#softeng-autumn20-7)
- [SoftEng-Autumn20-8: Συνεχής έμμεση αυθεντικοποίηση χρηστών κινητού τηλεφώνου με συνδυασμό των δεδομένων πλοήγησης και συμπεριφοράς](#softeng-autumn20-8)
- [SoftEng-Autumn20-9: Χρήση ιδιωμάτων κώδικα και μετρικών στατικής ανάλυσης για τη βελτίωση της αναγνωσιμότητας ενός έργου λογισμικού](#softeng-autumn20-9)

---

## SoftEng-Autumn20-1
**Ανάπτυξη βιβλιοθήκης μεταπρογραμματισμού Python για επαλήθευση κατά την εκτέλεση (A Python Metaprogramming Library for Runtime Verification)**

Οι εξελίξεις στην τεχνολογία λογισμικού έχουν οδηγήσει στην ολοένα και αυξανόμενη αντιμετώπιση του πηγαίου κώδικα ως προϊόν. Έτσι, καθίσταται ιδιαίτερα σημαντική η εξασφάλιση της ποιότητάς του με χρήση μηχανισμών ελέγχου προγραμματιστικών ή λογικών σφαλμάτων. Οι μηχανισμοί αυτοί κυμαίνονται από αυστηρά θεωρητική προτυποποίηση των μοντέλων του κώδικα μέχρι την κατά περίπτωση συγγραφή ευρεστικών ελέγχων (tests).

Ένας ανερχόμενος τρόπος ελέγχου της ποιότητας του κώδικα, ο οποίος παρέχει ισορροπία μεταξύ μαθηματικής αυστηρότητας και ευελιξίας, είναι η επαλήθευση της ορθής λειτουργίας του κατά την εκτέλεση (runtime verification). Η γενική ιδέα είναι ότι ένα σύστημα παρακολουθεί την εκτέλεση του κώδικα, για παράδειγμα προσπελαύνοντας και διατηρώντας εγγραφές της στοίβας κλήσεων συναρτήσεων στη μνήμη, και ελέγχει κατά πόσο αυτή υπακούει σε συγκεκριμένες ιδιότητες, οι οποίες μπορούν να εκφραστούν με γλώσσες γραμμικού χρόνου και να ελεγχθούν με πεπερασμένα αυτόματα (βλπ. θεωρία υπολογισμών και αλγορίθμων).

Στόχος αυτής της διπλωματικής είναι η εφαρμογή τεχνικών επαλήθευσης κατά την εκτέλεση στη γλώσσα Python με τρόπο φιλικό προς το χρήστη, για παράδειγμα με επέκταση της γλώσσας περιγραφής σεναρίων χρήσης Gherkin (https://cucumber.io/docs/gherkin/reference/) ώστε να περιγράφει η ροη πληροφορίας μέσα από μεταβλητές.

Για αυτό το σκοπό θα δημιουργηθεί μια βιβλιοθήκη μεταπρογραμματισμού (πρακτικά επέκτασης) της γλώσσας Python, η οποία μπορεί να επισυνάψει ιδιότητες στις μεταβλητές που προκύπτουν και να παρακολουθήσει συμβάντα, όπως εκτέλεση συναρτήσεων. Ο κορμός της βιβλιοθήκης αυτής είναι ήδη διαθέσιμος και θα επικεντρωθούμε στην ανάπτυξη μιας επέκτασης της Gherkin η οποία μπορεί να ερμηνεύσει (και άρα είναι εξίσου ισχυρή με) γλώσσες γραμμικού χρόνου, καθώς και σε σύστημα σύγκρισης συνημένων ιδιοτήτων (π.χ. ότι οι ιδιότητες “is_locked” και “SHOULD NOT is_locked“ κατά την εφαρμογή νηματοποίησης έρχονται σε αντίθεση).

Η διπλωματική αυτή μπορεί να αποκτήσει διάφορες κατευθύνσεις, ανάλογα με το πόσο έμφαση δώσουμε στο θεωρητικό υπόβαθρο σε σχέση με τη χρηστικότητα της βιβλιοθήκης. Ιδανικά, θα καταλήξουμε στη συγγραφή δημοσίευσης σχετική με την επαλήθευση κατά την εκτέλεση.

**Απαιτήσεις:** Ευχέρεια σε Python, διάθεση για δουλειά

**Εμπλεκόμενες τεχνολογίες:** Τεχνολογία λογισμικού, επαλήθευση κατά την εκτέλεση, θεωρία αλγορίθμων, λογική μοντελοποίηση

**Γνώσεις που θα αποκτηθούν:** Ερευνητική εμπειρία στην τεχνολογία λογισμικού, Ανάπτυξη βιβλιοθήκης Python, Ερευνητική εμπειρία σε θεωρία αλγορίθμων και λογικές χαμηλών επιπέδων, Συγγραφή δημοσίευσης

**Εκτιμώμενος χρόνος περάτωσης:** 6-12 μήνες

**Συνεργαζόμενοι ερευνητές:** Αναπληρωτής Καθηγητής Ανδρέας Λ. Συμεωνίδης, Υποψήφιος Διδάκτωρ Εμμανουήλ Κρασανάκης

---

## SoftEng-Autumn20-2
**Ανάλυση σφαλμάτων κώδικα με βάση το γράφο κλήσεων συναρτήσεων**

Η εύρεση και αντιμετώπιση σφαλμάτων αποτελεί σημαντικό μέρος του κύκλου ζωής έργων λογισμικού, καθώς διασφαλίζει την ομαλή λειτουργία τους στον πραγματικό κόσμο. Ένα σύνηθες πρότυπο αποσφαλμάτωσης είναι η άμεση καταγραφή σφαλμάτων από τους χρήστες, για παράδειγμα μέσω εργαλείων αναφοράς σφαλμάτων για εμπορικές εφαρμογές (reporting tools) ή άνοιγμα θεμάτων (issues) σε έργα λογισμικού ανοικτού κώδικα. Έτσι, δημιουργούνται  “τράπεζες γνωστών σφαλμάτων” τα οποία χρήζουν αντιμετώπιση από την ομάδα ανάπτυξης και συντήρησης.

Μεγάλα και δημοφιλή έργα λογισμικού καταλήγουν να έχουν ένα τεράστιο πλήθος αναφερομένων σφαλμάτων. Η επεξεργασία αυτών καθίσταται τόσο χρονοβόρα, ώστε συχνά συστήνονται υπο-ομάδες συντήρησης με σκοπό την οργάνωση της διαδικασίας επίλυσης, για παράδειγμα αναγνωρίζοντας τη σημαντικότητά τους και επιλέγοντας τους προγραμματιστές προς επίλυση.

Σε αυτή τη διπλωματική θα αναλύσουμε καταγεγραμμένα σφάλματα τα οποία περιέχουν πληροφορία του γράφου κλήσεων συναρτήσεων μέσω καταγραφών στοίβας (stack traces). Οι καταγραφές στοίβας είναι γνωστό ότι έχουν πρακτική χρησιμότητα για την επίλυσή μεμονωμένων σφαλμάτων. Χρησιμοποιώντας τες, μπορούμε να κινηθούμε σε διαφορετικούς αντικειμενικούς στόχου ανάλυσης, όπως η ανάθεση σφαλμάτων για επίλυση στους σωστούς προγραμματιστές, η αναγνώριση της σημαντικότητάς τους και η αναγνώριση των τμημάτων του έργου λογισμικού (π.χ. μεθόδων ή αρχείων) που οδηγούν στην εμφάνιση των περισσότερων σφαλμάτων.

Η γενική μεθοδολογία που θα ακολουθήσουμε συνίσταται στο να οργανώσουμε τις καταγραφες στοίβας σε έναν ενιαίο γράφο κλήσεων συναρτήσεων για όλα τα γνωστά σφάλματα και να εφαρμόσουμε τεχνικές εξόρυξης πληροφορίας από γράφους για να εξάγουμε χαρακτηριστικά (features) που περιγράφουν τα σφάλματα. Στη συνέχεια, θα χρησιμοποιήσουμε μια μίξη αυτών των χαρακτηριστικών με χαρακτηριστικά που θα εξαχθούν από την περιγραφή των σφαλμάτων σε φυσική γλώσσα και θα χρησιμοποιήσουμε τεχνικές μηχανικής μάθησης για να επιλύσουμε τον επιλεγμένο αντικειμενικό στόχο.

**Εμπλεκόμενες τεχνολογίες:** Τεχνολογία λογισμικού, Εξόρυξη δεδομένων, Θεωρία γράφων, Μηχανική μάθηση

**Γνώσεις που θα αποκτηθούν:** Ερευνητική εμπειρία στην τεχνολογία λογισμικού, Ανάπτυξη σε Python ή Java, Προγραμματιστικά εργαλεία εξόρυξης δεδομένων και μηχανικής μάθηση, Βασικές μέθοδοι εξόρυξης πληροφορίας από φυσική γλώσσα και γράφους

**Εκτιμώμενος χρόνος περάτωσης:** 6-9 μήνες

**Συνεργαζόμενοι ερευνητές:** Αναπληρωτής Καθηγητής Ανδρέας Λ. Συμεωνίδης, Υποψήφιος Διδάκτωρ Εμμανουήλ Κρασανάκης

---


## SoftEng-Autumn20-3
**Εφαρμογή τεχνικών εξόρυξης δεδομένων για την αυτοματοποιημένη διόρθωση σφαλμάτων**

Η ταχεία εξάπλωση του διαδικτύου και η εντατικοποίηση της διαδικασίας ανάπτυξης λογισμικού έχουν αλλάξει ριζικά τον τρόπο συγγραφής κώδικα τα τελευταία χρόνια. Τα έργα λογισμικού σήμερα ελέγχονται τόσο κατά τη φάση της ανάπτυξης όσο και κατά τη φάση της συντήρησης χρησιμοποιώντας πλήθος εργαλείων που αναφέρουν πιθανά σφάλματα και προβλήματα στον κώδικα (code bugs/violations).

Εργαλεία ανάλυσης κώδικα όπως το PMD (http://pmd.sourceforge.net/), το FindBugs (http://findbugs.sourceforge.net/), το CheckStyle (http://checkstyle.sourceforge.net/), κ.α. είναι σε θέση να παρέχουν λεπτομερείς αναφορές, ενώ πολλές φορές παρέχουν ακόμα και χρήσιμα παραδείγματα για τον κώδικα του προγραμματιστή. Ωστόσο, η επίλυση των ίδιων προβλημάτων παραμένει μια χρονοβόρα και πολλές φορές δύσκολη διαδικασία. Ως εκ τούτου, αναζητούνται μέθοδοι για την ανάλυση κώδικα (π.χ. σε αφηρημένα συντακτικά δένδρα) και την εφαρμογή προτύπων για το μετασχηματισμό τους, με τελικό σκοπό την πραγματοποίηση αλλαγών στον κώδικα και/ή το αυτοματοποιημένο refactoring.

Στόχος της διπλωματικής είναι να δημιουργηθεί ένα σύστημα που εφαρμόζει μετασχηματισμούς κώδικα με σκοπό την αυτόματη διόρθωση των διαφόρων προβλημάτων και σφαλμάτων στον κώδικα του προγραμματιστή.

**Σχετικά Εμπορικά και Μη Συστήματα**:
- Getafix by Facebook, https://engineering.fb.com/2018/11/06/developer-tools/ [getafix-how-facebook-tools-learn-to-fix-bugs-automatically/](https://engineering.fb.com/2018/11/06/developer-tools/getafix-how-facebook-tools-learn-to-fix-bugs-automatically/)
- WalkMod, https://walkmod.com/
- AutoRefactor, http://autorefactor.org/

**Εμπλεκόμενες τεχνολογίες:** Εξόρυξη Δεδομένων, Τεχνολογία Λογισμικού, Αλγόριθμοι

**Γνώσεις που θα αποκτηθούν:** Ερευνητική εμπειρία στην Τεχνολογία Λογισμικού, Δημιουργία εφαρμογής σε Python ή Java, Βασικές διαδικασίες Ανάκτησης Πληροφοριών και Αλγορίθμων

**Εκτιμώμενος χρόνος περάτωσης:** 6-9 μήνες

**Συνεργαζόμενοι ερευνητές:** Αναπληρωτής Καθηγητής: Ανδρέας Λ. Συμεωνίδης, Μεταδιδακτορικός Ερευνητής: Θεμιστοκλής Διαμαντόπουλος

---

## SoftEng-Autumn20-4
**Βελτίωση του ρυθμού μετατροπών ηλεκτρονικών καταστημάτων με τεχνικές δυναμικής τιμολόγησης**

H δυναμική τιμολόγηση (dynamic pricing) είναι η διαδικασία με την οποία οι επιχειρήσεις αλλάζουν τις τιμές πωλήσεις με χρήση αλγορίθμων που λαμβάνουν υπόψη τον ανταγωνισμό, την προσφορά και ζήτηση, και άλλους εξωτερικούς παράγοντες της αγοράς. Αποτελεί μία κοινή πρακτική την οποία συναντάμε σε πολλούς τομείς της καθημερινότητας, όπως όταν κάνουμε κράτηση για αεροπορικά εισιτήρια και ξενοδοχεία, ή στον τομέα της  ηλεκτρικής ενέργειας. Παρόλα αυτά η εφαρμογή παρόμοιων τεχνικών παρουσιάζει περιορισμένη εφαρμογή στα ηλεκτρονικά καταστήματα λιανικής πώλησης.

H δυναμική τιμολόγηση είναι μία διαδικασία με ιδιαίτερες προκλήσεις, απαιτεί μία πολυπαραγοντική ανάλυση η οποία συνδυάζει δεδομένα ζήτησης, ανταγωνισμού, κόστους και διαθέσιμου στοκ. Αποτελεί μια προσέγγιση καθορισμού των τιμών που βασίζεται στην ανάλυση των δεδομένων και την ευελιξία. Οι τεχνικές δυναμικής τιμολόγησης επιτρέπουν την διαμόρφωση και τον έλεγχο των τιμών σε συνθήκες σχεδόν πραγματικού χρόνου, ανάλογα με τα προϊόν, τις προηγούμενες αλληλεπιδράσεις των πελατών με την ιστοσελίδα και το προφίλ τους, δημιουργώντας εξατομικευμένες προσφορές.

Στόχος της διπλωματικής εργασίας είναι η ανάπτυξη μεθόδων δυναμικής τιμολόγησης που θα λαμβάνουν υπόψη την ζήτηση, τον ανταγωνισμό, το διαθέσιμο στοκ, καθώς και το προφίλ του χρήστη. Το σύστημα που θα δημιουργηθεί θα κάνει χρήση μεθόδων και αλγορίθμων βελτιστοποίησης και εξατομίκευσης, συνδυάζοντας τα παραπάνω δεδομένα και θα αποφασίζει δυναμικά την τιμή για κάθε προϊόν ανά πελάτη με στόχο την βελτιστοποίηση του ποσοστού μετατροπών (conversion rate). Η αξιολόγηση των μεθόδων που θα αναπτυχθούν θα πραγματοποιηθεί με ανώνυμα δεδομένα που θα προέλθουν από το ηλεκτρονικό φαρμακείο www.pharm24.gr

**Προαπαιτούμενα**: Καλή γνώση προγραμματισμού, Δομές και Βάσεις Δεδομένων, Φαντασία και όρεξη για δουλειά

**Εμπλεκόμενες Τεχνολογίες – Γνώσεις που θα αποκτηθούν**: Μέθοδοι εξατομίκευσης περιεχομένου, Αλγόριθμοι και τεχνικές ανάλυσης δεδομένων, Τεχνικές βελτιστοποίησης

**Εκτιμώμενος χρόνος περάτωσης:** 6-9 μήνες

**Συνεργαζόμενοι ερευνητές:** Κωνσταντίνος Βαβλιάκης

---

## SoftEng-Autumn20-5
**Τεχνικές εξατομικευμένης αναζήτησης σε ηλεκτρονικά καταστήματα**

Η εξατομίκευση περιεχομένου (personalization) αποτελεί ένα από τα μεγαλύτερα ανταγωνιστικά πλεονεκτήματα των ηλεκτρονικών καταστημάτων, έναντι των παραδοσιακών (brick and mortar) καταστημάτων. Σε ένα ηλεκτρονικό κατάστημα που γίνεται χρήση τεχνικών εξατομίκευσης, ο χρήστης-πελάτης βλέπει ως αποτελέσματα στις ενέργειας πλοήγησης ή αναζήτησης που κάνει, προϊόντα που είναι σχετικά με το προφίλ και τα ενδιαφέροντα του, με αποτέλεσμα να αυξάνεται ο ρυθμός μετατροπών, αλλά και η αξία του μέσου καλαθιού των αγορών. Ως αποτέλεσμα, αφενός ο πελάτης λαμβάνει υπηρεσίες αυξημένου επιπέδου, αφού βρίσκει ευκολότερα και γρηγορότερα προϊόντα που αναζητεί, αφετέρου το ηλεκτρονικό κατάστημα αυξάνει τις πωλήσεις του.

Παρόλο που η παροχή εξατομικευμένων υπηρεσιών έχει πολλαπλά οφέλη, η χρήση της περιορίζεται κατά βάση στην προβολή σχετικών προϊόντων ή στον διαχωρισμό (segmentation) πελατών με στόχο την αποστολή διαφορετικών μηνυμάτων. Αντίθετα, η προβολή αποτελεσμάτων αναζήτησης ελεύθερου κειμένου με εξατομικευμένο τρόπο έχει ακόμα περιορισμένη εφαρμογή, τουλάχιστον σε μικρομεσαία ηλεκτρονικά που δεν έχουν τους πόρους μεγάλων καταστημάτων όπως η Amazon και το Ebay.

Στόχος της διπλωματικής εργασίας είναι η ανάπτυξη μεθόδων εξατομίκευσης της αναζήτησης ελεύθερου κειμένου σε ηλεκτρονικά καταστήματα. Για τον λόγο αυτό θα χρησιμοποιηθεί η nosql μηχανή αναζήτησης ElasticSearch που έχει την δυνατότητα να εκτελεί ερωτήματα αναζήτησης ελεύθερου κειμένου σε μεγάλα σύνολα δεδομένων. Το σύστημα που θα δημιουργηθεί θα κάνει χρήση μεθόδων και αλγορίθμων βελτιστοποίησης και εξατομίκευσης, συνδυάζοντας δεδομένα σχετικά με το ερώτημα του χρήστη, τα χαρακτηριστικά των προϊόντων και του ιστορικού/προφίλ του χρήστη. Με βάση τα παραπάνω δεδομένα, το σύστημα θα αποφασίζει δυναμικά για την βέλτιστη σειρά εμφάνισης των αποτελεσμάτων αναζήτησης ανά πελάτη με στόχο την βελτιστοποίηση της εμπειρίας χρήσης (UX – user experience). Η αξιολόγηση των μεθόδων που θα αναπτυχθούν θα πραγματοποιηθεί με ανώνυμα δεδομένα που θα προέλθουν από το ηλεκτρονικό φαρμακείο www.pharm24.gr

**Προαπαιτούμενα**: Καλή γνώση προγραμματισμού, Δομές και Βάσεις Δεδομένων, Φαντασία και όρεξη για δουλειά

**Εμπλεκόμενες Τεχνολογίες – Γνώσεις που θα αποκτηθούν**: Μέθοδοι εξατομίκευσης περιεχομένου, ElasticSearch

**Εκτιμώμενος χρόνος περάτωσης:** 6-9 μήνες

**Συνεργαζόμενοι ερευνητές:** Κωνσταντίνος Βαβλιάκης

---

## SoftEng-Autumn20-6
**Κατανόηση και κατηγοριοποίηση του περιεχομένου κειμένου με χρήση αλγορίθμων deep learning**

Με την πρόοδο της τεχνολογίας των τελευταίων ετών τα conversational chatbots έχουν ενταχθεί στην καθημερινότητα μας. Ωστόσο, η μελέτη και η κατανόηση της φυσικής γλώσσας είναι ακόμη σε πρώιμο στάδιο και εμπεριέχει πολλές προκλήσεις. Ένα πρόβλημα που συναντάται είναι η αδυναμία των συστημάτων να διαχειριστούν συζητήσεις γενικού περιεχομένου, ώστε να επικοινωνήσουν με έναν πιο φυσικό τρόπο.

Η εργασία αυτή στοχεύει στην επίλυση αυτού του προβλήματος μελετώντας διάφορες θεματικές που συναντώνται σε καθημερινές συζητήσεις με την χρήση σύγχρονων αλγορίθμων κατανόησης γλώσσας. Στη συνέχεια, θα δημιουργηθεί μια conversational εφαρμογή υψηλού επιπέδου σε ένα state-of-the-art chatbot framework που θα μπορεί να διαχειριστεί καθημερινές συζητήσεις με τους χρήστες.

Πιο αναλυτικά, τα βήματα της διπλωματικής εργασίας περιλαμβάνουν:
- Τη δημιουργία ενός web crawler για την συλλογή ενός dataset ελληνικών κειμένων διάφορων θεματικών
- Την εξαγωγή χρήσιμων χαρακτηριστικών του κειμένου, όπως οντότητες (name entity recognition) και λέξεις κλειδιά
- Την μελέτη αλγορίθμων deep learning για την κατηγοριοποίηση κειμένου με βάση το περιεχόμενο και τα χαρακτηριστικά του (topic classification)
- Την χρήση των μοντέλων σε chatbots και την δημιουργία conversational εφαρμογής για επικοινωνία με βάση τις θεματικές που επιθυμεί ο χρήστης

**Γνώσεις που θα αποκτηθούν**: Python, Natural Language Understanding, Deep Learning, συλλογή δεδομένων, semantic analysis, chatbots

**Εκτιμώμενος χρόνος περάτωσης:** 6-9 μήνες

**Συνεργαζόμενοι ερευνητές:** Αναπληρωτής Καθηγητής: Ανδρέας Λ. Συμεωνίδης, Υποψήφιος Διδάκτωρ: Νικόλας Μάλαμας

---

## SoftEng-Autumn20-7
**Ανάπτυξη συστήματος Συνεχούς Επόπτευσης Ποιότητας Πηγαίου Κώδικα (Code Quality Assistant)**

Οι ολοένα αυξανόμενες απαιτήσεις των σύγχρονων έργων λογισμικού, τα οποία αυξάνονται τόσο σε μέγεθος όσο και σε πολυπλοκότητα έχουν καταστήσει απαραίτητη της επόπτευση της ποιότητας. Με τον όρο ποιότητα αναφερόμαστε σε μια σειρά από χαρακτηριστικά του πηγαίου κώδικα όπως είναι η διατηρησιμότητα, η δυνατότητα επαναχρησιμοποίησης, η αναγνωσιμότητα, η ασφάλεια κ.α., τα οποία σχετίζονται άμεσα με ιδιότητες όπως είναι η πολυπλοκότητα, η σύζευξη, ο τρόπος συγγραφής κώδικα κ.α. Η ανάγκη επόπτευσης της ποιότητας έχει οδηγήσει στη δημιουργία πολυάριθμων εργαλείων μέσω των οποίων δίνεται η δυνατότητα υπολογισμού μεγάλου αριθμού μετρικών (όπως οι ευρέως χρησιμοποιούμενες μετρικές Halstead Metrics) καθώς και η εύρεση προβλημάτων που σχετίζονται με τον τρόπο συγγραφής του πηγαίου κώδικα (βλ. τα εργαλεία PMD, ESLint, Pylint κ.α.). Η ύπαρξη πολυάριθμων εργαλείων και συνεπώς η άφθονη πληροφορία που προκύπτει από την ανάλυση του πηγαίου κώδικα δημιουργεί μια σειρά από προκλήσεις, οι οποίες αντικατοπτρίζονται στα παρακάτω ερωτήματα:
- Πώς μπορεί τόση πολλή πληροφορία να οργανωθεί και να επικοινωνηθεί σωστά με στόχο να είναι εύπεπτη, στοχευμένη και συνεπώς καλύτερα αξιοποιήσιμη?
- Έχω 2000 προβληματικά ευρήματα... Τώρα τι να κάνω?
- Μπορεί να εφαρμοστεί η επόπτευση ποιότητας σε επίπεδο commit (πριν να είναι πολύ αργά για να διορθωθεί το πρόβλημα...)?
- Αν έχω 2 μέρες για διορθώσεις, τι είναι αυτό που πρέπει να διορθώσω πρώτο?
- Μπορούν όλα τα μέλη μιας ομάδας ανάπτυξης λογισμικού να γράφουν κώδικα με τον ίδιο τρόπο? Αν ναι, πώς?
- Πώς διαφοροποιείται η ποιότητα μέσα στο χρόνο? Σήμερα νομίζω είμαστε καλά... αλλά σε 1 μήνα?

Στόχος της παρούσας διπλωματικής εργασίας αποτελεί η δημιουργία ενός συστήματος συνεχούς επόπτευσης ποιότητας με τη μορφή ενός Quality Assistant. Το σύστημα θα εφαρμόζει ποιοτική ανάλυση σε επίπεδο commit και θα αλληλεπιδρά με την ομάδα ανάπτυξης λογισμικού μέσω του αποθετηρίου στο οποίο γίνεται η συγγραφή του κώδικα (GitHub App). Στόχοι της σχεδίασης και υλοποίησης είναι οι εξής:
- Η γρήγορη απόδοση
- Η όσο το δυνατόν καλύτερη ομαδοποίηση και παρουσίαση των αποτελεσμάτων
- Η δημιουργία συστάσεων με στόχο την βελτίωση της ποιότητας
- Η πλήρης αυτοματοποίηση
- Η μη παρέμβαση στην ήδη υπάρχουσα διαδικασία ανάπτυξης


**Γνώσεις που θα αποκτηθούν**: 
- Προγραμματισμός σε Python και Javascript (node.js και React.js)
- Ανάπτυξη GitHub Apps
- Μετρικές Στατικής Ανάλυσης (Static Analysis Metrics) και Παραβιάσεις Πηγαίου Κώδικα (Violations)
- Χρήση πακέτων/συναρτήσεων μηχανικής μάθησης (π.χ. scikit-learn)

**Εκτιμώμενος χρόνος περάτωσης:** 6-9 μήνες

**Συνεργαζόμενοι ερευνητές:** Αναπληρωτής Καθηγητής: Ανδρέας Λ. Συμεωνίδης, Υποψήφιος Διδάκτωρ: Μιχαήλ Παπαμιχαήλ

---

## SoftEng-Autumn20-8
**Συνεχής έμμεση αυθεντικοποίηση χρηστών κινητού τηλεφώνου με συνδυασμό των δεδομένων πλοήγησης και συμπεριφοράς**

Με την εξέλιξη των σύγχρονων κινητών τηλεφώνων (smartphones), η χρήση τους αυξάνεται δραματικά ως ένα μέσο για την εκτέλεση καθημερινών εργασιών, όπως η αποστολή/λήψη ηλεκτρονικών μηνυμάτων (emails), οργάνωση/υπενθύμιση δραστηριοτήτων, λήψη/προβολή φωτογραφιών κλπ. Έτσι, οι πληροφορίες που αποθηκεύονται στις συσκευές αυτές είναι αρκετά προσωπικές και ευαίσθητες και μπορούν να αποτελέσουν το αντικείμενο επιθέσεων.

Ταυτόχρονα, οι κλασικές μέθοδοι αυθεντικοποίησης (PIN, μοτίβο, δακτυλικό αποτύπωμα, αναγνώριση προσώπου) συχνά αποδεικνύονται αναποτελεσματικές. Ένα μεγάλο μέρος των χρηστών συχνά επιλέγει συνηθισμένους κωδικούς και μοτίβα (προκειμένου να μην θυμούνται περίεργους συνδυασμούς) ή δεν χρησιμοποιεί καθόλου αυτές τις μεθόδους για να αποφύγει τη σχετική επιβάρυνση, ενώ, ακόμα και με τη χρήση αυτών των μεθόδων, η συσκευή μπορεί να μείνει εκτεθειμένη, αφού μετά την αρχική είσοδο στο σύστημα δεν παρέχεται καμία επιπλέον ασφάλεια (one-time authentication).

Στόχος της διπλωματικής είναι η έρευνα και η ανάπτυξη μεθόδων συνεχούς αυθεντικοποίησης του χρήστη μιας κινητής συσκευής μέσω ανάλυσης, τόσο των χειρονομιών που χρησιμοποιεί για την πλοήγησή του στο περιβάλλον της συσκευής, όσο και των δεδομένων που παράγονται από τους διάφορους αισθητήρες της συσκευής. Για τον σκοπό αυτό θα πρέπει να γίνεται μια έμμεση ανάλυση των δεδομένων που δημιουργεί ο χρήστης από ένα μοντέλο μηχανικής μάθησης, το οποίο στη συνέχεια θα πιστοποιεί την ταυτότητα του χρήστη. 

**Προαπαιτούμενα:** Καλή γνώση προγραμματισμού, φαντασία και όρεξη για δουλειά

**Γνώσεις που θα αποκτηθούν:** Προγραμματισμός σε python, χρήση πακέτων/συναρτήσεων μηχανικής μάθησης (π.χ. scikit-learn, keras)

**Εκτιμώμενος χρόνος περάτωσης:** 9-12 μήνες

**Συνεργαζόμενοι ερευνητές:** Υπ.Δρ. Καρανικιώτης Θωμάς

---

## SoftEng-Autumn20-9
**Χρήση ιδιωμάτων κώδικα και μετρικών στατικής ανάλυσης για τη βελτίωση της αναγνωσιμότητας ενός έργου λογισμικού**

Τα τελευταία χρόνια, οι απαιτήσεις των χρηστών από τα έργα λογισμικού συνεχώς μεταβάλλονται και αναπτύσσονται, ενώ η αύξησή τους οδηγεί σε πολύ περιορισμένες προθεσμίες εκπλήρωσης στόχων, το οποίο έχει συχνά σαν αποτέλεσμα κακογραμμένο κώδικα, επιρρεπή σε σφάλματα. Για τον λόγο αυτό, έχει δοθεί ιδιαίτερη έμφαση τα τελευταία χρόνια στην αξιολόγηση της ποιότητας ενός έργου λογισμικού, με τη χρήση μετρικών στατικής ανάλυσης κώδικα. Μία από τις πτυχές της ποιότητας ενός κώδικα αποτελεί η αναγνωσιμότητα (readability), η οποία διαδραματίζει σημαντικό ρόλο, τόσο κατά τη φάση ανάπτυξης ενός έργου λογισμικού, όσο και κατά τη φάση συντήρησης.

Ταυτόχρονα, έχουν αναπτυχθεί διάφορα εργαλεία που υποστηρίζουν και υποβοηθούν την παραγωγή κώδικα από τους προγραμματιστές, όπως η αναζήτηση ιδιωμάτων κώδικα. Τα ιδιώματα (code idioms) αποτελούν μικρά τμήματα κώδικα (snippets), που έχουν ένα συγκεκριμένο σημασιολογικό σκοπό και επαναλαμβάνονται σε έργα λογισμικού υψηλού επιπέδου, ενώ διακρίνονται για την απλότητα, την αναγνωσιμότητα και την μεγάλη δυνατότητα επαναχρησιμοποίησής τους.

Στόχος της διπλωματικής είναι η έρευνα και η ανάπτυξη μεθόδων με στόχο την βελτίωση της γενικότερης ποιότητας λογισμικού, αλλά και συγκεκριμένα της αναγνωσιμότητας, μέσω της χρήσης ιδιωμάτων που έχουν εντοπιστεί σε γνωστά αποθετήρια κώδικα (π.χ. GitHub). Για τον σκοπό αυτό, θα πρέπει να γίνεται ταυτόχρονα μελέτη και ανάλυση των μετρικών στατικής ανάλυσης του κώδικα, για την εξαγωγή συμπερασμάτων σχετικά με την ποιότητά του.

**Προαπαιτούμενα:** Καλή γνώση προγραμματισμού, φαντασία και όρεξη για δουλειά

**Γνώσεις που θα αποκτηθούν:** Προγραμματισμός σε python, χρήση πακέτων/συναρτήσεων μηχανικής μάθησης (π.χ. scikit-learn, keras)

**Εκτιμώμενος χρόνος περάτωσης:** 9-12 μήνες

**Συνεργαζόμενοι ερευνητές:** Υπ.Δρ. Καρανικιώτης Θωμάς
