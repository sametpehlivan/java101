## Pratik - Sayıları Büyükten Küçüğe Sıralama
```java
    int a,b,c;
    
    String  message="";
    Scanner reader = new Scanner(System.in);
    
    System.out.print("a sayısını giriniz");
    a = reader.nextInt();
    
    System.out.print("b sayısını giriniz");
    b = reader.nextInt();
    
    System.out.print("c sayısını giriniz");
    c = reader.nextInt();
    if(a >= c && a >=b  ) {
        message="a";
        if(b >= c ) {
                message += (a > b ?  " > b ":" = b ") + (b > c ? "> c":"= c");
        }
        else 
        {
            message += (a > c ? " > c ":" = c ") + ("> b");
        }
    }
    else if(b > a && b >= c) {
        message="b";
        if(a >= c) {
            message += (" > a ")+ (a > c ? "> c":"= c");
        }
        else {
            message += (b > c ? " > c ": " = c ") + ("> a");
        }
    }
    else if(c > a && c >b ){
        message = "c";
        if(a >= b) {
            message += (" > a " )+(a > b ? "> b":"= b");
        }
        else {
            message += (" > b ") + ("> a");
        }
    }
    System.out.print(message);

```