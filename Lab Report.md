# Grep Commands

## Grep -n Command

```
Command: grep -n "import" chapter-1.txt 

Output:
230:    The threat of Soviet bombers diminished significantly as the Cold War ended, and the number of NORAD alert sites was reduced from its Cold War high of 26. Some within the Pentagon argued in the 1990s that the alert sites should be eliminated entirely. In an effort to preserve their mission, members of the air defense community advocated the importance of air sovereignty against emerging "asymmetric threats" to the United States: drug smuggling, "non-state and state-sponsored terrorists," and the proliferation of weapons of mass destruction and ballistic missile technology.
578:    At about 9:20, security personnel at FAA headquarters set up a hijacking teleconference with several agencies, including the Defense Department. The NMCC officer who participated told us that the call was monitored only periodically because the information was sporadic, it was of little value, and there were other important tasks. The FAA manager of the teleconference also remembered that the military participated only briefly before the Pentagon was hit. Both individuals agreed that the teleconference played no role in coordinating a response to the attacks of 9/11. Acting Deputy Administrator Belger was frustrated to learn later in the morning that the military had not been on the call.
640:    Among the sources that reflect other important events of that morning, there is no documentary evidence for this call, but the relevant sources are incomplete. Others nearby who were taking notes, such as the Vice President's chief of staff, Scooter Libby, who sat next to him, and Mrs. Cheney, did not note a call between the President and Vice President immediately after the Vice President entered the conference room.

```


```
Command: grep -n "control" 1468-6708-3-1.txt

Output:
9:        Six large controlled population-based studies of
11:        between body mass index (BMI) and mortality, controlling
163:          the possibility of 'over-adjustment', controlling

```


## Grep -rl Command


```
Command: grep -rl "corporation" technical

Output:
technical/government/About_LSC/Comments_on_semiannual.txt
technical/government/About_LSC/Special_report_to_congress.txt
technical/government/About_LSC/commission_report.txt
technical/government/About_LSC/ONTARIO_LEGAL_AID_SERIES.txt
technical/government/About_LSC/LegalServCorp_v_VelazquezOpinion.txt
technical/government/About_LSC/diversity_priorities.txt
technical/government/About_LSC/State_Planning_Special_Report.txt
technical/government/Gen_Account_Office/d0269g.txt
technical/government/Gen_Account_Office/Testimony_cg00010t.txt
technical/government/Gen_Account_Office/d01376g.txt
technical/government/Gen_Account_Office/Statements_Feb28-1997_volume.txt
technical/government/Gen_Account_Office/gg96118.txt
technical/government/Gen_Account_Office/ffm.txt
technical/government/Gen_Account_Office/July11-2001_gg00172r.txt
technical/government/Gen_Account_Office/d03232sp.txt
technical/government/Gen_Account_Office/Oct15-2001_d0224.txt
technical/government/Gen_Account_Office/ai00134.txt
technical/government/Gen_Account_Office/ai9868.txt
technical/government/Gen_Account_Office/May1998_ai98068.txt
technical/government/Post_Rate_Comm/Gleiman_gca2000.txt
technical/government/Media/Federal_agency.txt
technical/government/Media/Legal_system_fails_poor.txt
technical/government/Media/Barnes_new_job.txt
technical/government/Media/Campaign_Pays.txt
technical/government/Media/Rumble_in_the_Bronx.txt
technical/government/Media/Major_Changes.txt
technical/government/Media/All_May_Have_Justice.txt
technical/government/Media/Entities_Merge.txt
technical/government/Media/pro_bono_efforts.txt
technical/government/Media/Aid_Gets_7_Million.txt
technical/plos/journal.pbio.0030032.txt
technical/plos/pmed.0020073.txt
technical/plos/pmed.0020009.txt
technical/plos/journal.pbio.0020113.txt
technical/plos/pmed.0010056.txt
technical/plos/journal.pbio.0020307.txt
technical/plos/pmed.0020281.txt
technical/biomed/1471-2156-3-11.txt
technical/biomed/1471-2121-3-10.txt
technical/biomed/1471-2172-3-4.txt
technical/biomed/1471-2334-3-9.txt
technical/biomed/1471-2091-2-11.txt
technical/biomed/1476-0711-2-7.txt
technical/biomed/1471-2121-3-13.txt
technical/biomed/1471-2407-3-18.txt
technical/biomed/1471-2121-3-12.txt
technical/biomed/1471-2156-3-17.txt
technical/biomed/gb-2003-4-7-r42.txt
technical/biomed/1471-2407-1-19.txt
technical/biomed/1472-6750-1-13.txt
technical/biomed/gb-2003-4-7-r43.txt
technical/biomed/1471-2350-4-6.txt
technical/biomed/1471-2121-3-15.txt
technical/biomed/1472-6769-1-2.txt
technical/biomed/1472-6904-2-5.txt
technical/biomed/1471-2172-4-1.txt
technical/biomed/1471-2172-3-12.txt
technical/biomed/gb-2002-3-6-software0001.txt
technical/biomed/1471-2164-4-23.txt
technical/biomed/1471-2148-2-8.txt
technical/biomed/cc1538.txt
technical/biomed/1471-213X-3-4.txt
technical/biomed/gb-2001-2-6-research0021.txt
technical/biomed/ar624.txt
technical/biomed/1471-2407-2-16.txt
technical/biomed/1471-2407-2-17.txt
technical/biomed/gb-2002-3-11-research0062.txt
technical/biomed/1471-2164-4-19.txt
technical/biomed/1471-2407-2-15.txt
technical/biomed/1476-4598-2-3.txt
technical/biomed/1475-4924-1-10.txt
technical/biomed/1471-2148-2-2.txt
technical/biomed/1471-2407-2-18.txt
technical/biomed/gb-2003-4-1-r5.txt
technical/biomed/1471-2318-3-2.txt
technical/biomed/1471-2164-3-35.txt
technical/biomed/1471-2164-4-28.txt
technical/biomed/1471-2164-4-16.txt
technical/biomed/1476-511X-1-2.txt
technical/biomed/gb-2002-3-12-research0071.txt
technical/biomed/gb-2001-3-1-research0005.txt
technical/biomed/1477-7525-1-10.txt
technical/biomed/ar615.txt
technical/biomed/1471-5945-2-13.txt
technical/biomed/1471-2199-3-7.txt
technical/biomed/1471-2121-2-15.txt
technical/biomed/1472-6750-2-14.txt
technical/biomed/1471-2334-2-7.txt
technical/biomed/1471-2105-3-22.txt
technical/biomed/1471-2164-3-30.txt
technical/biomed/1471-2121-3-25.txt
technical/biomed/1471-2121-3-19.txt
technical/biomed/1471-2164-4-6.txt
technical/biomed/1471-2369-3-1.txt
technical/biomed/1471-2199-2-3.txt
technical/biomed/1475-2891-1-2.txt
technical/biomed/1475-2867-2-10.txt
technical/biomed/1471-2121-4-2.txt
technical/biomed/1471-2407-2-9.txt
technical/biomed/1476-4598-2-28.txt
technical/biomed/1476-511X-2-2.txt
technical/biomed/1471-2261-2-11.txt
technical/biomed/1471-2105-3-2.txt
technical/biomed/1471-2148-1-1.txt
technical/biomed/1471-213X-1-13.txt
technical/biomed/1475-2867-2-15.txt
technical/biomed/gb-2001-2-12-research0051.txt
technical/biomed/gb-2002-3-8-research0038.txt
technical/biomed/1475-2875-1-5.txt
technical/biomed/1471-2458-1-9.txt
technical/biomed/1471-2156-4-9.txt
technical/biomed/1471-2121-4-5.txt
technical/biomed/1471-2164-2-4.txt
technical/biomed/1471-2407-3-16.txt
technical/biomed/1476-4598-1-6.txt
technical/911report/chapter-13.4.txt
technical/911report/chapter-13.3.txt

```


