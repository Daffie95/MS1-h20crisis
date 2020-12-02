# This page contains documentation for testing and debugging the project.

# Milestone Project 1

## The H20 Crisis

Please forward questions to my [e-mail](patrik.svahnstrom@gmail.com)

1. <strong>Testing</strong>
2. <strong>Bugs & Errors</strong>
3. <strong>Final Testing</strong>

# 1. Testing

Color codes:<br>
<span style="color:red;">Red is errors <br>
<span style="color:orange;">Orange is warnings<br>
<span style="color:green;">Green is fixed errors or warnings<br>

> <strong>#2020-12-02</strong> (~19:35) [Testing placeholder 404 page]
>
> > Expected result: 404 page to show when invalid link is selected.
> >
> > > Actual Result:
> >
> > > Measure Taken:

> <strong>#2020-12-02 (~13:20)</strong> [W3C CSS Validator - Jigsaw](https://jigsaw.w3.org/css-validator/)
>
> > <span style="color:orange;">unknown supplier extension</span><br>
> >
> > > - -webkit-background-size
> > > - -moz-background-size
> > > - -o-background-size
> > > > Measure Tanken:<span style="color:green;">No warnings found when removing webkit/moz/o-background-size.</span>

> <strong>#2020-12-01 (~18:30)</strong> [W3C CSS Validator - Jigsaw](https://jigsaw.w3.org/css-validator/)
>
> > <span style="color:red;">filepath errors across all pages.</span>
> >
> > > <span style="color: green;">Filepath errors across all pages (Fixed)</span>

> > <span style="color:red;">Background image slows down loading.</span>
> >
> > > <span style="color: green;">Backgrond image slows down loading (Fixed)</span>

> > <span style="color: orange;">Redundant code in css.style.</span>
> >
> > > <span style="color: red;">Redundant code in css.style </span>

# 2. Bugs & Errors

> <span style="color: orange;">Active link not showing correct color. (2020-11-30)

> - <strong>Expected result:</strong>
>   > "Help Us & Contacts" link to be correct color when active, and not green as it is in idle state.
>   >
>   > - <strong>Result:</strong>
>   >   > <span style="color: red;"> "Help Us & Contacts" link turns the wrong color on active but is being overwritten to turn back to green. </span>
>   > - <strong>Solution:</strong>
>   >   > <span style="color: green;">Targetting the correct class with proper selector</span>

# 3. Final Testing
