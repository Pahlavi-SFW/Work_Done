# Work_Done
SFW_GIT
/******************************************************************************

                            Online Java Compiler.
                Code, Compile, Run and Debug java program online.
Write your code in this editor and press "Run" button to execute it.

*******************************************************************************/

public class Main
{
	public static void main(String[] args) {
	 System.out.println(getPentagonalNumber(100));
	}
	static int getPentagonalNumber(int n){
	  final int PENT_NUM = n;
	  int pentagon = 0;
	  for (int i = 1;i<=PENT_NUM;i++){
	    pentagon = i * (3*i-1)/2;
	    
	    if (i % 10 == 0){
	      System.out.println(pentagon+ " ");
	    } 
	    else {
	      System.out.print(pentagon+" ");
	    }
	    
	   }
	   return pentagon;
	}
}
