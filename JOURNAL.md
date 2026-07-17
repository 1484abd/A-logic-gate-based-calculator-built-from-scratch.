---
title: "calculator using only logic gates"
author: "abderrhamen"
description: "it works its a 8 bit multiplier and 16 bit adder and sub"
created_at: "2026-07-16"
---

# july 16: i finished it all(update not everything"
so we go from the start of the project 

<img width="688" height="360" alt="لقطة شاشة 2026-07-16 172900" src="https://github.com/user-attachments/assets/04fe7859-13aa-41f5-94dd-a40b87d42339" />

this is the first full adder in this project i made it took me 5 min cause i built one before and we all know what happens after

we take that full adder we arange 4 now we have 

<img width="480" height="464" alt="لقطة شاشة 2026-07-16 172912" src="https://github.com/user-attachments/assets/43e2eb68-329e-4f5a-ae56-870bbf433e61" />
a 4 bit adder

and after that ofc we have to take the 4 bit adder and arange 2 of them and build a

<img width="812" height="602" alt="لقطة شاشة 2026-07-16 172926" src="https://github.com/user-attachments/assets/1e8c6071-0ccc-474b-93c6-24cbe90b1921" />

8 bit adder

then we just do the same thing with 4 bit

<img width="918" height="552" alt="لقطة شاشة 2026-07-16 172942" src="https://github.com/user-attachments/assets/6321c759-a24c-4c30-84c2-43f226cc87ba" />

and we have 16 bits adder and subtracter. we can make it 32 64 128 bits but lets stay with that

now we make the multiplier this is where i really was going to give up so the 4 bit one is easy it took me like 30 min. its just 3 4bit adders and some and gates:
<img width="1322" height="558" alt="لقطة شاشة 2026-07-16 173027" src="https://github.com/user-attachments/assets/d8f3c0ec-e2aa-4c8a-8f0c-da83ed628f50" />

and the 8 bit one is super hard i never built one i just started builing things with logic gates 2 weeks ago and now i have to face this monster:

<img width="516" height="387" alt="images (1)" src="https://github.com/user-attachments/assets/86242e1d-6dd9-4dcc-a1be-417263e713e2" />

i want to say to the one who made this schematic 'why the hell you didnt name the inputs and outputs: it took me an hour even lapse thought i wasent on the pc 

i built it normally first

<img width="780" height="470" alt="لقطة شاشة 2026-07-16 173129" src="https://github.com/user-attachments/assets/d3adb371-32c2-457a-830e-b3f58d334da1" />

but then i tested it

<img width="910" height="448" alt="لقطة شاشة 2026-07-16 173149" src="https://github.com/user-attachments/assets/6deb4788-a75f-4304-9b44-ca83829d530e" />

and guess what that calculation was wrong actually it gave 4*4 is 4096 so i was "WHY!" for like 30 min i was staring on the computer:

<img width="1434" height="606" alt="لقطة شاشة 2026-07-16 173248" src="https://github.com/user-attachments/assets/972e0dae-d202-4fe1-9832-9508f5e53765" />

i even asked gemini:

<img width="1436" height="646" alt="لقطة شاشة 2026-07-16 173207" src="https://github.com/user-attachments/assets/64f25f6b-0c3b-41ee-8c8e-3c587c62d70a" />

and it told me oh you are not using the RCA adder or whatever i spent 20 min just trying to figure out whats the difference between it and a normal 8 bit adder:

<img width="1432" height="672" alt="لقطة شاشة 2026-07-16 173300" src="https://github.com/user-attachments/assets/9bf4a9cf-9b84-44c6-93c7-427b3a66323a" />

it was the image reference i was using the inputs where inversed in it and it worked you don't know how happy i was.

<img width="1438" height="594" alt="لقطة شاشة 2026-07-16 173331" src="https://github.com/user-attachments/assets/f12c0685-621e-48fb-bd64-6758a59ec082" />

i just have now to connect every thing together.

<img width="1408" height="592" alt="لقطة شاشة 2026-07-16 173418" src="https://github.com/user-attachments/assets/b570bb89-2d82-410e-9a48-d507494348c2" />


but i forgot my way in making negative numbers (i call it my way knowing its wrong at least you can have the full 16 bit in negative)

<img width="804" height="602" alt="لقطة شاشة 2026-07-16 173457" src="https://github.com/user-attachments/assets/c12603ad-5d48-4ac7-becd-8f391b2dc320" />

then i finished connecting the outputs:

<img width="1416" height="612" alt="لقطة شاشة 2026-07-16 173525" src="https://github.com/user-attachments/assets/dec32de0-c110-4fd0-847a-fb0d79f1edae" />

and then the inputs:

<img width="730" height="598" alt="image" src="https://github.com/user-attachments/assets/b7de3264-22a6-4bc2-95dd-74a51b90f1c4" />

then i tested it:

<img width="1440" height="604" alt="لقطة شاشة 2026-07-16 173618" src="https://github.com/user-attachments/assets/9d4208d1-051f-4812-b416-320bc971dfe1" />

and it works

i just couldent have the tree for it :

<img width="432" height="136" alt="لقطة شاشة 2026-07-16 173636" src="https://github.com/user-attachments/assets/b841b950-174f-4efa-bf70-08ab60a8e8a5" />

and done.thanks for reading this

**Total time spent: 4 hours**

okay same day new problem i have to make a playable one so i will use circuitverse to make it
so i started like the same but this website is so hard to use:
so a 1 bit adder:

<img width="1434" height="642" alt="لقطة شاشة 2026-07-16 190409" src="https://github.com/user-attachments/assets/eee53ec5-d834-4362-9dc9-5761cee32962" />

a 4bit adder:

<img width="572" height="550" alt="لقطة شاشة 2026-07-16 192515" src="https://github.com/user-attachments/assets/d70ad8d0-f67c-4495-8edb-baa4b2042997" />

a 8 bit adder:

<img width="1438" height="688" alt="لقطة شاشة 2026-07-16 200744" src="https://github.com/user-attachments/assets/b4c24e55-807b-4df9-8693-2bfd7aee45f8" />

a 16 bit adder:

<img width="452" height="564" alt="لقطة شاشة 2026-07-16 213335" src="https://github.com/user-attachments/assets/a6fc422b-87b7-48dc-812b-656676cc8f98" />

a 4 bit multiplier:

<img width="1434" height="690" alt="لقطة شاشة 2026-07-16 213314" src="https://github.com/user-attachments/assets/6e5efb85-b351-4378-a6e9-ab1c6db11f12" />

a 8 bit multiplier:

<img width="780" height="534" alt="لقطة شاشة 2026-07-16 213325" src="https://github.com/user-attachments/assets/14b74c6c-b87c-4dd4-806a-14f2285fdb1a" />

as always i was going to give up here.

any ways i just have to assemble everything i will do it tommorow at the last day there is still 24 hours i belive

# july 17: i finished everything
ok good today was the easiest i just built the negative numbers:

<img width="626" height="496" alt="لقطة شاشة 2026-07-17 144316" src="https://github.com/user-attachments/assets/bf07e6bb-7dae-474f-8961-508f1b9951dc" />
<img width="418" height="410" alt="لقطة شاشة 2026-07-17 144323" src="https://github.com/user-attachments/assets/f979e08c-6882-45b8-99fd-b905c365f9a0" />

then done all finished:

<img width="908" height="540" alt="لقطة شاشة 2026-07-17 144338" src="https://github.com/user-attachments/assets/0a31845b-ddc7-46d7-922c-44c9c84d3dec" />
