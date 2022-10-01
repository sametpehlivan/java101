## Pratik - Hesap Makinesi
```java
	double a,b ;
    int islem = -1;
    Scanner reader  = new Scanner(System.in);
    System.out.print("Birinci sayıyı giriniz: ");
    a = reader.nextDouble();
    System.out.print("İkinci sayıyı giriniz: ");
    b = reader.nextDouble();
    System.out.println("İşlemler:1-Toplama,2-Çıkarma.3-Çarpma,4-Bölme");
    
    islem = reader.nextInt();
    switch(islem) {
        case 1:
            System.out.print(a+b);
            break;
        case 2:
            System.out.print(a-b);
            break;
        case 3:
            System.out.print(a*b);
            break;
        case 4:
            if(b==0) {
                System.out.print("Geçersiz işlem");
                break;
            }
            System.out.print(a/b);
            break;
        default:
            System.out.print("Geçersiz işlem");
    }
		

```