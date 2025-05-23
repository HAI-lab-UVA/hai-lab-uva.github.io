Visit **[hai-lab-uva.github.io](https://hai-lab-uva.github.io)** 🚀

# Summary

Source code for the HAI Lab at UVA website. The site should be updated regularly by the lab with new members, projects, and news as appropriate.

# Attributions

The site is based on a template from the Greene Lab, see the below template documentation and/or [``LICENSE.md``](LICENSE.md) for more information on this.

[**Template Documentation**](https://greene-lab.gitbook.io/lab-website-template-docs)

# Authors

* Andrew Balch - xxv2zh@virginia.edu
* Kyan Yang - kyan.b.yang@gmail.com
* Members of the HAI Lab!

# How to contribute

Most page modifications should be made to the ``Markdown`` files, contained within folders of the same title. To add new chunks of text, place these within ``{% capture text %} <text> {% endcapture %}`` commands.

Images should be added under the [``images``](images) directory. To include data (such as images) on a page, ``{% insert <filepath> %}`` commands should be used. Changes to other files and directories (especially those prefixed with an "_") should be made hesitantly, to avoid breaking the website.

It is recommended to check the above template documentation for more detailed information on the innerworkings of the website template and it's included features (like automatic citations).

### Managing team members

Each team member that should be shown on the "Team" page should have their own markdown file under the [``_members``](_members) directory. Adding and removing these files updates the list shown on the page.

### News post link redirects
Posts on the news page can redirect to URLs other than the page associated with that individual post. This is useful when you would like a user to be automatically sent to a paper or news feature when they click on the post exerpt. To do this, set the ```redirect``` field in the header of the markdown file like so:

```redirect: https://<url>```