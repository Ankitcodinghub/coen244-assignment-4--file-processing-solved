# coen244-assignment-4--file-processing-solved
**TO GET THIS SOLUTION VISIT:** [COEN244 Assignment 4 –File Processing Solved](https://www.ankitcodinghub.com/product/coen244-assignment-4-file-processing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96242&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COEN244 Assignment 4 –File Processing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

Q1.&nbsp; Assume the information of all the TAs of ECE department is stored in a file that is called TAs.txt. In order to be eligible for the TA position, a student should currently registered and can not be an alumni. However the file is corrupted and includes some records of TAs who are already graduated and are not allowed to work as a TA. The format of the record of each TA on the file is as follows:

Student_Id First_Name Last_Name Hire_Year Classification(Grad or Alum) number_of_working_hours

First line of the file shows the total number of students records (max number of records is 100).

a) You need to write a program that reads the file information, removes the lines with the invalid TAs (those who have Alum as the value for classification) and updates the original file.

Here is an example:

TAs.txt

5

19577 sarah lee 2018 Grad 20 40087 peter johnson 2018 Grad 35 22136 rayan lee 2017 Alum 40 40143 ahmed mobarak 2019 Grad 36 40221 rafel Niro 2018 Alum 24

—————————————————————-

TAs.txt After Correction:

3

19577 sarah lee 2018 Grad 20 40087 peter johnson 2018 Grad 35 40143 ahmed mobarak 2019 Grad 36

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Hint: You can create an array of TA objects when you open the original TAs.txt file and read the information of TAs.

b) You need to implement a function AddnewTA() that prompt the user for the information of one TA. The user is expected to enter the Student_Id followed by the rest of information. The new TA should be added to the TAs.txt file. Please note that if the user enters a duplicate Student_Id (already existed in the file), the program should reject the input and keep looping until the user enters a non-existing ID.

Please not that your program should handle the exceptions if the user tries to enter information of the unexpected type.

Q2.

Assume class electronic_device stores the information of an electronic device with these attribute: Barnd (string), serial_number (int), color (string), price (double). The class has a virtual function member print().

<ul>
<li>The class cellphone is derived from the electronic_device and has one extra attribute number_of_cameras (int).</li>
<li>The class smartwatch is derived from electronic_device and has one extra attribute, battery_life (int).</li>
<li>The class laptop is derived form the electronic_device and has two extra attributes: number_of_cores (int) and touchscreen(bool (0 or 1))</li>
</ul>
<ol>
<li>a) &nbsp;Implement the above classes with the needed setter/getter functions. Print() function in each class should display data members of the object.</li>
<li>b) &nbsp;In the main program, create an array of base class pointers. Then create a set of objects from different derived classes using dynamic memory allocation and store them in the array of base class pointers.</li>
<li>c) &nbsp;Create a sequential file called information.txt and read the objects stored in the array of base class pointers one by one, determine class of each object’s class name and store these objects in that file. An object will be stored in the file by writing the type of object and the values of its data members, with single space between the fields. An example storage of the objects in the file is given below:</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Field 1 Field 2 Field 3 Field 4 Field 5 Field 6 Field 7

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
cellphone

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
Apple

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
110002

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
blue

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
1000

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td colspan="3" rowspan="1"></td>
</tr>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
laptop

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Dell

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
22342

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
black

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
800.5

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
smartwatch

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
Samsung

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
123456

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
gray

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
600

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
24

</div>
</div>
</td>
<td colspan="3" rowspan="1"></td>
</tr>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
laptop

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Lenovo

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
23345

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
black

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
1000

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td></td>
</tr>
<tr>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
smartwatch

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
Apple

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
2324395

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
gray

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
800

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
36

</div>
</div>
</td>
<td colspan="3" rowspan="1"></td>
</tr>
<tr>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
cellphone

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
LG

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
345522

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
silver

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
650

</div>
</div>
</td>
<td colspan="3" rowspan="1">
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td colspan="3" rowspan="1"></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
3/3

</div>
</div>
</div>
