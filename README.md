# Quran Roots Compilation

This repository contains a list of Quranic roots and their derivatives in JSON format: [quranRoots.json](https://github.com/AbstractThinker0/quran-roots/blob/master/quranRoots.json).

The list is based on the root compilation from the Zekr.org App, originally available at [quran-root.txt](https://github.com/AbstractThinker0/quran-roots/blob/master/txt/quran-root.txt). It is compatible with the [Tanzil Project Quran text version 1.1](https://tanzil.net/download/).

For convenience, a Quran text in JSON format that aligns with this root list is available here: [quran.json](https://github.com/AbstractThinker0/tadabor/blob/master/public/res/quran_v2.json).

> **Note:** This root list has not been fully verified for accuracy and may contain errors or omissions.

---

## TODO

- Verify all root assignments using a formula-based approach.  
  Currently, some assignments are partially based on approximations.

---

## Usage Examples

Explore practical applications of this root list:

- 🌿 [Roots Browser](https://tadabor.pages.dev/roots): Browse all compiled roots and view the verses in which each root appears.
- 🔍 [Quran Inspector](https://tadabor.pages.dev/inspector): Browse the Quran and inspect any word to view its root and derived forms.

# Issues in the Original Compilation

A few issues have been identified in the original root list:

- **Duplicate root assignments:** Some words are linked to more than one root. For example, roots 831 (سمو) and 1844 (وسم) share certain derivatives.
- **Incomplete roots:** Some roots are missing common derivatives. For instance, root 384 (حزب) does not include occurrences of the word "أحزاب", which is oddly treated as a separate root.
- **Missing roots:** Some legitimate roots are absent. For example, the root (حقف) is missing, although its derivative "الأحقاف" is listed under root 23 (احقاف), which itself is derived from (حقف).

---

# What’s Different from the Original

While the list remains largely faithful to the original compilation, several improvements have been made:

- Reformatted into JSON for easier programmatic use.
- Minor corrections and enhancements have been incorporated (see the [changelog](https://github.com/AbstractThinker0/quran-roots/blob/master/CHANGELOG.md)).

> **Note:** These issues have only been partially addressed so far. A comprehensive cleanup and verification is planned for future updates.

# How to get the root of a word

TODO: Outline both common and new methodologies for retrieving a root.
