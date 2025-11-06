## Vendo se a etapa passou do tempo
Pensei em duas opções:
1. Serviço que roda aproximadamente a cada minuto, e faz um poll da ultima etapa de todos os veiculos, marcando aqueles que passaram do prazo da etapa com um campo.
2. utilizando a tabela de eventos, descrita em `linha_do_tempo_e_etapas.md`, selecionar ultimo evento e mostrar delta(timestamp_evento,timestamp_tempo_atual), e se este delta foi maior que o prazo mostrar um icone ou algo.