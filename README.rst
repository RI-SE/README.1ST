Where am I?
===========

This is the official GitHub organization for `RISE (Research Institutes of Sweden) <https://www.ri.se/>`_.

If you are looking for any specific repositories, please visit the member, team or project pages.

If you are a current or former employee and would like to be added, removed or have questions please contact the author of this document (preferably via company email).
If you are already a member of this organization, make your membership public `on this page <https://github.com/orgs/RI-SE/people>`_ to see the membership badge.




Guidelines
==========

If you plan to publish your work here, please make sure you comply with the following rules:

Do
--

- Create repositories under your own page or as a part of team or a project.

- Ensure your repositories always contain the minimum required files: .gitignore, LICENSE and README (we recommend README.rst)

- Always follow the RISE code of conduct and the `GitHub Community Guidelines <https://help.github.com/en/articles/github-community-guidelines>`_

- Make repositories private if needed


Do not
------

- Never upload sensitive or secret information (e.g. patent applications, cryptographic keys) to Github, not even to a private repository

- Do not place repositories directly under the organization. Use your own page, teams or projects

- Do not include software created by other people in your code without including
  a reference and the original license

  - Verify that their license is not "infecting" your code


Recommendations
===============

For easier collaboration when using git, please consider the following additional recommendations:

Do
--

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
------

- Do not break the build

  - Do not commit changes that fail to build

  - Do not have a build process that requires manual work

  - Do not reference or use files outside the repository (e.g. files on your personal laptop)

- Do not break git

  - Once published, do not alter the code history (there may be some exceptions)

  - Do not include large files, auto-generated files, backup and junk files

  - Do not artificially inflate the commit (e.g. by changing the indentation)

