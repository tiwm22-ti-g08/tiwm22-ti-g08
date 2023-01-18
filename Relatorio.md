# **Relatório de trabalho de tecnologia de internet**
O trabalho foi desenvolvido sobre o tema de **animais polares** onde o principal objetivo é informar quais são as especes de animais que abitam a parte da terra que totalmente coberto pelo gelo sendo assim criada um local onde vai servir como deposito de emborcações sobre as especes e que qualquer pessoa terá acesso rápido as informações das especes polares.
## **Inicio do projeto**

O trabalho teve o início no dia **18 de dezembro**, dia que foi escolhido sobre o que  a ser tratado. Pelo fato do professor do professor pedir com tema qualquer assunto desde que tenha uma ligação muito forte com os animais, o nosso grupo preferio tratar sobre os animais polares, animais que não estão no dia a dia da grande maioria das pessoas pois  só podem ser encotradas em lugares específicos tendo assim uma certa desenformação por parte dessas pessoas sobre esses animais.

Tendo o a esculha já definido o próximo passo era saber o que exatamente ia ser apresentado no trabalho quais recurso íamos usar para criar o website, o que iria aparecer e quais informações iao aparecere nisso chegamos a com conclusão de que a primeira coisa a se fazer era a criação da pagina inicial.Na paginal escolhemos que deveriam aparecer alguns elementos
feitas por **HTML5 e CSS** e as âncoras de links aonde sobre elas form os link que levaram as pessoas para as outras paginas as quais sõa:
* A pagina que fala sobre os **Ursos Polares** ;
* A pagina que fala sobre os **Piguins** ;
* A pagina que fala sobre as **Focas** ;
* A pagina que fala sobre as **orcas** ;
* A pagina que da ao usuario a opornodade de **saber mais informções** ;
* E por ultimo a âncoras que levam o utilizador a uma pagina que o posibilita a  **entrar em contacto com o suporte**.

    1. ![Pagina Inicial](https://cdn.discordapp.com/attachments/1063491342413611129/1064646877502521385/Screenshot_1.png)

Lembrando que para criar a paginal inicial foi Usa **HTML5 e CSS**  aonde foi esse o codifo obitido
``` <!DOCTYPE html>
<html lang="PT">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="CssPagIni.css" />
    <title>Animais Polares</title>
</head>
<body>
    <nav>
        <div class="logo">
            <a href="PagInicial.html">Animais Polares</a>
        </div>

        <ul>
            <li><a href="urso polar/ursopolar.html">Urso Polar</a></li>
            <li><a href="#">Pinguin</a></li>
            <li><a href="#">Focas</a></li>
            <li><a href="#">Morsa</a></li>
        </ul>
    </nav>
    <section class="fundo">
        <div class="texto">    
                <h1 class="titulo">Animais Polares</h1>
                <h2 class="sub_titulo">Conheça 5 Espécies de Animais que </br>Vivem No Gelo</h2>
                <div class="botoes">
                    <button class="n-orverlay">Saiba Mais</button>
                    <button class="overlay"><a href="form/index.html">Contacte-nos</a></button>
                </div>
        </div>
    </section>
</body>
</html>
```
```*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}
nav{
    background-color: rgb(95, 130, 119);
    padding: 10px 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
nav .logo a{
    text-decoration: none;
    color: white;
    font-size: 35px;
    font-weight: 600;
}
nav ul{
    display: flex;
    align-items: center;
    list-style: none;
    padding: 10px;
}
nav li{
    margin-left: 7px;
}
nav li a{
    text-decoration: none;
    color: white;
    font-size: 18px;
    font-weight: 500;
    padding: 8px 15px;
    border-radius: 5px;
    transition: 0.3s;
}
nav li a:hover{
    background-color: white;
    color:black;
}
.fundo{
    height: 100vh;
    background-image: url(jobbbs.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}
.texto .titulo{
    color: white;
    font-size: 60px;
    font-weight: 600;
}
.texto .sub_titulo{
    color: white;
    font-size: 58px;
    font-weight: 600;
}
.texto .botoes{
    margin-top: 30px;
}
.texto .botoes button{
    height: 55px;
    width: 170px;
    border-radius: 5px;
    border: 0;
    margin: 0 10px;
    font-size: 20px;
    font-weight: 500;
    padding: 0 10px;
    cursor: pointer;
    outline: none;
    transition: 0.3s;
}
.texto .botoes button.n-orverlay{
    color: white;
    background: none;
    border: 2px solid white;
}
.texto .botoes button.n-orverlay:hover{
    color: black;
    background-color: white;
}
.texto .botoes button.overlay{
    background: white;
    color: black;
    animation: vibrar 0.5s ease-in-out infinite both;
}
@keyframes vibrar {
    0%{
        transform: scale(1);
    }
    50%{
        transform: scale(1.1);
    }
    100%{
        transform: scale(1);
    }
}
```

Partindo paro o proximo passo, nos do menbro do gupo comesamos a pensar nas paginas aonde estariam as informações sobre os animais e nessas paginas e constituida por 
* Uma **Âncora de link** o qual a ser apertado levaria  o usuario de vola para a pagina incial (*o aqual se emcontra na parte superio direito*);
* As imformaçôes sobre os animais (*o aqual se emcontra na parte do meu da pagina *);
*  E no canto superior Esquerdo se emcontra o nome do animal as ser falado.

Assim como na pagina inicial para cria as paginas com as informaçoes dos animais foi pensado um 
designer bem simples pois assim seria mais facel de prestar atenção nas imformações assim como podemos observar nas **figura-2**, **figura-3**, **figura-4** e **figura-5**.

  2. ![Urso Polar](https://cdn.discordapp.com/attachments/1063491342413611129/1064646877859041351/Screenshot_2.png)

  3. ![Pinguin](https://cdn.discordapp.com/attachments/1063491342413611129/1064646878093906081/Screenshot_3.png)


  4. ![Focas](https://cdn.discordapp.com/attachments/1004600580104265750/1064677391835861114/sssss.png  )

  5. ![orcas](https://cdn.discordapp.com/attachments/1004600580104265750/1064676176104276018/ssss.png)

Para fazer essas paginas foram usadas os recorsos de HTML5
e os condigos obitidos foram:
```<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="ursopolar.css" />
    <title>Ursor Polar</title>
</head>
<body>
    <nav>
        <div class="logoursop">
            <a href="ursopolar.css">Urso Polar</a>
        </div>

        <ul>
            <li><a href="../PagInicial.html">Voltar</a></li>
        </ul>
    </nav>
    <section class="fundourso">
        <div class="sobreurso">
            <h1 class="titulourso">Animais Polares</h1>
                <h2 class="subt_urso">ConheÃ§a o Urso Polar</h2>
                <div class="aiai">
                   <nav class="ursoplar">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Error neque ad, earum commodi rerum illo quo eligendi expedita. Deserunt ducimus illo reiciendis, cumque repellendus officiis voluptatibus tempore hic accusantium soluta?</main></br>
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Explicabo labore ad tenetur nobis maiores, minima suscipit minus hic vitae neque ex nesciunt, velit porro temporibus dolorem soluta incidunt cupiditate ipsa!
                   </nav>
                </div>
        </div>
    </section>
</body>
</html>

```
```*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}
nav{
    background-color: rgb(95, 130, 119);
    padding: 10px 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
nav .ursoplar{
    align-items: center;
    justify-content: center;
    padding: 15px 60px;
    background-color: white;
    text-align: center;
    font-size: 25px;
}
nav .logoursop a{
    text-decoration: none;
    color: white;
    font-size: 35px;
    font-weight: 600;
}
nav ul{
    display: flex;
    align-items: center;
    list-style: none;
    padding: 10px;
}
nav li{
    margin-left: 7px;
}
nav li a{
    text-decoration: none;
    color: white;
    font-size: 18px;
    font-weight: 500;
    padding: 8px 15px;
    border-radius: 5px;
    transition: 0.3s;
}
nav li a:hover{
    background-color: white;
    color:black;
}
.fundourso{
    height: 100vh;
    background-image: url(fundourso.png);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: top;
    justify-content: center;
    text-align: center;
}
.sobreurso .titulourso{
    color: white;
    font-size: 60px;
    font-weight: 600;
}
.sobreurso .subt_urso{
    color: white;
    font-size: 58px;
    font-weight: 600;
}
```

> *obs:As paginas sobre animas são feitas com o mesmo codifgo base so moda as informações*

Voltando para a pagina principal tambem se encontra uma âncora nomeando de contact-nos aonde ao ser selecionado o usuario é enviado para uma outra janela que o possibilita a entar em contacto.E para fazer isso tem que prenger os espços em branco com os contactos (*email e numero de telefone*) e logo em seguida deixar a sua duvida, obiniao, reclamar de alguma coisa e etc.

6. ![Pagina de Contacto](https://cdn.discordapp.com/attachments/1004600580104265750/1064655070039396475/PC.png)


> E Assim chegamos a parete final da criação do nosso web site. Esperamos que esteja todo de acordo com o que o professor deseja, por nossa parde nos gostamos muito de ter feito o trabalho. O Nosso trabalho pode ser encontrado atraves do link
https://tiwm22-ti-g08.netlify.app/ 