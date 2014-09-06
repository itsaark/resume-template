## LaTeX Resume Template

I haven't been able to find a LaTeX resume template that I liked, so I created my own.  It's fairly basic, but in my opinion its readable and straightforward.  I've provided a sample.pdf for reference.

Feel free to use and modify as you wish.  If you notice any errors, please help me out and submit a pull request.

The files that I created are resume.tex and resume.cls.  The rest of the files are supporting packages that I needed for a successful compile, and so you should use them.  But I didn't write them.

## Installation

Pull the entire directory as is, the supporting files are there for successful compilation. Any packages that are included but don't have an associated file were already on my system.  Because the template uses FontAwesome, you should use XeLaTeX (PDFLaTeX won't work).

The only file that you need to edit is `resume.tex`.  The current file provides sample usage.

When you're done, run this command in terminal (make sure XeLaTeX is installed first!):

`xelatex resume.tex`

A file `resume.pdf` will be created in the same directory.  That's it!

## License

The code that I created is licensed under the MIT license.  The rest are copyright/licensed by their respective authors.

