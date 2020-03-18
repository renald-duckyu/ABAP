<h1>ABAP</h1>
ABAP is the programing language for SAP systems.

It is stands for "Allgemeiner Berichtsaufbereitungsprozessor"

Today, ABAP stands for "Advanced Business Application Programming."

More Information:<a href="https://blogs.sap.com/2020/02/26/do-you-know-abap-as-a-programing-language/">https://blogs.sap.com/2020/02/26/do-you-know-abap-as-a-programing-language/</a>

&nbsp;
<h2>Classic ABAP &amp; Modern ABAP</h2>
Originally, ABAP is procedural language,after it became object-oriented language.

People often calls former as "Classic ABAP", and later as "Modern ABAP".

&nbsp;
<h3>Classic ABAP</h3>
Classic ABAP is involved in Modern ABAP.

When you hear Classic ABAP, many people associate "Report Program".

There are three types of report programs, and a typical one is an "executable program" for selecting and displaying information on a selection screen.

The program has following event;

INITIALIZATION : refreshing parameter etc.
START-OF-SELECTION: defining selection screen view or behavior etc.
GET node (obsolete, for logical databases only) : SQL logics etc

Nomaly,Output Process (Showing result for SQL Query,Tables,calculation etc ) is executed after those processes.

&nbsp;
<h3>Modern ABAP</h3>
ABAP latest version is NW 7.5 which is a kind of ABAP for HANA.

More Information : <a href="https://blogs.sap.com/2015/11/27/abap-language-news-for-release-750/">https://blogs.sap.com/2015/11/27/abap-language-news-for-release-750/</a>

Help Portal          : <a href="https://help.sap.com/viewer/product/SAP_NETWEAVER_750/7.5.17/en-US">https://help.sap.com/viewer/product/SAP_NETWEAVER_750/7.5.17/en-US</a>

Section : <a href="https://help.sap.com/viewer/7bfe8cdcfbb040dcb6702dada8c3e2f0/7.5.17/en-US/435639792fc95f6ce10000000a1553f6.html">ABAP Programming Language</a>

cf.) Help Portal for 7.4 : <a href="https://help.sap.com/doc/abapdocu_740_index_htm/7.40/en-US/index.htm">https://help.sap.com/doc/abapdocu_740_index_htm/7.40/en-US/index.htm</a>

&nbsp;
<h2>ABAP Program Types</h2>
(Quote from <a href="https://help.sap.com/doc/abapdocu_740_index_htm/7.40/en-US/index.htm">https://help.sap.com/doc/abapdocu_740_index_htm/7.40/en-US/index.htm</a>  ABAP Keyword Documentation → ABAP - Reference → Program structure → ABAP Program Types)

Executable program : Statement SUBMIT or a dynpro or selection screen is called using a transaction code

Class pool : Call of a visible method or a call using a transaction code

Function group or function pool : A function module is called using CALL FUNCTION or a dynpro is called using a transaction code

Interface pool : A global interface from the class library

Module pool : A dynpro is called using a transaction code

Subroutine pool : External call of local procedures (subroutines or methods)

Type group or type pool : Statements TYPES and CONSTANTS

&nbsp;
<h2><a href="https://help.sap.com/viewer/cfae740a0a21455dbe6e510c2d86e36a/7.3.18/en-US/fceb2ed0358411d1829f0000e829fbfe.html">ABAP Syntax</a></h2>
ABAP statements contains Keyword,Additions,Operands,and period in one sentence.

Keyword decides the behavior,and Additions provides an additional explanation,and Operands is affection target or condition of the behavior.

&nbsp;

Syntax also have Open SQL(or ABAP SQL). It is SQL statements that do not depend on database-specific SQL.

Reference:<a href="https://help.sap.com/doc/abapdocu_750_index_htm/7.50/en-US/abennews-750-open_sql.htm">https://help.sap.com/doc/abapdocu_750_index_htm/7.50/en-US/abennews-750-open_sql.htm</a>

&nbsp;
<h2>Elements in ABAP</h2>
Reference : <a href="https://help.sap.com/doc/abapdocu_750_index_htm/7.50/en-US/abenddic_classical_objects.htm">https://help.sap.com/doc/abapdocu_750_index_htm/7.50/en-US/abenddic_classical_objects.htm</a>
<h3>Data types</h3>
<ul>
 	<li>Data elements：variable or value</li>
 	<li>Structures：conbination of Data elements</li>
 	<li>Table types : repeated aggregation of Structures</li>
</ul>
<h2>Database tables</h2>
pre-defined or user-defined table
<h2>Views</h2>
it is possible to change the way the table results are displayed as they are.
<h2>Lock objects</h2>
A lock object is used as a basis for SAP locks.
<h2>Search helps</h2>
A search help uses a combination of structure components, data elements, and check tables plus assigned data to find values without the user needing to enter the exact value in question.

&nbsp;

<em>I expect to update this document accordingly as new information and fixes are available. </em>

Thanks,RenaTakahashi
