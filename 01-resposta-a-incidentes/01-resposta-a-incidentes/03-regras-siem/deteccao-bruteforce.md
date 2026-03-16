# Detecção de Ataque de Brute Force

## Objetivo

Detectar múltiplas tentativas de login falhas a partir de um mesmo endereço IP em um curto intervalo de tempo.

## Lógica de detecção

Se um mesmo IP gerar mais de 10 tentativas de login falhas em um período de 5 minutos, gerar alerta de possível ataque de força bruta.

## Possível ameaça

Ataque de brute force ou password spraying.

## Referência MITRE ATT&CK

T1110 – Brute Force
