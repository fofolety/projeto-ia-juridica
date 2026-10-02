# Especificação do Projeto

## Finalidade

Analisar um caso jurídico fictício de relação de consumo envolvendo possível vício de produto, utilizando exclusivamente as fontes selecionadas no diretório `apoio/`.

## Público

O projeto foi desenvolvido para fins acadêmicos, destinado à demonstração de um fluxo de análise jurídica assistida por inteligência artificial.

## Entrada

A IA deverá receber o caso sanitizado e as fontes jurídicas previamente selecionadas.

## Saída esperada

A resposta deverá:

1. identificar os principais fatos juridicamente relevantes;
2. indicar os dispositivos aplicáveis;
3. explicar os possíveis direitos da consumidora;
4. indicar as fontes utilizadas;
5. informar o arquivo e o trecho utilizado como fundamento;
6. apontar eventuais limitações ou informações que não estejam disponíveis.

## Restrições

A IA não deverá:

* utilizar fontes externas às fontes autorizadas;
* inventar dispositivos legais;
* inventar fatos não presentes no caso;
* apresentar informações como certas quando não estiverem apoiadas pelas fontes;
* substituir a revisão humana.

## Critérios de aceitação

A resposta será considerada adequada quando:

* estiver baseada exclusivamente nas fontes autorizadas;
* houver correspondência entre as afirmações jurídicas e os trechos das fontes;
* não forem adicionados fatos inexistentes;
* forem identificadas eventuais incertezas;
* houver indicação clara das fontes utilizadas.
