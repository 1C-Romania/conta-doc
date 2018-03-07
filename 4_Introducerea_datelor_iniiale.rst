4. Introducerea datelor iniţiale
================================

Introducerea datelor iniţiale cuprinde două etape şi anume: completarea
cataloagelor: parteneri, depozite, nomenclatorul de articole şi
introducerea soldurilor.

Un catalog reprezintă o serie de elemente (înregistrări) de aceeaşi
natură. Catalogul de parteneri cuprinde toţi partenerii adăugaţi din
lista de parteneri ai firmei, nomenclatorul de articole cuprinde toată
gama de mărfuri, produse, ambalaje, etc.

Modul de funcţionare introdus de **1C:Contabilitate**, permite însă, pe
lângă traseul descris mai sus, o cale mai dinamică, în sensul că
dezvoltarea cataloagelor poate fi făcută pe măsura introducerii
soldurilor (cu alte cuvinte, nu este necesară descrierea în prealabil a
cataloagelor în cauză).

La înființarea unei firme noi, cataloagele particulare ale firmei sunt
în mod normal goale, urmând a se completa pe măsura introducerii datelor
în program. Există însă unele excepţii. De exemplu, planul de conturi,
catalogul de valute, unităţi de măsură şi altele, sunt aproape la fel în
orice firmă. În această situaţie, cataloagele vor fi pregătite de lucru,
cu înregistrări implicite.

Dacă veţi constata că o parte dintre aceste înregistrări nu corespund
firmei dumneavoastră, aveţi posibilitatea de a le modifica în ansamblu,
prin ştergerea înregistrărilor de prisos, adăugarea de înregistrări noi
sau modificarea înregistrărilor existente. Pe parcursul introducerii
datelor iniţiale vom învăţa cum pot fi introduse şi poziţii noi în
cataloage.

4.1. Politica de evidența
-------------------------

Politica de evidența se află în meniul "Societatea → Politica de
evidența", la acesarea acestuia se deschide meniul derulant ca în
imaginea de mai jos:

|image55|

Pentru a seta, adăuga sau modifica politica contabilă a societății
trebuie să selectăm butonul "**Politica contabilă**" din meniul
derulant.

În meniul "**Politica contabilă**" se pot adăuga politici contabile
diferite customizate pentru fiecare perioada de timp în parte în funcție
de legislația în vigoare și de politica pe care compania care utilizează
sistemul **1C:Contabilitate** o are. Astfel trebuie introduse: data de
la care să fie valabilă această politica ,societatea pentru care să fie
valabilă, metoda de evaluare stocuri, plătitor de TVA, capitalul social,
perioada de plată TVA , politică de TVA și alte informații.

|image56|

4.2. Politica de TVA
--------------------

Există două tipuri de politică de TVA ce pot fi selectate în
**1C:Contabilitate**: TVA la emitere și TVA la încasare conform
legislației din România.

4.2.1. TVA la emitere
~~~~~~~~~~~~~~~~~~~~~

Această informație se poate seta prin accesarea meniului "Societatea → Politică de evidență → Politică contabilă".Exsită două posibilități:fie modificăm câmpul deja existent și adăugăm datele necesare, fie adăugăm o nouă societate.

|image57|

Pentru a adăuga capitalul social, accesăm **"Societatea → Introducere
solduri inițiale → Introducere solduri"**, apăsăm butonul
**"Adăugare"**, selectăm perioada (de exemplu dacă introducem soldurile
inițiale pentru luna ianuarie, anul 2013, perioada de introducere a
soldurilor inițiale va fi luna decembrie, anul 2012).Vom adăuga contul
**"101.2 Capital subscris vărsat"**, apăsăm butonul **"Adăugare"** și
introducem suma capitalului social.

|image58|

După ce se introduce capitalul social sub forma soldului inițial,
preluarea sumei poate fi verificată în **"Politica contabilă"** a
companiei.

4.2.2. TVA la încasare
~~~~~~~~~~~~~~~~~~~~~~

Politica de TVA la încasare a intrat în vigoare de la 1 ianuarie 2013
fiind necesară o modificare a aplicației **1C:Contabilitate**.

Regula principală a sistemului de TVA la încasare, introdus în codul
fiscal prin OG nr. 15/2012, este aceea ca exigibilitatea taxei intervine
la momentul încasării contravalorii livrărilor/prestarilor efectuate
sau, în cazul facturilor neîncasate, în cea de-a 90 a zi calendaristică
de la data emiterii facturilor.

Toate facturile de vânzare-cumpărare vor fi cu TVA la încasare pentru
societățile care folosesc această politică de TVA.Conform legii
nr.227/2015 pot aplica sistemul de TVA la încasare persoanele impozabile
înregistrate în scopuri de TVA, care au sediul activității economice în
România și a căror cifră de afaceri în anul calendaristic precedent nu a
depășit plafonul de 2.250.000 lei. De asemenea există posibilitatea de a
modifica politica de TVA a facturilor direct din document de la fila **"
Cont evidență contabilă "**, sau modificând politica de TVA a companiei.

|image59|

Verificarea politicii de TVA a partenerilor se poate realiza din
Activitatea principală → Parteneri, se introduce CUI-ul și astfel
programul 1C:Contabilitate poate verifica pe site-ul
`www.anaf.ro <http://www.anaf.ro/>`__ politica de TVA a partenerilor și
completează automat informațiile.Se mai poate apăsa butonului
"**Verificare Politica TVA**".

|image60|

Apăsarea butonului va avea ca efect deschiderea ferestrei de mai jos.

|image61|

Introduceți codul Captcha și apăsați butonul **"OK".**

