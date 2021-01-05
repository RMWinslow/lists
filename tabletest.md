<style>
  table{
    overflow-x: scroll;
    width:auto;
    border: 0px;
  
  }
  
  table tr:nth-child(2n){background-color: rgba(255, 165, 0, 0);}
  
  th, td {vertical-align: top; border: 0px solid; padding: 0.4em}
  
  td:nth-child(4n) {
    border-right: 4px solid black;
  }
</style>


Some of the styling isn't being overtwritten. Hrm.

I can pretty easily type up songs in mathjax, but making it readable in markdown would be even better.
Just need a good way of dealing with vertically stacked characters, I guess.

Maybe I can include a kramdown frontmatter with the number of notes between the bars, and include a snippet of styletext based on that. 
Or have a bit of javasript in the head that defines it to be 4 by default, 
a bit of javascript in the foot that edits the style, 
and include a single line of js to change the value of that parameter when I need to. 




|   |   |   |   |
|---|---|---|---|
|1155|665-|4433|221-|
|5544|332-|5544|332-|
|1155|665-|4433|221-|

| | | | | | | | | | | | |
|---|---|---|---|---|---|---|---|---|---|---|---|
|1|1|5|5|6|6|5|-|4|4|3|3|2|2|1|-|
|5|5|4|4|3|3|2|-|5|5|4|4|3|3|2|-|
|1|1|5|5|6|6|5|-|4|4|3|3|2|2|1|-|

|1155|665-|4433|221-|
|5544|332-|55<span>4<br>g</span>4|332-|
|1155|665-|4433|221-|

|1|1|5|5|6|6|5|-|4|4|3|3|2|2|1|-|
|5|5|4|4|3|3|2|-|5|5|4|4|3|3|2|-|
|1|1|5|5|6|6|5|-|4|4|3|3|2|2|1|-|

|1|1|5|5|6|6|5|-|4|4|3|3|2|2|1|-|
|5|5|4|4|3|3|2|-|5|5|4|4|3|3|2|-|

<br><br>

|1155|665-|4433<br>123|221-|
|5544|332-|5544|332-|
|1155|665-|4433|221-|

|1|1|5|5|6|6|5|-|4|4|3|3<br>4|2|2|1|-|
|5|5|4|4|3|3|2|-|5|5|4|4|3|3|2|-|
|1|1|5|5|6|6|5|-|4|4|3|3|2|2|1|-|


|1|1|5|5|6|6|5|-|4|4|3|3<br>4|2|2|1|-|
|5|5|4|4|3|3|2|-|5|5|4|4|3|3|2|-|
|1|1|5|5|6|6|5|-|4|4|3|3|2|2|1|-|
{: style="width:auto; overflow-x: scroll;"}
