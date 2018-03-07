7. Producţia
============

Principala caracteristică a programului este posibilitatea de a folosi
reţetele (consumuri specifice) şi variaţia lor în timp, ceea ce înseamnă
că fiecare reţetă este introdusă la o dată exactă şi este valabilă şi
pentru datele următoare, până nu se fac noi modificări. Reţetele
precedente sunt păstrate şi pot fi vizualizate. Dacă folosiţi reţete
pentru produsele finite atunci le puteţi înregistra pe fila
"**Specificaţie produs**" din fereastra "**Informații despre articol**".

|image204|

Prin urmare reţetele sunt folosite ca o bazã în introducerea unui raport
de producţie. Reţetele şi raportul de producţie permit realizarea unui
calcul al costurilor de producţie plecând de la un nomenclator de
materii prime, materiale şi semifabricate. Pentru început sistemul
realizeazã o antecalculaţie de cost dupã unul planificat, urmând la
închiderea perioadei de gestiune programul automat sã calculeze
postcalculaţia de cost de producţie.

|image205|

La încheierea proceselor pot rezulta componente stocabile (repere,
subansamble, semifabricate etc.), componente care sunt recepţionate în
magaziile de produse. Acestea pot deveni componente de intrare pentru
alte procese de producţie. În ceea ce urmează vom parcurge ciclul de
producţie. Să începem cu configurarea constantelor de funcţionare.

7.1. Configurare constante de funcţionare
-----------------------------------------

Pentru buna funcţionare a producţiei se va avea în vedere configurarea
următoarelor constante generale de funcţionare:

**1.** **Cost planificat** – valoarea specificată ca preţ de referinţă
este preluată implicit în raportul de producţie. Această opţiune poate
fi accesată din meniu "**Parametri de evidenţă**" şi anume în pagina
"**Producţia**";

**2. Metode de repartizare cheltuieli indirecte** – în meniul
*Întreprindere → Politica de evidenţă → Metode de repartizare cheltuieli
indirecte*" există posibilitatea de a specifica baza de repartizare a
cheltuielilor indirecte. Cu ajutorul butonului "**Adăugare**" veţi
introduce cheltuielile indirecte, apoi veţi specifica contul de evidenţă
a lor, baza de repartizare şi departamentul.

**3. Ordinea de închidere a departamentelor** – pentru a realiza
condiţiile de precizie a postcalculului la calcularea costului de
producţie programul va solicita să aveţi specificată o ordine de
închidere a departamentelor. Încărcarea se va opera din "*Întreprindere
→ Politica de evidenţă → Ordinea de închidere departamente"*.

7.2. Repartizarea cheltuielilor pe departamente
-----------------------------------------------

La înregistrarea unui serviciu pe documentele de aprovizionare sau
vânzare din firmă se va solicita precizarea departamentului în cadrul
căreia se contabilizează respectiva cheltuială sau venit. De asemenea
această solicitare va apărea şi în cazul de înregistrare a unei încasări
sau plăţi dacă veţi indica operaţia "Alte încasări" sau respectiv "Alte
plăţi" şi ca și cont corespondent va fi indicat o cheltuială sau venit.

***Atenţie!** Toate cheltuielile care nu au fost legate de departamente
vor fi considerate ca fiind cheltuieli generale ale firmei.

7.3. Bonuri de consum
---------------------

Cu bonul de consum se înregistrează consumul de materii prime aferent
raportului de producţie. Documentul poate fi accesat din meniu
"*Activitatea principală → Producție → Raport de producție*".

|image206|

Pe baza raportului de producţie şi reţetelor introduse se poate genera
automat bonul de consum pe fiecare raport de producţie în parte.

|image207|

7.5. Raport de producţie
------------------------

Cu ajutorul raportului de producţie înregistrăm nota de predare produse
finite prin care departamentul de producţie predă depozitului (gestiunea
în care se face recepţia).

7.6. Producţie neterminată
--------------------------

Pentru precizia calculelor, privind costurile de producţie, este
necesară evaluarea producţiei neterminate şi introducerea ei cu
documentul "*Activitatea principală → Producţie → Inventariere producţie
neterminată*". Valoarea producţiei neterminate din acest document este
contabilizat automat de **1C:Contabilitate** la sfârşitul lunii,
inclusiv stornarea la începutul lunii următoare a înregistrărilor din
luna curentă.

|image208|

7.7. Deductibilitate limitată a cheltuielilor
---------------------------------------------

De la 1 iulie 2012, 50% din cheltuielile aferente vehiculelor unui agent
economic sunt deductibile la calculul impozitului pe profit, numai dacă
respectivele vehicule sunt utilizate exclusiv în scopul afacerii.
Astfel, pentru cheltuielile cu deductibilitate limitată trebuie setat de
la câmpul "Fiscal" varianta "Deductibilitate limitată".

|image209|

.. |image204| image:: media/image198.png
   :width: 6.54783in
   :height: 4.73004in
.. |image205| image:: media/image199.png
   :width: 6.24348in
   :height: 4.58097in
.. |image206| image:: media/image200.png
   :width: 5.97391in
   :height: 3.01722in
.. |image207| image:: media/image201.png
   :width: 5.92174in
   :height: 2.99204in
.. |image208| image:: media/image202.png
   :width: 5.9913in
   :height: 2.9659in
.. |image209| image:: media/image203.png
   :width: 4.0087in
   :height: 2.48786in
