---
title: "Adding content"
teaching: 0
exercises: 30
questions:
- "How to do basic modificaitons to a lesson?"
- "What tool can I use to edit the differnt files?"
objectives:
- "Learn about the built in github editor or how to edit locally"
- "Change the lesson title"
- "Add another episode"
- "Edit an episode"
- "Add a an image/figure"
keypoints:
 - "Can edit locally or directly on github"
 - "Some styles provided beyond the basics"
 - "Don't reinvent the wheel, reuse content when possible"
---
## Text Editors
Editing the lesson and episodes can take place both directly on github, using the in site editor
or locally using a basic text editor or Integrated development environment (IDE) like visual studio.
> ## Editing via github
> Viewing a markdown file, yaml file or plain text files is possible on github.
> When viewing those files, you can even edit them and commit changes all in browser
{: .callout}
<a href="{{ page.root }}/fig/10.png">
  <img src="{{ page.root }}/fig/10.png" alt="Github edit" />
</a>

> ## Visual studio code on Mana
> In our session on Mana, visual studio code is installed and can be used to edit files as well
> as commit changes to github.
{: .callout}
<a href="{{ page.root }}/fig/09.png">
  <img src="{{ page.root }}/fig/09.png" alt="Visual studio code" />
</a>


## Editing files
For any lesson, you will need to provide a correct title 
(_config.yml) and add and edit episodes with figures.

> ## Directory layout
> In case you forget what files and directories do what, you can refer back to 
> the episode on [lesson organization](https://carpentries.github.io/lesson-example/03-organization/index.html)
{: .callout} 

> ## Changing the lesson title and set the email
> With your basic lesson it is time to make it unique and less generic.
> Your first task is to change the title of your lesson and change the contact email address by editing the _config.yml file.
{: .challenge}

> ## Add a new episode
> We need to add a new episode for new lesson content. Create a new file in the _episodes folder called
> "02-figures.md".  
{: .challenge}
> ## Copy when you can
> I find it easier to copy conent or duplicate files when possible.  Why reinvent the wheel if someone has 
> alread done it for me.  Instead of a new file, copy/duplicate 01-introduction.md and rename it. Then
> change the text and remove tags that are needed.
> Github does not seem to have a duplicate file function, but you can copy the raw contents of a file and paste it into a new file created using the github menu.
{: .callout}  


> ## Edit your first episode
> With a new lesson title it is time to dive into editing an episode.  Go into the introductory episode
> "01-introduction.md" and change the title, add some questions and add some text where it says fix me.
> Use some styles to add section headers "##" and other [style](https://carpentries.github.io/lesson-example/04-formatting/index.html)
> and 
> [formatting](https://carpentries.github.io/lesson-example/06-style-guide/index.html)
>
{: .challenge}

> ## Episode 2 needs a figure
> Although we have a new episode focused on figures, it lacks what it claims it will have, figures!  
> Find an image and add it to your repository in the fig directory.  
> Once it is in the fig directory add it to your second episode. 
> ~~~
> {% raw  %}
> <a href="{{ page.root }}/fig/10.png">
>  <img src="{{ page.root }}/fig/10.png" alt="What am I" />
> </a>
> {% endraw %}
> ~~~
{: .challenge}


{% include links.md %}

