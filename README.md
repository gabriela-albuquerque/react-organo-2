#🗂️ Organo - Sistema de Organograma Interativo

Este projeto foi um aprimoramento da versão anterior e foi desenvolvido ao longo de uma formação em React da Alura. A nova versão do Organo inclui um segundo formulário para cadastrar novos times, o recurso de excluir e favoritar colaboradores, além da possibilidade de alterar a cor de um time.

##📋 Descrição e 🛠️ Funcionalidades do Projeto

O Organo é uma aplicação para gerenciar colaboradores em times de trabalho. O usuário pode:

📂 Cadastro de Colaboradores
Permite cadastrar novos colaboradores, informando:
Nome
Cargo
Time de trabalho
🎨 Personalização de Times
Alterar a cor de fundo de cada time utilizando um seletor de cores.
⭐ Favoritar Colaboradores
Marcar colaboradores como favoritos, destacando-os visualmente na interface.
🗑️ Exclusão de Colaboradores
Excluir um colaborador da lista de forma rápida.
➕ Adicionar Novos Times
Cadastro de novos times através de um formulário dedicado.

##🖥️ Demonstração

Confira a aplicação em funcionamento: https://react-organo-2-flax.vercel.app/

##🚀 Tecnologias Utilizadas

React: Biblioteca JavaScript para construção de interfaces.
JavaScript (ES6+): Para lógica de programação.
CSS: Estilização personalizada dos componentes.
UUID: Para gerar identificadores únicos (usado para IDs).

##📚 O que eu aprendi

Durante o desenvolvimento do projeto Organo, foram trabalhados conceitos como:

1. Estrutura e Organização do Projeto
   Criação de componentes reutilizáveis: Aprendi como criar e estruturar componentes para tornar o código mais modular e reutilizável.
   Uso de props: Entendi como passar dados de um componente pai para seus filhos utilizando props.
2. Manipulação de Estados com Hooks
   useState:
   Controlar o estado de listas de colaboradores e times.
   Alterar o estado de elementos individuais, como favoritismo de colaboradores.
   Atualizar a cor dos times dinamicamente.
3. Funcionalidades Implementadas
   Renderização Condicional: Renderizar os times somente quando há colaboradores associados.
   Manipulação de eventos: Capturar eventos de formulário e inputs de cor para personalizar times.
   Criação de IDs únicos com UUID, garantindo que cada colaborador e time tenha um identificador exclusivo.
   Filtragem de listas: Filtrar colaboradores de acordo com o time selecionado.
