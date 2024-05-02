<h1>Python Automation for File Updates</h1>

<h2>Project Description</h2>
In this scenario, I developed a Python algorithm to automate the process of updating a file containing IP addresses allowed to access restricted content in a company. The algorithm checks whether any IP addresses from a remove list need to be removed from the allow list and updates the file accordingly.
<br />


<h2>Steps taken</h2>

<p align="center">
Open the file that contains the allow list: <br/>
<img src="https://imgur.com/lbjyToN.png" />
<br />
<br />
Read the file contents:  <br/>
<img src="https://imgur.com/EP75nPS.png" />
<br />
<br />
Convert the string into a list:  <br/>
<img src="https://imgur.com/2M0xv3A.png" />
<br />
<br />
Iterate through the remove list:  <br/>
<img src="https://imgur.com/Hqyg0Vh.png" />
<br />
<br />
Remove IP addresses that are on the remove list:  <br/>
<img src="https://imgur.com/vfPwnWj.png" />
<br />
<br />
Update the file with the revised list of IP addresses:  <br/>
<img src="https://imgur.com/ZwSB5da.png" />


<h3>Summary</h3>
The algorithm starts by opening the file containing the allow list, reads its contents, and converts them into a list of IP addresses. It then iterates through the remove list, removing any IP addresses found in both lists. Finally, it updates the file with the revised list of IP addresses. This algorithm ensures that only authorized IP addresses have access to restricted content, enhancing the security of the healthcare company's systems.
