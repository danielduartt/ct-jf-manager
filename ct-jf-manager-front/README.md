# Protótipo Front-End | CT JF Manager

Esta pasta contém o protótipo estático e navegável da interface web para o sistema **CT JF Manager**. O objetivo deste front-end é validar a arquitetura da informação, a experiência do usuário (UX) e a identidade visual moderna que guiará o desenvolvimento do produto final, conforme especificado no Documento de Requisitos do Produto (PRD).

## 🎨 Design e Tecnologia

O protótipo foi desenvolvido com uma abordagem "mobile-first" e focado em uma estética moderna, limpa e profissional, utilizando apenas tecnologias web fundamentais.

* **HTML5:** Utilizado para a marcação e estruturação semântica de todo o conteúdo, garantindo uma base sólida e acessível.
* **CSS3:** Responsável por toda a estilização visual, incluindo:
    * **Dark Mode Sofisticado:** Um tema escuro que valoriza o conteúdo, cria contraste e é confortável para os olhos.
    * **Layout Responsivo:** A interface se adapta perfeitamente a desktops, tablets e smartphones[cite: 109].
    * **Microinterações:** Animações sutis em botões e elementos interativos para uma experiência de usuário mais fluida e agradável.

## 📁 Estrutura dos Arquivos

O protótipo é composto por um conjunto de páginas HTML que simulam o fluxo de navegação completo do usuário, desde o visitante até o aluno autenticado.

```
ct-jf-manager-front/
├── css/
│   └── style.css       # Folha de estilo centralizada e completa
├── images/
│   └── logo.jpg        # Logo do CT
├── index.html          # Landing Page / Portal Público
├── login.html          # Página de Login
├── cadastro.html       # Página de Cadastro de Aluno
├── aula-experimental.html # Formulário para agendamento via WhatsApp
├── dashboard.html      # Painel principal do aluno
├── videoteca.html      # Listagem de técnicas
├── tecnica-detalhe.html # Página de detalhe de uma técnica
├── campeonatos.html    # Listagem de campeonatos
├── campeonato-interesse.html # Formulário de interesse em campeonato
├── ranking.html        # Página com o ranking mensal
├── perfil.html         # Página de perfil com carteirinha digital
└── README.md           # Este arquivo
```

### Páginas Implementadas

1.  **`index.html`**: Landing page pública, servindo como portal institucional para apresentar o CT, a equipe, filosofia e horários, visando a captação de novos alunos[cite: 55].
2.  **`login.html`**: Formulário de autenticação para usuários acessarem a plataforma[cite: 67].
3.  **`cadastro.html`**: Formulário para o auto-cadastro de novos alunos, conforme requisito do MVP[cite: 66].
4.  **`aula-experimental.html`**: Formulário que coleta dados básicos e redireciona o interessado para o WhatsApp do CT com uma mensagem pré-preenchida[cite: 93].
5.  **`dashboard.html`**: Tela principal do aluno após o login, exibindo métricas chave de seu progresso como XP, frequência e técnicas aprendidas[cite: 52, 84].
6.  **`videoteca.html`**: Página que lista as técnicas disponíveis para estudo, com indicação visual daquelas que o aluno já aprendeu[cite: 82, 83].
7.  **`tecnica-detalhe.html`**: Tela para visualização do vídeo (embed do YouTube) e detalhes de uma técnica específica[cite: 51].
8.  **`campeonatos.html`**: Lista os próximos campeonatos e competições[cite: 88].
9.  **`campeonato-interesse.html`**: Formulário para o atleta manifestar interesse em participar de um campeonato[cite: 89].
10. **`ranking.html`**: Exibe o ranking mensal dos atletas, baseado em frequência e XP, para motivar e engajar os alunos[cite: 53, 90].
11. **`perfil.html`**: Página onde o usuário pode visualizar e editar suas informações e consultar sua carteirinha digital, que inclui a barra de progresso de XP para a próxima graduação[cite: 48, 78].

## 🖥️ Como Visualizar

Para navegar pelo protótipo, basta abrir o arquivo `index.html` em qualquer navegador web moderno. Todos os principais links e botões são funcionais para simular a experiência completa de navegação.