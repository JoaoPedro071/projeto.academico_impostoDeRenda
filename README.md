#  Calculadora de Imposto de Renda

Este projeto é uma aplicação simples em **Java** que calcula o valor do imposto de renda a ser pago com base no salário mensal informado pelo usuário.  
O objetivo é demonstrar lógica condicional, entrada de dados via console e cálculos básicos em Java.

---

##  Funcionalidades
- Solicita ao usuário o valor do salário mensal.
- Determina automaticamente a faixa de tributação.
- Calcula o valor do imposto de acordo com a alíquota.
- Exibe a alíquota aplicada e o valor do imposto.
- Informa se o usuário está **isento**.

---

##  Regras de Tributação

| Faixa Salarial (R$)        | Alíquota (%) | Situação       |
|-----------------------------|--------------|----------------|
| Até 5.000,00                | 0%           | Isento         |
| 5.000,01 – 6.500,00         | 7,5%         | Tributado      |
| 6.500,01 – 8.000,00         | 15%          | Tributado      |
| 8.000,01 – 10.000,00        | 22,5%        | Tributado      |
| Acima de 10.000,00          | 27,5%        | Tributado      |

---

##  Como Executar

1. Certifique-se de ter o **Java JDK** instalado.
2. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
   ```
3. Compile o código:
   ```bash
   javac Main.java
   ```
4. Execute o programa:
   ```bash
   java Main
   ```
5. Insira o valor do salário mensal quando solicitado.

---

##  Exemplo de Uso

**Entrada:**
```
Insira seu salário mensal:
7000
```

**Saída:**
```
Imposto sobre a renda: 15%.
Valor de imposto a ser pago: 1050.0
```

---

##  Tecnologias Utilizadas
- **Java** (linguagem principal)
- **Scanner** (entrada de dados via console)

---

##  Observações Importantes
- Este projeto é **didático** e não reflete a legislação oficial do Imposto de Renda no Brasil.
- As faixas e alíquotas foram definidas apenas para fins de prática de programação.

---

##  Possíveis Melhorias Futuras
- Implementar cálculo **progressivo** de imposto (como na legislação real).
- Adicionar **validação de entrada** para evitar valores inválidos.
- Criar uma interface gráfica simples (Swing/JavaFX).
- Exportar relatórios em **PDF** ou **CSV**.

---

##  Autor
- João  
- 📅 Maio/2026  
- 🌍 Recife, Pernambuco - Brasil
```
