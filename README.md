# Splunk-Hands-On

<h2>Description</h2>
The Splunk hands-on work activity aimed to learn how to use Splunk SPL [Search Processing language] to extract fields from the ingested data and what we could do with that extracted data. In this hands-on experience, I have performed some searches to know client IP addresses, Items bought by them, failed Logins and many other tasks.
<br />

<h2>Skills Learned</h2>

- How to extract fields from index data and lookup tables.
- How to filter data and use operators.
- How to use transforming commands.
- How to use subsearches and lookups.
- How to extract geolocation information.

<h2>Languages</h2>

- <b>SPl</b> 

<h2>License and Data Source</h2>

- Splunk Free License is used.
- Free Data Source Provided by Splunk education and training.
- "tutorialdata.zip" and "price.csv"

<h2>Hands-On Work:</h2>
<p align="center">
  Simple Splunk Search Query: <br/>
  <p align="left">- The search below will show us data events from sourcetypes which start with “access” and are inside source “tutorialdata” which is inside index named “main”.</p>
<p align="center"><img width="780" alt="Screenshot 2024-03-21 at 4 20 03 pm" src="https://github.com/Chahal-007/Splunk-Hands-On/assets/62164775/92a4a7b4-d0f5-4791-97d1-7163486d91f5" ></p>
<br />
<br />
<p align="center">
  Use of Transforming Commands: <br/>
  <p align="left">-	Transforming commands populate statistic and visualization tab.
-	Here, we are using “top” command with our fields. “action=purchase” this field will filter data events for us.<br/> - It is considered best practice in Splunk to filter as early as possible.<br/>
-	Top command finds most common values in your fields.<br/>
-	In the search, the client-Ip address has purchased more products than others.<br/>
</p>
<p align="center"><img width="777" alt="Screenshot 2024-03-21 at 4 36 17 pm" src="https://github.com/Chahal-007/Splunk-Hands-On/assets/62164775/baac0303-0413-43f7-84ee-7ef7f80bbabb" ></p>
<br />
<br />
<p align="center">
  Stats Commands and Iplocation Command: <br/>
  <p align="left">- Commands searching for items sold in different countries.</p>
<p align="center"><img width="777" alt="Picture 1" src="https://github.com/Chahal-007/Splunk-Hands-On/assets/62164775/3e457170-5113-4469-8801-7c9b57be94d7" ></p>
<br />
<p align="left">- Visualisation of sold Items in Different countries for better insights.</p>
<p align="center"><img width="777" alt="Picture 2" src="https://github.com/Chahal-007/Splunk-Hands-On/assets/62164775/bb838ad3-7dc7-414d-8528-8f2ef33b9e8b"></p>
<br />
<br />
<p align="center">
  Sub searches: <br/>
  <p align="left">-	Sub-searches, providing result of one search to other as an input. <br />
-	Search inside a search is sub-search. 
</p>
<p align="center"><img width="770" alt="Picture 3" src="https://github.com/Chahal-007/Splunk-Hands-On/assets/62164775/adbc9333-2b54-421d-aebd-56fc61f5f491"></p>
<br />
<p align="center"><img width="779" alt="Screenshot 2024-03-21 at 4 43 13 pm" src="https://github.com/Chahal-007/Splunk-Hands-On/assets/62164775/fc6d5c3e-3552-466c-bb8c-41b1caabdb6e"></p>


<br />
<br />
</p>




<!--
<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
-->
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
