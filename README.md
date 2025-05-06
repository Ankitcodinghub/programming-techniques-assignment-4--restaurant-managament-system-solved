# programming-techniques-assignment-4--restaurant-managament-system-solved
**TO GET THIS SOLUTION VISIT:** [Programming-Techniques Assignment 4 –Restaurant Managament System Solved](https://www.ankitcodinghub.com/product/programming-techniques-assignment-4-restaurant-managament-system-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97142&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming-Techniques Assignment 4 –Restaurant Managament System Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1. Requirements

Consider implementing a restaurant management system. The system should have three types of users: administrator, waiter and chef. The administrator can add, delete and modify existing products from the menu. The waiter can create a new order for a table, add elements from the menu, and compute the bill for an order. The chef is notified each time it must cook food that is ordered through a waiter.

Consider the system of classes in the diagram below.

To simplify the application, you may assume that the system is used by only one administrator, one waiter and one chef, and there is no need of a login process.

Solve the following:

1) Define the interface IRestaurantProcessing containing the main operations that can be executed by the waiter/administrator, as follows:

<ul>
<li>Administrator: create new menu item, delete menu item, edit menu item</li>
<li>Waiter: create new order; compute price for an order; generate bill in .txtformat.</li>
</ul>
2) Define and implement the classes from the class diagram shown above:

• Use the Composite Design Pattern for defining the classes MenuItem, BaseProduct and CompositeProduct

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
• Use the Observer Design Pattern to notify the chef each time a new order containing a composite product is added.

<ol start="3">
<li>3) &nbsp;Implement the class Restaurant using a predefined JCF collection that is based on a hashtable data structure. The hashtable key will be generated based on the class Order, which can have associated several MenuItems. Use JTable to display Restaurant related information.
<ul>
<li>Define a structure of type Map&lt;Order, Collection&lt;MenuItem&gt;&gt; for storing the order related information in the Restaurant class. The key of the Map will be formed of objects of type Order, for which the hashCode() method will be overwritten to compute the hash value within the Map from the attributes of the Order (OrderID, date, etc.).</li>
<li>Define an appropriate collection consisting of MenuItem objects to store the menu of the restaurant.</li>
<li>Define a method of type “well formed” for the class Restaurant.</li>
<li>Implement the class Restaurant using Design by Contract method (involvingpre, post conditions, invariants, and assertions).</li>
</ul>
</li>
<li>4) &nbsp;The menu items for populating the Restaurant object will be loaded/saved from/to a fileusing Serialization.</li>
</ol>
2. Deliverables

<ul>
<li>A solution description document (minimum 2000 words, Times New Roman, 10pt, Single Spacing) with the structure specified in the Lab Description document.</li>
<li>Source files</li>
<li>JavaDoc files including the custom tags and descriptions associated to the defined pre,post conditions and invariants</li>
<li>jar file required for executing the application</li>
<li>restaurant.ser – the file in which the Restaurant object is saved through serializationThe deliverables will be submitted as follows:</li>
</ul>
<ul>
<li>Create a repository on gitlab with the name:PT2020_Group_LastName_FirstName_Assignment_4</li>
<li>Push the following: source code (push the code not an archive with the code), jar file, restaurant.ser file, documentation</li>
<li>Share the repository with the user utcn_dsrl.</li>
</ul>
</div>
</div>
</div>
