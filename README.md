# 100 Days Of Blockchain Code - Log

## 100 Days Of Blockchain Code is a pledge to dedicate at least 1 hour of study or coding to blockchain development for 100 days
Inspired by [Siraj Raval's 100 Days Of ML Code challenge](https://www.youtube.com/watch?v=cuQMBj1cWPo)


### Day 1: July 18, 2018
##### Coding My Own Cryptocurrency on Ethereum

**Today's Progress**: Written First Smart Contract and started with coding front-end for ICO website.

**Thoughts**: I really struggled with having a test-driven development mindset. But getting the hang of it now.

**Link(s) to work**: [LabToken Repo](https://github.com/RoyVoetman/LabToken)

### Day 2: July 19, 2018
##### Coding My Own Cryptocurrency on Ethereum

**Today's Progress**: Deployed Smart Contract to Rinkeby test network

**Thoughts**: Tried to sync with the Rinkeby test network via `geth` but I got stuck on the last 60-70 blocks. Eventually solved this by running `geth` with the `--light` flag.

**Link(s) to work**: [LabToken Repo](https://github.com/RoyVoetman/LabToken)

### Day 3: July 20, 2018
##### Coding My Own Cryptocurrency on Ethereum

**Today's Progress**: Deployed ICO website to GitHub pages.

**Thoughts**: I struggled with loading all my css and js files with the right paths because for some weird reason the `app.js` file couldn't be accessed via GitHub pages.

**Link(s) to work**: [LabToken ICO website](https://royvoetman.github.io/LabToken/)

### Day 4: July 21, 2018
##### Coding My First DApp on Ethereum (Election DApp)

**Today's Progress**: Got started on coding the Election Smart Contract and added boiler plate code for the front-end.

**Thoughts**: I did some more research on ES6 Promises and found a cleaner way of writing promise chains with `async` and `await` instead of `.then(() => {})`. I also learned about the difference between a `mapping`, `array` and `struct` in Solidity. 

**Link(s) to work**: [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)

### Day 5: July 22, 2018
##### Coding My First DApp on Ethereum (Election DApp)

**Today's Progress**: Added the core voting functionality to Smart Contract and front-end.

**Thoughts**: 

* Today I had a problem with listening for Smart Contract events when starting from `block 0`. This meant that all the previous events would trigger at the same time on a page reload. This resulted in unnecessary code execution.

* Found a way for handling errors with `async` functions without `try` and `catch` blocks.

**Reference(s)**: [Article: How to write 

without try-catch blocks in Javascript](https://blog.grossman.io/how-to-write-async-await-without-try-catch-blocks-in-javascript/)

**Link(s) to work**: [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)

### Day 6: July 23, 2018
##### Coding My First DApp on Ethereum (Election DApp)

**Today's Progress**: Deployed front-end to IPFS.

**Thoughts**: At first at was not clear to me what the difference was between IPFS and IPNS but now I know that IPFS is the hash of the file and IPNS is the hash you can publish because that one isn't gonna change.

**Link(s) to work**:
 * [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)
 * [IPFS Gateway](https://gateway.ipfs.io/ipns/QmQVEuk8x7por9xSJVNTTxRqTJWxspJt5GnrEmWxEt29rd/)
 
 ### Day 7: July 24, 2018
 ##### Coding My First DApp on Ethereum (Election DApp)
 
 **Today's Progress**: Added functionality for contract admin to dynamically add new candidates / Started refactoring Token Sale tests (`async await` instead of `then()`).
 
 **Thoughts**: I didn't really have any struggles today apart from Metamask caching some things about my local test network, fixed this by changing netwerk_id of test network.
 
 **Link(s) to work**:
  * [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)
  * [LabToken ICO website](https://royvoetman.github.io/LabToken/)
  
   ### Day 8: July 25, 2018
   ##### Coding My First DApp on Ethereum (Election DApp)
   
   **Today's Progress**: Added functionality for contract admin to dynamically add new candidates in the front-end / Finished refactoring Token Sale tests (`async await` instead of `then()`).
   
   **Thoughts**: I faced a challenge by integrating special functionality for the Contract Owner because I didn't want everybody to know who the admin is so hard-coding the address or defining the 'admin' variable public wouldn't solve anything.
   
   Eventually, I created a getter function for the private 'admin' variable but added an 'onlyOwner' modifier to check if the address calling it is the owner. Then in the front-end, I wrapped the getter function in a 'try' block so the extra functionality would only be visable for the owner.
   
   **Link(s) to work**:
  * [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)
  * [LabToken ICO website](https://royvoetman.github.io/LabToken/)
  
 ### Day 9: July 26, 2018
 ##### Coding My First DApp on Ethereum (Election DApp)
   
   **Today's Progress**: Deployed Election DApp to Rinkeby test network and deployed frontend to IPFS.
   
   **Thoughts**: Today I finished my first DApp! Really learning a lot by just doing, without this challenge I would have probably procrastinated on this project.
   
   **Link(s) to work**:
  * [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)
  * [IPFS Gateway](https://gateway.ipfs.io/ipns/QmQVEuk8x7por9xSJVNTTxRqTJWxspJt5GnrEmWxEt29rd/)
  
    
 ### Day 10: July 27, 2018
   
   **Today's Progress**: Did more research on the possibilities/potentials of blockchain technology / Looked into the Drizzle front-end framework from truffle.
   
   **Thoughts**: Today there is a heat wave and because of this coding isn't really the best thing to do right now. But doing research on all the available tools and looking at how other people solve the problems they face when build DApps is also a very good learning opportunity.
   
   **Reference(s)**:
  * [Drizzle](https://truffleframework.com/docs/drizzle/getting-started)
  * [Video](https://www.youtube.com/watch?v=oCS05QSQ-1k)
  
 ### Day 11: July 28, 2018
   
   **Today's Progress**: Did research on NEO and EOS and what these technologies bring to the crypto space
   
   **Thoughts**: I personally think if Etheruem doesn't start improving it will be replaced by either NEO or EOS. My personal interest goes to EOS because of its low feeds and the use of an improved consensus protocol over regular PoS.
   
  **Reference(s)**:
  * [EOS](https://eos.io/)
  * [NEO](https://neo.org/)
  * [https://globalcoinreport.com/eos-vs-neo-which-one-will-replace-ethereum/](https://globalcoinreport.com/eos-vs-neo-which-one-will-replace-ethereum/)
  
### Day 12: July 29, 2018
   
   **Today's Progress**: Started reading EOS's white paper and doing more research on EOS in general
   
   **Thoughts**: I think there is a very high potential for EOS to grow in the next few months/years. Really excited to see what will happen over time. I will definitely look into developing DApps for EOS.
   
  **Reference(s)**:
  * [EOS](https://eos.io/)
  * [EOS Whitepaper](https://github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md)
  
### Day 13: July 30, 2018
   
  **Today's Progress**: Tried setting up EOS development environment.

  **Thoughts**: Today I learned about docker because the EOS documentation says that this is the quickest way to set up the development environment. The docker image is now successfully installed but I still can't execute commands like `nodeos`, `cleos`, and `keosd`.
   
  **Reference(s)**:
  * [EOS Quickstart](https://developers.eos.io/eosio-nodeos/docs/docker-quickstart)
  * [Docker](https://docs.docker.com/)
  
### Day 14: July 31, 2018
   
  **Today's Progress**: Continued setting up EOS development environment.

  **Thoughts**: After some more in-depth research about docker I found out how to execute a command in your docker container. But this is a pain to write every time so I added the following aliases to my `.zshrc` file:
   * `alias cleos='docker exec -it eosio /opt/eosio/bin/cleos -u http://127.0.0.1:8888 --wallet-url http://127.0.0.1:8888'`
   * `alias nodeos='docker exec -it eosio /opt/eosio/bin/nodeos'`
   * `alias keosd='docker exec -it eosio /opt/eosio/bin/keosd'`
   
  **Reference(s)**:
  * [EOS Introduction to smart contracts](https://developers.eos.io/eosio-cpp/docs/introduction-to-smart-contracts)
  * [Docker exec](https://docs.docker.com/engine/reference/commandline/exec/)
  
### Day 15: August 1, 2018
   
  **Today's Progress**: Begon developing HelloWorld smart contract with EOS

  **Thoughts**: Found out how to access the terminal of your Docker container and used the `eosiocpp` compiler (also added an alias to my `.zshrc` file). I struggled a bit with keeping track of all my different PKeys and SKeys all my different accounts but everything is very well documented so I am still excited to learn more!
   * `docker exec -it <container_id> /bin/bash`
   * `alias eosiocpp='docker exec -it eosio /opt/eosio/bin/eosiocpp'`
   
  **Reference(s)**:
  * [Documentation Guide](https://developers.eos.io/eosio-cpp/docs/hello-world)
  
### Day 16: August 2, 2018
   
 **Today's Progress**: Finished creating HelloWorld contract with EOS and Did more research on using Docker

 **Thoughts**: Found out about Dockers `-v` flag for `VOLUME (shared filesystems)` this prevents u having to rebuild the Docker image every time you make a change to your code. This makes the Docker developing experience way better.
   
  **Reference(s)**:
  * [Stack overflow post](https://stackoverflow.com/questions/24272535/rebuild-container-after-each-change)
  
  **Link(s) to work**:
  * [Hello world smart contract](https://github.com/RoyVoetman/EOS-Starter-kit/tree/master/helloWorld)
  
### Day 17: August 3, 2018
   
**Today's Progress**: Finally successfully setup a complete EOS development environment with Docker

**Thoughts**: Yesterday I already had a 'working' development environment but my wallets didn't sync with my local environment so every time I booted up the docker image I would need to recreate all my wallets/keys. I finally solved this by reading the in-depth documentation about `cleos` and `keosd`. When I knew where the wallets/keys where stored I added a `-v` flag so that the folder would sync to my local environment.

After that, I thought that it still didn't work because `cleos wallet list` still gave an empty array but after a lot of debugging I found out that only my unlocked wallets are shown with `cleos wallet list`.
   
  **Reference(s)**:
  * [Learn about wallets keys and accounts with cleos](https://eosio-nodeos.readme.io/docs/learn-about-wallets-keys-and-accounts-with-cleos)
