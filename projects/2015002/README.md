# Μάθημα: Επικοινωνία Ανθρώπου Υπολογιστή

### Ονοματεπώνυμο: Μάριος Κωνσταντίνου
### Αριθμός Μητρώου: Π2015002
### GitHub Profile: [mariosconsta] - https://github.com/mariosconsta
<br />

## Πίνακας με σύνοψη των παραδοτέων

| Εβδομάδα* | Παραδοτέο |
| --- | --- |
| 1 | [Εισαγωγή + Σύνοψη] |
| 2 | [Άσκηση προγραμματισμού: Mouse Eraser] |
| 3 | [Άσκηση γραμμής εντολών: Set-up the main dependencies and demonstrate your base system] |
| 4 | [Συμμετοχικό περιεχόμενο: Α1] |
| 5 | [Άσκηση προγραμματισμού: Mouse Option] |
| 6 | [~~Συμμετοχικό περιεχόμενο: Α2~~] |
| 7 | [Άσκηση γραμμής εντολών: Download MP3] |
| 8 | [~~Συμμετοχικό περιεχόμενο: Β1~~] |
| 9 | [Άσκηση γραμμής εντολών: Organise todo list] |
| 10 | [~~Συμμετοχικό περιεχόμενο: Β2~~] |
| 11 | [Άσκηση γραμμής εντολών: Organise the Terminal Window into Multiple Areas] |
| 12 | [Επίλογος] |

# ΕΙΣΑΓΩΓΗ
Αυτή είναι η τελική αναφορά για το μάθημα Επικοινωνία Ανθρώπου Υπολογιστή του Γ΄ εξαμήνου. Τα παραδοτέα βρίσκονται στον παραπάνω πίνακα. Για τις ασκήσεις γραμμής εντολών χρησιμοποίησα το πρόγραμμα VirtualBox και εγκατέστησα το Ubuntu.

# ΣΥΝΟΨΗ
Η τελική εργασία αποτελείτε από 10 παραδοτέα. Δύο ασκήσεις προγραμματισμού, 4 ασκήσεις γραμμής εντολών σε Linux και 4 ασκήσεις συμμετοχικού υλικού. Τις ασκήσεις συμμετοχικού υλικού δεν κατάφερα να τις ολοκληρώσω λόγο χρόνου και παράλληλα δεν μπορούσα να κατανοήσω πως ακριβός να τις κάνω. Τα υπόλοιπα παραδοτέα έγιναν και φαίνονται αναλυτικά παρακάτω με links σε Asciinema, CodePen, GitHub και gifs/εικόνες.

# 2ο Παραδοτέο - Mouse Eraser

Για το δεύτερο παραδοτέο επέλεξα την άσκηση Mouse Eraser. Στο παράδειγμα του κώδικα, χρησιμοποιούμε το ποντίκι ως eraser. Υπάρχουν δύο εικόνες όπου η μία κάνει overlap με την άλλη. Όταν μετακινούμε το κέρσορα πάνω από την εικόνα που φαίνεται πρώτη, τότε αυτή η εικόνα διαγράφεται και ξεκίνα να εμφανίζεται η δεύτερη εικόνα. Το ζητούμενο της άσκησης είναι να αλλάξουμε μία από τις δύο εικόνες αλλά και το μέγεθος του eraser.


<p align="center">
<img src="https://i.imgur.com/Oqbx1NT.png">
</p>

Το πρώτο ζητούμενο ήταν να αλλάξω μία από τις δύο φωτογραφίες. Επέλεξα να αλλάξω και τις δύο. Πρώτα άλλαξα τον HTML κώδικα και συγκεκριμένα το src στο <img> function όπου έβαλα το URL της φωτογραφίας που επέλεξα να φαίνεται μετά την διαγραφή, ουσιαστικά η εικόνα που φαίνεται μετά την διαγραφή είναι το background. Παράλληλα άλλαξα το width και το height για να ταιριάζει με την φωτογραφία που βρήκα. Τέλος άλλαξα στο width και το height στον καμβά όπου έβαλα τις ίδιες διαστάσεις με την φωτογραφία για να είναι η μία φωτογραφία ακριβός πάνω από την άλλη. <br />

