# Data Sample #

---

- 5 discharge summaries, 5 progress notes (the private information has been replaced)
- xml file is the text within CEMR
- ent file is for entity and assertion information
- rel file is for relation information

---



**Details of the entity and assertion information in the file "discharge1.xml.ent"**

C: entity

P: position in the text

T: entity type

A: assertion type


> C=肺腺癌(lung adenocarcinoma) P=63:66 T=disease A=possible
> 
C=右侧胸腔积液(right pleural effusion) P=67:73 T=disease A=possible
> 
C=肺腺癌(lung adenocarcinoma) P=97:100 T=disease A=possible
> 
C=右侧胸腔积液(right pleural effusion) P=101:107 T=disease A=possible
> 
C=肺腺癌(lung adenocarcinoma) P=131:134 T=disease A=present
> 
C=右侧胸腔积液(right pleural effusion) P=135:141 T=disease A=present
> 
C=胸痛(chest pain) P=172:174 T=complaintsymptom A=present
> 
C=胸闷(chest distress) P=175:177 T=complaintsymptom A=present
> 
C=肺腺癌(lung adenocarcinoma) P=183:186 T=disease A=possible
> 
C=颈静脉怒张(distention of jugular vein) P=220:225 T=testresult A=absent
> 
C=右肺呼吸音弱(Right lung breath sounds weak) P=226:232 T=testresult A=present
> 
C=引流管(drainage tube) P=238:241 T=treatment A=present
> 
C=干湿啰音(dry wet rale) P=245:249 T=testresult A=absent
> 
C=心率(heart rate) P=250:252 T=test
> 
C=病理性杂音(pathologic murmur) P=270:275 T=testresult A=absent
> 
C=压痛(pressing pain) P=287:289 T=testresult A=absent
> 
C=反跳痛(rebound tenderness) P=290:293 T=testresult A=absent
> 
C=肌紧张(muscular tension) P=294:297 T=testresult A=absent
> 
C=移动性浊音(shifting dullness) P=305:310 T=testresult A=absent
> 
C=浮肿(dropsy) P=315:317 T=testresult A=absent
> 
C=化疗(chemotherapy) P=354:356 T=treatment A=present
> 
C=保肝(liver protection) P=363:365 T=treatment A=present
> 
C=对症(symptomatic) P=367:369 T=treatment A=present
> 
C=支持治疗(supportive treatment) P=371:375 T=treatment A=present
> 
C=颈静脉怒张(distention of jugular vein) P=439:444 T=testresult A=absent
> 
C=右肺呼吸音弱(Right lung breath sounds weak) P=445:451 T=testresult A=present
> 
C=干湿啰音(dry wet rale) P=455:459 T=testresult A=absent
> 
C=病理性杂音(pathologic murmur) P=471:476 T=testresult A=absent
> 
C=压痛(pressing pain) P=488:490 T=testresult A=absent
> 
C=反跳痛(rebound tenderness) P=491:494 T=testresult A=absent
> 
C=肌紧张(muscular tension) P=495:498 T=testresult A=absent
> 
C=移动性浊音(shifting dullness) P=506:511 T=testresult A=absent
> 
C=浮肿(dropsy) P=516:518 T=testresult A=absent
> 
C=血常规(blood routine examination) P=567:570 T=test
> 
C=加强护理(intensive care) P=577:581 T=treatment A=present

**Details of the relation information in the file "discharge1.xml.rel"**

E: entity group

R: relation type

>
E={肺腺癌(lung adenocarcinoma)【63-66】disease;右侧胸腔积液(right pleural effusion)【67-73】disease;}
>
E={肺腺癌(lung adenocarcinoma)【97-100】disease;右侧胸腔积液(right pleural effusion)【101-107】disease;}
>
E={肺腺癌(lung adenocarcinoma)【131-134】disease;右侧胸腔积液(right pleural effusion)【135-141】disease;}
>
E={肺腺癌(lung adenocarcinoma)【183-186】disease;}||R=SID||E={胸痛(chest pain)【172-174】complaintsymptom;胸闷(chest distress)【175-177】complaintsymptom;}
>
E={颈静脉怒张(distention of jugular vein)【220-225】testresult;右肺呼吸音弱(Right lung breath sounds weak)【226-232】testresult;干湿啰音(dry wet rale)【245-249】testresult;病理性杂音(pathologic murmur)【270-275】testresult;压痛(pressing pain)【287-289】testresult;反跳痛(rebound tenderness)【290-293】testresult;肌紧张(muscular tension)【294-297】testresult;移动性浊音(shifting dullness)【305-310】testresult;浮肿(dropsy)【315-317】testresult;}
>
E={保肝(liver protection)【363-365】treatment;对症(symptomatic)【367-369】treatment;支持治疗(supportive treatment)【371-375】treatment;}
>
E={颈静脉怒张(distention of jugular vein)【439-444】testresult;右肺呼吸音弱(Right lung breath sounds weak)【445-451】testresult;干湿啰音(dry wet rale)【455-459】testresult;病理性杂音(pathologic murmur)【471-476】testresult;压痛(pressing pain)【488-490】testresult;反跳痛(rebound tenderness)【491-494】testresult;肌紧张(muscular tension)【495-498】testresult;移动性浊音(shifting dullness)【506-511】testresult;浮肿(dropsy)【516-518】testresult;}

PS: the contents in the round brackets above are not included in the annotations.