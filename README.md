# LaunchCode Education Slide Template

This repository contains a template for building LaunchCode-themed slides using HTML, CSS, JS, and Markdown. They're easy to work with for creating code-centric presentations.

Based on [`technopagan/slides-in-markdown`](https://github.com/technopagan/slides-in-markdown)

## Recommendations

If you wish to use the template, fork this repo and customize as desired.

If you want to create a collection of slides, we further recommend that you:

1. Enable GitHub Pages for the repo
2. Replace the contents of this README with an index of the various decks
3. Create subdirectories for organizing your decks by topic
4. Update the `template.html` file to include proper references to the include JS and CSS files
5. Copy `template.html` each time want to create a new deck

If you wand to create a set of slides within LaunchCodeEducation (assuming you have commit permissions to this org):

1. Clone this repo to a new local repo with a different name:
    ```nohighlight
    $ git clone git@github.com:LaunchCodeEducation/slide-template.git course-slides
    ```
    In this example, the new repo is named `course-slides`
1. Delete the origin:
    ```nohighlight
    $ git remote rm origin
    ```
1. Create a repo with the same name at within [LaunchCodeEducation](https://github.com/LaunchCodeEducation)
1. Add the new remote to your new local:
    ```nohighlight
    $ git remote add origin git@github.com:LaunchCodeEducation/course-slides.git
    ```
1. Push!

See [demo template](template.html) for details on how to create your slides within the template.
