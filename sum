import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int x=sc.nextInt();
       int power=1; int sum=1;
        String s=Integer.toString(x);
        //System.out.println(s);
        char a[]=s.toCharArray();
        for(int i=0;i<a.length;i++) {
            //System.out.println(a[i]);
        }
        for(int i=1;i<a.length;i++) {
            int d=a[i-1]-'0';
            int p=a[i]-'0';
            power=(int)(Math.pow(d,p));
            sum=sum+power;
        } 
        System.out.println(sum);
}}
