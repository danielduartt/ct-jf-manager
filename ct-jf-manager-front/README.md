# 🥋 CT Josuelmo Farias - Sistema de Gerenciamento# 🥋 CT Josuelmo Farias - Sistema de Gerenciamento

## Documentação Completa do Front-end

## 📋 Informações do Projeto

---

**Nome do Sistema:** CT Josuelmo Farias - Sistema de Gerenciamento e Videoteca

## 📋 Informações do Projeto

**Desenvolvedor:**

**Nome do Sistema:** CT Josuelmo Farias - Sistema de Gerenciamento e Videoteca- **Nome:** [Seu Nome Completo]

- **Matrícula:** [Sua Matrícula]

**Desenvolvedor:**

- **Nome:** [Seu Nome Completo]**Descrição:** Sistema web para gerenciamento de alunos, videoteca de técnicas de Jiu-Jitsu, acompanhamento de campeonatos e ranking de desempenho para o Centro de Treinamento Josuelmo Farias.

- **Matrícula:** [Sua Matrícula]

================================================================================

**Descrição:** Sistema web para gerenciamento de alunos, videoteca de técnicas de Jiu-Jitsu, acompanhamento de campeonatos e ranking de desempenho para o Centro de Treinamento Josuelmo Farias.INSTRUÇÕES DE NAVEGAÇÃO

================================================================================

**Tipo:** Protótipo Front-end (Interface)

ARQUIVO INICIAL:

---    Abra o arquivo "index.html" no navegador para começar a navegação.

    Este é a página principal (landing page) do sistema.

## 📁 Estrutura de Arquivos

FLUXO DE NAVEGAÇÃO RECOMENDADO:

```    1. index.html         → Página inicial/landing page

ct-jf-manager-front/    2. cadastro.html      → Registro de novo usuário

│    3. login.html         → Autenticação no sistema

├── 📄 index.html                     # Landing page pública    4. dashboard.html     → Painel principal após login

├── 📄 cadastro.html                  # Formulário de registro    5. perfil.html        → Gerenciamento do perfil do usuário

├── 📄 login.html                     # Autenticação de usuários    6. campeonatos.html   → Listagem de campeonatos

├── 📄 aula-experimental.html         # Agendamento de aula experimental    7. videoteca.html     → Biblioteca de vídeos técnicos

│

├── 🔐 dashboard.html                 # Painel principal (autenticado)================================================================================

├── 🔐 perfil.html                    # Perfil e carteirinha do alunoPÁGINAS IMPLEMENTADAS

├── 🔐 videoteca.html                 # Biblioteca de vídeos================================================================================

├── 🔐 tecnica-detalhe.html           # Detalhes de uma técnica

├── 🔐 campeonatos.html               # Listagem de campeonatosPÁGINAS PÚBLICAS (Acesso sem login):

├── 🔐 campeonato-interesse.html      # Formulário de interesse    ✓ index.html

├── 🔐 ranking.html                   # Ranking mensal de alunos        - Página inicial do site

│        - Apresentação do CT e seus benefícios

├── 📂 css/        - Links para cadastro e login

│   └── style.css                     # Arquivo CSS único e global

│    ✓ cadastro.html

├── 📂 images/        - Formulário de registro de novos usuários

│   ├── logo.jpg                      # Logo do CT        - Campos: nome, email, telefone, senha, categoria

│   └── [outras imagens]              # Fotos de treinos, professores, etc.

│    ✓ login.html

├── 📂 prd/        - Formulário de autenticação

│   └── [Documentação PRD]            # Product Requirements Document        - Campos: email e senha

│

└── 📄 README.md                      # Este arquivoPÁGINAS PRIVADAS (Requerem autenticação):

```    ✓ dashboard.html

        - Painel principal do sistema

---        - Visão geral das funcionalidades

        - Cards de acesso rápido

## 🚀 Como Iniciar

    ✓ perfil.html

### Arquivo Inicial        - Gerenciamento de dados do usuário

**Abra o arquivo `index.html`** no navegador para começar. Esta é a landing page pública do sistema.        - Edição de informações pessoais

        - Visualização de faixa e categoria

### Métodos de Visualização

    ✓ campeonatos.html

