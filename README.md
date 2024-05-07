# Verificar Status do Servidor Minecraft

Este é um projeto simples para verificar o status de um servidor Minecraft utilizando uma API externa. Ele consiste em uma página web onde você pode inserir o endereço do servidor Minecraft e verificar se está online ou offline, quantos jogadores estão conectados e a descrição do servidor.

![Logo](https://media.discordapp.net/attachments/1237168288685887572/1237202123465428992/image.png?ex=663ac9c4&is=66397844&hm=58834d4d44e26498adeb2dd1e2e2ee96cc3958d3a5c8728139a1c54d060fea1d&=&format=webp&quality=lossless&width=915&height=436)

## Tecnologias Utilizadas

- **HTML:** Utilizado para estruturar a página web.
- **CSS:** Utilizado para estilizar a página e criar animações.
- **JavaScript:** Utilizado para interagir com a API e exibir os resultados na página.

## Funcionamento da API

A API utilizada para verificar o status do servidor Minecraft é a [mcsrvstat.us](https://api.mcsrvstat.us/). Esta API fornece informações detalhadas sobre um servidor Minecraft, incluindo se está online ou offline, o número de jogadores conectados e a descrição do servidor.

Para utilizar a API, basta fazer uma requisição GET para o endpoint `https://api.mcsrvstat.us/3/{server_address}`, onde `{server_address}` é o endereço do servidor Minecraft que deseja verificar. A API retorna um objeto JSON com as informações solicitadas.

## Estrutura do Projeto

O projeto consiste em um arquivo HTML que contém a estrutura da página web, estilos CSS para a aparência da página e interações JavaScript para lidar com a interação do usuário e fazer requisições à API.

- **HTML:** A estrutura HTML inclui um formulário para inserir o endereço do servidor Minecraft e uma área para exibir o resultado da verificação.
- **CSS:** Os estilos CSS são utilizados para tornar a página visualmente atraente e responsiva, incluindo animações para a entrada suave dos elementos.
- **JavaScript:** O JavaScript é responsável por fazer a requisição à API, processar os dados recebidos e exibir o resultado na página. Ele também controla a abertura e fechamento das janelas de popup para exibir informações adicionais.

## Autor

Desenvolvido por [LkDeveloper](https://github.com/lucasdeveloperx).
