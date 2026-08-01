# Análise completa do site atual — a7n.com.br

> Levantamento feito em 2026-08-01 pra servir de base no site novo (reconstrução do zero).
> Objetivo: não perder nenhum conteúdo, contato ou copy que já funciona, e mapear o que falta.

## 1. Estrutura de navegação (site atual)

Menu principal:
- Home
- Pré-Lançamento → Jardim Dona Cilla
- Pré-Lançamento → Jardim Bom Sucesso
- Contato

**Observação técnica:** o site usa URLs do tipo `?page_id=110` pra algumas páginas (Contato, por exemplo) em vez de slugs limpos. No site novo, vale usar slugs (`/contato/`) em tudo — melhor pra SEO e pra lembrar a URL.

## 2. Conteúdo institucional

**Missão (repetida em quase toda página — texto oficial da marca):**
> "Realizar sonhos é nossa missão. O sonho da casa própria, o sonho do investimento, o sonho de morar na praia."

**Sobre a empresa:**
> "Atuamos na construção civil desde 2016, nas cidades de Balneário Camboriú e Camboriú. Nossos empreendimentos são projetados pensando no melhor para você e sua família, buscando qualidade de vida e valorização financeira."

**Hero da home (3 blocos):**
1. "JARDIM DONA CILLA" — "Feito para sua Família" — CTA "Pré-Lançamento"
2. "JARDIM BOM SUCESSO" — "Um Empreendimento Memorável" — CTA "Pré-Lançamento"
3. "Realize seu Sonho" — "Fale com nossos consultores" — CTA "Contato"

**Chamada da seção de pré-lançamentos:**
> "Você está procurando uma oportunidade de moradia ou investimento que seja perfeita para você? Então não perca tempo! A7N Empreendimentos está com oportunidades exclusivas por tempo limitado."

## 3. Empreendimentos

### Pré-lançamentos

**Jardim Dona Cilla** — `/prelancamentos/jardim-dona-cilla/`
- Subheadline: "Feito para sua Família"
- Texto: "O Jardim Dona Cilla foi pensado para proporcionar o máximo de bem-estar para toda sua família. Localizado no bairro Tabuleiro na cidade de Camboriú, une o contato e a proximidade com a natureza ao conforto e requinte de um empreendimento deste porte, com uma excelente área de lazer e convívio, apartamentos amplos e confortáveis."
- Localização: bairro Tabuleiro, Camboriú
- Amenidades: Salão de Festas, Academia, Sala de Jogos, Brinquedoteca, Piscina
- **Faltando no site atual:** metragens, tipos de unidade, previsão de entrega, condição de pagamento (temos isso internamente: entrada 3x R$49.997 + 30x R$7.497 + 5 intermediárias R$44.997 + saldo financiamento, entrega dez/2028, área privativa 68-103m² conforme tipo — ver `_memoria/estrategia.md`)

**Jardim Bom Sucesso** — `/prelancamentos/jardim-bom-sucesso/`
- Conceito: "O Jardim Bom Sucesso Residence chega para se tornar um marco no bairro histórico da Barra em Balneário Camboriú."
- Destaque: "Um bairro histórico merece um empreendimento memorável"
- Texto: "Inspirado na tradição e tranquilidade do bairro, une o contato e a proximidade com a natureza ao conforto e requinte de um empreendimento desse porte, com uma excelente área de lazer e convívio e apartamentos amplos e confortáveis."
- Amenidades: entrada principal, praça do fogo, piscina (com visualização 360°), área externa, academia, espaço kids
- Tipos de unidade: aptos tipo 1 e 8 / 2 e 7 / 3 e 6 / 4 e 5 (todos com vista 360°)
- Localização: bairro da Barra, Balneário Camboriú

**Alameda Jardins** — `/prelancamentos/alameda-jardins/`
- Headline: "Bem-vindo ao Alameda Jardins, um refúgio luxuoso para você e sua família."
- Subheadline: "Geminados em formato triplex de alto padrão. Este é o lugar em meio à natureza que você encontra conforto, bem-estar e segurança."
- Diferenciais: geminados triplex alto padrão, meio à natureza, conforto/bem-estar/segurança
- **Faltando:** metragens, entrega, condição de pagamento

### Entregues

**Sobrado Rio Pequeno** — `/sobrado-rio-pequeno/`
- Texto: "Ideal para quem procura morar bem, mas também não quer investir muito! Sobrados com excelente espaço interno, com cômodos bem divididos e espaçosos contendo 2 suítes, fundos com 4 metros de espaço livre e 2 vagas de garagem. More próximo a Balneário Camboriú, em uma região que vem valorizando muito e é de fácil acesso. Localizado a menos de 5 minutos da BR-101."
- Specs: 2 suítes, 4m de fundos livres, 2 vagas de garagem
- Localização: próximo BC, <5min da BR-101

