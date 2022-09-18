# Dan Gilleland's FREE TEST BANK

> This repository is at the heart of a set of free samples demonstrating how to use GitHub and git submodules to work as a **Test Bank** for student work.


----

## Appendix

### Submodule Strategy

Why use git submodules?

- The parent repository (this one) gives an overview of all the test bank items; this allows instructors to 
  - better see and manage which evaluation items are being used in the current semester,
  - maintain subtle variations in evaluation items to 
    - minimize having to create completely new labs/etc. any time one is suspected to have a "leaked" answer key
    - deploy in the same term to give variation between sections or even students within a section
  - maintain consistency in presentation, rubrics, etc.,
  - track all active, reserve, and deprecated evaluation items,
  - plan for future evaluation items
  - use issues to better maintain the test bank as a group, and
- The actual labs/quizzes/etc. exist as submodules and thus each will reside in a separate repository; this isolation gives them the benefit of being
  - available as Template Repositories, making them easier to use/deploy to students (e.g.: through GitHub Classroom),
  - automated through GitHub Actions for
    - automated testing/marking (e.g.: unit tests)
    - deployment of other means of delivery (e.g.: packaged for Moodle imports, markdown-to-PDF processing, etc.)
  - maintainable through GitHub issues on an individual basis (fix typos, etc.)

### How to Use git Submodules

- [Working With Submodules](https://github.blog/2016-02-01-working-with-submodules/)
- [Managing git projects with submodules and subtrees](https://opensource.com/article/20/5/git-submodules-subtrees)
- [Using Submodules in git](https://www.vogella.com/tutorials/GitSubmodules/article.html)
- [Managing Git Projects: Git subtree vs. submodule](https://gitprotect.io/blog/managing-git-projects-git-subtree-vs-submodule/)
