# DonateBin - DonateBin is an app that efficiently connects donors with non profit organisations.

## Inspiration
The global waste is projected to to increase by 70% by 2050, according to stats provided by the World Bank. Only about 13% of the total waste generated by the world is recycled. A lot of old _clothes_, _furniture items_, _stationary items_ thrown away by us can be _reused_ by others, but they end up in waste bins because we do not like to take the extra effort in looking up and contacting different non profit organisations and waiting for them to collect the items. <br>
Our application **connects donors to non profit organisations**, such that, **donation experience** for the donors is **easy and effortless** and the item **collection** for organisations is **systematic and efficient**.<br>
## What it does
The application has **two interfaces**, one for the donors and one for organisations. <br>The **donor** can sign up and log into their account as a donor. Then they can click a picture of the item they want to donate and proceed to checkout. They can click pictures of multiple items they want to donate before finally checking out. The item description is predicted by a machine learning algorithm in the backend so that the person doesn't have to spend time entering specific details. The item picture, description and the donor location are stored in our database. Now the donor has to wait until an organisation comes and picks up the items at their door step. Thus the donor is free of the hassle of looking up and calling different organisations and enquire about their collection details.<br> The **organisation** can signup or log into the app as an organisation. The app home page has a map, highlighting the locations of donors with different collectible items in whichever area they want to collect from. The organisation can click on any highlighted location and scan through the items available there. Thus the organisation can scan through all the items available in an area and fix a day to collect items they need from every location in that area.<br>
Hence the donors can donate any item in any quantity (without worrying about how less or how much there donation is going to be) and organisations can collect items from entire area in one day without having to make rounds or making different appointment with people.

## How we built it
Our development application is visual studio code.
Stack:<br>
<ul>
<li> Front-End - React Native </li>
<li>Back-End - Flask, PyTorch </li>
<li> Database - MongoDB </li>
</ul>

## Challenges we ran into
<ul>
<li> Data collection of different fashion items was a challenge.</li>
<li> Transfer learning on VGG-16 for fashion items and furniture items was time consuming.</li>
</ul>

## Accomplishments that we're proud of
We are proud to have built an application that contributes towards easy sustainability and reducing waste generation, at the same time creating an opportunity to help someone with a chance to live a better life.
## What we learned
While developing the application, we learnt many new things such as:
<ul>
<li> Integrating a map in an application </li>
<li> Transfer learning on VGG 16. </li>
</ul>

## What's next for DonateBin

We want to set up a verification method for organisations. We also want to set up a rating system for donors and organisations, to ensure good quality items are being donated and donation happens ethically. We want to reduce the size of the machine learning backend so that it can be deployed easily.<br>

<h1 align="center"> Contributors </h1>
<table align="center">
<tr align="center">
<td>
<strong>Breenda Das</strong>
<p align="center">
<img src = "https://cdn.discordapp.com/attachments/857649911759896579/858635368945156116/breenda.jpeg"  height="120" alt="Breenda Das">
</p>
<p align="center">
<a href = "https://github.com/ds-brx"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/breenda-das-68a1891aa/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
<strong>Shubhra Agarwal</strong>
<p align="center">
<img src = "https://cdn.discordapp.com/attachments/852945305280577588/853135575421943858/Untitled_design.png" alt="Shubhra Agarwal" height="120">
</p>
<p align="center">
<a href = "https://github.com/shubhraagarwal"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/agarwalshubhra/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
<strong>Sumrit Grover</strong>
<p align="center">
<img src = "https://cdn.discordapp.com/attachments/852945305280577588/852945815592632360/sumrit_grover.jpg" alt="Sumrit Grover" height="120">
</p>
<p align="center">
<a href = "https://github.com/smgrv123"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/sumrit-grover-1689351aa/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>
</tr>
</table>

