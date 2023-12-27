# Removable-Gate-GCC

This is a collection of custom gamecube controller files made to be resin printed. These files feature a variety of mods. Removable Gates, Digitally Notched Gateplates, Double Z, USB-C, Metal Threaded Shell Inserts, and a Fully Parametric Custom Notch Builder Tool!

The release contains F3D files with the STEP files for each part as well as the Notch Builder. It also includes a guide to using the Notch Builder and a guide on how to properly export files from Fusion360

The main branch contains individual STL files for each part, ready to be printed! (for those who dont have fusion360)

Parametric Notch Builder Tool by Bibben
https://github.com/B1bben

PhoZL and OlyU boards can be found here:
https://github.com/sean44104

USB-C plug provided by Rana Labs
https://twitter.com/rana_labs_/status/1646009376925261824

This design is based on, and uses the full oem gcc step file made by GearHawkStudios.

**Scroll to the bottom of the readme for an ordering guide and information on each JLC material (WIP) :D**

NOTE: This project is a work in progress! There are changes and improvements I want to make. I will list them here:

1. For now, please do not order the "ShellScrewMod" files. Just ignore them for now. After further IRL testing, I found the design to be faulty due to resin shrinkage. I want to redesign this system so it can be perfect :)

2. You may notice that your button wells are a bit wide. There is a larger gap between the walls of the button holes on these shells than on an OEM gcc shell. I am aware of this problem, and I have already developed a fix! it will be included in the next release when that is ready. If you want to try it early, dm me. Just keep in mind that if you are ordering transparent shells in 8001 translucent oil sprayed resin, the material is a bit thicker than the others and the tolerances change. For this reason, the wider button wells might actually be a good thing if thats the material you are going for. Things to think about...

3. Currently, the USB-C hole plug (BjartPlug) is a bit small. A lot of USB-C cables wont fit in there. Im working on a fix! I need to redesign that part a little to make it bigger while still making sure its nice and pretty.

![ControllerCollection](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/image1.png)
![NotchBuilder](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/image2.png)


### Removable Gates and Notched Gateplates
![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/rg1.png)
![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/rg2.png)

### Double Z
![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/dz1.png)

### UCB-C
![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/usbc.png)

### Notch Builder Tool
![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/pmg.png)

# JLCPCB Ordering Guide
Go to https://jlcpcb.com and click on "Order now" (make sure to sign up and create an account!)

![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC1.png)
![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC2.png)

Go to "3D/CNC" and then drag and drop your STLs into the "Add 3D Files" box of the "3D Printing" section

You can do multiple files at once! (Up to 10)

![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC3.png)
![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC4.png)

Once your files are finished uploading, select the type of 3D Technology and Material you want

My personal favorite for the shells currently is SLA(Resin) and Imagine Black with the default surface finish (sanding, general sanding)

![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC5.png)
![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC6.png)

For "Product Desc" select "DIYEntertainment" and then "Game controller Enclosure"

![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC7.png)

Once you are done with the settings on each individual STL uploaded, go ahead and "SAVE TO CART"

![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC8.png)

Lastly, "Secure Checkout" and put in your payment information! Shipping can be a lot, be prepared for that

