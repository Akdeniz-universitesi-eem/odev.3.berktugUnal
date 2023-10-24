# odev.3.berktugUnal

//4.SORU
public class UcBasamakliSayi {
    public static void main(String[] args) {
        for (int abc = 100; abc <= 999; abc++) {//değişkenini 100'den başlatır ve 999'a kadar olan üç basamaklı sayıları kontrol eder
            int cba = Integer.parseInt(new StringBuilder(String.valueOf(abc)).reverse().toString()); //abc sayısını tersten yazarak elde edilen sayıyı temsil eder.

            if (cba > abc && isPrime(abc) && isPrime(cba) && isPrime(abc % 100) &&
                    isPrime(abc / 10 % 10 * 10 + abc / 100) && isPrime(abc / 10 % 10 * 10 + abc % 10) &&
                    isPrime(abc % 100) && isPrime(abc % 10 * 10 + abc / 100)) {
                System.out.println("Üç basamaklı sayı: " + abc);
            }
/*isPrime(abc): abc bir asal sayı olmalıdır.
        isPrime(cba): cba bir asal sayı olmalıdır
        isPrime(abc % 100): bc asal olmalıdır
        isPrime(abc / 10 % 10 * 10 + abc / 100): bc asal olmalıdır
        isPrime(abc / 10); ab asal olmalıdır
        isPrime(abc / 10) % 10; cb asal olmalıdır
       isPrime(abc / 100 bc asal olmalıdır   isPrime(cba % 100) ba asal olmalıdır*/        }
    }

    // Bir sayının asal olup olmadığını kontrol eden fonksiyon
    public static boolean isPrime(int num) {
        if (num <= 1) {
            return false;
        }
        for (int i = 2; i <= Math.sqrt(num); i++) {
            if (num % i == 0) {
                return false;
            }
        }
        return true;
    }
}

