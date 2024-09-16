# CI-0112
Laboratorio 2: Crear repositorio y programa de arrays.
import java.util.Scanner;
public class lab2 {
        
    }

public class robot {
    public void setnombre(String nombre){
        this.nombre=nombre;
    }
    public String getnombre(String nombre){
        return nombre;
    }
    public void setvida(int vida){
        this.vida=vida;
    }
    public int getvida( int vida){
        return vida;
    }
    public void setataque(int ataque){
        this.ataque=ataque;
    }
    public int getataque (int ataque){
        return ataque;
    }
    public boolean vivo(){
        if (vida>0){
            return true;
        }else{
            return false;
        }
    }
}
public class batalla{
    public static void main(String[] args) {
        Scanner scanner =  new Scanner(System.in);
        System.out.println("Bienvenido a Simbot");
        System.out.println("Ingrese la cantidad de robots (máximo 10)");
        int t = scanner.nextInt();
        int x = t - 1;
        for(int f=0; f<t;f++){
        System.out.println("Ingrese el nombre su robot");
        String nombrerobot = scanner.nextInt();
        System.out.println("Ingrese el máximo de ataque (no mayor de 20)");
        int ataquer = scanner.nextInt();
        System.out.println("Ingrese el máximo de vida (no mayor a 100)");
        int vidar = scanner.nextInt();
    }
        robot nu1 = new robot();
        nu1.setnombre(nombrerobot);
        nu1.setataque(ataquer);
        nu1.setvida(vidar);
    
        robot nu2 = new robot();
        nu2.setnombre(nombrerobot);
        nu2.setataque(ataquer);
        nu2.setvida(vidar);

        robot nu3 = new robot();
        nu3.setnombre(nombrerobot);
        nu3.setataque(ataquer);
        nu3.setvida(vidar);

        robot nume4 = new robot();
        nume4.setnombre(nombrerobot);
        nume4.setataque(ataquer);
        nume4.setvida(vidar);

        robot nume5= new robot();
        nume5.setnombre(nombrerobot);
        nume5.setataque(ataquer);
        nume5.setvida(vidar);


        robot nu6 = new robot();
        nu6.setnombre(nombrerobot);
        nu6.setataque(ataquer);
        nu6.setvida(vidar);
        
        robot nume7 = new robot();
        nume7.setnombre(nombrerobot);
        nume7.setataque(ataquer);
        nume7.setvida(vidar);

        robot num8 = new robot();
        num8.setnombre(nombrerobot);
        num8.setataque(ataquer);
        num8.setvida(vidar);

        robot nu9 = new robot();
        nu9.setnombre(nombrerobot);
        nu9.setataque(ataquer);
        nu9.setvida(vidar);

        robot nu10 = new robot();
        nu10.setnombre(nombrerobot);
        nu10.setataque(ataquer);
        nu10.setvida(vidar);

    String [] grupo_r = new String[x];
    grupo_r[0]=(nu1);
    grupo_r[1]=(nu2);
    grupo_r[2]=(nu3);
    grupo_r[3]=(nume4);
    grupo_r[4]=(nume5);
    grupo_r[5]=(nu6);
    grupo_r[6]=(nume7);
    grupo_r[7]=(num8);
    grupo_r[8]=(nu9);
    grupo_r[9]=(nu10);
}
}

