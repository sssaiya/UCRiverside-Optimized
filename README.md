# UC Riverside Site Optimization

The UC Riverside site in its current state suffers from large file sizes, poor preloading, and ineffective caching policies. To remedy this and try to improve the performance of the site, we explored using file minification, image compression, and a more effective caching policy. By creating a local copy of the site, we were able to perform these optimizations and see their performance impact in real time.




## Original Performance Report
This was the performance report of the [UCR site](https://www.ucr.edu/) on 05/20/2020

![Original Performance Report](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/99e5e4af-257e-47de-9732-750525d18c66/Screen_Shot_2020-05-21_at_9.35.25_PM.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200621%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200621T191635Z&X-Amz-Expires=86400&X-Amz-Signature=8a69da53a8348beebfe6ce3d880b35992d51851f56200831ef6a7b51d326c680&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Screen_Shot_2020-05-21_at_9.35.25_PM.png%22)

## Optimized Site Performance Report
[Optimized Site](https://ucriverside-ec284.web.app/)

![Final Performance Report](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/246c9fdd-f4df-47fb-a0e7-dd69aaaaa5e8/Screen_Shot_2020-05-21_at_9.30.25_PM.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200621%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200621T192645Z&X-Amz-Expires=86400&X-Amz-Signature=fb79c5bb39c9294040f45f214a0fea645787029e2fdac84398bebc01911c98b3&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Screen_Shot_2020-05-21_at_9.30.25_PM.png%22)




## Steps taken
Our more detailed report is [here](https://www.notion.so/UC-Riverside-Site-Optimization-66277d2946054eabafd9a5c1e989478c)

Summary of optimizations
- Moved all static assets to our CDN
- Leverage Caching of static assets
- HTML, CSS and JS Minification
- Removing unused JS and CSS
- Image Compression
- Lazy Loading Images
- Remedy some security concerns


Effectively compressing and serving the site through our CDN which better leverages caching. 

Resulting in performance gains on first byte, start render, first contentful paint, and speed index among other things.



## License
[MIT](https://choosealicense.com/licenses/mit/)