#### Método 1: Duplo Clique (Mais Simples)        - Listagem de campeonatos disponíveis

```        - Sistema de filtros e busca

1. Navegue até a pasta ct-jf-manager-front        - Cards com informações dos eventos

2. Duplo clique em index.html

3. O navegador padrão abrirá automaticamente    ✓ campeonato-interesse.html

```        - Demonstração de interesse em campeonatos

        - Formulário de inscrição

#### Método 2: Live Server - VS Code (Recomendado)        - Seleção de categoria e peso

```

1. Instale a extensão "Live Server" no VS Code    ✓ videoteca.html

2. Clique com botão direito no index.html        - Biblioteca de vídeos técnicos de Jiu-Jitsu

3. Selecione "Open with Live Server"        - Sistema de filtros por categoria e dificuldade

4. Acessará: http://localhost:5500        - Player de vídeo integrado

5. Recarga automática ao salvar arquivos

```    ✓ tecnica-detalhe.html

        - Visualização detalhada de técnicas

#### Método 3: Servidor Python        - Descrição completa da técnica

```bash        - Vídeo demonstrativo

# No PowerShell/Terminal, dentro da pasta ct-jf-manager-front

python -m http.server 8000================================================================================

ESTRUTURA DE PASTAS

# Acesse no navegador:================================================================================

# http://localhost:8000

```ct-jf-manager-front/

    │

---    ├── index.html                      (Página inicial)

    ├── cadastro.html                   (Registro)

## 📄 Descrição Detalhada de Cada Página    ├── login.html                      (Autenticação)

    ├── dashboard.html                  (Painel principal)

### 🌐 PÁGINAS PÚBLICAS (Sem necessidade de login)    ├── perfil.html                     (Perfil do usuário)

    ├── campeonatos.html                (Listagem de campeonatos)

#### 1. `index.html` - Landing Page    ├── campeonato-interesse.html       (Demonstração de interesse)

**Título:** CT Josuelmo Farias - Jiu-Jitsu de Alta Performance    ├── videoteca.html                  (Biblioteca de vídeos)

    ├── tecnica-detalhe.html            (Detalhes da técnica)

**Objetivo:** Apresentar o Centro de Treinamento e atrair novos alunos    │

    ├── css/

**Conteúdo:**    │   └── style.css                   (Estilos globais)

- **Header:**    │

  - Logo do CT (70px × 70px, clicável)    ├── images/

  - Menu: "Área do Aluno" e "Criar Conta"    │   └── [Imagens do projeto]

      │

- **Seção Hero:**    ├── prd/

  - Título: "A Arte Suave que Transforma Vidas"    │   └── [Documentação do produto]

  - Descrição dos valores do CT    │

  - CTA: "Agende sua Aula Experimental"    └── README.txt                      (Este arquivo)

  - Background com imagem de fundo escurecida

  ================================================================================

- **Seção Filosofia:**RECURSOS E FUNCIONALIDADES

  - Grid 2 colunas (texto + imagem)================================================================================

  - Apresentação da metodologia

  - Imagem ilustrativa de treino (max-height: 500px)RECURSOS IMPLEMENTADOS:

      • Design responsivo para desktop, tablet e mobile

- **Seção Benefícios:**    • Sistema de navegação consistente em todas as páginas

  - Grid responsivo de cards    • Formulários com validação de campos

  - 3 cards: "Técnica e Disciplina", "Comunidade Forte", "Saúde e Bem-estar"    • Sistema de cards para exibição de conteúdo

  - Ícones FontAwesome    • Filtros e busca para campeonatos e vídeos

      • Modal para visualização de vídeos

- **Seção Equipe:**    • Integração com WhatsApp para contato

  - Grid de professores (3 cards)    • Animações e transições suaves

  - Fotos circulares (200px × 200px)    • Ícones e elementos visuais intuitivos

  - Nome, graduação e especialidade de cada professor

  TECNOLOGIAS UTILIZADAS:

- **Seção Horários:**    • HTML5

  - Tabela com grade de treinos    • CSS3

  - Divisão por faixas etárias    • Design Responsivo (Mobile First)

      • Flexbox e Grid Layout