Ca rezultat va fi afișat un mesaj de serviciu în care va fi precizat ce
politică de TVA aplică partenerul respectiv într-un mesaj asemănător cu
cel de mai jos.

|image62|

4.3. Introducere solduri iniţiale din balanţă
---------------------------------------------

În practică pot apărea trei variante de introducere a soldurilor:

-  **societatea este nou înfiinţată şi începe lucrul cu programul de la
zero**. În acest caz nu se introduc nici un fel de solduri de pornire
şi se trece direct la introducerea documentelor. Aici există și
posibilitatea ca firma să fie înfiinţată în anul curent şi automat ea
nu va avea sold de pornire la 1 ianuarie ci doar sume anterioare (se
va selecta perioada de pornire "Solduri şi rulaje în cursul anului");

|image63|

-  **societatea are deja cel puţin un an de activitate şi începe lucrul
în program de la 1 ianuarie.** În acest caz se vor introduce doar
soldurile de pornire de la 1 ianuarie (se va selecta perioada de
pornire "Solduri la început de an"). Tot la această variantă există
posibilitatea ca firma să aibă anii anteriori închişi şi să pornească
operarea cu programul într-o oarecare lună a anului curent. În acest
caz, se introduc soldurile de la 1 ianuarie şi rulajele anterioare
până la luna cu care începe (se va selecta perioada de pornire
"**Solduri şi rulaje în cursul anului**");

-  **societatea are anii anteriori închişi, se află cu activitatea de
contabilitate în mijlocul anului, dar nu are soldurile conturilor
defalcate la 1 ianuarie şi rulaj anterior anului curent**. În acest
caz ar fi eficient ca pe baza balanţei de verificare a ultimei luni
din anul anterior şi a balanţei de verificare a ultimei luni lucrate
să se calculeze manual aceste două tipuri de solduri şi să se
introducă defalcat.

Introducerea soldurilor se realizează în documentul "**Introducere
solduri**", aşa încât va trebui să lansaţi în execuţie lista de
documente. Din meniul principal, alegeţi opţiunea "**Societate**",în
continuare, se va selecta submeniul "**Introducere solduri iniţiale**"
şi printre opţiunile acestui meniu se găseşte şi opţiunea "**Introducere
solduri**"**.**

|image64|

Ca efect, pe ecran va apărea lista de documente, denumită în continuare
"**Introducere solduri**"**.**

|image65|

Explicaţiile pe care le vom da în ceea ce priveşte funcţionarea listei
"**Introducere solduri**" vor fi valabile şi în cazul celorlalte liste
de documente. Pentru adăugarea unui document nou, apăsaţi butonul
"**Adăugare**". Puteţi apăsa în acest scop şi combinaţia "**ALT-A**"
(litera "**A**" din eticheta butonului este subliniată şi reprezintă un
shortcut). Propunerea noastră este de a încerca să utilizaţi cu
încredere shortcut-urile: cu alte cuvinte, apăsaţi "**ALT-A**". În cazul
acţionării butonului de adăugare, pe ecran va apărea documentul de
adăugare a datelor (imaginea de jos).

|image66|

În ceea ce urmează se va descrie cum utilizăm această fereastră pentru a
introduce datele despre un cont preluat din balanţă. Elementele active
ale acestui document (ferestre) sunt de 4 feluri:

-  câmp de editare (zone dreptunghiulare);

-  etichetele câmpurilor de editare (aşezate în apropierea acestora);

-  tabel (grilă), fiecare rând din această grilă reprezintă o
înregistrare;

-  grup de butoane de diferite forme.

Navigarea printre câmpurile de date, butoane şi alte elemente ale
dialogurilor se poate face folosind tasta "**Tab**" pentru deplasare în
câmpul "**Înainte**" şi "**Shift Tab**" pentru deplasare în câmpul
anterior. Acest mod de deplasare este util atunci când se doreşte
deplasarea "pas cu pas", trecând prin toate elementele activabile ale
ferestrei.

Câmpul de editare vă permite să furnizaţi informaţii prin introducerea
unui şir de caractere de la tastatură. În funcţie de necesităţi,
câmpurile de editare pot fi:

-  câmpuri numerice (permit doar introducerea de cifre);

-  câmpuri alfanumerice (acceptă orice caracter);

-  câmpuri de tip data (permit introducerea datei calendaristice).

Majoritatea câmpurilor de editare din **1C:Contabilitate** au ca
rezolvare o selectare dintr-un catalog. Selectările se vor face similar
în toate cazurile, astfel încât explicaţiile pe care le vom da vor fi
valabile şi în cazul tuturor documentelor de acest tip.

Veţi recunoaşte un câmp, valoarea căruia poate fi selectată, prin două
elemente: are un buton ataşat de forma "..." (apăsarea butonului sau
tastarea "F4" va permite deschiderea şi apoi selectarea datelor dintr-un
catalog) sau de forma " " (apăsarea acestui buton sau tastarea F4 va
permite selectarea datelor dintr-o listă rapidă).

Pentru rapiditatea operării, în cazul în care aţi apăsat butonul de
selectare sau aţi tastat "F4" se recomandă să efectuaţi o căutare care
poate fi făcută în două feluri:

-  folosind săgeţile sus/jos de pe tastatură, eventual
Home/End/PageUp/PageDown pentru deplasare mai rapidă în catalog;

-  pentru cataloage lungi, puteţi scrie la tastatură denumirea căutată;
pe măsură ce apăsaţi tastele, **1C:Contabilitate** va deplasa
cursorul pe rândul cu denumirea căruia, coincide cu caracterele
scrise.

