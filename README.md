# comprar proxy brasil: quanto custa por GB, como testar IPs brasileiros antes de pagar e configurar em 5 minutos

Quem digita isso quase sempre tem o mesmo objetivo prático: fazer um site enxergar uma conexão brasileira. Às vezes é scraping de preços no comércio local, às vezes é conferir se o anúncio aparece certo para quem está em São Paulo, às vezes é acessar conteúdo liberado só no Brasil, às vezes é rodar várias contas sem que todas venham do mesmo endereço.

O problema é que quase toda página que aparece na busca para "comprar proxy brasil" fala de pool gigante, "IPs premium" e "alta performance" sem nunca mostrar o preço real. Aqui a ordem é outra: primeiro o que você está comprando, depois quanto custa, depois como gastar US$ 5 para validar antes de comprar volume.

## O que muda de verdade quando o proxy é brasileiro

O país do IP é só metade da história. A outra metade é o tipo de rede de onde ele vem, e isso define se o site de destino vai te tratar como visitante comum ou como bot.

Um IP de datacenter é rápido e barato, mas vem de um bloco de servidor. Sites com proteção anti-bot costumam olhar esse detalhe antes de qualquer outra coisa. Já um IP residencial sai de uma conexão doméstica real — o tipo de endereço que Vivo, Claro e operadoras regionais entregam para pessoas físicas — e por isso passa por esse primeiro filtro com muito mais frequência. IP móvel é o caso extremo: sai de uma rede celular, onde centenas de pessoas compartilham o mesmo endereço, então bloquear costuma custar caro para quem bloqueia.

Na prática, para tarefas brasileiras:

- **Monitoramento de preço e catálogo** (marketplaces, varejo, delivery) pede IP residencial brasileiro, porque a resposta muda conforme a região.
- **Verificação de anúncio e de SERP** também pede residencial, já que você quer ver exatamente o que o usuário local vê.
- **Coleta em massa de páginas abertas** pode rodar em datacenter e economizar metade do orçamento.
- **Alvos com defesa pesada** (apps, redes sociais, plataformas que checam reputação do IP) são onde o móvel faz diferença — e onde ele custa mais caro.

> Se você só precisa de geolocalização no Brasil e não de sessões longas e fixas, quase sempre o residencial resolve. O móvel só compensa quando residencial já está falhando no alvo específico.

## Quanto custa um proxy brasileiro hoje

A conta é por gigabyte de tráfego, não por IP. As faixas publicadas por fornecedores e por comparativos de mercado em 2026 ficam assim:

| Tipo de proxy | Faixa de mercado em 2026 | Como costuma ser cobrado |
| --- | --- | --- |
| Residencial | US$ 1 a US$ 8 por GB | por GB trafegado |
| Datacenter | US$ 0,50 a US$ 3 por GB | por GB ou por IP/mês |
| Móvel (4G/5G) | US$ 2 a US$ 15 por GB | por GB trafegado |
| ISP / estático | US$ 1,50 a US$ 5 por IP | por IP/mês |

O ponto que quase ninguém coloca na conta: taxa por GB anunciada não é custo final. Tráfego que expira no fim do mês, mínimo mensal obrigatório, cobrança extra para escolher cidade, taxa de sucesso baixa que força retentativa — tudo isso aparece depois, na fatura. Um provedor de US$ 0,60/GB que bloqueia metade das requisições sai mais caro do que um de US$ 1/GB que passa na primeira tentativa.

## DataImpulse: pagamento por GB, sem assinatura

A DataImpulse é uma provedora que apostou justamente nessa simplicidade: preço fixo por GB, sem mensalidade, sem contrato, e tráfego que não expira. O que você compra fica no saldo até você usar.

O que está publicado hoje pela própria empresa:

- Pool de mais de 90 milhões de IPs residenciais, em 195 países, com origem declaradamente consentida (participantes entram por app, recebem pelo tráfego compartilhado e podem sair).
- Segmentação por país inclusa no preço base. Cidade, estado, CEP e ASN entram como filtros avançados, cobrados em dobro no residencial padrão — no residencial premium, todos os filtros já vêm inclusos.
- Sessões rotativas (IP novo a cada requisição) e sessões fixas de até 30 minutos.
- HTTP/HTTPS e SOCKS5, autenticação por usuário/senha ou por lista de IPs permitidos.
- Taxa de sucesso divulgada de 99,51% e tempo de resposta abaixo de 1 segundo.
- Suporte humano 24/7, com nota 4,8/5 no G2 segundo a própria empresa.

Vale registrar o outro lado, porque ele existe: a sessão fixa de 30 minutos é curta comparada a provedores que oferecem sessões de horas, e a empresa não vende proxy ISP estático. Se o seu projeto depende de manter o mesmo IP por dias para gerenciar contas, esse não é o produto.

### Tabela de preços: todos os pacotes publicados

