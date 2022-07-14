# Uslu-_sayi_bulma.java
www.patika.dev Uslu sayilar





        import java.util.Scanner;

        public class us_alma {
        public static void main(String[] args) {
        int n,k,sonuc;
        System.out.println("Lutfen Ussu alinacak sayiyi giriniz:");
        Scanner input=new Scanner(System.in);
        n=input.nextInt();
        System.out.println("Lutfen Us olacak sayiyi giriniz:");
        k=input.nextInt();
        sonuc=1;
        //k defa n yi yan yana carp

        for (int i =1;i<=k;i++){
            sonuc*=n;
        }
        System.out.println("Sonuc:"+sonuc);
    }
}
