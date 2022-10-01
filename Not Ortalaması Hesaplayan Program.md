## Pratik - Not Ortalaması Hesaplayan Program

```java  
    int matematikNotu = 0,fizikNotu = 0,turkceNotu = 0,kimyaNotu=0,
    tarihNotu = 0,muzikNotu = 0;
    System.out.println("**** Donem Notu Hesaplama ***"); 
    Scanner reader  = new Scanner(System.in);
    
    System.out.print("Matematik notunuzu giriniz: "); 
    matematikNotu = Integer.parseInt(reader.nextLine());
    
    
    System.out.print("Fizik notunuzu giriniz: "); 
    fizikNotu = Integer.parseInt(reader.nextLine());
    
    System.out.print("Türkçe notunuzu giriniz: "); 
    turkceNotu = Integer.parseInt(reader.next());
    
    System.out.print("Kimya notunuzu giriniz: "); 
    kimyaNotu = Integer.parseInt(reader.next());
    
    System.out.print("Tarih notunuzu giriniz: "); 
    tarihNotu = Integer.parseInt(reader.next());
    
    System.out.print("Muzik notunuzu giriniz: "); 
    muzikNotu = Integer.parseInt(reader.next());

    float ort = (matematikNotu + fizikNotu + turkceNotu + kimyaNotu + tarihNotu + muzikNotu)/6;
    String sonuc = ort >= 60 ? "Geçti":"Kaldı"; 
    System.out.println("Ortalama Notunuz: " + ort + "\n" + "Sonucunuz: " + sonuc ); 
```