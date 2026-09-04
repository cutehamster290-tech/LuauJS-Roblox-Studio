# LuauJS-Roblox-Studio
An Open-Source Roblox Studio Plugin

## If you want to Install this Framework Outside from Roblox Studio checkout https://github.com/cutehamster290-tech/Luaujs-Framework-NPM

# How to Install
- Close Roblox Studio if it is Opened
- Install the Plugin here: https://create.roblox.com/store/asset/86432309809302/LuauJs
<img width="1370" height="873" alt="{A0EB30EE-1CCD-4CC4-A3E7-51311905521E}" src="https://github.com/user-attachments/assets/c10ed4fe-5291-4a1e-85da-c33e0fb34990" />
- Open Roblox Studio and open any Experience
- Check in Plugins Tab if there is the LuauJS Framework
<img width="1919" height="210" alt="image" src="https://github.com/user-attachments/assets/dbd2dacd-c561-42b8-a1c2-add71c4cae93" />
- If there is the Plugin, then go ahead to the **How to Set Up** Part Below.
- If there isn't the Plugin, then open the Toolbox:
<img width="1911" height="204" alt="image" src="https://github.com/user-attachments/assets/d67fcee3-cdc5-4e3f-b974-5abe776bc442" />
<img width="273" height="238" alt="{BCEC6B35-E287-4838-B6FA-25F61582CBD4}" src="https://github.com/user-attachments/assets/fcc37474-935f-4365-a8ca-4c7c568cf244" />
- Go to Inventory
<img width="1078" height="783" alt="image" src="https://github.com/user-attachments/assets/32913066-869e-4822-b146-9393d5b68160" />
- Choose the Right Category
<img width="1062" height="814" alt="image" src="https://github.com/user-attachments/assets/d19392ed-95a7-4162-9c9b-30597bc20263" />
<img width="166" height="284" alt="{EA6F44B4-0F33-4C2A-B467-B7DC4ACA78CC}" src="https://github.com/user-attachments/assets/45913aa2-7f6f-4bba-9451-2e18889a6b3c" />
- Search for LuauJS Plugin, and Click on it, if there isn't it, it means you have to re-download it from https://create.roblox.com/store/asset/86432309809302/LuauJs and go back to the start.
<img width="1105" height="733" alt="image" src="https://github.com/user-attachments/assets/ef2cac37-260f-44c6-a9a1-b849429b6f88" />
- Click install and close toolbox
<img width="845" height="729" alt="{EADB5791-56C5-46CD-A78D-F127D4C60C74}" src="https://github.com/user-attachments/assets/37804db5-cdcd-48fc-ad0f-3146097cfc1a" />
- Search again the Plugin in the Plugins Tab, if you found it, you can go in the **'How to Set Up'** Part Below!

## How to Set Up
Choose a Place where to Import the Framework, by clicking in the Explorer, i suggest **ServerScriptService**
<img width="496" height="434" alt="{ACE1B492-8656-4D4B-95EA-040013A57191}" src="https://github.com/user-attachments/assets/f0cf5362-4da0-4beb-8ea2-21cb9995093f" />
Once Chosen, Click on the LuauJS Plugin Button: <img width="1919" height="198" alt="image" src="https://github.com/user-attachments/assets/ddbf95a8-dcf3-46bc-b62a-501d19460045" />
And here you go! you Imported the Framework where you wanted!
<img width="422" height="59" alt="{FFEBD6F4-BD1C-4F09-BF11-A3E77EE18416}" src="https://github.com/user-attachments/assets/a83d4e2d-3d4c-4104-86f3-f5da613772df" />

# Documentation
So lets get Started with the Actual Framework, you can rename the folder i you want to give a Name to your WebPage.

You will see a folder and a script: <img width="502" height="101" alt="{29B672CD-FB36-4EAE-839F-8EDA8F3721D0}" src="https://github.com/user-attachments/assets/d99e6257-3c9e-4cd1-a027-49a4e30b9273" />
we will work with the Script, open it, and you will see something like this: <img width="879" height="309" alt="{41A44CEF-F131-4765-A7C2-7335E9CA7095}" src="https://github.com/user-attachments/assets/7355914c-eefd-47fe-93ac-c948726d518d" />

Now, lets Code a HTML Web Page using this Framework, we will first use the `Element.new(ElementName: string): Element` function that asks for a name you want to give to the Element, you can see all the Names Available in the Elements Module Script inside Elements which is inside the Modules: <img width="487" height="154" alt="{5BBB1A2D-2C92-44E5-843D-BD8F811A5B48}" src="https://github.com/user-attachments/assets/19547a10-eaad-4694-a081-848ff0d24f27" />

If you want add more Elements, just go to this ModuleScript and add as many Elements as you want<img width="961" height="176" alt="{6FF864B9-2E0C-4A07-9C44-2BE2701C348F}" src="https://github.com/user-attachments/assets/0bfbc607-6a14-48dd-abf5-a3583a5e66ef" />

Now we still need to see some other thins, like the Element Methods, such as:
- `element.addAttributes(Attributes: {[string]: string|{string}})`: adds some attributes inside the element, like 'Id', 'Class' and all the Attributes and HTML Element can have (you can also add not Existing Attributes)
- `element.setName(Name: string)`: which changes the element Name, so like if your element is a div, you can change it to a p or a h1 and so on.
- `element.View(): string`: this Function will return the element's InnerHTML as a String, so you can see if your element got generated Correctly!

Now this Framework is not Done, not even the NPM One, i am Still Updating it to make it Powerful, so that you can add Code inside it, and much more, you can also give me Ideas!
