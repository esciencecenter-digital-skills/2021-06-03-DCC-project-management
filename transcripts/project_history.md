# Project history

Keeping track of your project history is important in many situations. If at a
later stage, you want to make sure that you understand the status quo at a
certain date, it is crucial that you kept track of your project's history
throughout its lifetime. For example: imagine your project, project A, is the
basis of someone else's project, project B. Project B uses project A in its latest and
most up-to-date state. But you continue working on project A and make several
updates. For project B, simply referring to project A will probably not be
sufficient. It would be useful instead to be able to refer to project A in a way
that makes it clear what the state was when the project was used.

In this section we are going to look into ways that you can keep track of your
project history. We will be using tools that you already understand. There are
more sophisticated tools out there, that we do want to recommend you look into.
Using dedicated version control software (such as Git) is easier than you may
think, and it is supported by many text editors and has several graphical
interfaces as well. Git is one of those tools that will save you so much time in
the long run and it is absolutely worth the time investment.

Let’s start with the basics though.

## 1. Keep a changelog.

A changelog is a dedicated file where you keep track of the history. This file
lives in the root of the project. The changelog describes important changes you
made to the project throughout its lifetime. These changes are always
accompanied by the date they were implemented. Descriptions in a change log need
not be complicated or elaborate, but they are an important reference for changes
that were made in the past, and when.

A changelog typically sorts changes into types: Added, for new features.
Changed, for changes in existing functionality. Deprecated, for soon-to-be
removed features. Removed, for now removed features. Fixed, for any bug fixes.
Security, in case of vulnerabilities.

## 2. Formalize updates using semantic versioning

When substantial changes have been made it can be useful to release a new
version of the project. You may have seen version numbers associated to software
or other projects in the past. They usually consist of three elements, and these
three numbers have their own meaning. First is the major version, then the minor
version, finally a patch number. This system is called semantic versioning. Not
every project follows these rules, but they are quite common, so these rules are
likely a useful reference when interpreting other projects version numbers.

This is what they mean: the patch number is updated when small repairs to the
project are made, or bugs are fixed. If new aspects of the project are added,
new functionality is introduced, then the minor version is updated. Importantly,
if another project, project B, uses your project, project A, and project B was
made using project A version 1.2.0, then an update in the minor version, to
version 1.3.0 should not break project B. In other words: new things can be
added, but a minor version change signals that nothing that worked before has
been affected.

If there is a big change, and, for example, an existing part of the project is
altered, then this warrants a major version change. At this point, the minor and
patch numbers go back to 0. If project B was built with project A version 1.2.0,
then project A version 2.0.0 no longer guarantees that it works the same way.

Using the number zero is a fully legitimate way to number versions. It does have
a specific role to play. The major version zero is reserved to indicate that
this project is still in its initial development. Thus, a common first version
of a project is 0.1.0. This is usually a project that is under development, but a
version is out that is ready to be shown to the world.

Once a version is released, any updates made to the project will be for the next
version. Did you make a new version release, only to realize you made a typo? That's your first
patch.

With every version change, you obviously update the changelog. What relevant
things happened between the previous version and now?

You may not think your project is worthy of versioning. Think back to the last
time you wrote a manuscript. Did it look anything like this? Those are versions,
too. They're just not properly standardized.