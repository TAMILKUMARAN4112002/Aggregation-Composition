import java.util.*;
class Charger{
    private String brand;
    private  float voltage;

    public Charger(String brand,float voltage){
        this.brand=brand;
        this.voltage=voltage;
    }
    public String getBrand() {
        return brand;
    }
    public float getVoltage() {
        return voltage;
    }
}class Os{
    private String name;
    private int size;
    public Os(String name,int size){
        this.name = name;
        this.size = size;
    }
    public int getSize() {
        return size;
    }

    public String getName() {
        return name;
    }
}
class Mobile{
    Os os = new Os("apple",4);
     void hasA(Charger c){
         c.getBrand();
         c.getVoltage();
     }
}
class Main{
    public static void main(String[] args){
        Mobile  m =  new Mobile();
        Charger c = new Charger("iqoo",68.3f);
        System.out.println(c.getBrand());
        System.out.println(c.getVoltage());
        m=null;
        System.out.print(m.os.getName());
        System.out.print(m.os.getSize());
    }
}
