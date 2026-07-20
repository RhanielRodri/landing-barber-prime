---
project: Barber Prime
updated_at: "2026-07-20T01:38:06-03:00"
review_at: "2026-07-27"
status: active
current_phase: adoção ao padrão operacional ai/
technical_baseline:
  commit: 947ff735f54e2df73436e5ac71dfc0abf227f5c1
  validation_status: unvalidated
  validated_at: não confirmado
  validated: []
  not_validated:
    - carregamento do site em navegador
    - layout desktop e móvel
    - navegação e menu móvel
    - troca de idioma e persistência da preferência
    - CTAs e links de WhatsApp
    - imagens externas e Google Maps
    - console do navegador
    - runtime atual no Vercel
  evidence: []
source: descoberta somente leitura do repositório, Git remoto e registro técnico declarado
source_of_truth: Git e código observável no repositório
---

# Estado do projeto

## Baseline técnica

O último commit de código observado adiciona suporte bilíngue PT/EN por atributos `data-i18n`. A baseline está `unvalidated`: não há check-run ou status remoto ligado ao commit e nenhuma validação de aplicação foi executada nesta adoção.

## Snapshot Git

- `observed_at`: `2026-07-20T01:38:06-03:00`
- branch observada: `main`
- `head_at_observation`: `947ff735f54e2df73436e5ac71dfc0abf227f5c1`
- sincronização observada: `HEAD`, upstream e `origin/main` remoto no mesmo commit; divergência `0/0`
- classificação da working tree: limpa; staging vazio; nenhum arquivo não rastreado

## Último resultado confirmado

- Suporte bilíngue PT/EN presente no último commit de código.
- Estrutura estática com CTAs de WhatsApp, menu móvel, conteúdo comercial, imagens externas e mapa incorporado presente no repositório.

## Em andamento

- Nenhum trabalho funcional confirmado em andamento.
- Adoção documental ao padrão `ai/` autorizada nesta operação.

## Bloqueios

- Nenhum bloqueio de implementação foi confirmado.
- A saúde do runtime publicado e os fluxos essenciais permanecem não confirmados.
- Os CTAs usam número demonstrativo e não representam contato comercial real.

## Riscos

- O README e o registro global declaram deploy ativo, mas não há evidência atual de runtime ligada ao HEAD.
- A experiência depende de recursos externos do Unsplash, Google Maps e WhatsApp.
- O site não deve ser tratado como implantação real enquanto o número demonstrativo não for substituído em uma fase explicitamente autorizada.

## Próxima ação

Confirmar o runtime publicado e executar validação responsiva dos CTAs, idioma, navegação e console, sem alterar código.

## Snapshot histórico declarado

- README e registro global declaram deploy no Vercel.
- O registro global descreve o projeto como peça de portfólio e opção de entrada da oferta de barbearia.
- Essas declarações não substituem validação atual do runtime.

## Divergências

- A documentação declara o site publicado e ativo; o Git remoto do commit não apresenta check-run ou status de deploy e o runtime não foi consultado nesta adoção.

## Validações recentes

- 2026-07-20: resolução do checkout, identidade do origin, branch, HEAD, upstream, remoto real e divergência conferidos.
- 2026-07-20: arquitetura, funcionalidades, integrações, scripts e papel no portfólio inspecionados somente em leitura.
- 2026-07-20: ausência de check-runs e status remoto ligado à baseline confirmada.
- Testes, build, servidor, navegador, runtime, deploy, migration e banco não foram executados.
