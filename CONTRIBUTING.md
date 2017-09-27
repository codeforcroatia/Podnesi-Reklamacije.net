# Contributing to Reklamacije.net

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to Reklamacije.net and its Alaveteli module, which is maintained by [MySociety](https://github.com/mysociety) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[I don't want to read this whole thing, I just have a question!!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## Code of Conduct

This project and everyone participating in it is governed by the [Code for Croatia Code of Conduct](https://github.com/codeforcroatia/codeofconduct). By participating, you are expected to uphold this code.

## I don't want to read this whole thing I just have a question!!!

> **Note:** Please don't file an issue to ask a question. You'll get faster results by using the resources below.

We have an official message board with a detailed FAQ and where the community chimes in with helpful advice if you have questions.

* [Diskurs, the official HrOpen and Code for Croatia message board](http://diskurs.open.hr)
* [Reklamacije.net FAQ](http://reklamacije.net/help)

If chat is more your speed, you can join the Code for Croatia Slack team:

* [Join the Code for Croatia Slack Team](http://codeforcroatia.org/slackin)
    * Even though Slack is a chat service, sometimes it takes several hours for community members to respond &mdash; please be patient!
    * Use the `#reklamacije-net` channel for general questions or discussion about Reklamacije.net
    * Use the `#general` channel for questions about Code for Croatia
    * Use the `#user-testing` channel for questions or discussion about user contribution in form of testing
    * Use the `#introductions` channel to introduce yourself to the community
    * There are many other channels available, check the channel list

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for Reklamacije.net. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](ISSUE_TEMPLATE.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Check the [admin manual](http://alaveteli.org/docs/running/admin_manual/).** You might be able to find the cause of the problem and fix things yourself. Most importantly, check if you can reproduce the problem [in the latest version of Alaveteli](http://github.com/mysociety/alaveteli/), if the problem is confirmed in core modules open new issue on [Alaveteli repo](http://github.com/mysociety/alaveteli/issues/new/).
* **Check the [FAQs on the forum](http://diskurs.open.hr/)** for a list of common questions and problems.
* **Perform a [cursory search](https://github.com/issues?q=+is%3Aissue+user%3Acodeforcroatia)** and also don't forget to [(search here)](https://github.com/issues?q=+is%3Aissue+user%3Amysociety)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which repository your bug is related to, create an issue on that repository and provide the following information by filling in [the template](ISSUE_TEMPLATE.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started Alaveteli, e.g. which command exactly you used in the terminal, or how you started Alaveteli otherwise. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or an Atom command, and if so which one?
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, **record the GIF with the [Keybinding Resolver](https://github.com/atom/keybinding-resolver) shown**. You can use [this tool](http://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **If you're reporting that Alaveteli crashed**, include a crash report with a stack trace from the operating system. Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), or put it in a [gist](https://gist.github.com/) and provide link to that gist.
* **If the problem is related to performance or memory**, include a CPU profile capture with your report.
* **If Chrome's developer tools pane is shown without you triggering it**, that normally means that you have a syntax error in one of your themes.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Can you reproduce the problem in latest stable [Alaveteli branch (see releases)](https://github.com/mysociety/alaveteli/releases)?**
* **Did the problem start happening recently** (e.g. after updating to a new version of Alaveteli) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of Alaveteli?** What's the most recent version in which the problem doesn't happen? You can download older versions of Alaveteli from [the releases page](https://github.com/mysociety/alaveteli/releases).
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.
* If the problem is related to working with files (e.g. opening and editing files), **does the problem happen for all files and projects or only some?** Does the problem happen only when working with local or remote files (e.g. on network drives), with files of a specific type (e.g. only JavaScript or RoR files), with large files or files with very long lines, or with files in a specific encoding? Is there anything else special about the files you are using?

Include details about your configuration and environment:

* **Which version of Alaveteli are you using?**
* **What's the name and version of the OS you're using**?
* **Are you running Alaveteli in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
* **Which theme do you have installed?**

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for Alaveteli or specific project Reklamacije.net, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](ISSUE_TEMPLATE.md), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

* **Check the [admin guide](http://alaveteli.org/docs/running/admin_manual/)** for tips — you might discover that the enhancement is already available. Most importantly, check if you're using [the latest version of Alaveteli](https://github.com/mysociety/alaveteli/releases) and if you can get the desired behavior by changing Alaveteli theme.
* **Check if there's already [a release](https://github.com/mysociety/alaveteli/releases) which provides that enhancement.**
* **Determine which repository the enhancement should be suggested in (Alaveteli core or theme).**
* **Perform a [cursory search](https://github.com/issues?q=+is%3Aissue+user%3Amysociety)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which repository (Alaveteli core or theme) your enhancement suggestion is related to, create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of Alaveteli which the suggestion is related to. You can use [this tool](http://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **Explain why this enhancement would be useful** to most Alaveteli users and isn't something that can or should be implemented as a core enhancement.
* **List some other text editors or applications where this enhancement exists.**
* **Specify which version of Alaveteli you're using.**
* **Specify the name and version of the OS you're using.**

### Your First Code Contribution

Unsure where to begin contributing to Reklamacije.net? You can start by looking through these `easy` and `help-wanted` issues:

* [Easy issues][easy] - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues][help-wanted] - issues which should be a bit more involved than `easy` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

### Pull Requests

* Fill in [the required template](PULL_REQUEST_TEMPLATE.md)
* Do not include issue numbers in the PR title
* Include screenshots and animated GIFs in your pull request whenever possible.
* End all files with a newline
* Avoid platform-dependent code

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests. Most labels are used across all Code for Croatia repositories, but some are specific to this repo.

[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in. For example, you might be interested in [open issues across `Reklamacije.net` and all Atom-owned packages which are labeled as bugs, but still need to be reliably reproduced](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Acodeforcroatia+label%3Abug+label%3Aattention-needed) or perhaps [open pull requests in `Reklamacije.net` which haven't been reviewed yet](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Apr+repo%3Acodeforcroatia%2Freklamacije.net+comments%3A0). To help you find issues and pull requests, each label is listed with search links for finding open items with that label in `Reklamacije.net` only and also in core Alaveteli repository. We  encourage you to read about [other search filters](https://help.github.com/articles/searching-issues/) which will help you write more focused queries.

The labels are loosely grouped by their purpose, but it's not required that every issue have a label from every group or that an issue can't have more than one label from the same group.

Please open an issue on `Reklamacije.net` if you have suggestions for new labels, and if you notice some labels are missing on some repositories, then please open an issue on that repository.
