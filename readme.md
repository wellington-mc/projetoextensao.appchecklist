# Controle de Preços - Checklist

Este projeto é um aplicativo web simples de controle de preços de produtos, desenvolvido para auxiliar no acompanhamento de alterações de preços em produtos. Ele foi criado com HTML, CSS e JavaScript para fins de demonstração e pode ser usado como parte de um trabalho de extensão. O objetivo principal deste aplicativo é permitir que os responsáveis pela alteração de preços em um estabelecimento possam registrar essas mudanças e acompanhar o que foi modificado.

## Objetivo

O aplicativo tem como objetivo fornecer uma maneira simples de controlar a alteração de preços de produtos, marcando quais itens tiveram os preços modificados. O app exibe uma lista de produtos com seus preços atuais, permitindo que o usuário edite esses preços e marque os itens que tiveram alterações. As modificações são salvas quando o usuário clica no botão **Salvar Alterações**.

## Funcionalidades

- Exibição de uma lista de produtos com seus preços atuais.
- Campos para alterar os preços dos produtos.
- Checkbox para marcar se o preço do produto foi alterado.
- Botão para salvar as alterações feitas, exibindo um alerta com o status de cada produto.
- O app é simples e não faz persistência de dados, ou seja, as alterações não são salvas após o recarregamento da página.

## Como Usar

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador da sua escolha.
3. Acesse a lista de produtos e altere os preços nos campos fornecidos.
4. Marque o checkbox ao lado de cada produto cujo preço foi alterado.
5. Clique no botão **Salvar Alterações** para exibir um alerta confirmando as alterações feitas.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página e exibição de conteúdo.
- **CSS**: Estilização da interface.
- **JavaScript**: Lógica de controle de preços e interação com o usuário.

## Expansão Futuras

Este aplicativo pode ser expandido para atender a necessidades mais complexas. Algumas possíveis melhorias incluem:

- **Persistência de Dados**: Adicionar funcionalidade para salvar as alterações de preços permanentemente, utilizando armazenamento local (LocalStorage) ou um banco de dados.
- **Interface Mais Completa**: Adicionar mais funcionalidades de gerenciamento de produtos, como excluir ou adicionar novos itens à lista.
- **Autenticação**: Implementar um sistema de login para permitir que apenas usuários autorizados possam alterar os preços.
- **Design Responsivo**: Melhorar a interface para que o aplicativo seja totalmente funcional em dispositivos móveis.

## Como Contribuir

Se você deseja melhorar ou expandir este projeto, fique à vontade para enviar **pull requests**. Estamos abertos a sugestões e melhorias para tornar este aplicativo mais útil.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
