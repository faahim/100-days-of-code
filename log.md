# 100 Days Of Code - Log

### Day 0: January 1st, Monday

**Today's Progress**: Struggeled with fetching url metadata on client side in geckos-28 react app. Written a method to remove item from shelf.

**Thoughts:** I'm having a hard time understanding the CORS policy. I'm reading some articles to deepen my understannding on it. I'm also afraid that maybe I simply can't fetch cross origin data from the client side!


### Day 1: January 2nd, Tuesday

**Today's Progress**: Found a way to fix CORS issues using proxy on the client side for the react app.  

**Thoughts**: After a lot of searching and reading, I think I understand CORS on a high level now. I'm using a proxy to fix the issue on the client side but I don't feel like it's a proper solution. Gotta keep researching.

**Link to work**: [Today's commit](https://github.com/faahim/geckos-28/commit/8a485894081549d70b04d18e573fcd9513ed59d2)

### Day 2: January 3rd, Wednesday

**Today's Progress**: Fetching url metadata seems to be working fine now. 

**Thoughts**: The npm module I was using yesterday (node-metainspector) didn't really worked very well. It returned a lot of errors. So, today I tried some other npm module and found one (uel-metadata) that's working really well so far. It successfully fetches title, description and image from any given url. Now I gotta find a way to display those info when user inputs any url.

I'm currently on a family trip and it was so freaking hard today to manage to sit with computer for coding. I had to wait until everyone sleeps. It's 3 in the morning now and I'm tried as hell. Gotta push myself forward. :)

**Link to work**: [Today's commit](https://github.com/faahim/geckos-28/commit/6475537054cedc54ec2a589c7e8f3bb43cc1ab38)

### Day 3: January 4th, Thursday

**Today's Progress**: Viewing fetched metadata in the list view. 

**Thoughts**: The npm uses promise to store the fetched data. It was very challenging for me to come up with a way to update the state (and viweing component) when the metadata is available. Most of the approach I took didn't work because of 'this' keyword. It's very confusing sometimes. I learned that arrow function doesn't have it's own this. I used it at my disposal.

It's 3am in the morning again today! It's so hard to manage time sometimes! I'm a bit worried about the upcoming trips. :(

**Link to work**: [Today's commit](https://github.com/faahim/geckos-28/commit/11e27772732d1eab3b569d9afbf1e2af3b317046)
