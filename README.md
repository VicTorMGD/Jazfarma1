# Jazfarma1
Primer intento de subir a GitHub JazFarma

Mi primera contribucionlocal para github

Un commit mas desde github

clase JS
function calcularPromedioConBucleFor(arr) {
  let suma = 0;
  let valido = 0;  
  let num = 0;
  for (let i = 0; i < arr.length; i++) {
    num=arr[i];
    if (typeof num === 'number' && !(isNaN(num)) ){
      valido = valido + 1;
      suma += arr[i];
    }
  }
  const promedio = suma / valido;
  return promedio;
}
const numero = [10, 20, 30, NaN, 40 , 50 ,"10",30, "no",(()=>[]), false, "ok", "bien"];
console.log(calcularPromedioConBucleFor(numero)); 



