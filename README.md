# PRINTING-ASCII-VALUES-OF-THE-GIVEN-STRING
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String s1=sc.nextLine();
        int n=s1.length();
        char a[]=s1.toCharArray();
        for(int i=0;i<n;i++){
            int ch=(int)a[i];
              System.out.println(a[i]+" "+ch);
           
        }
    }
}
