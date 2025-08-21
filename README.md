# imersao-HTML
<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Curriculo | Elias</title>
  <link rel="stylesheet" href="./imagens/style.css">
</head>

<body>
  <div class="container">
    <div class="header">
      <img src="./imagens/img.png" alt="Imagem perfil">
      <h1>Elias Ferreira de Melo</h1>
      <p>Brasileiro, 17 anos</p>
      <p>Recife – Pernambuco</p>
      <p>📞 (81)9 8330-2397 | ✉ elias.ferreira07@souunit.com.br</p>
      <p>
        <a href="">LinkedIn</a> |
        <a href="https://github.com/Lias07e">GitHub</a>

   </p>
      <!-- Perfil -->
      <h2>Perfil</h2>
      <p>Meu nome é Elias , estudei em escola publica maior parte da minha época escolar, por estudar em escola pública 
      aprendi a estar sempre estudadndo por fora para estar no mesmo nivel que as pessoas que são de escola privada para poder passar no        vestibular e isso  me ensinou que tenho que estar sempre querendo mais e não me conforma com o que tenho,então posso dizer que sou        uma pessoa obstinada e que não desiste facil. </p>

      <!-- Formação -->
      <h2>Formação</h2>
      <ul>
        <li>Analise e Desenvolvimento de Sistema(ADS) – UNIT (2025–2027)</li>
        <li>Marketing Digital</li>
     
      </ul>
     
      </ul>

     

      <!-- Qualificações -->
      <h2>Qualificações</h2>
      <ul>
        <li>Habilidade/ Sou uma pessoa resiliente  1</li>
        <li>Habilidade/ Sou uma pessoa comunicativa 2</li>
        <li>Habilidade/ Trabalho em equipe 3</li>
      </ul>

      <!-- Idiomas -->
      <h2>Idiomas</h2>
      <ul>
        <li>Inglês – Nível: A2</li>
        <li>Spanhol – Nível: A1</li>
      </ul>

      <!-- Informações Adicionais -->
      <h2>Informações Adicionais</h2>
      <ul>
        <li>Tecnologias: HTML, CSS(básico), Jaba(básico)</li>
        <li>Ferramentas:GitHub </li>
        <li>Outros: criação de post para instagram </li>
      </ul>

      body {
  font-family: Arial, sans-serif;   /* Fonte padrão usada em toda a página */
  background-color:rgb(101, 144, 160);        /* Cor de fundo cinza claro */
  margin: 0;                        /* Remove a margem padrão do navegador */
  padding: 0;                       /* Remove o espaçamento interno padrão */
}

/* ======== CONTAINER PRINCIPAL ======== */
.container {
  max-width: 900px;                 /* Largura máxima do currículo = 900px */
  margin: 40px auto;                /* 40px em cima/baixo + auto nas laterais -> centraliza no meio */
  background: #7ddae9;                 /* Fundo branco dentro do cartão */
  padding: 30px;                    /* Espaço interno para afastar o texto da borda */
  box-shadow: 0 4px 10px rgba(0,0,0,.1); /* Sombra leve embaixo do container */
  border-radius: 10px;              /* Bordas arredondadas */
}

/* ======== CABEÇALHO (foto + nome + contatos) ======== */
.header {
  text-align: center;               /* Centraliza todo o conteúdo dentro do cabeçalho */
  margin-bottom: 20px;              /* Espaço abaixo do cabeçalho */
}

/* Estilo da foto do perfil */
.header img {
  width: 150px;                     /* Largura da foto */
  height: 150px;                    /* Altura da foto */
  object-fit: cover;                /* Mantém a proporção da foto sem distorcer */
  border-radius: 50%;               /* Transforma a foto em um círculo */
  border: 3px solid #2b6cb0;        /* Borda azul ao redor da foto */
}

/* Nome principal (H1) */
.header h1 {
  margin: 15px 0 5px;               /* Espaço em cima (15px), embaixo (5px) */
  color: #2b6cb0;                   /* Cor azul do título */
}

/* Informações do cabeçalho (idade, cidade, contato) */
.header p {
  margin: 2px 0;                    /* Espaçamento pequeno entre as linhas */
  color: #555;                      /* Cor cinza escuro para o texto */
}

/* ======== TÍTULOS DE SEÇÃO (H2) ======== */
h2 {
  color: #2b6cb0;                   /* Cor azul do título */
  border-bottom: 2px solid #2b6cb0; /* Linha azul logo abaixo do título */
  padding-bottom: 5px;              /* Espaço entre o texto e a linha */
  margin-top: 30px;                 /* Espaço acima de cada seção */
}

/* ======== TEXTO (parágrafos e itens de lista) ======== */
p,
li {
  text-align: justify;              /* Texto justificado (alinha dos dois lados) */
  line-height: 1.6;                 /* Aumenta o espaçamento entre linhas -> melhora leitura */
}

/* ======== LISTAS ======== */
ul {
  list-style: none;                 /* Remove os marcadores padrão (bolinha preta) */
  padding: 0;                       /* Remove espaçamento interno da lista */
}

/* Criação de marcadores personalizados */
ul li::before {
  content: "• ";                    /* Insere uma bolinha manualmente antes de cada item */
  color: #2b6cb0;                   /* Define a cor da bolinha (azul) */
  font-weight: bold;                /* Deixa a bolinha mais grossa/forte */
}
