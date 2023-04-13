<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <title>Barbearia Alura</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <h1 class="titulo-principal">Barbearia Alura</h1>
        </header>
 <img id="banner" src="img.jpg">
 <div class = "principal">
<H1>Sobre  a Barbearia </H1>
<p>Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. 
    Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</p>
    <p id="missao"></p>
    <p ><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>
        <p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. 
        O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
 </div>   

 <div class="beneficios" >
        
 <ul>
    <li class="itens">Atendimento aos Clientes</li>
    <li class="itens">Espaço diferenciado</li>
    <li class="itens">Localização</li>
    <li class="itens">Profissionais Qualificados</li>
</ul>
<img src="beneficios.jpg" class="beneficios.jpg">
 </div>     
</body>
</html>



#codigocss



body {
	
}

#banner {
	width:100%;
}

.principal{
	background: #CCCCCC;
	padding: 30px;
}

h1 {
	text-align: center
}

p {
	text-align: center;
}

#missao {
	font-size: 20px
}

em strong {
	color: #FF0000;
}

.itens {
	font-style: italic
}

.beneficios {
	background: #FFFFFF;
	padding: 20px;
}

h2 {
	text-align: center;
}

ul {
	display: inline-block;
	vertical-align: top;
	width: 20%;
	margin-right: 15%;
}

.imagem.beneficios {
max-width: 100%;
	width: 50%;
height: auto;

}