Combinând ultimul mod de căutare cu deplasarea din săgeţile tastaturii
sus/jos veţi putea identifica rapid valoarea dorită. Dacă aţi găsit ceea
ce căutaţi, selectarea se consideră acceptată dacă vă poziţionaţi cu
mouse-ul pe valoarea dorită şi tastaţi "**Enter**" sau efectuaţi un
DubluClickMouse pe valoarea respectivă. Fiind la începutul lucrului cu
programul, cataloagele nu vor fi bogate în informaţii. În acest caz
căutarea este de prisos, astfel încât este uşor de realizat pasul
următor: se vor adăuga înregistrări (elemente) noi în catalog. Apăsaţi
butonul "Adăugare" din bara superioară de navigare sau utilizaţi
shortcut-ul: apăsaţi "**Alt-A**".

Am terminat descrierea generală a câmpurilor, explicaţiile privind
selectarea datelor dintr-un catalog şi adăugarea unor înregistrări noi.
Aşadar, acum suntem pregătiţi pentru a începe introducerea datelor.

**Introducerea valorilor soldurilor iniţiale se începe cu alegerea
anului sau lunii de preluare.**

|image67|

***Atenţie! Alegeţi corect anul sau luna de preluare a soldurilor**.
Pentru selectarea anului sau lunii dorite folosind ClickMouse, apăsaţi
primul buton din dreapta-sus din bara superioară de navigare.

Primul câmp din document este "**Număr**". La adăugarea unui document
nou acest câmp va fi completat în mod automat de către program, dar
aveţi posibilitatea să-l modificaţi. Înainte de câmp este
"**Perioada**", care ia în considerare anul sau luna de preluare.
Astfel, veţi selecta perioada cu ajutorul butoanelor ataşate. În cazul
în care evidenţa se ţine doar pentru o societate atunci programul va
completa automat valoarea pentru câmpul "**Societatea**" (câmpul va fi
inactiv) şi va trece peste acest câmp la prima introducere.

În continuare trebuie să selectaţi contul din planul de conturi. Soluţia
cea mai rapidă este căutarea contului în planul de conturi prin tastarea
şirului de caractere dorit. O a doua modalitate ar fi să scrieți direct
primele caractere dorite în câmp, fără deschiderea planului de conturi.
Apoi apăsaţi "**Enter**" şi din lista rapidă afişată selectaţi contul
dorit.

Dacă doriţi să căutaţi în planul de conturi un anumit cont, de exemplu
"**411 – Clienți**" aveţi la dispoziţie posibilităţile de mai jos:

-  apăsaţi "**PageDown**" până când pe ecran va apărea contul "**411**",
urmează să deplasaţi cursorul cu săgeţile din tastatură până vă
poziţionaţi pe contul dorit;

-  soluţia rapidă: începeţi să scrieţi de la tastatură simbolul contului
ales (planul de conturi este aranjat în ordinea simbolurilor de
cont). Efectul apăsării tastei "**4**" este deplasarea cursorului pe
primul cont al cărui simbol începe cu "**4**" (şi anume pe contul
401), iar pe coloana de cont, în subsolul de grilă, se află deja
scris primul caracter tastat.

Dacă în continuare apăsaţi al doilea simbol al contului (adică "**1**"),
textul din chenarul coloanei devine "**41**", iar cursorul de selecţie
s-a deplasat deja pe primul cont al cărui simbol începe cu grupul de
caractere "**41**".

***Atenție!** În cazul conturilor care au analitice trebuie să
selectați analiticul (de ex: pentru contul 411 alegeți analiticul 411.1.

|image68|

Dacă aţi găsit ceea ce căutaţi, selectarea se consideră acceptată dacă
tastaţi "**Enter**" sau DubluClickMouse pe elementul ales. Dacă planul
general de conturi nu conţine contul dorit atunci contul respectiv poate
fi adăugat. Astfel, se pot adăuga atât conturi sintetice noi cât şi un
număr nelimitat de conturi analitice (de grad I sau II) aferente unui
anumit cont sintetic.

Pentru a crea un cont nou trebuie să apăsaţi butonul **"Adăugare"** în
planul de conturi. În acest moment pe ecran va apărea o nouă fereastră
în care se va introduce simbolul noului cont sintetic creat, precum şi
denumirea contului, funcţia acestuia, caracteristicile, lista de
analitice (subconturi). Aveţi posibilitatea de a interzice utilizarea
acestui cont în formule contabile (se va bifa în cazul în care acest
cont conţine conturi sintetice). Pentru un cont sintetic de grad II nou
se va specifica în câmpul "**Părinte**" contul de grad I din care face
parte.

|image69|

Insistenţa cu care explicăm funcţionarea acestui prim document de
introducere de date este justificată de faptul că, în marea lor
majoritate, documentele **1C:Contabilitate** folosesc aceleaşi câmpuri
de editare standard. Odată înţeleasă funcţionarea lor, explicaţiile
necesare înţelegerii celorlalte documente vor fi mult simplificate.

Grupul de câmpuri **"Sold la început de an"** va conţine câmpuri active
în funcţie de contul specificat. Astfel, în situaţia în care contul are
funcţia de activ atunci câmpul "**Sold Dt**" va fi activ, iar "**Sold
Cr**" – inactiv şi viceversa. Soldul la început de an (debitor sau
creditor) reprezintă de fapt soldul final al anului anterior încheiat.
Acest sold poate fi debitor sau creditor.

