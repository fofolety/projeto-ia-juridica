# Caso Fictício — Vício de Produto

## Repositório 
Url pública do repositório: https://github.com/fofolety/projeto-ia-juridica

## 1. Finalidade

Este repositório demonstra um fluxo de análise jurídica assistida por inteligência artificial, utilizando um caso jurídico inteiramente fictício.

O projeto apresenta as etapas de elaboração do relato, definição de limites de sigilo, sanitização das informações, seleção de fontes jurídicas, consulta baseada em fontes, verificação das respostas, auditoria, revisão humana e elaboração da orientação final.

## 2. Caso analisado

O caso envolve uma consumidora fictícia que adquiriu um notebook de uma empresa fictícia.

Após aproximadamente 20 dias de uso, o produto passou a apresentar desligamentos inesperados. O equipamento foi encaminhado para uma assistência técnica indicada pela fornecedora e permaneceu no local por 18 dias.

Após ser devolvido, o notebook voltou a apresentar o mesmo problema cinco dias depois. A consumidora solicitou a substituição do produto ou a restituição do valor pago, mas foi orientada pela empresa a encaminhar novamente o equipamento para avaliação.

A questão jurídica analisada consiste em identificar quais direitos podem ser exercidos pela consumidora diante do vício apresentado no produto.

## 3. Público

O projeto foi desenvolvido para fins acadêmicos e tem como público estudantes e interessados na utilização controlada de inteligência artificial em atividades de análise jurídica.

## 4. Organização do repositório

### `entrada/`

Contém o relato bruto do caso fictício, antes da sanitização das informações.

### `apoio/`

Contém a versão sanitizada do caso e as fontes jurídicas selecionadas para utilização pela IA.

### `docs/`

Contém os limites de sigilo e a especificação do funcionamento do projeto.

### `prompts/`

Contém os prompts utilizados para a consulta baseada nas fontes e para a auditoria da resposta produzida.

### `evidencias/`

Registra a resposta inicial, a verificação das afirmações, o resultado da auditoria e a revisão humana.

### `entrega/`

Contém a orientação inicial revisada após as etapas de verificação e auditoria.

## 5. Limites

O projeto utiliza exclusivamente informações fictícias e não contém dados reais de clientes, processos, documentos ou informações protegidas por sigilo.

Durante a consulta baseada em fontes, a IA deve utilizar exclusivamente os arquivos jurídicos previamente selecionados.

As respostas produzidas pela IA não devem ser consideradas automaticamente corretas e devem passar por verificação humana antes da entrega.

## 6. Critérios de aceitação

O projeto será considerado completo quando:

* o caso apresentado for integralmente fictício;
* houver relato bruto e versão sanitizada;
* os limites de sigilo estiverem documentados;
* houver fontes jurídicas previamente selecionadas;
* o prompt de consulta limitar a resposta às fontes autorizadas;
* houver registro da resposta inicial produzida pela IA;
* as afirmações relevantes forem verificadas;
* houver auditoria da resposta;
* houver decisão humana sobre os achados da auditoria;
* a orientação final apresentar suas fontes e limitações.

## 7. Fluxo do projeto

O fluxo desenvolvido neste repositório segue as seguintes etapas:

**Relato bruto → Sanitização → Seleção de fontes → Consulta RAG manual → Resposta inicial → Verificação → Auditoria → Revisão humana → Entrega**

## 8. Observação

O projeto possui finalidade exclusivamente acadêmica. O caso e os personagens utilizados foram criados para este exercício e não representam pessoas, empresas ou situações reais.
