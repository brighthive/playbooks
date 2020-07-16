# Responsible Data Use Playbook for Digital Contact Tracing

### Introduction
COVID-19 is an unprecedented public health crisis. As the disease continues to spread through communities across the U.S. and abroad, information about the illness continues to evolve. To slow the spread, public health officials are turning to contact tracing as a means to track cases, identify sources of transmission, and inform people who may have been exposed to take precautions that can prevent further transmission. 

Manual contact tracing is a scientifically established method that can help understand the spread of communicable diseases. For contact tracing to be most effective, people must share sensitive personal information regarding their whereabouts and the people with whom they have been in close proximity. This information allows contact tracing professionals to trace or map their locations and connect with those with whom they have been in close contact. One unique feature of the COVID-19 era is the way digital technology is facilitating these processes.

Digital contact tracing technology (DCTT) has the potential to significantly reduce the spread of COVID-19 and assist with reopening efforts. Technologies such as smartphones, mobile device applications (apps), and the network of data transfer protocols (e.g., APIs) have been pulled together to produce digital contact tracing technologies. Contact tracing apps track an individual’s exposure to COVID-19 and notify the individual if they encounter another app user who has tested positive for the virus, or who has self-reported as positive. These apps typically track users through either geolocation data or Bluetooth proximity data, or both. 

Apps relying on geolocation data use GPS, WiFi, or cell phone towers to track users’ locations, while Bluetooth apps check for other nearby devices using the app and exchange a unique, often rotating, token with the other device. The app later searches a database of tokens registered to users who have self-reported testing positive for COVID-19 to determine if the user was exposed to the virus. 

Apps using geolocation data are considered more privacy invasive because they rely on tracking the user’s location to determine proximity to other users. Bluetooth proximity apps only collect proximity data but rely on constant broadcast from a Bluetooth device, and may be less accurate than apps relying on location data. This is a particular problem for centralized Bluetooth-based apps, which are not able to make use of the Google-Apple Exposure Notification API for decentralized exposure notification apps. 

The design and use of these apps create privacy risks and raise ethical questions. MIT Technology Review [assessed](https://www.technologyreview.com/2020/05/07/1000961/launching-mittr-covid-tracing-tracker/) apps developed by 25 countries, while the Internet Digital Accountability Council [reviewed](https://digitalwatchdog.org/privacy-in-the-age-of-covid-an-idac-investigation-of-covid-19-apps/) 108 apps across 41 countries. Many of these apps failed to minimize their collection efforts and did not provide guarantees for destroying the data after a set period. Some countries’ apps also failed to place limits on the use of collected data and many of the apps reviewed did not provide transparency around their policies or design. By taking these concerns into account, organizations that develop or use contact tracing apps can protect both health and privacy, and increase trust in contact tracing apps and other digital tools.

While health behavior changes at the population level, such as social distancing, hand washing, and wearing face coverings, are the current best approach to containing the spread of COVID-19, both analog and digital contact tracing are important elements of a comprehensive approach to containing the spread of this viral disease. Nevertheless, DCTT raises significant ethical and privacy concerns that should be addressed through design and policy. 

Public health authorities, application developers, and users of DCTT need better information on how to best preserve privacy and ensure ethical use of contact tracing data, so they can better scale contact tracing initiatives and reduce the spread of COVID-19. 

[BrightHive](https://brighthive.io/) and the [Future of Privacy Forum](https://fpf.org/) teamed up to kick off this privacy playbook to assist the coalitions of professionals invested in development and deployment of trusted DCTT. The playbook provides a series of actionable steps that purposefully address the privacy concerns of DCTT and support the development of ethical and responsible digital contact tracing protocols. 

In particular, this playbook has been developed with the following types of scenarios, or use cases, in mind: 1) easing tension between application providers, public health officials, and government authorities; 2) supporting “opt-in” models for individuals to share health and location data; 3) supporting employers that are turning to internal contact tracing when their workplaces reopen.

This playbook is organized into two categories: Foundational and organizational plays, and technical and operational plays. Foundational and organizational plays create a strong, diverse coalition with a unified goal and set of values, aid in the administration of DCTT initiatives, and ensure that the coalition adheres to its shared values and gains the public’s trust. These plays are geared toward leadership, policy, and partnership roles in an initiative. 

The technical and operational plays support implementing the DCTT initiative in a way that is consistent with other plays, the coalition’s values, and users’ privacy rights. These plays are geared toward technical, project management, and day-to-day operational roles in the initiative. 

While plays are geared toward different roles, BrightHive and FPF advise collaborating across team and function through the lifecycle of the DCTT initiative.

*Take the Next Step*
* Suggest a play to add to this playbook or suggest edits by [sending us a message](https://brighthive.io/make-a-playbook-suggestion/).
* Discuss this playbook and share learnings with others using the playbook in our [BrightHive Slack Community](https://brighthive.io/slack-community-signup/).
* [Connect with a BrightHive team member](https://brighthive.io/playbook-next-steps/) to learn how BrightHive can help you solve a responsible data sharing challenge.

### Resources
This playbook was informed by the following resources: insights and recommendations from FPF [workshops](https://fpf.org/2020/03/27/privacy-and-pandemics-a-thoughtful-discussion/), [publications](https://fpf.org/tag/pandemic/) & [testimony](https://fpf.org/2020/04/09/fpf-provides-senate-testimony-on-strategies-to-mitigate-privacy-risks-of-using-data-to-combat-covid-19/); Georgetown Beeck Center [Data Governance Handbook](https://beeckcenter.georgetown.edu/wp-content/uploads/2020/01/Data-Sharing-Appendix.pdf); Johns Hopkins [Digital Contact Tracing book](https://muse.jhu.edu/book/75831/pdf); [Law.MIT principles](https://law.mit.edu/) and related efforts; [STAT](https://www.statnews.com/2020/06/05/contact-tracing-technology-protect-people-from-discrimination-disease/) news articles and commentary; and other data protection COVID-19 [guidance](https://sites.google.com/fpf.org/covid-19-privacy-resources/#h.p_l4tfppxBBjkU)/resources. 

### Acknowledgements
BrightHive would like to thank Kelly Dolan, Autumn Felty, Natalie Evans Harris, Samantha Levy, Brian Lim, Natalie Ortiz, Hana Passen, Joanna Tess, and Maithri Vangala for their expertise and contributions to the development of this playbook.

Future of Privacy Forum would like to thank Kelsey Finch, Dr. Sara Jordan, Brenda Leong, Katelyn Ringrose, Pollyanna Sanderson, and Dr. Rachele Hendricks-Sturrup for their expertise and contributions to the development of this playbook.
