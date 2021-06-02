# Future

## Video

<!--
Testing video embedding:
<iframe width="1280" height="720" src="https://www.youtube.com/embed/vgYS-F8opgE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Testing video embedding 2:
<iframe width="560" height="315" src="https://www.youtube.com/embed/vgYS-F8opgE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
-->

## Reminder: workflow

- Work in pairs (or groups of three); 'pair programming' style.
  - One of you is the _driver_: they share their screen and perform the actions.
  - The other(s) support(s) the driver, by e.g. looking up questions, and being
    active and engaged with the driver's work.
- Switch roles so that everyone in your team has been in the driver's seat:
  - The driver zips the entire project, and emails it to a partner *before the
    break*.
  - The recipient unzips all and confirms the project is complete.
  - Do not worry if you have not been able to finish the exercises. You can take
    your project to the next step.
- Ask for help when needed, we are happy to support you!
  - Use the "Ask for help" button in your breakout room. (Note that raised hands
    and chat messages will not be seen outside the room!)
  - A helper will join your breakout room.

## Exercise

**Before you start:** Make sure you have received the complete project folder as
a zipped file from your partner. Unzip the files.

1. [Make a new public repository on
   GitHub](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/creating-a-new-repository).
    * Do not create any files at this point, as they will conflict with your
      content.
1. Click on 'uploading an existing file', and drag and drop the contents of your
   folder to the repository.
    * Drag and drop the _files and folders inside_ of the main project folder;
      not the project folder itself.
    * Dropping a folder into the repository will upload all sub folders and
      files stored inside it.
    * Note that empty folders will not copy into a GitHub repository. Adding
      empty folders can be done with a workaround, but such a workaround should
      not be necessary when uploading a complete project. It is fine to leave
      these folders out at this point.
    * Click on 'commit changes' to complete the upload.
1. Add a license to the project:
    * Click 'Add file' > 'Create new file', and name your new file LICENSE
    * Go to [choosealicense.com](https://choosealicense.com/) and find a license
      that fits your project
    * Click through on the license of your choice, until you see a license text
      (for example, here is [the license text for the MIT
      license](https://choosealicense.com/licenses/mit/)). Copy this license
      text (just the text!) to the LICENSE file on your GitHub repository, and
      click 'Commit new file'.
1. Edit the changelog to reflect the addition of your license, and prepare for a
   new version release.
    * You can do this from inside GitHub, by clicking on the file, and then on
      the pen-icon to edit it. Don't forget to click 'Commit changes' when you
      are done, to save your changes.
    * You can also edit it locally and upload the changelog to your repository.
1. Connect your GitHub page to Zenodo.
    * [Log in to Zenodo's sandbox environment](https://sandbox.zenodo.org/login/?next=%2F)
    * Why are we using a Sandbox? Hint: the Sandbox is non-permanent, and
      forgets its "archived" projects!
    * Click 'log in with GitHub' and authorize Zenodo to connect to your GitHub account.
    * On Zenodo's main page, click on the triangle next to your name, and choose
      'GitHub'. Find the repository you just created, and enable Zenodo's access
      by toggling the switch to 'on'.
1. Make a release from the GitHub main page:
    * Click 'create a new release'
    * Tag the release with the version number. Note that it is common practice
      to prefix the letter 'v' to your version number; e.g.: v0.1.0.
    * Name the release. For example, using the version tag and the date (in
      YYYY-MM-DD format!)
    * Use the description field to copy the changelog information. Since this is
      the first release on GitHub, you can copy the entire changelog into the
      description. Future releases can be described by the changes made between
      the previous release and that one.
    * Click 'Publish release'.
1. Return to the GitHub page in your Zenodo profile. Verify that the repository
   is uploading. After the release is complete (this can take a while!), you
   should be able to click through to the sandbox page of your released project!
   * Under normal circumstances, you would get the DOI and place a badge in your
     GitHub README. Why should you not do this now you are working in the Zenodo
     sandbox?