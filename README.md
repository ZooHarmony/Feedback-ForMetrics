## We've successfully launch testnet events, within 6 hours we got more than 460 people who visited the DexSwap AMM and ZooHarmony NFT Marketplace with a page view more than 3.17K also with a total of 180 people who participated in the ZooHarmony Testnet event, 156 Feedback and 200 Minted NFT . We're glad to all of ZooHarmony and DexSwap Community, thanks for being part of our journey. Giveaway/Incentive event for testnet was closed! 

We pointed some feedback:

1. Very interesting and challenging because the process is very long and I feel like I have a new experience testing this web
- [x] Answer: We need to do this to users who test our dapp: so they can learn something new and feel the different experience.

2. The drawing features in ZooHarmony are very easy to use and no problem at all
- [x] Answer: Released Alpha v0.1.1

3. I really like the UI, then the UX is the same. the website is very responsive once used on my mobile device. then the selection of the background color is very suitable, and one sentence my first impression is a page with a minimalist and informative page display with all the existing features.
- [x] Answer: Released Alpha v0.1.1

4. I feel new things in the nft market that I have never felt before. The appearance and features of Zoo Harmony are very attractive.
- [x] Answer: Released Alpha v0.1.1

5. Well the welcome page UI is not that pleasing the eyes you guys need to made it more interesting by adding more color or some picture just be creative i think, so when people visit the page for the first tme they would feel wow
- [x] Answer: We will Release with Alpha v0.1.3 - Alpha v0.1.5

6. 
- Site is interactive but it would really need improve later when mainnet launch (it's seems lag on several situation)
- Mint and NFT Listing on Zoo Harmony is very easy. We do not need to bother to do both things. It's just that on my 2nd try to do an NFT listing that I had previously purchased, I experienced a long transaction delay and this is quite annoying.
- [x] Answer: Fixed with changeing the block from PastEvents Contracts on Index.js
```
    Before:
    const transactions = await sale_contract.getPastEvents('BoughtNFT', {
        fromBlock: 0,
        toBlock: 'latest',
    })
    After: Fixed with:
    const transactions = await sale_contract.getPastEvents('BoughtNFT', {
        fromBlock: 20523921, // ZooHarmonyNFT BLock
        toBlock: 'latest',
    })
```
7. Minting is going well. But on listing i have a problem thats not notification or something. If i succeed to listing my NFT
- [x] Answer: Released Alpha v0.1.2 | Adding more features and adding more toast

8. 
- The canvas size i think it better that we input the size number manualy rather than use scaled 
- Added more tools like pencils other than brush
- Add coloring tools like bucket paint cuz its really hard coloring using brush when on mouse
- Add background tool 
- [x] Answer: We will Release with Alpha v0.1.3 - Alpha v0.1.5 and rebuild Drawing to the stable version


9. Cannot Mint NFT
<img src="https://raw.githubusercontent.com/ZooHarmony/Feedback-ForMetrics/main/1.jpg">
- [x] Answer: Users should fill all the form
- Select the Categories 
- Name of NFT
- Url Promotions
- Description of NFT
<img src="https://raw.githubusercontent.com/ZooHarmony/Feedback-ForMetrics/main/fixed1.png">

10. Cannot Swaps ONE to ZOO
<img src="https://raw.githubusercontent.com/ZooHarmony/Feedback-ForMetrics/main/3.jpg">
- [x] Answer: Users should consider to use slip page more than 10% beacuse the LPs ONE-ZOO only just 10K
<img src="https://raw.githubusercontent.com/ZooHarmony/Feedback-ForMetrics/main/4.png">
