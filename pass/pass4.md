# Välkommen till pass 4!

Oscar Evertsson, "Oscmage"
Mail: oscarev@student.chalmers.se

## 1

Skriv följande metoder:

a)

En metod som får en int­array som parameter och skriver ut alla
siffror i array:en i tur och ordning.

b)

En metod som kopierar en int­array genom att få en array som
parameter och returnera en kopia av arrayen.

c)

En metod som skriver över en int­array så att alla dess siffror
ändras till 0.

## 2

a)

Varför har man arv i java?

b) 

När vill man ärva/implementera:

* En klass?
* En abstrakt klass (Abstract class)?
* Ett gränssnitt (Interface)?

c)

Vad innebär ordet "super" när det skrivs i en konstruktor.

## 3

Sant eller falskt

* Interfaces i Java kan innehålla privata instansvariabler
* Man kan instansiera abstrakta klasser
* Abstrakta metoder i en klass måste implementeras av subklasser
* En klass kan ärva från två andra klasser
* Ett interface kan ärva från ett annat interface
* Ett interface kan ärva från flera interface

## 4

Nämn ett tillfälle då det kan vara bra att använda static variabler i en klass.

## 5

Skriv en korrekt equals metod för följande klass.

```
public class School {
	private int yearCreated;
	private String name;
	private boolean happyTeachers;
	private boolean happyStudents;

	public School(int yearCreated,String name,boolean happyTeachers,boolean happyStudents) {
		this.yearCreated = yearCreated;
		this.name = name;
		this.happyTeachers = happyTeachers;
		this.happyStudents = happyStudents;
	}

	public int getYearCreated() {
		return this.yearCreated;
	}

	public int getName() {
		return this.name;
	}

	public int getHappyStudents() {
		return this.happyStudents;
	}

	public int getHappyTeachers() {
		return this.happyTeachers;
	}

	//Skriv denna metod :D!
	public boolean equals....
}
```



