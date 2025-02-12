---
title: Closing a pull request
intro: 'You may choose to *close* a pull request without [merging it into the upstream branch](/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request). This can be handy if the changes proposed in the branch are no longer needed, or if another solution has been proposed in another branch.'
redirect_from:
  - /github/collaborating-with-issues-and-pull-requests/incorporating-changes-from-a-pull-request/closing-a-pull-request
  - /articles/closing-a-pull-request
  - /github/collaborating-with-issues-and-pull-requests/closing-a-pull-request
  - /github/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/closing-a-pull-request
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Pull requests
---
{% tip %}

**Tip**: If you opened a pull request with the wrong base branch, rather than closing it out and opening a new one, you can instead change the base branch. For more information, see "[AUTOTITLE](/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-base-branch-of-a-pull-request)."

{% endtip %}

{% data reusables.repositories.sidebar-pr %}
2. In the "Pull Requests" list, click the pull request you'd like to close.
3. At the bottom of the pull request, below the comment box, click **Close pull request**.
  ![The close Pull Request button](/assets/images/help/pull_requests/pullrequest-closebutton.png)
4. Optionally, [delete the branch](/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/deleting-and-restoring-branches-in-a-pull-request). This keeps the list of branches in your repository tidy.