Grupul de câmpuri "**Rulaje de la început de an**" va fi activ doar în
cazul în care aţi specificat ca perioadă de introducere solduri -
"**Solduri şi rulaje în cursul anului**". Rulajul debitor sau creditor
de la început de perioadă (anterior lunii curente) reprezintă totalul
rulajelor efectuate în anul curent până la luna de lucru de la care se
va începe lucrul cu programul.

***Atenţie!** Este foarte important de reţinut faptul că în rulajele
anului curent nu trebuie incluse soldurile de la 1 ianuarie deoarece
soldul la 1 ianuarie împreună cu rulajul anterior reprezintă total sume
anterioare.

**1C:Contabilitate** permite să înregistraţi nu doar soldurile dar şi
analiticele, care trebuie trecute "**pe rând**" în grilă (tabel).
Fiecare rând din această grilă reprezintă o înregistrare analitică a
contului. Informaţiile vor fi afişate pe linie, astfel:

-  **"Solduri la început de an"** – sold debitor sau creditor.

-  **"Solduri şi rulaje în cursul anului"** – suplimentar vor apărea
coloanele "**Rulaj Dt**"(Rulaj Debitor) şi **"Rulaj Cr"(** Rulaj
Creditor).

Valoarea în câmpul "**Responsabil**" va fi completată, în mod automat,
ea va corespunde cu utilizatorul care a operat acest document şi este
responsabil pentru datele introduse.

Deoarece aţi terminat cu introducerea soldurilor pentru acest cont,
urmează să salvaţi documentul apăsând butonul "**OK**" sau utilizând în
acest scop shortcut-ul "**Ctrl-Enter**" (care acţionează butonul
"**OK**") şi trebuie să confirmați cu "**DA**".

Am ajuns astfel în faţa listei de documente "**Introducere solduri**" în
care se poate observa efectul adăugării: lista conţine acum un document.
Ordinea unui document în lista de documente este determinată de ordinea
de sortare.

Aşadar aţi introdus soldul iniţial pentru un cont din balanţă şi aţi
salvat documentul. În continuare introduceţi similar toate soldurile
iniţiale pentru fiecare cont din balanţă prin adăugarea de fiecare dată
a documentului "**Introducere solduri**".

|image70|

În cazul introducerii unor solduri iniţiale cu evidenţă
cantitativ-valorică de tip en-detail se va utiliza un alt document şi
anume "**Introducere** **solduri amănunt**".

|image71|

Dacă doriţi să faceţi vreo corecţie la datele introduse va trebui să
selectaţi documentul dorit din lista de documente "**Introducere
solduri**" şi să apăsaţi "**Modificare**". După efectuarea modificărilor
urmează în mod firesc să apăsaţi butonul "**OK**".

|image72|

4.2. Solduri iniţiale partener
------------------------------

În ceea ce urmează vom descrie mai detaliat cum pot fi introduse
soldurile iniţiale pentru parteneri. Vom aplica cunoştinţele deja
acumulate, deci pentru adăugarea unui document nou, apăsaţi butonul
"**Adăugare**" aflat pe bara superioară a listei de documente
"**Introducere solduri**". Deoarece un client al firmei poate fi în
acelaşi timp şi furnizor, catalogul de parteneri cuprinde atât clienţi
cât şi furnizori. În această situaţie, iniţializarea soldurilor de
clienţi şi furnizori este tratată unitar, diferenţierea dintre cele două
categorii distincte de parteneri făcându-se prin contul de caracterizare
al soldului.

De exemplu să introducem soldul de 412,56 lei pentru furnizorul "**ADS
Trading SRL**" (cont 401.1). Pentru început selectaţi perioada de
pornire: "**Solduri la început de an**" sau "**Solduri** **şi rulaje în
cursul anului**" cu primul buton din bara superioară şi apoi specificaţi
perioada cu butoanele ataşate la câmpul "**Perioada**".

Dacă aţi specificat perioada, deplasaţi cursorul pe câmpul "**Cont**" şi
începeţi să introduceţi de la tastatură contul 401.1, pentru acceptare
apăsaţi tasta "**Enter**".

|image73|

Apăsaţi "**Alt-A**" sau "**Insert**" pentru a introduce primul rând în
grilă. Cu ajutorul grilei avem posibilitatea de a specifica componenţa
soldului defalcat pe furnizori. Pentru a completa câmpul "**Partener**"
din grilă, apăsaţi butonul de selectare "**...**". Selectaţi partenerul
din listă. Pentru adăugarea unui partener nou, apăsaţi butonul
"**Adăugare**". Introduceţi prescurtarea "**ADS Trading SRL**" în
fereastra elementului din catalogul de parteneri.

***Atenţie!** De regulă pentru câmpul "**Prescurtarea**" se introduce
denumirea partenerului fără a se mai specifica forma sa de organizare
sau alte informaţii suplimentare. Identificarea ulterioară a
partenerilor în listele de căutare folosind căutarea rapidă prin
tastatură impune ca prescurtările introduse să nu aibă pe primele
poziţii grupuri de caractere identice.

