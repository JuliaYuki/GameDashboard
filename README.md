
# Game Dashboard 🎮

**Game Dashboard** é um painel interativo e responsivo desenvolvido para gamers que desejam acompanhar suas estatísticas e dados de desempenho. Este dashboard permite visualizar informações sobre jogos recentes, estatísticas de partidas e rankings, além de oferecer uma navegação intuitiva em dispositivos desktop e mobile.

O objetivo principal deste projeto é fornecer uma ferramenta simples, porém funcional, para visualizar dados de jogos, vitórias, derrotas e tempo jogado, tornando-se ideal para estudo ou uso pessoal.

[Game Dashboard](https://juliayuki.github.io/GameDashboard/)


## ⚙️ Funcionalidades

- **Sidebar** Responsiva:
  - Sidebar fixa para desktop.
  - Sidebar no formato **offcanvas** em dispositivos móveis, acessível via botão de menu.

- **Cards de Estatísticas:**
  - Exibição clara de informações essenciais:
    - Jogos Jogados.
    - Total de Vitórias.
    - Total de Derrotas.

- **Jogos Recentes:**
  - Lista detalhada dos últimos jogos, incluindo:
    - Imagens dos jogos.
    - Horas jogadas.
    - Total de vitórias e derrotas.

- **Ranking de Jogadores:**
  - Ranking dinâmico com visualização dos jogadores e pontuações.

- **Página de Login:**
  - Formulário simples para autenticação.

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **Bootstrap 5 (CDN para CSS e JS)**
- **Google Fonts** (para fontes personalizadas)
- **Bootstrap Icons** (para ícones de navegação)

## 📂 Estrutura de Arquivos


```Game-Dashboard/
├── index.html              # Página inicial (Dashboard)
├── jogos-recentes.html     # Página de Jogos Recentes
├── login.html              # Página de Login
├── style.css               # Estilos personalizados
├── assets/
│   ├── images/             # Imagens dos jogos
│   └── icons/              # Ícones adicionais
└── README.md               # Documentação do projeto
```


## 📖 Como Usar

   ### 1. Clone o Repositório
```bash
git clone https://github.com/seu-usuario/game-dashboard.git
```

### 2. Acesse o Diretório
```bash
cd game-dashboard
```

## 🌟 Detalhes do Projeto

### 1. Dashboard (index.html)

A página principal exibe estatísticas em formato de cards coloridos, garantindo uma visualização rápida e intuitiva:
- Jogos Jogados.
- Total de Vitórias.
- Total de Derrotas.

Os **cards** são responsivos, adaptando-se perfeitamente a telas menores.

**Screenshot:**

<img src=".\assets\img-gameDashboard\1.png">
<img src=".\assets\img-gameDashboard\2.png">

### 2. Jogos Recentes (jogos-recentes.html)

Esta página detalha os jogos recentes com:
- Imagens dos jogos.
- Horas jogadas.
- Número de vitórias e derrotas.

**Screenshot:**

<img src=".\assets\img-gameDashboard\3.png">
<img src=".\assets\img-gameDashboard\4.png">

### 3. Login (login.html)

Página de login com:
- Formulário estilizado para inserção de e-mail e senha.
- Botão de login com design moderno.

**Screenshot:**

<img src=".\assets\img-gameDashboard\5.png">
<img src=".\assets\img-gameDashboard\6.png">

### 4. Sidebar Responsiva

- **Desktop:** Sidebar fixa com links organizados para navegação.
- **Mobile:** Sidebar no formato **offcanvas**, acessível através de um botão no canto superior esquerdo.

## 📐 Layout Responsivo

O projeto foi desenvolvido para ser totalmente responsivo:

- **Desktop:** Sidebar fixa e layout espaçoso.
- **Tablets/Mobile:** Sidebar colapsável e elementos ajustados para telas menores.

Caso os cards de estatísticas fiquem muito próximos em resoluções abaixo de `575px`, eles ajustam o espaçamento automaticamente usando **media queries** personalizadas.

## 🌐 Hospedagem
### 1. Hospedar no GitHub Pages
    1. Faça upload do projeto para um repositório no GitHub.
    2. Vá para Settings → Pages.
    3. Escolha o branch principal (main) e clique em Save.
    4. Acesse o link gerado para visualizar o projeto online.


## 📷 Imagens Utilizadas

As imagens dos jogos estão armazenadas na pasta `assets/images/`. Substitua os arquivos de exemplo por imagens reais dos seus jogos.

## 📄 Licença

Este projeto está licenciado sob a **MIT License**.  
Sinta-se livre para usá-lo, modificá-lo e distribuí-lo conforme necessário.

## 💡 Contribuições

Contribuições são bem-vindas!  
Siga os passos abaixo para contribuir:
1. Faça um fork do projeto.
2. Crie uma nova branch para suas alterações:

```bash
git checkout -b minha-branch
```

3. Envie suas alterações:
```bash
git commit -m "Descrição da alteração" 
```
```bash
git push origin minha-branch
```

4. Crie um Pull Request para revisão.

## 👨‍💻 Autor
Desenvolvido por [Seu Nome]().  
Se tiver dúvidas ou sugestões, fique à vontade para entrar em contato!
