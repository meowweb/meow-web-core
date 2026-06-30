# How to add a meowweb page?
To add a meowweb page, you have to first do a pull request to the `index` folder.

The pull request must have a txt file, it must be named the same as the title of your webpage.
Follow this template that states how the txt file must be:

```json
[
{"domain":".meow (you can change it)"},
{"url":"name (eg. in cat.lol, the name would be cat)"},
{"code":"must include the url of the webpage, advised to be any kind of raw git, not the actual url of the webpage"}
]
```

The webpages are written in html, and you can pull request the .html file in the `core` folder, you can always host it in another repository. The code url must be a raw code, not a webpage itself

eg. `https://raw.githubusercontent.com/AsierSystem/AsierSystem/landingpage.html`

Tips: name the html file similar to your webpage to not create conflicts

      do first the pull request of the code, then the index, so that you have an assured url to host your code before indexing it
