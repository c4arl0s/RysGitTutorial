# RysGitTutorial

Ry's Git Tutorial

1. [Introduction](https://github.com/c4arl0s/RysGitTutorial#1-introduction)
2. [The basics](https://github.com/c4arl0s/RysGitTutorial#2-the-basics)
3. [Undoing Changes](https://github.com/c4arl0s/RysGitTutorial#3-undoing-changes)
4. [Branches I](https://github.com/c4arl0s/RysGitTutorial#4-branches-i)
5. [Branches II](https://github.com/c4arl0s/RysGitTutorial#5-branches-ii)
6. [Rebasing](https://github.com/c4arl0s/RysGitTutorial#6-rebasing)	
7. [Rewriting History](https://github.com/c4arl0s/RysGitTutorial#7-rewriting-history)
8. [Remotes](https://github.com/c4arl0s/RysGitTutorial#8-remotes)
9. [Centralized Workflows](https://github.com/c4arl0s/RysGitTutorial#9-centralized-workflows)
10. [Distributed Workflows](https://github.com/c4arl0s/RysGitTutorial#10-distributed-workflows)
11. [Patch Workflows](https://github.com/c4arl0s/RysGitTutorial#11-patch-workflows)
12. [Tips and Tricks](https://github.com/c4arl0s/RysGitTutorial#12-tips-and-tricks)
13. [Plumbing](https://github.com/c4arl0s/RysGitTutorial#13-plumbing)

Ry's Git Tutorial

# 1. [Introduction](https://github.com/c4arl0s/RysGitTutorial#1-introduction)
 * [A Brief History of Revision Control](https://github.com/c4arl0s/RysGitTutorial#-a-brief-history-of-revision-control)
 * [The birth of Git](https://github.com/c4arl0s/RysGitTutorial#-the-birth-of-git)
 * [Installation](https://github.com/c4arl0s/RysGitTutorial#-installation)
 * [Get Ready](https://github.com/c4arl0s/RysGitTutorial#-get-ready)
# 2. [The basics](https://github.com/c4arl0s/RysGitTutorial#2-the-basics)
 * [Create the example Site](https://github.com/c4arl0s/RysGitTutorial#-create-the-example-site)
 * [Initialize the Git Repository](https://github.com/c4arl0s/RysGitTutorial#-initialize-the-git-repository)
 * [View the repository status](https://github.com/c4arl0s/RysGitTutorial#-view-the-repository-status)
 * [Stage a snapshot](https://github.com/c4arl0s/RysGitTutorial#-stage-a-snapshot)
 * [Commit the Snapshot](https://github.com/c4arl0s/RysGitTutorial#-commit-the-snapshot)
 * [View the repository History](https://github.com/c4arl0s/RysGitTutorial#-view-the-repository-history)
 * [Configure Git](https://github.com/c4arl0s/RysGitTutorial#-configure-git)
 * [Create New HTML files](https://github.com/c4arl0s/RysGitTutorial#-create-new-html-files)
 * [Stage the New Files](https://github.com/c4arl0s/RysGitTutorial#-stage-the-new-files)
 * [Commit The new Files](https://github.com/c4arl0s/RysGitTutorial#-commit-the-new-files)
 * [Modify the HTML Pages](https://github.com/c4arl0s/RysGitTutorial#-modify-the-html-pages)
 * [Stage and Commit the Snapshot](https://github.com/c4arl0s/RysGitTutorial#-stage-and-commit-the-snapshot)
 * [Explore the Repository](https://github.com/c4arl0s/RysGitTutorial#-explore-the-repository)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference)
# 3. [Undoing Changes](https://github.com/c4arl0s/RysGitTutorial#3-undoing-changes)
 * [Display Commit Checksums](https://github.com/c4arl0s/RysGitTutorial#-display-commit-checksums)
 * [View an Old Version](https://github.com/c4arl0s/RysGitTutorial#-view-an-old-version)
 * [View an Older Version](https://github.com/c4arl0s/RysGitTutorial#-view-an-older-version)
 * [Return to current version](https://github.com/c4arl0s/RysGitTutorial#-return-to-current-version)
 * [Tag a Release](https://github.com/c4arl0s/RysGitTutorial#-tag-a-release)
 * [Try a Crazy Experiment](https://github.com/c4arl0s/RysGitTutorial#-try-a-crazy-experiment)
 * [Stage and Commit the Snapshot](https://github.com/c4arl0s/RysGitTutorial#-stage-and-commit-the-snapshot-1)
 * [View the Stable Commit]()
 * [Undo Committed Changes](https://github.com/c4arl0s/RysGitTutorial#-undo-committed-changes)
 * [Start a Smaller Experiment](https://github.com/c4arl0s/RysGitTutorial#-start-a-smaller-experiment)
 * [Undo Uncommitted Changes](https://github.com/c4arl0s/RysGitTutorial#-undo-uncommitted-changes)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-1)
 * [Quick References](https://github.com/c4arl0s/RysGitTutorial#-quick-references)
# 4. [Branches I](https://github.com/c4arl0s/RysGitTutorial#4-branches-i)
 * [View existing Branches](https://github.com/c4arl0s/RysGitTutorial#-view-existing-branches)
 * [Checkout the Crazy Experiment](https://github.com/c4arl0s/RysGitTutorial#-checkout-the-crazy-experiment)
 * [Create a New Branch](https://github.com/c4arl0s/RysGitTutorial#-create-a-new-branch)
 * [Make a Rainbow](https://github.com/c4arl0s/RysGitTutorial#-make-a-rainbow)
 * [Stage and Commit the Rainbow](https://github.com/c4arl0s/RysGitTutorial#-stage-and-commit-the-rainbow)
 * [Rename the Rainbow](https://github.com/c4arl0s/RysGitTutorial#-rename-the-rainbow)
 * [Return to the Master Branch](https://github.com/c4arl0s/RysGitTutorial#-return-to-the-master-branch)
 * [Create a CSS Branch](https://github.com/c4arl0s/RysGitTutorial#-create-a-css-branch)
 * [Add a CSS Stylesheet](https://github.com/c4arl0s/RysGitTutorial#-add-a-css-stylesheet)
 * [Link the Stylesheet](https://github.com/c4arl0s/RysGitTutorial#-link-the-stylesheet)
 * [Return to the Master Branch (again)](https://github.com/c4arl0s/RysGitTutorial#-return-to-the-master-branch-again)
 * [Merge the CSS Branch](https://github.com/c4arl0s/RysGitTutorial#-merge-the-css-branch)
 * [Delete the CSS Branch](https://github.com/c4arl0s/RysGitTutorial#-delete-the-css-branch)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-2)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference-1)
# 5. [Branches II](https://github.com/c4arl0s/RysGitTutorial#5-branches-ii)
 * [Continue the Crazy Experiment](https://github.com/c4arl0s/RysGitTutorial#-continue-the-crazy-experiment)
 * [Merge the CSS Updates](https://github.com/c4arl0s/RysGitTutorial#-merge-the-css-updates)
 * [Style the Rainbow Page](https://github.com/c4arl0s/RysGitTutorial#-style-the-rainbow-page)
 * [Link to the Rainbow Page](https://github.com/c4arl0s/RysGitTutorial#-link-to-the-rainbow-page)
 * [Fork an Alternative Rainbow](https://github.com/c4arl0s/RysGitTutorial#-fork-an-alternative-rainbow)
 * [Change the Rainbow](https://github.com/c4arl0s/RysGitTutorial#-change-the-rainbow)
 * [Emergency Update](https://github.com/c4arl0s/RysGitTutorial#-emergency-update)
 * [Publish the News Hotfix](https://github.com/c4arl0s/RysGitTutorial#-publish-the-news-hotfix)
 * [Complete the Crazy Experiment](https://github.com/c4arl0s/RysGitTutorial#-complete-the-crazy-experiment)
 * [Publish the Crazy Experiment](https://github.com/c4arl0s/RysGitTutorial#-publish-the-crazy-experiment)
 * [Resolve the Merge Conflicts](https://github.com/c4arl0s/RysGitTutorial#-resolve-the-merge-conflicts)
 * [Cleanup the feature Branches](https://github.com/c4arl0s/RysGitTutorial#-cleanup-the-feature-branches)
 * [Rename Branches Local and Remote]()
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-3)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference-2)
# 6. [Rebasing](https://github.com/c4arl0s/RysGitTutorial#6-rebasing)	
 * [Create an About Section](https://github.com/c4arl0s/RysGitTutorial#-create-an-about-section)
 * [Add an About Page](https://github.com/c4arl0s/RysGitTutorial#-add-an-about-page)
 * [Another emergency update!](https://github.com/c4arl0s/RysGitTutorial#-another-emergency-update)
 * [Publish News Hotfix](https://github.com/c4arl0s/RysGitTutorial#-publish-news-hotfix)
 * [Rebase the about Branch](https://github.com/c4arl0s/RysGitTutorial#-rebase-the-about-branch)
 * [Add a Personal Bio](https://github.com/c4arl0s/RysGitTutorial#-add-a-personal-bio)
 * [Add Dummy Page for Mary](https://github.com/c4arl0s/RysGitTutorial#-add-dummy-page-for-mary)
 * [Link to the About Section](https://github.com/c4arl0s/RysGitTutorial#-link-to-the-about-section)
 * [Clean up the Commit History](https://github.com/c4arl0s/RysGitTutorial#-clean-up-the-commit-history)
 * [Stop to Amend a Commit](https://github.com/c4arl0s/RysGitTutorial#-stop-to-amend-a-commit)
 * [Continue the Interactive Rebase](https://github.com/c4arl0s/RysGitTutorial#-continue-the-interactive-rebase)
 * [Publish the About Section](https://github.com/c4arl0s/RysGitTutorial#-publish-the-about-section)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-4)
 * [Quick References](https://github.com/c4arl0s/RysGitTutorial#-quick-references-1)
# 7. [Rewriting History](https://github.com/c4arl0s/RysGitTutorial#7-rewriting-history)
 * [Create the Red Page](https://github.com/c4arl0s/RysGitTutorial#-create-the-red-page)
 * [Create the Yellow Page](https://github.com/c4arl0s/RysGitTutorial#-create-the-yellow-page)
 * [Link and Commit the New Pages](https://github.com/c4arl0s/RysGitTutorial#-link-and-commit-the-new-pages)
 * [Create and commit the Green Page](https://github.com/c4arl0s/RysGitTutorial#-create-and-commit-the-green-page)
 * [Begin an Interactive Rebase](https://github.com/c4arl0s/RysGitTutorial#-begin-an-interactive-rebase)
 * [Undo the Generic Commit](https://github.com/c4arl0s/RysGitTutorial#-undo-the-generic-commit)
 * [Split the Generic Commit](https://github.com/c4arl0s/RysGitTutorial#-split-the-generic-commit)
 * [Remove the last Commit](https://github.com/c4arl0s/RysGitTutorial#-remove-the-last-commit)
 * [Open the Reflog](https://github.com/c4arl0s/RysGitTutorial#-open-the-reflog)
 * [Revive the Lost Commit](https://github.com/c4arl0s/RysGitTutorial#-revive-the-lost-commit)
 * [Filter the Log History](https://github.com/c4arl0s/RysGitTutorial#-filter-the-log-history)
 * [Merge in the Revived Branch](https://github.com/c4arl0s/RysGitTutorial#-merge-in-the-revived-branch)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-5)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference-3)
# 8. [Remotes](https://github.com/c4arl0s/RysGitTutorial#8-remotes-1)
 * [Clone the Repository (Mary)](https://github.com/c4arl0s/RysGitTutorial#-clone-the-repository-mary)
 * [Configure The Repository (Mary)](https://github.com/c4arl0s/RysGitTutorial#-configure-the-repository-mary)
 * [Start Mary's Day (Mary)](https://github.com/c4arl0s/RysGitTutorial#-start-marys-day-mary)
 * [Create Mary's Bio Page](https://github.com/c4arl0s/RysGitTutorial#-create-marys-bio-page)
 * [Publish the Bio Page (Mary)](https://github.com/c4arl0s/RysGitTutorial#-publish-the-bio-page-mary)
 * [View Remote Repositories (Mary)](https://github.com/c4arl0s/RysGitTutorial#-view-remote-repositories-mary)
 * [Return to Your Repository (you)](https://github.com/c4arl0s/RysGitTutorial#-return-to-your-repository-you)
 * [Add Mary as a Remote (you)](https://github.com/c4arl0s/RysGitTutorial#-add-mary-as-a-remote-you)
 * [Fetch Mary's Branches (you)](https://github.com/c4arl0s/RysGitTutorial#-fetch-marys-branches-you)
 * [Check out a Remote Branch](https://github.com/c4arl0s/RysGitTutorial#-check-out-a-remote-branch)
 * [Find Mary's Changes](https://github.com/c4arl0s/RysGitTutorial#-find-marys-changes)
 * [Merge Mary's Changes](https://github.com/c4arl0s/RysGitTutorial#-merge-marys-changes)
 * [Push a Dummy Branch](https://github.com/c4arl0s/RysGitTutorial#-push-a-dummy-branch)
 * [Push a New Tag](https://github.com/c4arl0s/RysGitTutorial#-push-a-new-tag)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-6)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference-4)
# 9. [Centralized Workflows](https://github.com/c4arl0s/RysGitTutorial#9-centralized-workflows-1)
 * [Create a Bare Repository (Central)](https://github.com/c4arl0s/RysGitTutorial#-create-a-bare-repository-central)
 * [Update Remotes (Mary and You)](https://github.com/c4arl0s/RysGitTutorial#-update-remotes-mary-and-you)
 * [Push the Master Branch](https://github.com/c4arl0s/RysGitTutorial#-push-the-master-branch)
 * [Add News Update (You)](https://github.com/c4arl0s/RysGitTutorial#-add-news-update-you)
 * [Publish the News Item (You)](https://github.com/c4arl0s/RysGitTutorial#-publish-the-news-item-you)
 * [Update CSS Styles (Mary)](https://github.com/c4arl0s/RysGitTutorial#-update-css-styles-mary)
 * [Update another CSS Style](https://github.com/c4arl0s/RysGitTutorial#-update-another-css-style)
 * [Clean up Before Publishing (Mary](https://github.com/c4arl0s/RysGitTutorial#-clean-up-before-publishing-mary)
 * [Publish CSS Changes (Mary](https://github.com/c4arl0s/RysGitTutorial#-publish-css-changes-mary)
 * [Pull in Changes (Mary)](https://github.com/c4arl0s/RysGitTutorial#-pull-in-changes-mary)
 * [Pull in Changes (you)](https://github.com/c4arl0s/RysGitTutorial#-pull-in-changes-you)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-7)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference-5)
# 10. [Distributed Workflows](https://github.com/c4arl0s/RysGitTutorial#10-distributed-workflows-1)
 * [Create a Bitbucket Account](https://github.com/c4arl0s/RysGitTutorial#-create-a-bitbucket-account)
 * [Create a Public Repository (you)](https://github.com/c4arl0s/RysGitTutorial#-create-a-public-repository-you)
 * [Push to a Public Repository (you)](https://github.com/c4arl0s/RysGitTutorial#-push-to-a-public-repository-you)
 * [Browse the Public Repository (you)](https://github.com/c4arl0s/RysGitTutorial#-browse-the-public-repository-you)
 * [Clone the Repository (John](https://github.com/c4arl0s/RysGitTutorial#-clone-the-repository-john)
 * [Add the Pink Page (John)](https://github.com/c4arl0s/RysGitTutorial#-add-the-pink-page-john)
 * [Publish the Pink Page (John)](https://github.com/c4arl0s/RysGitTutorial#-publish-the-pink-page-john)
 * [View John's Contributions (you)](https://github.com/c4arl0s/RysGitTutorial#-view-johns-contributions-you)
 * [Integrate John's Contributions (you)](https://github.com/c4arl0s/RysGitTutorial#-integrate-johns-contributions-you)
 * [Publish John's Contributions (you)](https://github.com/c4arl0s/RysGitTutorial#-publish-johns-contributions-you)
 * [Update Mary's Repository (Mary)](https://github.com/c4arl0s/RysGitTutorial#-update-marys-repository-mary)
 * [Update John's Repository (John)](https://github.com/c4arl0s/RysGitTutorial#-update-johns-repository-john)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-8)
# 11. [Patch Workflows](https://github.com/c4arl0s/RysGitTutorial#11-patch-workflows-1)
 * [Change the Pink Page (Mary)](https://github.com/c4arl0s/RysGitTutorial#-change-the-pink-page-mary)
 * [Create a Patch](https://github.com/c4arl0s/RysGitTutorial#-create-a-patch)
 * [Add a Pink Block (Mary)](https://github.com/c4arl0s/RysGitTutorial#-add-a-pink-block-mary)
 * [Create Patch of Entire Branch (Mary)](https://github.com/c4arl0s/RysGitTutorial#-create-patch-of-entire-branch-mary)
 * [Mail the Patches (Mary)](https://github.com/c4arl0s/RysGitTutorial#-mail-the-patches-mary)
 * [Apply the Patches (you)](https://github.com/c4arl0s/RysGitTutorial#-apply-the-patches-you)
 * [Integrate The Patches (you)](https://github.com/c4arl0s/RysGitTutorial#-integrate-the-patches-you)
 * [Update Mary's Repository (Mary)](https://github.com/c4arl0s/RysGitTutorial#-update-marys-repository-mary-1)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-9)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference-5)
# 12. [Tips and Tricks](https://github.com/c4arl0s/RysGitTutorial#12-tips-and-tricks-1)
 * [Archive The repository](https://github.com/c4arl0s/RysGitTutorial#-archive-the-repository)
 * [Bundle the Repository](https://github.com/c4arl0s/RysGitTutorial#-bundle-the-repository)
 * [Ignore a File](https://github.com/c4arl0s/RysGitTutorial#-ignore-a-file)
 * [Stash Uncommitted Changes](https://github.com/c4arl0s/RysGitTutorial#-stash-uncommitted-changes)
 * [Hook into Git's internals](https://github.com/c4arl0s/RysGitTutorial#-hook-into-gits-internals)
 * [View Diffs Between commits](https://github.com/c4arl0s/RysGitTutorial#-view-diffs-between-commits)
 * [Reset and checkout files](https://github.com/c4arl0s/RysGitTutorial#-reset-and-checkout-files)
 * [Aliases and Other Configurations](https://github.com/c4arl0s/RysGitTutorial#-aliases-and-other-configurations)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-10)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference-6)
# 13. [Plumbing](https://github.com/c4arl0s/RysGitTutorial#13-plumbing-1)
 * [Examine Commit Details](https://github.com/c4arl0s/RysGitTutorial#-examine-commit-details)	
 * [Examine a tree](https://github.com/c4arl0s/RysGitTutorial#-examine-a-tree)
 * [Examine a Blob](https://github.com/c4arl0s/RysGitTutorial#-examine-a-blob)
 * [Examine a Tag](https://github.com/c4arl0s/RysGitTutorial#-examine-a-tag)
 * [Inspect Git's Branch Representation](https://github.com/c4arl0s/RysGitTutorial#-inspect-gits-branch-representation)
 * [Explore the Object Database](https://github.com/c4arl0s/RysGitTutorial#-explore-the-object-database)
 * [Collect the Garbage](https://github.com/c4arl0s/RysGitTutorial#-collect-the-garbage)
 * [Add Files to the index](https://github.com/c4arl0s/RysGitTutorial#-add-files-to-the-index)
 * [Store the Index in the Database](https://github.com/c4arl0s/RysGitTutorial#-store-the-index-in-the-database)
 * [Create a Commit Object](https://github.com/c4arl0s/RysGitTutorial#-create-a-commit-object)
 * [Update HEAD](https://github.com/c4arl0s/RysGitTutorial#-update-head)
 * [Conclusion](https://github.com/c4arl0s/RysGitTutorial#-conclusion-11)
 * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#-quick-reference-7)


Ry's Git Tutorial

# 1. [Introduction](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

- Git is a version control system (VCS) created for a single task: managing changes to your files.

# 	* [A Brief History of Revision Control](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [The birth of Git](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Installation](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Get Ready](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

# 2. [The basics](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

- This module explores the fundamental Git workflow: creating a repository, staging and committing snapshots, configuring options, and viewing the state of a repository.

# 	* [Create the example Site](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>A Colorful Website</title>
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #07F">A Colorful Website</h1>
  <p>This is a website about color!</p>    
  
  <h2 style="color: #C00">News</h2>
  <ul>
    <li>Nothing going on (yet)</li>
  </ul>
</body>
</html>
```

# 	* [Initialize the Git Repository](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
cd /Users/carlossantiagocruz/SWIFT-PROGRAMMING/RysGitTutorial
```

- then initialize

```console
$ git init
```

- output

```console
Initialized empty Git repository in /Users/carlossantiagocruz/Documents/SWIFT-PROGRAMMING/RysGitTutorialRepository/.git/
```

# 	* [View the repository status](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git status
```

```console
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.html

nothing added to commit but untracked files present (use "git add" to track)
```

- Git does not automatically track files because there are often project files that we don't want to keep under revision control.

# 	* [Stage a snapshot](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

- tell git to start tracking index.html

```console
$ git add index.html
```

```console
$ git status
```

- output

```console
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   index.html

```

- A snapshot represents the state of your project at a given point in time.
- Git's term for creating a snapshot is called staging
- Staging give us the opportunity to group related changes into distinct snapshots.

# 	* [Commit the Snapshot](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git commit
```
![Screen Shot 2020-05-22 at 12 55 58](https://user-images.githubusercontent.com/24994818/82695901-9b39ba80-9c2b-11ea-9542-d3499c0dc735.png)

# 	* [View the repository History](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git log
```

- output

```console
commit 6a442fcc4ab51362713f09ed5eadc7af767db833
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 12:54:21 2020 -0500

    Create index page for the message
```

# 	* [Configure Git](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git config --global user.name "your name"
$ git config --global user.email your.email@example.com
```

[read book if you want more information]

# 	* [Create New HTML files](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

- orange.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>The Orange Page</title>
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #F90">The Orange Page</h1>
  <p>Orange is so great it has a
  <span style="color: #F90">fruit</span> named after it.</p>
</body>
</html>

```

- blue.html

```console
<!DOCTYPE html>
<html lang="en">
<head>
  <title>The Blue Page</title>
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #00F">The Blue Page</h1>
  <p>Blue is the color of the sky.</p>
</body>
</html>
```

# 	* [Stage the New Files](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git add orange.html blue.html
```

```console
$ git status
```

- output

```console
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   blue.html
	new file:   orange.html

```

![Screen Shot 2020-05-22 at 13 21 50](https://user-images.githubusercontent.com/24994818/82697808-3d0ed680-9c2f-11ea-9c17-f8f3009351dd.png)

# 	* [Commit The new Files](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git commit -m "add blue and orangle html file"
```

![Screen Shot 2020-05-22 at 13 47 10](https://user-images.githubusercontent.com/24994818/82699708-c1af2400-9c32-11ea-800a-1b578fcbcac5.png)

# 	* [Modify the HTML Pages](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

- add this at the end of index.html

```html
<h2>Navigation</h2>
<ul>
  <li style="color: #F90">
    <a href="orange.html">The Orange Page</a>
  </li>
  <li style="color: #00F">
```

- add this at the end of orange.html

```html
<p><a href="index.html">Return to home page</a></p>
```

# 	* [Stage and Commit the Snapshot](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git status
```

- output

```
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.html
	modified:   orange.html

no changes added to commit (use "git add" and/or "git commit -a")
```

-

```console
$ git add index.html orange.html blue.html 
```

- status

```console
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html
	modified:   orange.html

```

- commit 

```console
$ git commit -m "Add navigation links"
[master 453c8a4] Add navigation links
 2 files changed, 10 insertions(+), 1 deletion(-)
```

- Note that the red circle, which represent the current commit, automatically moves forward every time we commit a new snapshot.

![Screen Shot 2020-05-22 at 16 55 24](https://user-images.githubusercontent.com/24994818/82712156-0d6ec700-9c4d-11ea-8dd1-8f705f6996ae.png)

# 	* [Explore the Repository](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git log --oneline
```

- output

```console
453c8a4 Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

- Condensing output to a single line is a great way to get a high-level overview of a repository
- Another useful configuration is to pass a filename to git log:

```console
1047951 t Add blue an orange html files
```

- This display only  the blue.html history.
- Notice that the initial Create index page commit is missing, since blue.html did't exist in that snapshot.


# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

![Screen Shot 2020-05-22 at 17 01 45](https://user-images.githubusercontent.com/24994818/82712586-f086c380-9c4d-11ea-9896-d302b0345e8a.png)

# 	* [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git init
```

```console
$ git status
```

```console
$ git add fileName
```

```console
$ git commit
```

```console
$ git log
```

```console
$ git config --global user.name "nameOfTheUser"
```


# 3. [Undoing Changes](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

- In the last module, we learned how to record versions of a project into a Git repositoru.
- The whole point of maintaining these "safe" copies is peace of mind: should our project suddenly break, we will know that we have easy access to a functional version, and we will be able to pinpoint precisely where the problem was introduced.

- To this end, storing "safe" versions is not much help without the ability to restore them.- Our next task is to learn how to view the previous states of a project, revert back to them, and reset uncommitted changes.

# 	* [Display Commit Checksums](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

- Quick review

```console
$ git log --oneline
```

- output

```console
453c8a4 Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

- git only outputs the first seven characters of the checksum.
- These first few characters effectively serve as a unique ID for each commit.

# 	* [View an Old Version](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git checkout 1047951
```

- output

```console
Note: switching to '1047951'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 1047951 t Add blue an orange html files
```

![Screen Shot 2020-05-22 at 17 19 07](https://user-images.githubusercontent.com/24994818/82713376-60964900-9c50-11ea-81a9-6f1b73ca260d.png)

# 	* [View an Older Version]()

```console
$ git checkout 6a442fc
```

- output

```console
Previous HEAD position was 1047951 t Add blue an orange html files
HEAD is now at 6a442fc Create index page for the message
```

![Screen Shot 2020-05-22 at 17 37 35](https://user-images.githubusercontent.com/24994818/82714202-427e1800-9c53-11ea-8dbe-92ec1f95695b.png)

# 	* [Return to current version]()

```console
$ git checkout master
```

- output

```console
Previous HEAD position was 6a442fc Create index page for the message
Switched to branch 'master'
```

![Screen Shot 2020-05-22 at 17 41 33](https://user-images.githubusercontent.com/24994818/82714291-8244ff80-9c53-11ea-9a67-7949b919670b.png)

# 	* [Tag a Release]()

```console
$ git tag -a v1.0 -m "Stable Version of the website"
```

- print all tags

```console
$ git tag
v1.0
```
# 	* [Try a Crazy Experiment]()

- create crazy.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>A Crazy Experiment</title>
  <meta charset="utf-8" />
</head>
<body>
  <h1>A Crazy Experiment</h1>
  <p>We're trying out a <span style="color: #F0F">crazy</span>
  <span style="color: #06C">experiment</span>!
    
  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

# 	* [Stage and Commit the Snapshot]()

```console
$ git add crazy.html 
```

- commit

```console
$ git commit -m "Add a crazzy experiment"
[master 12e24f0] Add a crazzy experiment
 1 file changed, 14 insertions(+)
 create mode 100644 crazy.html
```

- status

```console
commit 12e24f0c4e03b3c991b287230548d8bdad3882d7
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 20:34:06 2020 -0500

    Add a crazzy experiment

commit 453c8a4db079c3d235e3470754a79a22ea0f0afd
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 16:53:53 2020 -0500

    Add navigation links

commit 1047951bab2636a3bc90682e48d9fb32644da036
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 13:45:14 2020 -0500

    t Add blue an orange html files

commit 6a442fcc4ab51362713f09ed5eadc7af767db833
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 12:54:21 2020 -0500

    Create index page for the message

```
# 	* [View the Stable Commit]()

```console
$ git checkout v1.0
```

- output

```console
HEAD is now at 453c8a4 Add navigation links
```

- go back to master

```console
$ git checkout master
```

- output

```console
Previous HEAD position was 453c8a4 Add navigation links
Switched to branch 'master'
```
# 	* [Undo Committed Changes]()

- We are ready to restore our stable tag by removing the most recent commit.
- Make sure to change the 12e24f0 to the ID to the crazy experiment's commit before running the next command:

```console
$ git revert 12e24f0
```

- This will show you the vim editor with the default message "Revert "Add a crazzy experiment"
- Save and close

```console
$ git revert 12e24f0
Removing crazy.html
[master 3553479] Revert "Add a crazzy experiment"
 1 file changed, 14 deletions(-)
 delete mode 100644 crazy.html
```

- git log

```console
$ git log --oneline
```

- output

```console
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

- Notice that instead of deleting the "crazzy experiment" commit, Git figures out how to undo the changes it contains, the tacks on another commit with the resulting content.
- So, our fifth commit and our third commit represent the exact same snapshot, as shown below.
- Again, Git is designed to never lose history: the fourth snapshot is still accessible, just in case we want to continue developing it.

![Screen Shot 2020-05-22 at 21 15 21](https://user-images.githubusercontent.com/24994818/82719550-605a7580-9c71-11ea-9926-618e5053ab4c.png)

- When using git revert, remember to specify the commit that you want to undo-- not the stable commit that you want to return to.
- It helps to think of this command as saying "undo this commit" rather than "restore this version"

# 	* [Start a Smaller Experiment]()

- Let's try a smaller experiment this time.
- Create dummy.html and leave it as a blank file.
- Then, add a link in the "Navigation Section" of index.html so that it resembles the following.

```html
<h2>Navigation</h2>
<ul>
  <li style="color: #F90">
    <a href="orange.html">The Orange Page</a>
  </li>
  <li style="color: #00F">
	<a href="blue.html">The Blue Page</a>
 </li>
 <li>
  <a href="dummy.html">The Dummy Page</a>
  </li>
</ul>
```

- In the next section, we are going to abandon this uncommitted experiment. But since the git revert command requires a commit ID to undo, we can't use the method discussed above.

# 	* [Undo Uncommitted Changes]()

- Before we start undoing things, let's take a look at the status of our repository

```console
$ git status
```

- output

```console
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	dummy.html

no changes added to commit (use "git add" and/or "git commit -a")
```

- We have a tracked file and an untracked file that need to be changed. First, we will take care of index.html

```console
$ git reset --hard
```

- output

```console
HEAD is now at 3553479 Revert "Add a crazzy experiment"
```

- This changes all tracked files to match the most recent commit. Note that the --hard flag is what actually updates the file.
- Running git reset without any flags will simply unstage index.html, leaving its contents as is.

```console
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	dummy.html
```

- In either case, git reset only operates on the working directory and the staging area, so our git log history remains unchanged.

* Next, let's remove the dummy.html file.
* Of course, we could manually delete it, but using Git to reset changes eliminates human errors when working with several files in large teams.
- Run the following commands,

```console
$ git clean -f
Removing dummy.html
```

- This will remove all untracked files. With dummy.html gone, git status should now tell us that we have a "clean" working directory, meaning our project matches the most recent commit.

```console
$ git status
On branch master
nothing to commit, working tree clean
```

- **Be careful** with **git reset** and **git clean**. Both operate on the working directory, not on the committed snapshots.
- Unlike **git revert**, they permanently undo changes, so make sure you really want to trash what you are working on before you use them.

	
# 	* [Conclusion]()

![Screen Shot 2020-05-23 at 7 46 49](https://user-images.githubusercontent.com/24994818/82731017-94618500-9cc9-11ea-9d20-5bb40446c1b3.png)

# 	* [Quick References]()

```console
$ git checkout commitID
```

```console
$ git tag -a tagName -m "description"
```

```console
$ git revert commitID
```

```console
$ git reset --hard
```

```console
$ git clean -f
```

```console
$ git reset --hard / git clean -f
```


# 4. [Branches I]()

- Branches are the final component of Git version control.
- This gives us four core elements to work with throughout the rest of this tutorial:

	* The working directory
	* The staged Snapshot
	* Committed Snapshots
	* Development Branches

- In Git, a branch is an independent line of development.
- First, Branches present an error-proof method for incorporating changes from an experiment.
- Second, they let you store all of your experiments in a single directory, which makes it much easier to keep track of them and to share them with others.
- Branches also lend themselves to several standardized workflows for both individual and colavorative development, which will b explored in the latter half of the tutorial.

# 	* [View existing Branches]()

- Lets start our exploration by listing the existingg branches for our project

```console
$ git branch
* master
```

- This will display our one and only branch: * master.
- The master branch is Git's default branch, and the asterisk next to ir tell us that it is currently checked out.
- This means that the most recent snapshot in the master branch resides in the working directory.

![Screen Shot 2020-05-23 at 8 09 49](https://user-images.githubusercontent.com/24994818/82731472-cde7bf80-9ccc-11ea-9029-32deb45c901f.png)

- Notice that since there is only one working directory for each project, only one branch can be checked out at a time.

# 	* [Checkout the Crazy Experiment]()

- The previous module left out some details about ho to checking out previous commits actually works.
- We are now ready to tackle this topic in depth.
- First, we need the checksums of our committed snapshots.

```console
$ git log --oneline
3553479 (HEAD -> master) Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

- Check out the crazy experiment from the last module, remembering to change 

```console
$ git checkout 12e24f0
```

- This command returns a message that says we are in a **detached HEAD state** and that the **HEAD** is git's internal way of indicating the snapshot that is currently checked out.

```console
HEAD detached at 12e24f0
nothing to commit, working tree clean
```

- This means the red circle in each of our history diagrams actually represets Git's HEAD.
- The followin figure shows the state of our repository before and after we checked out and old commit.

![Screen Shot 2020-05-23 at 8 25 18](https://user-images.githubusercontent.com/24994818/82731820-f7094f80-9cce-11ea-99d3-31959c7ce556.png)

- As shown in the "before" diagram, the **HEAD** normally resides on the tip of a development branch, But when we checked out the previous commit, the **HEAD** moved to the middle of the branch.
- We can no longer say we are on the **master** branch since it contains more recent snapshots than the **HEAD**.
- This is reflected in the **git branch** output, which tells us that we are currently on (no branch)

```console
$ git branch
* (HEAD detached at 12e24f0)
  master
```

# 	* [Create a New Branch]()

- We can not add new commits when we are not on a branch, so let's create one now.
- This will take our current working directory and fork it into a new branch.

```console
$ git branch crazy
```

- print all branches

```console
$ git branch
* (HEAD detached at 12e24f0)
  crazy
  master
```

- Note that git branch is a versatile command that can be used to either list branches or create them. 
- However, the above command only creates the crazy branch -It does not check it out.

```console
$ git checkout crazy
Switched to branch 'crazy'
```

- We are now free to experiment in the working directory without disturbing anything in the **master** branch.
- The **crazy** branch is a completely isolated development environment that can be visualized as the following:

![Screen Shot 2020-05-23 at 8 47 17](https://user-images.githubusercontent.com/24994818/82732309-08a02680-9cd2-11ea-9a98-de50000acc64.png)

- Right now, the crazy branch, **HEAD**, and working directory are the exact same as the fourth commit.
- But as soon as we add another snapshot, we will see a fork in our project history.

# 	* [Make a Rainbow]()

- We will continue developing our crazy experiment by changing **crazy.html** to the following.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>A Crazy Experiment</title>
  <meta charset="utf-8" />
</head>
<body>
  <h1>A Crazy Experiment</h1>
	<p>Look! A Rainbow!</p>

<ul>
    <li style="color: red">Red</li>
    <li style="color: orange">Orange</li>
    <li style="color: yellow">Yellow</li>
    <li style="color: green">Green</li>
    <li style="color: blue">Blue</li>
    <li style="color: indigo">Indigo</li>
    <li style="color: violet">Violet</li>
</ul>
  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

# 	* [Stage and Commit the Rainbow]()

- Hopefully, you are relatively familiar with staging and committing snapshots by now:

```console
$ git add crazy.html
```

```console
$ git status
On branch crazy
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   crazy.html
```

```console
$ git commit -m "add a rainbow to crazy.html"
```

![Screen Shot 2020-05-23 at 9 01 30](https://user-images.githubusercontent.com/24994818/82732641-03dc7200-9cd4-11ea-8d05-6d3d19922e60.png)

- Also notice that the **HEAD** (designated by the red circle) automatically moved forward to the new commit, which is intutively what we would expect when developing a project.
- The above diagram represents the complete state of our repository, but **git log** only displays the history of the current branch:

```console
$ git log
commit e1bc77119319d8b38ff46dbddd968f669cc37a4c
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 23 09:01:08 2020 -0500

    add a rainbow to crazy.html

commit 12e24f0c4e03b3c991b287230548d8bdad3882d7
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 20:34:06 2020 -0500

    Add a crazzy experiment

commit 453c8a4db079c3d235e3470754a79a22ea0f0afd
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 16:53:53 2020 -0500

    Add navigation links

commit 1047951bab2636a3bc90682e48d9fb32644da036
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 13:45:14 2020 -0500

    t Add blue an orange html files

commit 6a442fcc4ab51362713f09ed5eadc7af767db833
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 12:54:21 2020 -0500

    Create index page for the message
```

- Note that the history **before** the fork is considered part of the new branch (marked with asterisks above).
- That is to say, the crazy history spans all the way back to the first commit.

![Screen Shot 2020-05-23 at 9 08 05](https://user-images.githubusercontent.com/24994818/82732774-f07dd680-9cd4-11ea-8454-50261fc15be0.png)

- The project as a whole now has a complex history, however, each individual branch still has a linear history (snapshots occur one after another).
- This means that we can interact with branches in the exact same way as we learned in the first two modules.

# 	* [Rename the Rainbow]()

- Let's add one more snapshot to the crazy branch.
- Rename **crazy.html to **rainbow.html, 

```console
mv crazy.html rainbow.html

- then use the following Git commands to update the repository

```console
$ git status
On branch crazy
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	deleted:    crazy.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	rainbow.html

no changes added to commit (use "git add" and/or "git commit -a")
```

```console
$ git rm crazy.html
rm 'crazy.html'
```

- the git rm command tells Git to stop tacking crazy.html (and delete it if necesarry), and git add starts tracking rainbow.html.

```console
$ git add rainbow.html
```

```console
$ git status
On branch crazy
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	renamed:    crazy.html -> rainbow.html
```

- The renamed: crazy.html -> rainbow.html message in the final status output show us that Git is smart enough to figure out when we are renaming a file.

- Our snapshot is staged and ready to be commited:

```console
$ git commit -m "Rename craz.html to rainbow.html"
crazy 95a36a7] Rename crazy.html to rainbow.html
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename crazy.html => rainbow.html (100%)
```

```console
$ git log --oneline
95a36a7 (HEAD -> crazy) Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```
- After this addition, our complete repository history looks like the following

![Screen Shot 2020-05-23 at 11 01 37](https://user-images.githubusercontent.com/24994818/82735083-cc29f600-9ce4-11ea-89b2-22cc74585e12.png)

- Remember that the crazy branch does not include any commits in master after the fork.
	
# 	* [Return to the Master Branch]()

- lets switch back to the master branch:

```console
$ git checkout master
$ git branch
```

```console
$ git log --oneline
3553479 (HEAD -> master) Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

- After the checkout, crazy.html does not exist in the working directory, and the commits from the last few steps don't appear in the history. These two branches became completely independent development environment after they forked.
- You can think of them as separate project folders that you switch between with git checkout.
- They do, however, share their first four commits.

![Screen Shot 2020-05-23 at 11 37 52](https://user-images.githubusercontent.com/24994818/82735782-e0bcbd00-9ce9-11ea-9ccc-c6b53df0324c.png)

# 	* [Create a CSS Branch]()

- We are going to put our crazy experiment on the backburner for now and turn our attention to formatting the HTML pages with a cascading stylesheet (CSS).
- Again, if you are not comfortable with HTML and CSS, the content of the upcoming files is not nearly as important as the Git commands used to manage them.

- Let's create and check out a new branch called css.

```console
$ git branch css
```

- switch to css branch

```cosnsole
$ git checkout css
Switched to branch 'css'
```

- The new branch points to the currently checked out snapshot, which happens to coincide with the **master branch**

![Screen Shot 2020-05-24 at 8 44 44](https://user-images.githubusercontent.com/24994818/82755691-e1f9f280-9d9a-11ea-9b4c-d44f0d352cae.png)

# 	* [Add a CSS Stylesheet]()

- Next, create a file called **style.css** with the following content.
- This CSS is used to apply formatting to the HTML in our other files.

```css
body {
  padding: 20px;
  font-family: Verdana, Arial, Helvetica, sans-serif;
  font-size: 14px;
  color: #111;
}

p, ul {
  margin-bottom: 10px;
}

ul {
  margin-left: 20px;
}
```

- Commit the stylesheet in the usual fashion

```console
$ git add style.css
$ git status
$ git commit -m "Add CSS stylesheet"
```

# 	* [Link the Stylesheet]()

- We still need to tell the HTML pages to use the formatting in style.css.
- Add the following text on a separate line after the **title** element in **index.html**, **blue.html** and **orange.html** (remember that rainbow.html only exist in the crazy branch).
- You should be able to see the CSS formatting by opening index.html in a web browser.

```html
<link rel="stylesheet" href="style.css" />
```

- Commit the changes

```console
$ git add index.html blue.html orange.html 
```

```console
$ git status
On branch css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   blue.html
	modified:   index.html
	modified:   orange.html

```

```console
$ git commit -m "link HTML pages to stylesheet"
[css 1a27d0e] link HTML pages to stylesheet
 3 files changed, 3 insertions(+)
```

```console
$ git log --oneline
1a27d0e (HEAD -> css) link HTML pages to stylesheet
019e981 Add CSS stylesheet
3553479 (master) Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

- This results in a repository history looks like:

![Screen Shot 2020-05-24 at 8 44 44](https://user-images.githubusercontent.com/24994818/82755691-e1f9f280-9d9a-11ea-9b4c-d44f0d352cae.png)

# 	* [Return to the Master Branch (again)]()

- The css branch let us create and test our formatting without threatening the stability of the **master branch**. But, new we need to merge these changes into the main project. Before we attempt the merge, we need to return to the master branch.

```console
$ git checkout master
Switched to branch 'master'
```

- Verify that style.css does not exist and that HTML pages are not linked to it.
- Our repository history remains unchanged, but the working directory now matches the snapshot pointer to by the **master branch**.

![Screen Shot 2020-05-24 at 9 27 38](https://user-images.githubusercontent.com/24994818/82756619-d6a9c580-9da0-11ea-9445-a23d899e9189.png)

- take a look at the **git log --oneline** output as well.

```console
$ git log --oneline
3553479 (HEAD -> master) Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

- As expected, there is no mention of the CSS addition in the history of master, but we are about to change that.

# 	* [Merge the CSS Branch]()

- Use the git **merge** command to take the snapshots from the **css** branch and add them to the **master** branch.

![Screen Shot 2020-05-24 at 9 38 10](https://user-images.githubusercontent.com/24994818/82756851-508e7e80-9da2-11ea-8c28-66833b9b5a21.png)

- Instead of re-creating the commits in css and adding them to the history of master, Git reuses the existing snapshots and simply moves the tip of **master** to match the tip of **css**.
- This kind of merge is called a **fast-forward merge**, since Git is **"fast-forwarding"** through the new commits in the **css** branch.


- After the merge, both branches have the exact same history, which makes them redundant.
- Unless we wanted to keep developing on the css branch, we are free to get rid of it.

# 	* [Delete the CSS Branch]()

- We can safely delete a branch by passing the -d flag to git branch.

```console
$ git branch -d css
Deleted branch css (was 1a27d0e).
```

- Since **css** and **master** represent the same branch, our history looks the same, though the **css** branch has been removed.
- I have also put the master branch's commits in a straight line in the following visualization, making it easier to track during the upcoming modules.

```console
$ git branch
  crazy
* master
```

![Screen Shot 2020-05-24 at 11 12 51](https://user-images.githubusercontent.com/24994818/82758981-8be37a00-9daf-11ea-93a4-35e65b332800.png)

- Deleting branches is a relatively **"safe"** operation in the sense that Git will warn you if you are deleting a unmerged branch.
- This is just another example of Git's commitment to never losing your work.

# 	* [Conclusion]()

This module used two branches to experiment with new additions. In both cases, branches gave us an environment that was completely isolated from the **"Stable"** version of our website (the master branch). One of our experiments is waiting for us in the next module, while our CSS changes have been merged into the stable project, and its branch is thus obsolete. Using branches to develop small features like these is one of the hall-marks of Git-based software management.

While this module relied heavily on branch diagrams to show the complete state of the repository, you don't need to keep this high-level overview in mind during your every day development. Creating a new branch is really just a way to request an independent working directory, staging snapshot, and history. You can think of branches as a way to multiply functionality presented in the first two module.

Next, we will practice our branch management skills by examining the typical workflow of veteran Git users. We will also discover more complicated merges than the **fast-forward merge** introduced above.

# 	* [Quick Reference]()

```console
$ git branch
$ git branch branchName
$ git checkout branchName
$ git merge branchName
$ git branch -d brachName
$ git rm fileName
```

# 5. [Branches II]()

Now that you have covered the mechanics behind Git Branches, we can discuss the practical impact that they have on the software development process.
Instead of introducing new commands, this module covers how the typical Git user applies this workfow to real projects, as well as some of the problems that arise in a branched enviroment.

To git, a branch is a branch, but it is often useful to assign special meaning to different branches. For example, we have been using **master** as the stable branch for our example project, and we have also used a temporary branch to add some CSS formatting.
Temporary branches like the latter are called **topic branches** becaue they exis to develop a certain topic branches later in this module.

Amid our exploration of Git branches, we will also discover that some merges cannot **"fast-forwarded"**
When the history of two branches diverges, a dedicated commit is required to combine the branches. This situation may also give rise to a merge conflict, which must be manually resolved before anything can be committed to the repository.


# 	* [Continue the Crazy Experiment]()

Let`s start by checking out the crazy branch.

```console
$ git branch
  crazy
* master
```

```console
$ git checkout crazy
Switched to branch 'crazy'
```

```console
$ git log --oneline
95a36a7 (HEAD -> crazy) Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

The crazy branch is a **longer-running** type of topic branch called a **feature branch**.
This is fitting, as it was created with the intention of developing a **specific feature**. It is also a term tht makes Git's contribution to the development workflow readly apparaent: **branches enable you to focus on developing one clearly defined feature at a time**

This brings us to my **rule-thumb for using git branches**:

1. Create a new branch for each mayor addition to your project.
2. Don't create a branch if you cannot give it a specific name.

Following these simple guidelines will have a dramatic impact on your programming efficiency.


# 	* [Merge the CSS Updates]()

Note that CSS formatting we merged into **master** is nowhere to be found.
This presents a bit of a problem if we want to experiment to reflect these updates.
Conveniently, Git let us merge changes into **any branch** (not just the master branch).
So, we can pull the updates in with the familiar **git merge** command.
Remember that merging only affects the checked-out branch.

```console
$ git merge maste
```

- editing

```vim
Merge branch 'master' into crazy
""
""
""
```

```console
$ git merge master
Merge made by the 'recursive' strategy.
 blue.html   |  1 +
 index.html  |  1 +
 orange.html |  1 +
 style.css   | 14 ++++++++++++++
 4 files changed, 17 insertions(+)
 create mode 100644 style.css
```

As of Git 1.7.1.0, this will open your editor and prompt you for a message explaining why the commit was necessary.
You can use the default **Merge** branch **master** into crazy. When you save and close the file, you will notice an extra commit in your project history. Recall that our first merge didn't add any new commits; it is just **"fast-forwarded"** the tip of the master branch. This was not the case for our new merge, which is shown below.

![Screen Shot 2020-05-24 at 11 50 02](https://user-images.githubusercontent.com/24994818/82759729-c7cd0e00-9db4-11ea-9b4b-8e97fc80512e.png)

Take a moment to examine why the current merge could not be **fast-forward one**. 
How Could Git have walked the crazy pointer over the tip of the master branch ?
It is not possible without backtracking, which kind of defeats the idea of **"fast-forwarding"**
We are left with a new way to combine brancges: **the 3-way merge**

A 3-way merge occurs when you try to merge two branches whose history has diverged. It creates an extra merge commit to function as a link between the two branches.
As a result, it has two parent commits. The above figure visualizes this with two arros originating from the tip of crazy. It is like saying **"this commit comes from both the crazy branch and from master"**. After the merge, the crazy branch has access to both its history an the master history.

The name comes from the internal method used to create the merge commit. Git looks at **three** commits (numbered in the above figure) to generate the final state of the merge.

This kind of branch interaction is a big part of what makes Git such a powerful development tool. We can not only create independent lines of development, but we can also share information between them by tying together their stories with a 3-way merge.

# 	* [Style the Rainbow Page]()

Now that we have access to the CSS updates from master, we can continue developing our crazy experiment.
Link the CSS stylesheet to rainbow.html by adding the following HTML on the line after **title** element

```html
<link rel="stylesheet" href="style.css" />
```

- Stage and commit the update, then check that it is reflected in the history

```console
$ git status
On branch crazy
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   rainbow.html

no changes added to commit (use "git add" and/or "git commit -a")
```

```console
$ git commit -a -m "add CSS stylesheet to rainbow.html"
[crazy 6a43f42] add CSS stylesheet to rainbow.html
 1 file changed, 1 insertion(+)
```

```console
$ git log --oneline
6a43f42 (HEAD -> crazy) add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e (master) link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

Notice that we skipped the staging step this time aroun.
Instead of using **git add**, we passed the -a flag to git commit.
This convenient parameter tells Git to automatically include all tracked files in the staged snapshot.
Combined with the -m flag, we can stage and commit snapshots with a single command.
However, be careful not to include unintended files when using the -a flag.

# 	* [Link to the Rainbow Page]()

We still need to add  navigation link to the home page.
Change the "Navigation section of index.html to the following.

```html
<h2>Navigation</h2>
<ul>
  <li style="color: #F90">
    <a href="orange.html">The Orange Page</a>
  </li>
  <li style="color: #00F">
    <a href="blue.html">The Blue Page</a>
  </li>
  <li>
    <a href="rainbow.html">The Rainbow Page</a>
  </li>
</ul>
```

As usual, stage and commit the snapshots.

```console
$ git commit -a -m "Link index.html to rainbow.html"
[crazy 4310454] Link index.html to rainbow.html
 1 file changed, 3 insertions(+)
```

```console
$ git log --oneline
4310454 (HEAD -> crazy) Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e (master) link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

# 	* [Fork an Alternative Rainbow]()

Next, we are going to brainstorm an alternative to the current rainbow.html page.
This is a perfect time to create another topic branch:

```console
$ git branch crazy-alt
```

```console
$ git checkout crazy-alt
Switched to branch 'crazy-alt'
```

Remember, we can do whatever we want here without worrying about either crazy o master.
When **git branch** creates a branch, it uses the current **HEAD** as the starting point for the new branch.
This meeans that we begin with the same files as crazy (if we called **git branch** from **master**, we would have to re-create rainbow.html).
After creating th new branch, our repository's history looks like:


![Screen Shot 2020-05-25 at 8 26 51](https://user-images.githubusercontent.com/24994818/82816850-8181b880-9e61-11ea-8f1e-0019d14a9538.png)

# 	* [Change the Rainbow]()

Change the colorful list in rainbow.html from:

```html
  <li style="color: red">Red</li>
  <li style="color: orange">Orange</li>
  <li style="color: yellow">Yellow</li>
  <li style="color: green">Green</li>
  <li style="color: blue">Blue</li>
  <li style="color: indigo">Indigo</li>
  <li style="color: violet">Violet</li>”
```

to the following:

```html
<div style="background-color: red"></div>
<div style="background-color: orange"></div>
<div style="background-color: yellow"></div>
<div style="background-color: green"></div>
<div style="background-color: blue"></div>
<div style="background-color: indigo"></div>
<div style="background-color: violet"></div>
```

Then, add some CSS formatting to **head** on the line after the **meta** element

```html
	<style>
  div {
    width: 300px;
    height: 50px;
		 }
	 </style>
```

If you open rainbow.html in a browser, you should now see colorful blocks in place of the colorful text. Don't forget to commit the changes:

```console
$ git commit -a -m "Make a REAL rainbow"
[crazy-alt d247771] Make a REAL rainbow
 1 file changed, 13 insertions(+), 7 deletions(-)
```

The resulting project history is show below, with the first four commits ommitted for the sake of presentation.

![Screen Shot 2020-05-25 at 8 49 40](https://user-images.githubusercontent.com/24994818/82818699-b5aaa880-9e64-11ea-9eff-305ed0bca27d.png)


# 	* [Emergency Update]()

Our boss called in with some breaking news ! He needs us to update the site immediately, but what do we do with our rainbow.html developments? Well, the beauty of Git branches is that we can just leave them where they are and add the breaking news to master.

We will use what is called a **hotfix branch** to create and test the news updates. In contrast to our relatively long-running feature **branch (crazy)**, **hotfix** branches are used to quickly patch a production release.

For example: you would use a **hotfix branch** to fix a time-sensitive bug in a public software project. This distinction is useful for demonstrating when it is appropiate to create a new branch, but it is purely conceptual **- a branch is a branch according to Git**

```console
$ git checkout master
Switched to branch 'master'
```

```console
$ git branch news-hotfix
```

```console
$ git checkout news-hotfix
Switched to branch 'news-hotfix'
```

Change the "News" list in **index.html** to match the following.

```html
	<ul>
	  <li><a href="news-1.html">Blue Is The New Hue</a></li>
  </ul>
```

And, create a new HTML page called **news-1.html** with the following content.

```console
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Blue Is The New Hue</title>
  <link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #079">Blue Is The New Hue</h1>
  <p>European designers have just announced that
  <span style="color: #079">Blue</span> will be this year's
  hot color.</p>
    
  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

We can't use **git commit -a** to automatically stage **news-1.html** because it is an **untracked file** (as shown in **git status**).
So, let's use an explicit **git add**:

```console
$ git add index.html news-1.html 
```

```console
$ git status
On branch news-hotfix
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html
	new file:   news-1.html

```

```console
$ git commit -m "Add 1st news item"
[news-hotfix 049c9d9] Add 1st news item
 2 files changed, 17 insertions(+), 1 deletion(-)
 create mode 100644 news-1.html
```

Text these additions in a browser to make sure that the links work, it is typo free, etc. If everything looks good, we can "publish" the changes by merging them into the stable master branch. Isolating this in a separate branch is not really necessary for our trivial example, but in the real world, this would give you the opportunity to run build tests without touching your stable project.

# 	* [Publish the News Hotfix]()

Remember that to merge into the **master** branch, we first need to check it out.

```console
$ git checkout master
Switched to branch 'master'
```

```console
$ git merge news-hotfix
Updating 1a27d0e..049c9d9
Fast-forward
 index.html  |  2 +-
 news-1.html | 16 ++++++++++++++++
 2 files changed, 17 insertions(+), 1 deletion(-)
 create mode 100644 news-1.html
```

Since **master** now contains the news update, we can delete the **hotfix** branch:

```console
$ git branch -d news-hotfix
Deleted branch news-hotfix (was 049c9d9).
```

```console
$ git branch
  crazy
  crazy-alt
* master
```

The following diagram reflects our repository's history before and after the merge. Can you figure out why was this a **fast-forward** merge instead of a **3-way merge**?

![Screen Shot 2020-05-25 at 9 40 01](https://user-images.githubusercontent.com/24994818/82822643-bb57bc80-9e6b-11ea-9d72-eb5c7f1d250c.png)

Also notice that we have another fork in our history (the commit before **master** branches in two directions), which means we should expect to see another merge commit in the near future.

# 	* [Complete the Crazy Experiment]()

Ok, lets finish up our crazy experiment with one more commit.

```console
$ git checkout crazy
Switched to branch 'crazy'
```

Note that the news article is nowhere to be found, as should be expected (this branch is completely isolated development environment).

We will finish up our crazy experiment by adding a news item for it on the home page. Change the news list in **index.html** to the following:

```html
<h2 style="color: #C00">News</h2>
<ul>
  <li><a href="rainbow.html">Our New Rainbow</a></li>
</ul>
```

Astute readers have probably observed that this directly conflicts with what we changed in the **news-hotfix** branch.
**We should not manually add in the other news item** because it has no relationship with the current branch. In addition, there would be no way to make sure the links works because **news-1.html** does not exist in this branch. This may seem trivial, but imagine the errors that could be introduced had **news-hotfix** made dozens of different changes.

We will simply stage and commit the snapshot as if there were no conflicts:

```console
$ git commit -a -m "Add news item for rainbow"
[crazy ebb4171] Add news item for rainbow
 1 file changed, 1 insertion(+), 1 deletion(-)
```

Look at those experimental commits (marked with asterisks below)!

```console
$ git log --oneline
* ebb4171 (HEAD -> crazy) Add news item for rainbow
* 4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
* 95a36a7 Rename crazy.html to rainbow.html
* e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
* 12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

# 	* [Publish the Crazy Experiment]()

We are finally ready to merge our **crazy** branch into **master**:

```console
$ git checkout master
Switched to branch 'master'
```

```console
$ git merge crazy
Auto-merging index.html
CONFLICT (content): Merge conflict in index.html
Automatic merge failed; fix conflicts and then commit the result.
```

This is our first **merge conflict**. Conflicts occur when we try to merge branches that have edited the same content. Git does not know how to combine the two changes, so it stops to ask us what to do. We can see exactly what went wrong with the familiar **git status** command.

```console
$ git status
On branch master
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Changes to be committed:
	new file:   rainbow.html

Unmerged paths:
  (use "git add <file>..." to mark resolution)
	both modified:   index.html
```

We are looking at the staged snapshot of a merge commit. We never saw this with the first 3-way merge because we didn't have any conflicts to resolve. But now, Git stopped to let us modify files and resolve the conflict before committing the snapshot. The **"Unmerged paths"** section contains files that have conflict..

Open up index.html and find the section that looks like:

```console
<<<<<<< HEAD
	  <li><a href="news-1.html">Blue Is The New Hue</a></li>
=======
		<li><a href="rainbow.html">Our New Rainbow</a></li>
>>>>>>> crazy
```

$ git went ahead and modified the conflicted file to show us exactly which lines are afflicted. The format of the above text show us the difference between the two versions of the file. 

- The section **labeled** <<<<<<< HEAD show us the version in the current branch, while the part after the ======= shows the version in the **crazy** branch.

# 	* [Resolve the Merge Conflicts]()

We can change the affected lines to whatever we want in order to resolve the conflict. Edit the news section of **index.html** to keep changes from both versions:

```console
<h2 style="color: #C00">News</h2>
<ul>
  <li><a href="news-1.html">Blue Is The New Hue</a></li>
  <li><a href="rainbow.html">Our New Rainbow</a></li>
</ul>
```

The <<<<<<<, =======, and >>>>>>> markers are only used to show us the conflict and should be deleted. Next, we need to tell Git that we are done resolving the conflict:

```console
$ git add index.html
```

```console
$ git status
On branch master
All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
	modified:   index.html
	new file:   rainbow.html
```

That's right, all you have to do is **add index.html to the staged snapshot to mark it as resolved. Finally, complete the 3-way merge:

```console
$ git commit 
[master f79223d] Merge branch 'crazy'
```

We didn't ue the -m flag to specify a message beacuse Git already gives us a default message for merge commits. It also gives us a **"Conflict"** list, which can be particularly handy when trying to figure out where something went wrong in a project. Save and close the file to create the merge commit.

The final state of our project looks like the following.

![Screen Shot 2020-05-25 at 18 50 28](https://user-images.githubusercontent.com/24994818/82848331-af461c00-9eb8-11ea-881c-3d0868d16c01.png)

# 	* [Cleanup the feature Branches]()

Since our crazy experiment has been successfully merged, we can get rid of our feature branches.

```console
$ git branch -d crazy
Deleted branch crazy (was ebb4171).
```

```console
$ git branch -d crazy-alt
error: The branch 'crazy-alt' is not fully merged.
If you are sure you want to delete it, run 'git branch -D crazy-alt'.
```

As noted in the last module, the **git branch -d** command will not let you delete a branch that contains unmerged changes. But, we really do want to scrap the alternative experiment, so we will follow the error message's instructions for overriding this behavior:

```console
$ git branch -D crazy-alt
Deleted branch crazy-alt (was d247771).
```

Because we never merged **crazy-alt** into **master**, it is lost forever. However, the **crazy** branch is still accessible through its commits, which are now reachable via the **master** branch. That is to say, it is still part of the structure of the repository's history, even though we deleted our reference to it.

![Screen Shot 2020-05-25 at 19 38 28](https://user-images.githubusercontent.com/24994818/82849830-58901080-9ebf-11ea-9338-d8384871beac.png)

Fast-forward merges are not reflected in the project history. This is the tangible distinction between fast-forward merges and 3-way merges. The next module will discuss the appropiate usage of both and the potential complications of a non-linear history.


#   * [Rename Branches Local and Remote]()

This is a new note about how to rename branches. I remember use it when I couldn't rebase a branch over master, so I have to rename my branch as master and master as old-master

Checkout to the desired branch, this apply for local:

```console
Fri Jun 12 ~/iOS/ToDoListApp 
$ git checkout withoutStackViews
Switched to branch 'withoutStackViews'``console

Fri Jun 12 ~/iOS/ToDoListApp 
$ git branch -m old-master
```

Then check the list of branches
```console
$ git branch
* old-master
  withoutStackViews
```

- now change to the branch that you are going set as master

```console
$ git checkout withoutStackViews
Switched to branch 'withoutStackViews'

Fri Jun 12 ~/iOS/ToDoListApp 
$ git branch -m master
```

Check the new list of branches:

```console
$ git branch
* master
  old-master
```

To push this change remotely:

```console
Fri Jun 12 ~/iOS/ToDoListApp 
$ git push origin :master old-master
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/c4arl0s/ToDoListApp.git
 - [deleted]         master
 * [new branch]      old-master -> old-master
```

As you can see in Git hub, the old-master keeps appearing, the withoutStackViews branch also, Git didn't allow me to delete it from command line

![Screen Shot 2020-06-12 at 12 55 19](https://user-images.githubusercontent.com/24994818/84532552-09622200-acac-11ea-93d6-18cbb079870a.png)

git push origin :old-name new-name

# 	* [Conclusion]()

This module demonstrate the three most common uses of Git Branches:

- To develop long-running features (crazy)
- To apply quick updates (news-hotfix)
- To record the evolution of a project (master)


# 	* [Quick Reference]()

```console
$ git commit -a -m "messageToCommit"
```

```console
$ git branch -D branchName
```

# 6. [Rebasing]()	

Let's start this module by taking an in-depth look at our history. The six commits asterisked below are part of the same train thought. 

We even developed them in their own feature branch. However, they show up interspersed with commits from other branches, along with a superfluous merge commit (b9f2b14).
In other words, our repository's history is kind of messy:

```console
$ git log --oneline
f79223d (HEAD -> master) Merge branch 'crazy'
* ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
* 4310454 Link index.html to rainbow.html
* 6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
* 95a36a7 Rename crazy.html to rainbow.html
* e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
* 12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

Fortunately, Git includes a tool to help us clean up our commits: **git rebase**. 
**Rebasing lets us move branches around by changing the commit that they are based on.** 
Conceptually, this is what it allows us to do:

![Screen Shot 2020-05-26 at 11 15 18](https://user-images.githubusercontent.com/24994818/82924636-3a1f2900-9f42-11ea-8f9a-fb7163b73a5e.png)

After rebasing, the feature branch has a new parent commit, which is the same commit pointed to by **master**. Instead of joining the branches with a merge commit, rebasing integrates the feature branch by building on top of **master**. The result is a perfectly linear history that reads more like a story than the hodgepodge of unrelated edits shown above.

To explore Git's rebasing capabilities, we will need to build up our example project so that we have something to work with. Then, we will go back and rewrite history using **git rebase**


# 	* [Create an About Section]()

We will begin by creating an about page for the website. Remember, we should be doing all of our work in isolated branches so that we don't cause any unintended changes to the stable version of the project.

```console
$ git branch about
```

```console
$ git checkout about
Switched to branch 'about'
```

The next few steps break this feature into several unnecessarily small commits so that we can see the effects of a rebase.

First, make a new directory in your repository called about. Then, create the empty file about/index.html. Stage and commit a snapshot.

```console
mkdir about
```

```console
$ git add about
```

```console
$ git status
```

```console
$ git commit -m "Add empty page in about section"
[about 27b0924] Add empty page in about section
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 about/index.html
```

# 	* [Add an About Page]()

Next, we will add some HTML to about/index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>About Us</title>
  <link rel="stylesheet" href="../style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1>About Us</h1>
  <p>We're a small, colorful website with just two employees:</p>
  <ul>
    <li><a href="me.html">Me: The Developer</a></li>
    <li><a href="mary.html">Mary: The Graphic Designer</a></li>
  </ul>
    
  <p><a href="../index.html">Return to home page</a></p>
</body>
</html>
```

Stage and commit the snapshot

```console
$ git status
On branch about
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   about/index.html

no changes added to commit (use "git add" and/or "git commit -a")
```

```console
$ git commit -a -m "Add contents to about page"
[about c94fb42] Add contents to about page
 1 file changed, 19 insertions(+)
```

After a few commits on this branch, our history looks like the following.

![Screen Shot 2020-05-26 at 11 41 12](https://user-images.githubusercontent.com/24994818/82927109-d1d24680-9f45-11ea-92c9-98439ff3652c.png)

# 	* [Another emergency update!]()

Our boss just gave us some more breaking news ! Again, we will use a hotfix branch to update the site without affecting our about page developments. Make sure to base the updates on **master**, not the **about** branch.

```console
$ git checkout master
Switched to branch 'master'
```

```console
$ git branch news-hotfix
```

```console
$ git checkout
```

```console
$ git checkout news-hotfix
Switched to branch 'news-hotfix'
```

```console
$ git branch
  about
  master
* news-hotfix
```

Commit a snapshot:

```console
$ git status
On branch news-hotfix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

```

```console
$ git commit -a -m "Add 2nd news item to index page"
[news-hotfix 5142364] Add 2nd news item to index page
 1 file changed, 1 insertion(+)
```

Then, create a new page called news-2.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>A Red Rebellion</title>
  <link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #C03">A Red Rebellion</h1>    
  <p>Earlier today, several American design firms
  announced that they have completely rejected the use
  of blue in any commercial ventures. They have
  opted instead for <span style="color: #C03">Red</span>.</p>
    
  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

Stage and commit another snapshot:

```console
$ git add news-2.html
```

```console
$ git status
On branch news-hotfix
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   news-2.html
```

```console
$ git commit -m "Add article for 2nd news item"
[news-hotfix 74afd90] Add article for 2nd news item
 1 file changed, 17 insertions(+)
 create mode 100644 news-2.html
```

# 	* [Publish News Hotfix]()

We are ready to merge the news update back into **master**

```console
$ git checkout master
Switched to branch 'master'
```

```console
$ git merge news-hotfix
Updating f79223d..74afd90
Fast-forward
 index.html  |  1 +
 news-2.html | 17 +++++++++++++++++
 2 files changed, 18 insertions(+)
 create mode 100644 news-2.html
```

```console
$ git branch -d news-hotfix
Deleted branch news-hotfix (was 74afd90).
```

The **master** branch has not been altered since we created news-hotfix, so Git can perform a fast-forward merge. Our repository now looks like the following.

![Screen Shot 2020-05-26 at 16 45 12](https://user-images.githubusercontent.com/24994818/82953378-49b56680-9f70-11ea-8bc0-516728c17beb.png)

# 	* [Rebase the about Branch]()

This puts us in the exact position as we were in before our first 3-way merge. We want to pull changes from **master** into a feature branch, only this time we will do it with a rebase instead of a merge.

```console
$ git checkout about
Switched to branch 'about'
```

```console
$ git rebase master
First, rewinding head to replay your work on top of it...
Applying: Add empty page in about section
Applying: Add contents to about page
```

```console
$ git log --oneline
ebfbefc (HEAD -> about) Add contents to about page
edff70e Add empty page in about section
74afd90 (master) Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

Originally, the **about** branch was based on the Merge branch 'crazy-experiment' commit.
The rebase took the entire **about** branch and plopped it onto the tip of the **master** branch, which is visualized in the following diagram. Also notice that, like the **git merge** command, **git rebase** requires you to be on the branch that you want to move.

![Screen Shot 2020-05-26 at 16 56 45](https://user-images.githubusercontent.com/24994818/82954216-e75d6580-9f71-11ea-8cd6-ad0e3c78d9d2.png)

After the rebase, **about** is a linear extension of the **master** branch, enabling us to do a **fast-forward** merge later on. **Rebasing** also allowed us to integrate the most up-to-date version of **master** without a merge commit.

# 	* [Add a Personal Bio](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

With our news hotfix out of the way, we can now continue work on our about section. Create the file about/me.html with the following contents:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>About Me</title>
  <link rel="stylesheet" href="../style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1>About Me</h1>
  <p>I'm a big nerd.</p>

  <h2>Interests</h2>
  <ul>
    <li>Computers</li>
    <li>Mathematics</li>
    <li>Typography</li>
  </ul>

  <p><a href="index.html">Return to about page</a></p>
</body>
</html>
```

```console
$ git add about/me.html
```

```console
$ git commit -m "Add HTML page for personal bio"
[about fbe3d49] Add HTML page for personal bio
 1 file changed, 21 insertions(+)
 create mode 100644 about/me.html
```

```console
$ git log --oneline
fbe3d49 Add HTML page for personal bio
ebfbefc Add contents to about page
edff70e Add empty page in about section
74afd90 Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

Remember that thanks to the rebase, **about** rests on top of **master**. So, All of our **about** section commits are grouped together, which would not be the case had we merged instead of rebase. This also eliminates an unnecessary fork in our project history.


# 	* [Add Dummy Page for Mary](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Once again, the next two snapshots are unneccessarily trivil. However, we will use an **interactive rebase** to combine them into a single commit later on. That's right, **git rebase** not only lets you move branches around, it enables you to manipulate individual commits as you do so.

Create a new empty file in the about section about/mary.html

```console
$ vim about/mary.html
```

```console
$ git status
On branch about
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   about/mary.html
```

```console
$ git commit -m "Add empty HTML page for Mary's bio"
[about 5f022e1] Add empty HTML page for Mary's bio
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 about/mary.html
```

# 	* [Link to the About Section](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Then, add a link to the about page in index.html so that its "Navigation" section looks like the following:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>A Colorful Website</title>
	<link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #07F">A Colorful Website</h1>
  <p>This is a website about color!</p>    
  
  <h2 style="color: #C00">News</h2>
  <ul>
	  <li><a href="news-1.html">Blue Is The New Hue</a></li>
		<li><a href="rainbow.html">Our New Rainbow</a></li>
    <li><a href="news-2.html">A Red Rebellion</a></li>
  </ul>
</body>
</html>
<h2>Navigation</h2>
<ul>
	<li>
    <a href="about/index.html">About Us</a>
  </li>
  <li style="color: #F90">
    <a href="orange.html">The Orange Page</a>
  </li>
  <li style="color: #00F">
<a href="blue.html">The Blue Page</a>
  </li>
	<li>
    <a href="rainbow.html">The Rainbow Page</a>
  </li>
</ul>
```

Don't forget to commit the change:

```console
$ git commit -a -m "Add link to about section in home page"
[about ce9d652] Add link to about section in home page
 1 file changed, 3 insertions(+)
```

# 	* [Clean up the Commit History](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Before we merge into the **master** branch, we should make sure we have a clean, meaningful history in our feature branch. By **rebasing interactively**, we can choose **how** each commit is transferred to the new base. Specify an interactive rebase by passing the -i flag to the rebase command:

```console
$ git rebase -i master
```

This should open up a text editor populated with all of the commits introduced in the **about** branch, listed from the oldest to newest. The listing defines exactly how Git will transfer the commits to the new base. Leaving it as is will do a normal **git rebase**, but if we move the lines around, we can change the order in which commits are applied.

In addition, we can replace the **pick** command before each line to **edit it** or **combine it** with other commits. All of the available commands are shown in the comment section of the rebase listing, but right now, we only need the **squash** command. This will condensate our unnecessarily small commits into a single, meaningful snapshot. Change your listing to match the following:

```console
pick edff70e Add empty page in about section
squash ebfbefc Add contents to about page
pick fbe3d49 Add HTML page for personal bio
squash 5f022e1 Add empty HTML page for Mary's bio
pick ce9d652 Add link to about section in home page
```

then get inside editor vi

```vim
pick edff70e Add empty page in about section
squash ebfbefc Add contents to about page
pick fbe3d49 Add HTML page for personal bio
squash 5f022e1 Add empty HTML page for Mary's bio
pick ce9d652 Add link to about section in home page

# Rebase 74afd90..ce9d652 onto 5f022e1 (5 commands)
#
# Commands:
# p, pick <commit> = use commit
# r, reword <commit> = use commit, but edit the commit message
# e, edit <commit> = use commit, but stop for amending
# s, squash <commit> = use commit, but meld into previous commit
# f, fixup <commit> = like "squash", but discard this commit's log message
# x, exec <command> = run command (the rest of the line) using shell
# b, break = stop here (continue rebase later with 'git rebase --continue')
# d, drop <commit> = remove commit
# l, label <label> = label current HEAD with a name
# t, reset <label> = reset HEAD to a label
# m, merge [-C <commit> | -c <commit>] <label> [# <oneline>]
# .       create a merge commit using the original merge commit's
# .       message (or the oneline, if no original merge commit was
# .       specified). Use -c <commit> to reword the commit message.
#
# These lines can be re-ordered; they are executed from top to bottom.
#
# If you remove a line here THAT COMMIT WILL BE LOST.
#
# However, if you remove everything, the rebase will be aborted.
#
# Note that empty commits are commented out
```

After you edit, save and quit, it will appear the following 2 commit message:

```vim
# This is a combination of 2 commits.
# This is the 1st commit message:

Add empty page in about section

# This is the commit message #2:

Add contents to about page

# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
# Date:      Tue May 26 11:32:08 2020 -0500
#
# interactive rebase in progress; onto 74afd90
# Last commands done (2 commands done):
#    pick edff70e Add empty page in about section
#    squash ebfbefc Add contents to about page
# Next commands to do (3 remaining commands):
#    pick fbe3d49 Add HTML page for personal bio
#    squash 5f022e1 Add empty HTML page for Mary's bio
# You are currently rebasing branch 'about' on '74afd90'.
#
# Changes to be committed:
#	new file:   about/index.html
#
```

after the two message:

```console
$ git rebase -i master
[detached HEAD 97a4a22] Add empty page in about section
 Date: Tue May 26 11:32:08 2020 -0500
 1 file changed, 19 insertions(+)
 create mode 100644 about/index.html
[detached HEAD 1260437] Add HTML page for personal bio
 Date: Tue May 26 17:52:52 2020 -0500
 2 files changed, 21 insertions(+)
 create mode 100644 about/mary.html
 create mode 100644 about/me.html
Successfully rebased and updated refs/heads/about.
```

The following list describes the rebasing process in-depth and tells you what you need to change along the way.

```vim
pick edff70e Add empty page in about section
squash ebfbefc Add contents to about page
pick fbe3d49 Add HTML page for personal bio
squash w5f022e1 Add empty HTML page for Mary's bio
pick ce9d652 Add link to about section in home page
```

1. Git moves the edff70e commit to the tip of **master**
2. Git combines the snapshots of ebfbefc and 5f022e1 
3. Git stops to ask you what commit message to use for the combined snapshot. It automatically includes the messages of both commits, but you can delete that and simplify it to just **Create the about page**. Save and exit the text editor to continue.
4. Git repeats this process for commits  ce9d652 and 5f022e1.  Use **Begin creating bio pages** for the message.
5. Git adds the final commit ce9d652 on top of the commits created in the previous steps.

You can see the result of all this activity with **git log --oneline**

```console
def4be5 (HEAD -> about) Add link to about section in home page
c5c692e Begin creating bio pages
f4bb8c3 Create the about page
74afd90 (master) Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

As well in the diagram before

![Screen Shot 2020-05-26 at 19 09 34](https://user-images.githubusercontent.com/24994818/82961997-8723ef00-9f84-11ea-8324-be7e1496069e.png)

**Interactive rebasing** gives you complete control over your project history, but this can also be very dangerous. For example, if you were to delete a line from the rebase listing, the associated commit would not be transferred to the new base, and its content would be lost forever. In a future module, we will also see how rewriting history can get you in trouble with the public Git repositories.

# 	* [Stop to Amend a Commit](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

The previous rebase only stopped us to edit the messages of each commit.
We can take this one step further and alter a **snapshot** during the rebase.
Start by running another interactive rebasing session. Note that we have still been using **master** as the new base because it selects the desired commits from the **about** branch.

```console
$ git rebase -i master
```

Specify the **edit** command for the second commit, as shown below:

```vim
pick f4bb8c3 Create the about page
edit c5c692e Begin creating bio pages
pick def4be5 Add link to about section in home page
```

When Git starts to move the second commit to the new base, it will stoo to do some "amending" (enmendar, rectificar). This gives you the opportunity to alter the staged snapshot before committing it.

![Screen Shot 2020-05-28 at 18 43 50](https://user-images.githubusercontent.com/24994818/83205087-368ecc00-a113-11ea-926a-d29bb89f572b.png)

We will leave a helpful note for Mary, whom we will meet in the **Remotes** module. Open up **about/mary.html** and add the following.

```vim
[Mary, please update the bio!]
```

When you save and close

```console
$ git rebase -i master
Stopped at c5c692e...  Begin creating bio pages
You can amend the commit now, with

  git commit --amend 

Once you are satisfied with your changes, run

  git rebase --continue
```

then open the file and add the required message

```console
$ vim about/mary.html
```

now, that your changes are ready.

```console
$ git add about/mary.html 
```

```console
$ git status
interactive rebase in progress; onto 74afd90
Last commands done (2 commands done):
   pick f4bb8c3 Create the about page
   edit c5c692e Begin creating bio pages
Next command to do (1 remaining command):
   pick def4be5 Add link to about section in home page
  (use "git rebase --edit-todo" to view and edit)
You are currently editing a commit while rebasing branch 'about' on '74afd90'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   about/mary.html
```

```console
$ git commit --amend
[detached HEAD 71153c2] Begin creating bio pages (added message to mary)
 Date: Tue May 26 17:52:52 2020 -0500
 2 files changed, 22 insertions(+)
 create mode 100644 about/mary.html
 create mode 100644 about/me.html
```

```console
$ git log --oneline
71153c2 (HEAD) Begin creating bio pages (added message to mary)
f4bb8c3 Create the about page
74afd90 (master) Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

You can use the default message created by **git commit**. The new **--amend** flag tell Git to **replace** the existing commit with the staged snapshot instead of creating a new one. This is also very useful for existing premature commits that often occur during normal development.


# 	* [Continue the Interactive Rebase](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Remember that we are in the middle of a rebase, and Git still has one more commit that it needs to re-play. Tell Git that we are ready to move on with the **continue** flag:

```console
$ git rebase --continue
Successfully rebased and updated refs/heads/about.
```

```console
$ git log --oneline
20b9d5d (HEAD -> about) Add link to about section in home page
71153c2 Begin creating bio pages (added message to mary)
f4bb8c3 Create the about page
74afd90 (master) Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

# 	* [Publish the About Section](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

The point of all this interactive rebasing is to generate a **meaningful** history that we can merge back into **master**. And, since we have rebased **about** onto the tip of **master**, Git will be able to perform a **fast-forward** merge instead of using a merge commit to join the two branches.

```console
$ git checkout master
```

```console
$ git log --oneline
74afd90 (HEAD -> master) Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```
 
```console
$ git merge about
Updating 74afd90..20b9d5d
Fast-forward
 about/index.html | 19 +++++++++++++++++++
 about/mary.html  |  1 +
 about/me.html    | 21 +++++++++++++++++++++
 index.html       |  3 +++
 4 files changed, 44 insertions(+)
 create mode 100644 about/index.html
 create mode 100644 about/mary.html
 create mode 100644 about/me.html
```

```console
$ git log --oneline
20b9d5d (HEAD -> master, about) Add link to about section in home page
71153c2 Begin creating bio pages (added message to mary)
f4bb8c3 Create the about page
74afd90 Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

Don't forget to delete the obsolete **about** branch.

```console
$ git branch -d about
Deleted branch about (was 20b9d5d).
```

Our final history is shown in the figure below. As you can see, a linear history is much easier to comprehend that the back-and-forth merging of the previous module. But on the other hand, we don't have the slightest notion of **how** we got to our current state.

![Screen Shot 2020-05-29 at 11 06 55](https://user-images.githubusercontent.com/24994818/83280605-89609600-a19c-11ea-9686-133d7863dc33.png)

# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

**Rebasing enables fast-forward merges** by moving a branch to the tip of another branch. It effectively eliminates the need for merge commits, resulting in a completely linear history. To an outside observer, it will seem as though you created every part of your project in a neatly (pulcramente) planned sequence, even though you may have explored various alternatives or developed unrelated features in parallel. Rebasing gives you the power to choose exactly what gets stored in you repositories.

This can actually be a bit of a controversial topic within the Git community. Some believe that the benefits discussed in this module are not worth the hassle (molestia) of rewriting history. They take a more "pure" approach to Git by saying that your history should reflect **exactly** what you have done, ensuring that no information is ever lost. Furthermore, an advance configuration o **git log** can display a linear history from a highly-branched repository.

But, others contend that merge commits should be **meaningful**. Instead of merging at arbitrary points just to access updates, they claim that merge commits should represent a symbolic joining of two branches. In particular, large software projects (such as the Linux Kernel) typically advocate interactive rebasing to keep the repository as clean and straightforward as possible.

The use of **git rebase** is entirely up to you. Customizing the evolution of your project can b very beneficial, but it might not be worth the trouble when you can accomplish close to the same functionality using merges exclusively. As a related note, you can use the following command to force a merge commit when Git would normally do a **fast-forward** merge.

```console
$ git merge --no-ff branchName
```

The next module will get a little bit more involved in our project history. We will try fixing mistakes via complex rebases end even learn how to recover deleted commits.

# 	* [Quick References](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git rebase newBase
```

```console
$ git rebase -i newBase
```

```console
$ git commit --amend
```

```console
$ git rebase --continue
```

```console
$ git rebase abort
```

```console
$ git merge --no-ff branchName
```

Force a merge commit even if Git could do a fast-forward merge.

# 7. [Rewriting History](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

The previuous module on rebasing taught us how to move commits around and perform some basic edits while doing so, but now we are going to really get our hands dirty We Will learn **how to split up commits, revive lost snapshots, and completely rewrite a repository's history to our exact specifications**.

Hopefully, this module will get you much more comfortable with the core Git components, as we will be inspecting and editing the internal makeup of our project.

# 	* [Create the Red Page](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

First, let's create a new branch and add a few more HTML pages.

```console
$ git checkout -b new-pages
Switched to a new branch 'new-pages'
```

```console
$ git branch
  master
```

Notice that we created a new branch and check it out in a single step by passing the -b flag to the **git checkout** command.

Next, create the file **red.html** and add the following content:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>The Red Page</title>
  <link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #C00">The Red Page</h1>
  <p>Red is the color of <span style="color: #C00">passion</span>!</p>
    
  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

We will hold off on committing this page for the moment.

# 	* [Create the Yellow Page](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Create a file called **yellow.html**, which should look like the following.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>The Yellow Page</title>
  <link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #FF0">The Yellow Page</h1>
  <p>Yellow is the color of <span style="color: #FF0">the sun</span>!</p>
    
  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

# 	* [Link and Commit the New Pages](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Next, We will link both new pages to the home page. Add the following items to the "Navigation" section in index.html

```html
<li style="color: #C00">
  <a href="red.html">The Red Page</a>
</li>
<li style="color: #FF0">
  <a href="yellow.html">The Yellow Page</a>
</li>
```

Then commit all of these changes in a single snapshot.

```console
$ git add red.html yellow.html index.html 
```

```console
$ git status
On branch new-pages
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html
	new file:   red.html
	new file:   yellow.html
```

```console
$ git commit -m "add new HTML Pages"
[new-pages 4a5bfc9] add new HTML Pages
 3 files changed, 35 insertions(+), 1 deletion(-)
 create mode 100644 red.html
 create mode 100644 yellow.html
```

This is an example of a **bad commit**. It perform multiple unrelated tasks, and it has a relatively generic commit message. Thus far, we have not really specified when ti is appropriate to commit changes, but the general rules are essentially the same as for branch creation:

1. Commit a snapshot for each significant addition to your project.
2. Don't commit a snapshot if you cannot come up with a single, specific message for it.

This will ensure that your project has a meaningful commit history, which gives you the ability to see exactly when and where a feature was added or a piece of functionality was broken. However, in practice, you will often wind up committing several changes in a single snapshot, since you will not always know what constitutes a **"well-defined"** addition as you are developing a project. Fortunately, Git, lets us go back and fix up these problem commits after the fact.

# 	* [Create and commit the Green Page](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Let's create one more page before splitting that "bad" commit: Add the following HTML to a file called **green.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>The Green Page</title>
  <link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #0C0">The Green Page</h1>
  <p><span style="color: #0C0">Green</span> is the color of earth.</p>
    
  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

Add a link to index.html in the "Navigation" section:

```html
<li style="color: #0C0">
  <a href="green.html">The Green Page</a>
</li>
```

And finally, stage the green page and commit the snapshot.

```console
$ git add green.html index.html 
```

```console
$ git status
On branch new-pages
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   green.html
	modified:   index.html
```

```console
$ git commit -m "Add green page"
[new-pages 49fd8bf] Add green page
 2 files changed, 17 insertions(+)
 create mode 100644 green.html
```

# 	* [Begin an Interactive Rebase](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

The commits introduced in our new-pages branch are:

```console
49fd8bf (HEAD -> new-pages) Add green page
4a5bfc9 add new HTML Pages
```

But, we want these commits to look more like:

```console
49fd8bf Add green page
XXXXXXX Add yellow page
XXXXXXX Add red page
```

To achieve this, we can use the same interactive rebasing method covered in the previous module, only this time we will actually **create** commits in the middle of the rebasing procedure.

```console
git rebase -i master
```

Change the rebase listing to the following, then save the file and exit the editor to begin the rebase.

```console
edit 4a5bfc9 add new HTML Pages
pick 49fd8bf Add green page
```

# 	* [Undo the Generic Commit](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

First, let's take a look at where we are with **git log --oneline**:

```console
4a5bfc9 (HEAD) add new HTML Pages
20b9d5d (master) Add link to about section in home page
```

When Git encountered the **edit** command in the rebase configuration, it stopped to let us edit the commit. As a result, the green page commit does not appear in our history yet. This should be familiar from the previous module. But instead of **amending** the current commit, we are going to completely remove it:

```console
$ git reset --mixed HEAD~1
Unstaged changes after reset:
M	index.html
```

The **git reset** command moves the checked out snapshot to a new commit, and the **HEAD~1** parameter tells it **to reset** to the commit that occurs immediately before the current HEAD (likewise, **HEAD~2** would refer to **second commit before HEAD**). In this particular case, **HEAD~1** happens to coincide with **master**. The effect on our repository can be visualized as:

![Screen Shot 2020-05-30 at 13 36 49](https://user-images.githubusercontent.com/24994818/83336663-d0bd5400-a27a-11ea-9bd6-28b787c51e19.png)

You may recall from [Undoing Changes]() that we used **git reset --hard** to undo uncommitted changes to our project. The **--hard** flag told Git to make the working directory look exactly like the most recent commit, giving us the intended effect of removing uncommitted changes.

But, this time we use the **--mixed** flag to preserve the working directory, which contains the changes we want to separate. That is to say, the **HEAD** moved, but the working directory  remained unchanged. Of course, this results in a repository with uncommitted modifications. We now have the opportunity to add the **red.html** and **yellow.html** files to distinct commits.

# 	* [Split the Generic Commit](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Let's start with the red page. Since we only want to commit content that involves the red page, we will have to manually go in and remove the yellow page's link from the "Navigation" section. In index.html, change this section to match the following.

```html
<h2>Navigation</h2>
<ul>
  <li>
    <a href="about/index.html">About Us</a>
  </li>
  <li style="color: #F90">
    <a href="orange.html">The Orange Page</a>
  </li>
  <li style="color: #00F">
    <a href="blue.html">The Blue Page</a>
  </li>
  <li>
    <a href="rainbow.html">The Rainbow Page</a>
  </li>
  <li style="color: #C00">
    <a href="red.html">The Red Page</a>
  </li>
</ul>
``` 

Now, we can group the red page' updates into an independent commit.

```console
git add red.html index.html
```

```console
$ git status
interactive rebase in progress; onto 20b9d5d
Last command done (1 command done):
   edit 4a5bfc9 add new HTML Pages
Next command to do (1 remaining command):
   pick 49fd8bf Add green page
  (use "git rebase --edit-todo" to view and edit)
You are currently editing a commit while rebasing branch 'new-pages' on '20b9d5d'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html
	new file:   red.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	yellow.html
```

```console
$ git commit -m "Add red page"
[detached HEAD cb8d72b] Add red page
 2 files changed, 18 insertions(+), 1 deletion(-)
 create mode 100644 red.html
```

Next up is the yellow page. Go ahead and add it back to the "Navigation" section in index.html

```console
$ vim index.html 
```

```html
<li style="color: #FF0">
  <a href="yellow.html">The Yellow Page</a>
</li>
```

And again, stage and commit the snapshot

```console
$ git add yellow.html index.html 
```

```console
interactive rebase in progress; onto 20b9d5d
Last command done (1 command done):
   edit 4a5bfc9 add new HTML Pages
Next command to do (1 remaining command):
   pick 49fd8bf Add green page
  (use "git rebase --edit-todo" to view and edit)
You are currently editing a commit while rebasing branch 'new-pages' on '20b9d5d'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html
	new file:   yellow.html
```

```console
$ git commit -m "Add yellow page"
[detached HEAD 1b2f067] Add yellow page
 2 files changed, 17 insertions(+)
 create mode 100644 yellow.html
```

We have successfully split up the contents of a single commit into two new snapshots, as shown below.

![Screen Shot 2020-05-30 at 17 47 36](https://user-images.githubusercontent.com/24994818/83340445-acbf3a00-a29d-11ea-90c6-c8615da2042f.png)

But, do not forget that the rebase still needs to transfer the green page:

```console
$ git rebase --continue
Successfully rebased and updated refs/heads/new-pages.
```

To summarize, we removed the **"bad"** commit from the current branch with **git reset**, keeping the contained HTML files intact with the **--mixed** flag. Then, we committed them in separate snapshots with the usual **git add** and **git commit** commands. The point to remember is that during a rebase you can **add**, **delete**, and **edit** commits to your heart's content, and the entire result will be moved to the new base.

let's show

```console
$ git log --oneline
d417237 (HEAD -> new-pages) Add green page
1b2f067 Add yellow page
cb8d72b Add red page
20b9d5d (master) Add link to about section in home page
71153c2 Begin creating bio pages (added message to mary)
f4bb8c3 Create the about page
74afd90 Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

# 	* [Remove the last Commit](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Next, we are going to **"accidentally"** remove the green page commit so we can learn how to retrieve it via Git's **internal repository data**.

```console
$ git log --oneline
d417237 Add green page
1b2f067 Add yellow page
cb8d72b Add red page
20b9d5d Add link to about section in home page
71153c2 Begin creating bio pages (added message to mary)
f4bb8c3 Create the about page
74afd90 Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

```console
$ git reset --hard HEAD~
HEAD is now at 1b2f067 Add yellow page
```

```console
$ git status
On branch new-pages
nothing to commit, working tree clean
```

```console
$ git log --oneline
1b2f067 (HEAD -> new-pages) Add yellow page
cb8d72b Add red page
20b9d5d (master) Add link to about section in home page
71153c2 Begin creating bio pages (added message to mary)
f4bb8c3 Create the about page
74afd90 Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

This moves the checked-out commit backward by one snapshot, along with the **new-pages** pointer. Note that **git status** tells us that we have nothing to commit, since the **--hard** flag obliterated (remove) any changes in the working directory. And of course, the **git log** output shows that the **new-pages** branch no longer contains the green commit.

This behavior is slightly different from the reset we used in the interactive rebase: this time the branch: **this time the branch moved with the new HEAD**. Since we were on (no branch) during the **rebase**, there was no branch tip to move. However, in general, **git reset** is used to move branch tips around and optionally alter the working directory via one of its many flags. (e.g. **--mixed** or **--hard**).

![Screen Shot 2020-05-31 at 18 57 25](https://user-images.githubusercontent.com/24994818/83365813-9afa9700-a370-11ea-8592-0ecb23015250.png)

The commit that we removed from the branch is now a **dangling commit**. Dangling commits are those that cannot be reached from any branch and are thus in danger of being lost forever.


# 	* [Open the Reflog](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Git uses something called the **reflog** to record every change you make to your repository. Let's take a look at what it contains:

```console
$ git reflog
1b2f067 HEAD@{0}: reset: moving to HEAD~
d417237 HEAD@{1}: rebase -i (finish): returning to refs/heads/new-pages
d417237 HEAD@{2}: rebase -i (pick): Add green page
1b2f067 HEAD@{3}: commit: Add yellow page
cb8d72b HEAD@{4}: commit: Add red page
20b9d5d HEAD@{5}: reset: moving to HEAD~1
4a5bfc9 HEAD@{6}: rebase -i: fast-forward
20b9d5d HEAD@{7}: rebase -i (start): checkout master
49fd8bf HEAD@{8}: commit: Add green page
4a5bfc9 HEAD@{9}: commit: add new HTML Pages
20b9d5d HEAD@{10}: checkout: moving from master to new-pages
20b9d5d HEAD@{11}: merge about: Fast-forward
74afd90 HEAD@{12}: checkout: moving from about to master
20b9d5d HEAD@{13}: rebase -i (finish): returning to refs/heads/about
20b9d5d HEAD@{14}: rebase -i (pick): Add link to about section in home page
71153c2 HEAD@{15}: commit (amend): Begin creating bio pages (added message to mary)
c5c692e HEAD@{16}: rebase -i: fast-forward
f4bb8c3 HEAD@{17}: rebase -i (start): checkout master
def4be5 HEAD@{18}: rebase -i (finish): returning to refs/heads/about
def4be5 HEAD@{19}: rebase -i (pick): Add link to about section in home page
c5c692e HEAD@{20}: rebase -i (reword): Begin creating bio pages
c0ae323 HEAD@{21}: rebase -i (reword): Add HTML page for personal bio
f4bb8c3 HEAD@{22}: rebase -i (reword): Create the about page
a6d6855 HEAD@{23}: rebase -i: fast-forward
74afd90 HEAD@{24}: rebase -i (start): checkout master
7d4c122 HEAD@{25}: rebase -i (finish): returning to refs/heads/about
7d4c122 HEAD@{26}: rebase -i (pick): Add link to about section in home page
5a3bbf7 HEAD@{27}: rebase -i (reword): Add HTML page for personal bio
a6d6855 HEAD@{28}: rebase -i (reword): Add empty page in about section
97a4a22 HEAD@{29}: rebase -i: fast-forward
74afd90 HEAD@{30}: rebase -i (start): checkout master
a72282b HEAD@{31}: rebase -i (finish): returning to refs/heads/about
a72282b HEAD@{32}: rebase -i (start): checkout master
a72282b HEAD@{33}: checkout: moving from master to about
74afd90 HEAD@{34}: checkout: moving from about to master
a72282b HEAD@{35}: rebase -i (finish): returning to refs/heads/about
a72282b HEAD@{36}: rebase -i (start): checkout master
a72282b HEAD@{37}: reset: moving to HEAD
a72282b HEAD@{38}: rebase -i (finish): returning to refs/heads/about
a72282b HEAD@{39}: rebase -i (start): checkout master
a72282b HEAD@{40}: checkout: moving from master to about
74afd90 HEAD@{41}: checkout: moving from about to master
a72282b HEAD@{42}: rebase -i (finish): returning to refs/heads/about
a72282b HEAD@{43}: rebase -i (pick): Add link to about section in home page
1260437 HEAD@{44}: rebase -i (squash): Add HTML page for personal bio
8de18d7 HEAD@{45}: rebase -i (pick): Add HTML page for personal bio
97a4a22 HEAD@{46}: rebase -i (squash): Add empty page in about section
edff70e HEAD@{47}: rebase -i (start): checkout master
ce9d652 HEAD@{48}: checkout: moving from master to about
74afd90 HEAD@{49}: checkout: moving from about to master
ce9d652 HEAD@{50}: rebase -i (finish): returning to refs/heads/about
ce9d652 HEAD@{51}: rebase -i (start): checkout master
ce9d652 HEAD@{52}: rebase -i (finish): returning to refs/heads/about
ce9d652 HEAD@{53}: rebase -i (start): checkout master
ce9d652 HEAD@{54}: commit: Add link to about section in home page
5f022e1 HEAD@{55}: commit: Add empty HTML page for Mary's bio
fbe3d49 HEAD@{56}: commit: Add HTML page for personal bio
ebfbefc HEAD@{57}: rebase finished: returning to refs/heads/about
ebfbefc HEAD@{58}: rebase: Add contents to about page
edff70e HEAD@{59}: rebase: Add empty page in about section
74afd90 HEAD@{60}: rebase: checkout master
c94fb42 HEAD@{61}: checkout: moving from master to about
74afd90 HEAD@{62}: merge news-hotfix: Fast-forward
f79223d HEAD@{63}: checkout: moving from news-hotfix to master
74afd90 HEAD@{64}: commit: Add article for 2nd news item
5142364 HEAD@{65}: commit: Add 2nd news item to index page
f79223d HEAD@{66}: checkout: moving from master to news-hotfix
f79223d HEAD@{67}: checkout: moving from about to master
c94fb42 HEAD@{68}: commit: Add contents to about page
27b0924 HEAD@{69}: commit: Add empty page in about section
f79223d HEAD@{70}: checkout: moving from master to about
f79223d HEAD@{71}: commit (merge): Merge branch 'crazy'
049c9d9 HEAD@{72}: checkout: moving from crazy to master
ebb4171 HEAD@{73}: commit: Add news item for rainbow
4310454 HEAD@{74}: checkout: moving from master to crazy
049c9d9 HEAD@{75}: merge news-hotfix: Fast-forward
1a27d0e HEAD@{76}: checkout: moving from news-hotfix to master
049c9d9 HEAD@{77}: commit: Add 1st news item
1a27d0e HEAD@{78}: checkout: moving from master to news-hotfix
1a27d0e HEAD@{79}: checkout: moving from crazy-alt to master
d247771 HEAD@{80}: commit: Make a REAL rainbow
4310454 HEAD@{81}: checkout: moving from crazy to crazy-alt
4310454 HEAD@{82}: commit: Link index.html to rainbow.html
6a43f42 HEAD@{83}: commit: add CSS stylesheet to rainbow.html
b9f2b14 HEAD@{84}: merge master: Merge made by the 'recursive' strategy.
95a36a7 HEAD@{85}: checkout: moving from master to crazy
1a27d0e HEAD@{86}: merge css: Fast-forward
3553479 HEAD@{87}: checkout: moving from css to master
1a27d0e HEAD@{88}: commit: link HTML pages to stylesheet
019e981 HEAD@{89}: commit: Add CSS stylesheet
3553479 HEAD@{90}: checkout: moving from master to css
3553479 HEAD@{91}: checkout: moving from crazy to master
95a36a7 HEAD@{92}: commit: Rename crazy.html to rainbow.html
e1bc771 HEAD@{93}: reset: moving to HEAD
e1bc771 HEAD@{94}: commit: add a rainbow to crazy.html
12e24f0 HEAD@{95}: checkout: moving from 12e24f0c4e03b3c991b287230548d8bdad3882d7 to crazy
12e24f0 HEAD@{96}: checkout: moving from master to 12e24f0
3553479 HEAD@{97}: reset: moving to HEAD
3553479 HEAD@{98}: revert: Revert "Add a crazzy experiment"
12e24f0 HEAD@{99}: checkout: moving from 453c8a4db079c3d235e3470754a79a22ea0f0afd to master
453c8a4 HEAD@{100}: checkout: moving from master to v1.0
12e24f0 HEAD@{101}: commit: Add a crazzy experiment
453c8a4 HEAD@{102}: checkout: moving from 6a442fcc4ab51362713f09ed5eadc7af767db833 to master
6a442fc HEAD@{103}: checkout: moving from 1047951bab2636a3bc90682e48d9fb32644da036 to 6a442fc
1047951 HEAD@{104}: checkout: moving from master to 1047951
453c8a4 HEAD@{105}: commit: Add navigation links
1047951 HEAD@{106}: commit: t Add blue an orange html files
6a442fc HEAD@{107}: commit (initial): Create index page for the message
```

The resulting output should look something like the following. Depending on your version of Git, the message might be slightly different. You can press space to scroll through the content or q to exit.

The above listing reflects our last few actions. For example, the current HEAD, denoted by HEAD@{0}, resulted from reseting HEAD to HEAD~1. Four actions ago, the yellow page was applied during our rebase, as shown in HEAD@{3}.

The **reflog** is a **chronological** listing of our history, without regard for the repository's branch structure. This lets us find **dangling commits** that would otherwise be lost from the project history.

# 	* [Revive the Lost Commit](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

At the beginning of each **reflog** entry, you will find a commit ID representing, the HEAD~ after that action. Check out the commit at **HEAD@{2}**, which should be where the rebase added the green page (change the ID below to the ID from your reflog)

```console
$ git checkout d417237
Note: switching to 'd417237'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at d417237 Add green page
```

This puts us in a **detached HEAD state**, which means our HEAD is no longer on the tip of a branch. We are actually in the opposite situation as we were in [Undoing Changes]() when we checked our a commit **before** the branch tip. Now, we are looking at a commit **after** the tip of the branch, but we still have a detached **HEAD**:

![Screen Shot 2020-06-01 at 17 49 41](https://user-images.githubusercontent.com/24994818/83462250-58988f00-a430-11ea-8d1d-c476cb41dcf4.png)

To turn our dangling commit into a full-fledged branch, all we have to do is create one.

```console
$ git checkout -b green-page
Switched to a new branch 'green-page'
```

We now have a branch that can be merged back into the project:

![Screen Shot 2020-06-01 at 17 53 28](https://user-images.githubusercontent.com/24994818/83462430-d197e680-a430-11ea-815e-202f989519fc.png)

The above diagram makes it easy to see that the **green-page** branch is a extension of **new-pages**, but how would we figure this out if we weren't drawing out the state of our repository every step of the way ?

# 	* [Filter the Log History](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

To view the differences between branches, we can use Git's log-filtering syntax.

```console
$ git log new-pages..green-page
commit d41723777cff192f4b4453fe6115a997e3aeb1a5 (HEAD -> green-page)
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 13:19:55 2020 -0500

    Add green page
```

This will display all commits contained in **green-page** that are not in the **new-pages** branch. The above command tells us the **green-page** contains one more snapshot than **new-pages**: our dangling commit (although, it is not really dangling any more since we created a branch for it).

You can also use this syntax to limit the output of **git log**. For example, to display the ast 4 commits on the current branch, you could use.

```console
$ git log HEAD~4..HEAD
commit d41723777cff192f4b4453fe6115a997e3aeb1a5 (HEAD -> green-page)
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 13:19:55 2020 -0500

    Add green page

commit 1b2f067a2b67f40fc8a50b1d21d49469b3ff50d2 (new-pages)
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 17:46:40 2020 -0500

    Add yellow page

commit cb8d72bc066d0a4f60110a9cbd7351421cfe463c
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 17:43:00 2020 -0500

    Add red page

commit 20b9d5d6d3bdb09d440f9067bc9b3bbdfa308446 (master)
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Tue May 26 18:50:56 2020 -0500

    Add link to about section in home page
```

However, this is a bit verbose for such a common task, so Git developers added the -n flag as an easier way to limit output.

```console
$ git log -n 4
commit d41723777cff192f4b4453fe6115a997e3aeb1a5 (HEAD -> green-page)
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 13:19:55 2020 -0500

    Add green page

commit 1b2f067a2b67f40fc8a50b1d21d49469b3ff50d2 (new-pages)
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 17:46:40 2020 -0500

    Add yellow page

commit cb8d72bc066d0a4f60110a9cbd7351421cfe463c
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 17:43:00 2020 -0500

    Add red page

commit 20b9d5d6d3bdb09d440f9067bc9b3bbdfa308446 (master)
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Tue May 26 18:50:56 2020 -0500

    Add link to about section in home page
```

The -n 4 parameter tells Git to show only the last four commits from the current HEAD, making it the equivalent of the HEAD~4..HEAD syntax shown above. Similarly, -n 3, -n 2, and -n 1 would display three, two, and one commit, respectively. This feature becomes very useful once a repository grows beyond one screenful of history.

# 	* [Merge in the Revived Branch](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

We have revived our lost commit, and now we are ready to merge everything back into the **master** branch. Before we do the merge, let's see exactly what we are merging:

```console
$ git checkout master
Switched to branch 'master'
```

```console
$ git log HEAD..green-page --stat
commit d41723777cff192f4b4453fe6115a997e3aeb1a5
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 13:19:55 2020 -0500

    Add green page

 green.html | 14 ++++++++++++++
 index.html |  3 +++
 2 files changed, 17 insertions(+)

commit 1b2f067a2b67f40fc8a50b1d21d49469b3ff50d2
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 17:46:40 2020 -0500

    Add yellow page

 index.html  |  3 +++
 yellow.html | 14 ++++++++++++++
 2 files changed, 17 insertions(+)

commit cb8d72bc066d0a4f60110a9cbd7351421cfe463c
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 17:43:00 2020 -0500

    Add red page

 index.html |  5 ++++-
 red.html   | 14 ++++++++++++++
 2 files changed, 18 insertions(+), 1 deletion(-)
```

The **$ git log HEAD..green-page** command shows us only those commits in **green-page** that are not in **master** (since master is the current branch, we can refer to it as HEAD). The new **--stat** flag includes information about which files have been changed in each commit. For example, the most recent commit tells us that 14 lines were added to the **green.html** file and 3 lines were added to **index.html**:

```c
commit d41723777cff192f4b4453fe6115a997e3aeb1a5
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 13:19:55 2020 -0500

    Add green page

 green.html | 14 ++++++++++++++
 index.html |  3 +++
 2 files changed, 17 insertions(+)
```

If we didn't already know what was in this new commit, the log output would tell us which files we needed to look at. But, we authored all these changes, so we can skip right to the merge.

```console
$ git merge green-page
Updating 20b9d5d..d417237
Fast-forward
 green.html  | 14 ++++++++++++++
 index.html  | 11 ++++++++++-
 red.html    | 14 ++++++++++++++
 yellow.html | 14 ++++++++++++++
 4 files changed, 52 insertions(+), 1 deletion(-)
 create mode 100644 green.html
 create mode 100644 red.html
 create mode 100644 yellow.html
```

The following diagram shows us the state our repository after the merge.

![Screen Shot 2020-06-02 at 13 33 12](https://user-images.githubusercontent.com/24994818/83556525-af0bd900-a4d5-11ea-9407-23d61d12ff52.png)

```console
d417237 Add green page
1b2f067 Add yellow page
cb8d72b Add red page
20b9d5d Add link to about section in home page
71153c2 Begin creating bio pages (added message to mary)
f4bb8c3 Create the about page
74afd90 Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```

Note that the green-page branch already contains all the history of **new-pages**, which is why we merged the former instead of the latter. It this was not the case, Git would complain when we try to run the following command:

```console
$ git branch -d new-pages
Deleted branch new-pages (was 1b2f067).
```

We can go ahead and delete the green 

```console
$ git branch -d green-page
Deleted branch green-page (was d417237).
```

# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

This module took an in-depth look at rebasing, resetting, and the reflog. We learned how to split old commits into one or more new commits, and how to revive "lost" commits. Hopefully, this has given you a better understanding of the interaction between the working directory, the stage, branches, and commited snapshots. We also explored some new options for displaying our commit history, which will become an important skill as our project grows.

WE did a lot of work with the branch tips this module. It is important to realize that Git uses the tip of a branch to represent **entire branch**. That is to say, a branch is actually a pointer to a single commit- not a containter for a series of commits. This idea has been implicitly reflected in our diagrams:

![Screen Shot 2020-06-02 at 13 45 55](https://user-images.githubusercontent.com/24994818/83557547-740aa500-a4d7-11ea-8458-145596a4191d.png)

The history is represented by the parent of each commit (designated by arrows), not the branch itself. So, to request a new branch, all Git has to do is create a reference to the current commit. And, to add a snapshot to a branch, it just has to move the branch reference to the new commit. An understanding of Git's branch representation should make it easier to wrap your head around merging, rebasing, and other kinds of branch manipulation.

We will revisit Git's internal representation of a repository in the final module of his tutorial. But now, we are finally ready to discuss multi-user development, which happens to rely entirely on Git branches.

# 	* [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git reflog
```
```console
$ git reset --mixed HEAD~n
```
Move the HEAD backward n commits, but do not change the working directory

```console
$ git reset --hard HEAD~n
```
Move the HEAD backward n commits, and change the working directory to match.


```console
$ git log since..until
```
Display the commits reachable from until but not from since. These parameters can be either commit ID's o branch names.


```console
$ git log --stat
```
Include extra information about altered files in the log output.

# 8. [Remotes](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Simply put, a **remote repository*** is one that is not your own. It can be another Git repository that is on your company's network, the internet, or even your local file system, but the point is that it is a repository distinct from your my-git-repository project.

We have already seen how branches can streamline a workflow within a single repository, but they also happen to be Git's mechanism for sharing commits between repositories. **Remote Brances** act just like the local branches that we have been using, only the represent a branch in someone else's repository.

![Screen Shot 2020-06-03 at 12 30 45](https://user-images.githubusercontent.com/24994818/83668761-1721f400-a596-11ea-9f23-26b12b25960e.png)

This means we can adapt our merging and rebasing skills to make Git fantastic collaboration tool. Over the next few modules, we will be exploring various multi-user workflows by pretending to be different developers woking on our example website.

For several parts of this module, we are going to pretend to be Mary, the graphic designer for our website. Mary's actions are clearly denoted by including her name in the heading of each step.

# 	* [Clone the Repository (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

First, Mary needs her own copy of the repository to work with. The **Distributed Workflows** module will discuss network-based remotes, but right new we are just going to store them on the local filesystem.

```console
cd /Users/carlossantiagocruz/iOS/RysGitTutorialRepository
```

```console
cd ..
```

- Before we continue, I have to go back to fix the following command to pass the --local flag to do the correct cloning.

```console
$ git clone --local RysGitTutorialRepository/ RysGitTutorialMarysRepository
Cloning into 'RysGitTutorialMarysRepository'...
done.
```

```console
$ cd RysGitTutorialMarysRepository/
Wed Jun 03 ~/iOS/RysGitTutorialMarysRepository 
$ ls
about        green.html   news-1.html  orange.html  red.html     yellow.html
blue.html    index.html   news-2.html  rainbow.html style.css
```

The first two lines navigate the command shell to the directory **above** RysGitTutorialMarysRepository. Make sure to change to the actual path to your repository. The **git clone** command copies our repository into RysGitTutorialMarysRepository, which will reside in the same directory as my git repository. Then, we navigate to the Mary's repository so we can start pretending to be Mary.

First show all directories involved

```console
$ ls RysGitTutorial*
RysGitTutorialRepository:
blue.html    orange.html  style.css    news-1.html  rainbow.html news-2.html  about        green.html   index.html   red.html     yellow.html

RysGitTutorial:
LICENSE   README.md

RysGitTutorialMarysRepository:
about        blue.html    green.html   index.html   news-1.html  news-2.html  orange.html  rainbow.html red.html     style.css    yellow.html
```

Run **git log** verify that Mary's repository is in fact a copy of our original repository.

```console
$ git log --oneline
d417237 (HEAD -> master, origin/master, origin/HEAD) Add green page
1b2f067 Add yellow page
cb8d72b Add red page
20b9d5d Add link to about section in home page
71153c2 Begin creating bio pages (added message to mary)
f4bb8c3 Create the about page
74afd90 Add article for 2nd news item
5142364 Add 2nd news item to index page
f79223d Merge branch 'crazy'
ebb4171 Add news item for rainbow
049c9d9 Add 1st news item
4310454 Link index.html to rainbow.html
6a43f42 add CSS stylesheet to rainbow.html
b9f2b14 Merge branch 'master' into crazy
1a27d0e link HTML pages to stylesheet
019e981 Add CSS stylesheet
95a36a7 Rename crazy.html to rainbow.html
e1bc771 add a rainbow to crazy.html
3553479 Revert "Add a crazzy experiment"
12e24f0 Add a crazzy experiment
453c8a4 (tag: v1.0) Add navigation links
1047951 t Add blue an orange html files
6a442fc Create index page for the message
```
# 	* [Configure The Repository (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

First off, Mary needs to configure her repository so that we know who contributed what to the project.

```console
$ git config user.name "Mary"
```

```console
$ git config user.mail mary.example@icloud.com
```

You may recall from the first module that we used a **--global** flag to set the configuration for the entire Git installation. But since Mary's repository is on the local **filesystem**, she needs a **local** configuration.

```console
$ ls .git
info        hooks       packed-refs HEAD        index
description objects     refs        logs        config
```

```console
$ cat .git/config 
[core]
	repositoryformatversion = 0
	filemode = true
	bare = false
	logallrefupdates = true
	ignorecase = true
	precomposeunicode = true
[remote "origin"]
	url = /Users/carlossantiagocruz/iOS/RysGitTutorialRepository/
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
	remote = origin
	merge = refs/heads/master
[user]
	name = Mary
	mail = mary.example@icloud.com
```

Use a text editor to open up the file called **config** in the **.git** directory of Mary's project (you may  need to enable hidden files to see .git). This is where local configurations are stored, and we see Mary's information at the bottom of the file. Note that this overrides the global configuration that we set in **The basics**

# 	* [Start Mary's Day (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Today, Mary is going to be working on her bio page, which she should develop in a separate branch:

```console
git checkout -b bio-page
```

Mary can create and check out branches just like we did in our copy of the project. Her repository is a completely isolated development enviroment, and she can do whatever she wants in her without worrying about what's going on in my git repository. Just as branches are an abstraction for the working directory, the staged snapshot, and a commit history, a repository is an abstraction for branches.

# 	* [Create Mary's Bio Page](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Let's complete Mary's biography page. In mary's repository, change about/mary.html to:

```console
<html lang="en">
<head>
  <title>About Mary</title>
  <link rel="stylesheet" href="../style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1>About Mary</h1>
  <p>I'm a graphic designer.</p>

  <h2>Interests</h2>
  <ul>
    <li>Oil Painting</li>
    <li>Web Design</li>
  </ul>

  <p><a href="index.html">Return to about page</a></p>
</body>
</html>
```

Again, we are developing this in a branch as a best-practice step: our **master** branch is only for stable, tested code. Stage and commit the snapshot, then take a look at the result.

```console
$ git commit -a -m "Add bio page for mary"
[bio-pages 0d746d0] Add bio page for mary
 1 file changed, 21 insertions(+), 1 deletion(-)
```

```console
Author: Mary <c.santiago.cruz@gmail.com>
Date:   Fri Jun 5 11:09:51 2020 -0500

    Add bio page for mary
```

The **Author** field in the log output should reflect the local configurations we made for Mary's name and email. Remember that -n -1 flags limits history output to a single commit.

```console
$ git log -n 1
commit 0d746d0a6eb7b983e661e47f9347b196b2967a0d (HEAD -> bio-pages)
Author: Mary <c.santiago.cruz@gmail.com>
Date:   Fri Jun 5 11:09:51 2020 -0500

    Add bio page for mary
```

[Check why the email was not changed]()

# 	* [Publish the Bio Page (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Now, we can publish the bio page by merging into the **master** branch:

```console
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
```

Then try to merge

Oh Crap !!!

```console
merge: bio-page - not something we can merge
```

I suppose the repository was not created correctly, reading more documentation it suggest to pass the --local flag when you cloning.

So do it again, and configure.

```console
$ git clone --local RysGitTutorialRepository/ RysGitTutorialMarysRepository
```

the configure:

```console
$ git config user.name "Mary"
```

```console
$ git config user.mail mary@repository.com
```

Then merge again


```console
$ git merge bio-page
Updating d417237..49baa6e
Fast-forward
 about/mary.html | 21 ++++++++++++++++++++-
 1 file changed, 20 insertions(+), 1 deletion(-)
```
Woala ! Now it works !!!

Of course, this results in a fast-forward merge. 

![Screen Shot 2020-06-05 at 11 43 05](https://user-images.githubusercontent.com/24994818/83902300-be7f6200-a721-11ea-880d-fb7689c54d45.png)

Notice that both repositories have normal, local branches - we have not had any interaction between the two repositories, so we don't see any remote branches yet. Before we switch back to my git repository, let's examine Mary's remote connections.

# 	* [View Remote Repositories (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Mary can list the connections she has to other repositories using the following command.

```console
Fri Jun 05 ~/iOS/RysGitTutorialMarysRepository 
$ git remote
origin
```

Apparently, she has a remote called **origin**. When you clone a repository, Git automatically adds an **origin**. When you clone a repository, Git automatically adds an **origin** remote pointing to the original repository, under the assumption that you will probably want to interact with it down to the road. We can request a little bit more information with -v (verbose) flag:

```cosole
Fri Jun 05 ~/iOS/RysGitTutorialMarysRepository 
$ git remote -v
origin	/Users/carlossantiagocruz/iOS/RysGitTutorialRepository/ (fetch)
origin	/Users/carlossantiagocruz/iOS/RysGitTutorialRepository/ (push)
```

This shows the full path to our original repository, verifying that **origin** is a remote connection to my git repository. The same path is designated as a **"fetch"** and a **"push"** location. We will see what these means in a moment.

# 	* [Return to Your Repository (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

OK, we are done being Mary, and we can return to our own repository:

```console
$ cd ../RysGitTutorialRepository/
```

Notice that Mar's bio page is still empty. It is very important to understand that this repository and Mary's repository are completely separate. While she was altering her bio page, we could have been doing all sorts of other things in my git repository. We could have even changed her bio page, which would result in a merge conflict when we try to pull her changes in.

# 	* [Add Mary as a Remote (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Before we can get ahold of Mar's bio page, we need access to her repository. Let's look at our current list of remotes:

```console
$ git remote
```

We don't have any (**origin** was never created because we didn't clone from anywhere). So, let's add Mary as a remote repository

```console
$ git remote add mary ../RysGitTutorialMarysRepository/
```

```console
Fri Jun 05 ~/iOS/RysGitTutorialRepository 
$ git remote -v
mary	../RysGitTutorialMarysRepository/ (fetch)
mary	../RysGitTutorialMarysRepository/ (push)
```

We can now use **mary** to refer to Mar's repository, which is located at ../RysGitTutorialMarysRepository. The **git remote add** command is used to bookmark another Git repository for easy access, and our connections can be seen in the figure below.

![Screen Shot 2020-06-05 at 12 14 05](https://user-images.githubusercontent.com/24994818/83904777-1cae4400-a726-11ea-992e-9a47fb3bf53e.png)

Now that our remote **repositories are setup, we will spend the rest of the module discussing remote **branches**

# 	* [Fetch Mary's Branches (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

As noted earlier, we can use remote branches to access snapshots from another repository. Let's take a look at our current remote branches with the - flag.]()

```console
$ git branch -r
```

Again, we don't have any. To populate our remote branch listing, we need to **fetch** the branches from Mary's repository:

```console
$ git fetch mary 
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 1), reused 0 (delta 0)
Unpacking objects: 100% (4/4), 604 bytes | 100.00 KiB/s, done.
From ../RysGitTutorialMarysRepository
 * [new branch]      bio-page   -> mary/bio-page
 * [new branch]      master     -> mary/master
```

```console
Fri Jun 05 ~/iOS/RysGitTutorialRepository 
$ git branch -r
  mary/bio-page
  mary/master
```

This will go to the **"fetch"** location shown in **git remote -v** and download all of the branches it finds there into our repository. The resulting branches are shown below.

```console
  mary/bio-page
  mary/master
```

Remote branches are always listed in the form remoteName/branchName so that they will never be mistaken for local branches. The above listing reflects the sate of Mar's repository at the time of the fetch, but they will not be automatically updated if Mary continues developing any of her branches.

That is to say, our remote branches are not **direct** links into Mary's repository -they are read-only copies of her branches, stored in our own repository. This means that we would have to do another fetch to access new updates.

![Screen Shot 2020-06-05 at 12 25 09](https://user-images.githubusercontent.com/24994818/83905628-a1e62880-a727-11ea-944a-77e60c9a6399.png)

The above figure shows the state of **our** repository. We have access to Mary's snapshot (represented by sqeares) and her branches, even though we don't have a real-time connection to Mary's repository.

# 	* [Check out a Remote Branch](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Let's check out a remote branch to review Mary's changes.

```console
Fri Jun 05 ~/iOS/RysGitTutorialRepository 
$ git checkout mary/master
Note: switching to 'mary/master'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 49baa6e Add bio page for Mary
```

This puts us in a **detached** HEAD state, just like we were in when we checked out a dangling commit. This should not be that surprising, considering that our remote branches are **copies** of Mary's branches. Checking out a remote branch takes our HEAD off the tip of a local branch, illustrated by the following diagram.

![Screen Shot 2020-06-05 at 12 39 29](https://user-images.githubusercontent.com/24994818/83906672-a01d6480-a729-11ea-83ee-c616558f6d26.png)

We can't continue developing if we are not on a local branch. To build on **mary/master** we either need to merge it into our own local **master** or create another branch. We did the latter in Branches, Part I to build on an old commit and in the previous module to revive a "lost commit, but right now we are just looking at what Mary did, so the **detached** HEAD state does not really affect us.

# 	* [Find Mary's Changes](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

We can use the same log-filtering syntax from the previous module to view Mary's changes:

```console
Fri Jun 05 ~/iOS/RysGitTutorialRepository 
$ git log master..mary/master --stat
commit 49baa6e81a7ad87714540ec9ce9fceaaa12409c1 (HEAD, mary/master, mary/bio-page)
Author: Mary <c.santiago.cruz@gmail.com>
Date:   Fri Jun 5 11:34:45 2020 -0500

    Add bio page for Mary

 about/mary.html | 21 ++++++++++++++++++++-
 1 file changed, 20 insertions(+), 1 deletion(-)
```

This shows us what Mary has added to her master branch, but it is also a good idea to see if we have added any new changes that are not in Mary's repository

```console
Fri Jun 05 ~/iOS/RysGitTutorialRepository 
$ git log mary/master..master --stat
Fri Jun 05 ~/iOS/RysGitTutorialRepository 
$ 
```

This will not output anything, since we haven't altered our data-base since Mary cloned it, In other words, our history hasn't **diverged** - **we are just behind by a commit**.

# 	* [Merge Mary's Changes](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Let's approve Mary's changes and integrate them into our own **master** branch.

```console
Sat Jun 06 ~/iOS/RysGitTutorialRepository 
$ git merge mary/master
Updating d417237..49baa6e
Fast-forward
 about/mary.html | 21 ++++++++++++++++++++-
 1 file changed, 20 insertions(+), 1 deletion(-)
Sat Jun 06 ~/iOS/RysGitTutorialRepository 
```

Even though **mary/master** is a remote branch, this still results in a **fast-forward** merge because there is a linear path from our **master** to the tip of **mary/master**

![Screen Shot 2020-06-06 at 12 44 47](https://user-images.githubusercontent.com/24994818/83950893-86e0ea80-a7f3-11ea-8a1a-aa3b15bfe9ee.png)

After the merge, the snapshots from Mary's remote branch become a part of a our local **master** branch. As a result, our **master** is now synchronized with Mary's:

![Screen Shot 2020-06-06 at 12 46 36](https://user-images.githubusercontent.com/24994818/83950922-c6a7d200-a7f3-11ea-9969-4f0a5bb9d842.png)

Notice that we only interacted with Mary's **master** branch, even though we had access to her **bio-page**. If we hadn't been pretending to be Mary, we wouldn't have known what this feature branch was for it or if it was ready to be merged. But, since we've designated **master** as a stable branch for the project, it was safe to integrate those updates (assuming Mary was also aware of this convention).

# 	* [Push a Dummy Branch](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

To complement our **git fetch** command, we will take a brief look at **pushing**. Fetching and pushing are **almost** opposites, in that fetching imports branches, while pushing exports branches to another repository. Let's take a look:

```console
$ git branch dummy
```

This creates a new branch called **dummy**.

```console
$ git push mary dummy
Total 0 (delta 0), reused 0 (delta 0)
To ../RysGitTutorialMarysRepository/
 * [new branch]      dummy -> dummy
```

This sends it to Mary. Switch into Mary's repository to see what we did:

```console
Mon Jun 08 ~/iOS/RysGitTutorialRepository 
$ cd ../RysGitTutorialMarysRepository/
```

```console
$ git branch
  bio-page
  dummy
* master
```

You should find a new **dummy** branch in her **local** branch listing. I said that **git fetch** and **git push** are **almost** opposites because **pushing creates a new local branch**, while **fetching imports commits into remote branches**.

Now put yourself in Mary's shoes. She was a developing in her own repository when, all of a sudden, a new **dummy** branch appeared out of nowhere. Obviously, pushing branches into other people's repositories can make for a chaotic workflow. So, as a general rule, **you should never push into another developer's repository. But then, why does **git push** even exist?

Over the next few modules, we will see that pushing is a necessary tool for maintaining public repositories. Until then, just remember to never, ever push into one of your friends's repositories. Let's get rid of these dummy branches and return to our repository.

```console
$ git branch -d dummy
Deleted branch dummy (was 49baa6e).
```

Go back to your repository

```console
Mon Jun 08 ~/iOS/RysGitTutorialMarysRepository 
$ cd ../RysGitTutorialRepository/
```

the delete the branch

```console
$ git branch -d dummy
Deleted branch dummy (was 49baa6e).
```

# 	* [Push a New Tag](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

An important property of **git push** is that it does not automatically push tag associated with a particular branch. Let's examine this by creating a new tag.

```cosole
Wed Jun 10 ~/iOS/RysGitTutorialRepository 
$ git tag -a v2.0 -m "An even stabler version of the website"
```

We now have a v2.0 tag in my git repository, which we can see by running the **git tag** command. Now, let's try pushing the branch to Mary's repository.

```
$ git push mary master
Everything up-to-date
```

Git will say her **master** branch is already up-to-date, and her repository will remain unchanged. Instead of pushing the branch that contains the tag. Git requires us to manually push the tag itself:

```console
$ git push mary v2.0
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 180 bytes | 180.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0)
To ../RysGitTutorialMarysRepository/
 * [new tag]         v2.0 -> v2.0
```

You should now be able to see the v2.0 tag in Mary's repository with a quick **git tag**. It is very easy to forget to push new tags, so if it seems like your project has lost a tag or two, it is most likely because you didn't to push them to the remote repository.

```console
Wed Jun 10 ~/iOS/RysGitTutorialRepository 
$ cd ../RysGitTutorialMarysRepository/
Wed Jun 10 ~/iOS/RysGitTutorialMarysRepository 
$ git tag
v1.0
v2.0
```

# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

In this module, we learned how remote branches can be used to access content in someone else's repository. The remotes listed in **git remote** are merely bookmarks for a full path to another repository. We used a local path, but as we will soon see, Git can use the SSH protocol to access repositories on another computer.

The convention of **master** as a stable branch allowed us to pull changes without consulting Mary, but this doesn't necessarily have to be the case. When implementing your own workflow, Gif offers you a lot of flexibility about when and where you should pull from your team members. As long as you clearly define your project conventions, you can designate a special uses or privileges to **any** branch.

That said, it is important to note that remotes are for **people**, whereas branches are for **topics**. Do **not** create separate branches for each of your developers -give them separate repositories and bookmark them with **git remote add**. Branches should always be for project development, not user management.

Now that we know how Git shares information between repositories, we can add some more structure to our multi-user development environment. The next module will show you how to set up and access a shared central repository.

# 	* [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git -- clone remothePath
```
Create a copy of a remote Git repository

```console
$ git remote
```
List remote repositories.


```console
$ git remote add remoteName remotePath
```
Add a remote repository


```console
$ git fetch remoteName
```
Download remote branch information, but do not merge anything

```console
$ git merge remoteName/branchName
```
Merge a remote branch into the checked-out branch

```console
git branch -r
```
List remote branches

```console
git push remoteName branchName
```
Push a local branch to another repository

```console
$ git branch -r
```
List remote branches.

```console
$ git push remoteName branchName
```
Push a local branch to another repository

```consol
git push remoteName tagName
```
Push a tag to another repository

# 9. [Centralized Workflows](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

In the previous module, we shared information directly between two developers repositories: my git repository and mary's repository. This works for very small teams developing simple programs, but larger projects call for a more structured environment. This module Introduces one such environment the **centralized workflow**.

We will use a third Git Repository to act as a central communication hub between us and Mary. Instead of pulling changes into my git repository from mary's repository and vice versa, we will push to an fetch from a **dedicated storage repository**. After this module, our workflow will look like the following.

![Screen Shot 2020-06-11 at 11 16 40](https://user-images.githubusercontent.com/24994818/84412570-106a3100-abd5-11ea-8858-0e6e6d43749b.png)

Typically, you would store the central repository on a server to allow internet-based collaboration. Unfortunately, server configuration can vary among hosting providers, making it hard to write universal step-by-step instructions. So, we will continue exploring remote repositories using our local filesystems, just like in the previous module.

If you have access to server, feel free to use it to host the central repository that we are about to create. You will have to provide SSH paths to your server repository in place of the paths provided below, but other than that, you can follow this module's instructions as you find them. For everyone else, our network-based Git experience will begin in the next module.

# 	* [Create a Bare Repository (Central)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

First, let's create our central **"Communication Hub"**. Again, make sure to change /path/to/my-git-repo to the actual path to your repository. If you have decided to host the central repository on your server, you should SSH into it an run the **git init** command wherever you would like to store the repository.

The instructions leads you to the container directory of your git repository

```console
$ cd RysGitTutorialRepository/
```

```console
$ cd ..
```

```console
$ git init --bare central-repo.git
Initialized empty Git repository in /Users/carlossantiagocruz/Documents/SWIFT-PROGRAMMING/central-repo.git/
```

As in the very first module, **git init** creates a new repository. But this time, we used the **bare** flag to tell Git that we don't want a working directory. This will prevent us from developing in the central repository, which eliminates the possibility of messing up another user's environment with **git push**. A central repository is only supposed to act as a **storage facility** - not a development environment.

If you examine the contest of the resulting central-repo.git folder, you will notice that it contains the exact same files as the .git folder in our my-git-repo project. Git has **literally** gotten rid of our working directory. The conventional .git extension in the directory name is a way to convey this property.

# 	* [Update Remotes (Mary and You)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

We have successfully set up a central repository that can be used to share updates between us, Mary, and any other developers. Next, we should add it as a remote to both mary's repository and my git repository.

```console
Fri Jun 12 ~/iOS 
$ cd RysGitTutorialMarysRepository/
Fri Jun 12 ~/iOS/RysGitTutorialMarysRepository 
$ git remote rm origin
Fri Jun 12 ~/iOS/RysGitTutorialMarysRepository 
$ git remote add origin ../central-repo.git
```

Now for our repository

```console
$ cd ../RysGitTutorial
Fri Jun 12 ~/iOS/RysGitTutorialMarysRepository 
$ cd ../RysGitTutorialRepository/
Fri Jun 12 ~/iOS/RysGitTutorialRepository 
$ git remote add origin ../central-repo.git/
Fri Jun 12 ~/iOS/RysGitTutorialRepository 
$ git remote rm mary
```

Note that we deleted the remote connections between Mary and our git repository with **git remote rm**. For the rest of this module we will only use **the central repository** to share updates.

If you decided to host the central repository on a **server**, you will need to change the **../centra-repo.git** path to: **ssh://user@example.com/to/central-repo.git** substituting your **SSH username** and **Server location** for **user@example.com** and the central repository's location for **path/to/central-repo.git**

# 	* [Push the Master Branch](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

We didn't **clone** the central repository -We just initialized it as a **bare repository**. This means it does not have any of our project history yet. We can fix that using the **git push** command introduced the last module.

```console
Sat Jun 13 ~/iOS/RysGitTutorialRepository 
$ git push origin master
Enumerating objects: 80, done.
Counting objects: 100% (80/80), done.
Delta compression using up to 4 threads
Compressing objects: 100% (77/77), done.
Writing objects: 100% (80/80), 9.48 KiB | 422.00 KiB/s, done.
Total 80 (delta 35), reused 0 (delta 0)
To ../central-repo.git/
 * [new branch]      master -> master
```

Our central repository now contains our entire **master branch** which can **double-check** with the following

```console
Sat Jun 13 ~/iOS/central-repo.git 
$ cd ../central-repo.git/
```

```console
commit 49baa6e81a7ad87714540ec9ce9fceaaa12409c1
Author: Mary <c.santiago.cruz@gmail.com>
Date:   Fri Jun 5 11:34:45 2020 -0500

    Add bio page for Mary

commit d41723777cff192f4b4453fe6115a997e3aeb1a5
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 13:19:55 2020 -0500

    Add green page

commit 1b2f067a2b67f40fc8a50b1d21d49469b3ff50d2
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 17:46:40 2020 -0500

    Add yellow page

commit cb8d72bc066d0a4f60110a9cbd7351421cfe463c
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 30 17:43:00 2020 -0500

    Add red page

commit 20b9d5d6d3bdb09d440f9067bc9b3bbdfa308446
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Tue May 26 18:50:56 2020 -0500

    Add link to about section in home page

commit 71153c2e6ce3bdf5de20145c74a7e03dce3e689a
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Tue May 26 17:52:52 2020 -0500

    Begin creating bio pages (added message to mary)
    
    Add empty HTML page for Mary's bio

commit f4bb8c3c896c970fe8eb4a20c1322763bf42ba19
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Tue May 26 11:32:08 2020 -0500

    Create the about page
    
    Add contents to about page

commit 74afd9060deceb1ab2c8e66959cb97082aaa7450
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Tue May 26 16:32:13 2020 -0500

    Add article for 2nd news item

commit 514236461070f0cb3416a36985003636b49aa6c5
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Tue May 26 16:20:09 2020 -0500

    Add 2nd news item to index page

commit f79223d618f18d4ef58743e8f48e9abdd8b757cc
Merge: 049c9d9 ebb4171
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Mon May 25 18:45:20 2020 -0500

    Merge branch 'crazy'

commit ebb417105d308a3aaee55459b180d60b95a1b182
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Mon May 25 17:55:21 2020 -0500

    Add news item for rainbow

commit 049c9d941dfe20fc707fd3aa1eaf2b534a652368
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Mon May 25 09:15:43 2020 -0500

    Add 1st news item

commit 43104541f20a65f00d1c21679236ea0798353f19
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Mon May 25 08:11:35 2020 -0500

    Link index.html to rainbow.html

commit 6a43f42a003090aa434e7ec799c33dc2f29e5095
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sun May 24 12:51:34 2020 -0500

    add CSS stylesheet to rainbow.html

commit b9f2b14a3cd8f7ba33c363d60fedb1392154e46e
Merge: 95a36a7 1a27d0e
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sun May 24 11:43:32 2020 -0500

    Merge branch 'master' into crazy

commit 1a27d0e627f00920537126b1a7f460c656f993ad
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sun May 24 09:06:08 2020 -0500

    link HTML pages to stylesheet

commit 019e981718d56c5cfb26b335d5c9e935075588e6
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sun May 24 08:50:16 2020 -0500

    Add CSS stylesheet

commit 95a36a77010605d457a9e45b3ba3bba77ef02c6f
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 23 10:52:39 2020 -0500

    Rename crazy.html to rainbow.html

commit e1bc77119319d8b38ff46dbddd968f669cc37a4c
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat May 23 09:01:08 2020 -0500

    add a rainbow to crazy.html

commit 355347981e8da24d922766b60f33d93d96e0a1ba
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 21:07:02 2020 -0500

    Revert "Add a crazzy experiment"
    
    This reverts commit 12e24f0c4e03b3c991b287230548d8bdad3882d7.

commit 12e24f0c4e03b3c991b287230548d8bdad3882d7
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 20:34:06 2020 -0500

    Add a crazzy experiment

commit 453c8a4db079c3d235e3470754a79a22ea0f0afd
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 16:53:53 2020 -0500

    Add navigation links

commit 1047951bab2636a3bc90682e48d9fb32644da036
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 13:45:14 2020 -0500

    t Add blue an orange html files

commit 6a442fcc4ab51362713f09ed5eadc7af767db833
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Fri May 22 12:54:21 2020 -0500

    Create index page for the message
```

This should output the familiar history listing of the **master branch**

Recall that **git push** creates **local** branches in the destination repository. We said it was dangerous to push to a friend's repository, as they probably wouln't appreciate new branches appearing at random. However, it is safe to create local branches in **central-repo.git** because it has no working directory, which means it's impossible to disturb anyone's development.

# 	* [Add News Update (You)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Let's see our new centralized collaboration workflow in action by commiting a few more snapshots.

```console
Sat Jun 13 ~/iOS/central-repo.git 
$ cd ../RysGitTutorialRepository/
```

```console
at Jun 13 ~/iOS/RysGitTutorialRepository 
$ git checkout -b news-item
Switched to a new branch 'news-item'
```

Create a file called news-3.html in my git repository and add the following HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Middle East's Silent Beast</title>
  <link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #D90">Middle East's Silent Beast</h1>
  <p>Late yesterday evening, the Middle East's largest
  design house&mdash;until now, silent on the West's colorful
  disagreement&mdash;announced the adoption of
  <span style="color: #D90">Yellow</span> as this year's
  color of choice.</p>
    
  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

Next, add a link to the "News" section of index.html so that it looks like:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>A Colorful Website</title>
	<link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #07F">A Colorful Website</h1>
  <p>This is a website about color!</p>    
  
  <h2 style="color: #C00">News</h2>
  <ul>
	  <li><a href="news-1.html">Blue Is The New Hue</a></li>
		<li><a href="rainbow.html">Our New Rainbow</a></li>
    <li><a href="news-2.html">A Red Rebellion</a></li>
	  <li><a href="news-3.html">Middle East's Silent Beast</a></li>
  </ul>
</body>
</html>
<h2>Navigation</h2>
<ul>
	<li>
    <a href="about/index.html">About Us</a>
  </li>
  <li style="color: #F90">
    <a href="orange.html">The Orange Page</a>
  </li>
  <li style="color: #00F">
		<a href="blue.html">The Blue Page</a>
  </li>
	<li>
    <a href="rainbow.html">The Rainbow Page</a>
  </li>
	<li style="color: #C00">
  	<a href="red.html">The Red Page</a>
	</li>
	<li style="color: #FF0">
  	<a href="yellow.html">The Yellow Page</a>
	</li>
	<li style="color: #0C0">
  	<a href="green.html">The Green Page</a>
	</li>
</ul>
```

Stage and commit a snapshot

```console
Sat Jun 13 ~/iOS/RysGitTutorialRepository 
$ git add news-3.html index.html 
```

```console
Sat Jun 13 ~/iOS/RysGitTutorialRepository 
$ git status
On branch news-item
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html
	new file:   news-3.html
```

```console
Sat Jun 13 ~/iOS/RysGitTutorialRepository 
$ git commit -m "Add 3rd news item"
[news-item 450182a] Add 3rd news item
 2 files changed, 19 insertions(+)
 create mode 100644 news-3.html
```

# 	* [Publish the News Item (You)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Previously **"publishing"** mean merging with the local master branch. But since we are **only** interacting with the central repository, our **master** branch is private again. There is no chance of Mary pulling content directly from our repository.

Instead, everyone accesses updates through the **public** master branch, so **"publishing"** means pushing to the central repository.

```console
Mon Jun 15 ~/iOS/RysGitTutorialRepository 
$ git checkout master
Switched to branch 'master'
```

```console
$ git merge news-item
Updating 49baa6e..450182a
Fast-forward
 index.html  |  1 +
 news-3.html | 18 ++++++++++++++++++
 2 files changed, 19 insertions(+)
 create mode 100644 news-3.html
```

```console
Mon Jun 15 ~/iOS/RysGitTutorialRepository 
$ git branch -d news-item
Deleted branch news-item (was 450182a).
```

```console
Mon Jun 15 ~/iOS/RysGitTutorialRepository 
$ git push origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 703 bytes | 703.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
To ../central-repo.git/
   49baa6e..450182a  master -> master
```

After merging into **master** as we normally would, **git push** updates the central repository's master branch to reflect our **local master**. From our perspective, the **push** can be visualized as the following:

![Screen Shot 2020-06-15 at 10 57 16](https://user-images.githubusercontent.com/24994818/84679499-fee79880-aef6-11ea-9d3e-0acd0bc7211e.png)

Note that this accomplishes the exact same thing as going into the central repository and doing a **fetch/fast-forward** merge, except **git push** allows us to do everything from inside my git repository. We will see some other convenient features of this command later in the module.

# 	* [Update CSS Styles (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Next, let's pretend to be Mary again and add some CSS formatting (she is our graphic designer, after all)

```console
Mon Jun 15 ~/iOS/RysGitTutorialRepository 
$ cd ../RysGitTutorialMarysRepository/
```

```console
Mon Jun 15 ~/iOS/RysGitTutorialMarysRepository 
$ git checkout -b css-edits
Switched to a new branch 'css-edits'
```

Add the following to the end of style.css

```html
h1 {
  font-size: 32px;
}

h2 {
  font-size: 24px;
}

a:link, a:visited {
  color: #03C;
}
```

And, stage ad commit a snapshot.

```console
Mon Jun 15 ~/iOS/RysGitTutorialMarysRepository 
$ git commit -a -m "Add CSS styles for headings and links"
[css-edits 85d575c] Add CSS styles for headings and links
 1 file changed, 12 insertions(+)
```

# 	* [Update another CSS Style](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Opps, Mary forgot to add some formatting. Append the h3 styling to **style.css**:

```html
h3 {
  font-size: 18px;
  margin-left: 20px;
}
```

And of course, stage and commit the updates.

```console
Mon Jun 15 ~/iOS/RysGitTutorialMarysRepository 
$ git commit -a -m "Add CSS styles for 3rd level headings"
[css-edits ecc9090] Add CSS styles for 3rd level headings
 1 file changed, 1 insertion(+)
```

# 	* [Clean up Before Publishing (Mary](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Before Mary considers pushing her updates to the central repository, she needs to make sure she has a clean history. This **must** be done by Mary, because it is near-impossible to change history after it has been made public.

```console
Mon Jun 15 ~/iOS/RysGitTutorialMarysRepository 
$ git rebase -i master
```

```console
pick 85d575c Add CSS styles for headings and links
squash ecc9090 Add CSS styles for 3rd level headings
```

When Git stops to ask for the combined commit message, just use the first commit's message:

```console
Add CSS styles for 3rd level headings
```

Consider what would have happened had Mary rebase **after** pushing to the central repository. She would be re-writing commits that other developers may have already pulled into their project. To Git, Mar's re-written commits look like entirely new commits (since they have different ID's). This situation is shown below.

![Screen Shot 2020-06-15 at 11 32 42](https://user-images.githubusercontent.com/24994818/84682923-02315300-aefc-11ea-8947-5748d6cc11e1.png)

The commits labeled 1 and 2 are the public commits that Mary would be rebasing. Afterwards, the public history is still the exact same as Mary's original history, but now her local master branch has diverged from **origina/master** - even though they represent the same snapshot.

So, to publish her rebased master branch to the central repository, Mary would have to merge with origin/master. This cannot be a fast-forward merge, and the resulting merge commit is likely to confuse her collaborators and disrupt their workflow.

This brings us to **the most important rule to remember** while rebasing: **Nerver, ever rebase commits that have been pushed to a shared repository**

If you need to change a public commit, use the **git revert** command that we discussed in [Undoing Changes](). This creates a new commit with the required modifications instead of re-writing old snapshots.


# 	* [Publish CSS Changes (Mary](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Now that her history is cleaned up, Mary can publish the changes.

```console
Tue Jun 16 ~/iOS/RysGitTutorialMarysRepository 
$ git checkout master
Switched to branch 'master'
```

```console
Tue Jun 16 ~/iOS/RysGitTutorialMarysRepository 
$ git merge css-edits
Updating 49baa6e..61377ba
Fast-forward
 style.css | 13 +++++++++++++
 1 file changed, 13 insertions(+)
```

then:

```console
Tue Jun 16 ~/iOS/RysGitTutorialMarysRepository 
$ git branch -d css-edits
Deleted branch css-edits (was 61377ba).
```

She shouldn't push the css-edits branch to the server, since it is no longer under development, and other collaborators wouldn't know what it contains. However, if we had all decided to develop the CSS edits together and wanted an isolated environment to do so, it would make sense to publish it as an independent branch.

Mary still needs to push the changes to he central repository. But first, let's take a look at the state of everyone's project.

![Screen Shot 2020-06-16 at 9 34 51](https://user-images.githubusercontent.com/24994818/84788346-a8409400-afb4-11ea-8f41-5ccbf2fe44cf.png)

You might be wondering how Mary can push her **local maser** up to the central repository, since it has progressed since Mary last fetch from it. This is common situation when many people developers are working on a project simultaneously. Let's see how Git handles it:

```console
Tue Jun 16 ~/iOS/RysGitTutorialMarysRepository 
$ git push origin master
To ../central-repo.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to '../central-repo.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```

This will output a verbose rejection message. It seems that Git won't let anyone push to a remote server if it doesn't result in a **fast-forward** merge. This prevents us from losing the **"Add 3rd news"** item commit that would need to be overwritten for **origin/master** to match **mary/master**.

# 	* [Pull in Changes (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Mary can solve this problem by pulling in the central changes before trying to push her CSS changes. First, she needs the most up-to-date version of the **origin/master** branch.

```console
Tue Jun 16 ~/iOS/RysGitTutorialMarysRepository 
$ git fetch origin
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 2), reused 0 (delta 0)
Unpacking objects: 100% (4/4), 683 bytes | 85.00 KiB/s, done.
From ../central-repo
 * [new branch]      master     -> origin/master
```

Remember that Mary can see what's in **origin/master** and not in the **local master** using the .. syntax:

```console
Tue Jun 16 ~/iOS/RysGitTutorialMarysRepository 
$ git log master..origin/master
commit 450182ac3baacbcf473d42f100b058d1f64bf1bd (origin/master)
Author: c4arl0s <c.santiago.cruz@gmail.com>
Date:   Sat Jun 13 12:30:08 2020 -0500

    Add 3rd news item
```

And she can also see what's in her **master** that's not in **origin/master**:

```console
Tue Jun 16 ~/iOS/RysGitTutorialMarysRepository 
$ git log origin/master..master
commit 61377ba417dc0ea0dde974e03ae8b3683f5cb260 (HEAD -> master)
Author: Mary <c.santiago.cruz@gmail.com>
Date:   Mon Jun 15 11:07:51 2020 -0500

    Add CSS styles for headings and links
    
    Add CSS styles for 3rd level headings
```

Since both of these output a commit, we can tell that Mary's history diverged. This should also be clear from the diagram below, which shows the updated **origin/master** branch.

![Screen Shot 2020-06-16 at 10 23 26](https://user-images.githubusercontent.com/24994818/84794080-71ba4780-afbb-11ea-9ac0-3942cb7ffdb5.png)

Mary is now in the familiar position of having to pull in changes from another branch. She can either merge, which **cannot be fast-forwarded**, or she can **rebase for a linear history**.

Typically, you will want to rebase your changes on top of those found in your central repository. This is equivalent of saying, **"I want to add my changes to what everyone else has already done"**

As previously discussed, rebasing also eliminates superfluous merge commits. For these reasons, Mary will opt for a rebase. 

```console
$ git rebase origin/master
First, rewinding head to replay your work on top of it...
Applying: Add CSS styles for headings and links
```

After the rebase, Mary's master branch contains everything from the central repository, so she can do a **fast-forward** push to publish her changes.

![Screen Shot 2020-06-16 at 10 30 09](https://user-images.githubusercontent.com/24994818/84794851-60256f80-afbc-11ea-9e21-d746eb4a81c9.png)

# 	* [Pull in Changes (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Finally, we will switch back to our repository and pull in Mary's CSS formatting.

```console
Tue Jun 16 ~/iOS/RysGitTutorialRepository 
$ git fetch origin
```

```console
Tue Jun 16 ~/iOS/RysGitTutorialRepository 
$ git log master..origin/master --stat
```

```console
Tue Jun 16 ~/iOS/RysGitTutorialRepository 
$ git log origin/master..master --stat
```

Of course, the second log command won't output anything, since we haven't added any new commits while Mary was adding her CSS edits. **It is usually a good idea to check this before trying to merge in a remote branch**. 

Otherwise, you might en up with some extra merge commits when you thought you were fast-forwarding your branch.

```console
Tue Jun 16 ~/iOS/RysGitTutorialRepository 
$ git merge origin/master
Already up to date.
```

Our repository is now synchronized with the central repository. Note that Mary may have moved on and added some new content that we don't know about, but it does not matter. **The only changes we need to know about are those in central-repo.git. While this does not make a huge difference when we are working with just one another developer, **imagine having to keep track of a dozen different developer's repositories in real-time. This kind of chaos is precisely the problem a centralized collaboration workflow is designed to solve:

![Screen Shot 2020-06-16 at 11 12 30](https://user-images.githubusercontent.com/24994818/84799714-4a1aad80-afc2-11ea-88c5-1bd0d56c7fd8.png)

The presence of a central communication hub condenses all this development into a single repository and ensures that no one overwrites another's content, as we discovered while trying to push Mary's CSS updates.

# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

In this module, we introduced another remote repository to serve as the **central storage** facility for our project. We also discovered **bare repositories**, which are just like ordinary repositories -**minus the working directory**. Bare repositories provide **"safe"** location to push branches to, as long as you remember not to rebase the commits that it already contains.

We hosted the central repository on our local filesystem, right next to both ours and Mary's projects. However, **most real-world central repositories reside on a remote server with internet access**. This lets any developer fetch from or push to the repository over the internet, making Git a very powerful multi-user development platform. Having the central repository on a remote server is also an affordable, convenient way to back up a project.

Next up, we will configure a network-based repository using a service called GitHub. In addition to introducing network access for Git repositories, this will open the door for another collaboration standard: the integrator workflow.

#   * [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#9-centralized-workflows)

```console
$ git init --bare repositoryName
```
Create a Git repository, but omit the working directory

```console
$ git remote rm remoteName
```
Remove the specified remote from your book-marked connections.


# 10. [Distributed Workflows](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Now that we know how to share information via a centralized workflow, we can appreciate some of the drawbacks of this collaboration model. While it may be convenient, allowing everyone to push to an **"official"** repository raises some legitimate security concerns. It means that for everyone to contribute content, they need access to the **entire project**.

This is fine if you re only interacting with a small team, but imagine a scenario where you are working on an open-source software project and a stranger found a bug, fixed it, and wants to incorporate the update into the main project. You probably don't want to give them push-access to your central repository, since they could start pushing all sorts of random snapshots, and you would effectively lose control of the project.

But, what you can do is tell the contributor to push the changes to **their own** public repository. Then you can pull their bug fix into your private repository to ensure it does not contain any undeclared code. If you approve their contributions, all you have to do is merge them into a local branch and push it to the main repository, just like we did in the previous model. You have become an **integrator**, in addition to an ordinary developer.

![Screen Shot 2020-06-17 at 10 46 40](https://user-images.githubusercontent.com/24994818/84919664-d9d65f80-b087-11ea-9d7f-24901176d75b.png)

In this module, we will experience all of this first-hand by creating a free public repository on Bit-bucket.org and incorporating a contribution from an anonymous developer named John. Bitbucket is a DVCS hosting provider that makes it very easy to set up a Git repository and start collaborating with a team of developers.

# 	* [Create a Bitbucket Account](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

You can choose any username for your account, but the email address should match the one you assigned to your git installation with **git config** in [The basics](). If you need to change your email, you can run another **git config --global user.mail yoy@example.com** command.

```console
Thu Jun 18 ~/iOS/RysGitTutorialRepository/.git 
$ git config --global user.email c.santiago.cruz@icloud.com
```

# 	* [Create a Public Repository (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

To create our first nerworked Git repository, log into your Bitbucket account, and navigate to **Repositories - Create repository**. 

![Screen Shot 2020-06-18 at 10 21 51](https://user-images.githubusercontent.com/24994818/85039654-90504800-b14d-11ea-8cbd-cdfc61d51c02.png)

Use my git repository as the **RepositoryName**, and anything you like for the **description** field. Since this is just an example project, go ahead and uncheck the **This is a private repository** field. Select HTML/CSS for the **Language field**, then go ahead and click **Create repository**.

Essentially, we just ran **git init --bare** on a Bitbucket server. We can now push to and fetch from this repository as we did with **central-repo.git** in the previous module.

After initialization, Bitbucket offers some helpful instructions, but don't follow them just yet - we will through importing an existing repository in the next section,

![Screen Shot 2020-06-18 at 10 29 52](https://user-images.githubusercontent.com/24994818/85040678-aa3e5a80-b14e-11ea-8c4e-e5d5f691a99a.png)

# 	* [Push to a Public Repository (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Before populating this new repository with our existing my git repository project, we firs need to point our **origin remote** to the Bitbucket repository. Be sure to change the userName portion to your actual Bitbucket userName.

```console
Thu Jun 18 ~/iOS/RysGitTutorial_Carlos 
$ cd ../RysGitTutorialRepository/
```

```console
Thu Jun 18 ~/iOS/RysGitTutorialRepository 
$ git remote rm origin
```

```console
Thu Jun 18 ~/iOS/RysGitTutorialRepository 
$ git remote add origin https://C4rl0sS4nt14g0@bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git
```

The utility of remotes should be more apparent than in previous modules, as typing the full path to this repository every time we needed to interact with it would be rather tedious.

To populate the remote repository with our existing code, we can use the same push mechanism as with a centralized workflow. When prompted for a password, use the one that you signed up with.

```console
Thu Jun 18 ~/iOS/RysGitTutorialRepository/.git 
$ git push origin master
To https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://C4rl0sS4nt14g0@bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```

As you can see, and if you remember the creation a README file, the origin and the local is not the same, to overwrite what you have in you local repository pass the -f flag to pussh to force the push command.

```console
Thu Jun 18 ~/iOS/RysGitTutorialRepository/.git 
$ git push -f origin master
Enumerating objects: 84, done.
Counting objects: 100% (84/84), done.
Delta compression using up to 4 threads
Compressing objects: 100% (81/81), done.
Writing objects: 100% (84/84), 10.08 KiB | 449.00 KiB/s, done.
Total 84 (delta 37), reused 0 (delta 0)
To https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git
 + bfa132d...450182a master -> master (forced update)
```

# 	* [Browse the Public Repository (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

We should now be able to see our project on the bitBucket site. The **Source** tab displays all of the files in the project, and the **commits** tab contains the entire commit history. Note that the branch structure of the repository is also visualized to the left of each commit.

![Screen Shot 2020-06-18 at 11 18 23](https://user-images.githubusercontent.com/24994818/85046031-74e93b00-b155-11ea-81ed-83a45126a70a.png)

This repository now serves as the **"official"** copy our example website. We will tell everyone else to download from this repository, and we will push all the changes from our local my-git-repository to it. However, It is important to note that this **"official"** status is merely a convention. As the **master branch** is just another branch, our Bitbucket repository is just another repository according to Git.

Having both a public and a private repository for each developer makes it easy to incorporate contributions from third-parties, even if you have never met them before.

# 	* [Clone the Repository (John](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Next we are going to pretend to be John, a third-party contributor to our website. John noticed that we didn't have a pink page and, being the friendly developer that he is, wants to create one for us. We would like to let him contribute, but **we don't want to give him push-access** to our entire repository - this would allow him to re-write or even delete all of our hard word.

Fortunately, John knows how to exploit Bitbucket's collaboration potential. He will start by cloning a copy of our public repository:

```console
Fri Jun 19 ~/iOS/RysGitTutorialRepository 
$ cd ../RysGitTutorialRepository/
```

```console
Fri Jun 19 ~/iOS/RysGitTutorialRepository 
$ cd ../
```

I am going to follow the same pattern name used for all contributors, like RysGitTutorialMarysRepository and RysGitTutorialRepository, giving the name RysGitTutorialJohnsRepository

```console
Fri Jun 19 ~/iOS 
$ git clone https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git RysGitTutorialJohnsRepository
Cloning into 'RysGitTutorialJohnsRepository'...
remote: Counting objects: 84, done.
remote: Compressing objects: 100% (81/81), done.
remote: Total 84 (delta 37), reused 0 (delta 0)
Unpacking objects: 100% (84/84), 10.08 KiB | 43.00 KiB/s, done.
```

```console
Fri Jun 19 ~/iOS 
$ cd RysGitTutorialJohnsRepository/
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ 
```

You should now have another copy of our repository called RysGitTutorialJohnsRepositor in the same folder as RysGitTutorialRepository. This is John's private  repository - a completely isolated environment where he can safely develop the pink page. Let's quickly configure his name and email

```console
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ git config user.name "John"
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ git config user.email john.developer@icloud.com
```
 
# 	* [Add the Pink Page (John)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Of course, John should be developing his contributions in a dedicated feature branch.

```console
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ git checkout -b pink-page
Switched to a new branch 'pink-page'
```

In addition to being a best practice, this makes it easy for the integrator to see what commits to include. When John's done, he will tell us where to find his repository and what branch the new features resides in. Then, we will be able merge his content with minimal effort.

Create the file pink.html and add the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>The Pink Page</title>
  <link rel="stylesheet" href="style.css" />
  <meta charset="utf-8" />
</head>
<body>
  <h1 style="color: #F0F">The Pink Page</h1>
  <p>Pink is <span style="color: #F0F">girly,
  flirty and fun</span>!</p>

  <p><a href="index.html">Return to home page</a></p>
</body>
</html>
```

Add the pink page to the "Navigation" section in index.html

```html
<li style="color: #F0F">
  <a href="pink.html">The Pink Page</a>
</li>
```

Then, stage and commit the snapshot as normal.

```console
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ git add pink.html index.html 
```

```console
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ git status
On branch pink-page
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html
	new file:   pink.html
```

```console
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ git commit -m "Add pink page"
[pink-page 51f9d9e] Add pink page
 2 files changed, 18 insertions(+)
 create mode 100644 pink.html
```

# 	* [Publish the Pink Page (John)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Now, John needs to publish this contributions to a public repository. Remember that we don't want him to push or **our** public repository, which is stored in his **origin remote**, which is stored in his **origin remote**. In fact, **he can't push** to origin for reasons we will discuss in a moment.

Instead, he will create his own Bitbucket repository that we can pull contributions from. In the real world, John would have his own Bitbucket account, but for convenience, we will just store his public repository under our existing account. 

Once again, navigate to your Bitbucket home page and click Repositories then Create Repository to create Johns public repository. For the **Name** field, use RysGitTutorialJohnsRepositor 

![Screen Shot 2020-06-19 at 16 34 55](https://user-images.githubusercontent.com/24994818/85181183-e656e580-b24a-11ea-9468-0887dd082ffc.png)

Back in John's private repository, we will need to add this as a remote. Remember to copy the link that Bitbucket provides you, and name it john-public

```console
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ git remote add john-public https://C4rl0sS4nt14g0@bitbucket.org/C4rl0sS4nt14g0/rysgittutorialjohnsrepositor.git
```

This is where John will publish the pink page for us to access. Since he is pushing with HTTPS, he will need to enter the password for his bitbucket account (which is actually the password for your account).

```console
Fri Jun 19 ~/iOS/RysGitTutorialJohnsRepository 
$ git push john-public pink-page
Enumerating objects: 88, done.
Counting objects: 100% (88/88), done.
Delta compression using up to 4 threads
Compressing objects: 100% (85/85), done.
Writing objects: 100% (88/88), 10.48 KiB | 536.00 KiB/s, done.
Total 88 (delta 40), reused 0 (delta 0)
remote: 
remote: Create pull request for pink-page:
remote:   https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialjohnsrepositor/pull-requests/new?source=pink-page&t=1
remote: 
To https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialjohnsrepositor.git
 * [new branch]      pink-page -> pink-page
```

![Screen Shot 2020-06-19 at 16 47 32](https://user-images.githubusercontent.com/24994818/85181842-96791e00-b24c-11ea-905f-d540bec06580.png)

All John needs to do now is tell us the name of the feature branch and send us a link to his repository, which will be:

```html
https://C4rl0sS4nt14g0@bitbucket.org/C4rl0sS4nt14g0/rysgittutorialjohnsrepositor.git
```

Note that John used a different path for pushing to his public repository than the one he gave us for fetching from it. The most important distinction is the transport protocol: the former used https:// while the latter used http://. Accessing a repository over HTTPS (or SSH) lets you fetch or push, but as we saw, requires a password. This prevents unknown developers from overwriting commits.

On the other hand, fetching over HTTP requires no username or password, but pushing is not possible. This lets anyone fetch from a repository without compromising its security, In the integrator workflow, other developers access your repository via HTTP, while you publish changes via HTTPS. This is also the reason why John can't push to his origin remote.

Of course, if you are working on a private project, anonymous HTTP access would be disable for that repository.

# 	* [View John's Contributions (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Ok, we are done being John and we are ready to integrate his code into the official project. Let's start by switching back into our repository and adding John's public repository as a remote.

```console
Sat Jun 20 ~/iOS/RysGitTutorialJohnsRepository 
$ cd ../RysGitTutorialRepository/
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialRepository 
$ git remote add john https://C4rl0sS4nt14g0@bitbucket.org/C4rl0sS4nt14g0/rysgittutorialjohnsrepositor.git
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialRepository 
$ git fetch john
remote: Counting objects: 7, done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 7 (delta 2), reused 0 (delta 0)
Unpacking objects: 100% (7/7), 1.86 KiB | 118.00 KiB/s, done.
From https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialjohnsrepositor
 * [new branch]      master     -> john/master
 * [new branch]      pink-page  -> john/pink-page
```

```console
$ git branch -r
  john/master
  john/pink-page
  origin/master
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialRepository 
$ git log master..john/pink-page --stat
commit 51f9d9e84c2e10e5ac859f2c8a6c4ac66ed39b17 (john/pink-page)
Author: John <john.developer@icloud.com>
Date:   Fri Jun 19 16:17:28 2020 -0500

    Add pink page

 index.html |  3 +++
 pink.html  | 15 +++++++++++++++
 2 files changed, 18 insertions(+)
```

You can visualize this history information as the following:

![Screen Shot 2020-06-20 at 16 49 02](https://user-images.githubusercontent.com/24994818/85212191-f8518a80-b315-11ea-9bdd-9600c565fbe7.png)

Let's take a look at his actual changes:

```console
git checkout john/pink-page
Note: switching to 'john/pink-page'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 51f9d9e Add pink page
```

Open up the pink.html file to see if it is ok, remember that John is not a trusted collaborator, and we would normally have no idea what this file might contain. With that in mind, It is incredibly important to verify its contents. **Never blindly merge content from a third-party contributor.

# 	* [Integrate John's Contributions (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Assuming we approve John's updates, we are now ready to merge it into the project.

```console
Sat Jun 20 ~/iOS/RysGitTutorialRepository 
git checkout master
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialRepository 
$ git merge john/pink-page
Updating 450182a..51f9d9e
Fast-forward
 index.html |  3 +++
 pink.html  | 15 +++++++++++++++
 2 files changed, 18 insertions(+)
 create mode 100644 pink.html
```

Notice that is the exact same way we incorporated Mary's changes in the centralized workflow, except now we are pulling from and pushing to different locations.

![Screen Shot 2020-06-20 at 18 43 42](https://user-images.githubusercontent.com/24994818/85213586-fdb6d100-b325-11ea-9778-1b2f0d9bdaf1.png)

Furthermore, John's workflow is just like ours: develop in a local, private repository, then push changes to the public one. The integrator workflow is merely a standardized way of organizing the collaboration effort - nothing has changed about how we develop locally, and we are using the same Git commands as we have been for the las few modules.

# 	* [Publish John's Contributions (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

We have integrated John's contribution into our local git repository, but no one else knows what we have done, It is time to publish our master branch again.

```console
Sat Jun 20 ~/iOS/RysGitTutorialRepository 
$ git push origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 611 bytes | 305.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
To https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git
   450182a..51f9d9e  master -> master
```

![Screen Shot 2020-06-20 at 18 54 56](https://user-images.githubusercontent.com/24994818/85213704-8d10b400-b327-11ea-999d-647f7c9f1a50.png)

Since we designated our public Bitbucket repository as the "official" source for our project, everyone (Mary and John) will now be able to synchronize with it.


# 	* [Update Mary's Repository (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Mary should now be pulling changes from our Bitbucket repository instead of the central one from the previous module. This should be fairly easy to her to configure.

```console
Sat Jun 20 ~/iOS/RysGitTutorialRepository 
$ cd ../RysGitTutorialMarysRepository/
Sat Jun 20 ~/iOS/RysGitTutorialMarysRepository 
$
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialMarysRepository 
$ git remote rm origin
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialMarysRepository 
$ git remote add origin https://C4rl0sS4nt14g0@bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git
```

Again, remember to change userName to your bitbucket account's name. For the sake brevity. we will do a blind merge to add John's updates to Mary's repository (normally, Mary should check what she is integrating before doing so).

```console
Sat Jun 20 ~/iOS/RysGitTutorialMarysRepository 
$ git checkout master
Already on 'master'
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialMarysRepository 
$ git fetch origin 
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 2), reused 0 (delta 0)
Unpacking objects: 100% (4/4), 591 bytes | 7.00 KiB/s, done.
From https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository
 * [new branch]      master     -> origin/master
```

```console
$ git rebase origin/master
First, rewinding head to replay your work on top of it...
Applying: Add CSS styles for headings and links
```

For Mary, it does not really matter that the updates came from John. All she has to know is that the "Official" master branch moved forward, prompting her to synchronize her private repository.

# 	* [Update John's Repository (John)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

John still needs to incorporate the pink page into **his master** branch. He should **not** merge directly from his pink-page topic branch because we could have edited his contribution before publishing it or included other contributions along with it. Instead, **he will pull from the "official" master**:

```console
Sat Jun 20 ~/iOS/RysGitTutorialMarysRepository 
$ cd ../RysGitTutorialJohnsRepository/
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialJohnsRepository 
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialJohnsRepository 
$ git fetch origin
From https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository
   450182a..51f9d9e  master     -> origin/master
```

```console
$ git branch -r
  john-public/pink-page
  origin/HEAD -> origin/master
  origin/master
```

```console
Sat Jun 20 ~/iOS/RysGitTutorialJohnsRepository 
$ git rebase origin/master
First, rewinding head to replay your work on top of it...
Fast-forwarded master to origin/master.
```

If John had updated **master** directly from his local pink-page, it could have wound up out-of-sync from the main project. For this reason, the integrator workflow requires that everyone **pull** from a single, official repository, while they all **push** to their own public repositories.

![Screen Shot 2020-06-20 at 19 23 27](https://user-images.githubusercontent.com/24994818/85214018-97cd4800-b32b-11ea-91b8-35491a0ab6e6.png)

# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Using the integrator workflow, our private development process largely remains the same **(Develop a feature branch, merge it into master, and publish it)**. But, we have addedan additional task: incorporating changes from third-party contributors. Luckily, this does not required any new skills - just access to a few more remotes repositories.

While this setup forces us to keep track of more remotes, it also makes it much, much easier to work with a large number of developers. You will never have to worry about security using an integrator workflow because you will still be the only one with access to the **"official"i** repository.

There is also an interesting side-effect to this kind of security. By giving each developer their own public repository, the navigator workflow creates a more stable development environment for open source software projects. Should the lead developer **stop maintaining the "official" repository**, **any of the other participants could take over by simply designating their public repository as the new "official" project**. This is part of what makes Git **distributed** version control system: **There is no single central repository that Git forces everyone to rely upon.

# 11. [Patch Workflows](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Thus, far, all of the collaboration workflows we have seen rely heavily on branches. For example, in the last module, a contributor had to publish an entire **branch** for us to merge into our project. However, it is also a possible to communicate directly on the **commit** level using a **patch**.

**A patch file represents a single set of changes (i.e. a commit) that can be applied to any branch, in any order**. In this sense, the patch workflow is akin ii(parecido) to interactive rebasing, except **you can easily share patches with other developers**. This kind of communication lessens (aminora) the importance of a project's branch structure and gives complete control to the project maintainer (at least with regards to incorporating contributions).

Integrating on the commit level will also give us a deeper understanding of how a Git repository records project history.

```console
Wed Jun 24 ~/iOS/RysGitTutorialRepository 
$ git remote add origin https://C4rl0sS4nt14g0@bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git
fatal: remote origin already exists.
```

```console
Wed Jun 24 ~/iOS/RysGitTutorialMarysRepository 
$ git remote add origin https://C4rl0sS4nt14g0@bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git
fatal: remote origin already exists.
```

Both exist, reverse if needed.

# 	* [Change the Pink Page (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

We will begin by pretending to be Mary again. Mary didn't like the pink page that John contributed and wants to change it.

```console
Wed Jun 24 ~/iOS/RysGitTutorialRepository 
$ cd ../RysGitTutorialMarysRepository/
```

```console
Wed Jun 24 ~/iOS/RysGitTutorialMarysRepository 
$ git checkout -b pink-page
Switched to a new branch 'pink-page'
```

Developing in a new branch not only gives Mary an isolated environment, it also makes it easier to create a series of patches once she is done editing the pink page. Find these lines in **pink.html**

```html
<p>Pink is <span style="color: #F0F">girly,
flirty and fun</span>!</p>
```

and change them to the following:

```console
<p>Only <span style="color: #F0F">real men</span> wear pink!</p>
```
Stage and commit the update as normal.

```console
Wed Jun 24 ~/iOS/RysGitTutorialMarysRepository 
$ git commit -a -m "Change pink to a manly color"
[pink-page 58b51cb] Change pink to a manly color
 1 file changed, 1 insertion(+), 3 deletions(-)
```

Note that Mary's local development process does not change at all. **Patches** - like the centralized and integrator workflow - are merely a way to share changes amongst developers. It has little effect on the core Git concepts introduced in the first portion of this tutorial.

# 	* [Create a Patch](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Mary can create a patch from the new commit using the **git format-patch** command.

```console
Wed Jun 24 ~/iOS/RysGitTutorialMarysRepository 
$ git format-patch master
0001-Change-pink-to-a-manly-color.patch
```

This creates a file called 0001-Change-pink-to-a-manly-color.patch that contains enough information to recreate the commit from the last step. The master parameter tells Git to generate patches for every commit in the current branch that is missing from **master**.

Open up the patch file in a text editor. As shown by the address in the top of the file, it is actually a complete email. This makes it incredible easy to send patches to other developer. Further down, you should see the following.

```console
Wed Jun 24 ~/iOS/RysGitTutorialMarysRepository 
$ cat 0001-Change-pink-to-a-manly-color.patch 
From 58b51cbb457cf6fe142cd8bc5f11c2caec9b0212 Mon Sep 17 00:00:00 2001
From: Mary <c.santiago.cruz@gmail.com>
Date: Wed, 24 Jun 2020 13:16:13 -0500
Subject: [PATCH] Change pink to a manly color

---
 pink.html | 4 +---
 1 file changed, 1 insertion(+), 3 deletions(-)

diff --git a/pink.html b/pink.html
index 47ea234..c349233 100644
--- a/pink.html
+++ b/pink.html
@@ -7,9 +7,7 @@
 </head>
 <body>
   <h1 style="color: #F0F">The Pink Page</h1>
-  <p>Pink is <span style="color: #F0F">girly,
-  flirty and fun</span>!</p>
-
+  <p>Only <span style="color: #F0F">real men</span> wear pink!</p>
   <p><a href="index.html">Return to home page</a></p>
 </body>
 </html>
-- 
2.25.0
```

now with vim syntax

```vim
From 58b51cbb457cf6fe142cd8bc5f11c2caec9b0212 Mon Sep 17 00:00:00 2001
From: Mary <c.santiago.cruz@gmail.com>
Date: Wed, 24 Jun 2020 13:16:13 -0500
Subject: [PATCH] Change pink to a manly color

---
 pink.html | 4 +---
 1 file changed, 1 insertion(+), 3 deletions(-)

diff --git a/pink.html b/pink.html
index 47ea234..c349233 100644
--- a/pink.html
+++ b/pink.html
@@ -7,9 +7,7 @@
 </head>
 <body>
   <h1 style="color: #F0F">The Pink Page</h1>
-  <p>Pink is <span style="color: #F0F">girly,
-  flirty and fun</span>!</p>
-
+  <p>Only <span style="color: #F0F">real men</span> wear pink!</p>
   <p><a href="index.html">Return to home page</a></p>
 </body>
 </html>
-- 
2.25.0
```

now the following:

```vim
index 47ea234..c349233 100644
--- a/pink.html
+++ b/pink.html
@@ -7,9 +7,7 @@
 </head>
 <body>
   <h1 style="color: #F0F">The Pink Page</h1>
-  <p>Pink is <span style="color: #F0F">girly,
-  flirty and fun</span>!</p>
-
+  <p>Only <span style="color: #F0F">real men</span> wear pink!</p>
   <p><a href="index.html">Return to home page</a></p>
 </body>
 </html>
```

This unique formatting is called a **diff**, because it shows the difference between two versions of a file. In our case, it tells us what happened to the **pink.html** file between the 47ea234 and c349233 commits (your patch will contain different commt ID's). The @@ -7,9 +7,7 @@ portion describes the lines affected in the respective versions of the file, and the rest of the text shows us the content that has been changed. The lines beginning with - have been deleted in the new version, and the line starting with + has beed added.

While you don't have to know the ins-add-outs of diffs to make use of patches, you do need to understand that a single patch file represents a complete commit. And, since it is a normal file (and also an email), it is much easier to pass around than a Git branch.

Delete the patch file for now (we will re-create it later).

# 	* [Add a Pink Block (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Before learning how to turn patches back into commits, Mary will add one more snapshot.

In **pink.html**, add the following on the line after meta tag.

```html
<style>
  div {
    width: 300px;
    height: 50px;
  }
</style>
```

And, add the next line of HTML after only real men wear pink!:

```html
<div style="background-color: #F0F"></div>
```

stage and commit the snapshot.

```console
Sun Jun 28 ~/iOS/RysGitTutorialMarysRepository 
$ git commit -a -m "Add a pink block of color"
[pink-page da81d4a] Add a pink block of color
 1 file changed, 7 insertions(+)
```

Mary's repository now contains two commits after the tip of master:

![Screen Shot 2020-06-28 at 8 37 35](https://user-images.githubusercontent.com/24994818/85949161-c1cdce00-b91a-11ea-850c-043ddb0faad5.png)

# 	* [Create Patch of Entire Branch (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Mary can use the same command as before to generate patches for all commits in her pink-branch.

```console
Mon Jun 29 ~/iOS/RysGitTutorialMarysRepository 
$ git format-patch master
0001-Change-pink-to-a-manly-color.patch
0002-Add-a-pink-block-of-color.patch
```

The first patch is the exact same as we previously examined, but we also have a new one called 0002-Add-a-pink-block-of-color.patch. Note that the first line of the commit message will always be used to make a descriptive filename for the patch. You should find the following **diff** in the second patch.

```console
index c349233..431492b 100644
--- a/pink.html
+++ b/pink.html
@@ -4,10 +4,17 @@
   <title>The Pink Page</title>
   <link rel="stylesheet" href="style.css" />
   <meta charset="utf-8" />
+  <style>
+  div {
+    width: 300px;
+    height: 50px;
+  }
+  </style>
 </head>
 <body>
   <h1 style="color: #F0F">The Pink Page</h1>
   <p>Only <span style="color: #F0F">real men</span> wear pink!</p>
+  <div style="background-color: #F0F"></div>
   <p><a href="index.html">Return to home page</a></p>
 </body>
 </html>
-- 
2.25.0
```

This is the same formatting as the first patch, except its lack of - lines indicate that we only added HTML during the second commit. As you can see, this patch is really just a **machine-readable** summary of our actions from the previous section.


# 	* [Mail the Patches (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Now that Mary has prepared a series of patches, she can send them to the program maintainer (us). In the typical patch workflow, she would send them via email using one of the following methods:

* Copying and pasting the contents of the patch files into an email client. If she uses this method, Mary would have to make sure that her email application does not change the whitespace in the patch upon email.
* Sending the patch file as an attachment to a normal email.
* Using the convenient **git send-email** command and specifying a file or a directory of files to send. For example, **git send-email**, will send all the patches in the current directory. Git also requires some special configurations for this command. Please consult the official Git documentation for details.

The point is, the **.patch** files need to find their way into the Git repository of whoever wants to add it to their project. For our example, all we need to do is copy the patches into my-git-repo directory that represents our local version of the project.

# 	* [Apply the Patches (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Copy the two patches files from RysGitTutorialMaryRepository into RysGitTutorialRepository. Using the new **git am** command, we can use these patches to add Mary's commits to our repository.

```console
Wed Jul 01 ~/iOS/RysGitTutorialMarysRepository 
$ cd ../RysGitTutorialRepository/
```

```console
Wed Jul 01 ~/iOS/RysGitTutorialRepository 
$ git checkout -b patch-integration
Switched to a new branch 'patch-integration'
```

```console
Wed Jul 01 ~/iOS/RysGitTutorialRepository 
$ git am < 0001-Change-pink-to-a-manly-color.patch 
Applying: Change pink to a manly color
```

```console
Wed Jul 01 ~/iOS/RysGitTutorialRepository 
$ git log master..HEAD --stat
commit 958cd59173a387d6b9c3d3a78aa6370dce0318ca (HEAD -> patch-integration)
Author: Mary <c.santiago.cruz@gmail.com>
Date:   Wed Jun 24 13:16:13 2020 -0500

    Change pink to a manly color

 pink.html | 4 +---
 1 file changed, 1 insertion(+), 3 deletions(-)
```

First, notice that we are doing our integrating in a new topic branch. Again, this ensures that we won't destroy our existing functionality and gives us a chance to approve changes. Second, the **git am** command takes a patch file and creates a new commit from it. The log output shows us that our integration branch contains Mary's update, along with her author information.

Let's repeat the process for the second commit.

```console
Wed Jul 01 ~/iOS/RysGitTutorialRepository 
$ git am < 0002-Add-a-pink-block-of-color.patch 
Applying: Add a pink block of color
```

```console
Wed Jul 01 ~/iOS/RysGitTutorialRepository 
$ git log master..HEAD --stat
commit 56599780e162975562da46742664c1132a24b78e (HEAD -> patch-integration)
Author: Mary <c.santiago.cruz@gmail.com>
Date:   Sun Jun 28 08:36:02 2020 -0500

    Add a pink block of color

 pink.html | 7 +++++++
 1 file changed, 7 insertions(+)

commit 958cd59173a387d6b9c3d3a78aa6370dce0318ca
Author: Mary <c.santiago.cruz@gmail.com>
Date:   Wed Jun 24 13:16:13 2020 -0500

    Change pink to a manly color

 pink.html | 4 +---
 1 file changed, 1 insertion(+), 3 deletions(-)
```

The **git am** command is configured to read from something called **"Standard input"**, and the **"< character"** we can turn file's contents into standard input. As it is really more of an operating system topic, you can just think of this syntax as a quick of the **git am** command.

After applying this patch, our integration branch now looks exactly like Mary's pink-page branch. We applied Mary's patches in the same order she did, but that didn't necessarlily have to be the case. The whole idea begind patches is that **let you isolate a commit and move it around as you please**.

# 	* [Integrate The Patches (you)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Once again, we are in the familiar situation of integrating a topic branch into the stable master branch.

```console
Thu Jul 02 ~/iOS/RysGitTutorialRepository 
$ git checkout master
Switched to branch 'master'
```

```console
Thu Jul 02 ~/iOS/RysGitTutorialRepository 
$ git merge patch-integration
Updating 51f9d9e..5659978
Fast-forward
 pink.html | 11 ++++++++---
 1 file changed, 8 insertions(+), 3 deletions(-)
```

```console
Thu Jul 02 ~/iOS/RysGitTutorialRepository 
$ git branch -d patch-integration
Deleted branch patch-integration (was 5659978).
```

```console
Thu Jul 02 ~/iOS/RysGitTutorialRepository 
$ git clean -f
Removing 0001-Change-pink-to-a-manly-color.patch
Removing 0002-Add-a-pink-block-of-color.patch
```

```console
Thu Jul 02 ~/iOS/RysGitTutorialRepository 
$ git push origin master
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 834 bytes | 278.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0)
To https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository.git
   51f9d9e..5659978  master -> master
```

Mary's updates are now completely integrated into our local repository, so we ca get rid of the patch files with **git clean**. This was also appropiate time to push changes to the public repository so other developers can access the most up-to-date version of the project.

# 	* [Update Mary's Repository (Mary)](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Mary might be tempted to merge her pink-page branch directly into her master branch, but this would be a mistake. Her master branch **must** track the **"official"** repository's master, as discussed in the previous module.

```console
Fri Jul 03 ~/iOS 
$ cd RysGitTutorialMarysRepository/
```

```console
Fri Jul 03 ~/iOS/RysGitTutorialMarysRepository 
$ git checkout master
Switched to branch 'master'
```

```console
Fri Jul 03 ~/iOS/RysGitTutorialMarysRepository 
$ git fetch origin
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 3), reused 0 (delta 0)
Unpacking objects: 100% (6/6), 814 bytes | 67.00 KiB/s, done.
From https://bitbucket.org/C4rl0sS4nt14g0/rysgittutorialrepository
   51f9d9e..5659978  master     -> origin/master
```

```console
Fri Jul 03 ~/iOS/RysGitTutorialMarysRepository 
$ git rebase origin/master
First, rewinding head to replay your work on top of it...
Applying: Add CSS styles for headings and links
```

```console
Fri Jul 03 ~/iOS/RysGitTutorialMarysRepository 
$ git branch -D pink-page
Deleted branch pink-page (was da81d4a).
```

```console
Fri Jul 03 ~/iOS/RysGitTutorialMarysRepository 
$ git clean -f
Removing 0001-Change-pink-to-a-manly-color.patch
Removing 0002-Add-a-pink-block-of-color.patch
```

Patches are a convenient way to share commits amongst developers, but the patch workflow still requires an **"official"** repository that contains **everybody's changes**. What would happen if Mary was not the only one sending patches to us ?. We may very well have applied several different patches or applied Mary's contributions in a different order. Using Mary's **pink-page** to update her master branch would completely ignore all these updates.

Taking this into consideration, our final patch workflow resembles the following.

![Screen Shot 2020-07-03 at 18 38 37](https://user-images.githubusercontent.com/24994818/86501205-6d807f00-bd5c-11ea-83a9-73fdb2fd21f1.png)

# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Whereas **remote repositories** are a way to share entire **branches**, **patches** are a way to send **individual commits** to another developer. Keep in mind that patches are usually only sent to a project maintainer, who then integrates them into the **"official"** project for all to see. It would be impossible for everyone to communicate using only patches, as no one would be applying them in the same order. Eventually, everyone's project history would look entirely different.

In many ways, **patches are a simpler way** to accept contributions than the integrator workflow from the previous module. Only the project maintainer needs a public repository, and he will never have to peek at anyone else's repository. Form the maintainer's perspective, patches also provide the same security as the integrator workflow: **he still won't have to give anyone access to his "official" repository**. But now he won't have to keep track of everybody's remote repositories, either.

As a programmer,yoy are most likely to use patches **when you want to fix a bug in someone else's project**. After fixing it, you can send them a patch of the resulting commit. For this kind of one-time-fix, it's much more convenient for you to generate a patch than to set up a public Git repository.

This module concludes our discussion of the standard Git workflows. Hopefully you have a good idea of how Git can better manage your personal and professional software projects using a centralized, integrator, or patch workfloow. In then next module, we will switch gears and introduce a variaty of practical Git commands.

# 	* [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

```console
$ git format-patch branchName
```
Create a patch for each commit contained in the current branch but not in branchName. You can also specify a commit ID instead of branchName

```console
git am < patchFile
```
Apply a patch to the current branch

# 12. [Tips and Tricks](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

This module presents a broad survey of useful Git utilities. We will take a step back from the theoretical aspects of Git and focus on common tasks like preparing a project for release and backing up a repository. While working through this module, your goal shouldn't be to understand why they were created and when they might come in handy.

# 	* [Archive The repository](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

First, let's export our repository into a ZIP archive. Run the following command in your local copy of my git repository, in this case RysGitTutorialRepository.

```console
Sun Jul 05 ~/iOS/RysGitTutorialRepository 
$ git archive master --format=zip --output=../website-Jul-05-2020.zip
```

or, for Unix users that would prefer a tarball:

```console
Sun Jul 05 ~/iOS/RysGitTutorialRepository 
$ git archive master --format=tar --output=../website-Jul-05-2020.tar
```

This takes the current **master** branch and places all of its files into a ZIP archive (or tarball), ommitting the .git directory. **Removing the .git directory removes all version control information, and you are left with a single snapshot of your project**.

You can send the resulting archive to a client for review, even if they don't have Git installed on their machine. This is also an easy way to create Git-independent backups of important revisions, which is always a good idea.

# 	* [Bundle the Repository](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Similar to the **git archive** command, **git bundle** turns a repository into a single file. However, in this case, the file retains the versioning information of the entire project. Try running the following command.

```console
Mon Jul 06 ~/iOS/RysGitTutorialRepository 
$ git bundle create ../repo.bundle master
Enumerating objects: 94, done.
Counting objects: 100% (94/94), done.
Compressing objects: 100% (91/91), done.
Total 94 (delta 44), reused 0 (delta 0)
```

It's like we just pushed our master branch to a remote, except it's contained in a file instead of a remote repository. We can even clone it using the same **git clone** command.

```console
Mon Jul 06 ~/iOS/RysGitTutorialRepository 
$ cd ..
Mon Jul 06 ~/iOS 
$ git clone repo.bundle repo-bundle-copy -b master
Cloning into 'repo-bundle-copy'...
Receiving objects: 100% (94/94), 11.16 KiB | 2.23 MiB/s, done.
Resolving deltas: 100% (44/44), done.
```

```console
$ ls repo*
repo.bundle

repo-bundle-copy:
about        index.html   news-3.html  rainbow.html yellow.html
blue.html    news-1.html  orange.html  red.html
green.html   news-2.html  pink.html    style.css
```

```console
Mon Jul 06 ~/iOS/repo-bundle-copy 
$ git log
```

The log output should show you the entire history of our **master branch**, and **repo.bundle+* is also the **origin remote** for the new repository. This is the exact behavior we encountered when cloning a **"normal"** Git repository.

Bundles are a great way to backup entire Git repositoies (not just an isolated snapshot like **git archive**). They also let you share changes without a network connection. For example, if you didn't want to configure the SSH accounts for a private Git Server, you could bundle up the repository, put it on a jump drive, and walk it over to your co-worker's computer. Of course, this could become a bit tiresome for active projects.

We will not be needing the repo.bundle file and repo-copy folder, so go ahead and delete them now.


# 	* [Ignore a File](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Remember that Git does not automatically track files because we don't want to record generarted files llike C binaris or compiled Phyton modules. But, seeing these files under the **"Untracked files"** list in **git status** can get confusing for large projects, so Git lets us ignore content using a special text file called **.gitignore**. Each file or directory stored in **.gitignore** will be invisible to Git.

Let's see how this works by creating a file called **notes.txt** to store some personal (private) comments about the project. Add some text to it and save it, then run the following.

```console
Wed Jul 08 ~/iOS/RysGitTutorialRepository 
$ vim notes.txt
Wed Jul 08 ~/iOS/RysGitTutorialRepository 
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	notes.txt

nothing added to commit but untracked files present (use "git add" to track)
Wed Jul 08 ~/iOS/RysGitTutorialRepository 
```

As expected, this will show you **notes.txt** in the **"Untracked files"** section. Next, create a fie called **.gitignore** in the repository directory and add the following text to it. Windows users can create a file that starts with a period by executing the **touch .gitignore** command in Git bash (you should also make sure hidden files are visible in your file browser).

```console
Wed Jul 08 ~/iOS/RysGitTutorialRepository 
$ touch .gitignore
```

Run another git status and you will see that the notes file no longer appears under **"Untracked files"**, but **.gitignore** does. This is a common file for Git-based projects, so let's add it to the repository.

```console
Wed Jul 08 ~/iOS/RysGitTutorialRepository 
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.gitignore

nothing added to commit but untracked files present (use "git add" to track)
```

```console
Wed Jul 08 ~/iOS/RysGitTutorialRepository 
$ git add .
Wed Jul 08 ~/iOS/RysGitTutorialRepository 
$ git commit -m "Add .gitignore file"
[master da3867e] Add .gitignore file
 1 file changed, 1 insertion(+)
 create mode 100644 .gitignore
Wed Jul 08 ~/iOS/RysGitTutorialRepository 
$ git status
On branch master
nothing to commit, working tree clean
```

You can also specify entire directories in **.gitignore** or use the * wildcard to ignore files with a particular extension. For example, the following is a typical **.gitignore** file for a simple C project. It tells Git to overlook all **., .out, and .exe** files in the repository

```vim
*.o
*.out
*.exe
```

# 	* [Stash Uncommitted Changes](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Next, we will take a brief look at **stashing**, which conveniently **"Staches"** away uncommitted changes. Open up **style.css** and change the h1 element to:

```html
h1 {
 font-size: 32px;
 “font-family: "Times New Roman", serif;
}
```

Now let's say we had to make an emergency fix to our project. We don't want to commit an unfinished feature, and we also don't want to lose our current CSS addition. The solution is to temporarily remove these changes with the **git stash** command.

```console
Thu Jul 09 ~/iOS/RysGitTutorialRepository 
$ vim style.css 
```
```console
Thu Jul 09 ~/iOS/RysGitTutorialRepository 
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")
```

```console
Thu Jul 09 ~/iOS/RysGitTutorialRepository 
$ git stash
Saved working directory and index state WIP on master: da3867e Add .gitignore file
```

```console
Thu Jul 09 ~/iOS/RysGitTutorialRepository 
$ git status
On branch master
nothing to commit, working tree clean
```

Before the stash, style.css was listed as **"Change by not updated"**. The **git stash** command hid these changes, giving us a clean working directory. We are now able to switch to a new **hotfix** branch to make our important updates - without having to commit a meaningless snapshot just to save our current state.

Let's pretend we have completed our emergency update and we are ready to continue working on our CSS changes. **We can retrieve our stahed content** with the following command.

```console
Thu Jul 09 ~/iOS/RysGitTutorialRepository 
$ git stash apply
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")
```

The **style.css** file now looks the same as it did before the stash, and we can continue development as if we were never interrupted. Whereas patches represent a committed snapshot, a stash represents a set of uncommitted changes. It takes the uncommitted modifications, stores them internally, ten does a **git reset --hard** to give us a clean working directory. This also means that stashes can be applied to **any** branch, not just the one from which it was created.

In addition to temporarily storing uncommitted changes, this makes stashing a simple way to transfer modifications between branches. So, for example, if you ever found yourself developing on the wrong branch, you could stash all your changes, checkout the correct branch, then run a **git stash apply**.

Let's undo these CSS updates before moving on.

```console
Thu Jul 09 ~/iOS/RysGitTutorialRepository 
$ git reset --hard
HEAD is now at da3867e Add .gitignore file
```

# 	* [Hook into Git's internals](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Arguably, Git's most useful configuration options are its **hooks*. A hook is a script that Git executes every time a particular event occurs in a repository. In this section, we will take a **hands-on** look at Git hooks by automatically publishing our website every time someone pushes to the central-repo.git repository.

```console
Fri Jul 10 ~/iOS 
$ cd central-repo.git/
Fri Jul 10 ~/iOS/central-repo.git 
$ ls
description HEAD        config      info        refs        hooks       objects
Fri Jul 10 ~/iOS/central-repo.git 
$ cd hooks/
Fri Jul 10 ~/iOS/central-repo.git/hooks 
$ ls
commit-msg.sample         fsmonitor-watchman.sample pre-merge-commit.sample
pre-rebase.sample         pre-receive.sample        pre-applypatch.sample
pre-commit.sample         prepare-commit-msg.sample pre-push.sample
applypatch-msg.sample     post-update.sample        update.sample
```

In the centra-repo.git directory, open the **hooks** directory and rename the file **post-update.sample** to **post-update**. After removing the **.sample** extension, this script will be executed whenever **any** branch gets pushed to **central-repo.git**. Replace the default contents of **post-update** with the following.


```console
Fri Jul 10 ~/iOS/central-repo.git/hooks 
$ mv post-update.sample post-update
```

```vim
#!/bin/sh

echo "Publishing master branch!" >&2

# remove the old `my-website` directory (if necessary)
rm -rf ../my-website

# create a new `RysGitTutorialMyWebsitem` directory
mkdir ../RysGitTutorialMyWebsite

#Archive the `master` branch
git archive master --format=tar --output=../RysGitTutorialMyWebsite.tar

#Uncompress the archive into the `RysGitTutorialMyWebsite` directory
tar -xf ../RysGitTutorialMyWebsite.tar -C ..RysGitTutorialMyWebsite
```

While shell scripts are outside the scope of this tutorial, the majority of commands in the above code listing should be familiar to you. In short, this new **post-update** script creates an archive of the **master** branch, then exports it into a directory called **RysGitTutorialMyWebsite** repository.

We can see the script in action by pushing a branch to the central-repo.git repository.

```console
Fri Jul 10 ~/iOS/RysGitTutorialRepository 
$ git push ../central-repo.git master
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (13/13), 1.43 KiB | 366.00 KiB/s, done.
Total 13 (delta 7), reused 0 (delta 0)
remote: Publishing master branch!
To ../central-repo.git
   450182a..da3867e  master -> master
```

```console
.
.
central-repo.git
RysGitTutorialMyWebsite.tar
RysGitTutorialMyWebsite
Fri Jul 10 ~/iOS 
```

after the central repository receives the new master branch, our **post-update** script is executed. You should see the **Publishing master branch!** message echoed from the script, along with RysGitTutorialMyWebsite folder in the same directory as **RysGitTutorialRepository**. You can open **index.html** in a web browser to verify that it contains all the files from our **master branch**, and you can also see the **intermediate.tar** archive produces by the hook.

This is a simple unoptimized example, but **Git hooks** are infinitely versatile. Each of the **.sample** scripts in the hooks directory represents different event that you can listen for, an each of them can do anything from automatically creating and publishing releases to enforcing a commit policy,  making sure a project compiles, and of course, publishing websites (that means no more cluncy FTP uploads). Hooks are even configured on a per-repository basis, which means you can run different scripts in your local repository than your central repository.

# 	* [View Diffs Between commits](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

Up until now, we have been using **git log --stat** to view the changes introduced by new commits. However, this does not show us which lines have been change in any given file. For this level of detail, we need the **git diff** command. Let's take a look at the updates from the **"Add a pink block of color"** commit

This will output the diff between the "Add a pink block of color" commit (HEAD~1) and the one before it (HEAD~2):

```console
Mon Jul 13 ~/iOS/RysGitTutorialRepository 
$ git diff HEAD~2..HEAD~1
diff --git a/pink.html b/pink.html
index c349233..431492b 100644
--- a/pink.html
+++ b/pink.html
@@ -4,10 +4,17 @@
   <title>The Pink Page</title>
   <link rel="stylesheet" href="style.css" />
   <meta charset="utf-8" />
+  <style>
+  div {
+    width: 300px;
+    height: 50px;
+  }
+  </style>
 </head>
 <body>
   <h1 style="color: #F0F">The Pink Page</h1>
   <p>Only <span style="color: #F0F">real men</span> wear pink!</p>
+  <div style="background-color: #F0F"></div>
   <p><a href="index.html">Return to home page</a></p>
 </body>
 </html>
```

This diff looks nearly identical to the patches we created in the previous module, and it shows exactly what was added to get from HEAD~2 to HEAD~1. The **git diff** command is incredibly useful for pinpointing contributions from other developers. For example, we could have used the following to view the differences between John's pink-page branch and our master before merging it into the project in Distributed Workflows.

```console
diff --git a/.gitignore b/.gitignore
deleted file mode 100644
index 99ed0d4..0000000
--- a/.gitignore
+++ /dev/null
@@ -1 +0,0 @@
-notes.txt
diff --git a/pink.html b/pink.html
index 431492b..47ea234 100644
--- a/pink.html
+++ b/pink.html
@@ -4,17 +4,12 @@
   <title>The Pink Page</title>
   <link rel="stylesheet" href="style.css" />
   <meta charset="utf-8" />
-  <style>
-  div {
-    width: 300px;
-    height: 50px;
-  }
-  </style>
 </head>
 <body>
   <h1 style="color: #F0F">The Pink Page</h1>
-  <p>Only <span style="color: #F0F">real men</span> wear pink!</p>
-  <div style="background-color: #F0F"></div>
+  <p>Pink is <span style="color: #F0F">girly,
+  flirty and fun</span>!</p>
+
   <p><a href="index.html">Return to home page</a></p>
 </body>
 </html>
```

This flexible command can also generate a detailed view of our uncommitted changes. open up **blue.html**, make any kind of change, and save the file. Then run **git diff** without any arguments:

```console
Mon Jul 13 ~/iOS/RysGitTutorialRepository 
$ vim blue.html 
Mon Jul 13 ~/iOS/RysGitTutorialRepository 
$ git diff
diff --git a/blue.html b/blue.html
index 370563f..14728e6 100644
--- a/blue.html
+++ b/blue.html
@@ -10,3 +10,5 @@
   <p>Blue is the color of the sky.</p>
 </body>
 </html>
+<!-- You will not be able to see this text. -->
+
```

And, just in case we forgot what was added to the staging area, we can use the **--cahed** flag to generate a diff between the staged snapshot and the most recent commit:

```console
Mon Jul 13 ~/iOS/RysGitTutorialRepository 
$ git add blue.html 
Mon Jul 13 ~/iOS/RysGitTutorialRepository 
$ git diff --cached
diff --git a/blue.html b/blue.html
index 370563f..14728e6 100644
--- a/blue.html
+++ b/blue.html
@@ -10,3 +10,5 @@
   <p>Blue is the color of the sky.</p>
 </body>
 </html>
+<!-- You will not be able to see this text. -->
+
```

A plain old **git diff** will not output anything after the **blue.html** is added to the staging area, but the changes are now visible through the **--cached** flag. These are the three main configurations of the **git diff** command.

# 	* [Reset and checkout files](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)

We have used **git reset** and **git checkout** many times throughout this tutorial; however, we have only seen them work with **branches/commits**. You can also reset and checkout individual files, which slightly alters the behavior of both commands.

The **git reset** we are accustomed to moves the current branch to a new commit and optionally updates the working directory to match. But when we pass a file path, **git reset** updates the *+staging area** to match the given commit instead of the working directory, and it does not move the current branch pointer. This means we can remove **blue.html** from the staged snapshot with the following command.

```console
Mon Jul 13 ~/iOS/RysGitTutorialRepository 
$ git reset HEAD blue.html 
Unstaged changes after reset:
M	blue.html
```

```console
Mon Jul 13 ~/iOS/RysGitTutorialRepository 
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   blue.html

no changes added to commit (use "git add" and/or "git commit -a")
```

This makes the **blue.html** in the staging area match the version stored in HEAD, but it leaves the working directory and current branch alone. The result is a stagging area that matches the most recent commit and a working directory that contains the modified **blue.html** file. In other words, this type of **git reset** can be used to unstage a file.

![Screen Shot 2020-07-13 at 2 23 45](https://user-images.githubusercontent.com/24994818/87311099-6e47ac80-c4e4-11ea-8abc-947a4879a100.png)

Let's take this one step further with **git checkout**. The **git checkout** we have been using updates the working directory and switches branches. If we add a file path to **git checkout**, it narrows its focus to only the specified file and does **not** update the branch pointer. This means that we can **"check out"** the most recent version of **blue.html** with the following command.

```console
Mon Jul 13 ~/iOS/RysGitTutorialRepository 
$ git checkout HEAD blue.html 
Updated 1 path from c5ba33c
```

```console
$ git status
On branch master
nothing to commit, working tree clean
```

Our **blue.html** file now looks exactly like the version stored in **HEAD**, and we thus have a clean working directory. Passing a file path to **git checkout** reverts that file to the specified commit.

![Screen Shot 2020-07-13 at 2 36 03](https://user-images.githubusercontent.com/24994818/87311154-7dc6f580-c4e4-11ea-9ffe-ead0f1934c4e.png)

To summarize the file-path behavior of **git reset** and **git checkout**, both take a committed snapshot as an reference point and make a file in the stagging area or the working directory match that reference, respectively.


# 	* [Aliases and Other Configurations](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 13. [Plumbing](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Examine Commit Details](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)	
# 	* [Examine a tree](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Examine a Blob](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Examine a Tag](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Inspect Git's Branch Representation](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Explore the Object Database](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Collect the Garbage](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Add Files to the index](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Store the Index in the Database](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Create a Commit Object](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Update HEAD](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Conclusion](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
# 	* [Quick Reference](https://github.com/c4arl0s/RysGitTutorial#rysgittutorial)
 