- **Seção CTA Final:**    • Google Fonts (Poppins)

  - Chamada para ação

  - Botão destacado para agendamento================================================================================

  OBSERVAÇÕES RELEVANTES

- **Footer:**================================================================================

  - Copyright © 2025

IMPORTANTE:

**Navegação:** → `cadastro.html` ou `login.html`    • Este é um protótipo front-end (interface apenas)

    • Não há integração com banco de dados ou backend

---    • Os formulários não processam dados realmente

    • As funcionalidades de login/cadastro são simuladas

#### 2. `cadastro.html` - Registro de Novos Usuários    • Os dados exibidos são estáticos/mockados

**Título:** Cadastro - CT JF Manager

NAVEGAÇÃO:

**Objetivo:** Permitir que novos usuários criem uma conta    • O menu de navegação está presente em todas as páginas autenticadas

    • Use os links do menu superior para navegar entre as páginas

**Conteúdo:**    • O botão de logout retorna para a página de login

- Formulário centralizado em card    • Links externos (WhatsApp) abrem em nova aba

- **Campos:**

  - Nome completo (text, required)DESIGN:

  - Email (email, required)    • Palette de cores: Azul (#2563eb) e tons de cinza

  - Telefone (tel, required)    • Fonte principal: Poppins (Google Fonts)

  - Data de Nascimento (date, required)    • Layout responsivo com breakpoints: 768px (tablet) e 1024px (desktop)

  - Senha (password, required)    • Espaçamento consistente e hierarquia visual clara

  - Confirmação de senha (password, required)

  - Categoria (select): Infantil, Juvenil, AdultoCOMPATIBILIDADE:

- Botão "Cadastrar" (azul, full-width)    • Testado nos navegadores modernos (Chrome, Firefox, Edge, Safari)

- Link para login: "Já possui conta? Faça login"    • Requer navegador com suporte a CSS Grid e Flexbox

    • Melhor visualização em telas de resolução mínima de 320px

**Validações (HTML5):**

- Campos obrigatóriosPRÓXIMOS PASSOS (Desenvolvimento Futuro):

- Formato de email    • Implementação do backend (API REST)

- Tipo de telefone    • Integração com banco de dados

    • Sistema de autenticação real (JWT)

**Navegação:** → `login.html` (após cadastro) ou `index.html` (voltar)    • Upload de vídeos e imagens

    • Sistema de pagamentos para inscrições

---    • Área administrativa para gestão do CT

    • Notificações em tempo real

#### 3. `login.html` - Autenticação    • Sistema de mensagens entre usuários

**Título:** Login - CT JF Manager

================================================================================

**Objetivo:** Autenticar usuários cadastradosCOMO VISUALIZAR O PROJETO

================================================================================

**Conteúdo:**

- Formulário centralizado em cardMÉTODO 1 - Arquivo Local:

- **Campos:**    1. Navegue até a pasta ct-jf-manager-front

  - Email (email, required)    2. Dê duplo clique no arquivo index.html

  - Senha (password, required)    3. O navegador padrão abrirá a página

- Checkbox "Lembrar-me"

- Botão "Entrar" (azul, full-width)MÉTODO 2 - Servidor Local (Recomendado):

- Link "Esqueceu sua senha?"    1. Instale a extensão "Live Server" no VS Code

- Link para cadastro: "Não tem conta? Cadastre-se"    2. Clique com botão direito no index.html

    3. Selecione "Open with Live Server"

**Navegação:** → `dashboard.html` (após login) ou `cadastro.html`    4. O projeto abrirá em http://localhost:5500



---MÉTODO 3 - Python:

    1. Abra o terminal na pasta ct-jf-manager-front

#### 4. `aula-experimental.html` - Agendamento de Aula    2. Execute: python -m http.server 8000

**Título:** Aula Experimental - CT JF Manager    3. Acesse: http://localhost:8000



**Objetivo:** Permitir que visitantes agendem uma aula experimental gratuita================================================================================

CONTATO E SUPORTE

**Conteúdo:**================================================================================

- Header público (igual ao index.html)

- Formulário de agendamentoPara dúvidas ou sugestões sobre este projeto, entre em contato:

- **Campos:**    Email: [seu-email@exemplo.com]

  - Nome completo    GitHub: [seu-usuario-github]

  - Email

  - Telefone================================================================================

  - Categoria de interesse                        Desenvolvido em Outubro/2025

  - Data preferencial================================================================================

  - Horário preferencial
  - Observações (textarea)
- Botão "Agendar Aula"
- Informações sobre a aula gratuita

**Navegação:** → `index.html`

---

### 🔐 PÁGINAS AUTENTICADAS (Requerem login)

**Header Padrão em Todas as Páginas:**
```html
Logo (clicável → dashboard) + Menu de Navegação:
├── Dashboard
├── Videoteca
├── Campeonatos
├── Ranking
├── Meu Perfil
└── Sair (→ index.html)
```

---

#### 5. `dashboard.html` - Painel Principal
**Título:** Dashboard - CT JF Manager

**Objetivo:** Visão geral do progresso e acesso rápido às funcionalidades

**Conteúdo:**
- **Welcome Header:**
  - Saudação personalizada: "Bem-vindo de volta, Daniel!"
  - Mensagem motivacional
  
- **Grid de Estatísticas (4 cards):**
  1. **XP Total:** 1250 pontos
  2. **Frequência:** 85% no mês
  3. **Técnicas Aprendidas:** 42 técnicas
  4. **Posição no Ranking:** #5 (card clicável → ranking.html)
  
- **Cada card possui:**
  - Ícone FontAwesome
  - Número grande (métrica)
  - Descrição

**Características Especiais:**
- Card de Ranking é um link (`<a>`) com estilo de card
- Efeito hover em todos os cards
- Layout responsivo (grid adaptativo)

**Menu Ativo:** Dashboard (classe `current`)

**Navegação:** → Qualquer página do menu, especialmente `ranking.html` pelo card

---

#### 6. `perfil.html` - Perfil do Aluno
**Título:** Meu Perfil - CT JF Manager

**Objetivo:** Gerenciar dados pessoais e visualizar carteirinha digital

**Conteúdo:**

**Layout:** Grid 2 colunas (desktop) / 1 coluna (mobile)

**Coluna Esquerda - Carteirinha Digital:**
- Design card especial (sticky em desktop)
- **Informações:**
  - Foto do aluno (circular, 100px)
  - Nome completo
  - Graduação (badge colorido)
  - CPF
  - Data de Nascimento
  - Categoria
  - ID único (estilo monospace)
  
- **Barra de Progresso XP:**
  - XP atual: 1250 / 1500
  - Barra visual animada (83%)
  - Texto: "250 XP para próxima faixa"

**Coluna Direita - Formulário de Edição:**
- Título: "Editar Informações Pessoais"
- **Campos:**
  - Nome completo
  - Email
  - Telefone
  - Data de Nascimento
  - Endereço
  - Cidade
  - Estado (select)
  - CEP
- Botão "Salvar Alterações"

**Menu Ativo:** Meu Perfil (classe `current`)

**Navegação:** → Qualquer página do menu

---

#### 7. `videoteca.html` - Biblioteca de Vídeos
**Título:** Videoteca - CT JF Manager

**Objetivo:** Acesso à biblioteca de técnicas de Jiu-Jitsu em vídeo

**Conteúdo:**

**Header da Página:**
- Título: "Videoteca de Técnicas"
- Descrição: "Acesse nossa biblioteca..."

**Sistema de Filtros:**
- **Busca por nome** (input text)
- **Categoria:** Todas, Guarda, Passagem, Finalização, Raspagem, Posições
- **Dificuldade:** Todas, Iniciante, Intermediário, Avançado
- Botão "Filtrar"

**Grid de Vídeos:**
- Layout responsivo (3 colunas → 2 → 1)
- **Cada card contém:**
  - Thumbnail do vídeo
  - Título da técnica
  - Categoria (badge)
  - Nível de dificuldade (badge colorido)
  - Duração
  - Botão "Assistir" → `tecnica-detalhe.html`

**Vídeos Exibidos (exemplos):**
1. Raspagem de Guarda Aranha (Raspagem, Intermediário, 8min)
2. Triângulo de Guarda Fechada (Finalização, Avançado, 12min)
3. Passagem de Guarda X (Passagem, Iniciante, 6min)

**Menu Ativo:** Videoteca (classe `current`)

**Navegação:** → `tecnica-detalhe.html` (ao clicar em "Assistir")

---

#### 8. `tecnica-detalhe.html` - Detalhes da Técnica
**Título:** Raspagem de Guarda Aranha - CT JF Manager

**Objetivo:** Exibir vídeo e informações detalhadas de uma técnica específica

**Conteúdo:**

**Breadcrumb:**
- Videoteca > Raspagem de Guarda Aranha

**Player de Vídeo:**
- Container responsivo (16:9)
- Iframe do YouTube incorporado
- Bordas arredondadas

**Informações da Técnica:**
- **Título:** Raspagem de Guarda Aranha
- **Badges:**
  - Categoria: Raspagem
  - Nível: Intermediário
- **Duração:** 8 minutos
- **Instrutor:** Professor Rafael

**Descrição Detalhada:**
- Texto explicativo da técnica
- Pontos-chave
- Dicas de execução

**Seção de Pontos-Chave:**
- Lista de fundamentos
- Erros comuns
- Variações possíveis

**Botão de Ação:**
- "Voltar para Videoteca" → `videoteca.html`

**Menu Ativo:** Videoteca (classe `current`)

**Navegação:** ← `videoteca.html`

---

#### 9. `campeonatos.html` - Listagem de Campeonatos
**Título:** Campeonatos - CT JF Manager

**Objetivo:** Exibir campeonatos disponíveis e permitir manifestação de interesse

**Conteúdo:**

**Header da Página:**
- Título: "Campeonatos Disponíveis"
- Descrição: "Participe de competições..."

**Sistema de Filtros:**
- **Busca por nome** (input text)
- **Status:** Todos, Aberto, Em breve, Encerrado
- **Categoria:** Todas, Infantil, Juvenil, Adulto, Master
- Botão "Filtrar"

**Grid de Campeonatos:**
- Layout responsivo
- **Cada card contém:**
  - Nome do campeonato
  - Data (ícone calendário)
  - Local (ícone localização)
  - Categoria
  - Status (badge colorido)
  - Botão "Tenho Interesse" → `campeonato-interesse.html`

**Campeonatos Exibidos (exemplos):**
1. Copa Primavera de Jiu-Jitsu (15/11/2025, SP, Todas, Aberto)
2. Campeonato Estadual (22/11/2025, RJ, Adulto/Master, Aberto)
3. Torneio Interno CT (05/12/2025, CT JF, Todas, Em breve)

**Menu Ativo:** Campeonatos (classe `current`)

**Navegação:** → `campeonato-interesse.html` (demonstrar interesse)

---

#### 10. `campeonato-interesse.html` - Demonstração de Interesse
**Título:** Interesse em Campeonato - CT JF Manager

**Objetivo:** Registrar interesse em participar de um campeonato

**Conteúdo:**

**Header da Página:**
- Título: "Demonstrar Interesse no Campeonato"
- Nome do campeonato em destaque

**Formulário:**
- **Informações Confirmadas (read-only):**
  - Nome do aluno
  - Email
  - Graduação atual
  
- **Campos Editáveis:**
  - Categoria desejada (select): Infantil, Juvenil, Adulto, Master
  - Peso atual (kg)
  - Divisão de peso (calculado/select)
  - Observações (textarea)
  
- **Confirmação:**
  - Checkbox: "Li e aceito o regulamento"
  
- Botão "Confirmar Interesse"
- Link "Voltar" → `campeonatos.html`

**Menu Ativo:** Campeonatos (classe `current`)

**Navegação:** ← `campeonatos.html`

---

#### 11. `ranking.html` - Ranking Mensal
**Título:** Ranking Mensal - CT JF Manager

**Objetivo:** Exibir classificação dos alunos baseada em pontos/XP

**Conteúdo:**

**Header da Página:**
- Título: "Ranking Mensal"
- Mês de referência: "Outubro 2025"
- Descrição: "Classificação baseada em frequência..."

**Lista de Ranking:**
- Lista ordenada de alunos
- **Cada item contém:**
  - Posição (número grande, colorido)
  - Nome do aluno
  - Graduação/Faixa
  - Pontuação total
  - Ícone de troféu para top 3
  
- **Destaque Especial:**
  - Aluno atual (#5 - Daniel) com borda destacada
  - Classe CSS: `current-user`
  - Box-shadow colorido

**Top 10 Exibido:**
1. 🥇 João Silva - Faixa Roxa - 2100 pts
2. 🥈 Maria Santos - Faixa Azul - 1850 pts
3. 🥉 Pedro Costa - Faixa Roxa - 1720 pts
4. Carlos Mendes - Faixa Azul - 1580 pts
5. **Daniel (Você)** - Faixa Azul - 1250 pts ⭐
6. ...

**Menu Ativo:** Ranking (classe `current`)

**Navegação:** → Qualquer página do menu

---

## 🎨 Arquivo CSS - `style.css`

### Estrutura do CSS

O arquivo `style.css` é **único e global**, contendo todos os estilos do projeto de forma organizada.

**Organização por Seções:**

```css
1. Variáveis CSS (--primary-color, --text-primary, etc.)
2. Reset e Estilos Base
3. Container e Layout Global
4. Header e Navegação
5. Botões
6. Seções e Títulos
7. Hero Section (index.html)
8. Seção Sobre/Filosofia
9. Seção Benefícios
10. Seção Equipe
11. Seção Horários
12. CTA (Call-to-Action)
13. Footer
14. Formulários de Autenticação
15. Dashboard
16. Perfil e Carteirinha
17. Videoteca
18. Campeonatos
19. Ranking
20. Utilitários
21. Media Queries (Responsividade)
```

### Paleta de Cores

```css
--primary-color: #2563eb;        /* Azul principal */
--primary-color-hover: #1d4ed8;  /* Azul hover */
--dark-bg: #0a0a0a;              /* Fundo escuro */
--content-bg: #1a1a1a;           /* Fundo de cards */
--text-primary: #f5f5f5;         /* Texto principal */
--text-secondary: #a0a0a0;       /* Texto secundário */
--border-color: #2a2a2a;         /* Bordas */
--success-color: #10b981;        /* Verde sucesso */
--warning-color: #f59e0b;        /* Amarelo aviso */
--error-color: #ef4444;          /* Vermelho erro */
```

### Tipografia

- **Fonte:** Poppins (Google Fonts)
- **Pesos:** 300, 400, 500, 600, 700, 800
- **Tamanhos Base:**
  - H1: 4rem (hero) / 2.8rem (seções)
  - H2: 2.8rem
  - H3: 2rem
  - Parágrafo: 1rem
  - Small: 0.9rem

### Componentes Reutilizáveis

#### Cards
```css
.card {
  background: var(--content-bg);
  border: 1px solid var(--border-color);
  border-radius: 12px;
  padding: 2rem;
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
}
```

#### Botões
```css
.btn-primary {
  background: #2563eb;
  color: #f5f5f5;
  padding: 0.8rem 2rem;
  border-radius: 8px;
  font-weight: 600;
}

.btn-primary:hover {
  background: #1d4ed8;
  transform: translateY(-3px);
}
```

#### Badges
```css
.badge {
  display: inline-block;
  padding: 0.4rem 1rem;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 500;
}
```

### Responsividade

**Breakpoints:**
- **Desktop:** > 992px (padrão)
- **Tablet:** 768px - 992px
- **Mobile:** < 768px

**Principais Ajustes Responsivos:**

```css
@media (max-width: 992px) {
  /* Grids de 2 colunas → 1 coluna */
  .about-section { grid-template-columns: 1fr; }
  .perfil-container { grid-template-columns: 1fr; }
  
  /* Imagens menores */
  .team-member-card img { width: 180px; height: 180px; }
}

@media (max-width: 768px) {
  /* Menu em coluna */
  .main-header .container { flex-direction: column; }
  
  /* Textos menores */
  .hero-bg h1 { font-size: 2.5rem; }
  
  /* Logo reduzido */
  .logo-link img { height: 60px; width: 60px; }
  
  /* Imagens ajustadas */
  .team-member-card img { width: 150px; height: 150px; }
}
```

---

## 🧭 Fluxo de Navegação Completo

### Jornada do Usuário Visitante

```
index.html (Landing Page)
    │
    ├─→ cadastro.html (Criar conta)
    │       │
    │       └─→ login.html
    │
    ├─→ login.html (Entrar)
    │       │
    │       └─→ dashboard.html ✓
    │
    └─→ aula-experimental.html (Agendar aula)
            │
            └─→ index.html (Confirmação)
```

### Jornada do Usuário Autenticado

```
dashboard.html (Hub Central)
    │
    ├─→ perfil.html (Meu Perfil)
    │     │
    │     └─→ Editar informações
    │
    ├─→ videoteca.html (Biblioteca)
    │     │
    │     └─→ tecnica-detalhe.html (Assistir vídeo)
    │           │
    │           └─→ videoteca.html (Voltar)
    │
    ├─→ campeonatos.html (Competições)
    │     │
    │     └─→ campeonato-interesse.html (Interesse)
    │           │
    │           └─→ campeonatos.html (Confirmar)
    │
    ├─→ ranking.html (Classificação)
    │     │
    │     └─→ Ver posição no ranking
    │
    └─→ index.html (Sair/Logout)
```

### Menu de Navegação (Header Autenticado)

```
┌─────────────────────────────────────────────────────┐
│ [Logo]  Dashboard | Videoteca | Campeonatos |       │
│         Ranking | Meu Perfil | Sair                 │
└─────────────────────────────────────────────────────┘
```

**Classe `current`:** Indica a página ativa no menu

---

## 🔧 Tecnologias Utilizadas

### Front-end
- **HTML5**
  - Semântica estrutural
  - Formulários com validação nativa
  - Elementos multimídia (iframe para vídeos)
  
- **CSS3**
  - Variáveis CSS (Custom Properties)
  - Flexbox e CSS Grid
  - Transições e animações
  - Media queries para responsividade
  
- **FontAwesome 6.0**
  - Ícones vetoriais
  - CDN: `cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3`
  
- **Google Fonts**
  - Família: Poppins
  - Pesos: 300, 400, 500, 600, 700, 800

### Recursos Externos
- **YouTube Embed:** Player de vídeo (iframe)
- **Unsplash:** Imagens de background (hero section)

---

## ⚙️ Funcionalidades Implementadas

### ✅ Recursos Disponíveis

- [x] Design responsivo (mobile-first)
- [x] Sistema de navegação consistente
- [x] Formulários com validação HTML5
- [x] Cards interativos com hover effects
- [x] Sistema de filtros (videoteca e campeonatos)
- [x] Player de vídeo incorporado (YouTube)
- [x] Carteirinha digital do aluno
- [x] Barra de progresso XP animada
- [x] Ranking com destaque do usuário atual
- [x] Badges coloridos por status/categoria
- [x] Grid responsivo adaptativo
- [x] Animações suaves (transitions)
- [x] Ícones vetoriais (FontAwesome)
- [x] Tipografia profissional (Google Fonts)

### ⚠️ Limitações (Protótipo Front-end)

- [ ] Sem integração com backend
- [ ] Sem banco de dados
- [ ] Sem autenticação real (simulada)
- [ ] Sem processamento de formulários
- [ ] Sem upload de arquivos
- [ ] Sem sistema de pagamentos
- [ ] Dados estáticos/mockados
- [ ] Sem validação server-side

---

## 📊 Tamanhos de Imagens

### Logo
- **Header:** 70px × 70px
- **Mobile:** 60px × 60px
- **Formato:** Circular com borda
- **Object-fit:** Cover

### Fotos de Professores
- **Desktop:** 200px × 200px
- **Tablet:** 180px × 180px
- **Mobile:** 150px × 150px
- **Formato:** Circular
- **Object-fit:** Cover

### Imagem Seção Filosofia
- **Desktop:** Max-height 500px
- **Tablet:** Max-height 400px
- **Mobile:** Max-height 300px
- **Object-fit:** Cover
- **Bordas:** Arredondadas (12px)

### Foto do Aluno (Carteirinha)
- **Tamanho:** 100px × 100px
- **Formato:** Circular
- **Borda:** 3px solid

---

## 🎯 Observações Importantes

### 🔴 Crítico

1. **Protótipo Apenas:** Este é um projeto de interface (front-end only). Não possui funcionalidades de backend, banco de dados ou autenticação real.

2. **Dados Simulados:** Todos os dados exibidos (rankings, vídeos, campeonatos, perfis) são estáticos e inseridos diretamente no HTML.

3. **Formulários Não Funcionais:** Os formulários possuem validação HTML5, mas não processam ou enviam dados para nenhum servidor.

4. **Navegação Simulada:** Links de login/cadastro redirecionam para o dashboard sem verificação real de credenciais.

### 🟡 Atenção

1. **Consistência Visual:** Todas as páginas autenticadas compartilham o mesmo header com menu de navegação.

2. **Classe `current`:** Cada página marca o item ativo no menu com a classe CSS `current`.

3. **Responsividade:** O layout se adapta a 3 tamanhos: desktop (>992px), tablet (768-992px) e mobile (<768px).

4. **Compatibilidade:** Testado em Chrome, Firefox, Edge e Safari. Requer suporte a CSS Grid e Flexbox.

### 🟢 Boas Práticas

1. **CSS Único:** Todo o estilo está em um único arquivo (`style.css`), facilitando manutenção.

2. **Semântica HTML:** Uso correto de tags semânticas (`<header>`, `<main>`, `<section>`, `<nav>`, etc.).

3. **Acessibilidade Básica:** Atributos `alt` em imagens, labels em formulários, contraste de cores adequado.

4. **Performance:** Uso de CDN para FontAwesome e Google Fonts.

---

## 🚧 Próximos Passos (Desenvolvimento Futuro)

### Fase 1: Backend Básico
- [ ] API REST com Node.js/Express ou Python/Flask
- [ ] Banco de dados (MongoDB ou PostgreSQL)
- [ ] Sistema de autenticação JWT
- [ ] CRUD de usuários

### Fase 2: Funcionalidades Core
- [ ] Upload de vídeos e imagens
- [ ] Sistema de pontuação/XP real
- [ ] Cálculo automático de ranking
- [ ] Gestão de presença e frequência

### Fase 3: Recursos Avançados
- [ ] Pagamento de mensalidades
- [ ] Inscrição em campeonatos
- [ ] Notificações push/email
- [ ] Chat entre alunos e professores
- [ ] Relatórios e dashboards administrativos

### Fase 4: Melhorias
- [ ] PWA (Progressive Web App)
- [ ] App mobile (React Native)
- [ ] Integração com redes sociais
- [ ] Gamificação expandida
- [ ] Sistema de badges e conquistas

---

## 📱 Compatibilidade e Requisitos

### Navegadores Suportados
- ✅ Google Chrome 90+
- ✅ Mozilla Firefox 88+
- ✅ Microsoft Edge 90+
- ✅ Safari 14+
- ✅ Opera 76+

### Resolução Mínima
- **Desktop:** 1024px × 768px (recomendado 1920×1080)
- **Tablet:** 768px × 1024px
- **Mobile:** 320px × 568px (iPhone SE)

### Recursos Necessários
- CSS Grid Layout
- CSS Flexbox
- CSS Custom Properties (variáveis)
- HTML5 Form Validation
- Suporte a iframe (para vídeos)

---

## 📞 Contato e Suporte

Para dúvidas, sugestões ou reportar problemas sobre este projeto:

- **Email:** [seu-email@exemplo.com]
- **GitHub:** [@seu-usuario](https://github.com/seu-usuario)
- **LinkedIn:** [Seu Nome](https://linkedin.com/in/seu-perfil)

---

## 📄 Licença

Este projeto foi desenvolvido como parte de um trabalho acadêmico.

**Uso educacional e demonstrativo.**

---

## 🏆 Créditos

**Desenvolvido por:** [Seu Nome]  
**Instituição:** [Nome da Universidade/Curso]  
**Disciplina:** [Nome da Disciplina]  
**Professor:** [Nome do Professor]  
**Data:** Outubro/2025

---

<div align="center">

### 🥋 CT Josuelmo Farias
**Transformando vidas através do Jiu-Jitsu**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile_First-green?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

**© 2025 - Todos os direitos reservados**

</div>
