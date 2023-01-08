# kullanicii
Kullanıcı adı ve şifre girişi 
package day01;

import java.util.Scanner;

public class kullanıcı {
    public static void main(String[] args) {
        String  userName, password;

        Scanner inp=new Scanner(System.in);

        System.out.println("Kullancı Adınızı Giriniz= ");
        userName= inp.nextLine();

        System.out.println("Şifrenizi Giriniz= ");
        password= inp.nextLine();

        if (userName.equals("patika")&& password.equals("java123")) {
            System.out.println("Giriş Yaptınız !");
        }else{
            System.out.println("Bilgileriniz Yanlış !");
        }
        }

    }
