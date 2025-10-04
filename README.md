# Trabalho Prático 05 - Semanas 7 e 8

**Páginas de detalhes dinâmicas**

Nessa etapa, vamos evoluir o trabalho anterior, acrescentando a página de detalhes, conforme o  projeto escolhido. Imagine que a página principal (home-page) mostre um visão dos vários itens que existem no seu site. Ao clicar em um item, você é direcionado pra a página de detalhes. A página de detalhe vai mostrar todas as informações sobre o item do seu projeto. seja esse item uma notícia, filme, receita, lugar turístico ou evento.

Leia o enunciado completo no Canvas. 

**IMPORTANTE:** Assim como informado anteriormente, capriche na etapa pois você vai precisar dessa parte para as próximas semanas. 

**IMPORTANTE:** Você deve trabalhar e alterar apenas arquivos dentro da pasta **`public`,** mantendo os arquivos **`index.html`**, **`styles.css`** e **`app.js`** com estes nomes, conforme enunciado. Deixe todos os demais arquivos e pastas desse repositório inalterados. **PRESTE MUITA ATENÇÃO NISSO.**

## Informações Gerais

- Nome: Bernardo Belini Vale
- Matricula: 1431332
- Proposta de projeto escolhida: Blog Automotivo
- Breve descrição sobre seu projeto: Um blog dedicado a entusiastas de automóveis onde os usuários podem compartilhar experiências, problemas e soluções relacionados aos seus veículos. A plataforma permite visualizar postagens na página principal e acessar detalhes completos ao clicar em cada postagem.

## Print da Home-Page

![alt text](<public/imagens/home page.png>)

## Print da página de detalhes do item

![alt text](public/imagens/Screenshot_1.png)

## Cole aqui abaixo a estrutura JSON utilizada no app.js

```javascript

const postagens = [
  {
    id: "1",
    autor: "Pedro Henrique",
    data: "12 de setembro de 2025",
    texto:"Fala pessoal, passando pra compartilhar uma situação chata que rolou com meu Fastback Abarth. Sempre gostei do carro, mas ultimamente venho percebendo um barulho estranho na suspensão, especialmente quando passo por buracos ou pisos irregulares. Parece um rangido que não tinha antes, e tô começando a ficar preocupado. Já conferi as buchas e parece que algumas estão meio gastas, mas ainda não levei no mecânico para um diagnóstico mais detalhado.",
    membro: "10/06/2025",
    imagem: "imagens/sherek.jpg"
  },
  {
    id: "2",
    autor: "Maria Clara",
    data: "10 de setembro de 2025",
    texto:"Fala pessoal, passando pra compartilhar uma situação chata que rolou com meu Fastback Abarth. Sempre gostei do carro, mas ultimamente venho percebendo um barulho estranho na suspensão, especialmente quando passo por buracos ou pisos irregulares. Parece um rangido que não tinha antes, e tô começando a ficar preocupado. Já conferi as buchas e parece que algumas estão meio gastas, mas ainda não levei no mecânico para um diagnóstico mais detalhado.",
    membro: "19/04/2025",
    imagem: "imagens/barney.jpeg"
  }

