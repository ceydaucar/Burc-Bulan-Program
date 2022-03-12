# Burc-Bulan-Program
Patika.dev > Java101 > Koşullu İfadeler ve Kod Blokları > Pratik6 - Burç Bulan Program

## Aynı örneği switch-case kullanmadan yapınız.
- Koç Burcu : 21 Mart - 20 Nisan
- Boğa Burcu : 21 Nisan - 21 Mayıs
- İkizler Burcu : 22 Mayıs - 22 Haziran
- Yengeç Burcu : 23 Haziran - 22 Temmuz
- Aslan Burcu : 23 Temmuz - 22 Ağustos
- Başak Burcu : 23 Ağustos - 22 Eylül
- Terazi Burcu : 23 Eylül - 22 Ekim
- Akrep Burcu : 23 Ekim - 21 Kasım
- Yay Burcu : 22 Kasım - 21 Aralık
- Oğlak Burcu : 22 Aralık - 21 Ocak
- Kova Burcu : 22 Ocak - 19 Şubat
- Balık Burcu : 20 Şubat - 20 Mart

        import java.util.Scanner;

        public class Main {
        
            public static void main(String[] args) {

                Scanner input = new Scanner(System.in);
                int month, day;
                String burc = "";

                System.out.print("Doğduğunuz ay : ");
                month = input.nextInt();

                System.out.print("Doğduğunuz gün : ");
                day = input.nextInt();
                
                if (month < 1 || month > 12) {
                    System.out.println("You entered an incorrect month. Please try again...");
                }
                
                else {
                    if (month == 1) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Oğlak burcu";
                            else
                                burc = "Kova burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 2) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Kova burcu";
                            else
                                burc = "Balık burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 3) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Balık burcu";
                            else
                                burc = "Koç burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 4) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Koç burcu";
                            else
                                burc = "Boğa burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 5) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Boğa burcu";
                            else
                                burc = "İkizler burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 6) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "İkizler burcu";
                            else
                                burc = "Yengeç burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 7) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Yengeç burcu";
                            else
                                burc = "Aslan burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 8) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Aslan burcu";
                            else
                                burc = "Başak burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 9) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Başak burcu";
                            else
                                burc = "Terazi burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 10) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Terazi burcu";
                            else
                                burc = "Akrep burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 11) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Akrep burcu";
                            else
                                burc = "Yay burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                    if (month == 12) {
                        if (day >= 1 && day <= 31) {
                            if (day < 22)
                                burc = "Yay burcu";
                            else
                                burc = "Oğlak burcu ";
                         }
                         
                         else {
                            System.out.println("You entered an incorrect day. Please try again...");
                         }
                    }


                        System.out.print("Burcunuz : " + burc);
                  }
             }
        }
