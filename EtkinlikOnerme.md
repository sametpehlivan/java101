## Pratik - Hava Sıcaklığına Göre Etkinlik Önerme
    int heat;
    String message = "Kod yazabilirsin";
    Scanner reader = new Scanner(System.in);
    
    System.out.print("Hava Sıcaklığını(C) Giriniz: ");
    heat = reader.nextInt();
    
    if(heat<5) message += "\nKayak yapabilirsin";
    if(heat >= 5 && heat < 15 ) message+= "\nSinemaya gidebilirsin";
    if(heat >= 10 && heat < 25 ) message+="\nPikniğe Gidebilirsin";
    if(heat >= 25) message+= "\nYüzmeye Gidebilirsin";
    
    System.out.print(message);