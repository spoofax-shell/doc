# Project Plan

It is important that all agreements between us, the client and the coach
concerning the content, goals and methods of the project are set out in writing.
The purpose of this document therefore is to describe these items and to
formally agree upon how the project is realised. If anything changes over the
course of the project, these changes need to be documented in written form.
While an e-mail describing these changes is often sufficient, we propose that
this document is updated accordingly (perhaps simply by referring to said
emails) such that this document is the one document required to track our
progress.

## The deliverable: what the client expects from us

From Spoofax's website:

> Spoofax is a platform for developing textual domain-specific languages with
> full-featured Eclipse editor plugins.

A feature that Spoofax is lacking is a Read-Eval-Print Loop (REPL) service
generator. A REPL is an interactive programming environment that takes single
expressions, evaluates them and prints the result(s). REPLs are a popular tool
for programming because they facilitate exploratory programming and debugging.
Common examples include command-line shells such as Bash and Python's REPL.

The deliverable for this project, then, is to create such a REPL generator for
the Spoofax Language Workbench. This REPL should provide the following features:

* TODO: based on the research report and the minutes of meeting 2016-04-19,
  make our own list of features that we will propose to Eelco and Gabriel.

Non-features (e.g. features that should *not* be implemented) are:

* TODO: see above.

If the above turns out to be (too) easy, the REPL can be extended into a
language playground such as the one offered by the Swift programming language.
If we decide to extend the project, new agreements will be made between us and
the client.

## Methodologies and tooling

During this project we will work using the SCRUM methodology with weekly
sprints. Our backlog, current and completed sprints will be managed using
Trello. Trello will also be used to communicate documents to the client
and the TU coach.

We will use pull-based development using GitHub. GitHub Issues will be used to
track issues (all of this will be linked to Trello in one way or another). To
facilitate this, we will be given our own repository within the Metaborg
organization. Each of us will then fork this repository to our private GitHub
accounts. We will also use one private repository to hold all the documents
(e.g. this document, the research project, et cetera) supporting our project.

Since Spoofax is an already existing project, we will use whichever tools are
already being used. This means that we will use:

* the Java programming language;
* Maven for the build environment;
* JUnit for unit tests.

## What TU Delft expects from us

This section's purpose is to document additional agreements between the TU coach
and us. For the regular project deadlines, please see the end of this section.

Weekly meetings will be held on mondays at 11.00 to discuss the past and next week.
and the overall progress of the project. Documents (such as the meeting topics)
that will be discussed will be emailed to the TU coach at its latest the evening
before the day of the meeting.

Minutes will be made of every meeting, whether with the client, the TU coach or both.
These minutes shall be sent to the TU coach as well.

Regular project deadlines:

* 19-04-2016: Project Plan
* 29-04-2016: Research Report
* 20-05-2016 - 27-05-2016: mid-project meeting (coordinator + team + client)
* 27-05-2016: SIG 1st submission
* 17-06-2016: Final Report
* 17-06-2016: BEP infosheet
* 17-06-2016: SIG 2nd submission
* 24-06-2016: Final presentation