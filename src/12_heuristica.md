1) **Avaliação de IHC através de inspeção HEURÍSTICA [1 solução completa por pessoa da equipe - todas as telas do projeto]**

---

### Violação 1: Visualização dos Treinos em Cards Fixos e Neutros

* **Print da Tela:** 
  <img width="1919" height="920" alt="image" src="https://github.com/user-attachments/assets/d163c2bf-6be5-46e6-be21-84ac07ace302" />


* **Heurística Violada:** 
  **8. Projeto minimalista e estético** (e **4. Consistência e padrões**)

* **Grau de Severidade:** 
  `2` - Simples (Problema de baixa prioridade)

* **Descrição do Problema:**
  Na tela de treinos salvos, o card *"Treino A - Peito e Tríceps"* está envolto em um container amplo de fundo branco/neutro, gerando excesso de espaço sem aproveitamento adequado em telas desktop. Além disso, o menu de opções (`...`) no canto superior direito do card é muito discreto, reduzindo a visibilidade visual de ações importantes como editar ou excluir o treino.

* **Recomendação de Solução:**
  Reorganizar a exibição dos treinos salvos em um sistema de grid responsivo (cards de 2 a 3 colunas), aplicando maior destaque aos botões de ação e hierarquia visual clara às métricas de cada treino.

---

### Violação 2: Ausência de Atalho Direto para "Criar Treino" na Barra Lateral

* **Print da Tela:** 
  <img width="1919" height="919" alt="image" src="https://github.com/user-attachments/assets/8c000f35-c63f-4789-ae2d-ebeaa94914c3" />


* **Heurística Violada:** 
  **7. Flexibilidade e eficiência de uso**

* **Grau de Severidade:** 
  `2` - Simples (Problema de baixa prioridade)

* **Descrição do Problema:**
  O botão principal em destaque na barra lateral (Sidebar) é *"Começar Treino"*. No entanto, se o usuário desejar criar uma nova ficha de treino do zero (ação equivalente ao botão `+ Iniciar novo treino`), ele é obrigado a navegar primeiro até a aba **Treinos**. Não existe um atalho ou menu suspenso rápido na barra lateral para acionar a criação direta de novas fichas de treino a partir de qualquer página.

* **Recomendação de Solução:**
  Adicionar um menu suspenso (*dropdown*) ou submenu na Sidebar ao clicar/passar o mouse no botão de ação principal, oferecendo as opções: **"Iniciar Treino Atual"** e **"Criar Novo Treino"**.

---

### Violação 3: Falta de Ícones e Identificação nos Botões de Ação do Perfil

* **Print da Tela:** 
  <img width="1919" height="918" alt="image" src="https://github.com/user-attachments/assets/b98fd0ad-c4e8-48e8-8ebb-873b4d6957b9" />


* **Heurística Violada:** 
  **6. Reconhecimento em lugar de lembrança**

* **Grau de Severidade:** 
  `2` - Simples (Problema de baixa prioridade)

* **Descrição do Problema:**
  Na tela de Perfil, o painel de atalhos ("Histórico de treino", "Metas de peso", "Minhas Conquistas", "Configurações") utiliza blocos retangulares cinzas idênticos sem nenhum suporte visual (ícones). O usuário é forçado a ler todos os rótulos de texto para identificar o que procura, em vez de reconhecer instantaneamente as seções por meio de símbolos visuais universais.

* **Recomendação de Solução:**
  Incluir ícones representativos ao lado da rotulagem textual em cada um dos quatro botões (ex: ícone de histórico/relógio, balança/alvo para metas, troféu para conquistas e engrenagem para configurações).

---

2) **INDICAÇÃO DE BOAS PRÁTICAS DE HEURÍSTICA \- HEURÍSTICAS NÃO VIOLADAS \[1 solução completa por pessoa da equipe\]**

| # | Heurística de Nielsen | Exemplo de Aplicação Atendida no FitFEI |
| :-: | :--- | :--- |
| **1** | **Visibilidade do status do sistema** | **Destaque de Aba Ativa e Progresso:** O menu lateral destaca claramente a página atual em azul (`Início`, `Treinos` ou `Perfil`), e o widget *Meta Semanal* fornece visualmente a barra de progresso do usuário (*3 de 5 treinos concluídos*). |
| **2** | **Compatibilidade entre sistema e mundo real** | **Linguagem Natural do Domínio:** O sistema utiliza termos familiares e do cotidiano de praticantes de musculação, como *"Peito e Tríceps"*, *"Supino reto"*, *"Rosca Direta"*, *"Agachamento"*, *"kcal"* e *"min"*. |
| **3** | **Controle e liberdade para o usuário** | **Navegação Livre:** A Sidebar permanece fixa em todas as telas da aplicação, permitindo alternar a qualquer momento entre o feed social, gerenciamento de treinos e perfil sem perda de contexto ou etapas intermediárias. |
| **4** | **Consistência e padrões** | **Padronização Visual:** A estrutura em três colunas (Sidebar de navegação à esquerda, conteúdo principal ao centro e widgets laterais à direita) mantém o mesmo padrão gráfico e posicionamento em todas as páginas. |
| **5** | **Prevenção de erros** | **Contador de Caracteres no Feed:** No formulário de nova publicação (*"O que você quer compartilhar?"*), há um indicador explícito de limite (`0/500`), prevenindo que o usuário envie publicações que excedam o tamanho permitido. |
| **6** | **Reconhecimento em lugar de lembrança** | **Gráfico Semanal Visual:** O gráfico de barras no Perfil apresenta os dias da semana (S, T, Q, Q, S, S, D) indicando visualmente a frequência de treinos, dispensando o usuário de calcular mentalmente os dias em que se exercitou. |
| **7** | **Flexibilidade e eficiência de uso** | **Atalhos Rápidos de Exercícios:** Na aba *Treinos*, o painel de *"Exercícios mais praticados"* fornece botões diretos de cadastro para agilizar a criação de séries com os movimentos mais frequentes do usuário. |
| **8** | **Projeto minimalista e estético** | **Design Limpo (Clean UI):** A interface utiliza uma paleta de cores consistente (branco, tons de cinza e azul de destaque), bom espaçamento entre elementos e ausência de informações visuais desnecessárias ou poluídas. |
| **9** | **Auxiliar usuários a reconhecer e recuperar erros** | **Placeholders Orientativos:** Os campos de entrada da tela de login contêm mensagens de dica explicativas (*"Digite seu e-mail"*, *"Digite sua senha"*), auxiliando o correto preenchimento antes do envio. |
| **10** | **Ajuda e documentação** | **Rótulos e Status Contextuais:** Textos informativos de contexto, tais como *"Último treino: Há 2 dias"* ou *"Membro há 2 anos"*, orientam o usuário sobre as métricas do sistema de forma imediata e autodidática. |

---
