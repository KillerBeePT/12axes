# Integração das 12 personalidades portuguesas

Data: 01/11/2026. Branch local: `feat/portuguese-personalities`.

Os 12 perfis foram integrados nos metadados PT/EN, vetores, imagens e arquivo permanente de respostas. São simulações interpretativas baseadas nas fontes; as pessoas não responderam ao questionário. Não se atribui uma percentagem de certeza factual às 240 respostas.

## Exceção de semelhança

Em 01/11/2026, o utilizador autorizou explicitamente integrar os bloqueios exclusivamente de semelhança ≥97%, preservando as respostas fundamentadas. O validador e os seus limiares não foram alterados. Os resultados originais, incluindo os códigos de falha, permanecem nos ficheiros `*-validation.txt`. Esta autorização local não vincula o mantenedor do projeto.

| Perfil | Respostas + arquétipos | Validação | Bloqueios de semelhança |
|---|---|---|---|
| André Ventura | 240 + 5 | Exceção de semelhança autorizada | 98.6%  john-a-macdonald; 98.0%  sardar-vallabhbhai-patel |
| António Costa | 240 + 5 | Exceção de semelhança autorizada | 97.3%  olaf-scholz |
| Inês de Sousa Real | 240 + 5 | Passa | — |
| João Cotrim de Figueiredo | 240 + 5 | Exceção de semelhança autorizada | 97.5%  mariana-leitao |
| Jorge Pinto | 240 + 5 | Exceção de semelhança autorizada | 97.8%  guilherme-boulos; 97.7%  zohran-mamdani; 97.6%  mark-fisher |
| José Luís Carneiro | 240 + 5 | Exceção de semelhança autorizada | 98.2%  andy-burnham |
| José Manuel Pureza | 240 + 5 | Passa | — |
| Luís Montenegro | 240 + 5 | Passa | — |
| Mariana Leitão | 240 + 5 | Exceção de semelhança autorizada | 97.5%  joao-cotrim-figueiredo |
| Mariana Mortágua | 240 + 5 | Exceção de semelhança autorizada | 98.3%  hasan-piker; 97.5%  mark-fisher; 97.2%  jorge-pinto |
| Nuno Melo | 240 + 5 | Passa | — |
| Paulo Raimundo | 240 + 5 | Exceção de semelhança autorizada | 98.2%  allende; 97.2%  bernie-sanders |

## Implementação e limites

- 2 880 respostas, 60 escolhas de arquétipo e 12 vetores calculados por `profile_vector.compute_vector`.
- Retratos reais Wikimedia, com fonte, autor e licença/reutilização registados, comprimidos com o otimizador do projeto e inspecionados visualmente.
- Livros adicionados apenas quando autoria e pertinência foram verificadas; URLs de afiliado vazios.
- Histórico anterior de respostas preservado; temporários deste lote removidos após comparação com o arquivo permanente.
- `STATE.json`: 12 novos itens em `done` e +12 no total; a diferença preexistente entre o contador e o catálogo foi preservada.
- O retrato de António Costa tem discussão de eliminação no Commons; a proveniência e a condição de reutilização UE estão no relatório individual. Deve ser revisto se a decisão alterar a disponibilidade ou a licença.
- Nenhuma publicação remota, issue ou pull request foi efetuada nesta etapa.

## André Ventura

ID: `andre-ventura`. Religiões: `['catholic']`. Livro: Nenhuma obra elegível confirmada; não foi adicionado livro..

Arquétipos: `{"sociedade": "A", "poder": "C", "economia": "E", "mundo": "B", "tecnologia": "D"}`.

Vetor calculado: `{"estrutura": 18.8, "representacao": 66.8, "poder": 65.1, "imigracao": 87.2, "diplomacia": 60.0, "intervencao": 37.6, "economia": 35.1, "controle": 42.1, "comercio": 64.5, "religiao": 37.9, "moral": 14.9, "tecnologia": 60.6}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- FILTRO DE RELIGIAO: catholic (usuario que escolheu catholic) ---

=== TOP 2 PERSONALIDADES ===
95.7%  Éric Zemmour (eric-zemmour)
94.6%  Henry Clay Frick (henry-clay-frick)

=== TOP 2 IDEOLOGIAS ===
96.0%  Conservadorismo Nacional (conservadorismo-nacional)
95.3%  Nacionalismo de Direita (nacionalismo-de-direita)

=== TOP 2 PAISES ===
93.9%  Polônia (polonia)
92.6%  Roma Republicana (roma-republicana)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
97.3%  Rozwój Plus (rozwoj-plus)
96.1%  Irmãos da Itália (Fratelli d'Italia) (fratelli-ditalia)
```

