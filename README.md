<!DOCTYPE html>
<html lang="pt-BR">


<head>


   <meta charset="UTF-8">


   <meta name="viewport" content="width=device-width, initial-scale=1.0">


   <title>Lorem — Experience</title>


   <!-- Fonte Poppins -->
   <link rel="preconnect" href="https://fonts.googleapis.com">


   <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>


   <link
       href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap"
       rel="stylesheet"
   >


   <link rel="stylesheet" href="style.css">


</head>




<body>




   <!-- ================= HEADER ================= -->


   <header>


       <div class="logo">
           Lorem
       </div>




       <nav>


           <a href="#inicio">Início</a>


           <a href="#recursos">Recursos</a>


           <a href="#experiencia">Experiência</a>


           <a href="#sobre">Sobre</a>


       </nav>




       <a href="#contato" class="header-button">
           Conheça
       </a>


   </header>






   <!-- ================= HERO ================= -->


   <section id="inicio" class="hero">


       <div class="hero-content">


           <p class="eyebrow">
               NOVA GERAÇÃO
           </p>




           <h1>


               Simples.
               <span>Inteligente.</span>
               Extraordinário.


           </h1>




           <p class="hero-description">


               Uma experiência criada para tornar
               a tecnologia mais simples, elegante
               e intuitiva.


           </p>




           <div class="hero-buttons">


               <a href="#recursos" class="button-primary">
                   Explorar
               </a>




               <a href="#sobre" class="button-secondary">
                   Saiba mais →
               </a>


           </div>


       </div>




       <div class="hero-image">


           <img
               src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=1400&q=90"
               alt="Tecnologia e computador"
           >


       </div>


   </section>






   <!-- ================= SHOWCASE ================= -->


   <section class="showcase">


       <p class="eyebrow">
           DESIGN QUE INSPIRA
       </p>




       <h2>


           Feito para parecer
           <span>simples.</span>


       </h2>




       <p class="section-description">


           Cada detalhe foi pensado para criar
           uma experiência visual limpa,
           moderna e agradável.


       </p>




       <div class="showcase-image">


           <img
               src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853?auto=format&fit=crop&w=1600&q=90"
               alt="Notebook moderno"
           >


       </div>


   </section>






   <!-- ================= RECURSOS ================= -->


   <section id="recursos" class="features">


       <div class="section-heading">


           <p class="eyebrow">
               RECURSOS
           </p>




           <h2>
               Tudo o que você precisa.
           </h2>


       </div>




       <div class="feature-grid">




           <article class="feature-card">


               <span class="feature-number">
                   01
               </span>


               <h3>
                   Design
               </h3>


               <p>


                   Uma interface minimalista
                   desenvolvida para facilitar
                   cada interação.


               </p>


           </article>




           <article class="feature-card">


               <span class="feature-number">
                   02
               </span>


               <h3>
                   Performance
               </h3>


               <p>


                   Experiência rápida, fluida
                   e preparada para diferentes
                   dispositivos.


               </p>


           </article>




           <article class="feature-card">


               <span class="feature-number">
                   03
               </span>


               <h3>
                   Inteligência
               </h3>


               <p>


                   Tecnologia criada para
                   simplificar tarefas e melhorar
                   resultados.


               </p>


           </article>




       </div>


   </section>






   <!-- ================= EXPERIENCE ================= -->


   <section id="experiencia" class="experience">


       <div class="experience-image">


           <img
               src="https://images.unsplash.com/photo-1550745165-9bc0b252726f?auto=format&fit=crop&w=1400&q=90"
               alt="Tecnologia"
           >


       </div>




       <div class="experience-content">


           <p class="eyebrow">
               EXPERIÊNCIA
           </p>




           <h2>
               Tecnologia que
               desaparece.
           </h2>




           <p>


               Quando um produto é bem projetado,
               você não precisa pensar em como
               utilizá-lo. Tudo simplesmente funciona.


           </p>




           <a href="#contato" class="text-link">
               Descubra mais →
           </a>


       </div>


   </section>






   <!-- ================= SOBRE ================= -->


   <section id="sobre" class="about">


       <p class="eyebrow">
           NOSSA FILOSOFIA
       </p>




       <h2>


           Menos complicação.
           <br>
           Mais possibilidades.


       </h2>




       <p class="about-description">


           Lorem nasceu da ideia de que tecnologia
           não precisa ser complicada. Criamos
           experiências que combinam design,
           simplicidade e inovação.


       </p>


   </section>






   <!-- ================= CTA ================= -->


   <section id="contato" class="cta">


       <p class="eyebrow">
           PRONTO PARA COMEÇAR?
       </p>




       <h2>


           O próximo passo
           começa aqui.


       </h2>




       <a href="#inicio" class="button-primary">
           Começar agora
       </a>


   </section>






   <!-- ================= FOOTER ================= -->


   <footer>


       <div class="footer-logo">
           Lorem
       </div>




       <p>
           © 2026 Lorem. Todos os direitos reservados.
       </p>




       <div class="footer-links">


           <a href="#inicio">
               Início
           </a>


           <a href="#sobre">
               Sobre
           </a>


           <a href="#contato">
               Contato
           </a>


       </div>


   </footer>




