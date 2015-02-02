/**
 * Write a description of class Tester here.
 * 
 * @Ann Tran and Rebekah Leslie 
 * @January 31st, 2015
 */
public class Tester {
    static MonteCarlo monteCarlo = new MonteCarlo(5, 3, 2);
    static int cirCount = 0;
    static int sqrCount = 0;
    public static void main(String[] args){
        for (int i = 0; i < 1000000; i++)
        {
            double randX = monteCarlo.nextRainDrop_x();
            double randY = monteCarlo.nextRainDrop_y();
            if(monteCarlo.insideCircle(randX, randY))
            {
                cirCount++;
            }
            sqrCount++;
        }
        System.out.println("Pi is estimated to be about " + cirCount * Math.pow((2 * monteCarlo.r), 2) / (sqrCount * Math.pow(monteCarlo.r, 2)));
    }
}
