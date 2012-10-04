# Streams!

Recently, I had an epiphany, the node.js Stream interface is fucking the best thing in the world since the node.js EventEmitter!

I'm really really late to all this new found knowledge which makes it cool because I didn't have to screw around too long to find the right stuff to get me going. 

# The right stuff:

Read this article that @pierhugues pointed me to: https://github.com/substack/stream-handbook it contains the right stuff to get you started. 

Then for the purpose of being more nerdy focus on these modules: 

- [through](https://github.com/dominictarr/through)
- [from](https://github.com/dominictarr/from)
- [JSONStream](https://github.com/dominictarr/JSONStream)

Now be really brave and observe the inner-workings of a complex node.js stream implementation:

- [the node FileSystem module](https://github.com/joyent/node/blob/master/lib/fs.js)

Then comfort yourself knowing it's probably much simpler to get you where you need to be,  by perusing the node.js Stream module.

- [the node Stream module](https://github.com/joyent/node/blob/master/lib/stream.js)



 