O modelo é pay-as-you-go, então não existem "planos mensais" — existem pacotes de tráfego dentro de cada tipo de proxy. A compra mínima em qualquer um deles é US$ 5.

| Tipo de proxy | Pacote inicial | Preço por GB | Faixa intermediária | Volume grande (1 TB+) | Comprar |
| --- | --- | --- | --- | --- | --- |
| Residencial | 5 GB por US$ 5 | US$ 1,00 | mesmo preço por GB em qualquer volume | US$ 800 por 1 TB (US$ 0,80/GB) | [ver pacotes de proxy residencial](https://dataimpulse.com/residential-proxies/?aff=86938) |
| Datacenter | 10 GB por US$ 5 | US$ 0,50 | 100 GB por US$ 50 | US$ 450 por 1 TB (US$ 0,45/GB) | [ver pacotes de proxy datacenter](https://dataimpulse.com/datacenter-proxies/?aff=86938) |
| Móvel | 2,5 GB por US$ 5 | US$ 2,00 | 25 GB por US$ 50 | US$ 1.600 por 1 TB (US$ 1,60/GB) | [ver pacotes de proxy móvel](https://dataimpulse.com/mobile-proxies/?aff=86938) |
| Residencial Premium | 1 GB por US$ 5 | US$ 5,00 | 10 GB por US$ 50 | a partir de US$ 4.000 por 1 TB (US$ 4,00/GB) | [ver pacotes de residencial premium](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |

Nenhum desses pacotes tem renovação automática, cobrança mensal ou expiração de tráfego. O residencial premium (pool de menor latência, com gerente de conta dedicado) cobra mais por GB justamente porque o diferencial não é cobertura, é desempenho e atendimento.

## Cobertura do Brasil: o que checar antes de pagar

Aqui está a parte que economiza dinheiro. A DataImpulse publica contadores por país, então dá para ver o tamanho do pool brasileiro antes de colocar cartão. Consultando as páginas de localização, o pool de datacenter no Brasil aparece na casa dos milhares de IPs ativos, enquanto o residencial premium no Brasil mostra dezenas de milhares de IPs ativos em tempo real e algo em torno de meio milhão de IPs únicos em 30 dias. Esses números oscilam ao longo do dia — são contadores ao vivo, não uma promessa fixa.

Para quem trabalha com alvos brasileiros, o que importa é:

1. **Segmentação por país é gratuita.** Você não paga extra para pedir IP do Brasil. O parâmetro vai direto na credencial, no formato `usuario:senha_country-br`, apontando para o gateway `gw.dataimpulse.com` na porta `823`.
2. **Cidade custa o dobro no residencial.** Se você realmente precisa de IP de São Paulo ou do Rio, isso dobra o preço efetivo por GB. Se a cidade não é obrigatória, ficar no nível de país mantém a conta no valor anunciado.
3. **Sessão fixa de até 30 minutos.** Bom para login, teste de funil e coleta consistente; insuficiente para fluxos que exigem dias na mesma identidade.
4. **Filtros de exclusão de ASN entram na faixa gratuita**, o que ajuda a tirar operadoras específicas do caminho quando o alvo reclama de determinada rede.

👉 [Conferir o pool brasileiro de proxies residenciais premium](https://dataimpulse.com/pt/proxies-by-location/premium-residential-proxy/br/?aff=86938)

## Como testar com US$ 5 antes de comprar volume

O erro comum é começar com 100 GB para um projeto que talvez precise de 8. Como não há assinatura nem expiração, dá para fazer isso com risco baixo:

1. **Criar a conta** no cadastro self-service — não há etapa de aprovação comercial nem contato com vendas.
2. **Comprar o pacote de entrada do tipo escolhido.** Para tarefas brasileiras de coleta e verificação, o de 5 GB residencial por US$ 5 é o ponto de partida mais direto: são 5 GB para medir custo por requisição bem-sucedida no seu alvo real.
3. **Gerar as credenciais** no painel, escolhendo tipo de rotação (rotativa ou fixa) e o país.
4. **Testar em um endpoint de verificação** para confirmar que o IP responde como brasileiro, e depois rodar algumas centenas de requisições no site que você realmente quer acessar.
5. **Comparar taxa de sucesso**, não apenas latência. Se 3% das requisições falham e você precisa de retry, seu custo real por dado útil sobe — e é aí que a decisão de escalar ou não fica clara.

Só depois desse teste faz sentido comprar 1 TB para destravar o desconto de 20%. Comprar volume antes de medir taxa de sucesso é a forma mais fácil de pagar por tráfego que não vira dado.

## Pagamento, reembolso e o que não existe

O cadastro é em dólar, e o pagamento aceito hoje é cartão Visa/Mastercard, cripto e AliPay. PayPal não está na lista, o que é uma limitação real para quem depende só dele.

Não existe teste gratuito. Todo acesso começa com a compra mínima de US$ 5. O que existe é garantia de reembolso de 7 dias (168 horas) para pagamentos em cartão nos planos de entrada, desde que menos de 80% do tráfego tenha sido consumido. Compras feitas em cripto nos planos de entrada não são reembolsáveis. Em comparação, boa parte dos provedores do mercado oferece 24 horas de janela de reembolso ou nenhuma — o comparativo publicado pela Caproxy coloca a DataImpulse no topo desse quesito, junto com a Evomi.

## Onde essa escolha é errada

Vale ser direto: a DataImpulse não serve para todo mundo.

- **Gerenciamento de contas de longo prazo.** Não há IP ISP estático nem residencial estático. Se o seu fluxo depende de manter a mesma identidade por dias, você precisa de outro tipo de provedor.
- **Sites de banco, governo e serviços altamente sensíveis.** Proxies residenciais rotativos não são a ferramenta para isso, e a própria empresa posiciona o produto como coleta de dados públicos e acesso a conteúdo.
- **Sessões longas.** O teto de 30 minutos na sessão fixa elimina casos que exigem estabilidade de horas.
- **Extensão de navegador própria.** A integração é por API, credenciais e lista de IPs permitidos; quem quer um plugin pronto para o navegador não vai encontrar aqui.

Também vale olhar o desempenho medido por terceiros com ceticismo saudável. O Shifter mediu 172.893 IPs ativos em cinco países, aproximadamente 60% do tamanho da rede mais profunda que eles testaram, com medianas de resposta entre 430 ms e 501 ms. O ProxyLook registrou 99,3% de sucesso em benchmark e latência P95 em torno de 0,9 s. Ou seja: preço baixo não veio acompanhado de rede rasa no atacado, mas a profundidade por região não é a maior do mercado — e no Brasil isso significa que cidades pequenas podem ter menos opções do que capitais.

## Comparando com o que o mercado cobra

Segundo o guia de preços de proxies publicado pela própria DataImpulse, a faixa justa em 2026 é de US$ 1 a US$ 8 por GB no residencial, US$ 2 a US$ 15 no móvel e US$ 0,50 a US$ 3 no datacenter — sendo que a média do mercado fica entre US$ 3 e US$ 8 no residencial. Comparativos independentes, como o da Caproxy, apontam o mesmo intervalo de US$ 1 a US$ 8 por GB para residencial e listam a DataImpulse na taxa mínima, com reembolso de 168 horas e nota 4,6/5 no Trustpilot.

Isso muda a decisão de compra de duas formas. Primeiro: US$ 1/GB é preço de entrada, não preço médio — provedores que cobram US$ 5/GB normalmente estão vendendo pool mais profundo, SLA ou suporte empresarial. Segundo: como o tráfego não expira, quem tem uso irregular (pesado em um mês, quase zero no seguinte) tende a gastar menos aqui do que num plano mensal que reinicia a cota.

## Perguntas que aparecem antes da compra

**O tráfego expira?** Não. O que você compra fica no saldo indefinidamente, sem reset mensal.

**Preciso de CNPJ ou contrato?** Não há etapa de aprovação comercial. Você cria a conta, compra o pacote e usa. A cobrança é em dólar.

**Consigo escolher a cidade (São Paulo, Rio de Janeiro)?** Sim, mas no residencial padrão esse filtro é cobrado em dobro. No residencial premium, cidade, CEP, estado e ASN já estão incluídos no preço por GB.

**Funciona com Python, Scrapy, Playwright e Selenium?** Sim — é proxy HTTP(S) e SOCKS5 padrão, com autenticação por usuário/senha, o que funciona em qualquer ferramenta que aceite proxy.

**Quantos IPs brasileiros existem?** A empresa publica contadores por país, então dá para verificar antes de pagar. Os valores mudam ao longo do dia.

**Vale a pena para um projeto pequeno?** Sim. Com US$ 5 você já testa um alvo real. O modelo não penaliza quem compra pouco, o que é incomum no setor.

**Tem desconto para volume grande?** Sim: US$ 0,80/GB no residencial acima de 1 TB, US$ 0,45/GB no datacenter e US$ 1,60/GB no móvel. Acima disso, o preço é negociado.

## Resumo prático

Se você precisa de IP brasileiro residencial para coletar dados, verificar anúncios ou conferir SERP local, e quer previsibilidade de custo sem assinatura, a conta é simples: US$ 5 de entrada, US$ 1 por GB no residencial, filtro de país incluso e tráfego que não vence.

Se o projeto é multi-conta de longo prazo com IP fixo, banco, ou sessão de horas, procure outro tipo de fornecedor — não porque o preço é ruim, mas porque o produto não é esse.

Para o resto, a ordem que faz sentido é sempre a mesma: comprar o pacote mínimo, medir o custo por requisição bem-sucedida no seu alvo brasileiro real, e só então escalar para o volume que destrava os US$ 0,80/GB.

👉 [Começar com o pacote de 5 GB por US$ 5](https://bit.ly/dataimPulse)
