---
title: 'Adding an outside collaborator to a {% data variables.product.prodname_project_v1 %} in your organization'
intro: 'As an organization owner or {% data variables.projects.projects_v1_board %} admin, you can add an outside collaborator and customize their permissions to a {% data variables.projects.projects_v1_board %}.'
redirect_from:
  - /articles/adding-an-outside-collaborator-to-a-project-board-in-your-organization
  - /github/setting-up-and-managing-organizations-and-teams/adding-an-outside-collaborator-to-a-project-board-in-your-organization
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: コラボレーターの追加
allowTitleToDifferFromFilename: true
---

{% data reusables.projects.project_boards_old %}

An outside collaborator is a person who isn't explicitly a member of your organization, but who has permissions to a {% data variables.projects.projects_v1_board %} in your organization.

{% data reusables.profile.access_org %}
{% data reusables.user-settings.access_org %}
{% data reusables.organizations.organization-wide-project %}{% ifversion projects-v2 %}
1. Click **Projects (classic)**{% endif %}
{% data reusables.project-management.select-project %}
{% data reusables.project-management.click-menu %}
{% data reusables.project-management.access-collaboration-settings %}
{% data reusables.project-management.collaborator-option %}
9. \[Search by username, full name or email address\] (ユーザ名、フルネーム、メールアドレスでの検索) の下で、外部のコラボレータの名前、ユーザ名、{% data variables.product.prodname_dotcom %}メールを入力してください。 ![Octocat のユーザ名が検索フィールドに入力されているコラボレーターセクション](/assets/images/help/projects/org-project-collaborators-find-name.png)
{% data reusables.project-management.add-collaborator %}
{% data reusables.project-management.collaborator-permissions %}
