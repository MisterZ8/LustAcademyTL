<
    old "Self-voicing disabled."
    new ""

OR

translate chinese start_input_2_a0ecd7a8:

    # ch_Name "My name is [Name] [Surname] and I am 18 years old."
    ch_Name ""




block:
    # ch_Name "My name is [Name] [Surname] and I am 18 years old."
    ch_Name ""
result:
    # ch_Name "My name is [Name] [Surname] and I am 18 years old." 
    ch_Name "************ [Name] [Surname] *********************."

block:
    ch_Name "Good day, miss.{w} [Name] [Surname]."
result:
    ch_Name "***************{w} [Name] [Surname]."

block:
    ch_Name "{i}(I am 99%% sure Don and {b}Olivia{/b} know what's going on...){/i}"
result:
    ch_Name "{i}(**** 99%% ************ {b}******{/b} *************...){/i}"

block:
    "{#month}June"
result:
    "{#month}******"

block:
    "Load slot %s: [text]"
result:
    "********* %s: [text]"

block:
    Jacob "Well, \"just [Name]\" — you are a wizard!"
result:
    Jacob "****, \"**** [Name]\" — ****************!"
	
>