# Bitcoin Avarice (BTCAV)

**Avarice**

avarice 

**noun**

extreme greed for wealth or material gain. "he was rich beyond the dreams of avarice"

*synonyms*: greed, acquisitiveness, cupidity, covetousness, avariciousness, rapacity, rapaciousness, graspingness, materialism, mercenariness; meanness, miserliness; informal money-grubbing, money-grabbing, an itching palm; informal grabbiness; *rare:* Mammonism, pleonexia

"he had a reputation for ruthlessness and avarice"


# Bitcoin Avarice Specifications


    Algo: sha256d Hybrid  
    Name: BitcoinAvarice  
    Ticker: BTCAV   
    RPC: 8865  
    P2P: 8864   
    Block Spacing: 6 minutes


# BitcoinAvarice.conf

    rpcuser=BitcoinAvaricerpc
    rpcpassword=LOnglongLYougettheidea87444ok
    rpcallowip=127.0.0.1
    daemon=1
    server=1 
    rpcport=8865 
    port=8864


# Rewards POW'


**Avarice Super Blocks marked **


     int64_t nSubsidy = 0 * COIN;    
    if(pindexBest->nHeight < 2)
        nSubsidy = 1000000 * COIN; // Premine
    else if(pindexBest->nHeight == 3)
        nSubsidy = 1000000 * COIN; // ICO or burn
    else if(pindexBest->nHeight < 100)
        nSubsidy = 1 * COIN; 
    else if(pindexBest->nHeight < 1000)
        nSubsidy = 100 * COIN;
    else if(pindexBest->nHeight < 2000) // Avarice Blocks
        nSubsidy = 400 * COIN;
    else if(pindexBest->nHeight < 10000)
        nSubsidy = 100 * COIN;
    else if(pindexBest->nHeight < 11000) // Avarice Blocks
        nSubsidy = 500 * COIN;
    else if(pindexBest->nHeight < 20000)
        nSubsidy = 150 * COIN;
    else if(pindexBest->nHeight < 21000) // Avarice Blocks
        nSubsidy = 600 * COIN;
    else if(pindexBest->nHeight < 30000)
        nSubsidy = 200 * COIN;
    else if(pindexBest->nHeight < 31000) // Avarice Blocks
        nSubsidy = 700 * COIN;
    else if(pindexBest->nHeight < 999999)
        nSubsidy = 2 * COIN; 


# Rewards POS


- **50 % annually**
- minimum staking: 1 minute
- maximun staking: unlimited



## He has Avarice

![Avarice](https://cdn.pbrd.co/images/H2mT1iU.png)