## António Costa

ID: `antonio-costa`. Religiões: `[]`. Livro: Caminho Aberto (2012).

Arquétipos: `{"sociedade": "D", "poder": "C", "economia": "C", "mundo": "B", "tecnologia": "D"}`.

Vetor calculado: `{"estrutura": 46.2, "representacao": 89.4, "poder": 43.7, "imigracao": 30.7, "diplomacia": 36.2, "intervencao": 42.4, "economia": 58.0, "controle": 58.0, "comercio": 23.4, "religiao": 69.0, "moral": 68.1, "tecnologia": 55.8}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- SEM FILTRO DE RELIGIAO ---

=== TOP 2 PERSONALIDADES ===
97.3%  Olaf Scholz (olaf-scholz)
96.9%  Barack Obama (barack-obama)

=== TOP 2 IDEOLOGIAS ===
96.5%  Liberalismo de Estado (liberalismo-de-estado)
96.3%  Liberalismo Pragmático (liberalismo-pragmatico)

=== TOP 2 PAISES ===
96.5%  Illinois (Estados Unidos) (eua-illinois)
96.4%  Espanha (espanha)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
98.6%  Partido Social-Democrata da Alemanha (SPD) (spd)
97.4%  Partido Democrático (PD) (partido-democratico-italia)
```

## Inês de Sousa Real

ID: `ines-sousa-real`. Religiões: `[]`. Livro: Nenhuma obra elegível confirmada; não foi adicionado livro..

Arquétipos: `{"sociedade": "D", "poder": "C", "economia": "C", "mundo": "C", "tecnologia": "B"}`.

Vetor calculado: `{"estrutura": 45.0, "representacao": 91.8, "poder": 38.9, "imigracao": 24.8, "diplomacia": 19.3, "intervencao": 53.0, "economia": 55.6, "controle": 59.2, "comercio": 52.0, "religiao": 76.2, "moral": 82.4, "tecnologia": 24.0}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- SEM FILTRO DE RELIGIAO ---

=== TOP 2 PERSONALIDADES ===
96.0%  Carlos Drummond de Andrade (carlos-drummond-de-andrade)
95.5%  Yamandú Orsi (yamandu-orsi)

=== TOP 2 IDEOLOGIAS ===
96.3%  Progressismo (progressismo)
96.1%  Social-Democracia (social-democracia)

=== TOP 2 PAISES ===
95.0%  País de Gales (Reino Unido) (pais-de-gales)
94.8%  Islândia (islandia)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
96.7%  Aliança 90/Os Verdes (verdes-alemanha)
95.4%  Sumar (sumar)
```

## João Cotrim de Figueiredo

ID: `joao-cotrim-figueiredo`. Religiões: `[]`. Livro: Porque Sou Liberal (2025).

Arquétipos: `{"sociedade": "C", "poder": "C", "economia": "F", "mundo": "B", "tecnologia": "D"}`.

Vetor calculado: `{"estrutura": 67.6, "representacao": 91.8, "poder": 19.9, "imigracao": 32.9, "diplomacia": 39.8, "intervencao": 47.1, "economia": 28.0, "controle": 18.2, "comercio": 14.9, "religiao": 69.5, "moral": 62.1, "tecnologia": 66.5}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- SEM FILTRO DE RELIGIAO ---

=== TOP 2 PERSONALIDADES ===
97.5%  Mariana Leitão (mariana-leitao)
96.7%  Paul Romer (paul-romer)

=== TOP 2 IDEOLOGIAS ===
98.1%  Liberalismo (liberalismo)
97.7%  Neoliberalismo (neoliberalismo)

=== TOP 2 PAISES ===
94.8%  São Paulo (Brasil) (sao-paulo)
94.4%  Nevada (Estados Unidos) (eua-nevada)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
98.5%  Partido Democrático Liberal (FDP) (fdp)
97.1%  Partido Novo (NOVO) (partido-novo)
```

