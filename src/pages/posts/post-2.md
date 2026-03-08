---
layout: ../../layouts/PostLayout.astro
title: Islamic Infrastructure
pubDate: 2026-02-10
description: What does Islam need, now and in the future, in order to remain and expand as a religion?
author: Awwab Mahdi
image:
    url: '../../assets/favicon.svg'
    alt: 'A stylized geometric 3D graphic of the letter A and the letter M joined at their edges'
tags: ["blogging", "learning in public"]
---

As a Muslim, the current and future state of Islamic infrastructure is important to me. As a result, I want to determine how it stands right now, where it needs to go, and what solutions would be the most important.

Islam at its core requires following the 5 major pillars:
- Shahadah (Belief)
- Salah (Prayer)
- Saum (Fasting)
- Zakat (Charity)
- Hajj (Pilgrimage)

Shahadah is relatively straightforward. It requires believing that there is no god but Allah(SWT), and that Muhammad(PBUH) was his messenger. There are some natural extensions, like belief in the Quran as the Book of Allah, the Day of Judgement, Angels, Jinns, the previous Prophets, etc. The Shahadah is the initiation to the religion.

Salah is the daily prayer, 5 times a day. This pillar naturally lends itself to some infrastructure, and has resulted in the creation of probably hundreds, if not thousands, of prayer apps to make it easier for Muslims to keep track of their prayer. Concretely, a Muslim needs to track the time that each of the 5 daily prayers will start. Each of these prayers has fairly strict descriptions of when the prayer starts in the hadith of the Prophet(PBUH). Given an existing time tracking system(UTC, Unix Time, etc.) and some local parameters, its possible to get an algorithm that determines what the daily prayer times are for a specific location. 

Saum is fasting in the month of Ramadan. Fasting is not a large change from a Muslim's daily life, as it only encourages them to wake up before the morning prayer, Fajr, to eat a very early breakfast, and then eat their dinner after the sun sets at Maghrib time. Addressing food inequality is out of the scope of this document, so assuming that Muslims have their daily needs met, they just need the time and cultural tolerance to be able to do this. 

Zakat is donating a portion of a Muslim's yearly savings to the needy. Certain people are not required to pay Zakat, and Muslim's need to have more than a minimum amount of savings in order to qualify for paying Zakat. This minimum amount is based on a weight of gold or silver. Zakat is calculated as 2.5% of yearly savings, from the day that Zakat first becomes mandatory on the person. Zakat intersects with personal finance to a significant extent, so a personal finance app that integrated Zakat calculation would be more useful than a straightforward Zakat calculator. Most useful would be a well-designed library for determining Zakat, that could be incorporated into existing open source personal finance apps. Zakat also has another dimension, as after determining how much Zakat is required of you, and converting it into a donateable form (typically currency), you still need to determine who to donate it to. There are many charities that accept Zakat, but ideally there would be a list of Zakat eligible charities, perhaps with a ranking of how effective they are for their stated purposes. Zakat eligibility and certification is very useful and it's important to ensure that a standard like this does not get diluted, while still being applied as widely as applicable. As Zakat must be provided directly to the poor[citation needed], it's difficult to make more targeted improvements in human wellbeing by establishing trusts or funds, for establishing projects. Towards the future, assets will likely continue to become diversified, and well-integrated zakat calculators will remain important for determining how much should be paid on different types of assets. Charities will likely continue to use Zakat eligibility certifications to verify that they can process Zakat donations, and the amount of these charities will not likely decrease. Additionally, local contributions are usually possible in most cities as many people live in relative poverty, and the main considerations for a person being deserving of Zakat is them not having enough income to meet their necessary expenses(within reason).

Hajj is a pilgrimage Muslims should make once in their life to the Kaabah, which involves completing a set of rituals there over multiple days to complete the experience. Hajj is mandatory on anyone with the means to do it, and becomes mandatory as soon as one obtains the means to do it. For many, this will occur as soon as they pay off their debts and have received their first year of salary. Hajj is already a fairly complicated process, as in the modern era it requires a visa for Saudia Arabia, flight tickets, a hotel stay, a Hajj package, and more. There are many different procedures to observe while doing Hajj as well, so there is a real need for more streamlining of the process, and accessible and easy to use tools for understanding information about it.

These pillars are sufficient for an individual's basic worship in Islam, but there are many other peripheral considerations. Islam is a way of life for a group of people, and is not practiced by oneself. As a way of life, Islam needs doctors, morticians, scholars, teachers, entrepreneurs and funders, to name a few. As a community, Islam needs community tools, like shared spaces, methods to connect and advertise, and event organization tools.