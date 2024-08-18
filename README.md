# Digital Greeting Clock

Este é um projeto simples de um relógio digital que exibe uma saudação com base na hora atual do dia. O relógio atualiza automaticamente a cada segundo e mostra mensagens diferentes para manhã, tarde e noite.

## 🛠️ Tecnologias Utilizadas

- React: Biblioteca JavaScript para criar interfaces de usuário.
- Tailwind CSS: Framework para estilização com classes utilitárias.
- JavaScript/TypeScript: Linguagem de programação utilizada no projeto.

# 🚀 Funcionalidades

- Exibe a hora atual em um formato de relógio digital.
- Atualiza a hora automaticamente a cada segundo.
- Exibe uma saudação dependendo do horário:

- "Good morning 😄" para manhã (0h - 12h).
- "Good afternoon 😎" para tarde (12h - 18h).
- "Goodnight 😴" para noite (18h - 23h).

# 📦 Como Executar o Projeto

- 1 - Clone este repositório:
`git clone https://github.com/daniel-olive/Greeting_React_TypeScript`

- 2 - Navegue até o diretório do projeto:
`cd Greeting_React_TypeScript`

- 3 - Instale as dependências:
`npm install`

- 4 - Inicie o servidor de desenvolvimento:
`npm run dev`

- 5 - Acesse o projeto em seu navegador:
`http://localhost:3000`

# 📚 Explicação do Código

- useEffect: Utilizado para configurar um intervalo que atualiza o estado hourCurrent a cada segundo, garantindo que a hora exibida esteja sempre atualizada.
- formatTwoDigits: Função que formata números de 0 a 9 para exibir dois dígitos (ex.: 03, 09).
- getHourss: Função que retorna a saudação apropriada com base na hora atual.

# 🎨 Layout

- A interface do projeto utiliza um gradiente de fundo e fontes personalizadas para exibir o relógio e a saudação de maneira visualmente atraente.

# 📄 Licença
- Este projeto está licenciado sob a [MIT License](LICENSE).
