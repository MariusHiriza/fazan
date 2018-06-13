# fazan

Pentru a realiza acest joc am folosit o multime(set) pentru a retine toate cuvintele. La inceputul jocului se alege nivelul de dificultate al calculatorului (easy, medium, hard), iar cuvintele pentru categoria aleasa se adauga dintr-un fisier intr-un arbore binar de balansare, am facut 3 fisiere pentru fiecare nivel de dificultate.
<p>Programul se realizeaza in modul urmator:</p>
<ul>
 <li>1. Se da un cuvant de la tastatura. In caz ca nu exista cuvantul in multimea de cuvinte atunci se cere sa se dea un alt cuvant.
 <li>2. Se extrag ultimele 2 caractere din cuvantul dat de utilizator anterior si se cauta in arborele binar de balansare(level).
  <ul> 
<li>Daca exista vreun cuvant care sa inceapa cu cele 2 caractere si sa nu mai fi fost folosit cuvantul anterior(se cauta intr-un alt arbore binar de balansare daca nu exista cuvantul (used_words) ) atunci:
  <ul>
<li>Se insereaza cuvantul gasit in arborele binar de balansare(used_words) pentru cuvinte folosite
<li>Se afiseaza cuvantul 
<li>Se sterge cuvantul din arborele binar de balansare si si rebalanseaza arborele (level)
<li>Se cere utilizatorului sa dea un cuvant care incepe cu ultimele 2 litere din cuvant si sa existe in multimea de cuvinte pana respecta aceasta cerinta sau in caz contrar se va scrie 'None' daca nu exista sau nu stie vreun cuvant care sa respecte cerintele si se reia de la punctul 1) in caz ca utilizatorul nu este 'fazan'
  </ul>
<li>Daca nu exista un cuvant care sa respecte cerintele din lista de cuvinte din arborele binar de balansare(level) atunci computer este 'f' sau 'fa' etc. si se afiseaza pe ecran ce este computerul si se reia de la punctul 1) daca calculatoul nu este 'fazan'
  </ul>
 <li>La final se afiseaza cine a castigat
 </ul>
