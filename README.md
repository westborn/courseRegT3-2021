# U3A Course Management for Term3 2021

1. Create new repository

```
    create a new empty repository on github.com <reponame>

    mkdir <reponame>
    touch README.md
    git init
    git add README.md
    git commit -m "Initial Empty Setup"
    git remote add origin git@github.com:westborn/<reponame>.git
    git push -u origin main
```

2. Make a copy of Google Drive files to the new 'Term' folder

```
    files to copy/move examples:
      Term1-2021 - U3A Course Registration (Sheet)
      Term-1 Enrolments (Form)
```

3.  Update clasp.json to use new copy from above

    Open the spreadhseet from above.  
    Go to the "Tools" menu and select <> Script Editor  
    This opens the script in a new window.  
    Update the name of the script to reflect the new Term/Year  
    Copy the URL of this script from the address bar.

    Examples

    ```

    Sheet
    Script
    Form

    2021-Term3
    https://docs.google.com/spreadsheets/d/19mwP2JF7BMGLfO_JCtFGyWDsqSTufjeFJIkGuFMOKds/edit#gid=0
    https://script.google.com/home/projects/1UPG0wEfoggztdstD6A0UqXP3DnfZ-sg2Rl8uUDrDoXX3zZUV6Vj3Syr5/edit
    https://docs.google.com/forms/d/1lY5zY0TTpuxb3qaE3eBnkfxCDV0mOQbyH_6y6HBr4Do/edit


    2021-Term2
    https://docs.google.com/spreadsheets/d/1Xntdq_G8xE8fnw7P48sLK41ZtDUjDLVaeX97e1AWoUk/edit?usp=sharing
    https://script.google.com/home/projects/1p5vCRk2L1GMHU3dQAnanpozSN7Amj0SZRJ2oqwgBT-VSlBE6TuR8wTDO/edit

    2021-Term1
    https://docs.google.com/spreadsheets/d/1w81gWg61vwAUmwY3W05Oh6avFe3GSuUGmjXR5u7p6rk/edit?usp=sharing
    https://script.google.com/home/projects/1f4jdAOkHvgcFj1C12eR17WRKYN2kzLV1p5CgQlZQJ3nsRvWS5hXTFuva/edit
    ```

    Update the entry in clasp.json with the new script ID

4.  Update Enrolment form linking

    Open the form from above  
    Select "responses"  
    Use the "3 dots" and select response destination.  
    Select "Create a new Spreadsheet"

    Copy the URL from the form addres bar  
    Update the 'Code.gs' file to contain the correct file ID for the new Enrolments form
