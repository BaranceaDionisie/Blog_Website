Blog website

Note: To set up a local copy of the website use npm to install the dependencies: ejs, express, lodash, body-parser.

Personal blog website minimalistic home page got a header with a navbar:

![image](https://user-images.githubusercontent.com/53087427/111907651-f9f3de80-8a5e-11eb-9ae8-c96d3bbb9dfe.png)

It contains only 3 pages: home, about and contact us page 
(all of them being generated using ejs partials).

When you head over to the home page it is going to have all of the blog posts on it listed in chronological order but the actual blog
content will be truncated to 100 characters. When you click on "Read More" it will take you to an individual page of each of your blog
posts and you can read it independently on a single page.

![image](https://user-images.githubusercontent.com/53087427/111907717-42ab9780-8a5f-11eb-88f6-54980545ac28.png)

There is a hidden page wich allow you to compose your diary: localhost:300/compose. 

![image](https://user-images.githubusercontent.com/53087427/111907777-7dadcb00-8a5f-11eb-9da2-00edab5cd796.png)

When clicking publish after composing the post you 
can see it get's put right on the home page and a brand new page has been created just for that new post.
