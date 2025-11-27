link para a planilia: https://docs.google.com/spreadsheets/d/1NmfVQy066fiWdw_-Khsfzlr1xM7Ebt7qIKXG848ANK0/edit?usp=sharing

Bem-vindo à planilha de como fazer consultas usando Excel!

Para fazer uma consulta, você pode utilizar funções básicas como o famoso **PROCV**, além de outras funções importantes como **CONT.SE**, **MÉDIASE** e também recursos como **Validação de Dados**, que ajudam a manter a planilha organizada, precisa e fácil de analisar.

Abaixo está uma explicação clara de cada uma dessas ferramentas e como elas podem ser aplicadas na sua planilha.

---

## 🔍 PROCV - Procurando informações automaticamente

O **PROCV** é uma das funções mais utilizadas no Excel e serve para **buscar informações em formato vertical**, trazendo automaticamente dados relacionados a um valor específico.

Como funciona?
Você escolhe um valor para procurar, define onde o Excel precisa olhar e indica qual coluna deve ser retornada. 

Estrutura:
=PROCV(valor_procurado; tabela; número_da_coluna; FALSO)


## 🔢 CONT.SE – Contagens com critério

A função CONT.SE permite contar quantas vezes um determinado critério aparece dentro de um intervalo.

Estrutura:
=CONT.SE(intervalo; critério)


## 📊 3. MÉDIASE - Média Condicionada

A função MÉDIASE calcula a média somente dos valores que atendem a um critério específico.

Estrutura:
=MÉDIASE(intervalo_critério; critério; intervalo_média)

## ✔️Validação de Dados - Controle de Entradas na Planilha

A Validação de Dados não é uma função, mas uma ferramenta importantíssima para evitar erros digitados na tabela.

📌 Para que serve?

Ela permite definir regras para os valores permitidos, como:
Criar listas suspensas (dropdown)
Restringir apenas números
Limitar datas
Impedir textos inválidos

🎯 Exemplos de uso:

Criar uma lista de cidades válidas para evitar digitação incorreta
Garantir que a idade digitada seja um número entre 0 e 120
Impedir que a coluna “Status” receba valores fora de “Aprovado”, “Pendente” ou “Recusado”

🧭 Como aplicar:

Selecione as células desejadas
Vá em Dados → Validação de Dados
Escolha o tipo de regra (Lista, Número, Texto, etc.)
Defina o critério e confirme
