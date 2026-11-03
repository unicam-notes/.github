# UNICAM Notes — Community

[Italiano](../../README.md) · English

UNICAM Notes collects notes, exercises and teaching materials shared by students and tutors at the University of Camerino. This repository contains the [organization profile](../../profile/README.md), guidelines and Discussion Forms shared across course repositories.

## Discussions

| Category | Purpose | Slug |
| --- | --- | --- |
| Q&A | Questions and general discussions about courses, exercises and materials. | `q-a` |
| Contribution | Sharing new notes, exercises and other materials. | `contribution` |
| Correction | Reporting errors and suggesting corrections. | `correction` |

To share PDFs, ZIPs, Markdown, solutions or other relevant files, open a **Contribution** Discussion in the course repository or submit a pull request. Attachments depend on GitHub’s supported formats and limits: if a file is not accepted, use an accessible link or a pull request to add it to the repository.

Only share materials you have the right to distribute. Credit the original author and source, and retain signatures, credits and copyright notices. The [BSD 3-Clause](../../LICENSE) applies to materials covered by that license; it does not automatically relicense third-party materials as BSD or authorize their distribution.

All UNICAM Notes repositories use the BSD 3-Clause license. Every contribution must comply with its terms; by submitting original materials, you agree to make them available under this license.

## Guides

- [Contributing](CONTRIBUTING.md) · [Italiano](../../CONTRIBUTING.md)
- [Code of conduct](CODE_OF_CONDUCT.md) · [Italiano](../../CODE_OF_CONDUCT.md)
- Active Italian/English bilingual forms: [Q&A](../../.github/DISCUSSION_TEMPLATE/q-a.yml), [Contribution](../../.github/DISCUSSION_TEMPLATE/contribution.yml), [Correction](../../.github/DISCUSSION_TEMPLATE/correction.yml).
- English reference translations: [Q&A](DISCUSSION_TEMPLATE/q-a.yml), [Contribution](DISCUSSION_TEMPLATE/contribution.yml), [Correction](DISCUSSION_TEMPLATE/correction.yml).

## Manual setup for maintainers

1. Keep the `.github` repository public and publish these files on its default branch. Shared files are used where a course repository does not define its own corresponding files; they are not copied into individual repositories.
2. In each relevant repository, open **Settings → General → Features** and enable **Discussions**. For organization Discussions, also enable the feature in the organization settings and select the source repository.
3. Under **Discussions → Categories**, configure only **Q&A**, **Contribution** and **Correction**. Use the question/answer format for Q&A and open discussions for the other two; do not use polls. Before deleting any default categories, move existing discussions into the appropriate one of these three categories.
4. Check the category URLs: they must end in `/categories/q-a`, `/categories/contribution` and `/categories/correction`, respectively. Each YAML filename must match the actual slug. Put extended descriptions such as “Questions and discussions”, “Sharing materials” and “Reporting corrections” in category descriptions to preserve the expected slugs.
5. Start a new discussion in each category and verify that the fields load. Check for local forms overriding the shared defaults.

The three active forms in `.github/DISCUSSION_TEMPLATE/` are bilingual: labels and instructions are available in Italian and English, and answers can be written in either language. Copies under `i18n/en/` document the English version. GitHub has no language selector for a single form; separate language categories are unnecessary. The title uses the native Discussions field rather than an additional body field.

The license is not automatically inherited by other repositories: each repository must include its own BSD 3-Clause LICENSE file.

Official references: [shared files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file), [Discussion Forms](https://docs.github.com/en/discussions/managing-discussions-for-your-community/creating-discussion-category-forms), [syntax and slugs](https://docs.github.com/en/discussions/managing-discussions-for-your-community/syntax-for-discussion-category-forms).
