# oop244-workshop-6-class-with-a-resource-solved
**TO GET THIS SOLUTION VISIT:** [OOP244-Workshop 6 Class with a Resource Solved](https://mantutor.com/product/oop244-workshop-6-class-with-a-resource-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;59049&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;OOP244-Workshop 6 Class with a Resource Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In this workshop, you are to design and code a class type that accesses a resource.

<h1>LEARNING OUTCOMES</h1>
Upon successful completion of this workshop, you will have demonstrated the abilities to:

<ul>
<li>define a copy constructor</li>
<li>define an assignment operator</li>
<li>define a destructor</li>
<li>avoid duplication in coding these special member functions</li>
<li>describe what you have learned in completing this workshop</li>
</ul>
&nbsp;

<ul>
<li></li>
</ul>
<strong>IN</strong><strong>–</strong><strong>LAB </strong><strong>&nbsp;</strong>

Design a class named Contact, in namespace sict.&nbsp; This class holds information about a person and their phone numbers.&nbsp; The maximum number of characters in the person’s name is stored in an unmodifiable variable named MAX_CHAR. The type Contact contains the following information:

an array of characters of size MAX_CHAR (excluding the null byte ‘\0’) that holds the name of the contact;

a pointer to a <strong>dynamically allocated</strong> array of phone numbers.&nbsp; A valid phone number has one to two digits for the country code (cannot be zero), <strong>exactly</strong> three digits for the area code (cannot start with zero) and <strong>exactly</strong> seven digits for the number (cannot start with zero);

the number of phone numbers currently stored in the <strong>dynamically allocated</strong> array;

Your type exposes the following public member functions:

<strong>default constructor</strong> (a constructor with no parameters): this constructor sets the current object to a safe empty state;

<strong>constructor with 3 parameters</strong>: This constructor receives the address of an unmodifiable C-style string that holds the name of the contact, the address of an unmodifiable array of phone numbers and the number of phone numbers stored in the array. This constructor allocates enough memory dynamically to hold <strong>only the valid</strong> phone numbers from the array received and copies the valid numbers into the allocated array;

<strong>destructor</strong>: the destructor deallocates any memory that has been allocated dynamically;

bool isEmpty() const: a query that returns false if the current object has valid data; true if the object is in a safe empty state;

void display() const: a query that inserts into the standard output stream the data stored by the object applying the following format:

If the object is in a safe empty state, this function displays the following message:

Empty contact!&lt;ENDL&gt;

If the object is not in a safe empty state, this function displays the following message:

CONTACT_NAME&lt;ENDL&gt;

(+COUNTRY_CODE) AREA_CODE NNN-NNNN&lt;ENDL&gt;

(+COUNTRY_CODE) AREA_CODE NNN-NNNN&lt;ENDL&gt;

<ul>
<li>••</li>
</ul>
(+COUNTRY_CODE) AREA_CODE NNN-NNNN&lt;ENDL&gt;

Introduce as many private member functions as necessary to avoid any duplication of code in your Contact module.&nbsp; Store your class definition in a header file named Contact.h and your function definitions in an implementation file named Contact.cpp.&nbsp; Avoiding duplication will reduce the time that you will need to spend on the at home section.

Using the sample implementation of the w6_in_lab.cpp main module listed below, test your code and make sure that it works on Visual Studio.&nbsp; The expected output from your program is listed below this source code. The output of your program should match <strong>exactly</strong> the expected one.

<strong>I</strong><strong>N</strong><strong>-L</strong><strong>AB </strong><strong>M</strong><strong>AIN </strong><strong>M</strong><strong>ODULE</strong>

<table width="628">
<tbody>
<tr>
<td width="628">#include &lt;iostream&gt;

#include “Contact.h”

using namespace std; using namespace sict;

&nbsp;

int main()

{

cout &lt;&lt; “—————————————-” &lt;&lt; endl;

cout &lt;&lt; “Maximum no of characters in a name: “&lt;&lt; sict::MAX_CHAR &lt;&lt; endl;

cout &lt;&lt; “—————————————-” &lt;&lt; endl;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; “Testing the default constructor!” &lt;&lt; endl;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; “—————————————-” &lt;&lt; endl;&nbsp;&nbsp;&nbsp;&nbsp; sict::Contact empty; // sict:: intentional&nbsp;&nbsp;&nbsp;&nbsp; empty.display();

cout &lt;&lt; “—————————————-” &lt;&lt; endl &lt;&lt; endl;

&nbsp;

cout &lt;&lt; “—————————————-” &lt;&lt; endl;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; “Testing an invalid contact!” &lt;&lt; endl;

cout &lt;&lt; “—————————————-” &lt;&lt; endl;

Contact bad(nullptr, nullptr, 0);&nbsp;&nbsp;&nbsp;&nbsp; bad.display();

Contact alsoBad(“”, nullptr, 0);&nbsp;&nbsp;&nbsp;&nbsp; alsoBad.display();

cout &lt;&lt; “—————————————-” &lt;&lt; endl &lt;&lt; endl;

cout &lt;&lt; “—————————————-” &lt;&lt; endl;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; “Testing the constructor with parameters!” &lt;&lt; endl;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; “—————————————-” &lt;&lt; endl;
</td>
</tr>
<tr>
<td width="628">&nbsp;&nbsp;&nbsp; Contact temp(“A contact with a very looooong name!”, nullptr, 0);&nbsp;&nbsp;&nbsp;&nbsp; temp.display();

cout &lt;&lt; “—————————————-” &lt;&lt; endl &lt;&lt; endl;

&nbsp;

cout &lt;&lt; “—————————————-” &lt;&lt; endl;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; “Testing a valid contact!” &lt;&lt; endl;

cout &lt;&lt; “—————————————-” &lt;&lt; endl;

long long phoneNumbers[] = { 1416123456LL, 14161234567LL, 1416234567890LL,

14162345678LL, -1LL, 124163456789LL,

14161230002LL };

Contact someContact(“John Doe”, phoneNumbers, 7);&nbsp;&nbsp;&nbsp;&nbsp; someContact.display();

cout &lt;&lt; “—————————————-” &lt;&lt; endl &lt;&lt; endl;

&nbsp;

return 0;

}
</td>
</tr>
</tbody>
</table>
<strong>I</strong><strong>N</strong><strong>-L</strong><strong>AB </strong><strong>O</strong><strong>UTPUT</strong>

—————————————-

Maximum no of characters in a name: 20

—————————————-

Testing the default constructor! —————————————-

Empty contact!

—————————————-

&nbsp;

—————————————-

Testing an invalid contact!

—————————————-

Empty contact!

Empty contact!

—————————————-

&nbsp;

—————————————- Testing the constructor with parameters!

—————————————-

A contact with a ver

—————————————-

&nbsp;

—————————————-

Testing a valid contact!

—————————————-

John Doe

(+1) 416 123-4567

(+1) 416 234-5678

(+12) 416 345-6789

(+1) 416 123-0002

—————————————-

<strong>A</strong><strong>T</strong><strong>-H</strong><strong>OME </strong><strong>&nbsp;</strong>

For the <em>at-home</em> part, copy the Contact module that you created for your <em>inlab</em> submission. Declare the following additional member functions in the class definition and implement them in the .cpp file:

<strong>copy constructor</strong>: this constructor receives an unmodifiable reference to a

Contact object copies that object into the newly created instance; <strong>copy assignment operator</strong>: this operator receives an unmodifiable reference to a Contact object and copies the content of that object into the existing current object and returns a reference to the current object, as updated.

<strong>an overloaded += operator</strong>: this operator receives a new phone number as its parameter, validates the number received and, if valid, resizes the phone number array to hold all the existing numbers plus the received one and finally adds this new number to the array. If the number is not valid, this operator retains the original array and does not add the number.&nbsp; In either case, this operator returns a reference to the current object.

<strong>N</strong><strong>OTE</strong>: When you implement the copy assignment operator, make sure that the Contact instance is not being set to itself.

Using the sample implementation of the w6_at_home.cpp main module listed below, test your code and make sure that it works on Visual Studio. The expected output from your program is listed below this source code. The output of your program should match <strong>exactly</strong> the expected one.

<strong>A</strong><strong>T</strong><strong>-H</strong><strong>OME </strong><strong>M</strong><strong>AIN </strong><strong>M</strong><strong>ODULE</strong>

<table width="628">
<tbody>
<tr>
<td width="628">#include &lt;iostream&gt;

#include “Contact.h”

using namespace std; using namespace sict;

&nbsp;

int main() {

cout &lt;&lt; “—————————————-” &lt;&lt; endl;

cout &lt;&lt; “Maximum no of characters in a name: “&lt;&lt; sict::MAX_CHAR &lt;&lt; endl;&nbsp;&nbsp;&nbsp;&nbsp; sict::Contact theContact(“John Doe”, nullptr, 0); // sict:: intentional&nbsp;&nbsp;&nbsp;&nbsp; theContact.display();&nbsp;&nbsp;&nbsp;&nbsp; theContact += 14161234567LL;&nbsp;&nbsp;&nbsp;&nbsp; theContact += 14162345678LL;
</td>
</tr>
<tr>
<td width="628">&nbsp;&nbsp;&nbsp; theContact += 14163456789LL;&nbsp;&nbsp;&nbsp;&nbsp; theContact += 114164567890LL;&nbsp;&nbsp;&nbsp;&nbsp; theContact.display();

&nbsp;

cout &lt;&lt; endl &lt;&lt; “Testing! Please wait:” &lt;&lt; endl;

&nbsp;

for (int i = 1; i &lt;= 5000000; i++)

{

Contact temp = theContact;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; theContact = temp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; theContact = theContact;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (!(i % 10000))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; “.”;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (!(i % 500000))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; endl;

}

cout &lt;&lt; endl;

theContact.display();

&nbsp;

theContact = Contact(“”, nullptr, 0);&nbsp; theContact += 14161230002LL;&nbsp; theContact.display();

&nbsp;

return 0;

}
</td>
</tr>
</tbody>
</table>
<strong>A</strong><strong>T</strong><strong>-H</strong><strong>OME </strong><strong>E</strong><strong>XPECTED </strong><strong>O</strong><strong>UTPUT</strong>

<table width="628">
<tbody>
<tr>
<td width="628">—————————————-

Maximum no of characters in a name: 20

-John Doe

John Doe

(+1) 416 123-4567

(+1) 416 234-5678

(+1) 416 345-6789

(+11) 416 456-7890

&nbsp;

Testing! Please wait:

…………………………………………..

…………………………………………..

…………………………………………..

…………………………………………..

…………………………………………..

…………………………………………..

…………………………………………..

…………………………………………..

………………………………………….. …………………………………………..

John Doe

(+1) 416 123-4567 (+1) 416 234-5678

(+1) 416 345-6789

(+11) 416 456-7890 Empty contact!
</td>
</tr>
</tbody>
</table>
<strong>REFLECTION </strong><strong>&nbsp;</strong>

Study your final solution, reread the related parts of the course notes, and make sure that you have understood the concepts covered by this workshop.

Create a file named reflect.txt that contains your <strong>detailed description of the topics that you have learned </strong>in completing this workshop and mention any issues that caused you difficulty. Include in your explanation—<strong>but do not limit it to</strong>—the following points:

<ul>
<li>Why does the copy assignment operator check for self-assignment before doing anything else? What could go wrong if the operator doesn’t check for self-assignment?</li>
<li>List examples of how you avoided code duplication.</li>
</ul>
