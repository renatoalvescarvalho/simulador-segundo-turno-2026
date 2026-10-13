# Simulador do Segundo Turno — Brasil 2026

Simulador independente de um cenário de segundo turno presidencial entre Lula e Flávio Bolsonaro. Permite ajustar a transferência dos votos dos demais candidatos e o comparecimento de eleitores que se abstiveram.

## Como usar

Abra o arquivo `index.html` em um navegador. O projeto usa HTML, CSS e JavaScript e não precisa de instalação ou compilação.

- Ajuste os controles de transferência de votos.
- Escolha o percentual dos eleitores ausentes que passam a votar e distribua os votos adicionais.
- Consulte os totais, percentuais e a diferença entre os candidatos.
- Use **Reiniciar** para restaurar os valores iniciais.

O botão **Copiar resultado** depende da permissão de acesso à área de transferência do navegador e pode exigir que a página seja servida por HTTPS ou em um servidor local.

## Modelo da simulação

Os valores iniciais estão definidos em `index.html`. O cálculo mantém os votos de base dos dois finalistas, redistribui integralmente os demais votos válidos e acrescenta os votos decorrentes do comparecimento simulado.

O modelo não considera novas abstenções entre os eleitores dos finalistas, nem novos votos brancos ou nulos. O resultado representa um cenário hipotético; não é uma pesquisa eleitoral nem uma previsão.
