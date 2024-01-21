# java-number-patterns-
i create java number patterns 
class Main
 {
    public static void main(String[] args) {
//        int n = 5;
//        for(int i=1;i<=5;i++){
//            for(int j=1;j<=i;j++){
//                System.out.print(j);
//            }
//            System.out.println();
//
//        }
//          int n = 5;
//          for(int i=1;i<=n;i++){
//              for(int j=i;j<=n;j++){
//                  System.out.print(j);
//              }
//              System.out.println();
//          }
//        int n = 15;
//        int m =1;
//        for(int i=1;i<=3;i++){
//            for(int j=1;j<=5;j++){
//                System.out.print(m+"\t");
//                m++;
//            }
//            System.out.println();
//        }
//          int n=1;
          int m=1;
          for(int i=1;i<=4;i++){
              for(int j=1;j<=5;j++){
                  System.out.print(m+"\t");
                  m+=4;
              }
              m=i+1;
              System.out.println();
          }
    }
}
