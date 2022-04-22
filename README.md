# Cloudback Issue Tracker

User-reported issues for Cloudback. Need a new feature? Want to submit a bug report? You are at the right place!

- [Create a feature request](https://github.com/cloudback/issue-tracker/issues/new?template=feature_request.md)
- [Submit a new bug](https://github.com/cloudback/issue-tracker/issues/new?template=bug_report.md)

# What is Cloudback

Cloudback is the [cloud backup](https://en.wikipedia.org/wiki/Remote_backup_service) service for [GitHub repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-repositories). 

The main feature is the support of [various backup storages](https://docs.github.com/features/various-backup-storages). When user storage is configured we **do not store backup archives** inside Cloudback infrastructure at all. All archives are put into your storage. In case you don't have your own storage there is still an option to use our internal storage called `Cloudback`.

![github-repo-backup](https://user-images.githubusercontent.com/6689884/142473939-c5046e41-6bbb-43a3-8353-42c4c0fe204f.png)
