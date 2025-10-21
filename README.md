# Primeiro Grito: A Jornada do Parto Humanizado

Um quiz educacional interativo em formato de roleta, focado em conscientizar sobre o parto humanizado, violência obstétrica e os direitos da gestante.

Este projeto foi criado como uma ferramenta lúdica para informar sobre as fases do parto, intervenções comuns e os direitos garantidos por lei à gestante. O objetivo é fortalecer e informar mulheres e suas redes de apoio para uma experiência de parto mais positiva e respeitosa.

## 🕹️ Como Jogar

1.  Abra o arquivo `index.html` em qualquer navegador web.
2.  Na tela inicial, você verá a pontuação máxima já alcançada (salva localmente).
3.  Clique em **"Iniciar Jogo"**.
4.  Você será levado à **Roleta do Conhecimento**. Clique em **"Girar"**.
5.  A roleta parará em um dos 8 tópicos, e uma pergunta de múltipla escolha aparecerá.
6.  Selecione a resposta que julgar correta.
    * **Acerto:** Você ganha +10 pontos e recebe um feedback positivo.
    * **Erro:** Você perde -5 pontos (a pontuação não fica negativa) e vê a explicação da resposta correta.
7.  Clique em **"Próxima Rodada"** para poder girar a roleta novamente.
8.  O jogo termina após **10 perguntas**.
9.  Um pop-up de resultado aparecerá, cobrindo a tela com uma mensagem personalizada, um emoji e sua pontuação final, baseados no seu desempenho.

## ✨ Features (Funcionalidades)

* **Tela Inicial Acolhedora:** Mostra o título do jogo e a pontuação máxima salva.
* **Roleta do Conhecimento:** Uma roleta 100% CSS (`conic-gradient`) com 8 tópicos essenciais:
    1.  Sinais e Fases do Parto
    2.  Direitos (Geral)
    3.  Alívio e Posições
    4.  Apoio (Acompanhante/Doula)
    5.  Intervenções (Episio/Ocitocina)
    6.  Violência Obstétrica
    7.  O que Evitar (Jejum, Tricotomia)
    8.  Ambiente de Parto
* **Quiz Interativo:** 10 rodadas de perguntas e respostas com feedback imediato.
* **Sistema de Pontuação:** Incentiva o aprendizado (`+10` por acerto, `-5` por erro).
* **Resultados Personalizados:** 11 faixas de mensagens finais (de 0 a 100 pontos), oferecendo incentivo e um emoji correspondente ao desempenho.
* **Salva Pontuação Máxima:** Utiliza o `localStorage` do navegador para guardar a maior pontuação.
* **100% Responsivo:** Design adaptável que funciona perfeitamente em celulares e desktops.
* **Visual Lúdico:** Inclui decorações (como pétalas flutuantes) para criar um ambiente leve e convidativo.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica do jogo.
* **CSS3:** Estilização completa, responsividade (Media Queries), animações e a criação da roleta com `conic-gradient`.
* **JavaScript (Puro/Vanilla):** Controla toda a lógica do jogo, incluindo:
    * O giro e seleção da roleta.
    * O sistema de perguntas e respostas.
    * O cálculo de pontuação.
    * A manipulação do DOM (mostrar/esconder telas).
    * O gerenciamento do `localStorage` para a pontuação máxima.
    * A exibição do modal de resultado final.

## 🚀 Como Usar

Não é necessária nenhuma instalação ou servidor.

1.  Clone este repositório ou baixe o arquivo `index.html`.
2.  Abra o arquivo `index.html` diretamente no seu navegador de preferência (Google Chrome, Firefox, Safari, Edge, etc.).
3.  Jogue!

## 📄 Licença

Este projeto é distribuído sob a licença MIT.
