# Välkommen till pass 5!

## 1

Ta ett nytt papper. Samarbeta i gruppen runt ert bord och skriv en klass FÖRHAND som representerar en Chalmers­student.

	A. Tänk ut vilka egenskaper (klassvariabler och instansvariabler) som studenten ska ha och skriv kod för dessa.

	B. Tänk ut vilka beteenden (metoder) som studenten ska ha och skriv kod för dessa.

	C. Tänk ut hur studenten ska skapas och skriv en eller flera konstruktorer för detta.

	D. Ge variabler och metoder förklarande namn så att det blir lätt att förstå (kod­kommentarer ska inte behövas).

## 2 

Titta på klassen nedan:
```
public class Cat {
	private static int nbrOfLegs = 4;
	private String name;

	public Cat(String catName) {
		this.name = catName;
	}

	public static int getNbrOfLegs() {
		return this.nbrOfLegs;
	}

	public String getName() {
		return this.name;
	}
}
```
a) Titta på denna testklass för katten:

```
public class TestCat {
	public static void main(String[] args) {
		Cat cat1 = new Cat("Sven");
		Cat cat2 = new Cat("Nils");

		String cat1Name = cat1.getName();
		String cat2Name = cat2.getName();
		System.out.println("Name of cat1: " + cat1Name);
		System.out.println("Name of cat2: " cat2Name);

		int numberOfLegs = Cat.getNbrOfLegs();
		System.out.println("The number of legs is : " + numberOfLegs);
	}
}
```

b) 
Varför skriver man en katt-instans framför anrop av getName()?

c) Varför skriver man Cat framför anrop av getNbrOfLegs()?


## 3 

Ofta vill man för tydlighetens skull ha samma namn på en variabel som på parametern som skickas in. Hur gör man då? Fyll i koden som saknas nedan:

```
public class Dog {
	private String dogName;

	public Dog(String dogName){
		/*
		* Sätt Dog's dogName­variabel till samma som dogName­parametern
		*/
￼￼	} 
}
```

## 4

Titta på klasserna nedan och notera särskilt ordet abstract i Animal­klassen:

```
public abstract class Animal {
	private int nbrOfLegs;
	private String name;
	private boolean isAlive;

	public Animal(int nbrOfLegs, String name){
		this.nbrOfLegs = nbrOfLegs; this.name = name;
		isAlive = true;
	}

	public int getNbrOfLegs(){
		return nbrOfLegs; 
	}

	public String getName(){ 
		return name;
	}

	public void giveVirus(){
		isAlive = false; 
	}
}

public class Zebra extends Animal{

	public Zebra(int nbrOfLegs, String name) {
		super(nbrOfLegs, name); 
	}
}

public class Giraffe extends Zebra{
	private double neckLength;

	public Giraffe(int nbrOfLegs, String name, double neckLength){
		super(nbrOfLegs, name);
		this.neckLength = neckLength; 
	}

	public double getNeckLength(){ 
		return neckLength;
	} 
}

```

a)
Vad är en abstrakt klass? Diskutera.

b)
Vad är vitsen med att ha Animal­klassen abstrakt? Skulle den inte lika gärna kunna vara en helt vanlig icke­abstrakt klass?

c)
Hitta på ett nytt djur som ärver den abstrakta Animal­klassen. Skriv kod för klassen med papper och penna.

d)
Skriv ett testprogram som skapar ett av varje djur och testar dess egenskaper.

## 5

Titta på klasserna nedan och notera särskilt orden interface och implements:

public interface IDog { 
	public String doTrick();
}

public class Poodle implements IDog{ 

	@Override
	public String doTrick() { 
		return "Jumping";
	} 
}

public class GoldenRetriever implements IDog{ 

	@Override
	public String doTrick() { 
		return "Fetches a ball";
	} 
}

public class Doge implements IDog{

 	@Override
	public String doTrick() { 
		return "Says wow";
	} 
}

a)
Vad är ett interface? Diskutera.

b)
Vad betyder implements i de olika hundklasserna? Diskutera.

c)
Hitta på en ny hund med ett nytt trick och skriv för detta en klass som implementerar IDog­interfacet.

d)
Det kan vara klurigt i början att förstå vad man ska ha interface till, så vi ska nu öva på ett tillfälle då man har nytta av det.
Skriv en testklass som kör alla hundarnas tricks.

e)
Kan man använda IDog­interfacet för att for­loopa igenom alla hundar och köra deras tricks? Diskutera och fråga om hjälp om ni kör fast.

## 6
Sten sax påse­spel

* Skriv ett program för stensaxpåse
* Gör så att första spelarenkan mata in en siffra där 1 = sten, 2 = sax och 3 = påse.
* Därefter ge spelare 2 samma möjlighet
* Se till så att programmet skriver ut vem som vann eller om det blev lika

