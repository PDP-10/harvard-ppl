### Polymorphic Programming Language (PPL)

These files comes from the \[PPL,MWK] and \[PPL,SYS] directories on
the Stanford AI Lab PDP-10.

MWK is Mark Kahrs, and here is his recollection on why he made a copy
and why the files seem tailored for TENEX:

> I read the manual from Harvard and thought it looked very cool.  So,
> when I had a chance, I grabbed the files.  I am guessing that I
> grabbed them from PARC since Ed Taft was part of the PPL project at
> Harvard with Tom Cheatham.  And given that MAXC ran a version of
> TENEX, it all makes sense.

For completeness, a copy of the Unix version is also included.

According to Thomas Standish,

> PPL was written on a DEC PDP-10 at Harvard (1969-1971) by Standish
> and Ed Taft.  It was distributed to Brandeis, Cal Tech,
> Carnegie-Mellon, First Data Corp., Harvard, Irvine, Johns Hopkins,
> JPL, NSA, On-Line Systems, Princeton, Santa Barbara, Yale, TSC, and
> via the standard BBN-Tenex releases to Case, CCA, SRI, USC-ISI,
> Utah, Xerox PARC.  PPL has been implemented on the PDP-11/45 for use
> in Harvard’s undergraduate education program.  It was used from 1971
> to 1983 as the principal educational language for undergraduate
> education at Harvard.

According to Ed Taft,

> The language was designed by Tim Standish, based on work that he had
> done prior to becoming a professor at Harvard.  He recruited me to
> write the PDP-10 implementation, which I did under his guidance.  I
> worked on it sporadically during the school year and more
> intensively as a summer job working for Tim.  He and I jointly wrote
> the PPL User's Manual.  I eventually wrote a senior thesis, "Design
> and Implementation of PPL".
> 
> At Harvard, PPL was used as the programming language for an
> introductory programming class, NatSci 110, which was taught for
> many years.  Initially, students ran their PPL programs on a
> commercial PDP-10 time-sharing service.  Just before I graduated, a
> project was started to re-implement PPL for the PDP-11.  Harvard had
> a PDP-11 that had many terminals and was more readily accessible to
> undergraduates.  As I recall, the changes to the language were
> minor, but there were major improvements in the implementation.  One
> of the key players was Alfred Spector, who now works for Google; I
> don't remember the other participants.

According to languages.info from TECO EMACS,

> A language developed at Harvard for research in extensible
> languages, which turned into a pedagogic tool.  It was used to teach
> programming systems to non-science majors, and was quite successful
> in this task.  Its flavor is APL-ish, if you know APL; if not, then
> it's an interpretive, highly interactive language, with a great deal
> of power, allowing you to define new data types and operators, as
> well as performing in more mundane ways (e.g. like Basic).  PPL is
> now in use at several universities, most of whom run it under UNIX,
> and is the subject of at least two books on introductory
> programming.
> 
> Note from RMS:
> 
> My first system programming experience was helping a little in
> implementing PPL.  As far as I can see, any advantage it has over
> other languages for pedagogy lie in its interactive
> line-number-within-function editor, which somewhat resembles the APL
> editor.  This is easier than using a standard printing terminal text
> editor, and more so for students.  However, any display editor (such
> as EMACS) ought to even things out for other languages.
> 
> Aside from that, PPL does have the advantage of not having strong
> typing, so that the user is not burdened with data type declarations
> for variables.  This makes less to worry about when writing a simple
> program.  However, Lisp has the same advantage.
