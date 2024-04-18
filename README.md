<h1 align="center" display="inline" >Face Detection Model  </h1>
<h3 align="left">Technology Used:</h3>
<div align="left">
 
  ![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
  ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
  
</div>
<h3 align="left">Features:</h3>
<ul>
  <li>Use <a href="https://pypi.org/project/Flask/" target="_blank" > Flask </a> package to make API</li>
  <li>Use <a href="https://pypi.org/project/python-facepp/" target="_blank" > Python-FacePP </a>  package to compare faces</li>
  <li>Use <a href="https://pypi.org/project/python-facepp/" target="_blank" > Python-FacePP </a>  package to find out whether there is a face or a picture without faces</li>
  <li>Use <a href="https://pypi.org/project/python-facepp/" target="_blank" > Python-FacePP </a>  package to find out if there is one face or more than one face</li>
</ul>
<h3 align="left">Brief about the project:</h3>
<p>
The application serves as a tool for comparing faces in images with faces stored in a database, and for determining the presence of person in image, as well as whether there is more than one person in a image.<br> 
<b>Here's how it works:</b>
<ul>
  <li>Face Comparison: </li>
    <dl>Input:</dl>
      <dd>- The application receives an object containing the first image (the image to be searched for) and the images stored in the database.</dd>
    <dl>Process:</dl>
      <dd>- It compares the provided image with each image stored in the database until a similar match is found it return data. If no similar images are found, a "not found" message is returned.</dd>
 
  <li>Presence of person in image:
    <dt>Input:
      <dd>- send an image to determine if there are person in it.</dd>
    </dt>
    <dt>Process:
      <dd>- The application analyzes the image to identify any objects (person). If person are found, it returns an approval message for the photo; otherwise, it returns a rejection message.</dd>
    </dt>
  </li>
  <li>Detection of Single vs. Multiple Persons: </li>
    <dl>Input:</dl>
      <dd>- send an image to verify if it contains one or more persons.</dd>
    <dl>Process:</dl>
      <dd>- The application examines all objects in the image. If only one person is found, it returns an approval message, if more than one person is detected, it returns a rejection message.</dd>
 
</ul>
</p>
