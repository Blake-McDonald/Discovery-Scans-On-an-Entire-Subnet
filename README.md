<h1>Tenable: Discovery Scans On an Entire Azure Subnet </h1>

For the purposes of this tutorial we will be leveraging the Tenable Vulnerability Managment Platform as well as the Microsoft Azure Platform. This tutorial assumes you already have a virtual network populated with hosts already provisioned in your environment. 



<summary><strong>Step 1: Login to Tenable and Navigate to the Scans section and click Create Scan </strong></summary>

<br>


<img src="https://i.imgur.com/Hjhs7Eu.png">

<img src="https://i.imgur.com/Zy3ZzVX.png">

<br>

<summary><strong>Step 2: Select Host Discovery from the Select a Scan Template Menu </strong></summary>

<br>



<img src="https://i.imgur.com/zg8GYnE.png">


<br>

<summary><strong>Step 3: Enter your Scan's Title, Description and the Scanner Type as well as the Specific Scanner to be used. In this instance I will be using my Internal Scanner with my Local Scan Engine since my Discovery Scan is intended to only scan within my Virtual Network </strong></summary>

<br>


<img src="https://i.imgur.com/4Ta3lM9.png">

<br>

<summary><strong>Step 4: Navigate to the Microsoft Azure Portal and Navigate to the Virtual Networks page via Search or the Azure Services shortcut list </strong></summary>

<br>


<img src="https://i.imgur.com/GC6WpCd.png">

<br>

<summary><strong>Step 5: Next within the Virtual Networks Overview, select your Virtual Network of Choice </strong></summary>

<br>


<img src="https://i.imgur.com/HGR0Kt1.png">


<br>

<summary><strong>Step 6: After your selection has been made, navigate to the Subnets option on the left hand side under the Settings menu. This will be where your Virtual Networks Subnets are. After picking your subnet of choice copy the desired subnet </strong></summary>

<br>


<img src="https://i.imgur.com/hFYYXTW.png">

<br>

<summary><strong>Step 7: With the copied Subnet value in your Clipboard, Paste said value into the Targets field. This will dictate the network in which the Hosts will be scanned.</strong></summary>

<br>


<img src="https://i.imgur.com/i1iFKFj.png">


<br>

<summary><strong>Step 8: Next navigate to the Discovery Pane on the left hand side and select your Scan Type option. This will allow you to have as wide or granular control as you deem necessary. It is important to note discovery scans with more options enabled will take a longer time to finish scanning. For the purposes of this tutorial we will only be doing a Host Enumeration scan.</strong></summary>

<br>


<img src="https://i.imgur.com/cn7IFZa.png">
<br>

<summary><strong>Step 9: Once your desired settings are selected, Save & Launch the scan. The scan will begin immediately and may take an extended period of time depending on the amount of hosts on the desired subnet.</strong></summary>

<br>


<img src="https://i.imgur.com/lLJg6cQ.png">


<img src="https://i.imgur.com/pteUl55.png">

<br>

<summary><strong>Step 10: After your Scan has completed you can then click the See Details Button on the bottom right of the selected Scan.</strong></summary>

<br>


<img src="https://i.imgur.com/pA4LnHW.png">


<img src="https://i.imgur.com/YHW3fI3.png">

<br>

<summary><strong>Step 11: Within the Details section you can view the different methods taken to scan the hosts and their accompanying vulnerabilities found via the plugins used as well as see the vunlerabilities listed by assets </strong></summary>

<br>


<img src="https://i.imgur.com/ivNqo5R.png">


<img src="https://i.imgur.com/4uFeP8e.png">

<br>


<summary><strong>Step 12: Once finished you may export the results as you please </strong></summary>

<br>


<img src="https://i.imgur.com/gGYKqwT.png">


<img src="https://i.imgur.com/OjA1fOC.png">

<br>
