# ISS

Enunt problema:
O firma producatoare de software pune la dispozitia programatorilor si verificatorilor sai un sistem prin care acestia pot sa comunice electronic. Astfel, fiecare dintre angajatii mentionati are la dispoziție un terminal prin care:<br>
 
   •verificatorul  -poate  înregistra  un  bug,  dându-i  o  denumire, o descriere si un nivel de gravitate: Low, Medium, High<br>
                   -imediat  dupa înregistrarea bug-ului, toti  programatorii vad  lista bug-urilor  actualizata cu obiectul nou introdus<br>
                   -vizualizeaza bug-urile rezolvate de programatori si poate inchide un bug daca l-a testat din nou si a constatat ca e rezolvat, caz în care bug-ul este scos din                     lista tuturor programatorilor.<br>
    
   •programatorul  -vizualizeaza lista bug-urilor dupa nivelul de gravitate<br>
                   -un bug poate avea 3 statusuri: InWork, cand un programator lucreaza la rezolvarea lui<br>
                                                   Available, cand nimeni nu lucreaza la bug<br>
                                                   Ready for testing, cand bug-ul se considera rezolvat si tester-ul il poate verifica iar<br>
                   
   •Atat programatorii cat si testerii au acces la un raport de tipul nr bug-uri rezolvate/nr bug-uri noi
