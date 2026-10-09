# Lista de Compras (Mobile)

Aplicativo mobile simples, moderno e intuitivo para gerenciamento de listas de compras. Desenvolvido com React Native, Expo e TypeScript.

---

## Funcionalidades

- Adicionar Produtos: Cadastro rápido de novos itens com nome e quantidade.
- Remover Produtos: Exclusão individual de itens.
- Interface Intuitiva: Exibição com FlatList, suporte a estado vazio e validação de campos.
- Tipagem Estática: Código seguro e estruturado utilizando TypeScript.

---

## Tecnologias Utilizadas

- React Native (v0.86)
- Expo (SDK 57)
- TypeScript
- React (v19)

---

## Estrutura do Projeto

```text
lista-de-compras/
├── assets/                  # Ícones e imagens do aplicativo
├── components/              # Componentes reutilizáveis
│   ├── Cabecalho.tsx        # Cabeçalho da aplicação
│   ├── FormularioItem.tsx   # Formulário para adição de novos produtos
│   ├── ItemCompra.tsx       # Componente individual do item da lista
│   └── ListaCompras.tsx     # Exibição da lista dinâmica de compras
├── App.tsx                  # Componente principal e gerenciamento de estado
├── types.ts                 # Definição de interfaces e tipos TypeScript
├── app.json                 # Configurações do Expo
├── package.json             # Dependências e scripts do projeto
└── tsconfig.json            # Configurações do TypeScript
