# Organizador de Salas

**[Acessar o Organizador de Salas](https://rubenbruno89.github.io/organizador-de-sala/)**

Ferramenta para consultar quais salas de um centro universitário estão livres ou ocupadas em determinado horário. A consulta combina a lista de salas informada com os horários de ocupação de até duas planilhas.

## Como usar

1. Informe a lista completa de salas, de preferência uma por linha.
2. Selecione até dois arquivos de ocupação (`.xlsx`, `.xls` ou `.csv`).
3. Em cada arquivo, escolha a aba e confirme se as colunas de sala, dia ou data, início e fim foram identificadas corretamente.
4. Selecione o dia da semana ou informe uma data específica. Depois, indique o horário inicial e final.
5. Confira as listas de salas livres e ocupadas. Você também pode consultar o mapa visual do dia ou usar o botão **Copiar lista** para copiar as salas livres.

Uma sala é considerada ocupada se qualquer parte de uma aula ou reserva coincidir com o intervalo consultado. Por exemplo, uma aula das 19:00 às 20:40 ocupa a sala em uma consulta das 20:00 às 21:00.

## Modelo de planilha

Use uma linha para cada aula ou reserva:

| Sala | Dia | Início | Fim | Disciplina/Turma (opcional) |
| --- | --- | --- | --- | --- |
| Sala 101 | Segunda | 19:00 | 22:30 | Direito Civil — 3º A |
| Sala 102 | Terça | 08:00 | 12:00 | Anatomia — 1º B |
| Lab. Informática 1 | Sexta | 14:00 | 17:30 | Algoritmos — 2º C |

- Para uma reserva pontual, use uma coluna **Data**, no formato `DD/MM/AAAA`.
- Se os dois horários estiverem em uma única coluna, como `19:00 - 22:30`, selecione essa coluna no campo **Início** e deixe **Fim** como **nenhuma**.
- O botão **Baixar modelo** no site gera uma planilha Excel de exemplo.

## Dados e disponibilidade

As planilhas são lidas no próprio navegador. A lista de salas fica salva nele, mas os arquivos precisam ser selecionados novamente ao recarregar a página.

O sistema **consulta a disponibilidade, mas não efetua reservas**. Antes de confirmar uma sala, verifique se as planilhas estão atualizadas e se há avisos de linhas ignoradas ou salas não reconhecidas.
