# Android device tree para motorola cyprus64 (cyprus64)

Este repositório contém a base do device tree para o Motorola `cyprus64`, com foco em preparar um ambiente para compilar e testar uma build de recovery TWRP para este modelo.

## Objetivo do projeto

O meu objetivo aqui é criar uma tree funcional para o dispositivo, organizando os arquivos necessários para o Android e para o TWRP, além de ajustar as configurações de hardware e partições conforme o necessário para que o sistema possa inicializar corretamente.

Neste projeto estou tentando:

- adaptar o device tree para o modelo `cyprus64`;
- alinhar as definições de hardware e montagem do sistema;
- preparar a estrutura necessária para compilar um recovery TWRP;
- testar e corrigir erros de boot e compatibilidade;
- evoluir até chegar em uma primeira versão funcional.

## Status atual

Este projeto ainda está em desenvolvimento inicial. Eu estou montando a base do device tree e testando a compatibilidade dos arquivos necessários para que, no futuro, seja possível obter uma build funcional.

Essa etapa exige ajustes, testes e correções constantes, pois qualquer erro na configuração pode impedir o boot ou a compilação do recovery.

## Aviso importante

Atenção: até eu conseguir criar uma primeira versão que funcione de boot, pelo menos eu libero este projeto em estado de desenvolvimento experimental.

Ou seja, este repositório pode conter arquivos incompletos, ajustes parciais, configurações em teste ou builds ainda não estáveis. O objetivo é evoluir progressivamente até alcançar uma primeira versão funcional e confiável.

## Como estou trabalhando

A ideia é seguir um processo simples:

1. ajustar o device tree para o modelo correto;
2. validar as definições de partições e hardware;
3. compilar a recovery em ambiente adequado;
4. corrigir erros de boot e montagem;
5. liberar uma primeira versão funcional quando tudo estiver estável.

## Licença

```text
#
# Copyright (C) 2026 The Android Open Source Project
# Copyright (C) 2026 SebaUbuntu's TWRP device tree generator
#
# SPDX-License-Identifier: Apache-2.0
```

<footer>
    <p>© 2026 - Projeto em desenvolvimento para cyprus64</p>
</footer>
