<template>
  <body>
  <header class="cabecalho">
    <img class="cabecalho-imagem" src="assets/logo.svg" alt="logo da Ballerini">
    <nav class="cabecalho-menu">
      <a class="cabecalho-menu-item">Cominidade Ballerini</a>
      <a class="cabecalho-menu-item">Tutorial</a>
      <a class="cabecalho-menu-item">Open Source</a>
      <a class="cabecalho-menu-item">Comandos</a>
    </nav>
  </header>

  <main class="conteudo">
    <section class="conteudo-principal"> 
      <div class="conteudo-principal-escrito">
        <h1 class="conteudo-principal-escrito-titulo">Balle Bot</h1>
         <h2 class="conteudo-principal-escrito-subtitulo">Deixe a sua comunidade segura de um jeito fácil</h2>
         <button class="conteudo-principal-escrito-botao" onclick="meadd()" >Me adicione! </button> 

      </div>
      <img class="conteudo-principal-imagem" src="img/ballebot.svg" alt="imagem do balle bot">
    </section>

    <section class="conteudo-secudario"> 
       <h3 class="conteudo-secudario-titulo">O que ela faz por você?</h3>
       <p class="conteudo-secudario-paragrafo">1. Cria um <strong> sistema de verificação capcha</strong> para novos membros garantirem que não são robôs</p>
       <p class="conteudo-secudario-paragrafo">2. Possui um <strong> sistema de banimento automático</strong> para links suspeitos que forem enviados na comunidade</p>
       <p class="conteudo-secudario-paragrafo">3. <strong> Sistema de avisos e banimento manual</strong>, para pessoas administradoras utilizarem</p>

    </section>
  </main>

  <footer class="rodape">
   <img class="rodape-imagem" src="ballrrini.svg" alt="">
  </footer>

 
</body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Righteous&family=Sarala:wght@400;700&display=swap');


*{
margin:0 ;
padding: 0;
box-sizing: border-box;
text-decoration: none;
}

body{

  font-size: 100%;
  background: linear-gradient(68.15deg, #2F2325 16.62%, #8E5D52 85.61%);
}

.cabecalho{
display: flex;
flex-direction: row;
align-items: center;
justify-content: space-around;
padding: 24px;
}
.cabecalho-imagem{

  height: 72px;
}

.cabecalho-menu{

display: flex;
gap: 32px;

}

.cabecalho-menu-item{

  font-family: 'Sarala', sans-serif;
  color: #FFF2E7;
  font-weight: 400;
  font-size: 18px;

}
.conteudo{

  margin-bottom:48px ;
  border-top:0.4px solid #FFF2E7;
}

.conteudo-principal{

 display: flex;
 
 flex-direction:row ;

 align-items: center;

 justify-content: space-around;
 
 
}

.conteudo-principal-escrit{

display: flex;
flex-direction: column;
gap: 32px;

}

.conteudo-principal-escrito-titulo{

  font-family: 'Righteous', cursive;
  font-weight: 400;
  font-size: 64px;
  color: #FFF2E7;

}


.conteudo-principal-escrito-subtitulo{

  font-family: 'Sarala', sans-serif;
  font-weight: 400;
  font-size: 24px;
  color: #ecd6c4;


}

  
  .conteudo-principal-escrito-botao{


 background-color: #ecd6c4;

 width: 180px;
height: 60px;
left: 369px;
top: 382px;
border: none;
box-shadow: 4px 5px 4px rgba(0, 0, 0, 0.25);
border-radius: 20px;

font-family: 'Sarala', sans-serif;
  font-weight: 400;
  font-size: 24px;
  color: #2F2325;
  }

  .conteudo-principal-escrito-botao:hover{

   background-color: rgba(236, 214, 196, 0.53);

  }

  .conteudo-principal-imagem{
 height: 430px;


  }

  .conteudo-secudario{
   
    display: flex;

    flex-direction: column;
    align-items: center;
    gap: 24px;
    margin-top: 48px;



  }


  .conteudo-secudario-titulo{

  border-top: 0.4px  solid #FFF2E7;
  padding-top: 48px;
  font-family: 'Righteous', cursive;
  font-weight: 400;
  font-size: 24px;
  color: #FFF2E7;

  margin-bottom: 16px;


  }

  .conteudo-secudario-paragrafo{

    font-family: 'Sarala', sans-serif;
    font-weight: 350;
    font-size: 18px;
    color: #ecd6c4;
    

  }

   .rodape{
     padding: 32px;
     border-top: 0.4px  solid #FFF2E7;



   }

   .rodape-imagem{

    height: 48px;
    display: block;
    margin: 0 auto;

   }
</style>
