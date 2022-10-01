## Pratik - KDV Tutarı Hesaplayan Program

```java 
    double tutar;
    Scanner reader = new Scanner(System.in);

    System.out.print("Ucret Tutarını giriniz: ");
    tutar = Double.parseDouble(reader.next());

    double kdvOran = tutar >1000 ?  0.08 : 0.18; 

    System.out.println("KDV Oranı: " + kdvOran );
    System.out.println("KDV Tutarı: " + kdvOran * tutar );
    System.out.println("KDV Dahil Fiyat: " + (tutar + (kdvOran * tutar)) );
```