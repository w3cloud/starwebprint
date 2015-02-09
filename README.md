# starwebprint
This is a sample javascript that code, that demonstrates how to print to a Star Micronics WebPrnt printer like TSP 654ii, using html2canvas open source library. Directly drawing to a HTML5 canvas is tedious job, both to develop and to maintain.. A significantly easier and better approach is to render a receipt with HTML div tags and convert it into canvas and send it to the printer

Following are the benefits of rendering first as html and convert it to canvas over dierctly drawing in the canvas:
* While drawign text to canvas, we have to code to do the word wrapping. HTML tags provide automatic word wrapping.
* First we have to determine the height of the canvas (paper). We have to calculate the height. Most of the time we may need a two pass logic.
* Images are can be sized easily with html.
* Easy code maintenance. You will be using the same technolgies (like angulajs) that you are already familier with.
