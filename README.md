🎮 Dashboard de Aluguel de Jogos

Um projeto interativo que simula o controle de aluguel de jogos diretamente na interface.

💡 Ideia

Este projeto representa um pequeno sistema onde é possível:

Alugar um jogo
Devolver um jogo
Visualizar rapidamente quais itens estão disponíveis ou alugados

Tudo isso com atualização instantânea na tela.

⚙️ Como funciona

Cada jogo possui um botão que alterna entre dois estados:

Alugar → quando o jogo está disponível
Devolver → quando o jogo já foi alugado

Ao clicar:

A imagem do jogo muda de estado visual
O botão altera o texto
O estilo do botão é atualizado
🧠 Lógica por trás

A função principal controla tudo:

function alterarStatus(id)

Ela:

Identifica o item clicado
Busca elementos internos (imagem e botão)
Verifica o estado atual
Alterna classes CSS dinamicamente
🎯 O que esse projeto treina
Manipulação do DOM
Uso de querySelector
Alteração dinâmica de classes (classList)
Interação com eventos de clique
Controle de estado na interface
🖱️ Experiência

O foco aqui não é só funcionalidade, mas feedback visual:

Jogos alugados ficam visualmente diferentes
O botão muda de ação claramente
Tudo acontece sem reload da página
📂 Estrutura
index.html   → estrutura dos jogos  
style.css    → estilos e estados visuais  
app.js       → lógica de interação  
🚀 Como executar
Abra o projeto
Execute o arquivo:
index.html
Clique nos botões para interagir

🎯 Por que esse projeto é interessante?

Ele simula um comportamento comum em sistemas reais:

👉 controle de estado de itens (disponível vs alugado)

Esse tipo de lógica é base para aplicações maiores como:

e-commerces
sistemas de reservas
plataformas de streaming

👤 Autor
Mateus Cardoso

Desenvolvido como prática de JavaScript e DOM 🚀