## Jorge Pinto

ID: `jorge-pinto`. Religiões: `[]`. Livro: A Liberdade dos Futuros: Ecorrepublicanismo para o Século XXI (2021).

Arquétipos: `{"sociedade": "D", "poder": "C", "economia": "B", "mundo": "C", "tecnologia": "C"}`.

Vetor calculado: `{"estrutura": 55.7, "representacao": 95.4, "poder": 25.8, "imigracao": 11.7, "diplomacia": 18.1, "intervencao": 60.1, "economia": 81.0, "controle": 78.1, "comercio": 51.4, "religiao": 76.2, "moral": 89.5, "tecnologia": 36.9}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- SEM FILTRO DE RELIGIAO ---

=== TOP 2 PERSONALIDADES ===
97.8%  Guilherme Boulos (guilherme-boulos)
97.7%  Zohran Mamdani (zohran-mamdani)

=== TOP 2 IDEOLOGIAS ===
97.1%  Progressismo (progressismo)
96.9%  Socialismo Democrático (socialismo-democratico)

=== TOP 2 PAISES ===
97.2%  País de Gales (Reino Unido) (pais-de-gales)
96.4%  Vermont (Estados Unidos) (eua-vermont)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
98.0%  Sumar (sumar)
97.8%  Frente Amplio (frente-amplio-chile)
```

## José Luís Carneiro

ID: `jose-luis-carneiro`. Religiões: `['catholic']`. Livro: Vencer os Tempos (2026).

Arquétipos: `{"sociedade": "F", "poder": "C", "economia": "C", "mundo": "C", "tecnologia": "D"}`.

Vetor calculado: `{"estrutura": 48.6, "representacao": 87.0, "poder": 44.9, "imigracao": 31.2, "diplomacia": 38.3, "intervencao": 38.7, "economia": 71.0, "controle": 56.9, "comercio": 33.0, "religiao": 44.0, "moral": 67.7, "tecnologia": 51.0}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- FILTRO DE RELIGIAO: catholic (usuario que escolheu catholic) ---

=== TOP 2 PERSONALIDADES ===
98.2%  Andy Burnham (andy-burnham)
96.8%  Barack Obama (barack-obama)

=== TOP 2 IDEOLOGIAS ===
95.2%  Centrismo Social (centrismo-social)
93.6%  Liberalismo Pragmático (liberalismo-pragmatico)

=== TOP 2 PAISES ===
96.4%  Illinois (Estados Unidos) (eua-illinois)
94.3%  Espanha (espanha)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
96.2%  Partido Social-Democrata da Alemanha (SPD) (spd)
96.0%  Partido Democrático (PD) (partido-democratico-italia)
```

## José Manuel Pureza

ID: `jose-manuel-pureza`. Religiões: `['catholic']`. Livro: Linhas Vermelhas: Crítica da Crise-como-Política (2015).

Arquétipos: `{"sociedade": "F", "poder": "C", "economia": "B", "mundo": "C", "tecnologia": "C"}`.

Vetor calculado: `{"estrutura": 42.6, "representacao": 94.2, "poder": 34.1, "imigracao": 19.3, "diplomacia": 8.6, "intervencao": 75.6, "economia": 89.3, "controle": 87.7, "comercio": 63.3, "religiao": 44.0, "moral": 78.4, "tecnologia": 34.5}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- FILTRO DE RELIGIAO: catholic (usuario que escolheu catholic) ---

=== TOP 2 PERSONALIDADES ===
96.8%  Karl Polanyi (karl-polanyi)
96.5%  Paulo Raimundo (paulo-raimundo)

=== TOP 2 IDEOLOGIAS ===
96.7%  Progressismo Cristão (progressismo-cristao)
96.1%  Socialismo Democrático (socialismo-democratico)

=== TOP 2 PAISES ===
94.1%  Chile de Allende (chile-de-allende)
92.2%  País de Gales (Reino Unido) (pais-de-gales)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
96.2%  Movimento dos Trabalhadores Rurais Sem Terra (MST) (movimento-dos-trabalhadores-rurais-sem-terra)
95.9%  Pacto Histórico (PH) (pacto-historico)
```

