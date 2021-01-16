# Platform
This directory is dedicated for files that should be uploaded  
to the challenge's attachments in the platform (like [*CTFd*](https://ctfd.io/)).

## `challenge.json`
Include your challenge's details in this format:
```json
{
    "name" : "Template Challenge",
    "description" : "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
    "category" : "Web",
    "tags" : [ "Hard", ... ],
    "hints" : [ "I’m not superstitious, but I am a little stitious.", ... ],
    "prerequisites" : [ "Prison Mike", ... ]
}
```
Needless to say that not everything here is required. Name, description and category / tags should be more than enough.