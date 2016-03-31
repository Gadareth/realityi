# realityi
Integrating Instagram API into Media RSS 1.5.1

Steps:
1. Access the JSON media file of the user's Instagram account by going to https://www.instagram.com/(user-name)/media/
2. Loop through the standard resolution quality of the images by using i as the iterator with the following JS code: test.items[i].images.standard_resolution.url
3. Submit these images to an RSS feed.
