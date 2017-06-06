<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26778214/06444900-49e9-11e7-8db9-b6a4d1c05c6c.png">
</p>

# Τεχνολογία Λογισμικού 

# 	Εισαγωγή
*	**Ονοματεπώνυμο:** Αριστείδης Καρράς
*	**Αριθμός Μητρώου:** Π2013020
*	**Θέμα εργασίας:** "Δημιουργία Pacman"
*	**[Προσωπικό αποθετήριο κώδικα](https://github.com/ArisKarras/pacman "Aris's Repository")**
*	**[Εκτελέσιμο](https://ariskarras.github.io/pacman/pacman.html "Aris's Pacman")**

# Σύνοψη



# Ροή Παραδοτέων 
Παραθέτω την ροή παραδοτέων της εργασίας για τους εξής λόγους:
1. Ότι όλα τα προαπαιτούμενα και τα deadline της εργασίας τηρήθηκαν με συνέπεια.
2. Να είναι εμφανής η σταδιακή εξέλιξη του παιχνιδιού.
3. Να γίνει πιο εύκολα αντιληπτό η συνολική συνεισφορά της εργασίας μου.

**Aρχικός σχεδιασμός εφαρμογής:**
### Ζητούμενα:
  *	Αντί για τον Pacman χρησιμοποίησε έναν άλλο χαρακτήρα για πρωταγωνιστή του παιχνιδιού.
  *	Αντί ο πρωταγωνιστής να μαζεύει μόνο dots θα μπορούσε να μαζεύει διάφορα αντικείμενα (κέρματα, λουλούδια, φρούτα κτλ).
  *	Δημιούργησε μια νέα πίστα για το παιχνίδι χρησιμοποιώντας το Tiled.

### Υλοποίηση:
  * Αντικατέστησα τον χαρακτήρα του Pacman με τον βασικό χαρακτήρα/πρωταγωνιστή **Luke Skywalker** των ταινιών **Star Wars**.
  <p align="left">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609011/579a84fe-45a7-11e7-8d5a-44459a5c6d66.png">
  </p>
  
  * Πλέον, ο πρωταγωνιστής του παιχνιδιού δεν μαζεύει dots, αλλά μαζεύει κρυστάλλους (crystals), όπως και στις ταινίες **Star Wars** όπου με την βοήθεια τους γίνεται και η παρασκευή των **lightsabers**. Παρόλα αυτά, επέλεξα για λόγους καλαισθησίας ο **Luke** να κρατάει ήδη το **blue lightsaber** του, αλλά να μην μπορεί να νικήσει ακόμα τους εχθρούς χωρίς την κατάλληλη συλλογή άλλων items (τα οποία θα προστεθούν στα επόμενα Παραδοτέα).    

  <p align="left">
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
<p align="left">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609086/ca62bc40-45a7-11e7-9ad5-2ba0d3cd29f5.png">
</p>

  * Πρόσθεσα **Score** στο παιχνίδι, όπου αυξάνεται κατά 10 πόντους, όταν ο παίκτης μαζέψει έναν κρύσταλλο. 
  * Πρόσθεσα το **Bonus**, όπου απεικονίζεται από 2 συγκρουόμενα **lightsabers** (**Blue lightsaber** & **Red lightsaber**). Το **Bonus** αυξάνεται επίσης κατά 10 πόντους, όταν ο παίκτης συλλέξει το συγκεκριμένο αντικείμενο. Επίσης, επέλεξα οι πόντοι του **Bonus**, να προστίθενται και στο συνολικό **Score**.
<p align="left">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26609112/0650bd06-45a8-11e7-90de-1afa605e01a7.png">
</p>

  * Πρόσθεσα επίσης 3 ζωές, οι οποίες θα αποκτήσουν λειτουργικότητα με το επόμενο παραδοτέο.
<p align="left">
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

<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26828915/1a55a216-4acc-11e7-9e2c-be37494a8c60.png">
</p>

<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26828970/57d212fa-4acc-11e7-83a2-fa6639b96c07.png">
</p>

<p align="center">
      <img src="https://cloud.githubusercontent.com/assets/17282953/26829001/7aa029a2-4acc-11e7-93e5-c4fd07dcdb8a.png">
</p>


# Διαδικασία Ανάπτυξης
 
# Μελλοντικές Επεκτάσεις
 
# Συμπεράσματα
 
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
