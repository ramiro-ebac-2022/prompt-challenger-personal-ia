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


# Contexto.
Você é um especialista Personal Trainer e vai me ajudar a montar um treino ideal, baseado nas três variáveis abaixo : 

{{Biotipo_Corporal}}
{{Dias_Treino}}
{{Tipo_Treino}}

# Regras.
* Regra 1: Biotipo_Corporal.
Identificar qual o Biotipo_Corporal, que pode ser alguns dos itens abaixo : 
- Ectomorfo : Corpo mais magro, difícil ganhar peso e massa muscular.
- Mesomorfo : Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
- Endomorfo : Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

* Regra 2: Dias_Treino.
Dependendo da quantidade minima de dias informado na variável Dias_Treino, que pode ser uns dos itens abaixo : 
- 1 dia: Treino Full Body
- 3 dias: Treino ABC
- 5 dias: Treino ABCDE

* Regra 3: Tipo_Treino.
Dependendo do Tipo_Treino informado, que pode ser um dos itens abaixo : 
- Funcional : Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
- Maquinário : Exercícios feitos em máquinas, com foco em isolar grupos musculares.
- Peso Livre : Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
- Cardio : Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
- HIIT : Treinos intervalados de alta intensidade, ótimos para queima de gordura.

# Resultado esperado
Com base nos valores informados nas três variáveis, e conforme às regras correspondentes, crie um treino ideal para a pessoa que combina os seguintes valores das variáveis : 
{{Biotipo_Corporal}} : Endomorfo.
{{Dias_Treino}} : 3 dias.
{{Tipo_Treino}} : Peso Livre e Funcional.
No final, sugerir duas opções de dieta (Segunda a Sexta) para potencializar os treinos dependendo do biotipo.

# Resposta :
Treino Ideal
Biotipo Corporal: Endomorfo
Dias de Treino: 3 dias (Treino ABC)
Tipo de Treino: Peso Livre e Funcional

Estrutura do Treino ABC
Dia A: Peito e Tríceps

Supino reto com halteres - 4x10
Supino inclinado com halteres - 4x12
Flexões de braço - 3x15
Tríceps banco - 3x12
Tríceps francês com halteres - 3x12
Dia B: Costas e Bíceps

Remada curvada com halteres - 4x10
Remada unilateral - 4x12
Pulldown (barra) - 3x15
Rosca direta com halteres - 3x12
Rosca martelo - 3x12
Dia C: Pernas e Core

Agachamento com halteres - 4x12
Afundos com halteres - 4x10 cada perna
Stiff com halteres - 3x12
Elevação de panturrilhas - 4x15
Prancha - 3x30 segundos
Obs: Esse treino combina pesos livres com movimentos funcionais para ativar os grandes grupos musculares e promover gasto calórico eficiente, essencial para endomorfos que buscam perda de gordura.

Opções de Dieta (Segunda a Sexta)
Dieta 1 - Foco em Controle de Carboidratos

Café da Manhã: Omelete de 3 ovos com espinafre, 1 fatia de pão integral, chá verde.
Lanche da Manhã: Iogurte grego sem açúcar e 1 maçã.
Almoço: Frango grelhado (150g), brócolis cozido e 1 batata-doce pequena.
Lanche da Tarde: 1 punhado de nozes e 1 banana.
Jantar: Peixe grelhado (120g) com salada de folhas verdes, tomate e azeite de oliva.
Dieta 2 - Foco em Proteína e Baixo Carboidrato à Noite

Café da Manhã: Aveia com leite desnatado, morangos e sementes de chia.
Lanche da Manhã: 1 fatia de queijo branco com 1 pera.
Almoço: Filé de carne magra (150g), arroz integral (1 xícara), legumes variados no vapor.
Lanche da Tarde: 1 shake de proteína com água e 1 laranja.
Jantar: Salada de atum com mix de folhas, pepino e cenoura ralada, temperado com limão e azeite.
Dica: A dieta para endomorfos deve ser moderada em carboidratos, rica em proteínas e com boas fontes de gordura para ajudar na saciedade e controle do peso.
