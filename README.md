# Teste aula de iOS

## Instruções

Você irá criar um app que utiliza de um endpoint do GitHub (https://api.github.com/users/{usuário}/repos) para listar os repositórios de um usuário.
A aplicação deverá conter:
- Tela inicial com:
  - Campo de texto para inserir nome de usuário a ser buscado
  - Botão de "Buscar" para efetuar a busca
- Tela de resultados com:
  - Foto de perfil do usuário
  - Nome do usuário 
  - Lista de repositórios contendo:
    - Nome do repositório
    - Linguagem do projeto
- Tratamento de erros, como por exemplo:
  - Usuário não encontrado
  - Nenhum repositório público para listar
  - Falhas de conexão
  - e outros
### Exemplo de implementação
| Home | Perfil |
|---|---|
|![home](https://github.com/BrenoAngelotti/iOS-class-test/assets/18258467/43672779-3670-4d33-8b03-753b52e676f7) | ![profile](https://github.com/BrenoAngelotti/iOS-class-test/assets/18258467/359c2ef6-be1b-43b0-9b05-130acecab306) |
 
## Dicas
- Use quaisquer bibliotecas necessárias, mas lembre-se que quanto menos, melhor
- Use UIKit ou SwiftUI, mas não se limite a tentar apenas um deles
- Não se apegue a pequenas melhorias. Faça funcionar e depois refine
- Deixe o app responsivo, funcionando em qualquer tamanho de tela, seja iPhone ou iPad

## Como entregar
Faça um `fork` desse repositório, implemente sua solução e abra um `Pull Request` (o famoso PR) de volta para esse repositório
