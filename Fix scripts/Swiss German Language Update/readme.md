# Swiss German Language Update

This Fix Script replaces all "ß" special characters generated by the German language plugin (com.snc.i18n.german). 
In Swiss German, this character does not exist and must be replaced with "ss". Currently, unfortunately, there is no dedicated Swiss German language plugin available. 

### Instruction

As a prerequisite the "regular" German language plugin (com.snc.i18n.german) must be installed. 
After that the Fix Script can be executed, replacing the German special charactrer "ß" in the following relevant language tables with "ss": 
sys_translated, sys_ui_message, sys_documentation, sys_choice and sys_translated_text. 
I would recommend to run the Fix Script in the background, since the execution might take some time. 


### Benefits

- Quick fix to automatically replace all customer/end user visible special characters "ß" 
