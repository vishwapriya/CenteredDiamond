# CenteredDiamond
public class Centereddiamond {
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
                int n=sc.nextInt();
        Scanner sc1=new Scanner(System.in);
                String s=sc1.nextLine();
        int i,j,k;
        for(i=1;i<=n;i++) {
            for (j = i; j <= n; j++) {
                System.out.print(" ");
            }
            if (i == n) {
                System.out.print(s.toString());
            } else {

                for (j = 1; j <= (2 * i - 1); j++) {
                    System.out.print("*");
                }
            }
                System.out.println();

        }
        for(k=n-1;k>=0;k--)
        {
            for(j=k;j<=n;j++)
            {
                System.out.print(" ");
            }
            for(j=(2*k-1);j>=1;j--)
            {
                System.out.print("*");
            }
            System.out.println();
        }

    }
}
