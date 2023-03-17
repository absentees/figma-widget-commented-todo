# WIP: Commented TODO list (figma widget)

For smaller tasks within figma files i often leave a comment for myself. I can use the "Resolve" function to mark them as done, and also comment on them to let others know they are complete or need input.

It would be handy to be able to see just the TODOs in a visual widget, interact with them there, and have them update their comment.

## Setup / usage

- Leave a comment for yourself with the text TODO: in it
- Repeat
- Open widget and give it permission to access your figma file (this is need since widget API and plugin API can't interact with comments, but the REST API can.....)
- Widget will pull in all comment with TODO: and display them
