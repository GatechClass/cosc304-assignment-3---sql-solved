# cosc304-assignment-3---sql-solved
**TO GET THIS SOLUTION VISIT:** [COSC304 Assignment 3 – SQL Solved](https://mantutor.com/product/cosc-304-introduction-to-database-systems-assignment-3-sql-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113967&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSC304 Assignment 3 - SQL Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
customer(cid: integer, cname: string, address: string, city: string, state: string) product(pid: integer, pname: string, price: currency, inventory: integer) shipment(sid: integer, cid: integer, shipdate: DateTime) shippedproduct(sid: integer, pid: integer, amount: integer)

1. Return the customer name and address as one field called fullAddress that consists of the address, city, state. Only show customers in ‘IA’ or ‘BC’ that have a valid address. Order by customer name ascending. Hint: You will need the concat function in MySQL or the concatenate operator (||) if using PrairieLearn.

Output: +—————–+————————————-+ | cname | fullAddress | +—————–+–

———————————–+ | Aiden Adams | 324 2A Street, Kelowna, BC | | Beth Rosebud | 1 First

Street, Muscatine, IA | | David Denter | 23456 Main Street, Vernon, BC | | Elish Elias | 3445 Hwy 97 North,

Iowa City, IA | +—————–+————————————-+

Output:

+—–+———————+—–+——–+ | sid | shipdate | pid | amount | +—–+———————+–

1. Find all customers that have an ‘R’ or ‘T’ in their name and have a state of ‘MI’ or ‘IA’. Order by customer name descending.

Output:

+—–+—————–+———————+———–+——-+ | cid | cname | address | city | state |

+—–+—————–+———————+———–+——-+ | 8 | Shannon Rose | NULL | Wyandotte | MI

| | 2 | Joe Smithsonian | 245 Straight Street | Iowa City | IA | | 9 | Beth Rosebud | 1 First Street | Muscatine | IA | +—–+—————–+———————+———–+——-+

1. Return a list of the unique product id and names that have shipped before with an amount less than 5. Order by product id descending.

Output:

+—–+————————-+ | pid | pname | +—–+————————-+ | 10 | Textbook | | 9 |

Sports Car | | 8 | Table | | 7 | Deluxe Sweet Collection | | 4 | Chocolate Bar | | 3 | Teddy Bear | | 2 | Wooden Chair | | 1 | Swiss Chocolate | +—–+————————-+

1. For each state, return the number of customers in that state and the number of shipments for customers in that state. Hint:

Note: Count customers in a state even if they do not have any shipments.

Output:

+——-+————–+————–+ | state | numCustomers | numShipments | +——-+————–+——

——–+ | BC | 4 | 7 | | CA | 2 | 6 | | IA | 3 | 5 | | AB | 1 | 2 | +——-+————–+————–+

Output:

Chair | 499.95 | +——-+——+————–+———–+

Output:

+—–+—————–+———————-+——————–+——————-+ | pid | pname | numberOfTimesShipped | totalAmountShipped | totalValueShipped | +—–+—————–+———————+——————–+——————-+ | 10 | Textbook | 3 | 6 | 1500.00 | | 2 | Wooden Chair | 6 | 38 |

3799.62 | | 8 | Table | 3 | 38 | 113.62 | | 1 | Swiss Chocolate | 7 | 44 | 1451.56 | +—–+—————–

+———————-+——————–+——————-+

1. Return pairs of customers (only show a pair once) that have been shipped the same product. Return the number of times the pair of customers have been shipped the same product (numShippedProducts). Order by numShippedProducts descending, then first customer name ascending, and second customer name ascending. Note: If product 1 is in two shipments for customer 4 and two shipments for customer 15, that counts as 4 (2 x 2). We are not eliminating any duplicates when counting in this question. Show customer pairs that have 5 or more times that they have been shipped the same product.

Output:

+—–+—————–+—–+—————–+—————-+ | cid | cname | cid | cname |

numSameShipped | +—–+—————–+—–+—————–+—————-+ | 4 | Russell Johnson | 15

| Elish Elias | 7 | | 4 | Russell Johnson | 6 | Scott Charles | 7 | | 2 | Joe Smithsonian | 4 | Russell

Johnson | 6 | | 2 | Joe Smithsonian | 6 | Scott Charles | 5 | | 6 | Scott Charles | 15 | Elish Elias | 5 | +–

—+—————–+—–+—————–+—————-+

1. Return a complete list of all customers (cid, cname), the total number of shipments, and total shipped value (amount*price) that they have been shipped. Return the bottom five customers by total shipped value.

Output:

+—–+—————–+————–+——————-+ | cid | cname | numShipments | totalShippedValue

| +—–+—————–+————–+——————-+ | 1 | Fred Smith | 0 | NULL | | 5 | John Doe |

0 | NULL | | 14 | David Denter | 0 | NULL | | 7 | Robert Dean | 1 | 72.49 | | 3 | Steve Stevenson | 1 | 164.95

| +—–+—————–+————–+——————-+

Output:

+—–+—————–+————–+ | pid | pname | numShipments | +—–+—————–+————-+ | 1 | Swiss Chocolate | 8 | | 2 | Wooden Chair | 8 | | 4 | Chocolate Bar | 6 | | 10 | Textbook | 5 | +—-+—————–+————–+
