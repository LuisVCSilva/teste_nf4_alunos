# Relatório da equipe
Integrantes e contribuições: Vitor, Artur, Jefferson
Commit demonstrado:
Versões e data de execução:


#Respostas



## Evidências
| Experimento | Comando | Resultado esperado | Resultado observado | Explicação |
|---|---|---|---|---|
| Acesso a pedido de outro cliente | | 403 | | |
| Cabeçalho de perfil forjado | | 401/403 | | |
| Mesma chave e mesmo conteúdo | | mesmo pid | | |
| Mesma chave e outro conteúdo | | 409 | | |
| Timeout após cobrança | | uma cobrança | | |
| Restauração | | conteúdo validado | | |
| p95 | | medir sem inventar | | |

## Dados e correção cadastral
Inventário: campo, finalidade, classificação, acesso, retenção proposta, descarte.
Fluxo de verificação da identidade, correção e auditoria sem copiar dado pessoal ao log.

## Arquitetura proposta
Camadas, TLS, limites de confiança, gateway, API, banco, outbox, broker, worker e faturamento.
Como repetir publicação após crash? Como confirmar mensagem depois do efeito persistido?
O que ocorre quando a mesma mensagem chega duas vezes?

## Continuidade
Metas: RTO 2h; RPO 15min. Medidas observadas, lacunas e plano.
Tempo de restore SQL, validação, troca de configuração e retorno ao serviço.

## Qualidade e tecnologia
Algoritmo: tempo e espaço; contrato; teste com implementação falsa.
IA: métricas por grupo, limitações e revisão humana.
IoT: qualidade, duplicação, atrasos e escala.

## Limitações e melhorias
Distinguir implementado, observado, hipótese e proposta. Sem tokens nos anexos.