```
Command: grep -rl "creation" technical

Output:
technical/government/About_LSC/Strategic_report.txt
technical/government/About_LSC/Comments_on_semiannual.txt
technical/government/About_LSC/CONFIG_STANDARDS.txt
technical/government/About_LSC/commission_report.txt
technical/government/About_LSC/ONTARIO_LEGAL_AID_SERIES.txt
technical/government/About_LSC/State_Planning_Report.txt
technical/government/About_LSC/conference_highlights.txt
technical/government/About_LSC/State_Planning_Special_Report.txt
technical/government/Env_Prot_Agen/tech_sectiong.txt
technical/government/Env_Prot_Agen/tech_adden.txt
technical/government/Alcohol_Problems/Session4-PDF.txt
technical/government/Gen_Account_Office/d0269g.txt
technical/government/Gen_Account_Office/Sept27-2002_d02966.txt
technical/government/Gen_Account_Office/Statements_Feb28-1997_volume.txt
technical/government/Gen_Account_Office/og97019.txt
technical/government/Gen_Account_Office/pe1019.txt
technical/government/Gen_Account_Office/d01591sp.txt
technical/government/Gen_Account_Office/Oct15-2001_d0224.txt
technical/government/Gen_Account_Office/InternalControl_ai00021p.txt
technical/government/Gen_Account_Office/Testimony_Jul17-2002_d02957t.txt
technical/government/Post_Rate_Comm/Mitchell_RMVancouver.txt
technical/government/Media/Terrorist_Attack.txt
technical/government/Media/Texas_Supreme_Court.txt
technical/government/Media/Aid_Gets_7_Million.txt
technical/plos/pmed.0020273.txt
technical/plos/journal.pbio.0020419.txt
technical/plos/journal.pbio.0020145.txt
technical/plos/journal.pbio.0020187.txt
technical/plos/pmed.0020062.txt
technical/plos/pmed.0020158.txt
technical/plos/journal.pbio.0020052.txt
technical/plos/pmed.0010060.txt
technical/plos/journal.pbio.0020125.txt
technical/plos/pmed.0020162.txt
technical/plos/journal.pbio.0020113.txt
technical/plos/journal.pbio.0020272.txt
technical/plos/pmed.0020036.txt
technical/plos/journal.pbio.0020071.txt
technical/plos/pmed.0020246.txt
technical/plos/journal.pbio.0020214.txt
technical/plos/pmed.0020247.txt
technical/plos/journal.pbio.0020161.txt
technical/plos/journal.pbio.0020439.txt
technical/plos/journal.pbio.0020206.txt
technical/plos/journal.pbio.0020010.txt
technical/plos/journal.pbio.0020172.txt
technical/biomed/1471-2121-3-10.txt
technical/biomed/1471-2199-2-10.txt
technical/biomed/1472-6947-3-8.txt
technical/biomed/gb-2002-3-9-research0043.txt
technical/biomed/gb-2003-4-4-r26.txt
technical/biomed/1471-2172-3-2.txt
technical/biomed/1472-6882-1-7.txt
technical/biomed/1471-2334-1-24.txt
technical/biomed/gb-2002-3-9-research0046.txt
technical/biomed/1471-2156-3-16.txt
technical/biomed/1471-2458-3-2.txt
technical/biomed/gb-2002-3-2-research0008.txt
technical/biomed/gb-2002-3-8-research0040.txt
technical/biomed/1471-2172-3-12.txt
technical/biomed/1471-2458-2-6.txt
technical/biomed/1472-6815-2-3.txt
technical/biomed/gb-2002-3-12-research0081.txt
technical/biomed/1472-6750-2-13.txt
technical/biomed/1472-6963-3-11.txt
technical/biomed/1472-6793-3-6.txt
technical/biomed/1472-6750-3-4.txt
technical/biomed/1471-2202-3-7.txt
technical/biomed/gb-2002-3-10-research0052.txt
technical/biomed/1471-2261-2-11.txt
technical/biomed/1471-2164-2-7.txt
technical/biomed/1472-6947-3-5.txt
technical/biomed/1471-2296-3-3.txt
technical/biomed/1471-2458-3-11.txt
technical/911report/chapter-13.5.txt
technical/911report/chapter-13.1.txt
technical/911report/chapter-13.3.txt
technical/911report/chapter-3.txt
technical/911report/chapter-6.txt
technical/911report/chapter-12.txt

```