## Luís Montenegro

ID: `luis-montenegro`. Religiões: `[]`. Livro: Nenhuma obra elegível confirmada; não foi adicionado livro..

Arquétipos: `{"sociedade": "C", "poder": "C", "economia": "C", "mundo": "B", "tecnologia": "D"}`.

Vetor calculado: `{"estrutura": 33.1, "representacao": 87.0, "poder": 49.6, "imigracao": 53.1, "diplomacia": 42.1, "intervencao": 35.2, "economia": 47.2, "controle": 35.4, "comercio": 27.0, "religiao": 56.4, "moral": 40.7, "tecnologia": 52.2}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- SEM FILTRO DE RELIGIAO ---

=== TOP 2 PERSONALIDADES ===
95.7%  Nuno Melo (nuno-melo)
95.4%  Henri Bergson (henri-bergson)

=== TOP 2 IDEOLOGIAS ===
94.5%  Centrismo Liberal (centrismo-liberal)
93.1%  Centrismo (centrismo)

=== TOP 2 PAISES ===
97.2%  Kosovo (kosovo)
97.0%  Macedônia do Norte (macedonia-do-norte)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
96.8%  Partido Social Democrata (PSD) (psd-portugal)
96.8%  Casa de Bourbon (ramo espanhol) (casa-de-bourbon-espanha)
```

## Mariana Leitão

ID: `mariana-leitao`. Religiões: `[]`. Livro: Nenhuma obra elegível confirmada; não foi adicionado livro..

Arquétipos: `{"sociedade": "C", "poder": "C", "economia": "F", "mundo": "B", "tecnologia": "D"}`.

Vetor calculado: `{"estrutura": 56.9, "representacao": 90.6, "poder": 18.7, "imigracao": 32.9, "diplomacia": 51.7, "intervencao": 34.0, "economia": 25.6, "controle": 19.4, "comercio": 13.7, "religiao": 73.1, "moral": 76.4, "tecnologia": 74.9}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- SEM FILTRO DE RELIGIAO ---

=== TOP 2 PERSONALIDADES ===
97.5%  João Cotrim de Figueiredo (joao-cotrim-figueiredo)
95.2%  Leonard Peikoff (leonard-peikoff)

=== TOP 2 IDEOLOGIAS ===
96.2%  Neoliberalismo (neoliberalismo)
96.1%  Aceleracionismo Efetivo (aceleracionismo-efetivo)

=== TOP 2 PAISES ===
97.3%  Nevada (Estados Unidos) (eua-nevada)
92.4%  São Paulo (Brasil) (sao-paulo)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
98.2%  Partido Democrático Liberal (FDP) (fdp)
93.3%  Partido Novo (NOVO) (partido-novo)
```

## Mariana Mortágua

ID: `mariana-mortagua`. Religiões: `[]`. Livro: Manual de Economia Política (2021).

Arquétipos: `{"sociedade": "D", "poder": "C", "economia": "B", "mundo": "C", "tecnologia": "C"}`.

Vetor calculado: `{"estrutura": 41.4, "representacao": 95.4, "poder": 28.2, "imigracao": 12.9, "diplomacia": 14.5, "intervencao": 66.0, "economia": 94.1, "controle": 92.4, "comercio": 58.6, "religiao": 76.2, "moral": 90.7, "tecnologia": 48.8}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- SEM FILTRO DE RELIGIAO ---

=== TOP 2 PERSONALIDADES ===
98.3%  Hasan Piker (hasan-piker)
97.5%  Mark Fisher (mark-fisher)

=== TOP 2 IDEOLOGIAS ===
99.1%  Socialismo Democrático (socialismo-democratico)
96.1%  Socialismo Luxemburguista (socialismo-luxemburguista)

=== TOP 2 PAISES ===
94.2%  Chile de Allende (chile-de-allende)
93.1%  País de Gales (Reino Unido) (pais-de-gales)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
98.5%  A Esquerda (Die Linke) (die-linke)
97.1%  Partido Socialista dos Trabalhadores Unificado (PSTU) (partido-socialista-dos-trabalhadores-unificado)
```

