# Parallel-Servers-Queue-Simulation-R
Sistem de tip coadă cu două servere legate în paralel
Considerăm un sistem cu două servere ce îndeplinesc aceeași funcție, în mod similar.
Funcționarea acestuia este următoarea:
• La sosirea unui client, dacă serverul 1 este liber va servi imediat clientul, altfel acesta se adresează serverului 2 și în cazul în care și acesta este ocupat clientul intră ȋntr-o coadă de așteptare comună celor 2 servere.
• După finalizarea execuției de către serverul 1 sau 2, după caz, clientul părăsește sistemul și clientul cu timpul de așteptare cel mai mare din coadă urmează să fie deservit de serverul respectiv.
Convenții:
▪ Sosirea clienților se face conform unui proces Poisson neomogen cu
funcția de intensitate λ(t).
▪ Timpii de servire asociați celor două servere sunt considerate variabile
aleatoare având funcțiile de repartiție G1 și respectiv G2.
▪ Obiectivele simulării:
1) Determinarea timpului minim, maxim și mediu petrecut de un client în sistem( cu detaliere pentru fiecare server în parte)
2) Determinarea numărului mediu de clienți serviți de fiecare server, precum și al numărului mediu total de clienți serviți de sistem ȋntr-o anumită perioadă de timp.
3) Determinarea primului moment de timp la care este pierdut un client
4) Determinarea numărului mediu de clienți pierduți din cauza timpului de așteptare prea mare( cu detaliere pentru fiecare server în parte)
5) Determinarea cȃștigului mediu suplimentar care ar fi obținut dacă s-ar mări programul de lucru cu o oră(cu detaliere pentru ȋnceperea programului mai devreme și respectiv pentru prelungirea cu o oră a programului curent) și respectiv dacă s-ar mări dimensiunea maximă a cozii de așteptare.