## Grep -C Command


```
Command: grep -C 2 "mission" chapter-7.txt

Output:
                from the intended target area.
            
            Hazmi and Mihdhar were ill-prepared for a mission in the United States. Their only
                qualifications for this plot were their devotion to Usama Bin Ladin, their veteran
                service, and their ability to get valid U.S. visas. Neither had spent any
--
                that he might be connected with terrorist activity.
            
            When interviewed by both the FBI and the Commission staff, Thumairy has denied
                preaching anti-Western sermons, much less promoting violent jihad. More to the
                point, he claimed not to recognize either Hazmi or Mihdhar. Both denials are
--
                Diego from Los Angeles, possibly driven by Mohdar Abdullah. Abdullah, a Yemeni
                university student in his early 20s, is fluent in both Arabic and English, and was
                perfectly suited to assist the hijackers in pursuing their mission.
            
            After 9/11, Abdullah was interviewed many times by the FBI. He admitted knowing of
--
                deported to Yemen on May 21, 2004, after the U.S. Attorney for the Southern District
                of California declined to prosecute him on charges arising out of his alleged
                jailhouse admissions concerning the 9/11 operatives. The Department of Justice
                declined to delay his removal pending further investigation of this new
                    information.
--
                have tasked Rababah to help Hazmi and Hanjour. We share that suspicion, given the
                remarkable coincidence of Aulaqi's prior relationship with Hazmi. As noted above,
                the Commission was unable to locate and interview Aulaqi. Rababah has been deported
                to Jordan, having been convicted after 9/11 in a fraudulent driver's license
                    scheme.
--
                Atta understood this preference. Binalshibh says Bin Ladin had given the same
                message to Waleed al Shehri for conveyance to Atta earlier that spring. Binalshibh
                also received permission to meet Atta in Malaysia. Atef provided money for the trip,
                which KSM would help Binalshibh arrange in Karachi.
            
```


```
Command: grep -C 2 "aliens" chapter-10.txt

Output: 
                cooperation with the FBI began arresting individuals for immigration violations whom
                they encountered while following up leads in the FBI's investigation of the 9/11
                attacks. Eventually, 768 aliens were arrested as "special interest" detainees. Some
                (such as Zacarias Moussaoui) were actually in INS custody before 9/11; most were
                arrested after. Attorney General John Ashcroft told us that he saw his job in
--
                80 days.
            
            We have assessed this effort to detain aliens of "special interest." The detainees
                were lawfully held on immigration charges. Records indicate that 531 were deported,
                162 were released on bond, 24 received some kind of immigration benefits, 12 had

```

## Grep -color Command


```
Command: grep --color "role" 1468-6708-3-7.txt

Output:

![Image](Screenshot 2023-05-08 at 5.23.19 PM.png)	

```


```
Command: grep --color "oxygen" cc3.txt

Output: 

![Image](Screenshot 2023-05-08 at 5.24.53 PM.png)	

```
