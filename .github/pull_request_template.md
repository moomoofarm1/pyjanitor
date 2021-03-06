<!-- Thank you for your PR! 

BEFORE YOU CONTINUE! Please add the appropriate three-letter abbreviation to your title.

The abbreviations can be:
- [DOC]: Documentation fixes.
- [ENH]: Code contributions and new features.
- [TST]: Test-related contributions.
- [INF]: Infrastructure-related contributions.

Also, do not forget to tag the relevant issue here as well.

Finally, as commits come in, don't forget to regularly rebase!
-->

# PR Description

Please describe the changes proposed in the pull request: 

- 
- 
- 

<!-- Doing so provides maintainers with context on what the PR is, and can help us more effectively review your PR. -->

<!-- Please also identify below which issue that has been raised that you are going to close. -->

**This PR resolves #(put issue number here, and remove parentheses).**

<!-- As you go down the PR template, please feel free to delete sections that are irrelevant. -->

# PR Checklist

<!-- This checklist exists for newcomers who are not yet familiar with our requirements. If you are experienced with
the project, please feel free to delete this section. -->

Please ensure that you have done the following:

1. [ ] PR in from a fork off your branch. Do not PR from `<your_username>`:master, but rather from `<your_username>`:<branch_name>.
<!-- Doing this helps us keep the commit history much cleaner than it would otherwise be. -->
2. [ ] If you're not on the contributors list, add yourself to `AUTHORS.rst`.
<!-- We'd like to acknowledge your contributions! -->

## Quick Check

To do a very quick check that everything is correct, follow these steps below:

- [ ] Run the command `make check` from pyjanitor's top-level directory. This will automatically run:
    - black formatting
    - pycodestyle checking
    - running the test suite
    - docs build
    
Once done, please check off the check-box above.
    
If `make check` does not work for you, you can execute the commands listed in the Makefile individually.

## Code Changes

<!-- If you have not made code changes, please feel free to delete this section. -->

If you are adding code changes, please ensure the following:

- [ ] Ensure that you have added tests.
- [ ] Run all tests (`$ pytest .`) locally on your machine.
    - [ ] Check to ensure that test coverage covers the lines of code that you have added.
    - [ ] Ensure that all tests pass.

## Documentation Changes

<!-- If you have not made documentation changes, please feel free to delete this section. -->

If you are adding documentation changes, please ensure the following:

- [ ] Build the docs locally.
- [ ] View the docs to check that it renders correctly.

# Relevant Reviewers

<!-- Finally, please tag relevant maintainers to review. -->

Please tag maintainers to review.

- @ericmjl