</body>


</html>




















/* =========================================
  CONFIGURAÇÕES GERAIS
========================================= */


* {
   margin: 0;
   padding: 0;
   box-sizing: border-box;
}




html {
   scroll-behavior: smooth;
}




body {
   font-family: 'Poppins', sans-serif;


   background-color: #f5f5f7;
  


   color: #080849;
   /* DESAFIO 02: Altere o color de #080849 para uma cor escolhida por você */
}






/* =========================================
  HEADER
========================================= */


header {


   height: 70px;
   /* DESAFIO 03: Altere o height de 70px para 80px */


   padding: 0 8%;
   /* DESAFIO 04: Altere o padding de 0 8% para 0 10% */


   display: flex;


   align-items: center;


   justify-content: space-between;


   background-color: rgba(255, 255, 255, 0.92);
   /* DESAFIO 05: Altere o background-color para uma cor escolhida por você */


   border-bottom: 1px solid #e5e5e7;
   /* DESAFIO 06: Altere a cor da borda para uma cor escolhida por você */


   position: sticky;


   top: 0;


   z-index: 1000;


   backdrop-filter: blur(15px);
}






/* =========================================
  LOGO
========================================= */


.logo {


   font-size: 22px;
   /* DESAFIO 07: Altere o font-size de 22px para 26px */


   font-weight: 600;


   letter-spacing: -1px;
   /* DESAFIO 08: Altere o letter-spacing de -1px para 0px */


   color: #1d1d1f;
   /* DESAFIO 09: Altere o color para uma cor escolhida por você */
}






/* =========================================
  MENU
========================================= */


nav {


   display: flex;


   gap: 35px;
   /* DESAFIO 10: Altere o gap de 35px para 45px */
}




nav a {


   text-decoration: none;


   color: #6e6e73;
   /* DESAFIO 11: Altere o color para uma cor escolhida por você */


   font-size: 14px;
   /* DESAFIO 12: Altere o font-size de 14px para 16px */


   transition: 0.3s;
}




nav a:hover {


   color: #0071e3;
   /* DESAFIO 13: Altere o color para uma cor escolhida por você */
}






/* =========================================
  BOTÃO DO HEADER
========================================= */


.header-button {


   text-decoration: none;


   color: #ffffff;


   background-color: #1d1d1f;
   /* DESAFIO 14: Altere o background-color para uma cor escolhida por você */


   padding: 9px 18px;
   /* DESAFIO 15: Altere o padding de 9px 18px para 10px 22px */


   border-radius: 20px;
   /* DESAFIO 16: Altere o border-radius de 20px para 25px */


   font-size: 13px;


   transition: 0.3s;
}




.header-button:hover {


   background-color: #424245;
   /* DESAFIO 17: Altere o background-color para uma cor escolhida por você */


   transform: translateY(-2px);
}






/* =========================================
  HERO
========================================= */


.hero {


   min-height: 800px;
   /* DESAFIO 18: Altere o min-height de 800px para 850px */


   padding: 120px 8%;
   /* DESAFIO 19: Altere o padding de 120px 8% para 140px 8% */


   display: flex;


   align-items: center;


   justify-content: space-between;


   gap: 80px;
   /* DESAFIO 20: Altere o gap de 80px para 100px */


   background-color: #f5f5f7;
   /* DESAFIO 21: Altere o background-color para uma cor escolhida por você */
}




.hero-content {


   width: 48%;


   max-width: 650px;
}




.eyebrow {


   font-size: 12px;


   font-weight: 600;


   letter-spacing: 2px;


   color: #6e6e73;
   /* DESAFIO 22: Altere o color para uma cor escolhida por você */


   margin-bottom: 20px;
}






/* =========================================
  TÍTULO PRINCIPAL
========================================= */


