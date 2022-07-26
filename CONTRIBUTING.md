# Contributing

The repositories in this org are inactive and do not have any development
resources allocated for them. We are not looking for contributions at this time
but would love it if you would like to adopt a project or module.


## What it means to adopt a repository

After doing a little due diligence to ensure that the project is going to a good
home, we will transfer ownership to you. This means that you own the issue
queue, you own PR triage, you own release rights, everything. In turn, we will
ensure that redirects send users to your fork of the project.

*Note that Puppet, Inc. still retains license to all code we've contributed. This
means that you cannot change the license without conferring with us about it.*

Interested Puppet employees may continue to be involved with the project, but
they do so on an individual contributor basis, and not as a representative of
Puppet.


## How to adopt a repository

We are so glad to hear of your interest! First off, you'll want to familiarize
yourself with the project you're looking at. We're not going to quiz you about
it or anything, but we don't want you to accidentally become overwhelmed. Make
sure that you're familiar with:

* The codebase
* Pull requests and issue queue, both open and closed
* Any dependencies or frameworks used
* Any publishing marketplace, such as RubyGems or the Puppet Forge

Once you're ready, we'll transfer ownership and responsibility for the repository:

1. Let us know of your interest, either via an Open Source Stewards office hour
   in the Puppet Community Slack or by emailing us at open-source-stewards@puppet.com
    * Tell us a little bit about your plans for the project
    * Share the GitHub username or the org that should have ownership.
    * If we have any questions, we'll have a short conversation with you.
1. We'll transfer the repository to the namespace you provided. At this point,
   you assume ownership and responsibility for the project.
1. In a single commit, update the `README.md`, `CONTRIBUTING.md`, any metadata files,
   or any other files referring to Puppet as the maintainer to indicate the
   project's new status. You might be tempted to make other changes now, but resist
   that urge. This allows people to upgrade directly to your version with lower
   friction. Save your improvements for the next release.
   * If you're adopting a Forge module, you'll want to edit the `metadata.json` file
     and update the `author`, `source`, `project_page`, and `issues_url` fields to
     match your own Forge username and GitHub namespace.
1. Increment the project's `MINOR` SemVer version number, indicating that this is a
   backwards compatible update.
1. Tag a single release with that version. It should include the ownership changes
   but *no other code or functionality changes*, even if the previous release was
   broken in some way.
1. Publish it to any relevant marketplace, such as uploading a Forge module tarball
   or pushing a new gem.
1. Carry on as you wish; it's your baby now!


## Additional Resources

* [Puppet community guidelines](https://puppet.com/community/community-guidelines)
* [General GitHub documentation](https://help.github.com/)
* [Puppet Community Slack](https://slack.puppet.com)
