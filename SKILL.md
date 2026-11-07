---
name: spotify-camelot-clusters
description: Organizar playlists para Spotify Mix pelo método de Vitor — clusters Camelot com A/B juntos e percursos de BPM que ligam os grupos. Usar quando pedir este método, clusters harmónicos ou repetir esta organização. Não usar para uma simples ordenação por BPM ou para renderizar um DJ set.
---

# Playlists por clusters Camelot

Escrever em PT-PT. Organizar a playlist existente para audição com Spotify Mix. O pedido de organizar faixas não implica renderizar áudio nem configurar transições na aplicação.

## Critério confirmado

1. **Camelot primeiro:** juntar as faixas do mesmo número num cluster, incluindo A e B. São tonalidades relativas, com as mesmas notas, mas tónicas/modos diferentes; não são uma única tonalidade.
2. **Percorrer a roda por números consecutivos:** por exemplo, 9A/9B → 10A/10B → 11A/11B → 12A/12B → 1A/1B. Escolher o ponto de partida em função das ligações, salvo preferência do utilizador. O exemplo não obriga a começar em 9, nem a execução anterior obriga a começar em 12.
3. **BPM dentro e entre clusters:** construir uma sequência fluida em cada grupo e escolher a saída em conjunto com a entrada do seguinte. O BPM pode subir e descer; não exigir uma escada crescente, nem ordenar todos os grupos isoladamente antes de os concatenar.
4. Considerar metade/dobro do andamento ao comparar BPM: 60 e 120 podem ligar-se. A equivalência de andamento não altera o tom. Distinguir o BPM original do BPM equivalente usado no cálculo.

O agrupamento Camelot é a restrição principal. Dentro dessa restrição, equilibrar os saltos internos e as pontes entre clusters: uma ponte quase perfeita não compensa um salto interno evitável. Procurar alternativas de entradas, saídas e ordem interna em conjunto. Não fixar pesos, tolerâncias, largura de grupos de BPM ou ponto inicial como se fossem decisões de Vitor. A antiga ordenação por grupos de 2 BPM foi substituída por este método.

Não criar blocos por álbum, artista, época ou origem. Preservar todas as ocorrências e versões das faixas; deduplicação, adições e fusões só quando pedidas. Se faltarem números da roda, mostrar o salto entre os grupos existentes; não inventar faixas ou classificações para o preencher. A alternância A/B ao mudar de número nem sempre é uma ligação Camelot direta: favorecer a mesma letra na ponte quando isso também permitir boa ligação de BPM.

## Dados: usar a classificação que o utilizador vê

- Preferir **BPM e tom apresentados pelo próprio Spotify**, para a versão exata da faixa, quando disponíveis. Guardar a origem e a data de leitura, associando cada valor ao URI/versão.
- Inspecionar as capacidades reais da integração. Não assumir que metadados do catálogo incluem audio features, BPM ou tom: na sessão que originou este skill, a integração não os expunha.
- Se os valores só estiverem visíveis no Spotify aberto, usar acesso ao computador/navegador disponível. Capturas fornecidas pelo utilizador também servem. Confirmar título/artista/versão e cobertura das linhas; não extrapolar valores de linhas ocultas ou ilegíveis.
- Se não houver acesso visual, explicar a limitação concreta e pedir os dados/capturas necessários. Não alegar que se viu a janela nem tentar contornar a indisponibilidade com mecanismos não autorizados.
- As antigas análises de excertos desta playlist continham muitas tonalidades de baixa confiança e o utilizador identificou classificações erradas. **Não reutilizar essas estimativas como classificação Spotify nem aplicá-las silenciosamente.** Para uma experiência com dados incompletos, explicitar as lacunas e combinar com o utilizador o uso provisório de estimativas. Assinalar fonte, incerteza e divergências por faixa; não mudar a tonalidade atribuída só para melhorar a sequência.
- Valores do Spotify são a referência operacional pedida; não equivalem a uma prova musicológica de toda a gravação. Faixas com mudanças de andamento/tom podem exigir revisão auditiva.

## Preparação e aplicação

Usar as ferramentas e competências Spotify disponíveis para localizar, ler e editar a playlist. Ler todas as páginas e guardar uma cópia local da ordem inicial com URIs antes de escrever. Preparar uma proposta verificável contendo posição, faixa/versão, cluster, BPM original, BPM equivalente, Camelot, origem dos valores e incerteza.

Comparar alternativas de sequência com métricas de saltos internos e entre clusters. Mostrar os principais limites, sobretudo grupos pequenos sem faixas intermédias. Não apresentar uma heurística como ótimo global demonstrado, nem métricas como prova de audição. Não alterar a configuração Mix sem pedido.

Antes de aplicar, reler a playlist e detetar alterações concorrentes. Preferir uma operação de reordenação quando existir. Se só houver remoção/reinserção, explicar a alteração das datas de adição e respeitar a autorização existente para o método. A autorização de uma playlist não abrange outras playlists.

Preservar uma cópia recuperável da sequência e das multiplicidades. Verificar cada lote; respostas vazias não provam sucesso nem falha. Reler antes de repetir escritas para evitar duplicações. Se o estado observado divergir do esperado, parar o próximo lote e reconciliar os URIs efetivos com a cópia e a proposta, sem remover alterações novas do utilizador.

No fim, reler integralmente e confirmar ordem exata, número de faixas e multiplicidades. Só então declarar a organização aplicada. Guardar proposta, original, fontes e verificação; registar no cofre contextual quando as instruções do utilizador o exigirem. Não confundir aplicação verificada com transições ouvidas/testadas.
