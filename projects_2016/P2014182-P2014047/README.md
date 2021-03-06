#Interactive visualization

ΜΑΡΙΑ ΜΑΛΑΚΟΠΟΥΛΟΥ 
ΑΜ: P2014182

ΚΑΤΕΡΙΝΑ ΚΑΡΒΟΥΝΗ
ΑΜ: P2014047


##Παραδοτέο 1

ΘΕΜΑ ΕΡΓΑΣΙΑΣ:
Interactive visualization (Processing)

##Παραδοτέο 2

'Εγινε η κατάλληλη εγκατάσταση των εργαλείων με το οποία θα δουλέψουμε. Ανατρέξαμε σε διάφορα παραδείγματα και μας κέντρισε το ενδιφέρον το "Game of life" (https://processing.org/examples/gameoflife.html), με το οποίο και τελικά θα ασχοληθούμε. Κάναμε κάποιες αλλαγές στον κώδικα οι οποίες είναι οι εξής: 
-αλλάξαμε το μέγεθος παραθύρου στο οποίο γίνεται η αναπαραγωγή του κώδικα σε εικόνα
-προσθέσαμε ένα module το οποίο μπορεί να τραβάει στιγμιότυπα καθώς παίζει η εφαρμογή στο άλλο παράθυρο και να τα αποθηκεύει σε ένα άλλο φάκελο τον οποίο έχουμε φτίαξει εμείς. Αφού τραβήξει τα στιγμιότυπα, τα αποθηκεύει στο φάκελο με τη μορφη εικόνας. Σκοπός συτού του module είναι να συλλέξουμε τις εικόνες αυτές, να τις κάνουμε κάποιο βίντεο και να δούμε/μελετήσουμε την πορεία και την συμπεριφορά της εφαρμογηής αυτής.
-αλλάξαμε το μέγεθος των κελιών
-αλλάξαμε την πιθανότητα ζωής στο ξεκίνημα της εφαρμογής
-αλλάξαμε το χρώμα ζωής 
-αλλαξαμε την τιμή στο stroke

