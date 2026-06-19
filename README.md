# Registration Form 📝

Formulário de cadastro (Registration Form) desenvolvido em HTML, CSS, com layout centralizado em um card sobre fundo azul.

## 📋 Sobre o projeto

A página exibe um formulário de cadastro de usuário contendo os seguintes campos:

- **Full Name** — nome completo
- **Email address** — endereço de e-mail
- **Phone Number** — número de telefone
- **Birth Date** — data de nascimento (formato `dd/mm/aaaa`, com seletor de calendário)
- **Gender** — seleção via radio button: `Male`, `Female`, `Prefer not to say`
- **Address** — endereço, dividido em:
  - Linha de endereço (rua)
  - Linha de endereço complementar
  - País (seleção)
  - Cidade

O formulário é apresentado em um card branco centralizado, com cabeçalho em destaque (fundo azul/roxo) contendo um ícone circular e o título "Registration Form".

## 🚀 Tecnologias utilizadas

- **HTML5** — estrutura do formulário (`<form>`, `<input>`, `<select>`, `<input type="radio">`, `<input type="date">`)
- **CSS3** — estilização do card, cabeçalho, campos de entrada e responsividade

## 📁 Estrutura do projeto

```
.
├── index.html      # Página principal com o formulário
├── style.css       # Estilos do card, inputs e layout
```

> Ajuste esta estrutura conforme os arquivos reais do seu projeto.

## ▶️ Como executar

Este projeto é estático (HTML/CSS/JS), sem necessidade de instalação de dependências.

### Opção 1: Live Server (VS Code)
1. Abra a pasta do projeto no VS Code.
2. Instale a extensão **Live Server**.
3. Clique com o botão direito em `index.html` → **Open with Live Server**.
4. O navegador abrirá automaticamente em algo como:
   ```
   http://127.0.0.1:5500/index.html
   ```

### Opção 2: Abrir diretamente
Basta abrir o arquivo `index.html` direto no navegador (duplo clique).

## ✅ Funcionalidades

- [x] Campos de texto para nome, e-mail e telefone
- [x] Seletor de data de nascimento
- [x] Seleção de gênero via radio button
- [x] Campos de endereço (rua, complemento, país, cidade)
- [ ] Validação de campos obrigatórios *(adicionar se implementado)*
- [ ] Envio dos dados para um servidor/back-end *(adicionar se implementado)*

## 🎨 Customização

Você pode ajustar facilmente:
- **Cores do cabeçalho e botões** — alterando as variáveis de cor no CSS;
- **Campos do formulário** — adicionando ou removendo `<input>`/`<select>` conforme a necessidade;
- **Validações** — incluindo regras de obrigatoriedade, formato de e-mail, máscara de telefone, etc., via JavaScript.

## 📸 Demonstração

Formulário de cadastro com cabeçalho azul/roxo, campos para dados pessoais e de endereço, exibido em card centralizado sobre fundo azul.

## 📄 Licença

Este projeto é livre para uso e modificação.

---

> 💡 **Nota:** este README foi gerado a partir de uma captura de tela do projeto em execução. Para um README mais preciso (com nomes reais de arquivos, dependências exatas e instruções específicas), envie os arquivos do projeto.
