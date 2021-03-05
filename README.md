# LFPC-lab2

###### In .png este ilustrata varianta care trebuia sa o rezolv, NFA, DFA si tabelul cu tranzitii.

###### Code-ul pentru laboratorul Nr.2 am fost scris in python. Tot programul a fost impartit in mai multe blocuri, dupa semnificatie si rol. De asemenea, code-ul este scris, astfel incat cu acesta rezolva toate variantele din lucrare de laborator, nu daor a mea personala, varianta Nr.20.
###### In blocul Nr.1 se importeaza librariile necesare pentru ilustrarea tuturor tranzitiilor in forma tabelara atat in formtul NFA si DFA.
###### In blocul Nr.2 afiseaza legenda pentru gramatica care va fi utilizata pe parcursul programului.
###### In blocul Nr.3 se afla si se salveaza simbolurile terminale, marcate cu litere mici a alfabetului englez.
###### In blocul Nr.4 se afla si se salveaza simbolurile neterminale sau mai numite si state-uri, marcate cu litere mari a alfabetului englez.
###### In blocul Nr.5 se afla si se salveaza reguile gramaticii, numite si functiile de tranzitie, la moment ele sunt salvate intr-o lista de string-uri, astfel cum sunt specificate de utilizator, fara modificari.
###### In blocul Nr.6 se afla si se salveaza care simbol de finish, aka final state.
###### In blocul Nr.7 se afiseaza gramatica totala a limbajului specificat de utilizator prin intermediul la code-ul din blocurile 2 - 6. Acest bloc duce un caracter informativ
###### In blocul Nr.8 se contruieste Finite Automaton prin intermediul structuri de date din python. Pentru reprezentarea s-a utilizat dictionar, lista si tuple. Cheia este state-ul, de exemplu 'A', 'B'. Pentru fiecare cheie ii convine tuple de perechi. Fiecare pereche reprezinta o tranzitie de la nodul 1 spre nodul 2 cu pondere. Primul e simbolul terminal, al doilea e simbolul neterminal - state-ul. Dupa procesare se ilustreaza acest dictionar.
###### In blocul Nr.9 se creaza dictionarul NFA. Cheia reprezinta state-ul, iar fiecare chei ii revine o lista unde sunt ilustrate tranzitiile si noile state-uri formate.
###### In blocul Nr.10 se contruieste si se afiseaza tabelul NFA, utilizand functiile librariei pandas.
###### In blocul Nr.11 se creaza variabilele care vor fi utilizate in continuare pentru crearea la DFA
###### In blocul Nr.12 se calculeaza primul rand din tabelul DFA
###### In blocul Nr.13 se calculeaza restul randurilor din tabelul DFA
###### In blocul Nr.14 se printeaza dicionarul DFA nou format si tabelul de tranzitii DFA utilizand functiile pandas
###### In blocul Nr.15 se afla si se afiseaza care sunt state-urile finale, adica care contin variabila final_state
