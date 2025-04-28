# Definição da Estrutura Base da Página - Site APAE

## Descrição 📝

Definir uma estrutura base de layout do site da APAE, incluindo o sistema de grade, espaçamentos (margens, preenchimentos), tamanhos de componentes e alinhamentos. Isso garantirá que todas as páginas do site sigam um padrão visual coeso, facilitando tanto o design quanto o desenvolvimento.

## Grid

Um grid em um protótipo é uma estrutura de linhas invisíveis que ajuda a organizar e alinhar os elementos na tela de forma ordenada.

|    Aspecto     | WEB         | Tablet     | Mobile  |
|:---------------|:------------|:----------|:--------|
| **Colunas**    | 12          | 12        | 12      |
| **Gutter**     | 20          | 16        | 8       |
| **Margem**     | 40          | 24        | 16      |

## Espaçamento Vertical

Espaçamento vertical é o espaço entre elementos de cima para baixo em um layout. Ele ajuda na organização, leitura e visualização do protótipo.

### 1. Espaçamento Vertical WEB

|   VARIÁVEL      |     VALOR    |    QUANDO USAR                                        | 
|:----------------|:-------------|:------------------------------------------------------|
| **spacing-xs**  | 4px          | Evitar uso                                            |
| **spacing-sm**  | 8px          | Evitar uso                                            | 
| **spacing-md**  | 16px         | Listagens, inputs, subtítulos                         |
| **spacing-lg**  | 24px         | Espaço padrão entre componentes (cards, blocos)       |
| **spacing-xl**  | 32px         | Espaço entre blocos, cards maiores, padding interno de blocos |
| **spacing-2xl** | 40px         | Separação de grupos dentro de uma mesma página (ex: cards e seções) |
| **spacing-3xl** | 48px         | Separação entre blocos visuais maiores                |
| **spacing-4xl** | 64px         | Separação de áreas totalmente distintas (ex: entre o hero e o conteúdo, ou com o footer) |

### 2. Espaçamento Vertical TABLET

|   VARIÁVEL      |     VALOR    |    QUANDO USAR                                        | 
|:----------------|:-------------|:------------------------------------------------------|
| **spacing-xs**  | 4px          | Evitar uso                                            |
| **spacing-sm**  | 8px          | Igual ao mobile: microespaçamentos                    | 
| **spacing-md**  | 16px         | Ícones, labels, elementos próximos                    |
| **spacing-lg**  | 24px         | Espaço padrão entre componentes                       |
| **spacing-xl**  | 32px         | Cards com mais respiro, sessões dentro da mesma área  |
| **spacing-2xl** | 40px         | Separação entre grupos de conteúdo                    |
| **spacing-3xl** | 48px         | Espaço entre grandes sessões                          |
| **spacing-4xl** | 64px         | Evitar uso                                            |

### 3. Espaçamento Vertical MOBILE

|   VARIÁVEL      |     VALOR    |    QUANDO USAR                                        | 
|:----------------|:-------------|:------------------------------------------------------|
| **spacing-xs**  | 4px          | Ícones pequenos, detalhes sutis (ícone + texto, checkbox, microcomponentes) |
| **spacing-sm**  | 8px          | Espaço entre label e input, entre itens compactos     | 
| **spacing-md**  | 16px         | Espaço padrão entre blocos (ex: entre cards, seções, parágrafos) |
| **spacing-lg**  | 24px         | Espaço entre grupos (ex: lista de produtos e uma nova sessão) |
| **spacing-xl**  | 32px         | Espaço entre áreas maiores (ex: título de seção e grid de conteúdo) |
| **spacing-2xl** | 40px         | Evitar uso                                           |
| **spacing-3xl** | 48px         | Evitar uso                                           |
| **spacing-4xl** | 64px         | Evitar uso                                           |

## Espaçamento Horizontal

Espaçamento horizontal é o espaço entre elementos lado a lado. Ele organiza o layout na largura e evita que os itens fiquem amontoados.

|    Aspecto     | WEB         | Tablet     | Mobile  |
|:---------------|:------------|:----------|:--------|
| **Margem**     | 10px        | 8px       | 4px     |

## Frames Indicados

- Desktop
- iPad mini 8.3 - 1
- Iphone SE

## Botões

### 1. Botão Primário

| Aspecto                     | Web                                | Tablet                             | Mobile                          |
|------------------------------|------------------------------------|------------------------------------|---------------------------------|
| **Altura**                   | 48px                               | 48px                               | 48px                            |
| **Largura**                  | 144–240px                         | 144–200px                         | 100% do container               |
| **Padding**                  | 16px lateral                      | 12–16px lateral e vertical         | 16px lateral                    |
| **Ícone**                    | 24x24px                           | 24x24px                            | 24px                            |
| **Espaçamento ícone + texto** | 8–12px                            | 8–12px                             | 8–12px                          |
| **Texto**                    | 16–18px (600)                     | 16px (600)                         | 16px (600)                      |
| **Alinhamento**              | Centralizado (ícone à esquerda)    | Centralizado (ícone à esquerda)    | Centralizado (ícone à esquerda) |

### 2. Botão Secundário

| Aspecto                     | Web                                | Tablet                             | Mobile                          |
|------------------------------|------------------------------------|------------------------------------|---------------------------------|
| **Altura**                   | 48px                               | 48px                               | 48px                            |
| **Largura**                  | 144–200px                         | 144–160px                         | 100% do container               |
| **Padding**                  | 16px lateral                      | 16px lateral                      | 16px lateral                    |
| **Texto**                    | 16px (500)                        | 16px (500)                         | 16px (500)                      |

