Eve Nguyen
Arman Nurbalin 

1. The automated tests for the Recipe project should go within a Github action that runs whenever code is being pushed. This allows for automatically checking for bugs everytime changes are pushed. By testing incrementally, it's easier to debug along the way instead of running into bugs at the end of development. Github automated testing is also less error prone than manual testing.
2. No, I would not use end to end testing to check if a function is returning the correct output. I would use it for simulating user interaction with the software.
3. Navigation loads the performance after reloading the entire page while Snapshot analyzes from a specific state without reloading the page. Navigation provides a performance score for the entire website making it easy to understand the load performance of the page. Snapshot does not provide a performance score but it is useful for understanding interactive elements and dynamic content.
4. Things that can be improved:
- Properly size the images 
- Serve images in next-gen formats using image formats like WebP and AVIF
- Preconnect to required origins by adding preconnect or dns-prefetch