# Lanche Fácil - Aplicativo de Registro de Pedidos

## Descrição Geral

Este aplicativo foi desenvolvido como parte da disciplina de **Programação Mobile** no curso de **Análise e Desenvolvimento de Sistemas - 3º semestre - FECAP**.

O app tem como objetivo **registrar pedidos de clientes** para a lanchonete **Lanche Fácil** (www.lanchefacil.com.br) em eventos e lojas físicas. O aplicativo permite que o cliente selecione o tipo de lanche desejado, insira seu nome e visualize o resumo do pedido antes de finalizar. A interface é simples e intuitiva, proporcionando uma experiência agradável para o usuário.

---

## Desenvolvedor

- **Nome:** Deivid Gomes de Oliveira  
- **Curso:** Análise e Desenvolvimento de Sistemas  
- **Semestre:** 3º  
- **Instituição:** FECAP  
- **Disciplina:** Programação Mobile  
- **Professor:** Vinícius Heltai  

---

## Tecnologias e Componentes Utilizados

- **Java**  
- **Android Studio**  
- **Layouts em XML**  
- **Navegação entre Activities com `Intent` + `Bundle`**  
- **Componentes Android:**
  - `Button`, `TextView`, `ImageView`, `TextInputLayout`, `EditText`

---

## Funcionalidades e Fluxo de Navegação

1. **Activity 1 – Tela de Boas-Vindas**
   - Exibe a logomarca da lanchonete.
   - Contém um botão “Iniciar Pedido” que leva à tela de Formulário de Pedido.

2. **Activity 2 – Formulário de Pedido**
   - O cliente seleciona o tipo de lanche através de botões ou uma lista.
   - O cliente insere seu nome utilizando um campo de texto (com `TextInputLayout`).
   - Após inserir os dados, o cliente clica no botão de confirmação para visualizar o resumo do pedido.

3. **Activity 3 – Resumo do Pedido**
   - Exibe o nome do cliente e o lanche escolhido em um `TextView` dinâmico.
   - Contém uma imagem decorativa de "Pedido Concluído".
   - Há um botão para retornar à tela inicial e fazer novos pedidos.

---

## Requisitos Atendidos

- ✅ Navegação entre **3 Activities**:
  - Tela de Boas-Vindas.
  - Formulário de Pedido.
  - Resumo do Pedido.
  
- ✅ Uso de:
  - `Button`, `TextView`, `TextInputLayout`, `ImageView` em todas as telas.
  
- ✅ Formulário com `TextInputLayout` para a inserção do nome do cliente.
  
- ✅ Exibição dinâmica do nome do cliente e do lanche escolhido.
  
- ✅ Botão de retorno na tela de resumo para permitir novos pedidos.

---

## Desafios e Decisões no Desenvolvimento

- **Navegação entre Activities:** Utilizei `Intent` e `Bundle` para transferir o nome e o lanche escolhido entre as activities de forma simples e eficiente.
  
- **Design e Usabilidade:** Busquei criar uma interface amigável e fácil de usar, utilizando imagens e cores agradáveis para tornar a experiência visualmente atrativa e intuitiva.

- **Reusabilidade:** A possibilidade de retornar à tela inicial na terceira activity permite que o cliente refaça o pedido de forma rápida e sem complicação.

---

## Executável

- **APK gerado:** `lancheFacil.apk`  
- **Projeto completo disponível em formato .zip**
