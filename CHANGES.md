### Release Notes

#### **v0.16.4:**
- fixed pulse kernel-busy indicator

#### **v0.16.3:**
- removed broken matplotlib dependency
- added pulse kernel-busy indicator

#### **v0.16.2:**
- added matplotlib and seaborn dependencies
- updated index.ipynb for binder and compiled themes
- minor cosmetic improvements

#### **v0.16.1:**
- removed some excess fonts from sans-serif and serif collections
- added option for setting pandas dataframe font-size (-dfs , --dffontsize)
- added option for output area font-size (-ofs , --outfontsize)
- minor cosmetic improvements

#### **v0.16.0:**
- all fonts now default to whatever browser defaults are (users can still specify custom code-cell (-f), text-cell (-tcf), and notebook (-nbf) fonts as before).
- improved prompt style for text cells
- re-compiled css for binder
- minor cosmetic improvements

####  **v0.15.9:**
- improved kernel and notification widget alignment
- added helvetica, helveticaneue fonts
- fixed bug that prevented install if fontname not recognized
- added compatibility for hide_header nbext
- minor cosmetic improvements

#### **v0.15.8:**
- made changes to solarizedd style

#### **v0.15.7:**
- added solarized-dark theme "jt -t solarizedd" ([PR #103](https://github.com/dunovank/jupyter-themes/pull/103) submitted by [raybuhr](https://github.com/raybuhr))
- fixed jupyter-soft-selected style (multiple cell selected)
- modified table style
- deprecated -alt/--altlayout (use -altp/--altprompt for smaller prompts, no number)

#### **v0.15.6:**
- fixed bug that prevented fonts from being imported correctly

#### **v0.15.5:**
- added compatibility for Jupyter terminal app
- improved toolbar and NB name visibility
- better syntax highlighting in tracebacks
- widened main menubar container at top of NB
- notification widgets no longer interfere with menubar height
- minor cosmetic improvements
- added Hasklig monofont

#### **v0.15.4:**
- improved text editor visibility
- minor cosmetic improvements

#### **v0.15.3:**
- README & doc updates for jtplot module
- style fixes for new "add keyboard shortcuts" form
- minor cosmetic improvements

#### **v0.15.2:**
- re-added solarizedl theme (accidentally not included in v0.15.1)

#### **v0.15.1:**
- updated styles for notebook 5.0
- changed solarized-light to solarizedl
- cosmetic changes to onedork, solarizedl

#### **v0.15.0:**
- themed plotting styles
- python 3.6 compatibility

#### **v0.14.4:**
- fixed attribute and property syntax highlighting
- removed 'TeX' as preferred mathjax font

#### **v0.14.3:**
- [PR #102](https://github.com/dunovank/jupyter-themes/pull/102) submitted by  [pussinboot](https://github.com/pussinboot) fixed font installation [issue #71](https://github.com/dunovank/jupyter-themes/issues/71)

#### **v0.14.2:**
-removed numpy dependency ([meowklaski](https://github.com/meowklaski) : [PR #97](https://github.com/dunovank/jupyter-themes/pull/97))

#### **v0.14.1**
-fixed linenumbers in onedork theme

#### **v0.14.0:**
-add solarized light theme ([svendx4f](https://github.com/svendx4f): [PR #84](https://github.com/dunovank/jupyter-themes/pull/84))
-fixed bug that prevented theme reset
-fixed bug that prevented cursor settings from being applied
-made upload button visible on main page

#### **v0.13.9**
* minor bug fixes and thematic adjustments

#### **v0.13.8**
* add monokai theme ([bdell](https://github.com/bdell) : [PR #59](https://github.com/dunovank/jupyter-themes/pull/59))
* apply theme to auto-complete menu ([svendx4f](https://github.com/svendx4f) : [PR #69](https://github.com/dunovank/jupyter-themes/pull/69))
* added support for user less/precompiled themes ([osamaar](https://github.com/osamaar) : [PR #82](https://github.com/dunovank/jupyter-themes/pull/82))

#### **v0.13.7**
* misc visibility improvements

#### **v0.13.6**
* altlayout is now default for grade3 (white bg for txt/markdown)

#### **v0.13.5**
* full functionality has been added for Python 3.5
* better theme integration for command palette, keyboard shortcuts
* integration with Running, Clusters, and NBExtension pages.
* added font options for code-cells and notebook body
* vim nbextension compatibility provided by [alextfkd](https://github.com/alextfkd)
* customizable cursor color and size
