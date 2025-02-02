---
title: Restringir interações na organização
intro: É possível aplicar temporariamente um período de atividade limitada para determinados usuários em todos os repositórios públicos pertencentes à sua organização.
redirect_from:
  - /github/setting-up-and-managing-organizations-and-teams/limiting-interactions-in-your-organization
  - /articles/limiting-interactions-in-your-organization
  - /github/building-a-strong-community/limiting-interactions-in-your-organization
versions:
  fpt: '*'
  ghec: '*'
permissions: Organization owners and moderators can limit interactions in an organization.
topics:
  - Community
shortTitle: Limitar interações no org
---

## Sobre limites temporários de interação

O limite de interações na organização habilita limites de interação temporária para todos os repositórios públicos pertencentes à organização. {% data reusables.community.interaction-limits-restrictions %}

{% data reusables.community.interaction-limits-duration %} Após a duração do seu limite passar, os usuários podem retomar a atividade normal nos repositórios públicos da sua organização.

{% data reusables.community.types-of-interaction-limits %}

Os integrantes da organização não são afetados por nenhum dos tipos de limite.

Quando você habilita restrições de atividades para toda a organização, você não pode habilitar ou desabilitar restrições de interação em repositórios individuais. Para obter mais informações sobre limitação de atividade para um repositório individual, consulte "[Limitar interações no repositório](/communities/moderating-comments-and-conversations/limiting-interactions-in-your-repository)".

Os proprietários e moderadores da organização também podem bloquear usuários por um determinado período de tempo. Após o término do bloqueio, o usuário é automaticamente desbloqueado. Para obter mais informações, consulte "[Bloquear um usuário em sua organização](/communities/maintaining-your-safety-on-github/blocking-a-user-from-your-organization)".

## Restringir interações na organização


{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
1. _Para os proprietários da organização:_ Na seção "Acesso" da barra lateral, selecione **Moderação de {% octicon "report" aria-label="The report icon" %}** e, em seguida, clique em **Limites de interação**.

   _Para moderadores da organização:_ Na barra lateral, clique em **Limites de interação**.

{% data reusables.community.set-interaction-limit %}
  ![Opções Temporary interaction limit (Restrições de interação temporárias)](/assets/images/help/organizations/organization-temporary-interaction-limits-options.png)

## Leia mais
- "[Denunciar abuso ou spam](/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam)"
- "[Gerenciar o acesso de um indivíduo a um repositório da organização](/articles/managing-an-individual-s-access-to-an-organization-repository)"
- "[Permission levels for a personal account repository](/articles/permission-levels-for-a-user-account-repository)"
- "[Funções do repositório para uma organização](/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization)"
- "[Gerenciando moderadores na sua organização](/organizations/managing-peoples-access-to-your-organization-with-roles/managing-moderators-in-your-organization)"
