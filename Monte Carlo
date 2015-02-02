import java.util.Random;
/**
 * Write a description of class MonteCarlo here.
 * 
 * @Ann Tran and Rebekah Leslie 
 * @January 31st, 2015
 */
public class MonteCarlo {
    public double h, k ,r;
    private Random rand = new Random();
    public MonteCarlo(double h, double k, double r){
        this.h = h;
        this.k = k;
        this.r = r;
    }

    public double nextRainDrop_x(){
        return (rand.nextDouble() * 2 * r) + (h - r);
    }

    public double nextRainDrop_y(){
        return (rand.nextDouble() * 2 * r) + (k - r);
    }

    public boolean insideCircle(double x, double y){
        return Math.pow((x - h), 2) + Math.pow((y - k), 2) <= Math.pow(r, 2);
    }
}
