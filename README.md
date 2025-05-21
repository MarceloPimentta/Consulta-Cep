# Consulta de CEP

Este é um projeto simples de uma aplicação web para consulta de CEP (Código de Endereçamento Postal) no Brasil. A aplicação permite que o usuário digite um CEP e obtenha informações detalhadas sobre o endereço correspondente, como logradouro, bairro, cidade e estado (UF).

## Funcionalidades

- Consulta de CEP utilizando a API pública [ViaCEP](https://viacep.com.br/).
- Exibição dos dados do endereço de forma clara e organizada.
- Interface responsiva, adaptando-se a diferentes tamanhos de tela.
- Mensagens de erro para CEPs inválidos ou não encontrados.

## Tecnologias Utilizadas

- HTML5
- CSS3 (com responsividade)
- JavaScript (fetch API para requisição HTTP)

## Como usar

1. Abra o arquivo `index.html` em seu navegador preferido.
2. Digite o CEP desejado no campo indicado (exemplo: 01001000).
3. Clique no botão "Buscar".
4. Os dados do endereço serão exibidos logo abaixo do botão.
5. Caso o CEP não seja encontrado, uma mensagem de alerta será exibida.

## Estrutura do Projeto

- `index.html`: arquivo principal contendo a estrutura da página e o script para consulta do CEP.
- `style.css`: arquivo de estilos para a página, incluindo responsividade.

## Considerações

Este projeto é uma ótima base para quem deseja aprender a consumir APIs públicas e manipular dados em JavaScript, além de praticar a criação de interfaces simples e responsivas.

## Licença

Este projeto está aberto para uso e modificação livre.

---
Desenvolvido para fins educacionais.
