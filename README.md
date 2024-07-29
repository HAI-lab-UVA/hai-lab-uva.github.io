# Summary
Source code for the HAI Lab at UVA website. The site should be updated regularly by the lab with new members, projects, and news as appropriate. 

# Attributions
The site is based on a template from the Greene Lab, see the below template documentation and/or [```LICENSE.md```](LICENSE.md) for more information on this. 

[**Template Documentation**](https://greene-lab.gitbook.io/lab-website-template-docs)

# Authors
* Andrew Balch - xxv2zh@virginia.edu
* Members of the HAI Lab!

# How to contribute
Most page modifications should be made to the ```Markdown``` files, contained within folders of the same title. To add new chunks of text, place these within ```{% capture text %} <text> {% endcapture %}``` commands. 

Images should be added under the [```images```](images) directory. To include data (such as images) on a page, ```{% insert <filepath> %}``` commands should be used. Changes to other files and directories (especially those prefixed with an "_") should be made hesitantly, to avoid breaking the website. 

It is recommended to check the above template documentation for more detailed information on the innerworkings of the website template and it's included features (like automatic citations). 
