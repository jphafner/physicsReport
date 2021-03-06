
# physics Report

# table of contents
- [introduction](#introduction)
- [lesson-plan](#lesson-plan)
- [dependencies](#dependencies)
- [resources](#resources)

# introduction

The purpose of this project is to provide a formal laboratory template that complies with professional style conventions.
It is recommended that this project be zip archived for upload to [Share LaTeX](https://www.sharelatex.com).

```bash
$ zip -r physicsReport.zip revtex_example*
```

# lesson-plan

This is my take on doing a formal laboratory report.
Take it with a grain of salt,
    as this reflects my values and experience.

The key feature of a formal laboratory is that it complies with professional standards and has been peer reviewed.
As long as the student submitted a draft copy for review,
    and were confident in checking off everything on the checklist,
    I gave them full credit.
If they submitted it for grading, without previously submitting for review and made changed accordingly,
    I would grade based on the rubric.
I view perfection as a process, and not as an achievable state.
The student must show that they iterated towards perfection,
    but not necessarily that they achieved perfection.

As for expectations for expressing uncertainty,
    I would expect all students to be able to express the average of measurement with a minimum and maximum value.
They could then use the average, minimum and maximum value for any calculated value.
For advanced students, I would expect them to be able to calculate the expectation and variance,
    and to propagate uncertainty accordingly in all calculated values.
I would provide any necessary formulas.
For instance: If E[_x_] is the expectation of the variable _x_,
    then the variance can be calculated by Var[_x_] = E[_x_<sup>2</sup>] &minus; E[_x_]<sup>2</sup>.

For first year students, I wanted the students to focus purely on the writing aspect,
    so I generated [fake data](https://github.com/jphafner/fakeData) for each student.
This gave each student unique data, so each report would be different.
The students were to write the methods section as how they would do it if they did.
I thought this was important to help keep the assignment in the zone of proximal development.
This will likely represent the first formal expository writing assignment for many of the students.
Which requires an odd mixture of precision, clarity and marketing.

For second year students or advanced students,
    I would want real data from any of the labs they performed.
I allowed for great flexibility on what the students could write about.

For style conventions, I strongly pushed the idea of _Least Ink_.
This means that you should have to defend every piece of ink on the paper,
    and that if you can not defend its presence, it should be removed.
This is a very simple and powerful idea.
I also only gave a maximum submission size of four pages,
    and not a minimum submission size.
When I asked students to defend a line placed on a graphic,
    or a superfluous word, and if they could not defend it,
    I would remind them to remove it.
Also, I did not push for a passive or active voice,
    as many do, I would frame the question through the least ink principle.

I have framed my lesson plan using a learning cycle.
I really have no preference for one learning cycle over another.
But evidence shows that you should unequivocally be using one.
I have utilized the Karplus learning cycle below,
    please do not feel like I have endorsed this over others.

## exploration (the E)

I only provided direct instruction to the point of having the zip file uploaded to [Share LaTeX](https://www.sharelatex.com).
I would also recommend reviewing some keyboard shortcuts,
    Ctrl-Z for undo, Ctrl-Y for redo, Ctrl-X for cut, Ctrl-C for copy, Ctrl-V for paste.

Once the entire class has the zip file successfully loaded to [Share LaTeX](https://www.sharelatex.com),
    I instruct them to make _small_ edits, and to recompile to see what happens.
I would give them at least 30 minutes to explore.
I think giving the students time to explore with no expectation is important.

## concept invention (the I)

This would be a good time for whiteboarding,
    make your own whiteboard to fill in the gaps of what you see.
I also gave a presentation on some of the basics ideas of a formal lab report.

## application (the A)

Where they write, and I proofread.
Checkout Benjamin Crowell's [_Light and Matter_](http://lightandmatter.com)
    for ideas on [comment codes](http://lightandmatter.com/lab_comment_codes.pdf).

# dependencies

These are only necessary if you desire to compile on your personal machine.
I will recommend [Share LaTeX](https://www.sharelatex.com) once again,
    as they have all necessary dependencies already.

- [hyperref](http://ctan.org/pkg/hyperree/)
- [microtype](http://ctan.org/pkg/microtype/)
- [pgfplots](http://pgfplots.net/)
- [revtex4-1](https://ctan.org/pkg/revtex4-1/)
- [siunitx](https://ctan.org/pkg/siunitx/)
- [subcaption](https://ctan.org/pkg/subcaption/)
- [TikZ/PGF](http://www.texample.net/tikz/)

# resources

- [Write Good Scripts](http://matt.might.net/articles/shell-scripts-for-passive-voice-weasel-words-duplicates/)
- [Sample Paper](http://web.mit.edu/8.13/www/Samplepaper/sample-paper.tex)

- [Edward Tufte](https://www.edwardtufte.com/tufte/)
- [Excel Charts](http://www.excelcharts.com/blog/posts/)
- [The Mayfield Handbook](http://www.mit.edu/course/21/21.guide/)
- [Turabian: A Manual For Writers](http://www.press.uchicago.edu/books/turabian/turabian_citationguide.html)
- [Physical Review Style Guide](http://journals.aps.org/files/styleguide-pr.pdf)
- [PRL Information for Authors](http://journals.aps.org/prl/authors)
- [REVTex Homepage](http://journals.aps.org/revtex/)
- [REVTex 4.1 Author's Guide](http://journals.aps.org/files/revtex/auguide4-1.pdf)
- [APS Author's Guide for RevTeX 4.1](http://journals.aps.org/files/revtex/apsguide4-1.pdf)
- [Author's Guide to AIP Substyles for REVTeX 4.1](http://journals.aps.org/files/revtex/aipguide4-1.pdf)

