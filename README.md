# decentralized-collaborative-code-editor
A p2p collaborative code editor using ace editor, Y-JS, pubsub, and IPFS.

change to working directory and type: npm install to install packages.

Then run: npm start

Open two windows (two nodes generated with math.random to create distinct ipfs hashes)

start typing in either editor and the second will update. using conflict-free replicated data types, the node establish no authoritive user; allowing concurrent updates and can support offline use.