Στην συνέχεια έκανα το ίδιο πράγμα στο JavaScript κομμάτι. Άλλαξα το URL της φωτογραφίας στο img.src και μετά τις διαστάσεις για να ταιριάζουν με αυτές της φωτογραφίας.
Με αυτές τις αλλαγές κατάφερα να έχω δύο διαφορετικές εικόνες.


<p align="center">
<img src="https://i.imgur.com/JStw2xy.png">
</p>
Παράλληλα στο JavaScript κομμάτι της άσκησης άλλαξα μερικά πράγματα στο drawPoint function. Αυτό που παρατήρησα είναι πως το drawPoint είναι ουσιαστικά ο eraser. Αύξησα το μέγεθος στο ctx. και στο arc. κατά 25 πόντους (από 50 έγινε 75).


#### Τα αποτελέσματα μετά τις αλλαγές μου φαίνονται στο παρακάτω animated gif:
<p align="center">
<img src="https://i.imgur.com/LXrKdWA.gif" width="720px">
</p>

#### Link της άσκησης: [MouseEraser P2015002](https://codepen.io/P2015002/pen/LYLpJQB)


# 3ο Παραδοτέο - Set-up the main dependencies and demonstrate your base system

Ως πρώτη εργασία γραμμής εντολών επέλεξα να πραγματοποιήσω την εργασία που ζητούσε να εγκαταστήσω τα βασικά dependencies και να δείξω τα χαρακτηριστικά του συστήματος μου. Όλα μέσα από το terminal των Ubuntu.

#### Chaning my hostname to my AM: https://asciinema.org/a/433020 <br />
#### List of my Dot Files:  https://asciinema.org/a/433025 <br />
#### Showing Shell Config Files:  https://asciinema.org/a/433026 <br />
#### Showing System Config:  https://asciinema.org/a/433027 <br />

#### Η εργασία ουσιαστικά ζητούσε τα παρακάτω πράγματα:

### 1. Αλλαγή  του ονόματος μας με τον αριθμό μητρώου μας
Να αλλάξουμε το username μας με τον ΑΜ μας. Αυτό ήταν σχετικά εύκολο. Κόλλησα στο σημείο που έπρεπε να βάλουμε sudo μπροστά  από την εντολή. Κατάλαβα ότι το sudo παρέχει στον χρήστη Admin Permissions και για αυτό τον λόγο μου ζητήθηκε Password. Βέβαια αφού χρησιμοποίησα την εντολή το hostname δεν άλλαξε. Με λίγη αναζήτηση online έμαθα πως έπρεπε να κάνω restart το terminal.  <br />

### 2. να προβάλουμε την λίστα τα dot files μας
Για να βρω τα .dot files χρησιμοποίησα 2 εντολές. Η πρώτη ήταν «ls –ld  .?*» η οποία εμφάνιζε μόνο τα κρυμμένα αρχεία και η δεύτερη ήταν «ls -a» η οποία εμφάνιζε όλα τα αρχεία.  

### 3. να προβάλουμε το shell configuration file
Σε αυτό το ζητούμενο χρησιμοποίησα δύο εντολές. Την «nano ~/.bashrc» και την «nano /etc/profile».

### 4. να προβάλουμε πληροφορίες για το σύστημα μας (hardware και software)
Σε αυτό το ζητούμενο χρησιμοποίησα δύο εντολές. Την « sudo lshw -short» και την «sudo lshw». 

#### Προβλήματα που χρειάστηκε να επιλυθούν μέχρι την εκτέλεση:

