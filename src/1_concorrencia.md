# Análise de concorrência

> **_NOTE:_**: O fator mais importante desta entrega é a equipe conseguir identificar e documentar prints de telas de interfaces concorrentes (ou interfaces representativas para o público alvo). Esses prints serão usados na fase de caracterização de padrões, affordances, heurísticas, etc. CONCORRENTE NÃO É IDÊNTICO E SIM ATUANDO NA MESMA ÁREA


## 1. Mapeamento de Concorrentes Principais
### 1.2. Hevy
> **Foco:** B2C / Acompanhamento Social de Treinos e Alta Performance.

* **Link de Acesso:** [hevy.com](https://hevy.com)
* **Descrição:** App global focado em frequentadores de academia que registram cargas e séries ativamente durante a execução, com forte apelo de comunidade e gamificação.
* **Prints de Telas & Interfaces Representativas:**
  * *Tela de Treino Ativo (*In-Workout UI*):* Tabela dinâmica para ajuste de carga/repetições, cronômetro de descanso automático e cálculo de tonelagem.
  * *Dashboard de Perfil:* Gráficos detalhados de volume semanal por grupo muscular e marcas de recordes pessoais (PRs).

---
### 1.2. Strong Workout Tracker

> **Foco:** B2C / Minimalismo, Agilidade e Privacidade.

* **Link de Acesso:** [strong.app](https://www.strong.app)
* **Descrição:** O pioneiro dos *gym logs* modernos. Conhecido pelo design extremamente limpo e pela digitação ultrarrápida durante a execução dos exercícios.
* **Interfaces Representativas (Prints para Análise):**
  * *Modo Treino:* Interface escura minimalista, foco total nos campos numéricos e temporizador flutuante na barra de notificações.
  * *Tela de Estatísticas:* Gráficos de linha limpos mostrando a progressão de peso e 1RM (1 Repetição Máxima) estimada ao longo do tempo.

---
### 1.3. Boostcamp

> **Foco:** B2C / Programas Prontos de Treinadores e Progressão de Carga.

* **Link de Acesso:** [boostcamp.app](https://www.boostcamp.app)
* **Descrição:** Junta o registro de treinos com a distribuição de programas e fichas consolidadas criadas por treinadores famosos e atletas de força.
* **Interfaces Representativas (Prints para Análise):**
  * *Visão de Programa:* Organização por Semanas e Dias (ex: *Semana 1 - Dia A*), mostrando a evolução da sobrecarga progressiva estipulada pelo programa.
  * *Comunidade de Programa:* Comentários e discussões específicas sobre o desempenho em cada ficha de treino.

---

## 2. Comparativo de Funcionalidades e Características

| Funcionalidade | **Hevy** | **Strong** | **Boostcamp** |
| :--- | :--- | :--- | :--- |
| **UX no Treino (*In-Workout*)** | Excelente; histórico automático, temporizador e superséries | Excelente; o padrão de mercado para digitação rápida | Boa; focada na progressão das semanas do programa |
| **Camada Social / Feed** | Feed completo com fotos, curtidas e comentários | Ausente (foco individual) | Média; fórum e avaliações dentro dos programas |
| **Análise por Grupo Muscular** | Séries semanais por músculo com código de cores | Volume e histórico por exercício individual| Acompanhamento de progresso por programa |
| **Smartwatches (WatchOS/WearOS)** | Sincronização em tempo real com Apple Watch e Wear OS | Aplicativo nativo maduro para Apple Watch | Suporte básico via Apple Health / Google Fit |

---
## 3. Análise da Experiência do Usuário (UX)

### Hevy
*  **Pontos Fortes:** Transição perfeita entre o registro individual do treino e o compartilhamento social. A visualização de séries semanais por grupo muscular ajuda no planejamento de hipertrofia.
*  **Pontos Fracos:** O feed social pode ser uma distração para quem prefere uma experiência estritamente focada e privada.

### Strong
*  **Pontos Fortes:** Automação de cargas do treino anterior (*ghost text*) economiza toques preciosos durante a execução. O temporizador de descanso na barra de notificações é impecável.
*  **Pontos Fracos:** Desenvolvimento e atualizações lentas nos últimos anos; limites rígidos no plano gratuito (máximo de 3 rotinas salvas).

### Boostcamp
*  **Pontos Fortes:** Excelente para quem prefere seguir rotinas comprovadas de hipertrofia/força prescritas por especialistas sem ter que criar fichas do zero.
*  **Pontos Fracos:** Menos flexível para adaptações rápidas no meio do treino (ex: trocar uma máquina ocupada por outra equivalente).

---
## 4. Preços e Modelos de Negócio

* **Hevy:** *Freemium B2C*. Gratuito até 4 rotinas salvas. Plano Pro por assinaturas de \~$2,99/mês, \~$23,99/ano ou Licença Vitalícia por \~$74,99.
* **Strong:** *Freemium B2C*. Gratuito até 3 rotinas salvas. Plano Pro por assinaturas de \~$4,99/mês, \~$29,99/ano ou Licença Vitalícia por \~$99,99.
* **FitNotes / Strive:** *FitNotes*: 100% Gratuito no Android. *Strive*: Freemium com compras dentro do app para recursos estatísticos avançados.
* **Boostcamp:** *Freemium B2C*. Acesso gratuito a vários programas base. Plano Pro por \~$8,99/mês ou \~$59,99/ano para acesso a rotinas e métricas avançadas.

---
## 5. Padrões e Tendências no Mercado (*Gym Logs*)

1. **Auto-Populate de Cargas Anteriores:** Exibição da carga/repetições da semana passada em formato *ghost text* no campo de digitação para guiar a sobrecarga progressiva.
2. **Cronômetro de Descanso Automático:** Disparo do temporizador de descanso instantaneamente ao clicar no botão de "check" da série realizada, com vibração ao zerar.
3. **Volume Semanal por Grupo Muscular:** Contadores visuais (barras ou anéis) que indicam se o usuário atingiu entre 10 e 20 séries semanais por agrupamento muscular.
4. **Notificação de Recorde Pessoal (PR):** Telas comemorativas e distintivos exibidos quando o usuário bate recorde de carga, repetições ou volume em um exercício.

---
## 6. Relatórios e Sumarização dos Resultados da Pesquisa de Campo

A pesquisa quantitativa e qualitativa foi realizada com uma amostra de **14 praticantes de musculação**[cite: 1]. Os dados revelam padrões críticos de comportamento, hábitos de registo e fricções na experiência do utilizador (UX).

---

### Perfil da Amostra e Hábitos
* **Status Atual:** **78,6%** (11 de 14) frequentam a academia atualmente e **21,4%** (3 de 14) já frequentaram.
* **Frequência Semanal:** **71,4%** dos utilizadores treinam **4 ou mais vezes por semana** (50% treinam 4x/semana e 21,4% treinam 5x ou mais/semana).
* **Tempo de Prática:** **78,6%** possuem mais de 6 meses de experiência em academia (28,6% entre 6 meses e 1 ano; 28,6% entre 1 e 3 anos; 21,4% mais de 3 anos).
* **Visualização Rápida do Treino (Escala 1 a 5):** **85,7%** (12 de 14) atribuíram nota **4 ou 5** para a importância de ver o treino do dia de forma imediata (71,4% atribuíram nota máxima 5).

---

### Como os Utilizadores Controlam o Treino
Apesar da elevada frequência de treino, a adesão a aplicações dedicadas ainda enfrenta grande fricção:

---

## 7. Extração de Pontos Positivos, Negativos e Recomendações

### Pontos Positivos das Soluções Concorrentes (A Importar)
* **Tabela de Treino Ativo (*In-Workout UI*):** Disposição limpa em colunas `[Série | Anterior | Carga (kg) | Repetições | Check]`.
* **Autopreenchimento Inteligente ("Ghost Text"):** Exibição automática dos valores usados na semana anterior como sugestão, reduzindo a necessidade de digitação.
* **Cronômetro de Descanso Automático:** Disparo do temporizador imediatamente após a confirmação de uma série concluída.
* **Métricas de Volume Muscular:** Gráficos simples que contabilizam as séries semanais por grupo muscular.

---

### Pontos Negativos a Evitar no Projeto
* **Burocracia na Digitação:** Exigir múltiplos cliques ou modais sobrepostos para confirmar cada série executada.
* **Nomenclatura Erudita e Sem Vídeo/GIF:** Utilizar nomes técnicos obscuros sem incluir termos populares ou demonstração visual curta.
* **Dependência Exclusiva de Conexão (Online-Only):** Perda de dados ou travamentos caso o sinal de internet falhe no subsolo da academia.
* **Infrequência e Bloqueios em Funções Básicas:** Limitar a quantidade de fichas ou histórico no plano gratuito.

---

### Recomendações Práticas para o Desenvolvimento com Base na Interface

1. **Atalho Direto para o Treino do Dia na Aba "Meus Treinos":**
   * **No Figma:** A aba central "Meus Treinos" já apresenta o botão principal azul `+ Iniciar novo treino` no topo e o card `Treino A - Peito e Tríceps` com o botão `Iniciar treino` em destaque.
   * **Recomendação de UX:** Garantir que o card do treino agendado para o dia atual apareça fixado no topo automaticamente ao abrir esta aba, permitindo o início do treino com apenas **1 toque** (atendendo à exigência de **85,7%** dos utilizadores da pesquisa).

2. **Aproveitamento da Seção "Exercícios Mais Praticados":**
   * **No Figma:** A tela exibe atalhos rápidos para exercícios frequentes como *Supino Reto*, *Agachamento*, *Rosca Direta* e *Puxada Alta*.
   * **Recomendação de UX:** Permitir que o utilizador toque diretamente nesses cards para ver o histórico de cargas, atalhos de execução ou adicionar rapidamente o exercício como um "extra" durante um treino em andamento.

3. **Integração do Registo do Treino com o Feed Social:**
   * **No Figma:** A tela "Início" possui um feed interativo exibindo publicações de treinos de amigos (ex: post do *Vinicius_Santos* e *Fabiani* com tempo de treino de 50 min e calorias).
   * **Recomendação de UX:** Ao finalizar um treino registrado na aba de treinos, o app deve sugerir automaticamente a publicação do resumo (com tempo decorrido, volume total e tags de amigos) no feed social, promovendo o engajamento comunitário estilo *Hevy*.

4. **Visualização Rápida de Métricas e Consistência na Tela de Perfil:**
   * **No Figma:** O perfil inclui contadores de seguidores/treinos, gráfico de barras com a "Atividade semanal" (de Segunda a Domingo) e atalhos para *Histórico*, *Metas de peso* e *Conquistas*.
   * **Recomendação de UX:** Utilizar o gráfico de barras para exibir o volume total erguido ou o tempo de treino em cada dia da semana, estimulando a consistência do utilizador através do acompanhamento visual imediato.

5. **Aprimoramento do Fluxo de Registo Ativo (Modo Treino):**
   * **Recomendação de UX:** Ao clicar no botão azul `Iniciar treino`, a interface do treino ativo deve carregar as cargas e repetições do treino anterior (ex: *"Último treino: Há 2 dias"*) em formato pré-preenchido ("ghost text"), reduzindo o esforço de digitação do utilizador durante o treino.
