# Dataset para Precificação de Apartamentos à Venda em Porto Alegre (precificacao_ap_poa)
Um dataset com dados de apartamentos à venda em Porto Alegre para aplicação em técnicas de regressões

## Sobre o Dataset
O dataset é fruto de um trabalho prático na [disciplina de machine learning (CMP263)](https://www.inf.ufrgs.br/ppgc/disciplinas/lista-de-disciplinas/cmp263/) do Mestrado em Computação da UFRGS.

## Metodologia de coleta de dados
Os dados foram coletados no website [VivaReal](https://www.vivareal.com.br/).

## Localização e formato do dataset
O arquivo .csv do dataset se encontra no subdiretório dataset. O formato desse arquivo é constituído por colunas separadas por | (pipe) e com a codificação UTF-8.

## Descrição dos atributos numéricos
|    | atributo                |   count |           mean |           std |        min |         25% |         50% |         75% |          max |
|---:|:------------------------|--------:|---------------:|--------------:|-----------:|------------:|------------:|------------:|-------------:|
|  0 | preco                   |    4851 | 377514         | 204888        | 36460      | 219000      | 320000      | 500000      |    1.068e+06 |
|  1 | condominio              |    4851 |    412.528     |    181.166    |     1      |    285      |    373      |    511      |  960         |
|  2 | iptu                    |    4851 |    580.074     |    511.507    |     1      |    150      |    450      |    869      | 2334         |
|  3 | area                    |    4851 |     66.7229    |     21.4933   |    10      |     50      |     64      |     79      |  136         |
|  4 | quartos                 |    4851 |      2.14533   |      0.649273 |     1      |      2      |      2      |      3      |    4         |
|  5 | banheiros               |    4851 |      1.55308   |      0.70185  |     1      |      1      |      1      |      2      |    6         |
|  6 | suites                  |    4851 |      0.461142  |      0.526695 |     0      |      0      |      0      |      1      |    2         |
|  7 | vagas                   |    4851 |      0.960627  |      0.694229 |     0      |      0      |      1      |      1      |    3         |
|  8 | academia                |    4851 |      0.192538  |      0.394334 |     0      |      0      |      0      |      0      |    1         |
|  9 | aceita_animais          |    4851 |      0.272315  |      0.445197 |     0      |      0      |      0      |      1      |    1         |
| 10 | acesso_para_deficientes |    4851 |      0.0855494 |      0.279726 |     0      |      0      |      0      |      0      |    1         |
| 11 | ar_condicionado         |    4851 |      0.287776  |      0.452773 |     0      |      0      |      0      |      1      |    1         |
| 12 | area_de_servico         |    4851 |      0.253144  |      0.434857 |     0      |      0      |      0      |      1      |    1         |
| 13 | armario_embutido        |    4851 |      0.0907029 |      0.287216 |     0      |      0      |      0      |      0      |    1         |
| 14 | armario_na_cozinha      |    4851 |      0.0886415 |      0.284255 |     0      |      0      |      0      |      0      |    1         |
| 15 | bicicletario            |    4851 |      0.0723562 |      0.259104 |     0      |      0      |      0      |      0      |    1         |
| 16 | churrasqueira           |    4851 |      0.379716  |      0.485366 |     0      |      0      |      0      |      1      |    1         |
| 17 | circuito_de_seguranca   |    4851 |      0.0558648 |      0.229684 |     0      |      0      |      0      |      0      |    1         |
| 18 | cozinha_americana       |    4851 |      0.109462  |      0.31225  |     0      |      0      |      0      |      0      |    1         |
| 19 | elevador                |    4851 |      0.346114  |      0.475779 |     0      |      0      |      0      |      1      |    1         |
| 20 | espaco_gourmet          |    4851 |      0.153989  |      0.360975 |     0      |      0      |      0      |      0      |    1         |
| 21 | interfone               |    4851 |      0.190476  |      0.392717 |     0      |      0      |      0      |      0      |    1         |
| 22 | jardim                  |    4851 |      0.274376  |      0.446246 |     0      |      0      |      0      |      1      |    1         |
| 23 | lareira                 |    4851 |      0.0292723 |      0.168586 |     0      |      0      |      0      |      0      |    1         |
| 24 | mobiliado               |    4851 |      0.115646  |      0.319833 |     0      |      0      |      0      |      0      |    1         |
| 25 | perto_de_shopping       |    4851 |      0.0546279 |      0.227276 |     0      |      0      |      0      |      0      |    1         |
| 26 | piscina                 |    4851 |      0.185116  |      0.388432 |     0      |      0      |      0      |      0      |    1         |
| 27 | playground              |    4851 |      0.342197  |      0.474494 |     0      |      0      |      0      |      1      |    1         |
| 28 | portao_eletronico       |    4851 |      0.18388   |      0.387426 |     0      |      0      |      0      |      0      |    1         |
| 29 | portaria_24h            |    4851 |      0.131519  |      0.338002 |     0      |      0      |      0      |      0      |    1         |
| 30 | quadra_poliesportiva    |    4851 |      0.180169  |      0.384368 |     0      |      0      |      0      |      0      |    1         |
| 31 | salao_de_festas         |    4851 |      0.392909  |      0.488447 |     0      |      0      |      0      |      1      |    1         |
| 32 | salao_de_jogos          |    4851 |      0.0952381 |      0.293574 |     0      |      0      |      0      |      0      |    1         |
| 33 | seguranca_24h           |    4851 |      0.0981241 |      0.297513 |     0      |      0      |      0      |      0      |    1         |
| 34 | varanda                 |    4851 |      0.0999794 |      0.300003 |     0      |      0      |      0      |      0      |    1         |
| 35 | latitude                |    4851 |    -29.7862    |      2.50891  |   -31.286  |    -30.0807 |    -30.0397 |    -30.0154 |   -5.46843   |
| 36 | longitude               |    4851 |    -51.0835    |      0.729976 |   -52.0492 |    -51.2109 |    -51.1844 |    -51.1435 |  -44.2155    |
