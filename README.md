behat-pool
==========

What for?
---------
The idea here is to store a database of features/contexts for [Behat](https://github.com/Behat/). When we've got new tests to do, we can check on this pool to avoid reinventing the wheel.

How?
----
The folder structure helps you to know quickly where the code come from:
behat-pool
└── vendor
    └── repo or project's name
        ├── features
        └── README.md

README file inside each repo's folder contains infos about where the code were grabbed. When you browse folders, last log's commit message indicate the sha1 of the last commit from the source's repo.
