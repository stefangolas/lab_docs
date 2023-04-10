.. _contributing:

Contributing
-------------------------------------------------

This guide will walk you through the steps of cloning a repository, making changes, and creating a pull request to merge into the main repo.

Cloning the Repository
~~~~~~~~~~~~~~~~~~~~~~

#. Open your terminal.
#. Navigate to the directory where you want to clone the repository.
#. Run the following command:

   ::

       $ git clone https://github.com/stefangolas/lab_docs.git


Making Changes
~~~~~~~~~~~~~~

1. Once you have cloned the repository, navigate to the local copy of the repository using your terminal.
2. Add your change
3. Add the changes to the staging area by running the following command:

   ::

       $ git add .

4. Commit the changes by running the following command:

   ::

       $ git commit -m "Your commit message goes here"

   Replace ``Your commit message goes here`` with a short description of the changes you made.

Creating a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~

1. Push your changes to your forked repository by running the following command:

   ::

       $ git push origin main

   Replace ``main`` with the name of the branch that you made your changes on if not the main branch.

2. Navigate to your forked repository on GitHub and click on the **New pull request** button.
3. Select the appropriate base branch and compare branch for your pull request.
4. Add a description of your changes and click on the **Create pull request** button.



