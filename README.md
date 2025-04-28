# micro-processor-systems-lab-6-solved
**TO GET THIS SOLUTION VISIT:** [Micro Processor Systems Lab 6 Solved](https://www.ankitcodinghub.com/product/micro-processor-systems-%ce%b4%ce%b5%cf%8d%cf%84%ce%b5%cf%81%ce%bf-%ce%b5%cf%81%ce%b3%ce%b1%cf%83%cf%84%ce%ae%cf%81%ce%b9%ce%bf-risc-v-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119180&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Micro Processor Systems Lab 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Εργαστήριο Μικροϋπολογιστών

Σε αυτό το εργαστήριο θα προγραμματίσετε τα LEDs της πλατφόρμας RVfpga γράφοντας απευθείας κώδικα assembly. Αυτή η βασική διαφορά σε σχέση με την πρώτη άσκηση (η οποία υλοποιήθηκε σε γλώσσα C) θα επιφέρει μεγαλύτερη εξοικείωση με το ISA RV32I, και μπορεί να αποτελέσει τη βάση για περαιτέρω μελλοντική σας ενασχόληση με τη συγκεκριμένη οικογένεια επεξεργαστών.

Αρχικοποίηση περιβάλλοντος

Το περιβάλλον προγραμματισμού και debugging παραμένει ίδιο με αυτό που χρησιμοποιήσατε για τις ανάγκες της πρώτης άσκησης. Για να ξεκινήσετε τη γραφή του κώδικά σας, ακολουθήστε τα ακόλουθα βήματα:

1. Δημιουργήστε ένα νέο PlatformIO project.

2. Τροποποιήστε κατά τα γνωστά το αρχείο platformio.ini.

3. Δημιουργήστε στον φάκελο src του project σας ένα νέο αρχείο με όνομα της επιλογής σας και κατάληξη .S (παράδειγμα: dummy.S).

Αρχικοποίηση αρχείου assembly

Το ISA RISC-V παρέχει στον προγραμματιστή μια ποικιλία ειδικών οδηγιών, ονόματι directives, που διευκολύνουν (αν όχι επιτρέπουν) τη γραφή λειτουργικού και ουσιώδους κώδικα. Για παράδειγμα, το directive .globl ενημερώνει τον compiler πως η αντίστοιχη ετικέτα-διεύθυνση μπορεί να αναφερθεί και από αρχεία διαφορετικά του παρόντος (όπως έχουμε δει, το firmware του RVfpga πρώτα θα κάνει διάφορες δικές του ενέργειες και κατόπιν θα πηδήξει στη main).

Αντίστοιχα directives υπάρχουν για τη δήλωση σταθερών, αρχικοποίηση διανυσμάτων, κτλ. Άλλα από αυτά είναι απαραίτητα να συμπεριληφθούν, και άλλα προαιρετικά. Ο Πίνακας 1 συνοψίζει όλα τα directives και τις περιγραφές τους.

Το ακόλουθο παράδειγμα αποτελείται από την αρχή ενός προγράμματος που επεξεργάζεται δύο μονοδιάστατους πίνακες μήκους 10 στοιχείων για να παράξει έναν τρίτο, ισομήκη πίνακα. Συναρτήσει του Πίνακα 1, είναι εύκολο να εξάγετε συμπεράσματα για το πού συνεισφέρει το κάθε directive. Κάποια ενδιαφέροντα σχόλια που μπορούν να γίνουν είναι:

● γιατί ενώ ο πίνακας C είναι 10 στοιχείων (όσων δηλαδή και οι Α, Β) δεσμεύουμε για αυτόν μνήμη τετραπλάσιου μεγέθους;

○ διότι από το τμήμα κάτω από το directive .data βλέπουμε ότι τα στοιχεία των πινάκων είναι τύπου word (μήκος 4 bytes, byte addressed μνήμη)

● ποιοι καταχωρητές χρησιμοποιούνται στο σώμα της main;

○ κατά κόρον οι temporary καταχωρητές t0, t1 κ.ο.κ.

● ποια από τα directives του παραδείγματος φαίνονται απαραίτητα για τη γραφή της πλειοψηφίας απλοϊκών προγραμμάτων σαν και αυτό; ○ hint: δεν είναι το .equ

.globl main

#

.equ N, 10

.data

A: .word 0,1,2,7,-8,4,5,-12,11,-2

B: .word 0,1,2,7,-8,4,5,12,-11,-2

.bss

C: .space 4*N

.text

main:

la t0, A

la t1, B

add t1, t1, 4*(N-1)

#Rest of the program follows . . .

#…

.end

● πώς μπορώ να εποπτεύσω τις θέσεις μνήμης που παρέχονται σε κάθε έναν από τους πίνακες, εφ’ όσον αυτές δεν αναφέρονται ρητά;

○ αφήνεται ως άσκηση

Ζητούμενα

Οι παραπάνω πληροφορίες επαρκούν για την υλοποίηση των ακόλουθων ερωτημάτων. Όπως και στην πρώτη άσκηση, υλοποιήστε κάθε ερώτημα ως ξεχωριστό PlatformIO project. Αντίθετα με την πρώτη άσκηση, τα προγράμματά σας δεν είναι απαραίτητο να

είναι συνεχούς λειτουργίας.

Ερώτημα 1

Συμπληρώστε τον κώδικα του παραδείγματος ώστε στον πίνακα C να αποθηκεύονται όλα τα στοιχεία της μορφής:

Ερώτημα 2

Να γραφεί κώδικας assembly που εκτελεί την εξής σειρά βημάτων:

1. Άναμμα λιγότερο σημαντικού LED

2. “Ολίσθηση” ένδειξης προς τα αριστερά (δηλαδή σβήσιμο λιγότερο σημαντικού LED και άναμμα 2ου λιγότερο σημαντικού)

3. Επανάληψη βήματος 2 μέχρις ότου η ένδειξη φτάσει το πιο σημαντικό LED

4. Κρατώντας το πιο σημαντικό LED αναμμένο, επανάληψη βήματος 1

5. Επανάληψη βήματος 2 μέχρις ότου η ένδειξη φτάσει το 2ο πιο σημαντικό LED

6. Κρατώντας τα 2 πιο σημαντικά LED αναμμένα, επανάληψη βήματος 1

Όταν ανάψουν όλα τα LEDs, φροντίστε να ξεκινάει το σβήσιμό τους ακολουθώντας την ακριβώς αντίστροφη διαδικασία. Δηλαδή:

1. Σβήσιμο σημαντικότερου LED

2. “Oλίσθηση” μη-ένδειξης προς τα δεξιά (δηλαδή άναμμα σημαντικότερου LED και σβήσιμο 2oυ σημαντικότερου)

3. Κ.ο.κ. …….

Παραδοτέα

Η επιτυχής εξέταση της παρούσας άσκησης μεταφράζεται μόνο ως εμπρόθεσμη παράδοση αναλυτικής αναφοράς, συνοδευόμενης από τα αντίστοιχα PlatformIO projects. Δεν θα πραγματοποιηθεί προφορική εξέταση, όμως οι κώδικές σας θα βαθμολογηθούν αυστηρά (δώστε μεγάλη έμφαση, όπως και στην προηγούμενη άσκηση, στον σχολιασμό του κώδικά σας).

Ως τελική προθεσμία για την παράδοση της άσκησης ορίζεται η Παρασκευή 22/1.
