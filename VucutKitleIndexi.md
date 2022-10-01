## Odev - Vücut Kitle İndeksi Hesaplayan Program
```java
	double boy,kilo;
    Scanner reader = new Scanner(System.in);
    System.out.print("Boyunuzun uzunluğunu(metre) giriniz (Orn: 1,75): ");
    boy = reader.nextDouble();
    System.out.print("Kilonuzu giriniz(kg): ");
    kilo = reader.nextDouble();
    System.out.print("Vücut Kitle İndexiniz: " + kilo/(boy*boy));
		 
```