## Nuno Melo

ID: `nuno-melo`. Religiões: `['catholic']`. Livro: Direito de Oposição (2019).

Arquétipos: `{"sociedade": "B", "poder": "C", "economia": "C", "mundo": "B", "tecnologia": "D"}`.

Vetor calculado: `{"estrutura": 45.0, "representacao": 87.0, "poder": 61.5, "imigracao": 54.0, "diplomacia": 56.4, "intervencao": 38.8, "economia": 38.9, "controle": 39.0, "comercio": 40.1, "religiao": 46.0, "moral": 27.7, "tecnologia": 51.0}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- FILTRO DE RELIGIAO: catholic (usuario que escolheu catholic) ---

=== TOP 2 PERSONALIDADES ===
95.9%  Sérgio Moro (sergio-moro)
95.7%  Luís Montenegro (luis-montenegro)

=== TOP 2 IDEOLOGIAS ===
96.9%  Conservadorismo Pragmático (conservadorismo-pragmatico)
94.1%  Centrismo Conservador (centrismo-conservador)

=== TOP 2 PAISES ===
95.5%  Lituânia (lituania)
95.1%  Armênia (armenia)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
95.4%  União Democrata-Cristã (CDU/CSU) (cdu-csu)
94.7%  União Brasil (UNIÃO) (uniao-brasil)
```

## Paulo Raimundo

ID: `paulo-raimundo`. Religiões: `[]`. Livro: Nenhuma obra elegível confirmada; não foi adicionado livro..

Arquétipos: `{"sociedade": "D", "poder": "C", "economia": "A", "mundo": "C", "tecnologia": "C"}`.

Vetor calculado: `{"estrutura": 43.8, "representacao": 94.2, "poder": 43.7, "imigracao": 21.2, "diplomacia": 15.7, "intervencao": 85.1, "economia": 90.1, "controle": 86.5, "comercio": 72.9, "religiao": 72.6, "moral": 76.4, "tecnologia": 48.8}`.

Compatibilidades calculadas pelo script oficial (com o filtro religioso indicado na saída):

```text
--- SEM FILTRO DE RELIGIAO ---

=== TOP 2 PERSONALIDADES ===
98.2%  Salvador Allende (allende)
97.2%  Bernie Sanders (bernie-sanders)

=== TOP 2 IDEOLOGIAS ===
97.9%  Socialismo Democrático (socialismo-democratico)
95.0%  Socialismo Luxemburguista (socialismo-luxemburguista)

=== TOP 2 PAISES ===
97.1%  Chile de Allende (chile-de-allende)
92.7%  País de Gales (Reino Unido) (pais-de-gales)

=== TOP 2 PARTIDOS E ORGANIZACOES ===
97.3%  A Esquerda (Die Linke) (die-linke)
96.7%  Sinn Féin (sinn-fein)
```

## Verificação final

- Backend: 398 testes passaram, sem falhas nem testes ignorados.
- Frontend: 238 testes passaram em 34 ficheiros. Os limites de tempo dos testes de navegação foram temporariamente aumentados nesta máquina Windows; todas as asserções foram mantidas e o ficheiro de teste original foi restaurado. Com os limites originais, houve falhas por timeout antes da integração.
- `scripts/check_i18n.py`: passou, com cobertura completa dos overlays atuais.
- `npm run build`: passou (TypeScript, Vite e geração de 2 986 páginas PT/EN). Permanece o aviso preexistente de bundles acima de 500 kB.
- Verificadas as 24 novas páginas PT/EN, os 12 retratos copiados para a distribuição e a igualdade entre vetores arquivados e recalculados.
- Inspeção no navegador: perfil PT de Montenegro e perfil EN de Leitão, incluindo retrato, eixos e ligações de comparação.
- `git diff --check`: sem erros. Nenhuma mudança ao código de pontuação, ao validador ou aos testes fica no projeto.

O projeto está preparado para utilização local. A submissão pública ao GitHub continua por efetuar; a exceção de semelhança deve ser apresentada ao mantenedor.
