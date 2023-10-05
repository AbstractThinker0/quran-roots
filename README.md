# Quran roots compilation

This repository hosts a list of Quranic roots and their derivatives in JSON format: [quranRoots.json](https://github.com/AbstractThinker0/quran-roots/blob/master/quranRoots.json). The list is based on the roots compilation from the Zekr.org App and can be found at [quran-root.txt](https://github.com/AbstractThinker0/quran-roots/blob/master/txt/quran-root.txt), This list is compatible with (Tanzil Project Quran text)[https://tanzil.net/download/]. Please note that this list has not been verified for accuracy.

# Issues in the original compilation

We have identified a few flaws in the original list:

- Some words are attributed to more than one root, as seen in the case of root 831 (سمو) and root 1844 (وسم), which share some derivatives in common.
- Some roots are incomplete, such as root 384 (حزب). This root lacks the occurrences of the word (احزاب), which is treated as a distinct "root" for some reason.
- Some roots are missing, as in the case of the root (حقف). We can see that root 23 (احقاف) is present, which is a derivative of (حقف).

# What's different from the original

Apart from being in JSON format and incorporating some improvements detailed in the (changelog)[https://github.com/AbstractThinker0/quran-roots/blob/master/CHANGELOG.md] the list remains identical to the original. Our future goal is to address and resolve all the issues present in the original compilation. For now, these issues have been partially addressed.
