# **Monitoramento de Motores Industriais**

É um software onde monitora os motores colocando as suas estatisticas, limitações e status 
ele apresenta tabelas dizendo a temperatura de certo motor e o status dele. Irei deixar tambem uma ordem utilizada para as estatisticas do motor e vou deixar um exemplo da tabela mas ela está resumida.

## Estatísticas Operacionais da Planta
1. _Total de Motores:_
2. _Temperatura Média:_
3. _Corrente Média:_
4. _Potência Total:_
5. _Motores Mais Quentes:_

### Exemplo de Tabela:

| Status | ID/Setor | Temperatura | Potência |
:--- | :---: | :---: | ---:
| Normal | MTR-01   | 68.4 C      | 7.5 kW   |
| Crítico| MTR-02   | 84.7 C      | 11.0 kW  |
| Atenção| MTR-03   | 76.2 C      | 5.5 kW   |

## **Plano de Manutenção Preventiva**

Onde sera apresentado quais motores e quantos precisam
de manutenção para ter noção e desenvolver uma solução o mais 
rapido possivel para o motor com problema para a produção não parar.

### Exemplo de Plano de Manutenção Preventiva

**🚨 Parada Imediata (CRÍTICO):**

_Motores com 2 ou mais parâmetros fora_
_do limite operacional:_ 
> [MTR-02] - Usinagem (3 ocorrências)

----------------------------------------

**⚠️ Inspeção Programada (ATENÇÃO):**

_Motores com 1 parâmetro fora_
_do limite operacional:_
>[MTR-03] - Bobinagem (1 ocorrência)

----------------------------------------

**🟢 Operação Estável (NORMAL):**

_Motores operando dentro de_ 
_todos os limites:_
>[MTR-01, MTR-04]




Desenvolved by: @gustavo-silveira09