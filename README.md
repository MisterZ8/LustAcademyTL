# Summary

- [Welcome to our family!](#Welcome-to-our-family)
- [How to work with RenPy](#how-to-work-with-renpy)
- - [Special symbols](#special-symbols)
- - [Variables](#variables)
- - [Quotations](#quotations)
- [How to work with GitHub](#how-to-work-with-github)
- [How translations were done before me?](#how-translations-were-done-before-me)
- [What to translate](#what-to-translate)
- [Character names](#character-names)

# Welcome to our family!

I'm really happy that you want to help with translations!

I'm making this document because I'm getting some number of requests like this and although I'm super happy to get you help, I can't manually copy paste all the translated lines. So we have a process and here I'm going to explain how it works.  
First of all, translation are done with the [Ren'py](https://www.renpy.org/) framework.

Important
--------
Do not translate **Game name, Characters names, Places names (like Cordale), Variables**

if you feel something does not need to be translated, such as technical text

**old "Tab"**

**new ""**

Just leave the fields blank.

**DO NOT EDIT "old" TEXT, ONLY "new" ONE!**

# How to work with RenPy

RenPy is quite simple. Every scene in the game is translated in a separate file like "d04s03.rpy".  
Such file looks like this:
![image](https://user-images.githubusercontent.com/79453594/151206128-e7c724dc-f4a1-44bf-b898-1d1991bf6bc0.png)

This example is already a translated file. In the file, you would see all the lines of the text mentioned in English, and right after it the language that you are translating to.

![image](https://user-images.githubusercontent.com/79453594/151206419-6e75269a-bb1a-481b-9153-790fa30cb807.png)

What type of things you might see?

Special symbols
----
![image](https://user-images.githubusercontent.com/79453594/151206700-71746758-5fc8-48d8-9281-af3087f8ae46.png)

Those are special action symbols. They need to stay the same preferably in the same logical place. For example, this symbol is making a pause in the dialog.  
Also `{i}...{/i}` is to make text cursive.

![image](https://user-images.githubusercontent.com/79453594/151210790-06b79fd2-e2c6-423c-8b18-0df8cdfc9f63.png)

And you see "%%" like here:

![image](https://user-images.githubusercontent.com/79453594/151210876-d21ef443-69bf-4ebf-a957-5ecea9a8ff61.png)

It has to be translated like that. "%" is a special character.

## Variables

![image](https://user-images.githubusercontent.com/79453594/151210978-ae9c96c7-5041-4644-a025-1644ac4794a9.png)

Those are used to be replaced with something. In most cases that is character names. (In this case, it will be replaced with the name that player selected for him main character).

**Don't translate variables and just leave them.**

Usually variables looks like: [Name], %s , #weekday, {#weekday_short}

**Example:**

 old "{#weekday_short}Tue"
 
 new "{#weekday_short}Вт"

## Quotations

![image](https://user-images.githubusercontent.com/79453594/151211042-a4ad8faf-36c4-403b-ba5c-16b3dd6d84e8.png)

Those are quotes that need to be escaped to work properly. Be very careful with those. The wrong quote can break the whole game.  
You can read more about RenPy syntax here:  
[https://www.renpy.org/dev-doc/html/translations.html](https://www.renpy.org/dev-doc/html/translations.html)  
If there is something not clear reach out on our [Discord](https://discord.gg/tjNvTcew) on the #translations channel (ask [Majesti](https://discordapp.com/users/Majesti#4005) if you need access). 

# How to work with GitHub

[Github](https://github.com/) is a code management platform that is using Git.

First of all, you would need to create an account on Github (if you don't have one) or you can create a fake one just in case you don't want to use your professional one. Go here and create it: [https://github.com/](https://github.com/)  
Once you have an account you can open on the repositories that we have for translations:

**Translations for Lust Academy - Season 1** - url: [https://github.com/MisterZ8/LustAcademyTL](https://github.com/MisterZ8/LustAcademyTL)

You should see this:

![image](https://user-images.githubusercontent.com/79453594/151213502-adc127ac-02a7-4c98-8929-86c2df9835f1.png)

When you would open the language that you want to translate(if your language is not in the list you need to contact us and we will create it) you will see next:

![image](https://user-images.githubusercontent.com/79453594/151214260-e2844897-ce09-4807-b80c-ae4a81494ef2.png)

![image](https://user-images.githubusercontent.com/79453594/151214320-fc8468b1-2a4e-4779-95b9-a12ea1c2b9f6.png)

![image](https://user-images.githubusercontent.com/79453594/151214825-17511157-4ac9-4725-a276-e601aa98a990.png)

To start editing the file:

![image](https://user-images.githubusercontent.com/79453594/151214941-ffd28507-433e-41ee-8fdb-08fd4772f6af.png)

You will see the texteditor:

![image](https://user-images.githubusercontent.com/79453594/151215094-1f87dce8-728c-455e-963e-68516a193207.png)

You make changes:

![image](https://user-images.githubusercontent.com/79453594/151215201-685efc9c-67e0-4dcd-aa0c-b6ead15662bf.png)

Important
--------
Do not translate **Game name, Characters names, Places names (like Cordale)**

if you feel something does not need to be translated, such as technical text

**old "Tab"**

**new ""**

Just leave the fields blank.

**DO NOT EDIT "old" TEXT, ONLY "new" ONE!**


To save (propose) your changes:

![image](https://user-images.githubusercontent.com/79453594/151215261-16e4313b-5169-4ea1-abd1-8d636adde572.png)

You will see the screen with what you changed. And you need to create a Pull Request to send this change to my translation repository:

![image](https://user-images.githubusercontent.com/79453594/151219664-f1c5b898-624e-4f3e-859a-ecbfe33a7eeb.png)

And one more step:

![image](https://user-images.githubusercontent.com/79453594/151219861-4f112957-c354-4b89-a6c9-a85194a0033b.png)

Now it is done. You can see the number of opened pull requests:

![image](https://user-images.githubusercontent.com/79453594/151220457-fe26de9f-dbae-4cfa-a2cc-550eaa04f145.png)

If you already created a pull request and you want to edit it you still can change a file there:

![image](https://user-images.githubusercontent.com/79453594/151221347-1893e174-694a-4654-97ac-bb8b007ffe0d.png)




