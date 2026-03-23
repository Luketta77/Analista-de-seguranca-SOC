# Threat Hunting – Detecção de Movimentação Lateral

## Cenário

Durante a análise de logs de autenticação foi identificado um comportamento incomum de acesso entre múltiplos servidores internos.

## Hipótese

Um possível atacante pode estar utilizando credenciais comprometidas para se movimentar lateralmente na rede.

## Estratégia de análise

Buscar eventos de autenticação remota entre hosts internos.

## Etapas da investigação

1. Análise de logs de autenticação em servidores.
2. Identificação de conexões remotas incomuns.
3. Verificação de acessos administrativos fora do padrão.
4. Correlação com outros eventos de segurança.

## Indicadores observados

- Acessos remotos entre múltiplos servidores
- Uso de conta administrativa fora do horário comercial
- Origem do acesso em estação de trabalho de usuário comum

## Técnicas relacionadas (MITRE ATT&CK)

T1021 – Remote Services  
T1078 – Valid Accounts  

## Possível impacto

Movimentação lateral pode indicar comprometimento da rede interna e tentativa de escalonamento de privilégios.

## Ações realizadas

- Suspensão da conta comprometida
- Análise completa do endpoint de origem
- Monitoramento intensivo da rede
