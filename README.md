.🧮 Calculadora Simples Digital

.📝 Definição do Projeto
Este projeto é uma aplicação web que replica as funções lógicas e visuais de uma calculadora eletrônica física diretamente no navegador. O objetivo principal do desenvolvimento foi consolidar os conceitos de manipulação de strings, captura de eventos de interface e execução de operações aritméticas em tempo real através de código JavaScript puro (Vanilla JS).


.🛠️ Arquitetura e Definições Técnicas:
A estrutura do projeto foi dividida de forma modular para garantir um código limpo e de fácil manutenção:

.HTML5 (Interface Visual): Define o visor da calculadora (`<input>` ou `<div>` de exibição) e a grade de botões numéricos e operacionais utilizando elementos de botão comuns (`<button>`).
.CSS3 (Layout em Grade): Utiliza principalmente o **CSS Grid Layout** para organizar os botões de forma simétrica e perfeitamente alinhada, simulando o design de uma calculadora real, além de aplicar efeitos de transição (*hover*) quando o usuário passa o mouse ou clica nos botões.
.JavaScript ES6+ (Processamento Matemático): Controla todo o fluxo de entrada e saída de dados. É responsável por acumular os números clicados, identificar o operador matemático escolhido e disparar o cálculo final.


.⚙️ Funcionalidades e Regras de Negócio Explicadas:

.Escuta de Eventos (Event Listeners): O script adiciona ouvintes de clique em todos os botões. Quando um número é pressionado, o JavaScript intercepta esse valor e o concatena (junta) no visor de texto.
.Lógica de Avaliação de Expressões: Ao clicar no botão de igual (`=`), a aplicação processa a string matemática gerada no visor (por exemplo, `"15+5"`) e realiza a operação aritmética correspondente, devolvendo instantaneamente o resultado final (`20`).
.Tratamento de Limpeza (Clear): Implementação de funções para limpar totalmente o visor (função `C` ou `AC`), redefinindo as variáveis internas da aplicação para que um novo cálculo possa ser iniciado sem resíduos do anterior.
