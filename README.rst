Where am I?
===========

This is the official GitHub organization for `RISE Research Institutes of Sweden <https://www.ri.se/>`_.

Here you find a collection of repositories that will be maintained for the foreseeable future, i.e., repositories with a a maintenance plan for at least 10 years. The software contained in these repositories all have expected lifetimes that go beyond individual research projects. Examples include mature demonstrators, software that allows external replications of research studies, and projects that are of considerable interest to a wider open-source software community.

If you are looking for any specific repositories that do not adhere to any long-term maintenance plans, you can probably find them on pages of individual teams, projects, or listed under their lead developers.

Guidelines for RISE employees
==========

If you are a current or former employee and would like to be added, removed or have questions please contact our github administrators or RISE IT. If you are already a member of this organization, make your membership public `on this page <https://github.com/orgs/RI-SE/people>`_ to see the membership badge.

Note that most software development projects managed by RISE shall **not** be hosted directly under this organization. This is not the right place for master thesis projects, small proofs-of-concept, and general prototype development. The repositories hosted here shall all be development projects based on industry best practice in terms of quality assurance and governance.
If you plan to make open-source software available as part of your RISE projects, please make sure you comply with the following rules:

For repositories with a long-term maintenance plan
---------------

Do

- Clearly state the purpose of the repository and clarify that the software will be maintained for the foreseeable future, i.e., longer than the duration of any individual research projects.

- Specify a line organization (i.e., a business unit) that will maintain the repository. Ensure that the unit manager commits to the maintenance plan.

- Apply best practices for the development, e.g., follow code conventions, provide test cases, use continuous integration, and document your software.

- Ensure that the software is made available using a RISE compliant open-source software license.

- Ensure the repository contains the minimum required files: .gitignore, LICENSE and README

- Follow the RISE code of conduct and the `GitHub Community Guidelines <https://help.github.com/en/articles/github-community-guidelines>`_

For repositories that do not meet the strict requirements of a long-term maintenance plan
---------------

Do

- Create repositories under your own page, a team or a project.

- Ensure your repositories always contain the minimum required files: .gitignore, LICENSE and README (we recommend README.rst)

- Always follow the RISE code of conduct and the `GitHub Community Guidelines <https://help.github.com/en/articles/github-community-guidelines>`_

- Make repositories private if needed

For any repository, under this organization or elsewhere
---------------

Do not

- Upload sensitive or secret information (e.g., patent applications, cryptographic keys) to GitHub, not even to a private repository

- Do not include software created by other people in your code without including a reference and the original license

  - Verify that their license is not "infecting" your code

Recommendations
===============

For easier collaboration when using git, please consider the following additional recommendations:

Do

- Read the `Git Book <https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository>`_ to familiarize yourself with the Git workflow and best practices

- Ensure different stages of project are identifiable in the source code

  - `Commit changes often <https://blog.codinghorror.com/check-in-early-check-in-often/>`_

  - Mark special milestones (e.g. releases, experiments) using `tags <https://git-scm.com/book/en/v2/Git-Basics-Tagging>`_ or similar


- Make it more accessible

  - Use `reStructuredText <http://docutils.sourceforge.net/docs/user/rst/quickref.html>`_ for text files (e.g. README.rst instead of README)

  - Use the same coding and indentation style everywhere

    - we recommend `Linux Kernel Coding Style <https://www.kernel.org/doc/Documentation/process/coding-style.rst>`_ for C/C++ projects

    - we recommend `Oracle Code Conventions <http://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html>`_ for Java projects

  - Provide guidelines on how to set up the development environment (e.g. apt commands for Ubuntu/Debian)

    - Alternatively, provide a build machine (e.g. Vagrant or Docker scripts)

  - Keep the documentation in the docs/ folder

  - Use at most two different programming languages in the same project

  - If applicable, provide deployment scripts

- Make it more robust

  - Provide automatic unit tests

  - Use the issue system for registering and managing bugs

Do not

- Do not break the build

  - Do not commit changes that fail to build

  - Do not have a build process that requires manual work

  - Do not reference or use files outside the repository (e.g. files on your personal laptop)

- Do not break git

  - Once published, do not alter the code history (there may be some exceptions)

  - Do not include large files, auto-generated files, backup and junk files

  - Do not artificially inflate the commit (e.g. by changing the indentation)
