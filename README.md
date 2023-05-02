Download Link: https://assignmentchef.com/product/solved-cisco-networking-wan-implementation-with-soho-configuration
<br>
You have been recently hired as a network administrator for the xAcme Technology Trade School. The company is realizing that the local systems administrators need help implementing certain technologies at each of the remote locations, as well as final WAN configurations. Out of the network administrators on staff, you have been asked to move forward the project. With your background and skills, you will design, implement, and assist in configurations to support xAcme’s topology. Technologies to implement will differ from site to site, as administrators have begun topology implementations. You will be provided the overall topology as well as certain device configurations in order to determine the best course of action per site/challenge. In addition to helping them configure their network, they require that all new network administrators obtain their CCNA Certification within 60 days of being hired. You are excited about starting this project but realize creating a schedule to help balance your work and home life will be key to success

Below is the requirements for Springfield Site copied from the Network Paper.

Required Implementation: Device hostnames, banners, secured passwords and spanning tree protocol.

<ul>

 <li>

  <ul>

   <li>Device Configurations: Implement device hostnames to match the xACME educational topology labels. Provide a template and sample configuration for the MOTD banner and login banner (wording and implementation) for one of the switches. Keep this generic, as it will be implemented on all switches in the xACME educational topology. Lastly, include the configuration steps for implementing device passwords on both console port (out-of-band communications) and VTY (Telnet/in-band communications). All passwords should be encrypted.</li>

   <li>Spanning Tree Protocol (STP): Briefly explain the advantages and purpose of the STP. Administrators are having a difficult time placing switch 1 as the root. Provide a sample configuration for implementing SPT on the switches. Choose the mode you feel would be best suited for the environment and justify why. Switch 1 will need to be the root switch in the Springfield topology. Consider any security measures that can be implemented to protect the devices from bogus BPDUs.</li>

  </ul></li>

</ul>

<em>Note: When approaching the spanning tree challenge, do not concern yourself with the multiple VLANs at this time. Focus simply on the default VLAN1, which is the active VLAN that all ports belong to in this topology at this time.</em>

Please refer to the following configurations:

<ol>

 <li>SpringfieldSw1</li>

 <li>SpringfieldSw2</li>

 <li>SpringfieldSw3</li>

 <li>SpringfieldSw4</li>

</ol>

Springfield assignment Instruction

<strong>Problem statement:</strong>

In the beginning please give brief descriptions of the project, such as why are you doing, what are the problems, and possible solutions.From the given information, you are required to make a functional network. In Springfield we have a router and four switches connected as daisy chain topology. Then we have output of show commands. It is obvious that it is a non-functional network and you have to implement a solution to make functional.Task in Springfield assignment

<ul>

 <li>

  <ul>

   <li>From the show output commands, you can identify the problems and then provide solution.</li>

   <li>Configure all the tasks as in Springfield assignment as per instructions</li>

   <li>Create Server VLAN, Instructional VLAN, and Administrative VLAN</li>

   <li>Configure Access method of VLANs</li>

   <li>Configure Switch 1 as root bridge</li>

   <li>Configure trunking on all switches</li>

   <li>Configure default gateway</li>

   <li>Create and configure interface VLAN1</li>

  </ul></li>

</ul>

Background information:

Springfield site network is assigned to me to investigate the problems and find the solutions to fix the problem. From the site topology and sh output commands I determined that spanning-tree protocol is misconfigured and it is blocking few ports. And these are the reasons that network is a non-functional.

Implementing Solution:

The following are required information for configuring the networkIP address range 10.30.x.x/16Device to be configured

Configuring commands

<table>

 <tbody>

  <tr>

   <td>Device Names</td>

   <td>Configuration Required</td>

   <td>Configuring command</td>

  </tr>

  <tr>

   <td>Switch#1</td>

   <td>All devicesHost name</td>

   <td>Hostname Switch_Springfield1</td>

  </tr>

  <tr>

   <td>Switch#2</td>

   <td>Host name</td>

   <td>Hostname Switch_Springfield2</td>

  </tr>

  <tr>

   <td>Switch1</td>

   <td>All devicesCreate console password</td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td>Create vty password</td>

   <td></td>

  </tr>

  <tr>

   <td>Only on Switch1</td>

   <td>Create VLANs</td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td>Access vlan</td>

   <td>Interface fa0/0Switchport mode adccessSwitchport access vlan 11</td>

  </tr>

  <tr>

   <td>Switches</td>

   <td>Configure spanning-tree protocol</td>

   <td>Spanning-tree RPVST</td>

  </tr>

  <tr>

   <td>Switch1</td>

   <td>Make Switch 1 as root bridge of network</td>

   <td></td>

  </tr>

 </tbody>

</table>

Configurations

Under this heading, write details of configurations