## Pratik - Kenarları bilinen üçgenin alanı 
```java
    double a,b,c;
    Scanner reader = new Scanner(System.in);
    System.out.print("Birinci kenarın uzunluğu giriniz.");
    a = reader.nextDouble();
    System.out.print("İkinci kenarın uzunluğu giriniz.");
    b = reader.nextDouble();
    System.out.print("Üçüncü kenarın uzunluğu giriniz.");
    c = reader.nextDouble();
    
    double cevre = (a+b+c);
    
    double u = cevre/2;
        
    double alan  = Math.sqrt(u* (u-a)*(u-b)*(u-c));
    System.out.print(alan);
```