# Week 

## As this is a project inherited from last year...
- The group from last year implemented the player in unity and the rest of the work(choose file,
episodes) in a web App.

## Our requirements on platform...
- We would like to have a platform that works fast, and could be applied to different platforms
(Windows, Mac, Linux, Web).
- There are basically 2 options, the first one is continue with the Web(Electron)+Unity. 
- The second one is building the entire project on unity.

## Decision
- We decided to build the whole app within unity.
- Unity satisfies the "multi-platform" requirement.
- Also, building the whole app in unity allows the app running without the access to internet. This 
makes our app safe and secure.
- As some of the intended users are clinicians, which their videos has GDPR regulations with it, so
they cannot upload freely to online resources. So it is essential to keep the app offline.
