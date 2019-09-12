Explain the rendering of websites in the browser using a complete
block diagram. Every block should be explained in your own
words.List down all the names of JS engines and their creators.

```mermaid
graph LR
A[HTML] --> B(parsing)
C[CSS] --> D(parsing)
B --> E[Attachment]
D --> E
E --> F[Render]
//layout<->//
F --> G[Display]
```
HTML and Css are parsed on the server to an attachment.Then this attachment in rendered along with the layout and thus we get thee display

*HTML*

*CSS*

*ATTACHMENT*

*RENDER*

*DISPLAY*
