# ezviz_lan_rce

Category/Tags: Network Attacks

Tool Presented at: DEF CON Hacking Village at Defcon 31 - (Y.2023)

Author/presenter: [Octavio Gianatiempo](https://twitter.com/ogianatiempo), [Javier Aguinaga](https://twitter.com/pastaCLS)

## Description

![sadp](https://github.com/DefconParrot/DefconArsenalTools/assets/30528167/4d6d34ff-3d16-472b-b0fc-f1e13b52b99e)

When people think about a compromised surveillance camera, privacy is their first concern. But what about attacking the stream integrity? How hard can this movie hacking stunt be in real life? Previous research has focused on the network layer, but we wondered if we could achieve the feat by finding a zero-day on a device we owned.

Our research has uncovered two LAN RCE vulnerabilities in the implementation of Hikvision’s Search Active Devices Protocol (SADP) and SDK server found in several Ezviz products. Exploiting either of these bugs, we managed to serve a victim an arbitrary stream by tunneling their connection with the camera into an attacker-controlled server while leaving all other camera features operational.

We will take a deep dive into the whole research process: firmware analysis, vulnerability discovery, building a toolchain to compile a debugger for the target, developing an exploit capable of bypassing ASLR, and all the details about the Hollywood-style post-exploitation including tracing, in memory code patching and manipulating the execution of the binary that implements most of the camera features.

By filling the gap between IoT hacking and the big screen, we put the integrity of video surveillance systems into question and hope to raise awareness about the security risks posed by these devices.


## Reference Links:
- Link to Tool⚙️ => https://github.com/infobyte/ezviz_lan_rce
- Link to slide✍️ => https://github.com/infobyte/ezviz_lan_rce/blob/main/presentation/SADP%20goes%20to%20Hollywood.pdf
- Link to Talk(presentation)📺 => https://github.com/infobyte/ezviz_lan_rce/tree/main/presentation
- More details => https://dchhv.org/schedule/schedule.html#sadprotocol-goes-to-hollywood-hijacking-an-ip-camera-stream-as-seen-in-the-movies
- [Twitter: Hardware Hacking Village](https://twitter.com/DC_HHV)

## Author Description

*Octavio Gianatiempo* is a Security Researcher at Faraday and a Computer Science student at the University of Buenos Aires. He’s also a biologist with research experience in molecular biology and neuroscience. The necessity of analyzing complex biological data was his point of entry into programming. But he wanted to achieve a deeper understanding of how computers work, so he enrolled in Computer Science. As a Security Researcher at Faraday, he focuses on embedded devices, reverse engineering and fuzzing open and closed source software to find new vulnerabilities and exploit them.

*Javier Aguinaga* is a self-taught reverse engineer with a principal focus in exploiting, currently working at Faraday for the last 7 years. He started his journey as a hobbyist electronic enthusiast and began learning how to crack security systems for video games. This led him to pursue a career in reverse engineering, where he has gained extensive experience analyzing and breaking down complex systems. With his expertise, Javier has been able to identify vulnerabilities in various technologies and has presented his findings at several conferences. He looks forward to sharing his insights and learning from others at the upcoming conference.

## Author's Social Links:

- [Twitter: Octavio Gianatiempo](https://twitter.com/ogianatiempo)
- [Twitter: Javier Aguinaga](https://twitter.com/pastaCLS)
- [Website](#)
