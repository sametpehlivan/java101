## Pratik - Kullanıcı Girişi

```java
    String userName = "samet";
    String password="123456";
    
    String inputUserName="";
    String inputPassword="";
    
    Scanner reader = new Scanner(System.in);
    
    System.out.print("Kullanıcı adınız: ");
    inputUserName = reader.nextLine();
    
    System.out.print("Şifreniz: ");
    inputPassword = reader.nextLine();
    
    
    
    if(userName.equals(inputUserName) && password.equals(inputPassword)) {
        System.out.print("Giriş başarılı gardaş ");
    }
    else if (userName.equals(inputUserName) && !password.equals(inputPassword)) {
        System.out.print("Şifre yanlış ....\n");
        
        boolean flag = true;
        while(flag) {
        
            
            System.out.print("İşlem Seçiniz\n" + "1-Şifrenizi Değiştirme\n" + "2-Çıkış\n");
            int islem = reader.nextInt();
            switch(islem) {
                case 1: 
                    System.out.print("Yeni şifrenizi giriniz: ");
                    inputPassword = reader.next();
                    if(password.equals(inputPassword)) {
                        System.out.print("Şifreniz eski şifrenizle aynı olamaz\n");
                        break;
                    }
                    System.out.print("Şifreniz değiştirildi,hayırlı uğurlu olsun");
                    password = inputPassword;
                    flag = false;
                    break;
                case 2:
                    System.out.print("Çıkış yapılıyor");
                    flag = false;
                    break;
                default:
                    System.out.print("Geçersiz işlem");
                    break;
            }
            
        }
    }
    else {
        System.out.print("Bilgilerinizi kontrol ediniz");
    }
		
```