# 🚀 Redesign Oficial Moderno | Portal SENAI São Paulo

> **Projeto Acadêmico & Tecnológico:** Este projeto representa uma proposta de redesign moderno e de alto impacto para o portal institucional do **SENAI São Paulo (Serviço Nacional de Aprendizagem Industrial)**, alinhado aos padrões da **Indústria 4.0**, acessibilidade web e excelência em Engenharia Front-End.

---

## 📌 Visão Geral do Projeto

O objetivo deste projeto é reimaginar a experiência digital do ecossistema educacional do **SENAI-SP**, trazendo uma interface fluida, imersiva e responsiva. O projeto foi concebido a partir de especificações de design extraídas via **Google Stitch MCP Server** e implementado em código limpo com **Tailwind CSS**.

### 🎨 Identidade Visual e Design System

O projeto adota o design system **"Industrial Tech Precision"**, preservando o patrimônio visual do SENAI com toques contemporâneos de alta tecnologia:

* **Vermelho Oficial SENAI (`#E30613` / `#B5000B`):** Aplicado com rigor em pontos estratégicos de conversão, botões de ação primária (*calls to action*), badges de destaque e âncoras interativas.
* **Cinza Escuro Industrial Slate (`#111827`):** Utilizado para conferir contraste, autoridade técnica em títulos, navegações secundárias, seções em modo escuro e rodapé institucional.
* **Branco Puro & Superfícies Neutras (`#FFFFFF`, `#F8F9FB`, `#F3F4F6`):** Criam uma respiração visual ampla e organizada para catálogos extensos de cursos e dados técnicos.
* **Tipografia Moderna:**
  * **Plus Jakarta Sans:** Títulos, *display hero*, botões e badges estruturais para transmitir inovação e elegância geométrica.
  * **Inter:** Corpo de texto, formulários e descrições para máxima legibilidade (padrão WCAG 2.1 AA).
* **Ícones:** Google Material Symbols Outlined.

---

## 🛠️ Arquitetura e Componentes Desenvolvidos

1. **Header Institucional Inteligente:**
   * Barra superior com avisos rápidos e localização de escolas.
   * Logomarca do SENAI-SP e menu com efeito de sublinhado animado.
   * **Portal do Aluno:** Botão de alta visibilidade com efeito *shimmer*, abrindo um modal interativo de login e autenticação (suportando CPF, e-mail institucional e integração Gov.br).
   * Menu responsivo *mobile drawer* para telas menores.

2. **Hero Section de Alta Tecnologia (Indústria 4.0):**
   * Título de grande impacto visual (*"Transforme seu Futuro na Indústria"*).
   * Indicadores de impacto com contadores numéricos animados (+2 Milhões de formados, 85% de empregabilidade, +90 escolas em SP).
   * Imagem de laboratório mecatrônico de alta resolução extraída do Stitch, com efeito sutil de paralaxe 3D ao movimento do mouse.

3. **Buscador Rápido Interativo (Quick Course Finder):**
   * Filtro em tempo real por termos de busca (ex: *Robótica, Mecatrônica, TI, IA*), modalidade (*Presencial, EAD, Híbrido*) e unidade do estado de São Paulo.
   * Feedback visual dinâmico com contagem de cursos e botão de reset.

4. **Área de Cursos em Destaque:**
   * Grade moderna no estilo *Bento Grid* com cards informativos.
   * Cursos destacados: **Automação & Robótica**, **TI & Inteligência Artificial**, **Mecânica de Precisão & CNC** e **Energia Solar & Eletroeletrônica**.
   * Informações detalhadas de carga horária, duração e tags de certificação.

5. **Diferenciais da Metodologia SENAI:**
   * 3 pilares fundamentais: *Laboratórios com Padrão de Fábrica*, *Certificação de Alto Reconhecimento* e *Docentes Especialistas do Mercado*.
   * Gráfico vetorial (*sparkline*) destacando a taxa de 85.4% de absorção no mercado de trabalho.

6. **Banner de Conversão Corporativo (Dark Slate):**
   * Chamada para o Processo Seletivo Unificado com opções de matrícula e consulta de edital.

7. **Footer Institucional Completo:**
   * Vínculo com o Sistema Indústria (**FIESP, CIESP, SESI, SENAI, IRS**).
   * Links úteis, canais de transparência, ouvidoria, newsletter interativa e redes sociais.

---

## 🔌 Integração com o Google Stitch MCP

A concepção dos layouts e componentes foi guiada pela ferramenta MCP oficial do Google Stitch:
* Conexão estabelecida via endpoint JSON-RPC 2.0 (`https://stitch.googleapis.com/mcp`).
* Extração das propriedades estruturais das telas e do design system **"Industrial Tech Precision"** do projeto `projects/5295729667993717786`.
* Conversão fidedigna das diretrizes de cores, tipografia, espaçamento 8pt e micro-interações para Tailwind CSS limpo e sem dependências pesadas de build.

---

## 💻 Como Visualizar Localmente

Não requer instalação de frameworks ou gerenciadores de pacotes. Basta abrir o arquivo `index.html` em qualquer navegador moderno:

1. Dê um duplo clique no arquivo [`index.html`](file:///d:/Antigravity/Stitch/index.html) ou abra-o pelo seu navegador preferido (Chrome, Edge, Firefox, Safari).
2. Para uma experiência otimizada de desenvolvimento com live-reload, você pode executar:
   ```bash
   npx serve .
   ```
   ou usar a extensão *Live Server* no editor.

---

## 📄 Licença e Aviso Legal

* **Finalidade:** Projeto acadêmico e de demonstração de engenharia de software e UI/UX front-end.
* **Marca Registrada:** Todas as marcas, logotipos e identificadores institucionais do SENAI e da FIESP pertencem aos seus respectivos detentores de direitos.
