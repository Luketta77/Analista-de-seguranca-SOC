# Investigação de Login Suspeito (Impossible Travel)

## Cenário

Um alerta foi gerado pelo sistema de monitoramento indicando um possível caso de "impossible travel", onde a mesma conta realizou login em dois países diferentes em um curto intervalo de tempo.

## Detalhes do alerta

Usuário afetado: usuario@empresa.com  
Primeiro login: Brasil  
Segundo login: Rússia  
Intervalo entre logins: 10 minutos  

## Etapas da investigação

1. Análise dos logs de autenticação no sistema de identidade.
2. Verificação dos endereços IP utilizados nos acessos.
3. Consulta da geolocalização dos IPs.
4. Validação com o usuário sobre possíveis viagens ou uso de VPN.

## Indicadores identificados

- IP estrangeiro desconhecido
- Login em localização incompatível com deslocamento físico
- Atividade fora do horário padrão do usuário

## Possível ameaça

- Comprometimento de credenciais
- Ataque de credential stuffing

## Ações realizadas

- Bloqueio temporário da conta
- Forçar redefinição de senha
- Ativação de autenticação multifator (MFA)
- Monitoramento adicional da conta
