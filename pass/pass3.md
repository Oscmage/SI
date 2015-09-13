# Pass 3

## Välkommen till pass 3!

Idag kommer det blir mera kodning och mindre "förklara ordet"! Whoho!

Saknar du något?

Maila: oscarev@student.chalmers.se

## Uppgift 1
Vad skrivs ut då man skriver in bokstäverna ‘a’ till ‘e’ i metoden som heter “performSubTask(char subTask)”? (Koda inte utan tänk efter istället).

```
public class Uppg1 {
	public static void main(String[] arg){
		performSubTask('a');
	}

	public static void performSubTask(char subTask) {
		switch (subTask) {
		case 'a':
			while (true) {
				System.out.println("1a");
			}
			break;
		case 'b':
			int i = 0;
			while (i < 10) {
				i++;
				System.out.println("1b");
			}
			break;
		case 'c':
			boolean trueOrFalse = true;
			while (trueOrFalse) {
				System.out.println("1c");
				trueOrFalse = false;
			}
			break;
		case 'd':
			boolean falskt = false;
			boolean sant = true;
			while (sant || falskt) {
				System.out.println("1d");
				if (sant && !falskt) {
					sant = false;
				}
			}
			break;
		case 'e':
			while (false || (((true && true) && (false || !false)))) {
				System.out.println("1e");
			}
		}
	}
}

```

## Uppgift 2

Vad skrivs ut?

```
	public class A {
	    public void skriv() {
	        System.out.println("A");
	    }
	}

	public class B extends A {
	    public void skriv() {
	        System.out.println("B");
	    }
	}

	public class Utskrift {
	    public static void main(String[] arg) {

	        A a  = new A();
	        A a2 = new B();
	        B b  = new B();
	       
	        a.skriv();
	        a2.skriv();
	        b.skriv();
	    }
	}
```


## Uppgift 3

Skriv nicket "oscmage" eller annat vackert nick med hjälp av variablerna nedan ;)

	char[] roxanna = new char[] {'e','R', 'o', 'x', 'a', 'm', 'n', 'a'};
	char[] styrbjorn = new char[] {'S', 't', 'y', 'r', 'b', 'j', 'o', 'r', 'n'};
	char[] isotop = new char[] {'I', 's', 'o', 't', 'o','c', 'p','g'};

## Uppgift 4  

Sant eller falskt?

	a) 	Uttrycket nedan kompilerar ok. (Antag att o inte deklarerats tidigare)
			Object o = new Integer(5);

	b) 	Uttrycket nedan evalueras till sant
			new Integer(11) == new Integer(11)

	c) 	En statisk medlemsmetod kan referera icke statiska variabler i samma 
		klass men endast efter att en instans av klassen skapats.

	d)	När ett objekt skickas som argumet till en metod så kan metoden 
		ändra objektet.

## Uppgift 5

a) 
	Förklara innebörden av:

		* this
		* Konstruktor
b)

Är det möjligt att definiera en klass såhär? Motivera ditt svar.

```

public class Kluring {
    private String name;
    private int age;
    private int hp;
    private boolean happy;


    public Kluring(int age){
        this.age = age;
    }

    public Kluring(String name,int age,int hp,boolean happy){
        this.name = name;
        this.age = age;
        this.hp = hp;
        this.happy = happy;
    }
    
    public Kluring(String name, int age,int hp){
        this.name = name;
        this.age = age;
        this.hp = hp;
    }
    
    public void lowerHp(int decrease){
        this.hp = hp - decrease;
    }
    
    public void lowerHp(){
        this.hp = hp - 10;
    }
}
```

## Uppgift 6

Skapa en klass `Monster`. Ett monster har en instansvariabel, `damage`, som sätts när monstret skapas till en siffra mellan 1 och 30.

Skapa också en klass `HealingPotion` som har en instansvariabel `healingPower` som fungerar på samma sätt, men har ett värde mellan 1 och 5.

Testa dina klasser i din main metod så att de funkar som de ska.

## Uppgift 7

Skapa en klass `Player`. En spelare ska ha ett namn och ett visst antal `healthPoints`, förslagsvis 100. 

Utöver detta ska en player ha två metoder, en för att slåss mot ett monster, och en för att helas av en healing potion. Den första metoden ska ta ett monster som argument, och den andra en healing potion.

När spelarens metod för att möta ett monster anropas så förlorar spelaren samma antal health points som monstret gör skada. Om spelaren dör ska ett lämpligt meddelande med spelarens namn skrivas ut, och programmet avslutsas.

Om spelarens metod för att helas anropas ska spelarens health points öka lika mycket som potionens healing power.

**Hur avslutar man ett program i Java? Googla!** 

Testa din Player-klass i main metoden.

## Uppgift 8

Lägg till att programmet ska vila i två sekunder mellan det att spelaren stöter på ett monster eller en healing potion, och att spelarens health points uppdateras. Lägg också in ett meddelande i båda metoderna som berättar vad som händer: att spelaren stött på ett monster eller en healing potion innan fördröjningen, och hur mycket skada eller extraliv som spelaren får efter.
