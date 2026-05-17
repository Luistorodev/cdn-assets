# cdn-assets

\### Example



```html

<video controls preload="metadata">

&#x20; <source 

&#x20;   src="https://cdn.jsdelivr.net/gh/USERNAME/cdn-assets@main/videos/demo.mp4" 

&#x20;   type="video/mp4">

</video>

```



\## Structure



\- `/videos` — Video files (.mp4)

\- `/images` — Images and graphics

\- `/docs` — Documents and other static files



\## Notes



\- File size limit per asset: \*\*50 MB\*\* (jsDelivr limit for GitHub)

\- Repo must remain \*\*public\*\* for jsDelivr to serve files

\- To purge cache after updating a file:  

&#x20; `https://purge.jsdelivr.net/gh/USERNAME/cdn-assets@main/PATH/TO/FILE`

\- For production, prefer version tags (`@v1.0.0`) over `@main` for immutable URLs