### 3. FAB (Floating Action Button)

| Aspecto                     | Web                                | Tablet                             | Mobile                          |
|------------------------------|------------------------------------|------------------------------------|---------------------------------|
| **Tamanho**                  | 56x56px                           | 56x56px                            | 56x56px                         |
| **Ícone**                    | 24px                              | 24px                               | 24px                            |

## Inputs

| Aspecto                      | Web                                              | Tablet                                             | Mobile                          |
|------------------------------|--------------------------------------------------|----------------------------------------------------|---------------------------------|
| **Altura**                    | 44px – 48px                                      | 48px                                               | 48px                            |
| **Largura**                   | 240px min / 360–400px ideal                      | 100% (formulários) / 320–400px (isolados)           | 100%                            |
| **Padding**                   | 12px – 16px lateral                             | 12px lateral                                       | 12px – 16px                     |
| **Borda radius**              | 4px – 8px                                        | 6px – 8px                                          | 8px                             |
| **Ícone dentro do input**      | 16px – 20px                                      | 20px – 24px                                        | 20px – 24px                     |
| **Ícones isolados (ações)**    | 20px – 24px                                      | 24px                                               | 24px – 28px                     |
| **Espaçamento ícone + texto**  | 8px – 12px                                       | 12px – 16px                                        | 12px – 16px                     |
| **Texto**                     | 14px – 16px (regular)                            | 16px (regular)                                     | 16px – 18px (regular)           |

## Cards

### 1. Cards - Estrutura Geral

|               | WEB                     | Tablet                  | Mobile                                         |
|:--------------|:------------------------|:------------------------|:-----------------------------------------------|
| **Altura**    | 160px min                | 160px min               | 140px min                                     |
| **Largura** (sem hug) | 240–360px largura   | 200–320px               | 100% do container (com margens de 16px)        |
| **Tamanho de Texto** | 14px–16px (Regular)  | 16px (Regular)          | 16px–18px (Regular)                           |
| **Padding Interno** | 16px–24px            | 16px–20px               | 16px–20px                                     |

### 2. Cards - Conteúdo Interno

|                | WEB                     | Tablet                  | Mobile                                         |
|:---------------|:------------------------|:------------------------|:-----------------------------------------------|
| **Título**     | 18px–20px (600)          | 18px–20px (600)         | 18px–20px (600)                               |
| **Texto**      | 14px–16px (regular)      | 14px–16px (regular)     | 14px–16px (regular)                           |

## Títulos


| **Tipo de Título** | **Tamanho WEB** | **Tamanho MOBILE** | **Peso** | **Espaçamento** |
|---------------------|-----------------|--------------------|----------|-----------------|
| **H1**              | 36px            | 28px               | 700      | 24px            |
| **H2**              | 24px            | 20px               | 600      | 16px            |
| **H3**              | 20px            | 18px               | 500      | 12px            |
| **H4**              | 18px            | 18px               | 400      | 8px             |

## Definições de Tipografia

### Tipografia

- **Títulos (H1, H2)**:  
  Fonte: `Baloo 2`  
  Peso: **700** (Bold para H1, SemiBold para H2)  
  Tamanho:
  - **H1**: 36px (WEB), 28px (MOBILE)  
  - **H2**: 24px (WEB), 20px (MOBILE)  
  - **H3**: 20px (WEB), 18px (MOBILE)  
  - **H4**: 18px (WEB e MOBILE)  
  Espaçamento:  
  - **H1**: 24px abaixo  
  - **H2**: 16px abaixo  
  - **H3**: 12px abaixo  
  - **H4**: 8px abaixo  

- **Texto Comum (Parágrafos)**:  
  Fonte: `Nunito`  
  Peso: **Regular** (16px)  
  - **Tamanho**: 16px (WEB e MOBILE)  
  - **Espaçamento**: 8px abaixo de cada parágrafo  
  - **Espaçamento entre linhas (line-height)**: 1.5x o tamanho da fonte (24px)
  
- **Botões**:  
  Fonte: `Baloo 2`  
  Peso: **SemiBold**  
  Tamanho: 16px (em maiúsculas ou capitalizado)  
  - **Espaçamento**: 8px de padding interno  
  - **Altura**: 40px (geral)  

- **Textos de Apoio** (ex.: rodapés, rótulos, etc.):  
  Fonte: `Nunito`  
  Peso: **Light**  
  Tamanho: 14px  
  - **Espaçamento**: 6px abaixo, se houver outros elementos subsequentes.

### Resumo da Hierarquia:

| Elemento        | Peso      | Tamanho | Estilo / Uso recomendado |
|------------------|-----------|---------|--------------------------|
| **H1**           | 700 (Bold) | 36px (WEB), 28px (MOBILE) | Título principal, seções |
| **H2**           | 600 (SemiBold) | 24px (WEB), 20px (MOBILE) | Títulos secundários, subseções |
| **H3**           | 500 (Medium) | 20px (WEB), 18px (MOBILE) | Subtítulos menores |
| **H4**           | 400 (Regular) | 18px (WEB e MOBILE) | Títulos de menor hierarquia |
| **Texto Comum**  | Regular    | 16px (WEB e MOBILE) | Parágrafos, corpo de texto |
| **Textos de Apoio** | Light   | 14px | Rodapés, rótulos e mensagens explicativas |
| **Botões**       | SemiBold  | 16px (capitalizado) | Texto de botões |