Cu alte cuvinte, dacă introduceţi cu consecvenţă la prescurtarea
partenerului "**S.C**." pe prima poziţie ("**S.C. ADS Trading
S.R.L**."), atunci în lista de căutare vor apărea constant pe prima
poziţie aceste caractere, iar căutarea rapidă vă va impune să tastaţi
prescurtarea partenerului precedată de acest grup de caractere. Prin
urmare vă recomandăm la câmpul "**Prescurtarea**" să renunţaţi la
"**S.C**." din faţă.

|image74|

Pagina "**Date generale**" cuprinde informaţii generale, în timp ce
datele de pe pagina "**Informaţia de contact**" oferă informaţii mai
amănunţite privind adresa, telefoane, lista persoanelor de contact etc.,
pagina **"Conturi bancare şi contracte"** cuprinde lista de conturi şi
contracte încheiate.

Dacă aţi introdus denumirea partenerului, începeţi introducerea datelor
de pe pagina "**Date generale**" şi selectaţi grupul de parteneri
(categoria din care face parte partenerul, în cazul nostru
"**Furnizori**"), tipul contractului implicit, completaţi codul fiscal /
codul unic de înregistrare şi numărul din Registrul Comerţului.

Deocamdată, vom lăsa deoparte celelalte pagini şi să presupunem
adăugarea primului partener încheiată, astfel încât ar fi timpul să
lansaţi secvenţă "**Ctrl-Enter**", prin urmare butonul "**OK**".

Dacă aţi procedat aşa, atunci datele sunt deja salvate şi aţi şi ieşit
din fereastra elementului. În lista de selectare există acum elementul
"**ADS Trading SRL**". Apăsaţi "**Enter**" pentru a-l selecta. Iată-ne
din nou pe grila de introducere a soldurilor de parteneri. După
introducerea partenerului în câmpul "**Contract**" selectați căsuța cu
trei punctulețe si căutați în lista de contracte tipul contractului. În
cazul nostru va fi contract cu furnizor.

Observaţi următoarele coloane vor apărea în funcţie de perioada de
introducere, astfel:

-  în cazul "**Solduri la început de an**" – va fi activă coloana
"**Sold creditor**";

-  în cazul "**Solduri şi rulaje în cursul anului**" – suplimentar va fi
activă coloana "**Rulaj Creditor**".

Dacă doriţi să introduceţi doar solduri atunci bifaţi "**Introducere
numai solduri pentru analitice**". În coloana "**Sold creditor**"
introduceţi soldul de 412.56 lei.

|image75|

În rest, despre soldurile partenerilor nu sunt prea multe de spus:
introduceţi rând pe rând în grilă toate datele de pornire pentru
parteneri, cu observaţia că la introducerea soldurilor iniţiale,valoarea
pentru câmpul "**Documente**" trebuie să lipsească, iar valoarea
soldului să se refere la întreaga sumă din fişa partenerului respectiv.

Se salvează documentul prin pasarea tastei "**OK"**. În continuare
introduceţi soldurile iniţiale pentru clienţi în acelaşi fel, prin
adăugarea unui document nou ( veţi alege contul "**411**").

4.3. Solduri iniţiale bancă
---------------------------

Cunoaşteţi deja modul de funcţionare: pentru început vom adăuga un
document nou "**Introducere solduri**", apăsaţi butonul "**Adăugare**"
aflat pe bara superioară a listei de documente "**Lista Introducere
solduri**". Va trebui să acţionaţi primul buton de selectare din bara
superioară pentru a selecta perioada de pornire: "**Solduri la început
de an**" sau "**Solduri şi rulaje în cursul anului**" şi apoi să
specificaţi perioada cu butoanele ataşate la câmpul "**Perioada**".

Deplasaţi cursorul pe câmpul "**Cont**" şi începeţi să introduceţi de la
tastatură contul 512, apăsaţi tasta "**Enter**" şi din lista rapidă
afişată selectaţi contul analitic dorit (vezi imaginea de mai jos).

Acceptarea contului are ca efect apariţia coloanelor "**Conturi
bancare**", "**Sold Cr**" şi "**Sold Dt**" în grilă.

|image76|

De asemenea daca nu se cunoaște simbolul contului,acesta poate fi
selectat și din lista derulantă a planului de conturi .

|image77|

Acum trebuie să apăsaţi "**ALT-A**", "**INSERT**" sau "**Adăugare**"
(din bara de navigare a grilei) pentru a introduce primul rând în grilă.
În continuare acţionaţi butonul de selectare "…" pentru câmpul "**Cont
bancar**" din grilă, iar din listă se va selecta contul bancar dorit (în
care deja aveţi conturile bancare introduse la ghidul de pornire).

Dacă, contul bancar dorit încă nu este introdus atunci acţionaţi butonul
"**Adăugare**". Introduceţi contul IBAN, puteţi verifica corectitudinea
introducerii cu butonul "**Verificare**".

Poziţionaţi cursorul pe câmpul "**Banca**". Butonul de selectare "…" vă
permite să selectaţi din catalog banca unde este deschis contul în
cauză. Dacă banca lipseşte veţi introduce o bancă nouă în catalog cu
ajutorul butonului "**Adăugare**" sau "**Insert**". Apoi veţi selecta
valuta contului bancar cu butonul "…" din câmpul respectiv, iar
denumirea va fi generată.

Dacă aţi introdus contul IBAN, banca şi valuta atunci apăsaţi combinaţia
"**Ctrl+Enter**", sau butonul "**OK**". Dacă aţi procedat aşa, atunci
datele sunt deja salvate şi aţi ieşit din fereastra elementului. În
lista de selectare s-a adăugat un cont bancar. Apăsaţi "**Enter**"
pentru a-l selecta. Introduceţi soldul în câmpul "**Sold Cr**" sau
"**Sold Dt**". După ce aţi introdus valoarea apăsaţi tasta "**Enter**"
pentru acceptare. Cursorul a trecut pe al doilea rând, unde puteţi
continua cu introducerea datelor pentru al doilea cont bancar. Puteţi
introduce oricât de multe conturi bancare doriți.

