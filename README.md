# Amigo Secreto 🎁

Este é um projeto simples de uma aplicação web para gerenciar um sorteio de **Amigo Secreto**. O usuário pode adicionar amigos, visualizar a lista de amigos e realizar o sorteio. O projeto foi desenvolvido utilizando **JavaScript**, **HTML**, e **CSS**.

## 📋 Funcionalidades

- Adicionar o nome dos amigos.
- Visualizar a lista de amigos.
- Sortear aleatoriamente os amigos e exibir quem tirou quem.
- Remover amigos da lista ao clicar no nome.
- Reiniciar o sorteio e a lista de amigos.

## 🛠️ Tecnologias Utilizadas

- **HTML**: para a estrutura da página.
- **CSS**: para o estilo da interface.
- **JavaScript**: para manipulação de eventos e a lógica do sorteio.

## 🚀 Como Usar

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/amigo-secreto.git
2. cd amigo-secreto 
3. Abra o arquivo index.html no navegador.
4. Digite os nomes dos amigos e clique em Adicionar para incluir cada um na lista.
5. Depois que ao menos 4 amigos forem adicionados, clique no botão Sortear para ver o resultado do sorteio.
6. Você pode clicar no nome de um amigo para removê-lo da lista ou clicar em Reiniciar para começar tudo de novo.

### Funcionalidades Técnicas
-Adicionar amigos: Ao clicar no botão "Adicionar", o nome do amigo é verificado. Se o campo estiver vazio ou se o amigo já estiver na lista, uma mensagem de alerta será exibida.
-Exclusão de amigos: Os nomes adicionados podem ser removidos clicando sobre eles na lista.
-Sorteio: O sorteio embaralha a lista de amigos e atribui a cada um um par diferente de forma aleatória.
-Reiniciar: Limpa a lista de amigos e os resultados do sorteio  

## Informações sobre como contribuir
Este projeto aceita qualquer contribuição útil que ajude a manter o código atualizado e a melhorar sua funcionalidade. Isso pode incluir correções de bugs, melhorias na documentação, novas funcionalidades ou otimizações de desempenho. Sinta-se à vontade para abrir um pull request com suas sugestões ou relatar problemas que você encontrar.

## Links para documentação
Para aprender mais sobre JavaScript e suas funcionalidades, consulte a [documentação oficial do JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript). Para informações sobre HTML, você pode visitar a [documentação oficial do HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML) e para aprender mais sobre CSS, consulte a [documentação oficial do CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS). Esses recursos abrangentes oferecem guias, tutoriais e referências detalhadas sobre as tecnologias, permitindo que desenvolvedores de todos os níveis aprimorem suas habilidades e conhecimentos.

## Comentários sobre o código
### HTML
A estrutura HTML é responsável pela criação da interface do usuário. Ela define os campos de entrada onde o usuário pode especificar a quantidade de números a serem sorteados, o intervalo mínimo e máximo, e o botão para iniciar o sorteio. Os elementos HTML, como `input` e `button`, permitem interações do usuário com a aplicação. A área de resultados exibe os números sorteados após a execução do sorteio.
### CSS
O CSS é utilizado para estilizar a aplicação, proporcionando uma melhor experiência visual ao usuário. Ele define a aparência dos elementos, como cores, fontes, tamanhos e espaçamentos, garantindo que a interface seja amigável e atraente. Os estilos são aplicados a classes específicas e IDs dos elementos HTML, permitindo que a aparência da aplicação seja ajustada facilmente sem alterar a estrutura do HTML.
### JavaScript
O JavaScript é a parte do código que traz interatividade à aplicação. Ele puxa informações do HTML por meio do uso de métodos como `document.getElementById()`, que permite acessar os valores inseridos pelo usuário nos campos de entrada. As funções JavaScript realizam a lógica do sorteio, gerando números aleatórios dentro do intervalo especificado, garantindo que os números sorteados não se repitam. Além disso, o JavaScript atualiza a interface do usuário com os resultados do sorteio e gerencia o estado dos botões (ativando ou desativando) com base nas ações do usuário.

### Agradecimentos
Agradecimento especial à Alura pelos excelentes cursos e materiais que contribuíram para o desenvolvimento deste projeto.






