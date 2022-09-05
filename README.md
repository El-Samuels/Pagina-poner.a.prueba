<!DOCTYPE html>
<html lang="en">

<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Poner a prueba</title>


   <style>
      .textos-h1-h2 { 
         border-width: 3px;
         border-color: darkgrey;
         color:darkslategrey;
         font-family: 'open sans';
         text-align: center;
    padding-right: 30px;
    padding-left: 30px;
      }

      .formulario {
         color: darkblue;
         font-family: sans-serif;
         text-align: center;
         box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
      }

      /* box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
      esto es para una sombra, es para copiar y pegar */

      a:hover {
         color: blueviolet;

      }

      /* el a:hover es para cambiar el estado de un elemento cuando el cursor esta sobre
       este, ejemplo: para que cuando el cursor pase por ensima de un elemento y este
      cambie de color, se debe escribir:
      a:hover{
       color: "cualquiera"
       } 
       */

      body {
         background-color:darkgrey;
      }

      [type='checkbox'] {
         margin: 10px 3px 15px 3px;
      }

      [type='radio'] {
         margin: 10px 3px 10px 3px;
      }
      .Frase{
         font-size: 15px;
         font-family: 'open sans';
         color: black;
         text-align: center;
      }
      .border-de-form{ 
         margin-right: 510px;
         margin-left: 510px;
         border-style: solid;
         border-color: powderblue;
         border-width: 5px;
         border-radius: 10px;
         background-color:cornsilk;
      }
      .border-de-frase{
         border-style: solid;
         border-color: powderblue;
         border-width: 5px;
         margin-left: 420px;
         margin-right: 420px;
         margin-top: 20px;
         padding-top: 2px;
         padding-bottom: 2px;
         border-radius: 20px;
      }

      .text-transform {
         text-transform: uppercase;
      }

      /* .desplazamiento-al-centro {
         border-width: 5px;
         border-style: solid;
         border-color: black;
         border-radius: 10px;
          margin: 0 auto; */
        ;/* margin-left: 500px; */
         /* margin-top: 10px; */
         /* left: 500px; */

      /* } */

      .letra-estilo{
          /* text-align: center;  */
         font-family: 'open sans';
      }

      .desplazamiento-al-centro {
         border-width: 5px;
         border-style: solid;
         border-color: black;
         border-radius: 10px;
         position: relative;
         left: 530px;
         margin-right: 1062px;
         margin-top: 6px;
      }
      /* Cuando la posición de un elemento se establece a relative, 
      te permite especificar como CSS lo moverá relativo a su posición actual 
      dentro del flujo normal de la página. Se empareja con las propiedades de 
      desplazamiento CSS de left o right, y top o bottom. Estas dicen cuántos pixeles, 
      porcentajes, o ems se debe mover el elemento lejos de donde esté normalmente 
      posicionado.  relative */


   </style>



   <!-- paddin = relleno 
   margin = margen
   border = borde
   Los bordes CSS tienen propiedades como style (estilo), color y width (ancho).
-->





</head>

<body>
   <div class="textos-h1-h2 text-transform">
      <h1>Hello</h1>
      <h2>Im improving my skills of programer</h2>
   </div><hr>

   <main class="formulario border-de-form">


      <form action="messagepage.html">

         <p>click here for learn <a href="https://www.freecodecamp.org/espanol/learn">how to code </a>too</p>

         <div class="botones-de-radio">

            <label for="milk">
               <input id="milk" value="milk" type="radio" name="milk-water-oranje juice" checked>milk
            </label>

            <label for="water">
               <input required id="water" value="water" type="radio" name="milk-water-oranje juice">water
            </label>

            <label for="orange juice">
               <input required id="orange juice" value="orange juice" type="radio" name="milk-water-oranje juice">orange
               juice
            </label>


         </div>

         <input type="text" required placeholder="email">

         <button type="submit">Submit</button>

         <div class="botones-de-checkbox">

            <label for="bread">
               <input id="bread" value="bread" type="checkbox" name="bread-cheese-tomato">bread
            </label>

            <label for="cheese">
               <input id="cheese" value="cheese" type="checkbox" name="bread-cheese-tomato">cheese
            </label>

            <label for="tomato">
               <input id="tomato" value="tomato" type="checkbox" name="bread-cheese-tomato">tomato
            </label>


         </div>



      </form>

   </main>
   <hr> <!-- hr = linea horinzontal -->

   <div class="Frase border-de-frase">
      <h3><em> is not about being perfect, it's about being the better</em></h3>
   </div>
<div class="desplazamiento-al-centro letra-estilo">
   <h3 >para centrarlo con desplazamiento</h3>
</div>


</body>

</html>
