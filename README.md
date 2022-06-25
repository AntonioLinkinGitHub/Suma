# Suma
Código JAVA que suma 3 números establecidos
-------------------------------------------
public class Main {

    public static void main(String[] args) {
        int resultado;
        resultado = suma(29,66,12);
        System.out.println(resultado);
    }
    public static int suma(int param1, int param2, int param3){
        return param1 + param2 + param3;
    }

}
-------------------------------------------

public class Main {

    public static void main(String[] args) {
        int param1 =29;
        int param2 =66;
        int param3 =12;

        var suma= suma(param1, param2, param3);

        System.out.println(suma);
    }
    public static int suma(int param1, int param2, int param3){
        return param1 + param2 + param3;
    }

}
