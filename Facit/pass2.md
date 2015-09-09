# Facit pass 2

## 1) 

	Primitivtyp vs klasstyp se boken

## 2) 

 a) 
 int1 = 2;
 integer1 = new Integer(2);

 b) 
 integer1 är en klasstyp om du skriver integer1 = 2; ändrar du den minnesplats som redan existerar

 c) 
 Se föreläsning 5

## 3)
	
	Se boken

## 4)

	Se boken

## 5)

En klass som skall representera en biljardboll.

## 6)

Medium
Medium

## 7)

1. Mitt tips handlar om att dela upp uppgiften i mindre bitar som sedan löses "one by one". I detta fall börja med att skriva något som gör att användaren frågas för input tex 

```
Scanner in = new Scanner(System.in);
String str;
System.out.println("Var vänlig att skriva in något");
while(in.hasNext()) {
	str = in.next();
	System.out.println("Var vänlig att skriv in något");
}

```

2. Därefter lösa problemet med hur strängen skall skrivas ut baklänges.

3. Samt se till att programmet stängs ner när "TIXE" skrivs.