## Pratik - Daire Alan
```java
    double r,a;
    Scanner reader = new Scanner(System.in);
    System.out.print("Yarıçap uzunluğu giriniz: ");
    r = reader.nextDouble();
    System.out.print("merkez açısının ölçüsü: ");
    a = reader.nextDouble();
    System.out.println("Alan : " +(3.14*a*r*r)/360 );
```