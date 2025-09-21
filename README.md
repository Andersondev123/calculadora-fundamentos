# Calculadora em React

Uma **calculadora interativa** construída em **React**, com histórico de operações e interface responsiva. Este projeto foi desenvolvido como parte do aprendizado intermediário de React, focando em **componentização, hooks e Context API**.

---

## Tecnologias utilizadas

- **React 18** – criação de componentes funcionais e hooks  
- **Context API** – gerenciamento de estado global para histórico de operações  
- **useState & useEffect** – controle de estado e efeitos colaterais  
- **TailwindCSS** – estilização e responsividade  
- **Babel Standalone** – transpiler para ES6+  

---

## Funcionalidades principais

- Operações matemáticas básicas (`+`, `-`, `*`, `/`)  
- Histórico de operações armazenado no **localStorage**  
- Interface responsiva para **desktop e mobile**  
- Botões estilizados com **gradientes, cores e sombreamento**  

---

## Estrutura do projeto

- `App` – componente principal que engloba a calculadora e o histórico  
- `Calculator` – componente da calculadora  
- `CalculatorDisplay` – mostra operação atual e resultado  
- `OperationHistory` – lista de operações realizadas  
- `CalculatorProvider` – Context API para gerenciar histórico global  
- `Button` e `Card` – componentes reutilizáveis para interface  

---

## Como usar

1. Clone o repositório:  
   ```bash
   git clone https://github.com/Andersondev123/calculadora-fundamentos.git
2. Abra o arquivo index.html no navegador.

3. Utilize a calculadora normalmente; o histórico de operações será salvo automaticamente.