.hero h1 {


   font-size: 76px;
   /* DESAFIO 23: Altere o font-size de 68px para 76px */


   line-height: 1.04;


   letter-spacing: -3px;
   /* DESAFIO 24: Altere o letter-spacing de -3px para -4px */


   font-weight: 600;


   margin-bottom: 30px;
   /* DESAFIO 25: Altere o margin-bottom de 30px para 35px */


   color: #124cc9;
   /* DESAFIO 26: Altere o color para uma cor escolhida por você */
}




.hero h1 span {


   color: #6e6e73;
   /* DESAFIO 27: Altere o color para uma cor escolhida por você */
}




.hero-description {


   max-width: 520px;


   font-size: 18px;
   /* DESAFIO 28: Altere o font-size de 18px para 20px */


   line-height: 1.8;


   color: #6e6e73;
   /* DESAFIO 29: Altere o color para uma cor escolhida por você */


   margin-bottom: 40px;
}






/* =========================================
  BOTÕES DO HERO
========================================= */


.hero-buttons {


   display: flex;


   align-items: center;


   gap: 25px;
}




.button-primary {


   display: inline-block;


   padding: 15px 26px;
   /* DESAFIO 30: Altere o padding de 15px 26px para 17px 30px */


   background-color: #1d1d1f;
   /* DESAFIO 31: Altere o background-color para uma cor escolhida por você */


   color: #ffffff;


   text-decoration: none;


   border-radius: 30px;
   /* DESAFIO 32: Altere o border-radius de 30px para 35px */


   font-size: 14px;


   transition: 0.3s;
}




.button-primary:hover {


   background-color: #424245;
   /* DESAFIO 33: Altere o background-color para uma cor escolhida por você */


   transform: translateY(-3px);
}




.button-secondary {


   color: #1d1d1f;
   /* DESAFIO 34: Altere o color para uma cor escolhida por você */


   text-decoration: none;


   font-size: 14px;


   transition: 0.3s;
}




.button-secondary:hover {


   color: #1d3f9f;
   /* DESAFIO 35: Altere o color para uma cor escolhida por você */


   transform: translateX(3px);
}






/* =========================================
  IMAGEM DO HERO
========================================= */


.hero-image {


   width: 48%;
}




.hero-image img {


   width: 100%;


   height: 550px;
   /* DESAFIO 36: Altere o height de 550px para 600px */


   object-fit: cover;


   border-radius: 30px;
   /* DESAFIO 37: Altere o border-radius de 30px para 40px */


   display: block;


   box-shadow:
       0 25px 70px rgba(0, 0, 0, 0.12);


   transition: 0.5s;
}




.hero-image img:hover {


   transform: scale(1.02);
}






/* =========================================
  SHOWCASE
========================================= */


.showcase {


   padding: 140px 8%;
   /* DESAFIO 38: Altere o padding de 140px 8% para 160px 8% */


   background-color: #ffffff;
   /* DESAFIO 39: Altere o background-color para uma cor escolhida por você */


   text-align: center;
}




.showcase h2 {


   font-size: 58px;
   /* DESAFIO 40: Altere o font-size de 58px para 64px */


   line-height: 1.05;


   letter-spacing: -2px;


   margin-bottom: 25px;


   color: #1d1d1f;
   /* DESAFIO 41: Altere o color para uma cor escolhida por você */
}




.showcase h2 span {


   color: #6e6e73;
   /* DESAFIO 42: Altere o color para uma cor escolhida por você */
}




.section-description {


   max-width: 650px;


   margin: 0 auto 70px;


   color: #6e6e73;
   /* DESAFIO 43: Altere o color para uma cor escolhida por você */


   font-size: 17px;


   line-height: 1.8;
}




.showcase-image {


   max-width: 1200px;


   margin: auto;
}




.showcase-image img {


   width: 100%;


   height: 650px;


   object-fit: cover;


   border-radius: 30px;


   display: block;


   box-shadow:
       0 30px 80px rgba(0, 0, 0, 0.12);
}






/* =========================================
  RECURSOS
========================================= */


.features {


   padding: 140px 8%;


   background-color: #f5f5f7;
   /* DESAFIO 44: Altere o background-color para uma cor escolhida por você */
}




.section-heading {


   max-width: 700px;


   margin-bottom: 70px;
}




.section-heading h2 {


   font-size: 55px;


   line-height: 1.05;


   letter-spacing: -2px;
}






/* =========================================
  GRID DOS CARDS
========================================= */


