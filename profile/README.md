# Important Note
Shater Fantasy's organization profile read me will be updated as we finish the work on Alpha 1 release for the SF UI Elements tool's Unity package.
The SF UI Elements alpha 1 release is scheduled for Novemeber 14th.

The current read me here was typed up quickly just so people coming here would get an idea of what is coming for the week of November 10th and the week of November 17th.
Please ignore any slight spelling errors or grammar that needs cleaned up. We are mainly focusing on making the actual read me to be as clean as possible for the first release.

## Welcome to the Shatter Fantasy community tool profile. 👋

## Unity Version Requirements
All tools are being aimed at Unity 2023.2 and newer. This is because we don't want to waste resources on maintaining the legacy changes made to the following Unity stuff.
Most changes are to the UI Toolkit, Text Core, SRP packages, and the improved C# Span API support for several of Unity's core API.

### Unity UI Toolkit changes
In Unity 2023.2 they introduced the [Uxml Attributes](https://docs.unity3d.com/6000.0/Documentation/ScriptReference/UIElements.UxmlElementAttribute.html) set.
These attributes with no exageration lowered our code lines by 414 (yes we counted) across 22 files in our core SF Sprite Tool package being worked on.
Unity 2023.2 also added the better built in Tab and TabView visual element classes that made our WIP RPG Editor for our game project a lot easier to work with.
Due note some of Unity versions that have support for the new set of UXML attributes say they do not support them in certain versions of Unity even though they actual are supported.
Example on the Unity 2023.2 API documentation for the UXML attributes, it says this feature is not supported when that was the version it was actually added in.

### Unity rendering Changes
In Unity 2023.2 they started moving some code in all the Scriptable Rendering (SRP) packages to use the new Render Graph feature. 
This is making life a lot easier for different Shader, VFX Graph, and custom rendering features we were working on.

## Disclaimer: Community tools are in pre-alpha
At the moment there are a set of tools currently in pre-alpha that is currently having documentation being typed up.
We plan to release the documentation along side each alpha release so no one has to do any guess work of what is new and how to use it.
These tools are considered pre-alpha because we were working on designing a core archiecture system across all packages and we know some changes are breaking changes. 
This includes naming convention, design patterns, how to choose release features to prioritize, a release schedule, and how to seperate certain features into what tool package.

Example of seperation of features. At first the SF UI Elements packages was planned as a set of utility features inside of the SF Utility package.
We decided that it would be a bloated tool to put all of the UI Toolkit utilities into the SF Utility package. 
In the end we created a SF UI Elements package and the SF Utilities package now has general utility helpers and extention methods for general stuff.
Think type conversion extensions, math extensions, and extenstions for collection types like lists.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
