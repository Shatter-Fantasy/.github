## Important Notice
The SF Utilities and SF UI Elements package is being merged into a single package called SF Core.
This is to lower the amount of package dependcies and cross assembly references in assembly definitions.
The goal is to speed up development and make the packages easier to work with.

## Welcome to the Shatter Fantasy community tool profile.

## Unity Version Requirements
All tools are being aimed at Unity LTS 6.3 and newer. This is because we don't want to waste resources on maintaining the legacy changes made to the following Unity stuff.
Most changes are to the UI Toolkit, Text Core, SRP packages, and the improved C# Span API support for several of Unity's core API.

The packages don't use any Text Mesh Pro, only UI Toolkit with Visual Elements.

No packages with 2D physics like the SF Metroidvania package use Collider2D/Rigidbody2D. 
They purely use the low level physics 2D API introduced in 6.3 for allowing burst compiled code, custom collision tools, and high performance with low memory footprint.

For those not familar with it here is a primer repo made by the Unity dev that created the feature and added it to Unity.
[Low Level Physics 2D Primer](https://github.com/Unity-Technologies/PhysicsExamples2D/blob/master/LowLevel/Projects/Primer/README.md)


### Unity UI Toolkit Information
All packages use the UXML attibute classes and no UxmlFactory/UxmlTraits classes. The UxmlFactory/UxmlTraits classes are being removed by Unity themselves in Unity 6.4 anyways.

Link to Unity announcement about that
[Unity 6.4 Changes](https://discussions.unity.com/t/planned-breaking-changes-in-unity-6-4/1682100)

### Unity rendering Changes
We only use the more recent Render Graph API that is used as the core backend for both URP and HDRP pipelines.
The legacy Render Graph API is being removed in Unity 6.5.

Link to Unity announcement about that
[Unity 6.5 Changes](https://discussions.unity.com/t/planned-breaking-changes-in-unity-6-5/1694205)

## Disclaimer: Community tools are in alpha
At the moment there are a set of tools currently in alpha that is currently having documentation being typed up.
I am updating the doccumentation because of the merge of the SF Utilities and SF UI Elements into the single package called SF Core.

The SF Metroidvania alpha seven should be the last one with major breaking changes.
Currently working on Alpha six which should be small and mostly a cleanup from the massive package changes done in alpha five.

<!--
 Remember, you can do mighty things with the power of 
 [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
