---
permalink: /
title: "Xiaoyue Ma"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Ph.D. at the Department of Computer Science, [George Mason University (GMU)](https://www.gmu.edu/). Prior to joining George Mason, I earned the Bachelor degree in Computer Science in 2017 from Northeastern University in Shenyang, China, and obtained the Master degree from the University of Melbourne, Australia, in 2020.

My research mainly focuses on IoT Attacks and Defenses.

<!-- I also maintain a deadline countdown website for conferences related to software analysis, security & privacy, and AI: [Cybersecurity-Lab-GMU DDL Countdowns](https://cybersecurity-lab-gmu.github.io/).  
Contributions through pull requests or merge requests are welcome!! -->
 <!-- My reserch interests include IoT vulnerability analysis, mobile computing and software engineering. -->

News
======
* (08/2025)**[Paper]** Our Security’25 paper, which presents a terrifying attack that turns a device into an “AirTag” for tracking, has received the [USENIX Security Distinguished Artifact Paper Award](../assets/sec25_distinguished_artifact-chen.pdf). Only 6 out of 407 papers received this prestigious recognition!
* (06/2025)**[Paper]** Our paper has been accepted by MobiCom 2025! Congratulations to all the authors!
* (06/2025)**[News]** Our Demo Accepted at DEF CON 33!
DEF CON is one of the world’s largest and most influential hacker conferences. Our team will present at the Demo Labs, where [Junming](https://www.linkedin.com/in/junming-c/) will share our latest research and innovations with the security community.

<style>
.more-news {
    display: none;
}
.toggle-btn {
    background: none;
    border: none;
    color: #0066cc;
    cursor: pointer;
    font-size: 16px;
    padding: 0;
    text-decoration: underline;
}
</style>
<div id="more-news" class="more-news">
<ul>
<li>(01/2025)<strong>[Paper]</strong> We introduce a terrifying attack that can turn your computer into an "AirTag" to track you. Apple has patched this bug! Accepted to USENIX Security'25!</li>
<li>(12/2024)<strong>[Service]</strong> I will serve as a member of Artifact Evaluation Committee for Usenix Security 2025!</li>
<li>(11/2024)<strong>[Award]</strong> I received the Student Travel Grant from George Mason University!</li>
<li>(07/2024)<strong>[Award]</strong> I received the Student Travel Grant from Usenix Security!</li>
<li>(05/2024)<strong>[Paper]</strong> Our tool that discovered over 60 zero-day vulnerabilities is accepted to <a href="https://www.usenix.org/conference/usenixsecurity24">USENIX Security'24</a>.</li>
<li>(04/2024)<strong>[Service]</strong> I will serve as a member of the Local Organization Team for the Information Security Conference <a href="https://isc24.cs.gmu.edu">(ISC)</a>, which will be held in Virginia, USA, in October 2024. We welcome the submission of your best work! Check the <a href="https://isc24.cs.gmu.edu/docs/call-for-papers/">Call for Papers (CFP)</a> here!</li>
<li>(02/2023)<strong>[Paper]</strong> Our IoT fuzzing work that found over twenty zero-day vulnerabilities (six CVEs assigned) will be presented at <a href="https://www.sigmobile.org/mobisys/2023/">MobiSys'23</a>.</li>
</ul>
</div>
<button class="toggle-btn" onclick="(function(){
 var newsDiv = document.getElementById('more-news');
 var btn = event.target;
 if (newsDiv.style.display === 'none' || newsDiv.style.display === '') {
     newsDiv.style.display = 'block';
     btn.innerHTML = '▲ Less...';
 } else {
     newsDiv.style.display = 'none';
     btn.innerHTML = '▼ More...';
 }
})()">
▼ More...
</button>

Publications
======
* **LLM-Assisted IoT Testing:** *Finding Conformance Bugs in Matter SDKs*
  **Xiaoyue Ma**, Junming Chen, Lannan Luo, Qiang Zeng. \>\>[PDF](https://onedrive.live.com/?redeem=aHR0cHM6Ly8xZHJ2Lm1zL2YvYy9mY2VjN2NjNTNmY2ZjYzk0L0V0UkplWmtDdHB4TXJrME03R08zdFkwQnFpZl9HOXFKUjNzbmNydU95S2NLV2c_ZT1yN3FXZFg&cid=FCEC7CC53FCFCC94&id=FCEC7CC53FCFCC94%21sa739e76028ae467791b574fb3a1ba54a&parId=FCEC7CC53FCFCC94%21s997949d4b6024c9cae4d0cec63b7b58d&o=OneUp&v=validatepermission)

*MobiCom'25*, Hong Kong, China, Nov. 2025 


* **From One Thousand Pages of Specification to Unveiling Hidden Bugs:** *Large Language Model Assisted Fuzzing of Matter IoT Devices*  \>\>[PDF](../assets/Matter-Fuzzing.pdf)  
  **Xiaoyue Ma**, Lannan Luo, Qiang Zeng.    
*Security'24*, Philadelphia, USA, Aug. 2024 

This work has discovered over 60 vulnerabilites and 3 CVEs have been assigned: <span style="color: red;">CVE-2023-42189,CVE-2023-45955,CVE-2023-45956</span>.

* **No More Companion Apps Hacking but One Dongle:** *Hub-Based Blackbox Fuzzing of IoT Firmware*  \>\>[PDF](../assets/IoT-Fuzzing.pdf)  
  **Xiaoyue Ma**, Qiang Zeng, Haotian Chi, Lannan Luo  
*MobiSys'23*, Helsinki, Finland, June. 2023    
  
This work has discovered over twenty zero-day vulnerabilities and 6 CVEs have been assigned: <span style="color: red;">CVE-2023-24678, CVE-2022-47100, CVE-2023-29780, CVE-2023-29779, CVE-2023-34596, CVE-2023-34597</span>.  
<span style="color: blue;">Artifact Review and Badging:</span> Artifacts Evaluated – Functional v1.1 and Artifacts Evaluated – Reusable v1.1

*  **Tracking You from a Thousand Miles Away!** Turning a Bluetooth Device into an Apple AirTag Without Root Privileges  
   Junming Chen, **Xiaoyue Ma**, Lannan Luo, Qiang Zeng  
   *Security'25*, Seattle, USA, Aug. 2025

  We introduce a [terrifying attack](https://nroottag.github.io/) that can turn your computer into an "AirTag" to track you.  
> 📣 **The vulnerability and attack have been acknowledged by Apple and featured in**  
> [Dailymail](https://www.dailymail.co.uk/sciencetech/article-14470803/Frightening-flaw-iPhone-app-thats-downloaded-default-national-security-threat.html) |
> [Forbes](https://www.forbes.com/sites/davidphelan/2025/03/03/apple-iphone-find-my-critical-alert-issued-to-all-users-in-expert-warning/) |
> [TechRadar](https://www.techradar.com/phones/phone-accessories/this-find-my-exploit-lets-hackers-track-any-bluetooth-device-heres-how-you-can-stay-safe) |
> [ACM TechNews](https://technews.acm.org/archives.cfm?fo=2025-03-mar/mar-05-2025.html) |
> [Indian Express](https://indianexpress.com/article/technology/tech-news-technology/apple-find-my-network-security-flaw-track-bluetooth-devices-9861714/) |
> [MoneyControl](https://www.moneycontrol.com/technology/apple-s-find-my-network-exploit-enables-silent-tracking-from-any-bluetooth-device-article-12953351.html) |
> [Heise (DE)](https://www.heise.de/news/Sicherheitsforscher-nutzen-Apples-Wo-ist-um-alle-Bluetooth-Geraete-zu-tracken-10299195.html) |
> [CHIP (DE)](https://www.chip.de/nachrichten/apple,79701/gefahr-fuer-iphones-und-co-forscher-entdecken-sicherheitsluecke-in-apple-system_ce80b936-83db-49f5-aaf9-ca4144e467ee.html)



<!-- Awards/Honors
======
* Student Travel Grant, Usenix Security,2024
* Summer Research award, George Mason University, 2023.
* Engineering Scholarship, University of South Carolina, 2022.
* Higher Education Emergency Relief Fund Grant, University of South Carolina, 2021.
* Engineering Exchange Scholarship, The University of Melbourne, 2019.
* Excellent Student, Northeastern University, 2016-2017. -->

# Academic Service 
## Technical Program Committee
* **Security'26 AE**: Usenix Security artifacts evaluation, 2026
* **Security'25 AE**: Usenix Security artifacts evaluation, 2025
* **VTC'25**: IEEE Vehicular Technology Conference

## Reviewer of Refereed Conferences
* **VTC'23, 24**: IEEE Vehicular Technology Conference
* **ICCC'23, 24**: IEEE/CIC International Conference on Communications in China
* **GLOBECOM'23,24**: IEEE Global Communications Conference
* **ICCT'23, 24**: IEEE International Conference on Communication Technology
* **PIMRC'23, 24**: IEEE International Symposium on Personal, Indoor and Mobile Radio Communications 
* **INFOCOM Workshop'23, 24**: IEEE International Conference on Computer Communications Workshop

## Reviewer of Refereed Journals
* IEEE Transactions on Mobile Computing
* IEEE Transactions on Networking
* IEEE Internet of Things Journal
* IEEE Transactions on Vehicular Technology
* IEEE Communications Magazine
* ACM Transactions on Computing Education
* Journal of Computer Security
* Springer Peer-to-Peer Networking and Applications

Teaching Experience
======
* Spring 2023, *CS468, Secure Programming and Systems*, Teaching Assistant.


