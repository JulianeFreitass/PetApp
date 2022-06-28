# Pet App 


<h2>🎯Descrição</h2>

Aplicativo mobile para controle de gastos e medicamentos de pets.

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- **[React Native](https://reactnative.dev/)**
- **[Expo](https://docs.expo.dev/)**
- **[javascript](https://www.javascript.com/)**


## ⚙️ Funcionalidades

- [x] Listar, Adicionar e Remover um pet
- [x] Listar, Adicionar e Remover um pagamento do pet
- [x] Listar, Adicionar e Remover um medicamento do pet
- [x] Refatorar o codigo utilizando hooks e contexts
- [x] Converter projeto de Javascript para Typescript


## :pushpin: Contexts e Hooks

```              
├── Contexts:
│   ├── Auth
│   ├── Index
│   ├── Medicine
│   ├── Payments
│   └── Pet
├── Hooks:
│   ├── Index
│   ├── useAuth
│   └── useBackHandler
└── 
``` 
<h2>Contexts</h2>

- <b>Auth:</b>
Responsável por conter as propriedades e funções da tela de Login, tela de Criação do Uusário e a função de LogOut do aplicativo

- <b>Index:</b>
Responsável por hospedar e exportar os outros arquivos da pasta Contexts

- <b>Medicine:</b>
Contém os códigos funcionais das funções da página de listagem de medicamentos

- <b>Payments:</b>
Contém os códigos funcionais das funções da página de listagem de pagamentos

- <b>Pet:</b>
Contém os códigos funcionais das funções da página de listagem de pets


<h2>Hooks</h2>

- <b>Index:</b>
Responsável por hospedar e exportar os outros arquivos da pasta Hooks

- <b>useAuth:</b>
Responsável por retornar as propriedades do "value" do AuthContext.Provider

- <b>useBackHandler:</b>
Responsável por detectar o toque do usuário do aplicativo no botão voltar da aplicação




