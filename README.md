<h1>Kubenertes - Deployments</h1>

<h2>Description</h2>
This assignment will guide you through setting up a Kubernetes deployment and detailing parameters for each property using YAML style.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Kubernetes</b> 
- <b>Command prompt</b>
- <b>Yaml</b>
<h2>Environments Used </h2>

- <b>Windows 11 Pro</b> (21H2)

<h2>Common commands used</h2>

- <b>kubectl create -f</b>
- <b>kubectl apply -f</b>
- <b>vim [name of deployment] (edit)</b>

<h2>Program walk-through:</h2>

<p align="center">
Add the root properties: <br/>
<img src="https://i.imgur.com/oJtGPPP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Define the values for the apiVersion and kind:  <br/>
<img src="https://i.imgur.com/QAblls7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name the deployment frontend, and add the labels, define the app (mywebsite) and tier (frontend): <br/>
<img src="https://i.imgur.com/DzdfBJY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add the sub-root properties for the spec:  <br/>
<img src="https://i.imgur.com/4vOJLrF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Determine how many replicas you would like to run:  <br/>
<img src="https://i.imgur.com/dh598lY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Pull a previous replicaSet and paste it under the template sub-root. Be sure to make sure your spacing is correct:  <br/>
<img src="https://i.imgur.com/pg9vVJ0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add your matchLabels and copy the app from the primary spec:  <br/>
<img src="https://i.imgur.com/TodulDX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
