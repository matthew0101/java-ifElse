# java-ifElse
basic code for if/else if/else

public class IfElse

    public static void main(String[]args){
        byte x=100;

        if (x>=100){
            System.out.println("RICH");

        }else if (x>=70){
            System.out.println("COMFORT");

        }else if (x>=50){
            System.out.println("NORMAL");

        }else if (x>=20){
            System.out.println("SMALL");

        }else 
        System.out.println("POOR");

// Or the shorter version
    x=100
    String result = x >=100 ? "RICH" : x >= 70 ? 
"COMFORT" : x >= 50 ? "NORMAL" : x >= 20 ? "SMALL"
: "POOR";
          }
}