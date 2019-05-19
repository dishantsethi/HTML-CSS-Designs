# HTML For Beginners

- Hyper Text Markup Language
- It is not a programming language
- Building Blocks of a Webpage

## Tags

- Element names surrounded by angle brackets <>
- Normally comes in pair
- End tag usually comes with forward slash
- > \<tagname> content \</tagname>

## Tag attributes

- Provide information about the element
- Placed within the start tag
- > \<tagname attributename="attribute"> content \</tagname>

## HTML Page Structure

![HTML Page Structure](/html-structure.png)

- Everything is enclosed in \<html> .. \</html> tag
- \<head> .. \<head> tag has nothing to do with the page content, it has things like page title, link to css files, line to js file, meta data(searching keyword)
- \<body> .. \<body> have actual markup which is displayed in browser, it has things like paragraph, headings, audio, video, images, dropdowns etc.

## Lists

### Unordered Lists

- It is like a bullet point list
- \<ul> tag for unordered list
- \<li> tag for list items of unordered list
- >     <ul> <br>
  >         <li> Item 1 \</li> <br>
  >         <li> Item 2 \</li> <br>
  >     </ul>
- > - Item 1
  > - Item 2  

### Ordered Lists

- It gets rid of bullet points and replace them with ordered numbers
- \<ol> tag for ordered list
- \<li> tag for list items of ordered list
- >     <ol>
  >        <li> Item 1 </li>
  >        <li> Item 2 </li>
  >     </ol>

- > 1. Item 1
  > 2. Item 2

## Tables

- \<table> tag for table
- \<thead> tag for table headings
- \<tbody> tag for table data
- \<tr> tag for table row, present in both thead and tbody
- \<th> tag for table heading data, present in \<tr> of \<thead>
- \<td> tag for table body data, present in \<tr> of \<tbody>
- >      <table>
  >      <thead>
  >          <tr>
  >              <th> Name </th> 
  >              <th> address </th>
  >              <th> Email </th> 
  >          </tr>
  >      </thead>
  >      <tbody>
  >           <tr>
  >             <td> dishant </td>
  >              <td> remote </td>
  >              <td> dishant@dishant </td>
  >          </tr>
  >          <tr>
  >              <td> dhruv </td>
  >              <td> local </td>
  >              <td> dhruv@dhruv </td>
  >          </tr>
  >          <tr>
  >              <td> abc </td>
  >              <td> permanent </td>
  >              <td> abc@abc </td>
  >          </tr>
  >      </tbody>
  >      </table>
- <table>
     <thead>
       <tr>
       <th> Name </th> 
       <th> address </th>
       <th> Email </th> 
       </tr>
      </thead>
      <tbody>
       <tr>
       <td> dishant </td>
       <td> remote </td>
       <td> dishant@dishant </td>
       </tr>
       <tr>
       <td> dhruv </td>
       <td> local </td>
       <td> dhruv@dhruv </td>
       </tr>
       <tr>
       <td> abc </td>
       <td> permanent </td>
       <td> abc@abc </td>
       </tr>
      </tbody>
     </table>  

## Inline vs Block level Elements

### Inline Elements

- Do not start on a new line
- Take only the necessary width
- \<span>, \<img>, \<a>

### Block Elements

- Start on a new line
- Take full width available
- \<div>, \<h1>,..,\<h6>,\<p>,\<form>

## HTML Cheat Sheet

- \<!-- content --> for comments
- Ctrl + U to see the exact html source code running in the browser, this will show you exact html being parsed
- h1 to h6 tags for headings
    - \<h1> Heading one \<h1>
    - \<h2> Heading two \<h2>
    - \<h6> Heading six \<h6>
- \<p> tag for paragraphs
