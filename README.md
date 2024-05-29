public class Main {
    public static void main(String[] args) {
        int number = 4;
        int number1 = number * number;
        int number2 = number * number * number;
        System.out.println("Sabit sayı: "+ number);
        System.out.println("Sayının karesi: "+ number1);
        System.out.println("Sayının küpü: "+ number2);
        String ad = "Betül";
        int age = 39;
        String city = "İstanbul";
        System.out.println("Adım: "+ ad +" "+ "Yaşım: "+ age);
        System.out.println(age);
        System.out.println("Şehrim: " + city);
        System.out.println(ad);
    }
}
public class AlininDegeri {
    public static void main( String[] args){
        String name = "Ali";
        int age = 23;
        double height = 1.86;
        double money = 635176.8;
        System.out.println("Benim adım "+ name+  ", yaşım " + age+", boyum " +height+ " metre ve cebimde " +money+ "TL para var.");
        System.out.println("Benim adım "+ name+ ".\t Yaşım: " + age+"\nBoyum " +height+ " metre.  \tBanka hesabımda " +money+ "TL para var.");
    }
}
public class NewNumber {
    public static void main(String[] args) {
        int a = 10;
        int b;
        b = a;
        System.out.println(b);
    }
}
public class Car {
    public static void main(String[] args) {
        int year = 2022;
        String brand = "Toyota";
        String model = "Corolla";
        String color = "Beyaz";
        long price = 1200000L;
        System.out.println(year +" "+ brand +" "+ model +" "+ color +" "+ price +" TRY");
    }
}
public class Plus50 {
    public static void main(String[] args) {
        int a = 6;
        a += 50;
        System.out.println(a);
    }
}
public class Arithmetics {
    public static void main(String[] args) {
        int a = 3, b = 8;
        int toplam = a + b;
        int cikar = a - b;
        int bolme = a / b;
        int carpma = a * b;
        int modulus = a % b;
        System.out.println("toplam = " + toplam);
        System.out.println("cikar = " + cikar);
        System.out.println("bolme = " + bolme);
        System.out.println("carpma = " + carpma);
        System.out.println("modulus = " + modulus);
    }
}
public class Numbers {
    public static void main(String[] args) {
        float price = 123.456f;
        int Alis_price = (int) price;
        byte Velis_price = (byte) Alis_price;
        int total_price = Alis_price + Velis_price;
        System.out.println(Alis_price);
        System.out.println(Velis_price);
        System.out.println(total_price);
    }
}
public class NightOut {
    public static void main(String[] args) {
        boolean havaGuzel = true;
        boolean yeterliPara = true;
        boolean nightOut = havaGuzel && yeterliPara;
        System.out.println(nightOut);

    }
}
public class Allin {
    public static void main(String[] args) {
        int a = 5;
        int b = 8;
        int c = 12;
        boolean first = (a+b+c == 25);
        boolean second = (a+b > c);
        boolean third = (a * a < b);
        boolean fourth = (b == (a + c)/2);
        boolean fifth = (c < a+b);
        System.out.println("a, b ve c'nin toplamı 25'e eşit mi? "+first);
        System.out.println("a ve b'nin toplamı c'den büyük mü? " +second);
        System.out.println("a'nın karesi b'den küçük mü? "+third);
        System.out.println("b, a ve c arasında ortanca değer mi? "+fourth);
        System.out.println("c, a ve b'nin toplamından küçük mü? "+fifth);
    }
}