Dacă doriţi să ştergeţi unul dintre rândurile deja introduse în grilă,
va trebui să poziţionaţi cursorul grilei pe unul din rândurile în cauză,
apoi să apăsaţi butonul "**Ştergere**" cu ClickMouse sau să apăsaţi
"**Del**" de la tastatură. Încheiaţi acţiunea de iniţializare a soldului
de bancă apăsând "**OK**" sau secvenţa "**Ctrl+Enter**". Pentru conturi
bancare în valută se va introduce un document nou şi la câmpul
"**Cont**" se va selecta 512.4."**Conturi curente la bănci în valută**"
şi se vor relua modalităţile de completare descrise mai sus.

4.4. Solduri iniţiale casierii
------------------------------

Modalitatea de completare seamănă cu cea descrisă la capitolele
precedente, singura diferenţă fiind introducerea contului de casă la
câmpul respectiv. Trebuie să adăugăm un document nou în lista de
documente "**Lista Introducere** **solduri**". Astfel, din meniul
principal alegeţi opţiunea "**Societate**", în continuare, se va selecta
submeniul "**Introducere solduri iniţiale**" şi printre opţiunile
acestui meniu se găseşte şi opţiunea "**Introducere solduri**". Prin
urmare, pe ecran va apărea lista de documente, denumită în continuare
"Lista Introducere solduri". Deci, cu butonul "**Adăugare**" vom adăuga
un document nou. Introduceţi în mod similar cu celelalte solduri:
perioada de pornire, apoi va trebui să deplasaţi cursorul pe câmpul
"**Cont**" şi să introduceţi de la tastatură contul 531, apăsaţi tasta
"**Enter**" şi din lista rapidă afişată selectaţi contul sintetic
"**531.1 Casa în lei**". Grila are, după cum puteţi observa, o coloană
nouă "**Casierii**" pe lângă coloana "**Sold Dt**".

Acum ne aflăm în faţa unei grile, apăsăm butonul de selectare al
casieriei "…" din dreptul câmpului respectiv. Deoarece casieria se află
deja introdusă în catalog (ne-am gândit că orice firmă are măcar o
casierie în lei), nu ne rămâne decât să acţionăm butonul "**Enter**" sau
Dublu Click Mouse pentru acceptare. În continuare aşadar introduceţi
soldul de numerar. Şi cu aceasta aţi terminat introducerea.

Salvaţi şi validaţi documentul ("**OK**" sau "**Ctrl-Enter**").

4.5. Solduri iniţiale avans de trezorerie
-----------------------------------------

Alegeţi din meniul principal "**Societate**" / "**Introducere solduri
iniţiale**" / "**Introducere solduri**". Ca urmare a alegerii opţiunii
"**Introducere solduri**", pe ecran va apărea o listă de documente. În
continuare există o singură posibilitate: butonul "**Adăugare**",
"**Alt-A**"sau "**Insert**". De exemplu, să realizam introducerea
soldului de 1.700,12 lei pentru "**Dumitru Adrian**", sold care
reprezintă avans de trezorerie nejustificat. Pentru început selectaţi
perioada de pornire şi apoi introduceţi de la tastatură contul 542,
pentru acceptare apăsaţi tasta "**Enter**".

Să pornim cu ceea ce ştim deja: să selectăm din catalogul de persoane
fizice, folosind butonul de selectare "**…**", persoana "**Dumitru
Adrian**". Apoi va apărea, lista de selectare a catalogului de persoane
fizice. Catalogul este gol, deocamdată nu a fost adăugat nici un
element; acţionaţi "**Adăugare**" sau combinaţia "**Alt-A**".

|image78|

Dacă aţi introdus numele, prenumele şi marca, începeţi introducerea
datelor de pe pagina "**Date generale**". În cazul în care această
pagină nu este "în faţă", atunci apăsaţi ClickMouse pe denumirea ei,
apoi completaţi codul numeric personal, locul de naştere, actul de
identitate, cetăţenia, ziua de naştere şi sexul. Pentru salvarea fişei
apăsaţi butonul "**OK**" sau combinaţia "**Ctrl + Enter**". Acum pentru
acceptarea persoanei în document apăsaţi "**Enter**" sau DubluClickMouse
pe poziţia respectivă. Iar la câmpul "**Sold Dt**" introduceţi valoarea
1.700,12 lei. Încheiaţi acţiunea de introducere a soldului de avans de
trezorerie apăsând "**OK**", sau combinaţia "**Ctrl-Enter**".

4.6. Solduri iniţiale evidenţa cantitativ-valorică
--------------------------------------------------

Am ajuns la ultimul capitol al iniţializării anume "**Stocuri cu
evidenţa cantitativ-valorică**". Aceste stocuri se introduc în program
cu un document diferit de cel prezentat până acum, şi anume
"**Introducere solduri amănunt**". Alegeţi din meniu opţiunea
"***Societatea → Introducere solduri inițiale → Introducere solduri
amănunt***". Veţi observa o listă de documente care nu diferă cu nimic
faţă de ***"Lista Introducere solduri"*** descrisă mai devreme, acum nu
vă mai poate speria! Dimpotrivă, ea devine chiar familiară: acelaşi grup
de butoane pentru navigare, tot un buton de adăugare la început, iarăşi
o grilă cu documente şi comentariul curent afişat în subsol! Pentru a
introduce un document nou apăsaţi aşadar butonul "**Adăugare**" sau
combinaţia "**ALT-A**".

|image79|

Pentru început veţi specifica perioada de pornire. Apoi continuaţi cu
specificarea depozitului. Apăsaţi aşadar butonul de selectare "**…**" al
depozitului. În lista de căutare veţi observa poziţiile introduse la
ghidul de pornire. Apăsaţi aşadar DubluClickMouse pe poziţia dorită
(ceea ce este echivalent cu deplasarea cursorului pe poziţie şi apăsarea
tastei "**Enter**").

