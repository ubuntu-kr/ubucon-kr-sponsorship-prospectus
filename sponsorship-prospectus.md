---
marp: true
title: UbuCon Korea 2025 Sponsorship prospectus
theme: ubucon
paginate: true
---
<script src="https://unpkg.com/mermaid/dist/mermaid.min.js"></script>
<script>
  // Replaces <pre class="mermaid"> blocks with <img> blocks, to make mermaid render properly.
  // Preserves classes and styling so they can be used to fix sizing if necessary.

  mermaid.initialize({ startOnLoad: false });

  window.addEventListener('load', async function () {
    const mermaidEls = document.querySelectorAll('pre.mermaid');

    for (const el of mermaidEls) {
      const { svg } = await mermaid.render('asd', el.textContent);

      const img = document.createElement('img');
      img.setAttribute('src', `data:image/svg+xml;base64,${btoa(svg)}`);
      img.setAttribute('class', el.getAttribute('class'));
      img.setAttribute('style', el.getAttribute('style') || '');

      el.parentNode.replaceChild(img, el);
    }
  });
</script>

<style scoped>
    section {
        background-image: url(https://assets.ubuntu.com/v1/ed94a429-0000_suru-corner-fan--top-right-light.jpg);
        background-position: top right;
        background-size: 20rem 15rem;
        align-content: end;
        font-size: 40px;
    }
    h1 {
        font-size: 60px;
    }
</style>

![w:200](./assets/logo.svg)
# UbuCon Korea 2025
August 9
Microsoft Korea (13F)
Seoul, South Korea
**Sponsorship prospectus**

<img src="./assets/uck24opening.JPG" style="margin-left: -40px; margin-bottom: -50px; width: 210mm; height: 300px; object-fit: cover;">

<!-- _paginate: skip -->

---

<!-- header: ![w:50](./assets/logo.svg) -->
<!-- footer: https://2025.ubuntu-kr.org | sponsorship@ubuntu-kr.org -->

<img src="./assets/group_photo.jpg" style="margin-left: -40px; margin-top: -40px;  width: 210mm; height: 300px; object-fit: cover;">

# About Ubuntu & UbuCon Korea

**Ubuntu**, co-developed by the Ubuntu Community with people from worldwide and Canonical, stands as the world's leading open-source Linux-based operating system. While Ubuntu started as an easy-to-use Linux desktop 20 years ago, today, with its mission to bring free software to the widest audience while accelerating innovation and underpinning operations, Ubuntu powers millions of devices from personal computers to cloud infrastructure, serving as the foundation for technological advancement in AI, cloud computing, IoT, and enterprise solutions.

Today, there are **two major annual events** that bring together people from the global Ubuntu community to share various projects and practices in the Ubuntu ecosystem: **UbuCon**(s) across different regions and the **Ubuntu Summit.**

The main difference between the two events is that Canonical, the creator of Ubuntu, is largely involved with organizing the Ubuntu Summit, while UbuCon is a community-driven event that is **solely organized by the community.** These UbuCons are held in **different regions within a continent or country,** and today there are UbuCon NA @ SCaLE, UbuCon Europe, UbuCon Latin America, UbuCon Portugal, and UbuCon Asia.

**UbuCon Korea** is the largest domestic Ubuntu community event of the year, bringing together contributors and users of Ubuntu projects in Korea, and was started as a spin-off of UbuCon Asia 2022, which was the first in-person event in Seoul. UbuCon Korea 2023 was successfully held last year on September 9 at Microsoft Korea with 151 attendees, with the theme of "Ubuntu for Developer Productivity". Following the success of last year's event, UbuCon Korea 2024 will be held on August 10 at the same venue as last year's event, with a variety of programs organized around the theme of "Deploy with Ubuntu"!


## Event overview

- **Name:** UbuCon Korea 2025
- **Theme:** Deploy with Ubuntu
- **Date:** August 9th, 2025 
- **Venue:** Microsoft Korea (The K Twin Tower - Building A 13F)
- **Scale:** 150+ participants (Including speakers and staff)
- **Host:** Ubuntu Korea Community
- **Tickets**
  - Standard (Paid)
  - Individual patron/business (Paid)


---

# About Ubuntu Korea Community

## About the community
Started in 2005, the Ubuntu Korea Community is a place for Korean Ubuntu users and contributors, and is also an official Ubuntu local community verified by the Ubuntu Local Community Council. To expand the popularity of Ubuntu and related open sources in Korea, the community operates forums for Ubuntu-related Q&A, translates various Ubuntu packages into Korean, runs a Korean Ubuntu wiki, and works on documentation. We also hold various offline events such as general meetings, regular seminars, workshops, group study activities, and UbuCon for offline exchanges among community members.

## Activities to expand Ubuntu adoption and improve usability
Our online forum, which has been with the community since its beginning, is still live and has recently been revamped with Discourse to make it more user-friendly. Multilingual support for the various packages available in Ubuntu is maintained by local communities in each country. Our community also has a translation team, which continues to contribute to Korean support for Ubuntu. When necessary, we translate documents of interest to many people, such as Ubuntu release notes, into Korean, making it easier for people who are not familiar with English to access information about Ubuntu.

## Host a variety of in-person events
In addition to online-based activities such as running online forums and contributing to Ubuntu projects. We periodically organize offline events for community members to meet and interact. These events include regular general meetings (within three months after closing finances each year), regular seminars, hands-on workshop events, group study activities, and the annual UbuCon, a large-scale event that brings together Ubuntu users and contributors from various fields.

## Engaging with international communities
We continue to interact with various overseas Ubuntu and open source communities, including Ubuntu Japan, Ubuntu Taiwan, Ubuntu Malaysia, Ubuntu Indonesia, Debian Japan, FOSS Nepal, Ubuntu India and FOSSASIA, and we also participate in UbuCon Asia, the premier event for Ubuntu community exchange in Asia, where we share our activities with each community.


<div style="display: flex; flex-direction: row; margin-left: -40px; width: 210mm; height: 180px; ">
  <img src="./assets/forum.png" style="flex: 1">
  <img src="./assets/l10n.jpg" style="flex: 1">
  <img src="./assets/uck24hallway.jpg" style="flex: 1">
</div>


---
# The venue & Proposed timetable

<div style="display: flex; flex-direction: row; margin-left: -40px; width: 210mm; height: 160px; ">
  <img src="./assets/venue1.jpg" style="flex: 1">
  <img src="./assets/venue2.jpg" style="flex: 1">
  <img src="./assets/venue3.jpg" style="flex: 1">
</div>

## The venue
**Microsoft Korea (The K Twin Tower - Building A 13F)**

Microsoft Korea is located on the 13th floor of Building A of The K Twin Tower, near Gwanghwamun Station. It has a conference room with a total capacity of 110 people, a registration desk, and a lounge area that can be used for networking, booths, and catering. The conference room has automatic partitions, so it can be used as a single room for the keynote, and then partitioned off to run the talks and workshop programs simultaneously.

## Proposed timetable

| Jeju Hall | Donghae Hall | Dokdo Hall |
| --- | --- | --- |
| **10:00** Opening (30min) | | |
| **10:30** Keynote (30min) | | |
| **11:00** Talk (30min) | **11:00** Workshop (90min) | **11:00** Talk (30min) |
| **11:30** Talk (20min + 10min break) | | **11:30** Talk (20min + 10min break) |
| **11:00** Talk (30min) | | **11:00** Talk (30min) |
| **12:30** Lunch break (60min) | | |
| **13:30** Talk (30min) | **13:30** Workshop (90min) | **13:30** BoF (40min +10min break) |
| **14:00** Talk (20min + 10min break) | | |
| **14:30** Talk (30min) | | **14:20** BoF (40min) |
| **15:00** Afternoon break (20min) | | |
| **15:20** Talk (30min) | **15:20** Workshop (90min) | **15:20** BoF (40min + 10min break) |
| **15:50** Talk (20min + 10min break) | | |
| **16:20** Talk (30min) | | **16:10** BoF (40min) |
| **16:50** Lightning talks (20min) | | |
| **17:10** Closing (10min) | | |
---

# Who attends UbuCon Korea
<div style="display: flex; flex-direction: row;">
  <div style="flex: 1; padding: 10px;">
  <p><b>Software Engineers</b><br/>Web (Frontend, Backend), Embedded & IoT, OS & System & Kernel, Desktop Applications, Robotics</p>
  <p><b>Academic & Other</b><br/>Students (Mostly IT related majors), Professors, Researchers, Sales Manager, Enterprisers</p>
  </div>
  <div style="flex: 1; padding: 10px;">
  <p><b>IT Infra & Operations</b><br/>Cloud Engineer, DevOps, SRE, Solutions Architect, Support Engineer, SysAdmin</p>
  <p><b>Data & AI</b><br/>Data Engineers, Data Scientists, AI/ML Engineers, Data Analysts</p>
  <p><b>Community & Marketing</b><br/>Community Managers, Developer Relations, Marketing Managers</p>
  </div>
</div>

## Highlights from last year
<div style="display: flex; flex-direction: row;">
  <p  style="flex: 1"><b>173</b><br>Registrations</p>
  <p  style="flex: 1"><b>151</b><br>Attendees</p>
  <p  style="flex: 1"><b>18</b><br>Sessions</p>
  <p  style="flex: 1"><b>~76%</b><br>First time<br>attendee</p>
  <p  style="flex: 1"><b>50%+</b><br>2 Years+<br>career</p>
  <p  style="flex: 1"><b>60%+</b><br>IT related<br>profession</p>
</div>
<pre class="mermaid mermaid-100h">
%%{init: {'theme': 'base', 'themeVariables': { 'pieLegendTextSize': '11px', 'fontFamily': 'Ubuntu'}}}%%
pie showData
title Participants by profession (2024)
    "Software Engineer(Web Backend)" : 20
    "Software Engineer(Web Frontend)" : 8
    "Software Engineer(Embedded & IoT)" : 4
    "Software Engineer(OS, System & Kernel)" : 5
    "Software Engineer(Desktop Application)" : 7
    "Software Engineer(Robotics)" : 10
    "Cloud Engineer": 19
    "DevOps Engineer": 9 
    "SRE": 4
    "Support Engineer": 2
    "Solutions Architect": 3
    "AI/ML Engineer": 3
    "Researcher (Institute)": 2
    "Researcher (Enterprise)": 4
    "Students (IT majors)": 33
    "Students (Other majors)": 6
    "Teenagers": 5
    "Education": 4
    "Community Manager": 4
    "Marketing Manager": 7
    "Officials": 5
    "Enterprisers": 2
    "Etc": 7


</pre>

---
# What sponsorship means and its benefits
## Become a sponsor
As a non-profit event, UbuCon Korea is organized by a volunteer organizing committee without financial compensation and relies on sponsorships and individual patrons to make the event happen.

Through this event, we hope to bring together a wide range of people, including those who are interested in Ubuntu, those who use it in the field, and those who contribute to the project, as well as collaborate with other open source communities to strengthen our network and reach a wider audience. Securing sufficient funding is crucial to achieving this goal.

By joining the event as a sponsor, you'll not only help us achieve our goals, but you'll also show your sincere support for the Ubuntu community. With our sponsorship packages, you'll be able to enhance your branding, promote your company or service to our audience, and engage with attendees to potentially recruit new developers or engineers.

## Why sponsor
<div style="display: flex; flex-direction: row;">
  <div style="flex: 1; padding-right: 10px;">
  <p>
    <img src="./assets/icons/target.svg" style="height: 40px"/><br/>
    <b>Targeted audience</b><br/>
    A good opportunity to boost leads through targeted marketing with most of our audience from tech industry.
  </p>
  <p>
    <img src="./assets/icons/talent.svg" style="height: 40px"/><br/>
    <b>Talent acquisition</b><br/>
    Recruit the brightest minds in the industry to fill your open positions.
    60%+ of our attendees last year were with IT related professions.
  </p>
  <p>
    <img src="./assets/icons/bullhorn.svg" style="height: 40px"/><br/>
    <b>Empower your branding</b><br/>
    Your logo will be exposed on banners, websites, videos as well as our media coverages.
  </p>
  </div>
  <div style="flex: 1; padding: 10px;">
  <p>
    <img src="./assets/icons/present.svg" style="height: 40px"/><br/>
    <b>Showcase products and services</b><br/>
    Showcase your innovative products and service face-to-face with your potential and existing customers and receive valuable feedback. 
  </p>
  <p>
    <img src="./assets/icons/speak.svg" style="height: 40px"/><br/>
    <b>Establish thought leadership</b><br/>
    Showcase your expertise on Ubuntu and its ecosystem and educate the community about your organization’s products, services and open source strategies.
  </p>
  <p>
    <img src="./assets/icons/opensource.svg" style="height: 40px"/><br/>
    <b>Support Open source and Community</b><br/>
    Sponsoring our event is one of the best ways to show your sincere and support to open source and community.
  </p>
  </div>
</div>

---

# Past sponsors
<div class="imgrow">
  <img src="./assets/sponsor_logos/canonical.svg">
  <img src="./assets/sponsor_logos/onlyoffice.svg">
  <img src="./assets/sponsor_logos/ahnlabcloudmate.svg">
</div>
<div class="imgrow">
  <img src="./assets/sponsor_logos/naver_cloud.png">
  <img src="./assets/sponsor_logos/microsoft.png">
  <img src="./assets/sponsor_logos/invesume.png">
</div>
<div class="imgrow">
  <img src="./assets/sponsor_logos/whatap.png">
  <img src="./assets/sponsor_logos/nhncloud.png">
  <img src="./assets/sponsor_logos/eventus.svg">
</div>
<div class="imgrow">
  <img src="./assets/sponsor_logos/grometric.svg">
  <img src="./assets/sponsor_logos/OSCKorea.svg">
  <img src="./assets/sponsor_logos/hanbit.svg">
</div>
<div class="imgrow">
  <img src="./assets/sponsor_logos/inflearn.svg">
  <img src="./assets/sponsor_logos/elastic.svg">
</div>

**More than half** of our past sponsors have already sponsored our event **twice or more.**


---

# Sponsorship packages

| **Package** | Diamond | Gold | Silver | Bronze | Supporter  |
| --- | --- | --- | --- | --- | --- |
| **Slots** | 1 | 1 | 2 | 4 | ∞ |
| Price(KRW)<sup>*0</sup> | 6,000,000 | 3,000,000 | 1,600,000 | 800,000 | 500,000 |
| Price(USD) | 4,592  | 2,296 | 1,224  | 612 | 382 |
| **Logo exposures** |  |  |  |  |  |
| Basic | O | O | O | O | O |
| Recordings & Stage(or Podium) | O | O | X | X | X |
| Badges & Swags | O | O | X | X | X |
| **Tickets**  | Free 5 tickets | Free 4 tickets | Free 3 tickets | Free 2 tickets | 10% off for 5 tickets |
| **Sponsored session**<sup>*1</sup> | Keynote & 1 Session<sup>*2</sup> |1 Session<sup>*3</sup> | Lightning talk (5min) | X | X |
| **Sponsor booth** | 1.8m width | 1.8m width | 1.8m width<sup>*4</sup> | X | X |
| **Marketing** |  |  |  |  |  |
| Basic | O | O | O | O | O |
| Marketing (Email) | Name+URL+Logo | Name+URL+Logo | Name+URL | Name+URL | Mention name only |
| Marketing (Engagement) | O | O | O | O | X |
| **Swag giveaway** | O | O | O | O | O |

**Footnotes**
- *0: VAT 10% is not included in this price.
- *1: Sponsored sessions are also subject to Code of Conduct compliance and content team review, with no exceptions, and must be related to Ubuntu or related open source technologies. In addition, blatant marketing and sales pitches are prohibited. 
- *2: Choose between a Workshop, a Talk and a BoF Session.
- *3: Choose between a Talk and a BoF Session.
- *4: 1 slot available, and served as an Add-on with 200,000 KRW fee. (Approx 153 USD, VAT not included) First come first serve.

---
# Sponsorship package details

## Logo exposure
- **Basic:** Your logo will be exposed on our website, a large photo wall that will be installed on the lounge, and intro part of each session recordings.
- **Recordings & Stage(or Podium):** Your logo will be also exposed on banner areas of each session recordings, and banners inside the conference room which will be installed next to the stage.
- **Badges & Swags:** Your logo will be also exposed on badges and swags (such as T-shirts) that all participants will get. Badges are the most frequent and effective way to expose your logo, as they are worn by participants at all times during the event, and swags allow for logo exposure even after the event.

<div style="display: flex; flex-direction: row; margin-left: -40px; width: 210mm; height: 180px; ">
  <img src="./assets/photowall.jpg" style="flex: 0.9">
  <img src="./assets/booth.jpg" style="flex: 0.9">
  <img src="./assets/sponsored_session.jpg" style="flex: 1.2">
</div>

## Tickets
As a token of our appreciation, we'll provide free or discounted tickets based on your sponsorship level. You'll be able to attend the event with your sponsored ticket and easily interact with attendees.

## Sponsor session
- Showcase your experience with Ubuntu and related open source technologies, case studies, and the culture of working in their teams.
- Session content must be related to Ubuntu or related open source technologies and adhere to the Code of Conduct. UbuCon is not a place to sell products, so excessive promotion of products is also prohibited.
- Sponsored sessions will be labeled as such on the website and in other media.

## Sponsor booth
Sponsor booths at the event are a great way to showcase your organization and engage directly with attendees. Activities such as booth events and mini-sessions are also possible to promote your company or organization's products, services, and activities.

---
# Sponsorship package details

## Marketing
**Basic:** Before and after the event, we'll promote your sponsorship through a variety of community outreach and participant-targeted channels.
- Your sponsorship will be mentioned during opening and closing with your logo exposed
- Post sponsor introductions and thank you post through the community's social media channels
- Dedicate sponsor information page on our website

**Email:** A reminder email sent to attendees 1-3 days before the event starts, with a brief introduction or mention of the sponsor. Depending on your sponsorship level, your visibility in the body of the email will vary.

**Engagement:** We help sponsors interact with participants even after the event ends. If you don't request otherwise when registering as a sponsor, we can send a single email to participants with the text you requested.
- At the time of sponsor registration, You may also choose to receive a list of participants who have given their consent to disclose their personal information to third parties instead of sending emails by us.
  - The items to be provided are the participant's name, affiliation, title (or profession), and email address. The information to be included in the privacy policy disclosed by the organizing committee through the website (who will receive the personal information, location (address), person in charge and contact information, purpose of use, and method of destruction upon expiration of the retention period) must be provided.
  - The retention period of the personal information received will be until September 9, 2025 (1 year) and will be described in the organizer's privacy policy.

## Swag giveaway
If you'd like, you can give out sponsor swag (stickers, t-shirts, eco-bags, mugs, etc.) to participants. You can send a small amount for a raffle, or you can send enough for all participants. We'll let you know how to do this separately.

<div style="display: flex; flex-direction: row;  height: 280px; ">
  <img src="./assets/marketing.png" style="flex: 1">
  <img src="./assets/swag.jpeg" style="flex: 1">
</div>


---
# How to become a sponsor

## Choose your sponsorship package
Please select your preferred sponsorship package from the ones listed above and submit the sponsorship application form. Once confirmed, we will proceed with the registration process if a slot is available. If you would like to adjust the details of your package, or if you would like to make an in-kind contribution, such as swags, equipment, or services needed to run the event, you can do so in consultation with the organizing committee. For in-kind sponsorships, we will provide benefits based on the value in cash.

## Issue required documents for registration 
- Quotation - In case you need to submit a purchase order (PO) in your company and get approval.
- Sponsorship agreement - Complete the event sponsorship agreement as required by the sponsor. Can be omitted if not required by the sponsor.
- Tax Invoice(or Invoice) - After completion of the contract, or if the contract is omitted, we will issue a tax invoice under the name of "Ubuntu Korea Community" after completion of the sponsor's internal approval process. If you are an overseas corporation, an invoice will be issued through our fiscal host  instead.

## Make payment
After the tax invoice (or invoice) is issued, please deposit the sponsorship fee including 10% VAT to the bank account provided, and the sponsor registration will be completed after confirmation. If a contract has been signed, the deadline will be as specified in the contract. If a contract has skipped, the deadline will be 2 weeks from the date of the tax invoice (or invoice) issued. If you need to extend the deadline, it can be extended by agreement. The deposit must be completed no later than 3 weeks before the start of the event.

## Once registration is complete… 
Once you have registered as a sponsor, your logo will be displayed on the website and you will be informed about access to benefits such as sponsored sessions. Your sponsorship will be used to cover the costs of installing venue facilities, catering, badges and swags such as stickers and T-shirts, catering for participants, travel grants speakers/volunteers/organizing committee members from non-capital areas, travel grants for selected participants who apply for the grants, and rental of video streaming and recording equipment. Any funds left over after use will be utilized for community management costs, such as tax agent fees.

## Comply with Ubuntu Code of Conduct
At all events organized by the Ubuntu Korean Community, we ask all participants to follow the "Ubuntu Code of Conduct" in order to create a safe environment where all participants are treated with respect. This also applies to sponsors, without exception. Please read the full text of the Code of Conduct and abide by it.
https://ubuntu.com/community/ethos/code-of-conduct 


---

<style scoped>
    section {
        background-image: url(https://assets.ubuntu.com/v1/ed94a429-0000_suru-corner-fan--top-right-light.jpg);
        background-position: top right;
        background-size: 20rem 15rem;
        align-content: end;
        font-size: 30px;
    }
    h1 {
        font-size: 60px;
    }
</style>

# End of Document

Thank you for consider sponsoring our event.
For inquires and securing sponsorship,
Contact sponsorship team at
sponsorship@ubuntu-kr.org 

More details on this event can be found at
https://2025.ubuntu-kr.org

<img src="./assets/uck24opening.JPG" style="margin-left: -40px; margin-bottom: -50px; width: 210mm; height: 300px; object-fit: cover;">

<!-- _paginate: skip -->
<!-- footer: false -->