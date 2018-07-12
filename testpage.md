<!-- TITLE: Testpage -->
<!-- SUBTITLE: A quick summary of Testpage -->
| Property            | Required | Description                                                                                                                          |   Default Value  |
|---------------------|:--------:|--------------------------------------------------------------------------------------------------------------------------------------|:----------------:|
| **title**           | yes | The title of the website. Displayed in the navigation bar. | Wiki |
| **host**            | yes | The full hostname of the site, as accessed by the user. Do not add a trailing slash. You must add the port if you expect users to access your wiki via a non-standard port. | http://localhost |
| **port**            | no  | The port on which the server should listen to. You can also use the environment variable PORT using $(PORT). | 80 |
| **paths.repo**      | yes | The path (absolute or relative to server.js) to the folder where markdown content will be synchronized with the Git repository. Make sure this folder has the necessary write permissions. Note that this folder will contain all uploads (images, documents, etc.), so make sure to allow enough disk space depending on your usage. | ./repo |
| **paths.data**      | yes | The path (absolute or relative to server.js) to the folder where temporary data will be stored (cache, thumbnails, search indexes, etc.). Make sure this folder has the necessary write permissions. | ./data |
| **lang**            | yes | The default language to use for the site UI. Possible values: `en`,  `es`, `fr`, `ko`, `pt`, `ru` or `zh` | en |

# Header

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
####### Header 7
######## Header 8
Normal Text
## Sets
-Origins
##### Battle for Zendikar Block
Battle for Zendikar , Oath of the Gatewatch

> A line of text

> A blockquote with
> 
> multiple lines  
> of text!

> You can even include **styling** in your text, or **icons** :apple:

> Default

> Info
{.is-info}

> Success
{.is-success}

> Warning
{.is-warning}

> Danger
{.is-danger}

<a href="https://discord.gg/nSceXUe">![DISCORD EMBED PLUGIN](https://discordapp.com/api/guilds/270013046649257984/widget.png?style=banner2)</a>
