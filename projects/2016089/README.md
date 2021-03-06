# Bonus Εργασία Βιογραφικού

*  Ονοματεπώνυμο: **Σακουμπέντας Χρήστος**
*  Αριθμός Μητρώου: **Π2016089**
*  Επιλεγμένο Θέμα εργασίας πρώτου παραδοτέου: **"Δημιουργία (αυτόματης) λίστας μαθημάτων για την κάθε κατεύθυνση"**
*  Προσωπικό αποθετήριο του κώδικα: [Link Αποθετηρίου του κώδικα εργασίας ανάπτυξης](https://github.com/csakou/site)
*  Αποθετήριο κώδικα Μπόνους Εργασίας: [Link αποθετηρίου του κώδικα της σελίδας βιογραφικού](https://github.com/csakou/resume)
*  Link για το εκτελέσιμο: [Link Εκτελέσιμου](https://csakou.github.io/site)
*  Link για το δεύτερο μπόνους(2 μονάδες): [Link Bonus Σελίδας Βιογραφικού](https://csakou.github.io/resume)

## Παραδοτέο Α

* Επιλογή θέματος από παραδείγματα. Αλλαγή layout, προσθήκη έξτρα τύπων δεδομένων και Navigation Bar. Επιπλέον αυτόματη προσμαρμογή του Navigation Bar σε μικρότερες οθόνες.
* Συπλήρωση Βιογραφικού.

## Παραδοτέο Β

* Μέσο της γραμμής εντολών και με την χρήση των εργαλείων [Pandoc](https://pandoc.org/) και [LaTeX](https://www.latex-project.org/), μέσα από το ίδιο αρχείο που χρησιμοποιείται για την δομή και τα δεδομένα της σελίδας (\_config.yml) παίρνει τα δεδομένα και το "resume.pdf" έτσι ώστε να υπάρχει ένα μοναδικό workflow και για τα δύο.
* Με την χρήση του [Travis-CI](https://travis-ci.com/) δημιουργείται το pdf του βιογραφικού στο αποθετήριο και ελέγχονται οι αλλαγές. Κάθε φορά που θα γίνονται αλλαγές πλέον στο αρχείο των δεδομένων μέσω του travis θα αλλάζει αυτόματα και το "resume.pdf".

![travis_run](https://github.com/csakou/sw/blob/P2016089/projects/2016089/bonus.gif)