![image](https://raw.githubusercontent.com/sean44104/Removable-Gate-GCC/main/Images/JLC/JLC9.png)

# JLCPCB Ordering Guide

I am currently writing this up, its a work in progess. Eventually I hope to have useful documented information on each material available so that you can make the best decisions possible when ordering parts. Give me time!





# Important information for working with resin printed parts, please read:
<details>
  <summary>Click to expand</summary>

# Important information for working with resin printed parts:
 
Resin does not melt. Do not try to melt it. It will begin to disintegrate instead of melt. With that being said, I do believe that you can soften resin with heat. If something is slightly warped, you can run it under hot water and gently bend it.
 
Resin is brittle. If you try and cut it with flush cutters, it is likely to break off in a larger piece than you anticipated. I recommend sanding it and being gentle with your physical modifications of the material. If you drop it, it may break. Screw posts especially end up being very fragile. This is why i designed the metal threads mod. that way, you dont thread into it. I left the back shell as it is though, so you will have to thread there for the trigger guards. I didn't do metal threads here because the posts are so small that I couldn't find a good part for it. Also, the trigger guards are less important than the shell screws. Lastly, I have never had the trigger guard screw posts actually break in any way.
 
White resins will yellow when exposed to UV (sunlight) over time. If you order a part in LEDO6060, expect it to be a bit yellowed in about 6 months.
 
While it is likely not a huge deal, you should probably try and minimize the amount of UV exposure your parts get. Keep them out of direct sunlight. Just like most materials, including plastic, resin never stops reacting to uv light, even when “fully cured” and solid. With enough UV light, it will even begin to degrade. Clear coating your parts would probably help with this. 
 
# Important Note About Resin Safety
 
### DISCLAIMER:
I am not a professional on this subject. Information on this topic tends to be very unclear and vague. Please do your own research and carefully vet the people who you get your information from. I have done my best to do good research on this and come to my own personal conclusion. The following is my honest opinion
 
SLA UV Resin is initially a liquid. When exposed to UV light, it cures and hardens into a solid. When UV Resin is in its uncured liquid state, it is toxic. It is not safe to touch with bare hands or breathe in its fumes. This is all very important to think about when doing your own resin printing. I own a resin printer and I do my best to take the proper safety precautions when using it. I use gloves when working with it and I wear a mask. I clean the parts with isopropyl alcohol and fully cure them with a UV lamp. When you get a part from JLCPCB, it is complete. Fully cured, solid, perfect, ready to go. But does that mean that these parts are 100% safe? From my own research, I am of the opinion that the safety of UV resin is like an asymptote. As it cures, it becomes safer and safer, to the point of being mostly safe when fully cured. But does it ever reach a point of being absolutely 100% without a shadow of a doubt safe? I don't know, and I don't think anyone else really knows either. I can not responsibly make the claim that it is absolutely safe, because I don't know. The jury is very much out on this. The long term risks of exposure to uv resin are not fully understood due to a lack of research. The long term risks of exposure to fully cured uv resin in the hands is *even less understood*
 
 
The safety of UV resins also likely depends on the resin. For example, UV resin is used in the medical field. SLA parts are used for tissue contact medical device applications. Is the resin that JLC uses as safe as the resin used in the medical field? I can not say for sure. I have put in an inquiry to JLCPCB for a Material Safety Data Sheet on their different resins. They were only able to provide me with one for their LEDO6060 resin. Furthermore, the information provided in the MSDS is clearly targetted at the uncured version of the resin. This is because safety precautions are most important when working with the material in the production phase. The MSDS is more made for *them* while they make the parts, not really for the end user. This makes finding information about the safety of these parts even more difficult.

If you would like to read the MSDS for yourself, here it is. Let me know if you find anything useful! https://cdn.discordapp.com/attachments/684468475464384723/1189654549963743292/MSDS_Ledo6060.pdf?ex=659ef323&is=658c7e23&hm=a3720d4aae3bad57797445d258488913121f4ed673805fa01456909fc8037068&
 
Here is a link to a research paper done about this subject:
https://pubs.acs.org/doi/10.1021/acs.estlett.5b00249
Here is a link to their results:
https://pubs.acs.org/doi/suppl/10.1021/acs.estlett.5b00249/suppl_file/ez5b00249_si_001.pdf
 
In this publication, the researchers tested multiple different stages of UV resin cured-ness on zebrafish embryos. After printing a part, it comes off the printer wet and very soft (not fully cured whatsoever). you *must* clean it and cure it. The researchers did a total of 5 resin print tests. 4 of the 5 used parts that were only cleaned, and not fully cured. Only their 5th test was cured. Interestingly, you can see from the graphs that while the 4 uncured parts were extremely harmful to the zebrafish embryos, while the 5th test was either significantly less harmful or indistinguishable from the control test, depending on the test. This clearly shows that curing UV Resin makes it drastically more safe. Furthermore, you are not a zebrafish embryo
 
With all of that being said, I personally use these parts. I have for over a year and I will continue to use them. I am not personally particularly worried about my resin controller. If you feel differently about this however, here are some steps you can take.
 
Choose a different material
JLC has many different types of 3D Technology beyond just SLA Resin! Instead of SLA Resin, you can go for either SLS Nylon or MJF Nylon. These materials are 100% safe to use and touch.
 
Paint or Clear Coat your resin
By putting a layer between you and the resin, you can make it for sure safe to touch. If you are especially worried about the safety risks of SLA Resins, but still want to use them, or if you are planning on selling resin printed parts at large scales, I would recommend that you hit them with a little clear coat
 
When researching the safety of UV resin for yourself, please be aware that most of the information online is aimed at people who resin print themselves. This environment has safety hazards, and this is the context that discussions about safety are usually in. Please do not be irresponsible and spread misinformation about the harmful effects of cured resin parts based on the information you read that was likely referring to liquid or uncured resin parts.
</details>