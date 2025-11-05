Readme

byte0: Αρχικά έτρεξαα cat και είδα ότι ο τελευταίος φάκελος είναι το treasure. Εκανα cd ./i_wanna_be….../your_reward_is_here οπου εδώ είναι το treasure, και μεσω pico treasure βρηκα το string

byte1:Έγραψα την παρακάτω εντολή
      man supercalifragilisticexpialidocious, 
      και βγήκα το strin
byte2:Αρχικά ls, ( byte2@ip-172-31-37-131:~$ ls 
                   shakespeare.txt)
       Μετά ( $ grep -i "will find" shakespeare.txt)
       και βρήκα το string

byte3: έβαλα diff shakespeare.txt shakespeare.modified.txt

byte4: εκανα find και παρατήρησα ότι το cup.txt είναι σε αυτό το filepath (./maze/left/right/8/cup.txt)
   έτρεξα ./maze/left/right/8/cup.txt και μου έβγαλε το string

byte5: εκανα mkdir -p /tmp/byte5dir, ώστε μετα να κανω copy ( cp ~/byte5.c /tmp/byte5dir/) και μεταγλωττισή ( gcc byte5.c -o byte5 ). Όμως επαιρνα αυτό το μυνημα προσαθωντας να τρεξω το ./byte5
         Usage: ./byte5 <SDI> . Το ελυσα αυτό με την εντολη ./byte sdi2500086

byte6: έκανα unzip -p byte6.zip

Byte7: Προσπαθησα να το μεταγλωτισω εκει που ηταν, δεν γινοταν. Αρα δημιουργησα νέο φακελο (mkdir /tmp/byte7dir) στον οποιο εκανα αντιγραφη το tar αρχειο ($ cp byte7.tar.gz /tmp/byte7dir) και μεταγλωτιση ($ tar -xzf byte7.tar.gz) ώστε τελικα να τρεξω cat byte7.txt και να παρω το string

Byte8: εκανα ls, Πηρα carriage_return.txt, και ετρεξα pico carriage_return.txt, μεσα στα σχολια βρηκα το string 

Byte9: ετρεξα ls, πηρα -, ετρξα cat ./- και πηρα το string

Byte10: εκανα ls, Πηρα i_wonder_what_this_does  names.txt, κοιταξα το (i_wonder_what_this_does) τελικα δεν το χρειαζομουν, και μετα απο πολυ ψαξιμο ετρεξα την εντολη $ sort names.txt | head -n 42 | tail -n 1

Byte11: εκανα ls
              sort births.txt
              uniq --help
              sort births.txt | uniq -c | sort -nr | head -n 1

Byte12: Ετρεξα find

Byte13: ετρεξα ls, μετα cd repo και τελος git log

Byte14: εκανα ls και μετα cd ./repo. Μεσα στο repo εκανα git log -p και κατεβηκα αρκετα μεχρι που βρηκα το string

Byte15: Δεν προλαβα να το λυσω

*****Επειδή τα ειχα μπερδεψει όταν τα ελυνα και δεν ειχα ένα byte ανα commit, τα εσβησα και ξαναεκανα τα commits, προσθετωντας ένα byte ανα commit