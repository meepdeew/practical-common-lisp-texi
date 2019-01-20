# practical-common-lisp-texi

[Practical Common Lisp](http://gigamonkeys.com/book/) typeset for [GNU Texinfo](https://www.gnu.org/software/texinfo/), Emacs' interactive documentation system. For when you've read enough in your browser to know that you don't want to read it in your browser.

To view in info-reader mode, open `pcl.info` with `C-u C-h i` (just as you would visit a file with `C-x C-f`).

![How It Looks](./pcl-info-screenshot.png)

TODOs:
- [ ] mid-section asides
  - [ ] @node 1-2 Where It Began
    `But I learned Lisp Once, And IT Wasn't Like what you're describing`
  - [ ] @node 8-7 Plugging the Leaks
    `Another classic macro-writing MACRO: ONCE-ONLY`
  - [ ] @node 14-6 Filenames
    `How We Got Here`
  - [ ] @node 15-2 *FEATURES* and Read-Time Conditionalization
    `Packaging the Library`
  - [ ] @node 16-8 Multimethods
    `Multimethods vs. Method Overloading`
  - [ ] @node 17-1 DEFCLASS
    `What Are "User-Defined Classes"?`
  - [ ] @node 19-3 Condition Handlers
    `JAVA-STYLE EXCEPTON HANDLING`
  - [ ] @node 19-6 Other Uses for Conditions
    `Writing Robust Software`
  - [ ] @node 27-1 The Database
    `The Package`
  - [ ] @node 28-2 Song Sources
    `The Package`
  - [ ] @node 29-1 Playlists
    `The Package`
  - [ ] @node 30-3 Character Escaping
    `The Package`
  - [ ] @node 30-6 The Pretty Printer Backend
    `Using Conditions to Have Your Cake and Eat It Too`
- [ ] tables
  - [ ] Table 6-1.
    `Assignment with = in Other Languages`
  - [ ] Table 8-1.
    `Backquote Examples`
  - [ ] Table 10-1.
    `Character Comparison Functions`
  - [ ] Table 10-2.
    `Literal Strings`
  - [ ] Table 10-3.
    `String Comparison Functions`
  - [ ] Table 11-1.
    `Basic Sequence Functions`
  - [ ] Table 11-2.
    `Standard Sequence Function Keyword Arguments`
  - [ ] Table 12-1.
    `Other List Functions`
  - [ ] Table 30-1.
    `FOO Output for Self-Evaluating Objects`
- [ ] footnotes
- [ ] inline text formatting
- [ ] images
  - [X] @node 12-1 cons cell diagrams
  - [X] @node 12-2 cons cell diagrams
  - [ ] @node 13-1 cons cell diagrams
  - [ ] @node 13-3 cons cell diagrams
  - [ ] @node 16-3 class hierarchy
  - [ ] @node 19-4 more con cells
  - [ ] @node 26-1 `Figure 26-1. Sample Web page`
  - [ ] @node 26-2 `Figure 26-2. http://localhost:2001/hello.html`
  - [ ] @node 26-3 `Figure 26-3. http://localhost:2001/random-number`
  - [ ] @node 26-6 `Figure 26-4. http://localhost:2001/show-query-params?foo=bar&baz=10`
  - [ ] @node 26-6 `Figure 26-5. http://localhost:2001/simple-form`
  - [ ] @node 26-6 `Figure 26-6. Result of submitting the simple form`
  - [ ] @node 26-7 `Figure 26-7. http://localhost:2001/show-cookies with no cookies`
  - [ ] @node 26-7 `Figure 26-8. http://localhost:2001/set-cookie`
  - [ ] @node 26-7 `Figure 26-9. http://localhost:2001/show-cookies after setting a cookie`


@emph for bold

@itemize @bullet
@item
Some text for foo.

@item
Some text
for bar.
@end itemize

green font!
‘Here's how you do it—and why’

Build from the project root with $ makeinfo pcl.texi
