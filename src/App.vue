<template>
  <div class="Header">
  <header-vue></header-vue>
  </div>
  
  
  <div class="Content">
  
    <card url="https://www.comida-peruana.com/base/stock/Recipe/166-image/166-image_web.jpg" nombre="Ensalada Andina"  descripcion="Compuesta a base de quinua, frijol, aguacate, pepinillos" costo="125"/>
    <card url="https://www.comida-peruana.com/base/stock/Recipe/164-image/164-image_web.jpg" nombre="Ensalada Peruana"  descripcion="Verduras acompañadas de atun,queso y aceitunas" costo="100 "/>
     <card url="https://www.comida-peruana.com/base/stock/Recipe/227-image/227-image_web.jpg" nombre="Ensalada Polleria" descripcion="Vegetales bañados en una vinagreta blanca de sabor    " costo="150"/>
    <card url="https://www.comida-peruana.com/base/stock/Recipe/169-image/169-image_web.jpg" nombre="Ensalada Palta"  descripcion="Ensalada peruana a base de aguacates, limón y cilantro" costo="75"/>
    <card url="https://www.comida-peruana.com/base/stock/Recipe/161-image/161-image_web.jpg" nombre="Ensalada Chonta"  descripcion="Ensalada de chontas, con vegetales y aguacate ..." costo="180"/>
    <card url="https://www.comida-peruana.com/base/stock/Recipe/165-image/165-image_web.jpg" nombre="Ensalada Mixta"  descripcion="Delicia de ensalada mixta bastante fresca y saludable." costo="85"/>
    
  </div>
  
  
  
  <FooterVue></FooterVue>
  
    </template>
  
  
  <script>
    import Card from "./components/Card.vue";
    import FooterVue from "./components/Footer.vue";
    import HeaderVue from "./components/Header.vue"
    export default {
      components:{
        Card, 
        FooterVue, 
        HeaderVue,
      },
    };
  
  </script>
    
  