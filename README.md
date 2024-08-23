# CriandoUmPersonalTrainnerComIA
<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto





Ótima estrutura para o prompt de resposta! Com base no seu exemplo, o plano de treino gerado pode ser ajustado para incluir todas as informações necessárias. Aqui está o prompt de resposta completo e formatado, pronto para ser utilizado:

---

## 🎯 Prompt de Resposta Proposto

### Prompt de Entrada

"Você é um assistente de personal trainer. Meu objetivo é receber um plano de treino personalizado com base nas seguintes informações:

1. **Biotipo Corporal**: (Escolha um dos seguintes: Ectomorfo, Mesomorfo, Endomorfo)
2. **Dias Disponíveis para Treino**: (Escolha um dos seguintes: 1 dia, 3 dias, 5 dias)
3. **Tipo de Exercício Preferido**: (Escolha um dos seguintes: Funcional, Maquinário, Peso Livre, Cardio, HIIT)

Com base nas informações fornecidas, gere um plano de treino detalhado para a semana, incluindo o tipo de treino (Full Body, ABC, ABCDE) e uma lista de exercícios recomendados com repetições e séries."

### Exemplo de Resposta

**Plano de Treino Personalizado**

**Biotipo Corporal**: Mesomorfo  
**Dias Disponíveis para Treino**: 5 dias  
**Tipo de Exercício Preferido**: Peso Livre  

**Treino ABCDE**

**Dia 1: Peito**  
- **Supino reto com barra**: 4 séries de 8-12 repetições  
- **Supino inclinado com halteres**: 3 séries de 10-15 repetições  
- **Crucifixo com halteres**: 3 séries de 12-15 repetições  
- **Flexões**: 3 séries até a falha

**Dia 2: Costas**  
- **Puxada na frente com barra**: 4 séries de 8-12 repetições  
- **Remada curvada**: 3 séries de 10-12 repetições  
- **Puxada atrás com barra**: 3 séries de 12-15 repetições  
- **Barra fixa**: 3 séries até a falha

**Dia 3: Pernas**  
- **Agachamento com barra**: 4 séries de 8-12 repetições  
- **Leg press**: 3 séries de 10-15 repetições  
- **Extensão de pernas**: 3 séries de 12-15 repetições  
- **Flexão de pernas**: 3 séries de 12-15 repetições

**Dia 4: Ombros**  
- **Desenvolvimento com barra**: 4 séries de 8-12 repetições  
- **Elevação lateral**: 3 séries de 12-15 repetições  
- **Elevação frontal**: 3 séries de 12-15 repetições  
- **Encolhimento de ombros com barra**: 3 séries de 10-12 repetições

**Dia 5: Bíceps e Tríceps**  
- **Rosca direta com barra**: 4 séries de 8-12 repetições  
- **Rosca alternada com halteres**: 3 séries de 10-12 repetições  
- **Tríceps na polia alta**: 4 séries de 12-15 repetições  
- **Mergulho**: 3 séries até a falha

**Nota:** Ajuste o peso e a intensidade conforme seu nível de condicionamento físico e objetivos pessoais. Lembre-se de fazer um aquecimento adequado antes dos treinos e de incluir um período de recuperação entre as sessões. Hidratação e alimentação adequada também são essenciais para alcançar os melhores resultados.

---

Esse exemplo de resposta proporciona um plano de treino completo e detalhado, alinhado com o biotipo corporal, a disponibilidade de dias e o tipo de exercício preferido do usuário.
