# Apptem-1

Just some Js code from a begginer (Spanish);




var a = prompt("Ingrese una frase : ");
var contar = 0;
var b = prompt("Ingrese la letra que desea contar : ");

if(b.length == 1){

    for(i = 0; i <= a.length; i++){

        if(a[i] == b){
    
            console.log("si");
            contar++;       
        }
    }
    
    console.log("La letra  "+ b + "   Un total de :   " + contar + "   veces");

}else if(b.length >=2 ){

    document.write("Usted ha ingresado mas de una letra a buscar y eso va en contra de lo establecido, por favor recargue la pagina.");

}
