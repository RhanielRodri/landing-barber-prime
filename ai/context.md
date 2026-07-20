---
project: Barber Prime
updated_at: "2026-07-20T01:38:06-03:00"
status: active
product_type: landing page demonstrativa para barbearia
primary_action: visitante escolhe um serviço e abre o contato pelo WhatsApp
target_user: pequenos negócios locais de barbearia e seus clientes
stack:
  - HTML5
  - CSS3
  - JavaScript vanilla
repository: "."
production: declarada na documentação como Vercel; runtime atual não confirmado
source_of_truth: Git e código observável no repositório
---

# Contexto do projeto

## Problema resolvido

Apresenta serviços de uma barbearia demonstrativa e concentra a conversão em CTAs de contato pelo WhatsApp.

## Fluxo principal

O visitante conhece os serviços, preços, galeria, informações do negócio e localização, escolhe um CTA e abre uma mensagem pré-preenchida no WhatsApp.

## Arquitetura confirmada

- Site estático sem framework, backend, banco ou etapa de build declarada.
- `index.html` concentra conteúdo e estrutura.
- `style.css` implementa o layout responsivo.
- `script.js` controla a navegação móvel.
- `i18n.js` fornece português e inglês com preferência salva no navegador.

## Ambientes e integrações observados

- Execução local direta pelo navegador, sem dependências.
- Deploy no Vercel declarado no README e no registro técnico global.
- Links externos para WhatsApp com número demonstrativo.
- Imagens carregadas do Unsplash.
- Mapa incorporado do Google Maps.
- Existe configuração local ignorada do Vercel; seus valores não foram lidos nem persistidos.

## Papel no portfólio

O registro técnico declara Barber Prime como peça de portfólio e opção de entrada para a oferta de barbearia. O código confirma que se trata de uma demonstração fictícia orientada à conversão pelo WhatsApp.

## Fontes autoritativas

- Git e código do repositório para funcionalidades e arquitetura.
- README e registro técnico global somente como declarações de objetivo, papel e deploy.

## Limites de confiança

Esta adoção não abriu a aplicação no navegador, não executou smoke, não consultou o runtime publicado e não alterou arquivos preexistentes. A responsividade, os CTAs, o menu, a troca de idioma, os recursos externos e a URL declarada de produção permanecem sem validação atual.
