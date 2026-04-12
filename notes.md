Things to come back to

Static vs. Dynamic 

In english, static and dynamic are direct anotnyms, complete opposite 

static means not moving and dynamic means constant movement 

in coding, specifically in Astro, static means the page is built ahead of time(before anyone visits), while dynamic means the page is created when someone visits 

Static(In Astro)
- astro builds your pages into HTML once you run astro build
- then it serves the same page to everyone 

Example: 
<h1>Welcome to my Site</h1>

Dynamic(In Astro)
-the server builds the page on the spot 
-it can show different things to different to different people 

Example:
<h1>Hello {username}</h1>


What is a Prop?
Prop = short for 'property'

a prop is just data you pass into a component 

Lunchbox Analogy: 

A component is like a lunchbox
- the lunchbox = the component 
-the food inside = the props 



#Today we are going to try to finish my 2nd project, I will Create a blog post archieve. 

I will:
- Acess data from my posts at ounce using import.meta.glob()
- Display a dynamically generated list of posts on my Blog page
- Refactor to use a <BlogPost /> component for each list item 


Generating tap pages Notes

objective: I will 
- create a page to generate multiple pages
- specify which page routes to build, and pass each page its own props 

What is frontmatter?

Front matter is a small block of information you put at the very top of a file. it gives extra details about the file, instead of being the main content itself.