Τα προβλήματα που αντιμετώπισα ήταν ότι μπερδεύτηκα αρκετά με τα .dot files. Online μου έβγαζε αρκετές εντολές που έδειχναν άλλα αρχεία αντί τα .dot files. Η εντολή lshw με δυσκόλεψε λίγο διότι έχει αρκετές παραμέτρους που έκαναν όλες κάτι διαφορετικό.
Τέλος μια γενική δυσκολία που είχα ήταν να κάνω το Virtual Box να δουλέψει. Έπρεπε να αλλάξω πράγματα στα BIOS του υπολογιστή μου, να αλλάξω τον αριθμό των διαθέσιμων processors και τον αριθμό της διαθέσιμης γραφικής μνήμης. Χωρίς αυτές τις αλλαγές δεν έκαναν boot τα ubuntu. Παράλληλα ήθελα κάποιο χρόνο να εξοικειωθώ με το καινούριο λογισμικό και το terminal.

### Συνδέσμοι πηγών:
[How do I change the hostname?](https://phoenixnap.com/kb/ubuntu-20-04-change-hostname) |
[How to show only hidden files in Terminal?](https://askubuntu.com/questions/468901/how-to-show-only-hidden-files-in-terminal) |
[Bash Shell: Display All Hidden Dot Files In a Directory](https://www.cyberciti.biz/faq/bash-shell-display-only-hidden-dot-files/) |
[Linux Commands for Beginners 07 - The Bash Configuration File](https://www.youtube.com/watch?v=esNITi0RkPE) |
[How do I check system specifications?](https://askubuntu.com/questions/55609/how-do-i-check-system-specifications) |
[Linux lshw Command](https://linuxhint.com/use-linux-lshw-command) |

# 4ο Παραδοτέο - Συμμετοχικό περιεχόμενο: Α1
Σαν χόμπι έχω τα video games και για αυτό ήθελα να βρω κάτι σε αυτή την ενότητα. Η πρώτη εικόνα που βρήκα είναι η πρώτη κονσόλα για video games που δημιουργήθηκε το 1972 με όνομα Magnavox Odyssey!<br />

https://github.com/mariosconsta/_gallery/blob/master/First-generation-of-video-game-consoles.md<br />

Η δεύτερη εικόνα είναι το Xbox adaptive controller της Microsoft το οποίο είναι ένα εξαιρετικό εργαλείο για άτομα με ειδικές ανάγκες που θέλουν να παίξουν παιχνίδια.<br />

https://github.com/mariosconsta/_gallery/blob/master/Xbox-Adaptive-Controller.md

# 5ο Παραδοτέο - Mouse option

Για το επόμενο παραδοτέο επέλεξα την Mouse Option άσκηση. Η άσκηση περιέχει ένα παράδειγμα κώδικα ο οποίος επιτρέπει στον χρήστη να αλλάξει το περιεχόμενο της σελίδας. Το ζητούμενο είναι να αλλάξουμε τον κώδικα του παραδείγματος με αποτέλεσμα να υπάρχουν περισσότερες επιλογές στην φόρμα. <br />

Αρχικά παρατήρησα στον κώδικα πως υπάρχει η γραμμή «<option value="content2">Περιεχόμενο 2</option>». Εκεί κατάλαβα αμέσως πως η γραμμές αυτές καθορίζουν τις επιλογές του drop down menu. Πρόσθεσα μία ακόμη επιλογή και άλλαξα τα ονόματα όλων των επιλογών. Διαβάζοντας τον κώδικα πιο κάτω κατάλαβα πως ήταν το κομμάτι για το content της σελίδας.

<p align="center">
<img src="https://i.imgur.com/Cym6IGO.png" width="460px">
</p>

Στην συνέχεια άλλαξα το κείμενο της πρώτης επιλογής και πρόσθεσα ένα λίνκ. Έπειτα με λίγο ψάξιμο βρήκα πως βάζεις εικόνες σε html και πρόσθεσα δύο εικόνες στην δεύτερη επιλογή του μενού. Τέλος προσπάθησα να βάλω βίντεο και εκεί αντιμετώπισα ένα πρόβλημα. Ο player του Youtube μου έβγαζε ένα error. «www.youtube.com refused to connect». Μετά από λίγο ψάξιμο έμαθα πως πρέπει να κάνω embed το video με διαφορετικό URL.

<p align="center">
<img src="https://i.imgur.com/Uc8RXQW.png" width="460px">
</p>

#### Link της άσκησης: [Mouse Option](https://codepen.io/P2015002/pen/eYRJwvo)

## Xρήσιμοι συνδέσμοι σχετικά με το παραδοτέο:
[w3 schools](https://www.w3schools.com/html/)
[YouTube Refused to Connect](https://forum.freecodecamp.org/t/youtube-refused-to-connect/245262)<br />

# 7ο Παραδοτέο - Download mp3

Για την επόμενη εργασία γραμμής εντολών επέλεξα αυτήν που ήθελε να κάνουμε search στο YouTube, να κατεβάσουμε το τραγούδι και στην συνέχεια να το παίξουμε σε ενάν player. Μετά από πάρα πολύ ώρα βρήκα το εργαλείο ytfzf.<br/>

Έκανα install όλα τα dependencies με την εντολή sudo apt install <dependence name>, άλλαξα το working directory για το κατέβασμα των τραγουδιών, χρησιμοποίησα την εντολή ytfzf -d, μετά έγραψα Tash για να βρω το αγαπημένο μου τραγούδι και να το κατεβάσω στο working directory που έβαλα (/home/Marios/Deskstop/Music).<br/>

#### Asciinema link:  [Παραδοτέο 7](https://asciinema.org/a/433601)<br />

#### Η εργασία ουσιαστικά χωρίζετε στα εξής βήματα:

### 1. Αναζήτηση του τραγουδιού στο YouTube
Η αναζήτηση ήταν σχετικά εύκολη δεδομένου ότι το ytfzf εγκαταστάθηκε σωστά. Απλά γράφουμε ytfzf και μετά σε κάνει promt να γράψεις τι θα ήθελες να κάνει search. Στην συνέχεια αφού κάνεις την αναζήτηση σου βγάζει διάφορες επιλογές, διαλέγεις το κομμάτι σου και πατάς enter για αναπαραγωγή.<br/>

Θα αναφέρω πολλά προβλήματα που είχα με την αναζήτηση στο τέλος.

### 2. Κατέβασμα του τραγουδιού από το YouTube σε μορφή mp3
Το κατέβασμα είναι σχεδόν το ίδιο με την αναζήτηση. Στην αρχή για αναζήτηση γράψαμε ytfzf, τώρα για το κατέβασμα πρέπει να προσθέσουμε -d στο τέλος. Δηλαδή ytfzf -d.
Στην συνέχεια όπως και πριν, γράφουμε αυτό που θέλουμε να κατεβάσουμε και μας βγάζει μία λίστα από επιλογές. Διαλέγουμε το τραγούδι και ξεκινάει το κατέβασμα.<br/>

Θα ήθελα να σημειώσω δύο πράγματα. Το ytfzf χρησιμοποιεί το youtube-dl για το κατέβασμα. Για να μπορέσω να κατεβάσω ένα βίντεο έπρεπε πρώτα να γράψω sudo apt install youtube-dl. Έπειτα έπρεπε να αλλάξω το working directory του terminal έτσι ώστε το τραγούδι να κατέβει στο φάκελο που ήθελα και όχι στο default.

### 3. Αναπαραγωγή του τραγουδιού από το terminal
Η αναπαραγωγή του τραγουδιού ήταν σχετικά εύκολη. Χρειάστηκα δύο πράγματα. MPV και Mplayer. Αφού τα κατέβασα, έπρεπε να αλλάξω το working directory του terminal με την εντολή cd /home/Marios/Deskstop/Music. Για να βεβαιωθώ ότι είμαι στο σωστό directory έγραψα την εντολή pwd η οποία μου κάνει print το working directory του terminal. Στην συνέχεια έγραψα την εντολή ls η οποία που κάνει print τα contents του directory. Στον φάκελο είχα μόνο το τραγούδι που κατέβασα και έτσι για αναπαραγωγή έγραψα "mplayer 'όνομα αρχείου'". Πάτησα enter και ξεκίνησε το τραγούδι να παίζει. Στο asciinema δεν φαίνεται το βίντεο αλλά φαίνεται η αναπαραγωγή από το terminal.

### Προβλήματα που χρειάστηκε να επιλυθούν μέχρι την εκτέλεση:
Προβλήματα είχα πολλά. Αρχικά προσπάθησα να αναζητήσω τραγούδι με το εργαλείο ytp. Το API δεν ήθελε να συνεργαστεί και διάβασα πως πρέπει να κάνω δικό μου API μέσο Google Console. Το έκανα αλλά και πάλι, μου έβγαζε άλλα errors. Στην συνέχεια δοκίμασα το εργαλείο youtube-viewer αλλά και πάλι τίποτα, μετά από το youtube-viewer δοκίμασα ακόμη ένα εργαλείο αλλά και πάλι κάτι δεν του άρεσε. Τέλος βρήκα το ytfzf και κατάφερα να κάνω την αναζήτηση μου. Το άλλο πρόβλημα που είχα ήταν πως δεν ήξερα ότι έπρεπε να αλλάξω το directory του terminal για να κατέβει το τραγούδι εκεί που ήθελα. Έψαξα λίγο και έμαθα για τις εντολές cd, pwd και ls. Τέλος, το τελευταίο πρόβλημα που είχα ήταν τα errors που έβγαζε το ytfzf. Η λύση ήταν να δω αν είναι εγκατεστημένο το python3 με την εντολή whereis python3. Ήταν εγκατεστημένο, στην συνέχεια έπρεπε να δημιουργήσω ένα symlink με την εντολή sudo ln -s /usr/bin/python3 /usr/bin/python.

### Εργαλεία που χρησιμοποίησα:
ytfzf, youtube-dl, mpv, mplayer

### Συνδέσμοι πηγών:
[ytfzf - Search (With Thumbnails) And Play YouTube Videos From A Terminal](https://www.linuxuprising.com/2021/03/ytfzf-search-with-thumbnails-and-play.html) |
[youtube-dl](https://github.com/ytdl-org/youtube-dl) |
[ytfzf](https://github.com/pystardust/ytfzf) |
[How To Play Video From The Terminal In Linux With Mplayer](https://www.youtube.com/watch?v=D1lGmif0w94) |
[How to change directory in Linux terminal](https://www.cyberciti.biz/faq/how-to-change-directory-in-linux-terminal/) |
[mplayer](https://github.com/philipl/mplayer) |
[mpv](https://github.com/mpv-player/mpv) |
[ubuntu /usr/bin/env: python: No such file or directory](https://stackoverflow.com/questions/3655306/ubuntu-usr-bin-env-python-no-such-file-or-directory/61608129?fbclid=IwAR2Jah5CiPubxsJW2HsH3Td1LvLRTtSLNPZ9-Wv3QpzCbSUKBhrrjcbQ4T0) |

# 9ο Παραδοτέο - Organise todo list
Για την επόμενη άσκηση προγραμματισμού αποφάσισα να οργανώσω τις σημειώσεις μου με το emacs. <br/>
  
Αρχικά εγκατέστησα το emacs γράφοντας sudo apt-get install emacs, άφησα το terminal να κάνει τα δικά του και σε μερικά δευτερόλεπτα ήταν έτυμο.
Στην συνέχεια, άνοιξα το emacs και δημιούργησα ένα αρχείο todo.org . Επειδή έβαλα .org στο τέλος, αυτόματα το αρχείο θα είναι σε org mode.
Έπειτα άρχισα το γράψιμο της λίστας μου. Γενικά δεν ήμουν/είμαι καθόλου εξοικειωμένος με το emacs. Χρειάστηκα αρκετή εξάσκηση για να μάθω τα hot keys και πολύ διάβασμα του manual/documentation. <br/>
  
##Προβλήματα δεν αντιμετώπισα
Η εγκατάσταση πήγε ομαλά και η λίστα δημιουργήθηκε χωρίς κανένα θέμα. Στο μόνο σημείο που κόλλησα ήταν στο ότι αν έγραφα emacs άνοιγε GUI αντί στο terminal με αποτέλεσμα το asciinema να μην μπορεί να το κάνει record. Αυτό το έλυσα με την προσθήκη του -nw (emacs -nw) που ουσιαστικά λέει στο emacs να ανοίξει χωρίς παράθυρο. Παράλληλα έπρεπε να γράψω κάπου τα hotkeys διότι ήταν αρκετά και δεν μπορούσα να τα αποστηθίσω.


#### Asciinema link: [Παραδοτέο 9](https://asciinema.org/a/433950)<br />

### Εργαλεία που χρησιμοποίησα:
emacs

### Συνδέσμοι πηγών:
[Emcas Documentation](https://www.gnu.org/software/emacs/documentation.html) |
[The Emacs Editor](https://www.gnu.org/software/emacs/manual/html_node/emacs/index.html) |
[Running Shell Commands from Emacs](https://www.gnu.org/software/emacs/manual/html_node/emacs/Shell.html) |
[How to open Emacs inside Bash](https://stackoverflow.com/questions/8746227/how-to-open-emacs-inside-bash) |

# 11ο Παραδοτέο - Άσκηση γραμμής εντολών

Για την τελευταία άσκηση γραμμής εντολών επέλεξα να κάνω αυτήν που ζητούσε να χωρίσουμε το terminal σε πολλαπλά παράθυρα. Για την εργασία θα χρησιμοποιήσω το tmux το οποίο εγκατέστησα με την εντολή sudo apt-get install tmux. Παράλληλα κατέβασα το glances για να κάνω monitor τον υπολογιστή μου. 
Αφού εγκατέστησα όλα τα εργαλεία ξεκίνησα με το tmux γράφοντας tmux στο terminal. Έπειτα χρησιμοποίησα τα hotkeys CTRL + b και μετά “ ή % για να διαχωρίσω τα παράθυρα. Επέλεξα το τέρμα δεξία παράθυρο με το hotkey CTRL + b και μετά το δεξιά βελάκι. Έγραψα glances για να ξεκινήσει το monitoring program και έπειτα με τον ίδιο τρόπο πήγα στο αριστερά παράθυρο και να παίξω ένα βίντεο στο YouTube. Βέβαια το asciinema κάνει record μόνο το terminal αλλά φαίνεται από το buffering πως γίνετε αναπαραγωγή. Τέλος ήθελα να παίξω και ένα τραγούδι που είχα κατεβασμένο από μια άλλη εργασία και δημιούργησα ακόμη ένα παράθυρο στο terminal με τα ίδια hotkeys. Όπως είπα πριν, το βίντεο δεν φαίνεται αλλά φαίνεται το buffering. <br />

#### Asciinema link: [Παραδοτέο 11](https://asciinema.org/a/433960)<br />
  
### Συνδέσμοι πηγών:
[Tmux Command Examples To Manage Multiple Terminal Sessions](https://ostechnix.com/tmux-command-examples-to-manage-multiple-terminal-sessions/) |
[Glances - An eye on your system](https://github.com/nicolargo/glances) |
[Glances - Quickstart](https://glances.readthedocs.io/en/latest/quickstart.html) |


# ΕΠΙΛΟΓΟΣ
Μου άρεσαν αρκετά οι εργασίες του μαθήματος. Το μάθημα σου δίνει την επιλογή να διαλέξεις ποιες εργασίες θες να κάνεις για το κάθε παραδοτέο και έχει εργασίες για κάθε level. Παράλληλα δεν είχα την ευκαιρία μέχρι τώρα να έρθω σε επαφή με το Linux και το GitHub και μπορώ να πω πως τα βρήκα πάρα πολύ ωραία και χρήσιμα εργαλεία (ειδικά το GitHub). 
