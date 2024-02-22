
# ♻️ Fluxo de Trabalho

:rotating_light: **TODAS** as modificações que forem realizadas nos repositórios devem estar atreladas a algum chamado.

:rotating_light: **SEMPRE** que alterações forem realizadas é necessário seguir este fluxo de trabalho baseado no GITHUB Flow

:rotating_light: **SEMPRE** envie suas alterações ao GIT, principalmente se já estiverem aplicadas em **produção**

### :pushpin: Introdução

Todos os nosso repositórios são compostos por 1 ou mais branches, sendo a principal a **main**

Nela ficam as ultimas alterações realizadas no repositório que já tenham ido para **produção**.

As demais branches são frutos de features e correções que não foram finalizadas ou enviadas para produção ainda.

Então, no momento que for necessário realizar alguma alteração no código, deve-se seguir esse fluxo de ações.

> Caso não tenha familiaridade com o git ou linhas de comando, é recomendado que utilize o aplicativo Github Desktop

> [Fluxo de trabalho com o Github desktop](https://github.com/starplast/.github/blob/main/profile/Documentations/fluxo_trabalho_github_desktop.md)

1. Vá até o repositório em questão.

2. Faça uma cópia do repositório remoto localmente em sua máquina com `git clone <link_para_o_repo>`

3. Crie uma nova branch seguindo o padrão de nomenclatura estipulado com `git branch -b <nome_branch>`

4. Faça as alterações necessárias, realize testes etc
 
5. Adicione os arquivos alterados para o commit com `git add <arquivos>`

6. Envie suas alterações para o repositório remoto com `git push origin <nome_branch>`

7. Abra a página WEB do repositório

8. Por ter alterações recentes, o github automaticamente vai identificar e perguntar se gostaríamos de criar um pull request para a branch
 ![](../Documentations/assets/github-web-recent-pushes.png)

9. Pressione "Compare & pull request"

10. Uma tela irá ser exibida para a criação do pull request, nela é possível verificar com qual branch gostaríamos de mesclar nossa branch pelo campo "base" e qual a nossa branch pelo campo "compare".

![](../Documentations/assets/github-web-open-pull-request.png)

Nesta tela também será exibida a mensagem do pull request, ela já será gerada por padrão, mas é necessário preencher com as informações corretas.

11. Ao finalizar o preenchimento das informações basta pressionar "Create pull request" no canto inferior direito.

12. Após criar o pull request é possível visualizá-lo entrando na aba "Pull requests"

Seu pull request irá aparecer na lista

![](../Documentations/assets/github-web-pull-requests.png)

> Obs: Após a criação do pull request, o seu código ainda não irá para a branch principal, ele passará por uma análise e aprovação manual, assim que for aprovado, o código será mesclado.

> Para mais informações sobre o Git acesse: [GIT Documentation](https://git-scm.com/docs)