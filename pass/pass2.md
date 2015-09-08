# Pass 2

## Välkommen till pass nummer 2!

## 1) Diskutera skillnaden mellan följande två rader:

	int int1 = 1;
	Integer integer1 = new Integer(1);

## 2)

 a)  På vilka olika sätt kan man ändra siffran i int1 respektive i integer1 till värdet 2? 

 b) Vad är det som gör att man inte kan göra på samma sätt med int och Integer i uppg a)? 

 c) Försök lista ut när det bäst lämpar sig att använda sig av.

 * primitivatyper(som int)
 * klasstyper(som Integer)

## 3) Förklara innebörden av följande begrepp:

* final
* konstruktor
* getter
* setter
* gränssnitt

## 4) Förklara skillnaden mellan följande begrepp:

* klass vs objekt
* instansvariabel vs klassvariabel
* instansmetod vs klassmetod
* private vs public
* equals() vs "=="


## 5) När man kodar i java är det viktigt med bra namn på typer och metoder för att koden ska kunna förstås av andra (och en själv). 
Förklara, rad för rad, vad ni tror att koden nedan gör. Använd namnen på typerna och metoderna som vägledning: 


```
int radius = 10; 
double speed = 0; 	
String color = “Black”; 
char number = ‘8’; 
boolean isDownInAPocket = false; 

PoolBall biljardBoll = new PoolBall(radius, speed, color, number, isDownInAPocket); 
biljardBoll.setSpeed(10); 
biljardBoll.setDownInPocket(true); 
biljardBoll.setSpeed(0); 
System.out.println("The color of the ball is: " + 	biljardBoll.getColor());

```
## 6) Vad skrivs ut?

```
public static void main(String [] args){
	 int tal = 5;

	if(tal < 4) {  	
		System.out.println("Small");
	} else if(tal >= 4 && tal <= 8) {  
		System.out.println("Medium"); 
	} else {
		System.out.println("Big");
	 }

	switch (tal) {
	  	case 4: System.out.println("Small");
	   		break;  	
	  	case 5:  System.out.println("Medium");
	  		break;
  	  	case 6:  System.out.println("Big"); 
  	 		break; 
	} 
}
```
## 7) Skriv längre program

Skriv en kodsnutt som tar in input från användaren och sedan skriver ut detta baklänges. Om användaren skriver in "TIXE" (dvs EXIT baklänges) skall programmet stängas ner och sluta fråga användaren för mer inputs. 

Innan ni börjar med uppgiften fundera/diskutera över följande frågeställningar:

1. Vad kan vara bra att tänka på när DU ser större uppgifter?
2. Dela med er i gruppen hur ni tänker kring problemlösningen och vad ni tror är smartaste sättet att gå tillväga.













