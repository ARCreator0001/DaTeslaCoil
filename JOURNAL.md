# Da Tesla Coil - A cool half bridge DRSSTC

It is a cool Tesla Coil I want to build, for years I am trynna get to build one but either I don't have the necessary parts or I cheap out and they blow up. So want to build a mid sized about like the OneTesla TS coil since I am obsessed with musical coils and lighting and wireless energy!

# 2026-05-27: What next, tuning

**Total time spent: 4.6 hours**

well the coil played good and I noticed after winding its 6th turn ebfroe didnt and putting it on a grounded foil sheet containign mdf platform it actually pefromed slightly worse.
but still ok

One thing was that it was first impossibel to film it properly playing arcs and also it was super stypidly loud, my ears hurted a lot after just 5 misn of attempting to record it, I can hear it from my street road and it was in the apartment lit very loud.

I then put sheets behind it to hopefully film better, still very bad.

![image.png](https://cdn.hackclub.com/019e6a00-cd44-725d-a2ca-5a59263e238d/image.png)
it can capture it a lil better now but problem fundementally i cannot get any good recording in day lol due to light and in night i get best recording but I wake up my neighbours lol.

Ok, coil works, now what?
Me satisfied, hell nah, its a sprawlign mess in my table not the amazing tesla coil I imagined and it looks like its put together and held with hopes and dreams.

I want a proper product. Rn the topload is just there. the secondary too, theres nothing securing it.

So I aim to now actualy tune it further bcs it seems there is a freq mismatch between primary and secondary so working on it, a 3d printer would be super helpful but ehh, you gotta live with what u have until u blow a million uccs and give up lmao

So from now on, I wanna do few thinsg that will make this truly a project.

I am gonna first figure out and add over current protection and protect the IGBTs
then I want a proper soft start system to prevent the inrush and  away to limit current, rn its just ebing done with old incandescent lightbulbs.

Next a secure sturdy proper case safe to hous electronics properly and shield it.

Next make it visually appealing

Then make this a proper tesla coil build in the form that I can carr7y this as a whooe and just sue it and put it away and it be secure lol.



# 2026-05-27: New topload and experiment with diff coils

**Total time spent: 11 hours**

so after these tiny arcs I tried my taller coil and got bit better arcs.

![image.png](https://cdn.hackclub.com/019e69de-ab44-72f3-ba32-6fb40c5424ae/image.png)
https://photos.app.goo.gl/vozBrzEDexr75UMFA
It was slightly better btu strill it drawed so much current from mains by the bulb glowing so much and for that much consuption it should atleast give big arcs btu it gave these tinyyy arcs only.

This continued on as I tested the coil and I also added this grounded box nearby to help increase the arc length by a little bit encourage it.
![image.png](https://cdn.hackclub.com/019e69e0-9fd6-746c-a8ba-8296ada2effb/image.png)
it only did bit better in playing bad apple but still very bad for the amt of current it took.

![image.png](https://cdn.hackclub.com/019e69e3-ace9-7f31-ab28-f64448fa0578/image.png)
main thing i think that was suckign away arcs was these sharp edges too and also the fact that teh topload was trash.

So I then unable to 3D print a proper toroid I spent hours with cardboard and some smart plannign and hacking and just redneck enginerring I made this fairly ok topload.

I dont hgave any pics of internals but what I did was I made a 2D drawing of my topload from 3D model in solidworks(got it student sponsorship lol and its so hard to use) and I made the drawign 1:1 and i printed it and I cut multiple cardboard pieces of the shape of a cross section of the toroid and I glued them onto a thin circle made out of thin cardboard from my old school notes.

Then I stuck them in a clock style way and stuck those pieces with PVA glue and let it dry then stuck another circle on other side top of toroid.

Then I actually planned on stickign paper to like translate the ribbed rough toroid to my proper smooth toroid shape to stick some aluminium tape.

That very quickly failed. And then I used a leftover tube that was almost dry lmao of T8000 glue, and that just made it harder to remove the failed attempt of paper.

Then I just went mad, got a roll of maskign tape and just started going at it sticking lmaooo

![image.png](https://cdn.hackclub.com/019e69e9-1946-7c7a-9656-a487dc6baaa0/image.png)

The white paper strip cut is my initial plan lol.

![image.png](https://cdn.hackclub.com/019e69e9-f5ab-795c-9c82-8a7e3760ff87/image.png)

Then I just put more and more masking tape on lol to get this rough crinkly toroid disc thing.
It looks very awful but, to my eyes its good and thats what matters hehe.

![image.png](https://cdn.hackclub.com/019e69ea-456a-7e92-95d3-4ed72c35ec77/image.png)

I mean from morning about 10am till the night 10:30pm I worked at this toroid lol so about 11 hours I can say with breaks.

And at night Ifinally rush to poweron the coil after I stick the aluminium tape and oh boy,those are some arcs....
![image.png](https://cdn.hackclub.com/019e69f1-7be0-73a9-8760-8008c6f6859b/image.png)
https://photos.app.goo.gl/7C5fBV51yr256FXW7

https://photos.app.goo.gl/L4Qy2Cvpx8ybhqre7
you can see such arcsss!!

![image.png](https://cdn.hackclub.com/019e69f3-00c5-72b7-a927-979305a08f5e/image.png)


Insane arcs with playing stay compared to before, still less for mains volatge but see this is a far better improvement.

![image.png](https://cdn.hackclub.com/019e69fd-92c6-7157-ac7a-e073f5aeff9b/image.png)

https://photos.app.goo.gl/5WXdYE1qEHWy5Cit7

litreally its good

# 2026-05-27: Finally upto speed and rn

**Total time spent: 8 hours**

So finally updated to now.
I succumbed to it and declared that there's no option but to spend money to buy from digikey..
so placed orders on ucc chips and also a fiber receiver the original one the pcb is made for IF-D95T
And at this time I also built the BLUEPRINT project my ESP32 DRSSTC Interrupter.

So I did the wait. And they arrived.
I quickly insert them into the pcb, and I perform a power test LV side by buzzing method and using my new interrupter too, and it actually didnt die immediately and the uccs were very cool, ig the robu ones are defective, well need money to buy legit ig and its worth it.

Then I just tested it on one of my tesla coils I wound alr would make a sep entry for it covering process, and at 68v bus from that 48v transfromer it actually did something after I flip the uccs! initially it did a lot of nothing except the interrupter music playing more loudly through primary. Then after I flip, I saw my first sparks finally and coil oscillated and the noise got bigger!!

I don't have a topload thats proper and could not afford one so just used plates and stuff and I then test with mains and I got some very meager arcs at mains voltage, but still somethign compared to nothing.

[Video](https://photos.app.goo.gl/Qr2euDFFvzk4ZFbP6)
![image.png](https://cdn.hackclub.com/019e69da-cc61-7e52-ad82-90f793867c7d/image.png)
You can see sooo tiny arcs but it atleast oscillated but sooo bad at 325v bus

# 2026-05-27: Testing HV side- How I actually did it

**Total time spent: 4 hours**

So I was basically not at all confident with mains, since alr as a kid whiel trynna build a half bridge blew up my fets upon first powerup and also popped the mains breaker and got a tight slap, so for inrush reasons and mains isolation ones, I put up a sketchy plan.
I pulled out a large toroidal autotransformer from a voltage stabiliser that tripped RCCB at that time and it was nice to play with lol but broke my back.
![image.png](https://cdn.hackclub.com/019e69a1-3d30-7f7e-be12-e576144b6bb9/image.png)
![image.png](https://cdn.hackclub.com/019e69a1-522a-702b-bc74-93d5078b6d01/image.png)
here is it in my balcony, I tripped over it many times lol.

So what I did was I was playing with it and I connected few taps to the output of a center tapped 48v transformer and I can get 125vac or 260vac from few taps lol by accident and I used it to power up the bridge with a series light bulb to limit current.
![image.png](https://cdn.hackclub.com/019e69a3-77c3-7b1a-8e54-d45eda298119/image.png)
![image.png](https://cdn.hackclub.com/019e69a3-f3bd-7527-a4aa-a861fbf809cf/image.png)
Here is da setup, please do not recreate in home, could not afford safetly lol, safety third.

https://photos.app.goo.gl/VBNeGSWPHD9N46zt7
And my way of testing if it is ok is if it didnt immediately blow up to the voltage it passes lmao.

# 2026-05-27: Explain continued

**Total time spent: 2 hours**

So, this journal again is just explanation from what I alr done that I havent logged.
So I built the pcb 99% and I used a heatsink that i always use for stuff a massive one tbh and I painstakingly drill holes with a DIY crappy drill to mount the IGBTs lol.

Oh and since I was(and I am rn) not spending a doller since cant lol, I cracked open my chinese 12v 15 amp SMPS power supply and I stole its thermal pads and I cut it in half lmaooo and used for the IGBTs since without them ur guarenteed to short shit since both are in same heatsink, and its mains operated.

I then to hopefully not kill the IGBTs from heat just lit soldered in 3 sec at 275c, with a huge thermal sink too so the soldering is crap but ehh it can carry current lol.

I also spent about half an hour tinning the PCB's exposed tracks since they carry a ton of current. And prolly the fumes from the flux would have made me real good mentally lmfao.

Then I used my interrupter I made at that time as a breadboard project with the crappy toslink transmitter and my dongly toslink receiver from the pcb lol to interrupt.
So first I was happyw ith my gate drivers buzzing to the tune lol but they got super hot super fast and also like were ont he verge of dying and this wa sat 12v more liek 10v on the side of UCC chips, see the drivers I ordered from robu I think after that and before were lit faulty or smth or my circuit is trash and it just died each time but after one of the UCC died and teh other followed, I ordered so many UCCs and the pcb precisely did 'nothing', yea, pure nothingness, and the UCCs would get super hot too or do nothing :(

I was lit devastated for a while that I put away this and got on to in the middle desinging a newer pcb?? ig that supported both 1230 and 220v but i think now int he future will remove that and just make 2 versions ig.
well lemme continue in next journal but i dont wanna do false hours here so thats why i am putting so low hours on these explanatory ones. I will include time of tinning the pads tho but a hour less.

Here is pcb at that stage
![IMG_20260404_214501.jpg](https://cdn.hackclub.com/019e699a-6e6a-7045-9034-c50e8d7c8c9c/IMG_20260404_214501.jpg)
And btw as a result of all those dead UCCs, I kept killing all my logic ICs too and they were super expensive for me i mean 90 rupees for me for tht is stupid price tbh but still many 74HCT14 and 74HCT74 were killed brutally.
I ended up just using a crappy 74HC74 and a 74HCT14 that I pulled from a perfboard of a failed attempt of this circuit #6 ( I tried os many times and failed).

And also burnt a lot of voltage regulators :(

# 2026-05-27: CLARITY journal 1

**Total time spent: 0.01 hours**

(hereon this added after import from blueprint)

So geenrally mind the inconsistency of this project from start. 
Basically as an explanation on what I am doing.
I wanted to build basically a Tesla Coil driver that actually worked and didnt blow up right away so I settled on the OneTesla's old TS kit design but the thing  is the components was ancient and was impossible to source them easily. And I wanted to make many changes to it and customise it so I downloaded the files of the old TS from wayback machine of onetesla.com then I have taken the file imported to my cad software easyeda and I started off the mods.

First off I wanted to use modern gate drivers UCC2742* series ones, since they are faster and newer and also cheaper. So I had re routed the traces meant for the UCC37322 & 37321 and instead made it for UCC27423P & UCC27424P and I kept a DIP-8 socket for them not commiting to smt gate drivers(good idea for future).
I also then modified the footprints of the components like the IGBTs so I can use my TGAN60N60 ones I had on hand, and also I replaced 99.9% of all caps to SMT 1206 ones since I figured SMT it is.

I then also changed the gate resistor footprint and also used a different value one other than the ones OneTesla used based on few napkin math with the help of my friend.

I also then changed out the tiny footprint for the 1uF series to GDT primary cap since I CANNOT find a cap of 1uF with that size, for same reason used 1206 1uF caps for everything else.

Then I should have adjusted the bus capacitor footprint and size too but stupid me did not.

Rest of the stuff I tried my best to stick onto OneTesla's footprints and I hit order on my first PCB that I ordered ever, was expensive and took time to fab but it came, then I built it.

I ordered a cheap cap series with the primary of same value 68nF since I have no scope to tune so I am trynna recreate OneTesla atp. Hopefully I am funded for a scope lol.
I also ordered gate drivers in smt format and pcb adfaptors from robu(bad idea)
I also ordered a 200 turn feedback CT  instead of 300 turn one but same model series CST206 iirc.Since it is a drsstc and is designed for primary feedback using it.

For the GDT core I just used a random one from a power supply which I think will be  abd idea, hoep can buy a proper material GDT core or in the future use premade GDT if possible. GDT is wound 1:1:1 btw.

the bus caps tho were a steal I spent like smth insane its exactly 0.073USD for 2 1200uF 450v caps EPCOS from RS components, by the price should have ordered 100s of caps but stupid me didnt. I think it was on a pricing error and like the updated price is 8 bucks a pop so yea lmfao.
Sad thign is the cap aint fit on the pcb! event the new 1000uF ones hopign they r smaller I got which I overpayed for !

So after just buildign tot his point I left this project and went and now I am here to finally pick up, finish my goal of 3 years to build a cool TC.
![image.png](https://cdn.hackclub.com/019e6985-9fb0-7a90-9cf4-6e7e9866d9cb/image.png) pic of blueprint project from which I picked up this to here


# 2026-05-27: 3/27/2026 - Major PCB changes V2 ,prototype ready for initial production

**Total time spent: 5.0h_**

_Time spent: 13.0h_  

The PCB is finally ready.
Many changes I have done like the gate driver part,etc.
Next I hope i would make a 3D model for a shell but I have to make it which is more challenging than just building it by rough measurements from wood but I will do it.

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI4NTU5LCJwdXIiOiJibG9iX2lkIn19--2c59bf76854326a8ba5d5c5b9a6415bee39d70dd/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI4NTYwLCJwdXIiOiJibG9iX2lkIn19--1f76d2d49d1050fbe391cff276650be3ac89fbab/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI4NTYxLCJwdXIiOiJibG9iX2lkIn19--bbc3f31fc1e28968596f55d3e8cfdea26a872e42/image.png)

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI4NTYyLCJwdXIiOiJibG9iX2lkIn19--1968b203601b054809840794f2852eabafd7f2cb/image.png)
 updated schematic.

[Schematic_OneTeslaTSRevived_2026-03-27](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI4NTYzLCJwdXIiOiJibG9iX2lkIn19--35c608daf4cc4e647c8c22d17e1fb247c263789c/Schematic_OneTeslaTSRevived_2026-03-27.pdf)
[BOM_OneTeslaTSRevived_2026-03-27](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI4NTY0LCJwdXIiOiJibG9iX2lkIn19--82c4a55ed8544d28e1ff9e5dc9e1b3a39770bc59/BOM_OneTeslaTSRevived_2026-03-27.csv)

# 2026-05-27: 3/26/2026 11 PM - New PCB design V1.1 with improvements

**Total time spent: 7.0h_**

_Time spent: 7.0h_  

Compared to original pcb prototype that i was able to get fabbed i have changed the dimensions and footprints of this one to match more accurately.
I have also updated many components here to newer more efficient parts easy to find and keeping in mind to make it easy to assemble by hobbyists.
Next should make a wooden case or design a plastic case with metal shielding inside.
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI3OTIzLCJwdXIiOiJibG9iX2lkIn19--428baacfc23c2fc8d8b52fd4b9ac8a707fc9d8cc/image.png)![image](https://raw.githubusercontent.com/ARCreator0001/OneTeslaRevived/main//user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI3OTI0LCJwdXIiOiJibG9iX2lkIn19--3d1598bbadbf5feb130f8faba40535f8200ca32e/image.png)

# 2026-05-27: 3/26/2026 6 PM - Unfortunately couldnt get prototype to work rn

**Total time spent: 10.0h_**

_Time spent: 10.0h_  

So its a harsh time now that i ran out of capital rn for buying UCCs and stuff to continue this build further, so far i built it from scrap I extracted and a pcb i saved up for, now I am planning a new design with better stuff for proper operation.
The problem is mainly in LV side and its due to use of cheap stuff that is breaking like the fiber receiver is toslink stuff not made for this, so I will figure out stuff.
I also keep wasting soic stuff since no hot air so i am working around it with stove tops!
As of now the project physically is on hold but i am continuing to improve stuff and making better pcb design for future product, a good kit for the aspiring maker!
![01e0b237-75f5-40ce-84f3-abb205192cd5](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI3Nzc5LCJwdXIiOiJibG9iX2lkIn19--70916a8ba013fd0404c04b67a851fac62bfaba3c/01e0b237-75f5-40ce-84f3-abb205192cd5.jpg)

# 2026-05-27: 3/23/2026 - LV system works! Board is ready for power on

**Total time spent: 12.0h_**

_Time spent: 12.0h_  

The board is finally ready for power on. I just have to make a little daughterboard for the fiber receiver since the pinout for the IF-D95T is NOT the same as the receiver I used in terms of pin order and also pitch is different. 
and also wanna put it in my wood enclosure I made out of MDF that I will put some metal tape on it inside.(foreshadowig, thats not good)
I am very excited for when I finally power up my coil hopefully by this month end but the circuitry perfectly works! i am now focusing on modelling up a good enclosure for it.

Once I am able to work again I will fire up the coil in my lab! Till that I plan on making the final touches like the topload too, which I have already done.
![IMG_20260318_142114](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI2MjY3LCJwdXIiOiJibG9iX2lkIn19--da982964b55d03b5220528ec2f81b61627c1520a/IMG_20260318_142114.jpg)
![IMG_20260318_142028](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI2MjY1LCJwdXIiOiJibG9iX2lkIn19--fb44cb7b298401d991bd27173c8bff29dacf6687/IMG_20260318_142028.jpg)
![IMG_20260318_143613](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI2MjY2LCJwdXIiOiJibG9iX2lkIn19--fe533070d224d97105cee222a4686d23c132a372/IMG_20260318_143613.jpg)![IMG_20260318_142136](https://raw.githubusercontent.com/ARCreator0001/OneTeslaRevived/main//user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTI2MjY4LCJwdXIiOiJibG9iX2lkIn19--4b660efa20bd054b79a20e0f213ef02716a06ff2/IMG_20260318_142136.jpg)
[Video](https://photos.app.goo.gl/v6eqWWCjtmWWdwZM6)

# 2026-05-27: 3/15/2026 - HV system in check, LV system some changes

**Total time spent: 9.0h_**

_Time spent: 9.0h_  

I was really nervous powering up the HV section from mains the first time, so i used few transformers and appled about 125VAC rms to the input first then checked inrush, insulation,etc then sent 250v the absolute max ac input for ideal operation i designed for and it held up! I finally decided to use mains wall power and was really nervous about popping breakers, and thankfully with help fo current limit inrush light bulbs in series, the inrush problem is solved and it can handle mains input![https://photos.app.goo.gl/hGtiFCkLXZJ6VfBP6](https://raw.githubusercontent.com/ARCreator0001/OneTeslaRevived/main/url)

# 2026-05-27: 3/1/2026 - Going to test HV system,LV is working

**Total time spent: 6.2h_**

_Time spent: 6.2h_  

I have assembled with minimal parts and the logic circuitry seems to work and soon after i get more components i have ordered i will assemble it fully and test it!
 ![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTEzMTg4LCJwdXIiOiJibG9iX2lkIn19--0772722897c1f4060cb3dbd97c9887763a02d65a/image.png)
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTEzMTg5LCJwdXIiOiJibG9iX2lkIn19--4f8bf887256adda7579aba2af71f0bd7b6b4b3a7/image.png)

# 2026-05-27: 2/26/2026 - Have made improvements on PCB

**Total time spent: 5.5h_**

_Time spent: 5.5h_  

![PCB_oneteslabigv2_2026-02-26](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTExNDkyLCJwdXIiOiJibG9iX2lkIn19--9e47264eba2f14a0212ecb9e8245d879355a0301/PCB_oneteslabigv2_2026-02-26.png)
I had already made a prototype pcb design before this journal and today I worked on more EMI stuff etc and making the board better and also changing its size and arrangement of components to fit my large bus half bridge capacitors that didnt quite fit when i printed out a 1:1 of the pcb design, my 1200uf caps are simply too huge lol, I am still working on it hopefully come to a final better version and one day i want to make some good DRSSTC arcs! The schematic needs some work but mainly focusing on the PCB[PCB_oneteslabigv2_2026-02-26](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTExNDkwLCJwdXIiOiJibG9iX2lkIn19--5cb27e5decc3846e6940dd1a304858199108d9cb/PCB_oneteslabigv2_2026-02-26.pdf)[OBJ_oneteslabigv2_2026-02-26](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTExNDkxLCJwdXIiOiJibG9iX2lkIn19--09f68c00a8a9d8e608b6d39ca98d0a7b2a692b57/OBJ_oneteslabigv2_2026-02-26.zip)
[Schematic_OneTeslaTSRevived_2026-02-26](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MTExNDg5LCJwdXIiOiJibG9iX2lkIn19--7f383ff59e148cee9d6170f9b7a190a34bc088f6/Schematic_OneTeslaTSRevived_2026-02-26.pdf)