Στιγμιότυπα εικόνων( https://github.com/maroumal/-2-/commit/191a95b4390c582bdecfddb581b136e0af64534c ):
0-6 (πηγαίος κώδικας)
7 (φάκελος με το εγκατεστημένο εργαλειο)
8 (στιγμιότυπα εφαρμογής)
9 (τρέξιμο πηγαίου κώδικα)
10,11,16 (αλλαγές στον κώδικα)
12 (τρέξιμο νέου κώδικα)
13-15 ( δημιοθργία βίντεο για την μελέτη της εφαρμογής)




##Παραδοτέο 3

Σε αυτό το παραδοτέο κάναμε κάποιες αλλαγές/τροποποιήσεις στον κώδικα της εφαρμογής. Στον πηγαίο κώδικα υπάρχουν κάποια πλήκτρα τα οποία, όταν τα πατάς εκτελούν κάποιες λειτουργίες. Αυτά τα πλήκτρα είναι το c(το οποίο καθαρίζει το παράθυρο ), το space (το οποίο κάνει παύση της εφαρμογής ) και το r (το οποίο αρχίζει από την αρχή την αναπαραγωγή της εφαρμογής). Εμείς προσθέσαμε άλλα 3 πλήκτρα στον κώδικα τα οποία είναι το a (το οποίο καθαρίζει το παράθυρο και μετά ενεργοποιεί όλα τα κελιά ταυτόχρονα ), το k (το οποίο καθαρίζει το επάνω μισό μέρος του παραθύρου) και το h (το οποίο καθαρίζει το αριστερό κάθετο μέρος του παραθύρου). Στη συνέχεια φαίνεται σε screenshot ο κώδικας ο οποίος έχουμε προσθέσει(https://github.com/maroumal/screenshot-for-3-/blob/master/2016-11-30.png).



##Tελική Αναφορά

ΤΙΤΛΟΣ: GAME OF LIFE

ΣΥΝΟΨΗ: Πήραμε το αρχικό παιχνίδι game of life, το οποίο βρήκαμε στο processing, το επεξεργαστήκαμε, προσθέσαμε κάποια επιπλέον κομμάτια κώδικα, ώστε με συγκεκριμένες λειτουργίες του χρήστη να αλλάζει η διαμόρφωση της οθόνης.

ΕΙΣΑΓΩΓΗ: Διαμορφώσαμε το παιχνίδι game of life ως προς τα στοιχεία εμφάνισης του και προσθέσαμε συγκεκριμένα πλήκτρα, έτσι ώστε όταν τα χρησιμοποιεί ο χρήστης να αλλάζουν τη διαμόρφωση της οθόνης.

ΕΠΙΛΟΓΗ ΕΡΓΑΛΕΙΩΝ: Χρησιμοποιήσαμε το εργαλείο processing.

ΔΙΑΔΙΚΑΣΙΑ ΑΝΑΠΤΥΞΗΣ: Μελετήσαμε τον κώδικα και τον τροποποιήσαμε καταλλήλως, έτσι ώστε να αλλάξει το μέγεθος της οθόνης, το χρώμα, όπως επίσης προσθέσαμε ένα κομμάτι κώδικα το οποίο αποτύπωνε και αποθήκευε στιγμιότυπα από το τρέξιμο της εφαρμογής. Επίσης προσθέσαμε ειδικό κώδικα, ο οποίος μέσω κάποιων συγκεκριμένων πλήκτρων συντελεί κάποιες λειτουργίες, όπως ο διαχωρισμός της οθόνης είτε κάθετα, είτε οριζόντια, όπως επίσης ο καθαρισμός της και ο διαχωρισμός της σε τεταρτημόρια. Τέλος, προσθέσαμε ένα τελευταίο κομμάτι κώδικα, ο οποίος δεν εμφανίζει τις γραμμές των κελιών.


ΔΙΑΓΡΑΜΜΑ ΛΕΙΤΟΥΡΓΙΑΣ ΣΥΣΤΗΜΑΤΟΣ:
1) Επεξεργασία μεγέθους οθόνης.
2) Επεξεργασία μεγέθους κελιών.
3) Μορφοποίηση χρώματος οθόνης.
4) Αποτύπωση και αποθήκευση στιγμιοτύπου οθόνης.
5) Προσθήκη πλήκτρου c, το οποίο καθαρίζει το παράθυρο. 
6) Προσθήκη πλήκτρου space, το οποίο κάνει παύση της εφαρμογής.
7) Προσθήκη πλήκτρου r, το οποίο αρχίζει από την αρχή την αναπαραγωγή της εφαρμογής.
8) Προσθήκη πλήκτρου a, το οποίο καθαρίζει το παράθυρο και μετά ενεργοποιεί όλα τα κελιά ταυτόχρονα. 
9) Προσθήκη πλήκτρου k, το οποίο καθαρίζει το επάνω μισό μέρος του παραθύρου.
10) Προσθήκη πλήκτρου h, το οποίο καθαρίζει το αριστερό κάθετο μέρος του παραθύρου.


ΕΝΔΕΙΚΤΙΚΕΣ ΟΘΟΝΕΣ: Υπάρχουν σε φακέλους από πάνω.

ΣΥΜΠΕΡΑΣΜΑΤΑ: Κάνοντας αυτήν την εργασία μπορέσαμε να εξοικειωθούμε με το εργαλείο processing. Μελετήσαμε και επεξεργαστήκαμε τον κώδικα της εφαρμογής και αυτό μας βοήθησε να κατανοήσουμε καλύτερα τη γλώσσα προγραμματισμού στην οποία είναι γραμμένο. Τέλος, κάνοντας αυτήν την εργασία μπορεί κάποιος να εξοικειωθεί με τα πολυμέσα.
