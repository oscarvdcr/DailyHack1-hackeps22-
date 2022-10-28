Author: Òscar van de Crommert Rodoreda
Github link: https://github.com/oscarvdcr
Repository link: https://github.com/oscarvdcr/DailyHack1-hackeps22-


Llavor inicial:
Com es veurà la grid al codi.																	Com es veurà la grid al executar.
 -------------------------------------------------------------------------						. . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 0 | 0 | 0 | 0 |      	. ░░ ░░ ░░ ░░ ██ ██ ██ ██ ██ ██ ██ ██ ██ ██ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						.														.
 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 						. ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ ░░ .
 -------------------------------------------------------------------------						. . . . . . . . . . . . . . . . . . . . . . . . . . . . .
 
 Que fa aquesta llavor:
 
 -> Aquesta llavor s'expandeix i recull de manera que mai surt de un array de 16x9 imitant l'expansió i encongiment del cor en cada cicle(no l'imita dibuixant-lo, però si en el nivell d'intensitat d'enxamplament).
 
 Com vaig descobrir aquesta llavor:
 
 -> Vaig descobrir aquesta llavor mentre jugaba una mica amb el programa per veure quines limitacions te (apart de no tenir una grid infinita).
 -> Miraba de probar patrons simples que puguesin tenir una vida indefinida pero que anesin rotant entre patrons.
 
 Perquè aquesta llavor:
 
 -> He escollit aquesta llavor ja que es molt simple, te uns patrons bastant curiosos al executar-se i es mante viva de forma indefinida.
 -> Te varies coses curioses:
 -> La llavor pot variar en llargada de la cadena de cel·les vives pero sempre tindra una execució similar.
 -> La llavor pasa per 17 patrons diferents pero curiosament de tots aquestos hi han dos que nomes apareixen una vegada, la propia llavor i el patro que va despres de la llavor.
 
