# Avaliação de Bem-Estar Emocional

Este é um projeto desenvolvido em Angular que consiste em um quiz interativo voltado para a saúde mental. O objetivo é auxiliar os usuários a identificarem possíveis sinais de ansiedade ou depressão com base em suas respostas.

## Tecnologias Utilizadas
- **Angular**: Framework front-end para a construção da aplicação
- **TypeScript**: Linguagem utilizada para desenvolvimento
- **CSS**: Estilização da interface do quiz
- **JSON**: Armazenamento de perguntas e respostas do quiz

## Funcionalidades
- Exibição de perguntas dinâmicas baseadas em um arquivo JSON
- Registro de respostas do usuário
- Cálculo de resultados baseado nas respostas selecionadas
- Interface responsiva e amigável

## Estrutura do Projeto

```
/src
  /app
    /components
      - quizz.component.ts (Lógica do quiz)
      - quizz.component.html (Template do quiz)
      - quizz.component.css (Estilos do quiz)
  /assets
    - quizz_questions.json (Arquivo de perguntas e respostas)
```

## Instalação e Execução

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse o diretório do projeto:
   ```sh
   cd seu-repositorio
   ```
3. Instale as dependências do Angular:
   ```sh
   npm install
   ```
4. Execute a aplicação:
   ```sh
   ng serve
   ```
5. Acesse o navegador e abra:
   ```
   http://localhost:4200/
   ```

## Como Funciona?
1. O usuário inicia o quiz clicando em uma das opções de resposta.
2. O sistema registra as respostas e exibe a próxima pergunta.
3. Ao final, é exibido um diagnóstico inicial com base nas respostas.

## Contribuição
Se deseja contribuir com este projeto:
- Fork o repositório
- Crie uma branch com sua feature (`git checkout -b minha-feature`)
- Commit suas mudanças (`git commit -m 'Adicionando nova feature'`)
- Envie um pull request

## Licença
Este projeto é distribuído sob a Licença MIT. Para mais informações, consulte o arquivo `LICENSE`.

