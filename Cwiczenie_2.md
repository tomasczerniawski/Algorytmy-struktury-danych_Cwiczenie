# Zadanie 1

Factorial
```
factorial(fact,n){
fact=1

 for(i=1;i<=n;i++){
 
 fact=fact*i
 }
}
// Jezeli podamy liczbe 5 dla n (n=5) to w foru bedzie poruwnywana od jedynki do 5 i zamiast i bedzie wpisywana o jedna jednostka wiecej czym n i puzniej z mienna fact bedzie mnozona na kazda i ktura z tego wyszla to 5!=5*4*3*2*1;
```
# Zadanie 2

Iloczyn i reszta. Realizacja z warunkem pocztkawym calkowita liczba - n, wyjsce licby(lista) - q i r
```



```
# Zadanie 3

NWD 
```



```
# Zadanie 4
Srednia arytmetyczna
 
```
obliczenie_sriedniej(n,liczby[]){
suma=0
i=0

for(i=0;i<n;i++){

  suma=liczby[i]+suma

}
  sriednia=suma/n
  return sriednia
}
Z (forem) robimy loop gdzie (n) jest ilosc liczb w tabeli i w sriodku  (fora) jest obliczana suma tych liczb podstawia zamias (liczby[i] ) ilbe na pozycji zerowej i dodaje sume poprzedniego wyniku np. (suma(0)=liczby[0](2)+suma(0) to ruwnas 2 puzniej suma(2)=liczby[1](4)+suma(2)=6) puzniej wynik jest dzielony na (n) ilosc liczb
```
# Zadanie 5
Wyszukiwanie maksimum (minimum) w tablice liczb naturalnych
```
maksymum(zbiur,max){
 max = zbiur[0]
 
	for( i = 0;i<n;i++) {
 
		if(max<zbiur[i]) {
  
			 max = zbiur[i];	
		}
	}
 return max;
 }
 
minimum(zbiur, min){
 min = zbiur[0];
 
	for( i = 0;i<n;i++) {
 
		if(min>zbiur[i]) {
  
			 min = zbiur[i];
			
		}
	}
 return min
}

Spoczatku przeruwnujemy liczbe ktura jest na zerowej pozycji jako maksymum tej tablicy i wprowadzamy petle for zeby poruwnac kazda liczbe w tabeli i sprawdzamy przez if jezeli  if jest prawdziwy to zamiast maksymuma wprowadzasie nowa zmienna itakie robi dobukej nieporuwna wszytkie liczby w tabeli 
A w minimu wzystko tosamo tyko szuk mniejszej liczby

```