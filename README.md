# starwebprint
This sample javascript code, demonstrates how to print to a Star Micronics Thermal printer like TSP 654ii webprnt, using html2canvas open source library. Directly drawing to a HTML5 canvas is time consuming job, both to develop and to maintain. A significantly easier and better approach is to render a receipt with HTML div tags and convert it into canvas and send it to the printer

Following are the benefits of rendering first as html and convert it to canvas over dierctly drawing in the canvas:
* While drawing text to a canvas, you have to code the word wrapping logic. HTML tags provide automatic word wrapping.
* First you have to determine the height of the canvas (paper). Then in the second pass you have to draw. In essense you need a two pass logic. By using html to render, you eliminate this hussle.
* Images are can be sized easily with html.
* Easy code maintenance. You will be using the same technolgies (like angulajs) that you are already familier with.
