# Source for Aikido Zbraslav Web Site

Static site generator Zola is used for building web pages for this source. 

## Content

The content is solely in the Czech language.
The project uses Markdown as a format 
for the content.

## Templates

Templates are in HTML with usage:
* Tera templates (for including content to templates for creating the web pages)
* Tailwind CSS (version 4) for styles. Tailwind CSS is included into the templates using the Play CDN.
* DaisyUI (version 5) for components. DaisyUI is included into the templates also from CDN.

## Building and Deployment

After committing changes and pushing them to  Github an action is triggered in Cloudflare Pages. The source is read by Zola SSG and the pages are generated and deployed.
