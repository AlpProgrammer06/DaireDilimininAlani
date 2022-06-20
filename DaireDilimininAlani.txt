package com.aslan;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {


        int r;
        double pi = 3.14;
        double a= 0;

        Scanner scanner = new Scanner(System.in);

        System.out.println("Dairenin yaricapini giriniz : ");
        r = scanner.nextInt();
        System.out.println("Dairenin Diliminin Acisini Giriniz : ");
        a= scanner.nextInt();


        double DaireDilimininAlani = (3.14 * (r * r) * a) / 360;
        System.out.println("DaireDilimininAlani = " + DaireDilimininAlani);
        

    }
}
