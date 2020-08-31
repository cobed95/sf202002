# Software Foundations, SNU M1522.001200, 2020 Fall

- Instructor: Prof. [Chung-Kil Hur](http://sf.snu.ac.kr/gil.hur)
    + Email address: gil.hur@sf.snu.ac.kr
    + Office: 302-426
- TA: [Dongjoo Kim](http://sf.snu.ac.kr/dongjoo.kim)
    + Email address: dongjoo.kim@sf.snu.ac.kr
    + Office: 302-312-2
- Class material: http://www.cis.upenn.edu/~bcpierce/sf/current/index.html
- Please use email to ask questions (Don't use GitHub Issues)

## Announcements

TBA

## Assignments

TBA

## Grading

TBA

## Coq

- Install Coq [8.12.0](https://coq.inria.fr).
    + Using an installer (Windows, MacOS)
        * Download [Binaries](https://coq.inria.fr/download) and install it.

    + Using OPAM (Linux / MacOS)
        * OPAM is OCaml package manager, and you can use it to install Coq in Linux.
        * See [https://coq.inria.fr/opam/www/using.html](https://coq.inria.fr/opam/www/using.html).

    + Using brew (MacOS)
        * Run `brew install coq`.
        * Note this wouldn't install CoqIDE.

- Install IDE for Coq.
    + CoqIDE: installed by default.
    + Emacs: [Company-Coq](https://github.com/cpitclaudel/company-coq). Follow the setup instructions.
        * If it shows `Searching for program No such file or directory coqtop` error, please add `(custom-set-variables '(coq-prog-name "PATH/TO/coqtop"))` to `.emacs` file.
        * In case of MacOS, coqtop is at `/Applications/CoqIDE_8.9.1.app/Contents/Resources/bin/`.

#### Honor Code: *DO NOT CHEAT*
- Do not copy others' source code, including other students' and resources around the web. Especially, do not consult with public repositories on software foundations.
- Assignment score will be adjusted with the exam score. See above.