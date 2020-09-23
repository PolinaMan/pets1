# GMiner - High-performance miner for AMD/Nvidia GPUs.

# Supported algoritms:
  - Ethash (Nvidia only)
  - ProgPoW (Sero) (Nvidia only)
  - KAWPOW (Ravencoin) (Nvidia only)
  - Ethash+Eaglesong (Nvidia only)
  - Ethash+Blake2s (Nvidia only)
  - Eaglesong (Nvidia/Amd)
  - Blake2b+Sha3 (Handshake) (Nvidia only)
  - Cuckarood29/Cuckaroom29/Cuckarooz29 (Grin) (Nvidia only)
  - Cuckatoo31 (Grin) (Nvidia only)
  - Cuckatoo32 (Grin) (Nvidia only)
  - Cuckoo29 (Aeternity) (Nvidia/Amd)
  - CryptoNightBBC (BBC) (Nvidia only)
  - BFC (Nvidia/Amd)
  - Cortex (Nvidia only)
  - Cuckaroo29b (BitTube) (Nvidia only)
  - Cuckaroo29s (Swap) (Nvidia/Amd)
  - Cuckarood29v (MoneroV) (Nvidia only)
  - Blake2s(KDA) (Nvidia/Amd)
  - Eaglesong (CKB) (Nvidia/Amd)
  - Equihash 96,5 (MinexCoin) (Nvidia only)
  - Equihash+Scrypt (Vollar) (Nvidia only)
  - Equihash 125,4 (ZelCash) (Nvidia only)
  - Equihash 144,5 (Bitcoin Gold, BitcoinZ, SnowGem, ZelCash) (Nvidia/Amd)
  - Beam Hash (BEAM) (Nvidia/Amd)
  - Equihash 192,7 (Zero, Genesis) (Nvidia/Amd)
  - Equihash 210,9 (Aion) (Nvidia only)

# Features:
  - Watchdog (Automatically restart miner on GPU failure, loss of connection to pool, miner crashes)
  - Failover pools (Automatically connect to failover pool when main pool unavailable, support unlimited number of failover pools)
  - Power efficiency calculator (Show power consuming for each GPU, Sol/W)
  - SSL stratum connection (optional)
  - API / Telemerty
  
  - Fee is 0.65% for Ethash, 5% for BBC, 5% for Cortex, 3% for Cuckaroom29, 3% for BFC, 2% for all other algorithms
  
  # Requirements:
 - CUDA compute compability 5.0+
 - Cuckaroo29 ~ 3.8GB VRAM
 - Cuckatoo31 ~ 7.68GB VRAM
 - Cuckoo29 ~ 3.8GB VRAM
 - Equihash 96,5 ~0.75GB VRAM
 - Equihash 144,5 ~1.75GB VRAM
 - Beam Hash ~2.9GB VRAM
 - Equihash 192,7 ~2.75GB VRAM
 - Equihash 210,9 ~1GB VRAM
 - CUDA 9.0+
