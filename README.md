# Blossom-Clients

This repository hold copies of existing blossom clients with modifications for testing with swarm relay. 

## For Testing
For convenience, this repository contains a copy of frontends for testing with the swarm blossom relay, these two are called bouquet and sakura and a copy reside in the clients directory. Both have been modified to fix issues as of 15 AUG 2025. They are early prototypes and not actively maintained upstream, so beware when syncing, there might be issues. Bouquet is good for bulk syncing, Sakura is good for individual file mirroring.

Buggy Client Notes:
- Sakura syncs images well but videos might sync to type application/octet-stream and then they are binaries, will need to fix this.
- Sakura takes a really long time to login, be patient
- Fixed some syncing issue bugs with Sakura, as well as refresh page, so it will not logout user.
- Bouquet syncing can be inconsistent, needs investigation
- Bouquet - there is a cors error on the bouquet deploy on vercel
- works with alby and nos2x, may have issues with nos2x-fox

Live instances at:
- https://sakura-beta-ochre.vercel.app/
- https://bouquet.slidestr.net/

  
## Videos - how to upload via a client

How to Mirror files
[Watch the video](https://github.com/user-attachments/assets/5a0847d3-49f1-406a-bea2-9487c5b37318)

How to Upload
[Watch the video](https://github.com/user-attachments/assets/89e400e8-7816-4739-9690-ddc28135b5a6)



