+<!DOCTYPE html>
<html lang="pt-BR">
    <meta charset=utf-8">
    <title> LAYOUT 1 </title>
    <link rel="stylesheet" href=.css">
</head>
<body>
     <h1> Testando MEDIA QUERIE-Resolução diferente.>
     <p> Mude o tamanho do seu navegador para ver as mudanças.
     </p>
     <div class="caixa um">Esta caixa ficará rosa se a aréa de visão for inferior a 600px</div>
     <div class="caixa dois>"Esta caixa fiacará laranja se a aréa de visão for maior a 900px</div>
     <div class="caixa tres">Esta caxia ficará azul se a aréa de visão for maior a 900px</div>
     <div class="wrapper iphone"> Essa caixa só será aplicavel a dispositivos  co max-device-witdh:480px (ou seja,Iphone)
     <p class="area-visivel"<>strong> Sua área de visão atual, é:
     </strong><span class="1t600">menor que 600px

</body> 
</html>

<style type="text/css">
body{padding:15px;background:#eee;font-family:Arial,Helvetica,sans-serif }.

.arca-visivel span {
    color:#666;
	display:none;
{
/* max-witdh */
@media screen and (max-witdh:600px) {
 .um {
     background: #F9C;
 }
span.1t600 {
    display:inline-block;
   }
}

/*min-witdh*/
@media screen and (min-witdh:900px) {
  .doia {
  background #F90;
 }
span.gt900 {
   display:inline-block;
  }
}

/* min-witdh & max-witdh*/
@media screen and (max-witdh:600px and (max-witdh:900px) {
   .tres{
       background:#9CF;
	}
span.bt600-900 {
      display:inline-block;
      }
}
/*max device-witdh */
@media acreen and (max-device-witdh:480px) {
   .iphone {
    background:#ccc;
  }
}
</style>  
