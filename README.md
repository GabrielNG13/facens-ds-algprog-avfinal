# Aplicativo para Reservas de Quartos

Este repositório contém o projeto desenvolvido como atividade final da disciplina Algoritmos e Programação em Python do curso de pós-graduação em Ciência de Dados da Facens. Abaixo estão os requisitos e informações relevantes sobre o projeto:

## Descrição do Projeto
O objetivo do projeto é desenvolver um sistema de gerenciamento de hotéis, proporcionando uma plataforma para administrar informações sobre diversos estabelecimentos hoteleiros e suas respectivas reservas. 
Além de atender às necessidades mínimas do sistema de gestão hoteleira, o projeto visa demonstrar os conhecimentos adquiridos ao longo do curso da disciplina, abordando os seguintes conceitos:

* Estruturas de dados
* Laços de repetições
* Criação de funções
* Orientação a Objeto
* Manipulação de arquivos
* Utilização de bibliotecas

## Requisitos
O projeto foi desenvolvido seguindo a seguinte proposta:

* Possibilitar ao usuário o cadastro completo (inserção, edição, exclusão e consulta) de hotéis e quantidade de quartos a serem reservados.
* ⁠Considere que ao editar ou excluir um hotel - em especial na quantidade de quartos, a aplicação deverá apresentar antes os quartos que estavam reservados e serão cancelados por conta da edição da quantidade (ou seja, as reservas serão perdidas por conta do ajuste).
* Manter os dados armazenados e atualizados em algum tipo de arquivo.
* Apresentar um gráfico demonstrando a quantidade de quartos reservados e disponíveis de cada hotel cadastrado.

## Desenvolvimento
O código consiste em quatro classes principais para manipular hotéis e suas reservas, gerenciar uma lista de hotéis e fornecer uma interface de sistema para interação com essas classes.

1. **Classe Storage**:
   - Responsável por armazenar e recuperar dados em um arquivo JSON.
   - Encapsula a lógica para leitura e escrita de dados em arquivos.

2. **Classe Hotel**:
   - Representa um hotel com suas informações básicas, como CNPJ, nome, endereço, etc.
   - Gerencia o estado das reservas dos quartos do hotel.

3. **Classe Hotels**:
   - Manipula uma lista de objetos do tipo Hotel.
   - Responsável por operações como adição, atualização e exclusão de hotéis na lista.

4. **Classe System**:
   - Fornece uma interface de sistema para interagir com a lista de hotéis.
   - Gerencia a interação com o usuário, exibindo menus e recebendo entrada para operações no sistema.

## Instalação
Recomenda-se a utilização do ambiente Google Colabolatory para execução do projeto, onde basta carregar o arquivo e realizar sua execução.
Para demais ambientes, é necessário alterar os caminhos utilizado para input padrão de dados.

## Contato
Para mais informações sobre o projeto, entre em contato com Gabriel Nunes Ghirardelli através do e-mail gabrielnunesmghirardelli@gmail.com.
