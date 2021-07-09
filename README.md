# 1A-Theatre-Square

//problem link:http://codeforces.com/problemset/problem/1/A
// Name        : Java
// Author      : Ibrahim Nashaat
// Version     :8
// Copyright   : use it under your responsibility
// Description : Hello World in java
//status:accepted

          import java.util.Scanner;
          public class Todo {

    public static void main(String[] args)
    {
        
       Scanner s = new Scanner (System.in);
       
       long n , m , a ;
       long  x;
       
        n = (long) s.nextDouble();
        m = (long) s.nextDouble();
        a = (long) s.nextDouble();
        
       x=(long) (Math.ceil((double)n/a)*Math.ceil((double)m/a));
        
        System.out.println(x);
         
      
    }
