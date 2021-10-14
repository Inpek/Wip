Chap 4 : Etude de fonctions

I - Rappels :

Def: Soient a et b deux réels tels que a<b. Alors les intervalles de R sont décrits par 

[a,b] = {x, a<=x<=b}
[a,b[ = {x, a<=x<b }
]a,b] = {x, a<x<=b}
]a,b[ = {x, a<x<b }

]a,+inf[ = {x, a<=x }
]a,+inf[ = {x, a<x }
]-inf,b] = {x, x<=b }
]-inf,b[ = {x, x<b }

Rq: R=]-inf,+inf[
	R+=[O,+inf[
	R*= R\{O}
	  = ]-inf,0[U]0,+inf[
	  		 (union)

II - Notion de fonction

Def: Soient E et F deux ensembles 
On appelle fonction de E dans F tout "procédé" qui à certains
élements de E associe, pour chacun,
un unique élément de F. On la note f:E--> F


Exple :
[1] Fonctions affines :

f: R --> R
x |--> ax+b

[2] Fonction carré :
f: R --> R
   x |--> x^2

A - Image et antécédent

def : Soit f:E-->F une fonction et soit xËE. Alors :

[1] f(x) est l'image de x par f.
[2] x est un antécédent de f(x)

[3] L'Image de la fonction f est l'ensemble noté Im(F) de tous les éléments de F qui possèdent
un antécédent par f; Autrement dit Im(f)={yEF, il existe xËE tel que f(x)=y}

Exemple : Prenons f: R --> R
					 x|--> x^2

[1] L'image de 2 par f est 4.
[2]            5           25
[3] Un antécédent de 9 par d est 3
[4] Un autre                    -3
[5] -1 n'a pas d'antécédent par f.

Rq: 
[1] Un élément n'a qu'une seule image
[2] Il peut y avoir plusieurs ou aucun antécédents.

Def : SOit f:E-->F est une fonction. L'ensemble de définition de f est le sous ensemble de 
E, noté Df, contstitué des élément de E auquels f fait correspondre un éléent de F.
Autrement dit, il s'agit de ce sont les c pour lesquel, on peut calculer f(x).

Exple :
[1] Pour f : R --> R
			 x --> x^2
ona Df = R
[2] Pour g: R --> R
			x --> 1/x

on a Dg = R* = R\{0}

[3] Pour h : R --> R
			 x --> r.c(X)

on a Dh=R+r

Exple : 

[1] Si f: R  --> R
		  x |--> r.c(x+11).

	alors Df = [-11,+inf]
	a x s'associe
	x+11>=0
	x>-11

[2] Si f: R |--> R
		  x |--> x-1/x+3

	alors Df = ]-inf,-3[U]-3,+inf[
			 = R\{-3}

[3] Si f: x |--> x+3/5x-3
	
	alors Df = R {3/5}

[4] Si g: x |--> r.c(x-1)(-x+3) Dg = [1,3] 
[5] Si h: x |--> r.c(x^2-1)/-x^2+9 Dh = []
[6] Si i: x |--> r.c(x+1/x-1) 


