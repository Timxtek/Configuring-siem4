<p align="center">
<img src="https://i.imgur.com/JWXNvVN.png" height="75%" width="100%"alt="SIEM logo"/>
</p>

<h1>Configuring a SIEM in MS Azure</h1>
This tutorial outlines the setup and use of a Security Operations Center (SOC) & the deployment of a SIEM in MS Azure.<br />


<h2>Configuration Steps</h2>

<h3 align="center">Configure Virtual Machine</h3>
<br />
<p>
  Virtual Machines- preset configuration- create.
</p>

<p>
  <img src="https://i.imgur.com/KigsoyB.png" height="75%" width="100%" alt="Preset 1"/>
  <img src="https://i.imgur.com/KOVvYJ3.png" height="75%" width="100%" alt="Preset 2"/>
  <img src="https://i.imgur.com/PECekYI.png" height="75%" width="100%" alt="Preset 3"/>
  <p>
    <h3 align="center">MS Sentinel</h3>
  </p>
  <p> MS Sentinel- create a workspace- create.
  </p>
  <img src="https://i.imgur.com/1LNwfRm.png" height="75%" width="100%" alt="Preset 4"/>
  <img src="https://i.imgur.com/sHbu7ZG.png" height="75%" width="100%" alt="Preset 5"/>
  <img src="https://i.imgur.com/UKSpc5l.png" height="75%" width="100%" alt="Preset 6"/>
  <p>
    After creation, add the sentinel to a workspace.
  </p>
  <img src="https://i.imgur.com/RaaSYKD.png" height="75%" width="100%" alt="Preset 7"/>
  <p>
    Navigate back to the "Microsoft Sentinel" tab. Open configuration- Data connectors- content hub.
  </p>
  <img src="https://i.imgur.com/Qiq8sl5.png" height="75%" width="100%" alt="Preset 10"/>
  <p>
    Search and install "Windows Security Events"
  </p>
  <img src="https://i.imgur.com/rt6SYNX.png" height="75%" width="100%" alt="Preset 11"/>
  <p> After installation, select "Windows Security Events via AMA"- open connector page. 
  </p>
  <img src="https://i.imgur.com/Zkuzgc1.png" height="75%" width="100%" alt="Preset 12"/>
  <img src="https://i.imgur.com/dI7xi8D.png" height="75%" width="100%" alt="Preset 13"/>
  <p>
    Create a data collection rule
  </p>
  <img src="https://i.imgur.com/x8M9f9e.png" height="75%" width="100%" alt="Preset 14"/>
  <img src="https://i.imgur.com/hAsFxAR.png" height="75%" width="100%" alt="Preset 15"/>
  <img src="https://i.imgur.com/8xPiLVp.png" height="75%" width="100%" alt="Preset 16"/>
  <img src="https://i.imgur.com/8lcox2x.png" height="75%" width="100%" alt="Preset 17"/>
  <p>
    Create a Sentinel rule<br>Navigate to MS Sentinel- logs- input and run security event code @ last 3 days</br>Select add new alert rule -create MS Sentinel alert
  </p>
  <img src="https://i.imgur.com/eY6CAaa.png" height="75%" width="100%" alt="Preset 18"/>
  <img src="https://i.imgur.com/LXxXmAV.png" height="75%" width="100%" alt="Preset 19"/>
  <img src="https://i.imgur.com/UyyfFX7.png" height="75%" width="100%" alt="Preset 20"/>
  <p>
    After rule creation, log in & out of VM for SIEM monitoring<br>Navigate to MS Sentinel- incidents.</br>
  </p>
  <img src="https://i.imgur.com/Rr3TX5T.png" height="75%" width="100%" alt="Preset 21"/>
  <p>Select overview- Finished!</p>
  <img src="https://i.imgur.com/ekablQT.png" height="75%" width="100%" alt="Preset 22"/>
  
</p>
