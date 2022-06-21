# Notepad++ User Defined Language files for Telosys

Notepad++ "User Defined Language" (UDL) allows to define rules for specific languages
(keywords, comments, etc)
See https://npp-user-manual.org/docs/user-defined-language-system/ 

The following files contains UDL for Telosys files
- **telosys-xx-vm-xxx.xml** for **".vm"** files (templates files)
- **telosys-xx-entity-xxx.xml** for **".entity"** files (entities in DSL model)

### UDL file installation

In Notepad++ **main menu** :  
   **Langage > User Defined Language > Define your language...**

For each UDL file to install import the UDL file 

   - Button **[ Import... ]**
     - Choose an ".xml" file provided by Telosys 
     - If all goes well the message "Import succesful" is displayed  
       
If a previous version is already present remove it before import

Open or re-open files with ".entiy" or ".vm" extension to check the coloration. 



   
### UDL file for ".entity"

**Keywords list :**
 - Keywords1 : Types : int, string, etc (prefix mode = false)
 - Keywords2 : Annotations : @Id (prefix mode = false)
 - Keywords3 : Annotations : @FK (prefix mode = false)
 - Keywords4 : Annotations : all annotations without value (prefix mode = false)
 - Keywords5 : Annotations : all annotations with value (prefix mode = false)
 - Keywords6 : Tags : starting "#" character with prefix mode = true (for any tags)



   