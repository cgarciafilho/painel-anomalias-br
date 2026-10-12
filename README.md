# Mortalidade infantil por anomalias congênitas no Brasil — painel (versão preliminar)

Painel interativo com óbitos de menores de 1 ano por anomalia congênita (capítulo XVII da CID-10) e nascidos vivos com
anomalia registrada, por unidade da federação de residência, 2001–2025 (2025 preliminar). É a versão nacional, com escopo
menor, do [painel do Ceará](https://cgarciafilho.github.io/painel-anomalias-ce/): a UF é o menor território (não há
município, região de saúde nem estabelecimento). É uma página única (`index.html`): os dados estão embutidos nela, e os
filtros funcionam no navegador, sem servidor e sem internet depois de aberta. O arquivo tem cerca de 13 MB; a primeira
abertura pode levar alguns segundos.

## Aviso

Este painel é um projeto pessoal de pesquisa, em **versão preliminar e de teste**. Não é um produto oficial, não foi
revisado nem aprovado por nenhuma instituição e não representa a posição do Ministério da Saúde, de secretarias de saúde
ou de qualquer outra instituição a que o autor esteja vinculado.

**Pode conter erros, e é provável que contenha.** A concepção, o escopo, os passos, as fontes e as decisões de método são
de cgarciafilho; a extração, o código, os gráficos, os testes e o texto foram feitos com inteligência artificial. Esta
versão nacional ainda não foi lida aba a aba por uma pessoa nem avaliada por colegas; as conferências feitas até aqui são
automáticas e estão listadas na aba “Sobre esta versão”, que também diz quem fez o quê. Use com cautela e confira os
números na fonte oficial (TabNet do DATASUS) antes de citar ou de decidir algo com base neles. As limitações estão na
aba “Qualidade e métodos”.

## Fontes

- SIM: microdados públicos do DATASUS, arquivos de óbitos infantis do Brasil (`DOINF`), 2001–2025, conferidos no FTP em 26/09/2026.
- SINASC: microdados públicos do DATASUS, arquivos de nascidos vivos por UF (`DN<UF>`), 2001–2025, conferidos no FTP em 12/10/2026.
- Malha das unidades da federação: IBGE.

Não há identificação de pessoas. Os números podem mudar quando o DATASUS atualizar os arquivos, sobretudo os de 2025.

## Contato

Erros, dúvidas e sugestões: cgarciafilho@gmail.com

## Sobre este repositório

Aqui fica só a página publicada. Os scripts que baixam os dados, calculam as contagens e conferem o painel (com o TabNet
do DATASUS, por combinações de filtros contra as bases, e contra o painel do Ceará) ficam no projeto de origem, que não
está publicado.

## Licença

MIT (arquivo `LICENSE`), para a página e o código. Os dados de origem (SIM e SINASC do DATASUS, malha do IBGE) são
públicos e seguem os termos de cada fonte.
