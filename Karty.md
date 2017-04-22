#### [HOME OPJzM](https://agnieszkamucha.github.io/OPJzM/)
## Kategoria `PRIMARY'
W niej definiowane są parametry żródła promienowania - rodzaj, pęd lub energię, kształt. Określamy również liczbę wychodzących czątek i _seed_ symulacji:
[!["Primary"](Images/primary.png)](Images/primary.jpg)

`BEAM` definiuje wielkości charakteryzujące wiązkę: typ cząstek, energię lub pęd, rozbieżność i profil wiązki.<BR>
Poszczególne pola, w których definiuje się parametry źródła nazywane są we Fluce `What[N]`. Flair podpowiada w rozwijanej liście możliwe paramery, możemy dokanać następujących ustaleń:
[!["Beam"](Images/beam.png)](Images/beam.jpg)

`WHAT(1)`
Wybrać typ wiązki. Możliwość wyboru: Momentum (pęd) lub Energy (energia) <br> 
	p:	podać średni pęd cząstek wiązki (w GeV/c) <br>
	E:	podać średnią energię cząstek wiązki (w GeV) <br>
Wartość domyślna dla pędu to 200.0 GeV/c  
`WHAT(2)`	
	Δp:	wybrać rozkład dla pędu. Możliwość wyboru: Flat (płaski) lub Gauss. Dla pędu zaleca się wybór rozkładu płaskiego. <br>
	ΔE:	wybrać rozkład dla energii Flat (płaski) lub Gauss.<br>
	- Flat	Δp: podać niepewność pędu (w GeV/c).<br>
	- Gauss	Δp(FWHM): podać szerokość połówkową (FWHM = 2,355σ) rozkładu Gaussa. 
`What(3)' Określa rozbieżność wiązki w mrad. <br>	
	- Δφ: Wybrać rozkład kątowy rozbieżności wiązki. Możliwość wyboru: Flat (płaski), Gauss lub Isotropic (izotropowy). <br>
	Flat, Gauss	Δφ: podać wartość rozbieżności kątowej (od 0 do 1999).<br>
	Isotropic	Oznacza rozbieżność wiązki >2π rad <br>

`WHAT(4)`
Określa szerokość wiązki w cm	
	Shape(X):	wybrać kształt wiązki w kierunku X. Możliwość wyboru: Rectangular (prostokątny), Annular (kątowy) lub Gauss. (Function – nieaktywne). 
	Rectangular	Δx: podać szerokość wiązki w kierunku osi X.
	Annular	Rmin: podać minimalny promień wiązki o kształcie kątowym
	Gauss		x(FWHM): podać szerokość połówkową wiązki o kształcie gaussowskim 
 		w kierunku osi X
Wartość domyślna 0.0
WHAT(5)
Określa szerokość wiązki w cm	
	Shape(Y):	wybrać kształt wiązki w kierunku Y. Możliwość wyboru: Rectangular (prostokątny), Annular (kątowy) lub Gauss. (Function – nieaktywne). 
	Rectangular	Δy: podać szerokość wiązki w kierunku osi Y.
	Annular	Rmax: podać maksymalny promień wiązki o kształcie kątowym
	Gauss		y(FWHM): podać szerokość połówkową wiązki o kształcie gaussowskim 
 		w kierunku osi Y
Wartość domyślna 0.0

WHAT(6)
Wartość ignorowana

SDUM 
Part:	wybrać nazwę cząstek wiązki