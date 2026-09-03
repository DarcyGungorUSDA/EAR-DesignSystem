# Background

This folder contains the XML code for the `FNA_EAR_2026.hmx` Microsoft Office theme file. Microsoft Office themes are customizable combinations of fonts and colors that can be applied across Word, PowerPoint, and Excel. Using a theme file is an easy way to make reports, presentations, tables, and figures with a consistent look and feel.

A `.thmx` file is an XML-based file like `.docx`, `.pptx`, and `.xlsx` files (see https://support.microsoft.com/en-us/office/vba/open-xml-formats-and-file-name-extensions). All of these file types are actually zipped collections of XML files. 

You can create, modify, and save `.thmx` files within Word (Design tab), PowerPoint (Design tab), and Excel (Page Layout tab), but modifying the underlying XML gives an organization more options. For our purposes, a benefit is expanding the typical 10-color palette by up to 50 additional custom colors (see https://www.brandwares.com/bestpractices/2015/06/xml-hacking-custom-colors/). In a research office like ours, the expanded color palette is especially useful for data visualization.

# Methods

1) I saved the `.thmx` file from a recently created Word template (Design tab, Theme dropdown, "save current theme"). File name `FNA_EAR_2026.thmx`, file path `C:\Users\Your Name\AppData\Roaming\Microsoft\Templates\Document Themes`. Note: AppData is a hidden folder so if you try to navigate this file path manually you may need to go to View > Show > Hidden items in File Explorer.

2) Since a `.thmx` file is actually a zipped set of XML files, I changed file extension from `.thmx` to `.zip` and extracted it. Note: You may not be able to see the file extensions in File Explorer until you go to View > Show > File name extensions.

3) I opened the XML theme file in Notepad++. File name `theme1.xml`, file path `C:\Users\Your Name\AppData\Roaming\Microsoft\Templates\Document Themes\FNA_EAR_2026\theme`. Note: To make it easier to see the hierarchy of the XML file, go to Plugins > XML tools > Pretty Print

5) I followed the instructions in the Brandwares link to add a custom color palette (see Design)

6) I saved the XML code, re-zipped, and changed the file extension back from `.zip` to `.thmx`. Note: Zip the contents of the FNA_EAR_2026 folder which has 3 folders (`_rls`, `docProps`, `theme`) and an XML file `[Content_Types].xml`. Note: Make sure the updated `.thmx` file is located at the file path in step 1.

# Helpful Resources

https://www.brandwares.com/bestpractices/2015/06/xml-hacking-custom-colors/ including the comment section at the end

# Future Notes

Now that the XML code is here in GitHub, we can edit it here (or using VS Code and GitHub Desktop - both are available in the FNA software center, helpful video to get started: https://youtu.be/8Dd7KRpKeaE?si=U9mRvX51fwG_CYFp). Document changes in the README file. Replicate changes in other code (e.g., R, SAS).