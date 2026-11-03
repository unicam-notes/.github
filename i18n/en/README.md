# UNICAM Notes — Community

[Italiano](../../README.md) · English

UNICAM Notes collects notes, exercises and teaching materials shared by students and tutors at the University of Camerino. This repository contains the [organization profile](../../profile/README.md), guidelines and forms for the central Discussions space.

## Where to contribute

Pull requests must be opened in the specific course repository. Discussions must be opened only in the [central `unicam-notes/.github` space](https://github.com/unicam-notes/.github/discussions).

## Discussions

Use the [central Discussions space](https://github.com/unicam-notes/.github/discussions) for all courses. Specify the course or repository in each post; pull requests and teaching files remain in the course repositories. No Discussions setup is needed in individual course repositories.

| Category | Purpose | Slug |
| --- | --- | --- |
| Q&A | Questions and general discussions about courses, exercises and materials. | `q-a` |
| Contribution | Sharing new notes, exercises and other materials. | `contribution` |
| Correction | Reporting errors and suggesting corrections. | `correction` |

To share PDFs, ZIPs, Markdown, solutions or other relevant files, open a **Contribution** Discussion in the central space, specifying the course, or submit a pull request in the course repository. Attachments depend on GitHub’s supported formats and limits: if a file is not accepted, use an accessible link or a pull request to add it to the repository.

Only share materials you have the right to distribute. Credit the original author and source, and retain signatures, credits and copyright notices. The [BSD 3-Clause](../../LICENSE) applies to materials covered by that license; it does not automatically relicense third-party materials as BSD or authorize their distribution.

All UNICAM Notes repositories use the BSD 3-Clause license. Every contribution must comply with its terms; by submitting original materials, you agree to make them available under this license.

## Share files in a message

To share materials, open **New discussion → Contribution**, enter a title and write your message naming the course. Drag supported files directly into the message, paste images or add links. A pull request is not required to propose materials through a Discussion; attachments are not automatically added to the course repository.

## Guides

- [Contributing](CONTRIBUTING.md) · [Italiano](../../CONTRIBUTING.md)
- [Code of conduct](CODE_OF_CONDUCT.md) · [Italiano](../../CODE_OF_CONDUCT.md)
- Active Italian/English bilingual forms: [Q&A](../../.github/DISCUSSION_TEMPLATE/q-a.yml), [Contribution](../../.github/DISCUSSION_TEMPLATE/contribution.yml), [Correction](../../.github/DISCUSSION_TEMPLATE/correction.yml).

## Manual setup for maintainers

1. Keep the `.github` repository public and publish these files on its default branch. Shared files are used where a course repository does not define its own corresponding files; they are not copied into individual repositories.
2. In `unicam-notes/.github` only, open **Settings → General → Features** and enable **Discussions**. To display this space at organization level, enable organization Discussions and select `.github` as the source repository. Do not recreate categories in course repositories.
3. Under **Discussions → Categories**, configure only **Q&A**, **Contribution** and **Correction**. Use the question/answer format for Q&A and open discussions for the other two; do not use polls. Before deleting any default categories, move existing discussions into the appropriate one of these three categories.
4. Check the category URLs: they must end in `/categories/q-a`, `/categories/contribution` and `/categories/correction`, respectively. Each YAML filename must match the actual slug. Put extended descriptions such as “Questions and discussions”, “Sharing materials” and “Reporting corrections” in category descriptions to preserve the expected slugs.
5. Start a new discussion in each category and verify that the fields load. Check for local forms overriding the shared defaults.

The three active forms in `.github/DISCUSSION_TEMPLATE/` are bilingual: labels and instructions are available in Italian and English, and answers can be written in either language. GitHub has no language selector for a single form; separate language categories are unnecessary. The title uses the native Discussions field rather than an additional body field.

The license is not automatically inherited by other repositories: each repository must include its own BSD 3-Clause LICENSE file.

Official references: [shared files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file), [Discussion Forms](https://docs.github.com/en/discussions/managing-discussions-for-your-community/creating-discussion-category-forms), [syntax and slugs](https://docs.github.com/en/discussions/managing-discussions-for-your-community/syntax-for-discussion-category-forms).