**Vila Orizada Residence** — `/vila-orizada-residence/`
- Localização: bairro Monte Alegre, Camboriú — "um dos bairros que mais valoriza na cidade", "rua tranquila e livre de enchentes"
- Acabamento: "fachada com acabamentos diferenciados", porcelanato, teto com detalhes em gesso, infraestrutura pra ar-split, internet e TV

**Ariels I** — `/ariels-i/`
- Texto: "Com excelente custo/benefício, é uma ótima opção para quem quer morar bem"
- Specs: 2 dormitórios, área de fundos privativa, 1 vaga de garagem, construção estilo sobrado
- Localização: próximo BC, <5min BR-101, perto de supermercados/comércio

**Ariels II** — `/ariels-ii/`
- Texto: "Localizado em uma esquina de um dos bairros que mais cresce em Camboriú, de fácil acesso a Balneário Camboriú e próximo dos principais comércios da cidade."
- Specs: 1 suíte + 1 dormitório, sala estar/jantar integrados, cozinha, área de serviço, banheiro social, vaga de garagem privativa

## 4. Blog / Matérias (`/materias/`)

SEO de conteúdo institucional/regional, 6 artigos publicados:

1. **A7N Empreendimentos: Seu Parceiro Ideal para Investir em Balneário Camboriú** — `/investir-em-balneario-camboriu/` — argumenta experiência/credibilidade, projetos inovadores, localização estratégica, atendimento personalizado
2. **O Mercado Imobiliário em Balneário Camboriú: Oportunidades e Valorização** — `/mercado-imobiliario-em-balneario-camboriu/` — valorização, demanda, qualidade de vida, infraestrutura, retorno financeiro
3. **Balneário Camboriú: A Jóia do Litoral Catarinense** — `/balneario-camboriu/` — belezas naturais, infraestrutura, cultura/lazer, desenvolvimento urbano
4. **Balneário Camboriú e suas belas praias!** — `/balneario-camboriu-e-suas-belas-praias/` — guia das praias (Central, Taquarinhas, etc.)
5. **Conheça o bairro histórico da Barra/BC** — `/conheca-o-bairro-historico-da-barra-bc/` — história do bairro, Capela de Santo Amaro (1810), Casa Linhares, Maracatu
6. **Turismo Rural de Camboriú** — `/turismo-rural-de-camboriu/` — institucional genérico, pouco conteúdo específico sobre turismo rural (oportunidade de melhorar no site novo)

**Padrão identificado:** os artigos servem mais pra SEO local (nome da cidade/bairro no título) do que pra gerar autoridade de conteúdo real — no site novo dá pra aprofundar mais em dados concretos (preço médio do m², histórico de valorização) em vez de texto genérico.

## 5. Contato

- **Telefone/WhatsApp:** (47) 99754-0084 (também aparece como (47) 9954-0084 em algumas páginas — inconsistência a corrigir no site novo)
- **Emails:** adm@a7n.com.br e contato@arielscontrutora.com.br (dois domínios diferentes — vale unificar)
- **Endereços:**
  - Rua Biguaçu, 534 – Balneário Camboriú – SC (principal, página de contato)
  - Rua 981, nº196, sala 01 – Balneário Camboriú – SC (aparece nas páginas de empreendimento)
- **Horário de atendimento:** segunda a sexta, 08h às 18h
- **Redes sociais:** Facebook, Instagram, YouTube, WhatsApp
- **Formulário de contato:** campos — nome, email, assunto, mensagem (opcional)

## 6. Rodapé

> "© 2024 – Todos os Direitos Reservados – A7N Empreendimentos. Balneário Camboriú – SC. Desenvolvido por BC Sites e Sistemas"

(Nota: copyright ainda em 2024, desatualizado)

## 7. Recomendações pro site novo

- **Unificar contato:** um telefone só, um email só (o domínio `arielscontrutora.com.br` parece resquício de nome anterior/associado — decidir se mantém ou descarta)
- **Padronizar URLs:** trocar `?page_id=` por slugs limpos em todas as páginas
- **Adicionar specs técnicas nas páginas de empreendimento:** metragem, tipos de unidade, previsão de entrega, condição de pagamento — hoje só aparecem informações internas (PDF/planilha), não no site
- **Aproveitar a identidade visual já validada:** logo navy/teal, tipografia Bebas Neue + Source Sans 3, já usada nos criativos do Jardim Dona Cilla (ver `identidade/design-guide.md`)
- **Atualizar rodapé** (ano do copyright)
- **Reaproveitar a missão/tagline** — "Realizar sonhos é nossa missão" já é uma frase forte e repetida consistentemente, vale manter como âncora de marca
- **Formulário de contato:** considerar adicionar as perguntas de qualificação de lead já definidas em `_memoria/estrategia.md` (finalidade, capacidade de entrada, urgência)