.feature-grid {


   max-width: 1200px;


   margin: auto;


   display: grid;


   grid-template-columns: repeat(3, 1fr);
   /* DESAFIO 45: Altere o grid-template-columns para repeat(3, 1fr) */


   gap: 25px;
   /* DESAFIO 46: Altere o gap de 25px para 30px */
}






/* =========================================
  CARDS
========================================= */


.feature-card {


   background-color: #ffffff;
   /* DESAFIO 47: Altere o background-color para uma cor escolhida por você */


   color: #1d1d1f;


   padding: 40px;
   /* DESAFIO 48: Altere o padding de 40px para 45px */


   min-height: 330px;
   /* DESAFIO 49: Altere o min-height de 330px para 350px */


   border-radius: 28px;
   /* DESAFIO 50: Altere o border-radius de 28px para 35px */


   transition: 0.4s;
}




.feature-card:hover {


   transform: translateY(-8px);
   /* DESAFIO 51: Altere o translateY de -8px para -12px */


   box-shadow:
       0 25px 60px rgba(0, 0, 0, 0.08);
}




.feature-number {


   display: block;


   font-size: 13px;


   color: #86868b;
   /* DESAFIO 52: Altere o color para uma cor escolhida por você */


   margin-bottom: 70px;
   /* DESAFIO 53: Altere o margin-bottom de 70px para 90px */
}




.feature-card h3 {


   font-size: 28px;
   /* DESAFIO 54: Altere o font-size de 28px para 32px */


   color: #1d1d1f;
   /* DESAFIO 55: Altere o color para uma cor escolhida por você */


   margin-bottom: 15px;
   /* DESAFIO 56: Altere o margin-bottom de 15px para 20px */
}




.feature-card p {


   color: #6e6e73;
   /* DESAFIO 57: Altere o color para uma cor escolhida por você */


   line-height: 1.7;
   /* DESAFIO 58: Altere o line-height de 1.7 para 1.9 */


   font-size: 15px;
   /* DESAFIO 59: Altere o font-size de 15px para 16px */
}






/* =========================================
  EXPERIENCE
========================================= */


.experience {


   min-height: 700px;


   display: flex;


   align-items: center;


   gap: 100px;


   padding: 120px 8%;


   background-color: #000000;
   /* DESAFIO 60: Altere o background-color para uma cor escolhida por você */


   color: #ffffff;
}




.experience-image {


   width: 50%;
}




.experience-image img {


   width: 100%;


   height: 520px;
   /* DESAFIO 61: Altere o height de 520px para 580px */


   object-fit: cover;


   border-radius: 30px;
   /* DESAFIO 62: Altere o border-radius de 30px para 35px */


   display: block;
}




.experience-content {


   width: 40%;


   max-width: 500px;
}




.experience-content .eyebrow {


   color: #86868b;
   /* DESAFIO 63: Altere o color para uma cor escolhida por você */
}




.experience-content h2 {


   font-size: 58px;
   /* DESAFIO 64: Altere o font-size de 58px para 64px */


   line-height: 1.05;


   letter-spacing: -2px;


   margin-bottom: 30px;
}




.experience-content p {


   color: #a1a1a6;
   /* DESAFIO 65: Altere o color para uma cor escolhida por você */


   line-height: 1.8;


   font-size: 17px;


   margin-bottom: 30px;
}




.text-link {


   color: #2997ff;
   /* DESAFIO 66: Altere o color para uma cor escolhida por você */


   text-decoration: none;


   font-size: 15px;
}






/* =========================================
  SOBRE
========================================= */


.about {


   padding: 150px 8%;
   /* DESAFIO 67: Altere o padding de 150px 8% para 170px 8% */


   text-align: center;


   background-color: #ffffff;
   /* DESAFIO 68: Altere o background-color para uma cor escolhida por você */
}




.about h2 {


   font-size: 64px;
   /* DESAFIO 69: Altere o font-size de 64px para 70px */


   line-height: 1.05;


   letter-spacing: -3px;


   margin-bottom: 35px;


   color: #1d1d1f;
   /* DESAFIO 70: Altere o color para uma cor escolhida por você */
}




.about-description {


   max-width: 700px;


   margin: auto;


   color: #6e6e73;
   /* DESAFIO 71: Altere o color para uma cor escolhida por você */


   font-size: 18px;


   line-height: 1.8;
}






/* =========================================
  CTA
========================================= */