Aici mai există o singură întrebare majoră care trebuie explicată pe
larg şi anume problema tipului contabil. În datele iniţiale se vorbeşte
despre marfă la preţ de amănunt, deci cu TVA neexigibil şi diferenţe de
preţ incluse. Va trebui să reuşim să "înghesuim" într-o singură grilă o
mulţime de informaţii cum ar fi: cantitatea, contul de stoc (371.1),
contul de diferenţe de preţ (378), cota de TVA şi faptul că are TVA
neexigibil (442.8) pe toată valoarea.

La fel ca şi la celelalte iniţializări, pe prima poziţie se află un
buton de adăugare a unui rând nou în grilă. Apăsaţi secvenţa "**ALT-A**"
sau ClickMouse pe butonul "**Adăugare**". În lista de selectare a
nomenclatorului de articole observaţi, ca la majoritatea cataloagelor:
lipsa înregistrărilor şi mai nou existenţa unor grupuri. Ideea de la
care se porneşte este că informaţiile pot fi grupate după specificul
lor.

**1C:Contabilitate** permite împărţirea (gruparea) articolelor pe grupe.
De exemplu, pentru a uşura căutarea în nomenclatorul de articole (cu
timpul acestea vor fi foarte multe!), puteţi descrie câteva clase de
caracterizare, să zicem grupe, precum: "**Materii prime**", "**Produse
finite**", "**Semifabricate**" etc. Cu o asemenea structură a
nomenclatorului de articole, fiecare articol ar fi în una din grupele
descrise. În această situaţie, se poate stabili o caracterizare
contabilă "pe grupe". În acest fel, în momentul în care veţi selecta un
articol, conturile vor fi completate implicit în documente.

Acest mod de operare este valabil, de asemenea, pentru parteneri şi
depozite. Modul de structurare a grupelor ţine de nevoile dumneavoastră.
Acum apăsaţi butonul "**Adăugare**" sau secvenţa "**ALT-A**".

Sunteţi în faţa ferestrei care permite descrierea articolelor de stoc.
Cursorul clipitor din linia de editare etichetată "**Prescurtare**" vă
anunţă că acest câmp este selectat şi puteţi introduce prescurtarea.

***Atenţie!** Cum am mai menţionat, pentru câmpul "**Prescurtarea**" se
introduce doar denumirea articolului fără a se mai specifica alte
informaţii suplimentare. Menţiuni suplimentare se pot introduce la
câmpul "Denumirea completă", aceasta din urmă va fi folosită la listare.

Dacă este cazul se va selecta în câmpul precedent cu ajutorul mouse-lui
grupul de articole din care face parte articolul respectiv. Am explicat
deja că există posibilitatea grupării articolelor pe grupe (clase) de
caracterizare. Această încadrare nu rezolvă însă toate problemele legate
de diversitatea variantelor de articole. Grupele au fost introduse
pentru a uşura gestionarea evidenţei contabile a articolelor şi căutarea
lor în catalog.

|image80|

Câmpul "**Cod articol**" nu este unul obligatoriu, se va utiliza în caz
de necesitate, să zicem articolul trebuie să conţină un cod special (de
exemplu: cod folosit la exportul la casele de marcat sau un cod special
intern). Pentru a utiliza acest cod trebuie să bifaţi căsuţa **"Se va
utiliza cod articol"** localizată în parametri de evidenţă la fila
**"Articole"**. Trebuie menţionat că în nomenclatorul de articole, pe
lângă înregistrările obişnuite care se referă la stocuri, există
posibilitatea de a introduce şi elemente care vizează diverse servicii
"primite" sau "prestate". Astfel în cazul în care elementul reprezintă
un serviciu se va bifa căsuţa "**Serviciu**".

***Atenţie!** Dacă doriţi să introduceţi coduri de bare atunci pentru
început veţi bifa căsuţa **"Se va ține evidenţa după coduri de bare"**
localizată în **"Parametri de evidenţă"** la fila **"Coduri de bare"**.
În continuare în fereastra articolului va apărea fila "**Coduri de
bare**" unde veţi specifica codurile de bare. **1C:Contabilitate**
permite să introduceţi mai multe coduri de bare pentru un singur
articol. De asemenea, aveţi posibilitatea să definiţi unitatea de măsură
pentru fiecare cod de bare în parte.

Celelalte date despre articol trebuie introduse în filele "**Unităţi de
măsură**", "**Date generale**", "**Caracterizare contabilă**" şi
"**Coduri de bare**" (după caz) aflate în fereastra articolului. Ne vom
concentra deocamdată asupra filelor "**Unităţi de măsură**" şi "**Date
generale**". În fila "**Unităţi de măsură**" va trebui să alegeţi
neapărat unitatea de măsură de bază a articolului folosind lista de
selectare ataşată butonului "**UM de bază**". Dacă pentru utilizatorul
curent s-a indicat o unitate de măsură implicită în setări, atunci la
introducerea unui articol nou câmpul va fi automat completat cu valoarea
respectivă. Să explicăm mai detaliat cum **1C:Contabilitate** operează
cu unităţile de măsură. În mod normal în această filă se definesc toate
unităţile de măsură utilizate la comercializarea articolului.
**1C:Contabilitate** permite convertirea automată dintr-o unitate de
măsură în alta pe baza unui coeficient. Pentru început veţi defini
***unitatea de măsură de bază***. UM de bază reprezintă acea unitate de
măsură în raport cu care vor fi calculate celelalte unităţi de măsură.

