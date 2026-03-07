# ⚖️ Calculadora de IMC Profissional - JavaScript & Lógica de Dados

Uma aplicação interativa para cálculo de Índice de Massa Corporal (IMC) que utiliza uma base de dados interna para classificar o estado de saúde do usuário. O projeto foca em precisão de dados e uma interface de usuário intuitiva com feedbacks visuais coloridos.

## 🚀 Tecnologias Utilizadas
* **HTML5 Semântico:** Estrutura de formulários e tabelas dinâmicas.
* **CSS3 Avançado:** * **Layout Flexbox:** Centralização e alinhamento do painel de resultados.
    * **Sistema de Cores Dinâmico:** Classes específicas (`good`, `low`, `medium`, `high`) para indicar visualmente a gravidade do IMC.
    * **Clean UI:** Design escuro (Dark Mode) moderno com a fonte Google Lato.
* **JavaScript (ES6+):**
    * **Regex (Expressões Regulares):** Implementação de filtro em tempo real para permitir apenas números e vírgulas nos campos.
    * **Data Mapping:** Uso de um Array de Objetos para gerar a tabela de classificações dinamicamente.
    * **Lógica de Fluxo:** Funções para alternar entre a tela de cálculo e a tela de resultados sem recarregar a página.

## 🧠 Lógica e ADS Aplicada:
* **Sanitização de Dados:** Tratamento de strings (substituição de vírgula por ponto) para garantir cálculos matemáticos precisos no JavaScript.
* **Manipulação Ativa do DOM:** Criação dinâmica de elementos HTML (`createElement`) para preencher a tabela de referência.
* **UX/UI Design:** Limpeza automática de campos e suporte à tecla "Enter" para melhorar a experiência de uso.

## ⚙️ Como visualizar
1. Clone este repositório.
2. Abra o arquivo `index.html` no seu navegador.
3. Insira seu peso e altura para ver sua classificação de saúde.

---
Projeto desenvolvido para consolidar conceitos de manipulação de dados e lógica condicional no curso de ADS. 💻🔥
