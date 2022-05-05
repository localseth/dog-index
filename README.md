# DOG INDEX
This project is form a workshop as part of the Treehouse WebDev program. I have added the JavaScript to a page that will generate a photo of a dog randomly, and then based on its breed. All of the photos and breed information comes from this API: https://dog.ceo/dog-api/

I made two modifications that I felt were lacking from the original project:
1. On page load, the breed of dog did not match the randomly generated image. The select option was automatically chosen as the first one alphabetically. I modified this with the `initialFetch()` function in order to find the breed of dog in the initial image provided, and then display that dog's breed in the description as well as the select menu.
2. Some images were rather small, and others were so large that they would not be contained within the `.card` div element. I set the width for each image to 100% so that the margins around the image are consistent.

## Note
The comment section was strictly for education purposes and does not do anything. If you look at the console in the browser, you can see the object created by a comment and where it would fall in line with a list of other sample comments. It always generates an id value of 501.