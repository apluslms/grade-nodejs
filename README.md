Grading environment with specific Node.js version in path.

Tags
----

Images are tagged with Node.js and grading-base versions in format `<nodejs>-<grading-base>`.
Version tag can also include `uN` meaning _update N_ where N is an increasing number.
The update part is used to indicate updates to the image, where software versions did not change.
For an example, `8-2.0u1` includes Node.js 8 on top of grading-base 2.0 and has one update after first release.

There is also few additional versions of the image:

 * `zombie-*` includes zombie headless browser for nodejs


Utility commands
----------------

In addition to [grading-base](https://github.com/apluslms/grading-base), this container provides following utilities.
