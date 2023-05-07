Download Link: https://assignmentchef.com/product/solved-paraphrassing-tool-in-c
<br>
<strong>Paraphrasing Application</strong>

Paraphrasing is the process of rewording a text, often done for simplification or clarity. Implement a simple C++ console-based application for paraphrasing purposes, in the following manner.

<ol>

 <li>Create a class <strong>Dictionary</strong> that contains a list of words represented by class <strong>Word</strong>.</li>

 <li>A <strong>Word</strong> has a text (of type String, implemented in Assignment-2) and a list of synonyms, where each synonym is also represented as a (pointer to) <strong>Word</strong>.</li>

 <li><strong>Dictionary</strong> shall load its list of words from a file that contains a list of words and synonyms, where each synonym is separated by a single white space character, as in the following example:</li>

</ol>

<table width="584">

 <tbody>

  <tr>

   <td width="584">abandon discontinue vacate absent missing unavailable cable wirecalculate compute determine measure safety security refuge</td>

  </tr>

 </tbody>

</table>

<ol start="4">

 <li>Create a class <strong>Paraphraser</strong> that:

  <ol>

   <li>takes a text as input from the user and tokenize it into words.</li>

   <li>For each word, look it up in the <strong>Dictionary</strong> and replace it with a corresponding synonym (selected randomly in case of multiple options)</li>

   <li>Produce the output as paraphrased text</li>

  </ol></li>

</ol>