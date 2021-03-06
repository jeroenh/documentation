Code Reviews on GitHub
======================

  Given enough eyeballs, all bugs are shallow

  -- Linus' Law

Introduction
------------

In order to increase the code quality within ownCloud, developers are requested
to perform code reviews.  As we are now heavily using the GitHub platform these
code review shall take place on GitHub as well.

Precondition
------------

From now on no direct commits/pushes to master or any of the stable branches are
allowed in general.  **Every code** change - **even one liners** - have to be
reviewed!

How will it work?
-----------------

#. A developer will submit his changes on GitHub via a pull request.
   `GitHub:help - using pull requests`_ #. Within the pull request the developer
   could already name other developers (using @GitHubusername) and ask them for
   review.
#. Other developers (either named or at free will) have a look at the changes
   and are welcome to write comments within the comment field.  #. In case the
   reviewer is okay with the changes and thinks all his comments and suggestions
   have been take into account a :+1 on the comment will signal a positive
   review.
#. Before a pull request will be merged into master or the corresponding
   branch at least 2 reviewers need to give :+1 score.
#. Our `continuous integration server`_ will give an additional indicator for
   the quality of the pull rquest.

Examples
--------

These are two examples that are considered to be good examples of how pull
requests should be handled

* https://github.com/owncloud/core/pull/121
* https://github.com/owncloud/core/pull/146

Questions?
----------

Feel free to drop a line on the `mailing list`_ or join us on `IRC`_.

.. _core repository: https://GitHub.com/owncloud/core
.. _GitHub:help - using pull requests: https://help.GitHub.com/articles/using-pull-requests
.. _continuous integration server: https://ci.tmit.eu/
.. _mailing list: https://mail.kde.org/mailman/listinfo/owncloud
.. _IRC: http://webchat.freenode.net/?channels=owncloud-dev
