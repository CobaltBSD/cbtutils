# cbtutils (Cobalt Utils)

An assortment of various UNIX system utilities ported to Cobalt from a wide variety of sources. Most of these are ported from various UNIX-like sources that are not GNU/Linux. A few of these, such as our version of `ls`, are heavily modified from their original ported form to support additional functionality.

## Utils
* astro - Displays rising/setting times of various celestial objects (Ported from Plan9)
* banner - Displays an ASCII art text banner (Ported from Heirloom)
* fortune - Displays a random message from a database (Ported from OpenBSD)
* freq - Displays a histogram of character frequencies (Ported from Plan9)
* locale - Displays locale environment variables (Ported from OpenBSD)
* ls - List files (Forked from OpenBSD; heavily modified)
* nbperf - Generate a perfect hash function (Ported from NetBSD)
* news - Displays news items as they appear in a directory (Ported from Plan9)
* pbd - Display name of current working directory (Ported from Plan9)
* primes - Display primes in a selected range of numbers (Ported from OpenBSD)
* rs - Columnate a list of entries (Ported from NetBSD)
* unicode - Display unicode characters corresponding to a number (Ported from Plan9)
* units - Convert between different units (Ported from OpenBSD)
* unutf - Convert characters into their corresponding number (Ported from Plan9)

## Libraries
cbtutils also includes a shared lib9 and libbio, which are used by the Plan9 utilities.