Ca rezultat, dacă veţi defini în grilă mai multe unităţi de măsură
atunci trebuie să specificaţi în care din unităţile de măsură introduse
se va ţine evidenţa stocului (***UM stocuri***). În a doua filă "**Date
generale**" pentru început se va specifica cota de TVA. Dacă pentru
utilizatorul curent s-a indicat o cotă de TVA implicită în setări,
atunci la introducerea unui articol nou câmpul va fi automat completat
cu valoarea respectivă.

4.7. Verificare solduri cu balanţa de verificare
------------------------------------------------

Pentru a verifica corectitudinea datelor introduse,se procedează la
analiza valorii TVA atât în Jurnalul de cumpărare, cât și în Jurnalul de
vânzare.Aceste sume sunt comparate cu cele din "**Balanţa de
verificare**" **("*Rapoarte* *→Balanță de verificare*")** . Toate
operaţiunile necesare vă sunt deja cunoscute:

-  intraţi în meniu "**Rapoarte**" (ClickMouse pe opţiunea
"**Rapoarte**");

-  folosind ClickMouse sau tastatura, alegeţi opţiunea "**Balanţa de
verificare**".

Așa arată primul raport **1C:Contabilitate.**

|image81|

În cadrul acestei ferestre veţi defini perioada de afişare, societatea
şi pentru întocmire veţi apăsa butonul "**Creare**".

|image82|

Dacă la totalul soldului iniţial există egalitate debit-credit atunci
înseamnă că înregistrările sunt corecte.Aceeași procedură se aplică
pentru **Rulajul debitor și creditor**, **Total sume** și **Sold
final**. Dacă însă totalul nu corespunde, va trebui să căutaţi în lista
de documente "Introducere solduri", soldul iniţial care nu corespunde şi
să încercaţi corectarea sa (evident, la opţiunea din meniu
"***Societatea → Introducere solduri iniţiale***").

De asemenea, **"Balanța de verificare"** poate fi afișată pe anumite
intervale de conturi. Pentru a fi posibil acest lucru trebuie setat
acest interval. Putem face acest lucru selectând din meniul raportului
butonul **"Configurare"**. Se va deschide fereastra de mai jos, mergem
pe fila **"Filtre"** unde putem seta intervalul din planul de conturi.
Se poate bifa "Doar conturi valutare" pentru a face o sortare
suplimentară care să aducă în balanță doar conturile în valută.

|image83|

De exemplu, vom face o filtare de la contul [100.1] până la contul
[214]. Aceast filtru va simplifica modul de lucru al utilizatorilor.

|image84|

Un alt raport de verificare a soldurilor este **"Balanța de verificare
pe cont"** unde putem vedea pe o perioadă definită de noi soldurile ,
rulajul și soldul final pentru un anumit cont.

|image85|

.. |image55| image:: media/image55.png
   :width: 5.61378in
   :height: 3.33386in
.. |image56| image:: media/image56.png
   :width: 6.92153in
   :height: 2.13889in
.. |image57| image:: media/image57.png
   :width: 3.56522in
   :height: 4.88406in
.. |image58| image:: media/image58.png
   :width: 6.07159in
   :height: 3.35652in
.. |image59| image:: media/image59.png
   :width: 4.52008in
   :height: 5.32205in
.. |image60| image:: media/image60.png
   :width: 6.24921in
   :height: 4.55157in
.. |image61| image:: media/image61.png
   :width: 3.03478in
   :height: 1.81739in
.. |image62| image:: media/image62.png
   :width: 6.92913in
   :height: 1.13386in
.. |image63| image:: media/image63.png
   :width: 6.08978in
   :height: 3.37391in
.. |image64| image:: media/image64.png
   :width: 4.27594in
   :height: 2.36522in
.. |image65| image:: media/image65.png
   :width: 7.13989in
   :height: 4.26087in
.. |image66| image:: media/image66.png
   :width: 6.51202in
   :height: 3.81739in
.. |image67| image:: media/image67.png
   :width: 3.68696in
   :height: 1.53913in
.. |image68| image:: media/image68.png
   :width: 6.92153in
   :height: 3.71319in
.. |image69| image:: media/image69.png
   :width: 6.6087in
   :height: 5.46293in
.. |image70| image:: media/image70.png
   :width: 6.92847in
   :height: 3.56852in
.. |image71| image:: media/image71.png
   :width: 7.11304in
   :height: 3.03805in
.. |image72| image:: media/image72.png
   :width: 6.1809in
   :height: 3.86956in
.. |image73| image:: media/image73.png
   :width: 6.42609in
   :height: 4.40869in
.. |image74| image:: media/image74.png
   :width: 6.20748in
   :height: 4.96929in
.. |image75| image:: media/image75.png
   :width: 6.92795in
   :height: 4.2374in
.. |image76| image:: media/image76.png
   :width: 4.06944in
   :height: 2.03472in
.. |image77| image:: media/image77.png
   :width: 6.92153in
   :height: 3.77361in
.. |image78| image:: media/image78.png
   :width: 4.5913in
   :height: 4.14784in
.. |image79| image:: media/image79.png
   :width: 6.85217in
   :height: 2.94381in
.. |image80| image:: media/image80.png
   :width: 6.1913in
   :height: 4.25446in
.. |image81| image:: media/image81.png
   :width: 6.92153in
   :height: 3.62639in
.. |image82| image:: media/image82.png
   :width: 6.92153in
   :height: 4.12153in
.. |image83| image:: media/image83.png
   :width: 4.53889in
   :height: 2.89583in
.. |image84| image:: media/image84.png
   :width: 6.92153in
   :height: 3.86944in
.. |image85| image:: media/image85.png
   :width: 6.92153in
   :height: 3.2in
