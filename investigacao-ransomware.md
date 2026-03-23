# Investigação de Incidente de Ransomware

## Cenário

Um alerta crítico foi gerado pela ferramenta de EDR indicando possível atividade de ransomware em um servidor de arquivos.

## Detalhes do alerta

Tipo de alerta: Detecção de comportamento de ransomware  
Host afetado: FILE-SERVER01  
Fonte da detecção: EDR  

## Etapas da investigação

1. Verificação do processo suspeito executado no servidor.
2. Identificação de um executável desconhecido realizando múltiplas alterações em arquivos.
3. Análise de logs de acesso a arquivos e atividades do sistema.
4. Verificação de possíveis conexões SMB indicando movimentação lateral.

## Técnicas relacionadas (MITRE ATT&CK)

T1486 – Data Encrypted for Impact  
T1021 – Remote Services  

## Ações de resposta

- Isolamento do servidor afetado da rede
- Bloqueio do hash do arquivo malicioso
- Comunicação com equipe de segurança
- Preservação de logs para análise forense
