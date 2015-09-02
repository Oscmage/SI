

# Pass 1

### Välkommen!

#### Info innan vi kör igång. Om det skulle vara så att du upplever att SI-passet saknar något eller det var för lätt/svårt så kontakta mig på "oscarev@student.chalmers.se", så skall jag göra mitt bästa för att ditt önskemål skall lösas till nästa gång :)! Jag är här för er skull inte för min egen så fråga på! 


## Uppgift 1
### Vad blir outputen när man kör följande loopar?

#### a)
     for(int i = 1; i <= 5; i++) {
         System.out.println(i*i);
     }

#### b)

   for(int i = 1; i <= 10; i++) {
       if(i%2 == 0) {
           System.out.println(i);
       }
   }

#### c)
     for(int i = 1; i <= 3; i++) {
         for(int j = 1; j <= 3; j++) {
             System.out.println(i*j);
         }
     }

#### d)
     for(int i = 1; i <= 3; i++) {
         for(int j = 1; j <= 3; j++) {
             if((i*j)%2 == 0) {
                 System.out.println(i*j);
             }
         }
     }

#### e)
     for(int i = 1; i <= 3; i++) {
         for(int j = 3; j >= 1; j--) {
             System.out.println(i*j);
         }
     }

#### f)
     for(int i = 3; i >= 1; i--) {
         for(int j = 3; j >= 1; j--) {
             System.out.println(i*j);
         }
     }

#### g)
    for(int i = 1; i <= 5; i++) {
         if(i%2 == 0) {
             for(int j = 1; j <= 3; j++) {
                 System.out.println(i*j);
             }
         }
     }


## Uppgift 2

a) Hur skapar man en klass?

b) Hur skapar man en metod?

c) Vad är ett objekt? Beskriv det så bra ni kan i gruppen!

d) Vad är skillnaden och likheter mellan en primitiv typ och en klasstyp?

e) Säg att du vill manipulera en sträng(/String) t.ex. skriva ut den baklänges. Vart någonstans är ett bra ställe att börja leta information på om du inte vet vilka metoder strängar har?

## Uppgift 3
Fibonaccis talföljd är följande: 0 1 1 2 3 5 8 13 ...

Den brukar definieras såhär:

    fib(1) = 1
    fib(2) = 1
    fib(n) = fib(n-1) + fib(n-2) , n > 2

Skriv ett program som skriver ut de 10 första fibonacci-talen. Använd for- och while-loopar.

## Uppgift 4
Skriv en metod som givet ett heltal n skriver ut de n första fibonacci-talen.
(ex. om n = 4 skall “0 1 1 2” skrivas ut i konsolen)

## Uppgift 5
Skriv ett program som skriver ut följande rutnät

        + + + + +
        + + + + +
        + + + + +
        + + + + +

## Uppgift 6
Skriv ett program som skriver ut triangeln nedan:

    00000
      0000
        000
          00
            0

