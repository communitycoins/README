# CONTRIBUTING

This Communitycoins hub/library operates on [Forgejo](https://forgejo.org/), an open source Gitea fork. The library serves to maintain and collect multiple projects that are releated to Communitycoins. 

The main structure in Forgejo is an `Organisation`. Organisations are not technically interconnected, but each contains a set of interconnected `repositories`. A `repository` is a hierarchical set of `files`, usually to bundle a software project. One special file (README.md) describes the purpose of the repository contents.

Normaly there is no organisation of `Organisations` and only maintainers can add organisations. For clarity we maintain a single `Organisation` named [Communitycoins](/Communitycoins). It contains one `repository` named [README](https://git.communitycoins.org/Communitycoins/README) to bundle directions for readers and those that want to contribute.

Since a software project is never finished Forgejo serves to maintain project-`issues`, -`branches`, -`tags` and -`releases`. Before anything changes you need to tell us why. Your answer becomes an `issue`. Before you start to work on an `issue` or a set of issues you need to create a `branch`, which is a named copy of all the files in a `repository`. Once the issues that caused a branch are finished the changes can be 'pulled' back in the original through a `pull request`. That is the way a repository changes. After a change it is possible to define a `tag`. Through tags it is possible to rewind the project to a previous state or to declare a `release`.

Forgejo also uses the name `project` which is confusing because a Forgejo-project is not a repository but a set of issues. So you cannot define a forgeo-project when there are no issues. A Forgejo `project` is a management board to collect and manage issues within an `organisation`.

## Continuity

All repositories are standard Git repositories.
Any team may mirror any repository at any time.

In the event that git.communitycoins.org becomes unavailable,
the project continues from existing mirrors.


