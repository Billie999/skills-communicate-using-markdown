
## Step 1: Add headers

_Welcome to "Communicate using Markdown"! :wave:_

**What is _Markdown_?** Markdown is a [lightweight syntax](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for communicating on GitHub. You can format text to add a heading, lists, **bold**, _italics_, tables, and many other stylings. You can use Markdown in most places around GitHub:

- Comments on [issues](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues), [pull requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests), and [discussions](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions)
- Files with the `.md` or `.markdown` extension
- Sharing snippets of text in [Gists](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists)

**What is a _header_?** A header is a larger bit of text at the beginning of a section. There are six sizes.

### Example

```md
# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest
```

#### How it looks

# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest

### :keyboard: Activity: Edit your file with headers

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. Open the **pull requests** tab.
1. Click **New pull request**, for the branches to compare, select `base: main` and `compare: start-markdown`.
1. Click **Create pull request**.
1. In this pull request, go to the **Files changed** tab. We made an empty file `index.md` for you.
1. Select **Edit file** from the three dotted **...** menu in the upper right corner of the file view on `index.md`.
1. On the **Edit file** tab, add a `#`, followed by a **space**, before any content you like to make it an H1 Header. You can add more headers, using one to six `#` characters followed by a **space**.
1. Above your new content, click **Preview**.
1. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file.
1. Click **Commit changes**.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

## Step 2: Add an image

_Great job adding headers to the file :sparkles:_

Let's add an image. Include descriptive text in the square brackets. This text is read aloud for people using screen readers. It's also shown at times when your image doesn't display, such as when there's a poor connection. You can see the syntax for images below:

### Example

```md
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

#### How it looks

<img alt="Image of Yaktocat" src=https://octodex.github.com/images/yaktocat.png width=400>

### :keyboard: Activity: Adding an image

1. As you did before, edit the `index.md` file in this pull request.
1. In the file, add the correct Markdown for your image of choice. Don't forget to include alt-text!
1. Use the **Preview** tab to check your Markdown formatting.
1. Commit your changes.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

## Step 3: Add a code example

_Great job adding an image to the file :tada:_

In addition to code blocks, some code blocks should be rendered differently depending on the language, such as JavaScript or command-line text.

### Example

<pre>
```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```
</pre>

#### How it looks

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

### :keyboard: Activity: Adding a code example

1. As you did before, edit the file in this pull request.
1. In the file, add the correct Markdown for a code example of your choice.
1. Use the **Preview** tab to check your Markdown formatting.
1. Commit your changes.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

## Step 4: Make a task list

_Great job adding a code example to the file :partying_face:_

**What is a _task list_?** A task list creates checkboxes to check off. They're very useful for tracking issues and pull requests. If you include a task list in the body of an issue or pull request, you'll see a progress indicator in your issue list. The syntax for task lists is very specific. Be sure to include the spaces where required, or else they won't render.

### Example

```
- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete
```

#### How it looks

- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete

### :keyboard: Activity: Add a task list

GitHub Actions went ahead and made a branch for you. So you'll need to add to the file we've created in the branch, and we will check your work as you work through this course!

1. Return to your pull request.
1. Use Markdown to create a task list. Here is an example:

   ```md
   - [ ] Turn on GitHub Pages
   - [ ] Outline my portfolio
   - [ ] Introduce myself to the world
   ```

   Remember, a task list starts with the syntax `- [ ]` and then the task list item. The formatting is specific!

1. Use the **Preview** tab to check your Markdown formatting.
1. Commit the changes to the file.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

## Step 5: Merge your pull request

_Great job adding a task list to the file :heart:_

You can now [merge](https://docs.github.com/get-started/quickstart/github-glossary#merge) your pull request!

### :keyboard: Activity: Merge your pull request

1. Click **Merge pull request**.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
## Finish

_Congratulations friend, you've completed this course!_

<img src=https://octodex.github.com/images/welcometocat.png alt=celebrate width=300 align=right>

Here's a recap of all the tasks you've accomplished in your repository:

1. You learned about Markdown, headings, images, code examples, and task lists.
1. You created and merged a Markdown file.
1. You learned an essential GitHub skill. 🎉

### What's next?

- You can enable GitHub Pages and see your Markdown file as a website!
  1. Under your repository name at the upper right, click :gear: **Settings**.
  1. Then on the lower left, click **Pages** in the **Code and automation** section.
  1. In the **GitHub Pages** section, ensure "Deploy from a branch" is selected from the **Source** drop-down menu, and then select `main` from the **Branch** drop-down menu as your GitHub Pages publishing source.
  1. Click the **Save** button.
  1. Wait about 30 seconds then refresh the page. When you see "Your site is published at ..." you can click on the link to see your published site.
- Learn more about [Markdown](https://docs.github.com/github/writing-on-github).
- We'd love to hear what you thought of this course [in our discussion board](https://github.com/skills/.github/discussions)
- [Take another GitHub Skills course](https://github.com/skills).
- [Read the GitHub Getting Started docs](https://docs.github.com/get-started).
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore).
