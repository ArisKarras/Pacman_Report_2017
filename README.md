<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26778214/06444900-49e9-11e7-8db9-b6a4d1c05c6c.png">
</p>

# Τεχνολογία Λογισμικού - Τελική Αναφορά

# 	Εισαγωγή
*	**Ονοματεπώνυμο:** Αριστείδης Καρράς
*	**Αριθμός Μητρώου:** Π2013020
*	**Θέμα εργασίας:** "Δημιουργία Pacman"
*	**[Προσωπικό αποθετήριο κώδικα](https://github.com/ArisKarras/pacman "Aris's Repository")**
*	**[Εκτελέσιμο](https://ariskarras.github.io/pacman/pacman.html "Aris's Pacman")**

# Σύνοψη
 Στα πλαίσια του μαθήματος **Τεχνολογία Λογισμικού** εκπονήθηκε η παρούσα εργασία από τον **Αριστείδη Καρρά (Π2013020)** κατά το έτος 2016-2017, η οποία σχετίζεται με την δημιουργία ενός παιχνιδιού PacMan σε HTML5 με την βοήθεια της βιβλιοθήκης Phaser. Όντας λάτρης και υποστηρικτής των ταινιών Star Wars, εμπνεύστηκα και πήρα την απόφαση η εργασία μου να βασιστεί, σχεδιαστεί αλλά και να αναπτυχθεί πάνω στις ταινίες αυτές. Όλα τα παραδοτέα και τα απαιτούμενα της εργασίας υλοποιήθηκαν και παραδόθηκαν εγκαίρως, εντός της εκάστοτε δοσμένης προθεσμίας. 
 
Εν συντομία, ο κύριος πρωταγωνιστής του παιχνιδιού είναι ο Luke Skywalker ο οποίος απεικονίζεται στο παιχνίδι να κρατάει το blue lightsaber του, ο εχθρός του ο Darth Vader ( αποτελεί και έναν από τους κακούς στην ταινίες Star Wars) ο οποίος απεικονίζεται στο παιχνίδι να κρατάει το red lightsaber του  και αντί για dots ο παίκτης συλλέγει κρυστάλλους (crystals), όπου στις ταινίες με την βοήθεια τους γίνεται η παρασκευή των lightsabers. Ο πρωταγωνιστής γίνεται ανίκητος για 10 δευτερόλεπτα και μπορεί να κερδίσει τους κακούς, εάν συλλέξει το bonus, το οποίο απεικονίζεται από 2 συγκρουόμενα lightsabers (Blue lightsaber & Red lightsaber). Ενώ, εάν δεν το συλλέξει οι κακοί μπορούν να τον εξουδετερώσουν. Επίσης, σχεδίασα και δημιούργησα μια τελείως διαφορετική πίστα με ενδιαφέρουσες αλλαγές. Επιπροσθέτως, να αναφέρω ότι έχω προσθέσει 3 είδη ήχων βασισμένα αποκλειστικά στις ταινίες.  

Τέλος, να αναφέρω ότι περισσότερες πληροφορίες σχετικά με το παιχνίδι παρουσιάζονται σε επόμενες ενότητες.

# Ροή Παραδοτέων 
Παραθέτω την ροή παραδοτέων της εργασίας για τους εξής λόγους:
1. Ότι όλα τα προαπαιτούμενα και τα deadline της εργασίας τηρήθηκαν με συνέπεια.
2. Να είναι εμφανής η σταδιακή εξέλιξη του παιχνιδιού.
3. Να γίνει πιο εύκολα αντιληπτή η συνολική συνεισφορά της εργασίας μου.

**Aρχικός σχεδιασμός εφαρμογής:**
### Ζητούμενα:
  *	Αντί για τον Pacman χρησιμοποίησε έναν άλλο χαρακτήρα για πρωταγωνιστή του παιχνιδιού.
  *	Αντί ο πρωταγωνιστής να μαζεύει μόνο dots θα μπορούσε να μαζεύει διάφορα αντικείμενα (κέρματα, λουλούδια, φρούτα κτλ).
  *	Δημιούργησε μια νέα πίστα για το παιχνίδι χρησιμοποιώντας το Tiled.

### Υλοποίηση:
  * Αντικατέστησα τον χαρακτήρα του Pacman με τον βασικό χαρακτήρα/πρωταγωνιστή **Luke Skywalker** των ταινιών **Star Wars**.
  <p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609011/579a84fe-45a7-11e7-8d5a-44459a5c6d66.png">
  </p>
  
  * Πλέον, ο πρωταγωνιστής του παιχνιδιού δεν μαζεύει dots, αλλά μαζεύει κρυστάλλους (crystals), όπως και στις ταινίες **Star Wars** όπου με την βοήθεια τους γίνεται και η παρασκευή των **lightsabers**. Παρόλα αυτά, επέλεξα για λόγους καλαισθησίας ο **Luke** να κρατάει ήδη το **blue lightsaber** του, αλλά να μην μπορεί να νικήσει ακόμα τους εχθρούς χωρίς την κατάλληλη συλλογή άλλων items (τα οποία θα προστεθούν στα επόμενα Παραδοτέα).    

  <p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609036/78cd5764-45a7-11e7-98d3-c39f39b7de08.png">
  </p>
  
  * Δημιούργησα μια νέα πίστα με βάση την πίστα που υπήρχε στον φάκελο assets.
  
 <p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609060/9a6bb15e-45a7-11e7-8b71-e64e80445cf9.png">
 </p>

### Αποτέλεσματα:
  * Τέλος παραθέτω ένα τελικό screenshot του παιχνιδιού, με βάση τις προδιαγραφές του 2ου Παραδοτέου.

<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609076/b6931e08-45a7-11e7-8562-800b112118ad.png">
</p>

**Τελικό προσχέδιο έργου για σχολιασμό και βελτιώσεις:** 
### Ζητούμενα:
  * Προσθήκη αντικειμένου που εμφανίζεται και μετά από κάποιο χρονικό διάστημα εξαφανίζεται.
  * Προσθήκη score, bonus και ζωών.
  * Προσθήκη ήχων.
  
### Υλοποίηση:
  * Πρόσθεσα έναν κόκκινο σταυρό ως το αντικείμενο που εμφανίζεται και εξαφανίζεται μετά από κάποιο χρονικό διάστημα. 
<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609086/ca62bc40-45a7-11e7-9ad5-2ba0d3cd29f5.png">
</p>

  * Πρόσθεσα **Score** στο παιχνίδι, όπου αυξάνεται κατά 10 πόντους, όταν ο παίκτης μαζέψει έναν κρύσταλλο. 
  * Πρόσθεσα το **Bonus**, όπου απεικονίζεται από 2 συγκρουόμενα **lightsabers** (**Blue lightsaber** & **Red lightsaber**). Το **Bonus** αυξάνεται επίσης κατά 10 πόντους, όταν ο παίκτης συλλέξει το συγκεκριμένο αντικείμενο. Επίσης, επέλεξα οι πόντοι του **Bonus**, να προστίθενται και στο συνολικό **Score**.
<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609112/0650bd06-45a8-11e7-90de-1afa605e01a7.png">
</p>

  * Πρόσθεσα επίσης 3 ζωές, οι οποίες θα αποκτήσουν λειτουργικότητα με το επόμενο παραδοτέο.
<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609124/171cdc46-45a8-11e7-8bf0-377afb030657.png">
</p>

  * Τέλος, όσον αφορά τους ήχους, έχω επιλέξει 3 διαφορετικούς.
    1. Επέλεξα το κλασσικό theme song του **Star Wars** να παίζει σε όλη την διάρκεια του παιχνιδιού.
    2. Επέλεξα, όταν συλλέγεται ένας κρύσταλλος, να αναπαράγεται ένας κλασσικός ήχος από **lightsabers**.
    3. Και τέλος, και όταν γίνεται συλλογή του **Bonus**, να αναπαράγεται ένας κλασσικός ήχος από **Blasters**(τύπος όπλου) βασισμένα στην ταινία.  
  * Επίσης, πρόσθεσα φωτογραφία στο background του παιχνιδιού που μοιάζει με διάστημα.
 
### Αποτέλεσματα:
  
<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609133/291348fe-45a8-11e7-8a34-c6cd271086ba.png">
</p>

**Τελικό Έργο:** 
### Ζητούμενα:
  * Προσθήκη εχθρών.
  * Αντιμετώπιση εχθρών με την συλλογή του κατάλληλου αντικειμένου.
  * Δυνατότητα teleport για τον πρωταγωνιστή σε συγκεκριμένα σημεία της πίστας.
  
### Υλοποίηση: 
  * Βασισμένος στις ταινίες Star Wars, επέλεξα να εισάγω για εχθρό τον **Darth Vader** που στην πραγματικότητα αποτελεί έναν από τους κακούς χαρακτήρες των ταινιών. Συγκεκριμένα, επέλεξα 5 φορές να εμφανίζεται ο **Darth Vader** στο παιχνίδι.
 <p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26828915/1a55a216-4acc-11e7-9e2c-be37494a8c60.png">
</p>

  * Ο χαρακτήρας με την συλλογή του Bonus, γίνεται ανίκητος για 10 δευτερόλεπτα και μπορεί να εξουδετερώσει τους εχθρούς του παιχνιδιού.
  
  * Παρέχεται δυνατότητα **teleport** για τον πρωταγωνιστή του παιχνιδιού, όταν έρθει σε επαφή με το παρακάτω πράσινο εικονίδιο:
   <p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26829001/7aa029a2-4acc-11e7-93e5-c4fd07dcdb8a.png">
</p>

  * Τέλος πρόσθεσα το χρονόμετρο στο παιχνίδι και άλλαξα την θέση του Score, του Bonus και των ζωών, μεταφέροντας τα σε μια πιο responsive θέση.
  
# Τελικά Αποτελέσματα - Ενδεικτικές Εικόνες:

<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26828970/57d212fa-4acc-11e7-83a2-fa6639b96c07.png">
</p>

<p align="center">
      <img src="https://user-images.githubusercontent.com/17282953/26849264-29f5d714-4b0c-11e7-93dd-dd49ddfe6cc3.png">
</p>

# Διαδικασία Ανάπτυξης
  * Αρχικά, άλλαξα τον χαρακτήρα του παιχνιδιού και στην θέση του Pacman, επέλεξα να βάλω έναν από τους κύριους πρωταγωνιστές των ταινιών Star Wars, τον **Luke Skywalker**, ο οποίος απεικονίζεται στο παιχνίδι να κρατάει το blue lightsaber του.
  * Στην συνέχεια, αντικατέστησα τα dots με τους κρυστάλλους και δημιούγησα μια νέα πίστα με το Tiled.
  * Πρόσθεσα το Score στο παιχνίδι, το οποίο αυξάνεται κατά 10 μονάδες με την συλλογή ενός κρυστάλλου.
  * Πρόσθεσα έναν σταυρό ως αντικείμενο που εμφανίζεται και εξαφανίζεται μετά από κάποιο χρονικό διάστημα.
  * Έπειτα τοποθέτησα ζωές στο παιχνίδι όπου αρχικά οι ζωές του παίκτη είναι τρεις (3) και κάθε φορά που εξουδετερώνεται, μειώνεται κατά μία.
  * Μετέπειτα, έγινε προσθήκη του Bonus στο παιχνίδι, το οποίο απεικονίζεται από 2 συγκρουόμενα lightsabers (Blue lightsaber & Red lightsaber). Το Bonus αυξάνεται κατά δέκα (10) μονάδες και προστίθενται στο συνολικό Score.
  * Πρόσθεσα τρεις (3) διαφορετικούς ήχους στο παιχνίδι. Επέλεξα το κλασσικό theme song του Star Wars να παίζει σε όλη την διάρκεια του παιχνιδιού. Όταν συλλέγεται ένας κρύσταλλος, να αναπαράγεται ένας κλασσικός ήχος από lightsabers. Και τέλος, όταν γίνεται συλλογή του Bonus, να αναπαράγεται ένας κλασσικός ήχος από Blasters(τύπος όπλου) βασισμένα στην ταινία.
  * Πρόσθεσα φωτογραφία στο background του παιχνιδιού που μοιάζει με διάστημα.
  *  Στην συνέχεια, έγινε προσθήκη των εχθρών, και συγκεκριμένα του **Darth Vader**,  ο οποίος απεικονίζεται στο παιχνίδι να κρατάει το red lightsaber του. Επέλεξα, να εμφανίζεται πέντε (5) φορές ο εχθρός στο παιχνίδι. Και φυσικά, εάν ο πρωταγωνιστής δεν συλλέξει το Bonus, δεν μπορεί να κερδίσει του εχθρούς. Αντιθέτως, οι εχθροί μπορούν να εξουδετερώσουν τον **Luke**.
  * Έγινε προσθήκη χρονομέτρου και εισήχθη δυνατότητα teleport για τον χαρακτήρα του παιχνιδιού, όταν έρθει σε επαφή με το πράσινο εικονίδιο.
  * Έδωσα την δυνατότητα στον χαρακτήρα του παιχνιδιού, να γίνεται ανίκητος για δέκα (10) δευτερόλεπτα και να μπορεί να εξουδετερώσει τους εχθρούς, με την συλλογή του Bonus.
  * Το εργαλείο που χρησιμοποιήθηκε για την επεξεργασίας των εικόνων είναι το **[PicMonkey](https://www.picmonkey.com/)**.
  * Το εργαλείο που χρησιμοποιήθηκε για την επεξεργασίας των ήχων είναι το **[Mp3 Cutter](http://mp3cut.net/)**.

# Μελλοντικές Επεκτάσεις
 1. Προσθήκη περισσότερων πιστών.
 2. Προσθήκη Levels (πχ. Easy-Medium-Hard).
 3. Προσθήκη μετρητή υψηλότερου σκόρερ και αποθήκευση.
 4. Προσθήκη περισσότερων εχθρών.
 5. Προσθήκη περισσότερων ήχων.
 6. Προσθήκη αποστολών τις οποίοες θα πρέπει ο παίκτης να ολοκληρώσει για την επιβίωση του.
 7. Προσθήκη περισσότερων αντικειμένων βασισμένων στις ταινίες Star Wars.
 
# Συμπεράσματα
Το θέμα της εργασίας και το συμπληρωματικό περιεχόμενο του διδάσκοντα του μαθήματος κ. [Κωνσταντίνο Χωριανόπουλο](https://github.com/epidrome) ήταν οι αιτίες για ένα αρκετά εποικοδομητικό, δημιουργικό και πολύ ενδιαφέρων τρόπο ενασχόλησης με τη γλώσσα HTML5, τη βιβλιοθήκη Phaser, την πρακτική πάνω στην πλατφόρμα ανοιχτού κώδικα Github αλλά κυρίως με τον "κόσμο" της Τεχνολογίας Λογισμικού. 

Tέλος, το τελικό περιεχόμενο του παιχνιδιού, είναι ανεπτυγμένο σε μεγάλο βαθμό, καλύπτει/πληρεί όλα τα ζητούμενα της εκφώνησης και θεώρώ ότι είναι μια καλή συνεισφορά στο υλικό του μαθήματος και όχι μόνο. Καθώς επίσης, είναι αρκετά εξελίξιμο και πολλοί μπορούν να βασιστούν πάνω σε αυτό για την δημιουργία περισσότερων εκδόσεων Pacman.

# Αναφορές
1. **[Γραφικά Χαρακτήρα Παιχνιδιού](https://gr.pinterest.com/pin/137148751122666263/)**
2. **[Γραφικά Εχθρού](http://tsgk.captainn.net/index.php?p=search&q=darth+vader)**
3. **[Γραφικά Κρυστάλλων](http://finalfantasy.wikia.com/wiki/File:FFI_PSP_Crystal.png)**
4. **[Γραφικά Σταυρού](http://www.purezc.net/index.php?page=tiles&id=592)**
5. **[Γραφικά Bonus](http://www.purezc.net/index.php?page=tiles&id=592)**
6. **[Γραφικά Ζωών](http://makepixelart.com/peoplepods/files/images/12067.resized.png)**
7. **[Γραφικά αντικειμένου Teleporting](http://www.purezc.net/index.php?page=tiles&id=592)**
8. **[Κύριος Ήχος Παιχνιδιού](http://www.soundboard.com/sb/starwars)**
9. **[Ήχος Συλλογής Κρυστάλλων - Lightsabers](http://www.soundboard.com/sb/starwars)**
10. **[Ήχος Συλλογή Bonus- Blasters](http://www.soundboard.com/sb/starwars)**
