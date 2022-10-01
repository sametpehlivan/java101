## Ödev - Manav Kasa Programı

```java
    double armutPriceKg = 2.14,elmaPriceKg=3.67,domatesPriceKg=1.11,muzPriceKg = 0.95,patlıcanPriceKg=5;
    int armutKg,elmaKg,domatesKg,muzKg,patlicanKg;
    Scanner reader =  new Scanner(System.in);
    
    System.out.print("Elma Kaç Kilo ? : ");
    elmaKg = reader.nextInt();
    
    System.out.print("Armut Kaç Kilo ? : ");
    armutKg = reader.nextInt();
    
    System.out.print("Domates Kaç Kilo ? : ");
    domatesKg = reader.nextInt();
    
    System.out.print("Muz Kaç Kilo ? : ");
    muzKg = reader.nextInt();
    
    System.out.print("Patlıcan Kaç Kilo ? : ");
    patlicanKg = reader.nextInt();

    double total = (elmaKg*elmaPriceKg + armutPriceKg*armutKg + domatesPriceKg*domatesKg + muzPriceKg*muzKg + patlıcanPriceKg*patlicanKg);
    System.out.print("Toplam Tutar : "+total+" TL");
```