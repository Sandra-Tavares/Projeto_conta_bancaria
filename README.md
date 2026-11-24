# Projeto Conta Bancária — Java

## Objetivo

Simulação educacional de operações bancárias com Java e interfaces de diálogo Swing (`JOptionPane`).

## Operações apresentadas no menu

- Conta corrente e poupança.
- Consulta de saldo/extrato, saque, depósito e transferência entre contas.
- Opções de empréstimo e investimento.

## Estrutura

- `src/Main.java`: entrada da aplicação e menus.
- `src/controle/`, `src/interfaces/`, `src/modelo/`: organização das classes e interfaces.
- `projetoBanco.iml`: configuração de módulo do IntelliJ IDEA.

## Como executar

Com um JDK instalado, abra o projeto em uma IDE Java, configure `src` como pasta de fontes e execute a classe `Main`.

## Pendências

O `case 1` do menu principal não possui `break` ao final, podendo avançar para o menu de poupança. Entradas não numéricas ou canceladas também merecem tratamento. A análise foi estática, sem execução ou validação das regras financeiras. Projeto educacional, não destinado a operações bancárias reais.
