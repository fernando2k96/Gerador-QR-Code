# Gerador de QR Code 📱

## Descrição do Projeto
Este é um projeto de um **Gerador de QR Code** construído utilizando HTML, CSS e JavaScript, que faz chamadas para uma API de geração de QR Codes. O objetivo é fornecer uma ferramenta simples e intuitiva para que usuários possam gerar QR Codes personalizados para qualquer link ou texto, diretamente pelo navegador.

A interface é amigável e permite que o usuário insira rapidamente a URL ou texto desejado, e receba um QR Code que pode ser baixado ou compartilhado.

## Funcionalidades
- **Geração de QR Code instantânea**: Basta inserir um link ou texto no campo designado e o QR Code será gerado automaticamente.
- **Suporte a vários formatos**: Pode-se inserir URLs, textos, números de telefone, etc.
- **Download do QR Code**: O QR Code gerado pode ser facilmente baixado no formato de imagem (PNG).
- **Interface responsiva**: O design do site é responsivo, adaptando-se a diferentes dispositivos, como celulares e tablets.
- **Customização do QR Code**: Possibilidade de definir tamanhos ou outros parâmetros (dependendo da API utilizada).

## Tecnologias Utilizadas
- **HTML5**: Estrutura do site e formulários de entrada.
- **CSS3**: Estilização da interface, proporcionando um design clean e responsivo.
- **JavaScript**: Lógica de interação do usuário, integração com a API e manipulação dinâmica da DOM.
- **API de QR Code**: A API é utilizada para gerar os QR Codes a partir dos dados inseridos pelo usuário.

## Como Funciona
1. O usuário insere um **link** ou **texto** no campo de entrada.
2. Ao pressionar o botão "Gerar QR Code", uma solicitação é enviada para a API, que retorna o QR Code.
3. O QR Code é exibido na página, com a opção de ser baixado em formato de imagem.

## Como Contribuir
1. Faça um fork deste repositório.
2. Crie um branch para sua feature ou correção: `git checkout -b minha-feature`.
3. Faça commit das suas mudanças: `git commit -m 'Adiciona nova feature'`.
4. Envie seu branch: `git push origin minha-feature`.
5. Abra um pull request.

## Licença
Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte o arquivo [LICENSE](LICENSE).