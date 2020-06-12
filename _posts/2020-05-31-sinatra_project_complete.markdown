---
layout: post
title:      "Sinatra Project Complete"
date:       2020-05-31 12:42:44 -0400
permalink:  sinatra_project_complete
---


Today is the final day to submit my project. I am nervous but confident. The past 2 weeks have been really trying for me with the global pandemic affecting my work schedule and ability to effectively work on my project. The last 4 days I have been able to complete my project with success.

When I first started I had no idea what I was doing. I knew what I wanted, but the execution took a lot of patience and googling. Once I got started, the long nights perseded and things started to make sense. To start I went and reviewed earlier labs like the Fwitter and the ActiveRecord lessons helped tremdously with set up. It took me a while to come up with a concept.

I chose to create an app that mirrors a simple and basic admission process. Frustration of course ensued but after watching a couple lectures the concepts started to make more sense and I was able to get into a great flow to complete the project on time.

Things I had trouble with:

Helper Methods. Specifically where to use them in relation to replacing the code that was there before. It was a new concept to me so it took me a minute to fully grasp the idea. From what I understand you can create helper methods to be called in place of recurring code.

For example, if you want to locate a specific object you would use `Object.find_by(argument)`. Instead of using this to find the object in all of your routes you can replace them with this by defining your helper method to do it. It turns into:

```
def find_object
Object.find_by(argument)
end
```

`find_object `can be called in your routes instead of typing the whole thing out. Learning this helped me condense my code so it looks a lot cleaner and easier to read.
