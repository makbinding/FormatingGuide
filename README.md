# Formatting Guide

This guide is meant as a brief description of the template used for the printed books. The elements described below roughly correspond to the template's formatting elements. 

Although this is for the printed books, some of its rules can be also applied to e-books. You will however have to keep the text re-flowable, so the fixed-height choices will have to be redefined.

# Word Template Details

## Rythm

The rythm of the book is defined by the line spacing. This defines our grid and allows all page elements to align with each other accross pages. This requires that all element heights and margins are a multiple of the line spacing. 

Current choice is 15pt which gives ~40 lines in an A5 sized textblock. 

You need to pay attention to images. They should be kept inline to avoid moving them outside of the line spacing grid. Their height is in cm, but you can manually define it in pt and word will automatically  translate it to cm.

Changing the grid lines to 15pt also gives a nice visual verification that everything in the page follows the rythm.

Keeping a rythm and selecting multiples is the first step to also making your book reflowable for e-books. You will just have to define the element heights in relative terms. Unfortunately word is terrible for this. Html and css is what you really need.

## Margins
- Side margins are defined at 1.8cm. 
- Top and bottom are 4 x line spacing = 60pt which corresponds to ~2.1cm
- The default gutter is 5mm, but you should change it based on the thickness and binding of the book.

## Header / Footer
The top/bottom margins allow us to also have rythm at the header and footer if we set their distance from top/bottom to 0.

## Paragraph

- 12pt Garamond. It's a bit large to be easier to read. 11pt will work nicely as well with the 15pt line spacing
- Identation is 0.5cm on the first line. 
- No margins before or after the paragraph.

## Header, Title

- 30pt Goody Old Style with a 30pt line height. 
- Margins are 30pt before and after the header. This is meant to be used in Chapters, as the header will be included in the Table of Contents.
- The Title element is identical, but does not appear in the table of contents. Useful for example for the book front page or general purpose titles.
- You can select a page break before each header
- Header 2 is 15pt with 15pt line spacing. Subtitle is the same but does not appear to Table of Contents.

# Book Binding Details

The prefered method is sewn case binding. The page size is A5 (148mm x 210mm) just because of the easy availability of A4 paper. If you want proper paper grain, then the easiest way to get quality paper is probably to get A3 sheets and cut them (not in half)

Word can print the signatures in the correct order. Printing to pdf first allows you to easily review your settings for errors and gives you a reprintable final document.

The suggested dimensions are
- 16 page signatures (adjust according to the required swell)
- 4mm square
- 10mm hinge (8mm + thickness)
- Cover boards:
  - 210 + 2 x square = 218mm height
  - 148 + square - hinge = 142mm width
  - 2mm thickness (suggested to use 1mm if less than 100 pages)

Signature holes for A5 paper and 20mm cotton tapes:
10mm - 60mm - 20mm - 70mm - 20mm - 60mm - 10mm

For more information and help you may want to refer to the DAS Bookbinding channel on youtube.
https://www.youtube.com/channel/UCbCGQEhxF94sQqb3zUqChXw

