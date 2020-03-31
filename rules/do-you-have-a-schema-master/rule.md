---
type: rule
archivedreason: 
title: Do you have a "Schema Master"?
guid: c40124b5-f5e9-4f6c-8085-e3b91e645379
uri: do-you-have-a-schema-master
created: 2009-10-05T05:51:48.0000000Z
authors:
- id: 1
  title: Adam Cogan
related: []

---

You have a web site master right? This is the central point of contact if the site goes down.
 When developing an application, all members can code. However schema changes being done by many developers often can lead to trouble. 

 Who is "Schema Master"? What does he do?   
<!--endintro-->
<dl class="image">    &lt;dt&gt;<img src="Nick.png" alt=""> &lt;/dt&gt;
    <dd>Figure: One person should be the 'Schema Master', on an average sized project (of 5-10 devs) </dd>
If your project has a database, you need to select a "Schema Master". This is the one person who should review all modifications to the database. These include:

* Creating, Modifying and Deleting tables and columns
* Relationships
* Modify [Controlled Lookup Data](/Pages/DoYouDeployLookupData.aspx)

 The "Schema Master" in a development shop is often the lead programmer on the team. They are in charge of all database changes and scripts. Team members should still feel free to make changes, just get them double checked by the Schema Master.<dl class="image">    &lt;dt&gt;<img src="zsVersionTable.png" alt=""> &lt;/dt&gt;
    <dd>Figure: The Applications Database stores version info in a table called _zsVersion </dd>
    <dd>Figure: Only a "Schema Master" checks in the .sql files </dd>