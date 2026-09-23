# 💸 Refund

> Aplicação web para solicitação, controle e cálculo dinâmico de reembolso de despesas corporativas.

---

## 📌 Sobre o Projeto

O **Refund** é uma solução de interface moderna e intuitiva voltada para o gerenciamento de despesas e pedidos de reembolso corporativo. A aplicação permite que o usuário registre despesas por categorias específicas (como alimentação, hospedagem, transporte e serviços), aplique valores monetários formatados e acompanhe o somatório total das despesas em tempo real.

O projeto foi construído com foco em **JavaScript Vanilla**, manipulação eficiente da DOM, boas práticas de semântica com **HTML5** e estilização responsiva com **CSS3**.

---

## 🚀 Tecnologias e Recursos

- **HTML5:** Estruturação semântica e acessível da página.
- **CSS3:** Estilização moderna, layout responsivo e transições fluidas.
- **JavaScript (Vanilla / ES6+):** Lógica de formulário, formatação de moedas (BRL), manipulação dinâmica da lista de itens e cálculos de totais.
- **SVG Icons:** Ícones vetoriais otimizados para cada categoria de despesa.

---

## ✨ Funcionalidades

- [x] **Cadastro de Despesas:** Inserção do nome da despesa, categoria e valor.
- [x] **Classificação por Categorias:** Suporte a ícones e filtros para:
  - 🏨 Hospedagem (`accommodation.svg`)
  - 🍽️ Alimentação (`food.svg`)
  - 🚗 Transporte (`transport.svg`)
  - 🛠️ Serviços (`services.svg`)
  - 📦 Outros (`others.svg`)
- [x] **Formatação de Moeda:** Máscara de valor e formatação automática em Real Brasileiro (R$ / BRL).
- [x] **Cálculo Automático:** Atualização do valor total e quantidade de itens na lista conforme adições e remoções.
- [x] **Exclusão de Despesas:** Botão individual para remoção dinâmica de cada item registrado (`remove.svg`).

---

## 📁 Estrutura de Arquivos

```
refund-page/
├── img/
│   ├── accommodation.svg   # Ícone de hospedagem
│   ├── chevron-down.svg    # Ícone do seletor dropdown
│   ├── food.svg            # Ícone de alimentação
│   ├── logo.svg            # Logo da aplicação
│   ├── others.svg          # Ícone para despesas gerais/outros
│   ├── remove.svg          # Ícone de exclusão de item
│   ├── services.svg        # Ícone de serviços prestados
│   └── transport.svg       # Ícone de transporte/combustível
├── index.html              # Estrutura e marcação da aplicação
├── styles.css              # Estilos visuais e regras de responsividade
├── script.js               # Lógica de negócio, validações e eventos
└── README.md               # Documentação do projeto
```

---

## 🛠️ Como Executar o Projeto

Como o projeto foi desenvolvido com tecnologias web nativas, não há necessidade de gerenciadores de pacotes ou comandos de build.

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/refund-page.git
cd refund-page
```

### 2. Executar no navegador

Você pode abrir o projeto de duas maneiras simples:

#### Opção A: Abertura direta
Dê um duplo clique no arquivo `index.html` ou arraste-o para dentro do seu navegador padrão.

#### Opção B: Servidor local (Recomendado)
Se você utiliza o **VS Code**, utilize a extensão **Live Server**:
1. Clique com o botão direito no arquivo `index.html`.
2. Selecione **"Open with Live Server"**.
3. A página abrirá automaticamente em `http://127.0.0.1:5500`.

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

Feito com ☕ e código limpo.
