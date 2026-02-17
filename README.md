# Smart_Health_Monitoring
Java codes for Smart Health Monitoring to monitore a the blood sugar.
public class SmartHealthApplication { 
    public static void main(String args[]){
 
         int done =0;
 
         while (done == 0){
             double bloodsugar =135.0;
             double BMI= 32.5;
    

         if( bloodsugar  > 126 && BMI > 30 ){
             System.out.println("The Risk Assessment:");
             System.out.println("\nHigh Risk ");
         }
         
         else{
             System.out.println("The Risk Assessment:");
             System.out.println("\nLow Risk ");
         }
         
         done =1;
  }
 }   
}