.cta {


   padding: 130px 8%;
   /* DESAFIO 72: Altere o padding de 130px 8% para 160px 8% */


   background-color: #f5f5f7;
   /* DESAFIO 73: Altere o background-color para uma cor escolhida por você */


   text-align: center;
}




.cta h2 {


   font-size: 58px;


   line-height: 1.05;


   letter-spacing: -2px;


   max-width: 700px;


   margin: 0 auto 40px;


   color: #1d1d1f;
   /* DESAFIO 74: Altere o color para uma cor escolhida por você */
}






/* =========================================
  FOOTER
========================================= */


footer {


   padding: 40px 8%;
   /* DESAFIO 75: Altere o padding de 40px 8% para 50px 8% */


   background-color: #f5f5f7;
   /* DESAFIO 76: Altere o background-color para uma cor escolhida por você */


   border-top: 1px solid #d2d2d7;
   /* DESAFIO 77: Altere a cor da borda para uma cor escolhida por você */


   display: flex;


   align-items: center;


   justify-content: space-between;


   color: #6e6e73;
   /* DESAFIO 78: Altere o color para uma cor escolhida por você */


   font-size: 12px;
}




.footer-logo {


   color: #1d1d1f;


   font-weight: 600;


   font-size: 18px;
}




.footer-links {


   display: flex;


   gap: 25px;
}




.footer-links a {


   color: #6e6e73;


   text-decoration: none;
}






/* =========================================
  DESAFIO FINAL — IDENTIDADE VISUAL
========================================= */


/*
DESAFIO 79:


Escolha uma nova cor principal
para o seu site.


Depois altere pelo menos
5 propriedades "color" ou
"background-color" utilizando
a cor escolhida.


Você pode escolher qualquer cor.


Exemplos:


Azul:
#3155d9


Roxo:
#7c3aed


Verde:
#059669


Laranja:
#ea580c


Vermelho:
#dc2626


Ou escolha qualquer outra
cor de sua preferência.
*/






/* =========================================
  DESAFIO 80 — FONTE
========================================= */


/*
DESAFIO 80:


Troque a fonte Poppins por
outra fonte do Google Fonts.


Exemplos:


'Montserrat'
'Roboto'
'Inter'
'Raleway'


Altere a propriedade abaixo.
*/


body {


   font-family: 'Poppins', sans-serif;
}






/* =========================================
  DESAFIO 81 — EFEITO EXTRA
========================================= */


/*
DESAFIO 81:


Altere o tamanho do efeito
de aumento da imagem.


Experimente:


1.01
1.03
1.05
*/




.hero-image img:hover {


   transform: scale(1.02);
}






/* =========================================
  DESAFIO 82 — EFEITO DOS CARDS
========================================= */


/*
DESAFIO 82:


Altere a altura do movimento
dos cards quando o mouse passa
sobre eles.


Experimente:


-5px
-10px
-15px
*/


.feature-card:hover {


   transform: translateY(-8px);
}






/* =========================================
  RESPONSIVIDADE
========================================= */


@media (max-width: 900px) {


   header {


       padding: 0 6%;
   }




   nav {


       display: none;
   }




   .hero {


       flex-direction: column;


       text-align: center;


       padding: 90px 6%;


       gap: 60px;
   }




   .hero-content {


       width: 100%;
   }




   .hero h1 {


       font-size: 52px;


       letter-spacing: -2px;
   }




   .hero-description {


       margin-left: auto;


       margin-right: auto;
   }




   .hero-buttons {


       justify-content: center;
   }




   .hero-image {


       width: 100%;
   }




   .hero-image img {


       height: 400px;
   }




   .showcase {


       padding: 100px 6%;
   }




   .showcase h2 {


       font-size: 45px;
   }




   .showcase-image img {


       height: 400px;
   }




   .features {


       padding: 100px 6%;
   }




   .section-heading h2 {


       font-size: 45px;
   }




   .feature-grid {


       grid-template-columns: 1fr;
   }




   .experience {


       flex-direction: column;


       padding: 100px 6%;


       gap: 60px;
   }




   .experience-image {


       width: 100%;
   }




   .experience-content {


       width: 100%;


       text-align: center;
   }




   .experience-content h2 {


       font-size: 45px;
   }




   .about {


       padding: 100px 6%;
   }




   .about h2 {


       font-size: 48px;
   }




   .cta {


       padding: 100px 6%;
   }




   .cta h2 {


       font-size: 45px;
   }




   footer {


       flex-direction: column;


       gap: 20px;


       text-align: center;
   }


}
