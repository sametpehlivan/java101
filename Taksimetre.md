## Pratik - Taksimetre
```java
    double km ,startPrice=10,perKmPrice=2.20;
    
    Scanner reader  = new Scanner(System.in);
    
    System.out.print("KM giriniz: "); 
    km = reader.nextDouble();
    
    double totalPrice = ((perKmPrice*km) < 20 ?  20:(perKmPrice*km)) +   startPrice;
    System.out.print("Ödenecek tutar : " + totalPrice);
```