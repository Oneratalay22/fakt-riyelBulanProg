import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Faktöriyel Sayısı Giriniz : ");
        int n = input.nextInt();
        int i=1;
        int total=1;

        while (i<=n){
            total*=i;
            i++;
        }
        System.out.println(n+"Faktöriyel :"+total);


    }

}
