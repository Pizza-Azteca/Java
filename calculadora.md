import java.util.Scanner; 
public class Calculadora{ 
double num1=0,num2=0,res=0;
Scanner in = new Scanner (System.in); 
//este es para que escribam los numeros 
public void leerDatos(){ 
System.out.println("Escribe el primer numero"); 
num1 = in.nextInt(); 
System.out.println("Escribe el segundo numero"); 
num2 = in.nextInt(); 
} 
//Suma
public void Suma(){ 
res=num1+num2; 
System.out.println(num1+" + "+num2+" = "+res); 
}
public static void main(String[]args){ 
Calculadora cal1=new Calculadora(); 
cal1.leerDatos(); cal1.Resta(); 
cal1.Suma(); 
} 
//Resta 
public void Resta(){ 
res=num1-num2; 
System.out.println(num1+" - "+num2+" = "+res); 
} 
//Multiplicacion
public void Multiplicacion(){
res=num1*num2; 
System.out.println(num1+" x "+num2+" = "+res);
} 
//Division 
public void Division(){ 
res=num1/num2;
System.out.println(num1+" / "+num2+" = "+res);
} 
}
