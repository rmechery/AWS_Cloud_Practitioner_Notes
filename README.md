# AWS CCP Notes Website
This website was developed to overcome boredom while studying for the AWS CCP exam. I was already creating notes for the certification and wanted to share them without much overhead. The tools below allowed me to spend most of my time writing notes while simultaneously creating a website that allowed me to more easily digest the plethora of services provided by AWS. 

### Obsidian
![image](https://github.com/rmechery/AWS_Cloud_Practitioner_Notes/assets/69287143/27265444-2a55-4041-9bcc-78c251aa6a52)
Obsidian is a note-taking application that allows you to streamline writing markdown and comes with many built-in features. 

The one I found the most useful was **Wikilinks** which allows you to create links that simply connect notes or embed images/websites the same way Wikipedia does it. Traditional markdown links are tedious to write out so this feature saved me a lot of time and helped me connect topics more easily. With wikilinks, you just put the content you want in two sets of brackets (e.g. "[[EC2 Pricing Models]]") and Obsidian's full-text search provides a list of things to link from. 

Another feature I found useful is Obsidian's main selling point which is graph view. Different from other note-taking applications, the developers of Obsidian want you to spend less time organizing your notes and placing them in the right folder structure and more time *writing* your notes. Graph view automatically creates a mindmap of your notes that helps you understand connections between topics without having to create complex diagrams or charts. 

And finally, although this isn't really a feature per se, because Obsidian provides you all the barebone features to develop markdown and uses local storage, it's blazingly fast. 

### Hugo
![image](https://github.com/rmechery/AWS_Cloud_Practitioner_Notes/assets/69287143/28189525-a8a6-4212-b089-ef404e290bdd)
Hugo is static-site generator that markets itself as "The world’s fastest framework for building websites." It allows you to develop content for websites in markdown and format those notes in the Golang language. This allows you to completely bypass writing boilerplate html documents and spend more time writing content for your website. Hugo offers many different themes to use and provides many shortcodes to extend the functionality of markdown. 

### Quartz
Quartz is an application that bridges the gap between Obsidian and Hugo and allows you to easily convert your markdown notes into a GitHub pages website. Quartz provides a theme and extensions that provide many Obsidian-like features out of the box. It also uses Github actions to automatically build changes and deploy your site without any manual intervention.

# Disclaimer
The notes I created are not my own product. I took notes on Andrew Brown's free 13-hour AWS CCP course and provided sample quizzes from Rajesh Daswani's textbook. 
