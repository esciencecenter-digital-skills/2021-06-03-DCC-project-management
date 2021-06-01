# Past

## Video

<!--
Testing video embedding:
<iframe width="1280" height="720" src="https://www.youtube.com/embed/vgYS-F8opgE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Testing video embedding 2:
<iframe width="560" height="315" src="https://www.youtube.com/embed/vgYS-F8opgE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
-->

## Reminder: workflow

Work in pairs ('pair programming' style):

- the *driver* shares their screen and performs the actions);
- the *partner* supports the driver, looks up questions, is active and engaged
    with the driver's work.

At the end of the exercise:

- the driver zips the entire project, and emails it to partner before the break;
- the partner unzips all and confirms the project is complete.

Ask for help when needed:

- raise your hand in the Zoom breakout;
- a helper will join your breakout room.

Prepare the discussion:

- write down any questions you would like to discuss with the group;
- discuss choices you make during the exercise, and write down your decisions;
- at the end of each workshop-element we will reconvene in a plenary session to
  discuss these.

## Exercise

**Before you start:** Make sure you have received the complete project folder as
a zipped file from your partner. Unzip the files.

Your project is growing! As you are continuing, it is good to keep track of your
changes, so that work done with different states of the project can be
adequately assessed later on. Your job will be to start a record of your changes
(a '[changelog](https://keepachangelog.com/en/1.0.0/)'), and create a first
version of your project. For this to make sense, you are invited to create a
figure with the data you have cleaned up during the first session.

1. Take a look at the changelog at the top of the page on
   [keepachangelog.com](https://keepachangelog.com/en/1.0.0/).
1. Create a file in the root called `CHANGELOG.txt`. If you feel comfortable
   with Markdown, please [use Markdown
   formatting](https://www.markdownguide.org/basic-syntax/), and name your file
   `CHANGELOG.md`.
1. Set up your changelog with a small introduction, for example (Markdown format):
  ```
  # Changelog

  All notable changes to this project will be documented in this file.

  The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
  and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
  ```
1. Define the version of your project, using [semantic
   versioning](https://semver.org/spec/v2.0.0.html). Make a first entry in the
   changelog, entering your version number, and the date. Be sure to enter the
   date in the YEAR-MONTH-DAY format:
  ```
  ## [VERSION] - YEAR-MONTH-DAY
  ### Added
  ```
1. Describe the current state of the project briefly in bullet points.
1. Zip the entire project, and save it using the name of the project and the
   version number. E.g.: `wooden-duck-situation-v0.1.1.zip`. Store the zipped
   version next to your project folder in your system.
1. Build on your project. The exact nature of this change is up to you and your
   creativity, but you could imagine:
    * making a plot of the data, plotting e.g. the number of hatched eggs to the
      weight of the birds, saving this image in a results folder;
    * describing the data cleaning steps you took in a 'methods' section of the
      documentation;
    * deleting your students' excel files from the project.
1. Prepare the release of a new version:
    * Describe your changes to the project briefly in the changelog, using the
      change type tags described by
      [keepachangelog.org](https://keepachangelog.com/en/1.0.0/#how): n.b.
      Added, Changed, Deprecated, Removed, Fixed, Security.
    * Define the version number of this new version, based on semantic
      versioning guidelines.
1. Zip the project and save it using the new version number, just outside your
   project's main folder.

When you are done: zip the entire project (you do not need to include the old
versions at this point), and email it to your partner. They will continue as the
driver during [FUTURE](lessons/future.md).