# Changelog

## 1.0.5

- Novo status **Interrompido**, acionado pelo plugin CRM quando a oportunidade volta para a negociação; o ciclo é liberado quando ela seguir para o Fechamento. Eventos "Ciclo interrompido" e "Ciclo liberado" na linha do tempo.
- Devolver o ciclo ao Aviso de Fechamento devolve a oportunidade para a Negociação no CRM e interrompe o ciclo; ao seguir de novo, o aviso se conclui sozinho e o ciclo volta à fase seguinte.
- `Fase::pause()` e `Fase::resume()` para integrações.

## 1.0.4 e anteriores

- Versão piloto: fases com área responsável, SLO e chamado por fase, itens da venda, devoluções como retrabalho e painel.
