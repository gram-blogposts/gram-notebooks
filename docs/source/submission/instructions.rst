Submitting your notebook
==============================

If you have a notebook that you would like to submit to the repository, please follow the steps below.

Fork the Repository
----------------------------

First, you need to have a copy of the repository under your GitHub account. We trust the reviewers to not pay attention to the author of the PR, but to the content of the PR.
You can achieve this by forking the repository.

**Fork the Repository** 
  1. Go to the GitHub page of the repository.
  2. Click on the **Fork** button, usually found at the top right of the page. This creates a copy of the repository in your GitHub account.


Create a New Branch
-------------------

Create a branch on your local machine to isolate your changes:

.. code-block:: bash

    git checkout -b your-branch-name

Replace ``your-branch-name`` with a name relevant to the notebook you are submitting.

Make Your Changes
-----------------

Add your notebook under the ``notebooks`` folder. After making changes, stage and commit them:

.. code-block:: bash

    git add .
    git commit -m "Add a descriptive commit message here"

Push Your Changes
-----------------

After committing your changes, push the branch to your GitHub repository:

.. code-block:: bash

    git push origin your-branch-name

Create a Pull Request
---------------------

1. Go to your repository on GitHub.
2. You'll often see a "Compare & pull request" button. Click on it.
3. Ensure the base repository is set to the original repository you cloned or forked from and the base branch is ``master``.
4. Select your repository and branch from the "head repository" and "compare" dropdowns.
5. Enter a title and description for your pull request.
6. Click **Create pull request**.

Link your Pull Request to OpenReview
----------------------

Once you have submitted your pull request, you can use the URL to submit it to the OpenReview platform. 

Additional Information
----------------------

You can also submit your work as a Google Collab notebook. In that case, create a short jupyter notebook and link your Collab notebook in your `.ipynb` file. 
If you have any questions, feel free to reach out at: `organizers AT gram-workshop DOT org <organizers@gram-workshop.org>`_.