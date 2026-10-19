# VetCare_Hospital
Página HTML de uma clínica veterinária

VetCare - Hospital Veterinário e Centro Diagnóstico

Uma aplicação web moderna, acessível e responsiva desenvolvida para simular a presença online do VetCare, um hospital veterinário e centro diagnóstico com atendimento 24 horas.

## 📌 Visão Geral e Objetivo

O objetivo deste projeto é entregar uma solução front-end completa e profissional para a clínica veterinária fictícia VetCare. A interface foi desenvolvida focando na melhor experiência do usuário (UX), semântica do HTML5, padrões de acessibilidade, responsividade fluida e uma arquitetura CSS bem definida.

Principais Objetivos:

Apresentar o hospital veterinário, seus serviços, infraestrutura e corpo clínico.

Facilitar a navegação do tutor através de um menu fixo com rolagem suave.

Fornecer um canal direto de contato emergencial via API do WhatsApp.

Garantir leitura e uso confortáveis em dispositivos móveis, tablets e desktops.

## 🛠️ Tecnologias e Conceitos Aplicados

HTML5 Semântico: Uso correto de tags (<header>, <nav>, <main>, <section>, <article>, <details>, <summary>, <footer>) garantindo acessibilidade e estrutura limpa.

CSS3 Moderno & CSS Variables: Utilização de tokens de design para controle unificado de paleta de cores, tipografia, sombras e espaçamentos.

Metodologia BEM (Block Element Modifier): Padrão rigoroso de nomenclatura de classes para evitar conflitos de estilo e manter o código escalável.

Flexbox Layout: Construção de containers flexíveis e alinhamentos para componentes e cards.

Tipografia Escalável (rem): Definição proporcional de fontes, espaçamentos e bordas no CSS a partir da raiz (html), permitindo alta flexibilidade e acessibilidade visual.

Responsividade Fluida (Media Queries): Adaptação contínua do layout para múltiplos tamanhos de tela.

Interatividade & Microinterações: Pseudo-classes (:hover, :focus), efeitos de transição (transition) e sombras dinâmicas (box-shadow).

Integração Externa:

Google Fonts: Importação da família tipográfica Poppins (pesos 400, 500, 600 e 700).

API do WhatsApp: Botão flutuante para contato direto com a instituição.

## 📁 Arquitetura de Arquivos

O projeto segue estritamente o princípio de separação de responsabilidades, mantendo o código limpo e organizado:

vetcare-hospital/
│
├── index.html            # Estrutura principal da página (HTML5 Semântico)
├── README.md             # Documentação completa do projeto
│
├── css/
│   ├── style.css         # Arquivo principal de estilos (Importações, Variáveis e Estilos Globais)
│   ├── reset.css         # Reset básico de estilos padrão dos navegadores
│   └── components/       # (Opcional) Estilos modularizados por componentes/seções
│
└── assets/
    └── images/           # Imagens e recursos visuais do projeto


## 🚀 Instruções de Visualização e Execução

Pré-requisitos

Para visualizar a aplicação em sua máquina local, você precisará apenas de um navegador web atualizado (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, etc.).

Passo a Passo

Clonar o Repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git


Acessar a Pasta do Projeto:

cd seu-repositorio


Executar a Aplicação:

Abra o arquivo index.html diretamente em seu navegador dando um duplo clique sobre ele.

Alternativamente, se estiver utilizando o VS Code, utilize a extensão Live Server para rodar o projeto em um servidor local.

## 💡 Desafios Técnicos e Aprendizados

Ajuste de Âncora com Menu Lateral Fixo:

Desafio: Como o menu lateral e o rodapé possuem posicionamento fixo (position: fixed), o conteúdo das seções ao navegar via links internos tendia a ficar oculto sob as barras de navegação.

Aprendizado: Ajuste de preenchimento (padding) nas seções e controle fino de rolagem com a propriedade CSS scroll-behavior: smooth, garantindo que a navegação âncora posicione o conteúdo perfeitamente na viewport.

Adoção da Escala REM e Layout Fluído:

Desafio: Substituir completamente os valores fixos em pixels por unidades relativas (rem, %, vh, vw).

Aprendizado: Configurar a porcentagem da fonte base no elemento html permitiu uma escala tipográfica proporcional e facilidade no ajuste de responsividade para diferentes resoluções de tela.

Metodologia BEM em Componentes Repetitivos:

Desafio: Manter a nomenclatura de classes organizada nos cards de especialidades, corpo clínico e na seção de FAQ sem gerar especificidade excessiva no CSS.

Aprendizado: O uso do padrão bloco__elemento--modificador garantiu seletores CSS limpos, modulares e reutilizáveis.

## 📞 Contato e Atendimento

Cliente: VetCare Hospital Veterinário

Atendimento: Pronto Atendimento 24 Horas

Instituição de Ensino Responsável: Escola SENAI Henrique Lupo

Projeto desenvolvido como parte da avaliação prática de desenvolvimento Front-End.