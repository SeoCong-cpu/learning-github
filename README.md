<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Introduction to GitHub

_Get started using GitHub in less than an hour._

</header>

<!--
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

## Finish

_Congratulations, you've completed this course and joined the world of developers!_

<img src=https://octodex.github.com/images/collabocats.jpg alt=celebrate width=300 align=right>

Here's a recap of your accomplishments:

- You learned about GitHub, repositories, branches, commits, and pull requests.
- You created a branch, a commit, and a pull request.
- You merged a pull request.
- You made your first contribution! :tada:

### What's next?

If you'd like to make a profile README, use the quickstart instructions below or follow the instructions in the [Managing your profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) article.

1. Make a new public repository with a name that matches your GitHub username.
2. Create a file named `README.md` in its root. The "root" means not inside any folder in your repository.
3. Edit the contents of the `README.md` file.
4. If you created a new branch for your file, open and merge a pull request on your branch.
5. Lastly, we'd love to hear what you thought of this course [in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github).

Check out these resources to learn more or get involved:

- Are you a student? Check out the [Student Developer Pack](https://education.github.com/pack).
- [Take another GitHub Skills course](https://github.com/skills).
- [Read the GitHub Getting Started docs](https://docs.github.com/en/get-started).
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore).

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>














# My Project Plan (Level 1 Heading)

***note:*** THis document is written merely as an illustrative example, and does not provide any working guide to an actual project.

### Proposal (Level 3 Heading)
---
I am planning to make a computer vision software that detects objects in images.
In order to build it, I will use opencv, deep learning libraries, such as [TensorFlow](https://www.tensorflow.org/?hl=ko) or [PyTorch](https://pytorch.org), and other open source softwares.

For example, the objects in the following images were detected using [mmdetection](https://github.com/open-mmlab/mmdetection):
![Images](https://user-images.githubusercontent.com/12907710/137271636-56ba1cd2-b110-4812-8221-b4c120320aa9.png)

---
### Dependencies (Level 3 Heading)
- python
- opencv-python
- tensorflow
- openmmlab
- package manager

### Installation

In a bash terminal, run the following commands (*Do NOT actually run these commands in your computer*):

```sh
$ sudo apt update
$ conda create -n cv_detection
$ conda activate cv_detection
$ python --version
$ python example.py
```
