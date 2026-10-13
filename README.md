# Simulador do Segundo Turno — Brasil 2026

Simulador independente de um cenário de segundo turno presidencial entre Lula e Flávio Bolsonaro. Permite ajustar a transferência dos votos dos demais candidatos e o comparecimento de eleitores que se abstiveram.

## Como usar

Abra o arquivo `index.html` em um navegador. O projeto usa HTML, CSS e JavaScript e não precisa de instalação ou compilação.

- O resultado inicial contém apenas os votos de base de Lula e Flávio Bolsonaro.
- Marque **Incluir votos na simulação** no candidato eliminado cujos votos deseja transferir. Seus votos do primeiro turno continuam visíveis.
- Ajuste a barra para dividir os votos habilitados entre os finalistas. Desmarcar o candidato retira seus votos do resultado e preserva a posição escolhida na barra.
- Escolha o percentual dos eleitores ausentes que passam a votar e distribua os votos adicionais.
- Consulte os totais, percentuais e a diferença entre os candidatos.
- O painel **Resultado simulado** permanece no topo durante a rolagem e fica compacto no celular, para acompanhar os números enquanto ajusta as barras.
- Use **Reiniciar** para restaurar os valores iniciais, desmarcar todas as transferências e zerar o comparecimento adicional.

O botão **Copiar resultado** depende da permissão de acesso à área de transferência do navegador e pode exigir que a página seja servida por HTTPS ou em um servidor local.

## Modelo da simulação

Os valores iniciais estão definidos em `index.html`. O cálculo mantém os votos de base dos dois finalistas, redistribui apenas os votos dos candidatos habilitados e acrescenta os votos decorrentes do comparecimento simulado. Os candidatos eliminados começam desmarcados. Os percentuais dos finalistas são calculados sobre os votos incluídos na simulação, e o resumo mostra também os votos ainda disponíveis para transferência.

O modelo não considera novas abstenções entre os eleitores dos finalistas, nem novos votos brancos ou nulos. O resultado representa um cenário hipotético; não é uma pesquisa eleitoral nem uma previsão.
