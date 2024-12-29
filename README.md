## BRIEF OVERVIEW OF PROJECT
- Bu bir akıllı sözleşme projesidir. Kullanıcılar burada kripto varlıklarını stake ederek pasif gelir elde edebilir. Stake edilen miktar boyunca yıl boyunca ödül alma şansları vardır. Sözleşme merkeziyetsiz bir sistem üzerinde çalışır ve oldukça güvenilir ve şeffaftır. Proje yatırımcılar, kripto meraklılarına vb hitap ediyor. Gelecekte ek özellikler eklenecektir. 

## INSTRUCTIONS FOR HOW TO  COMPILE AND DEPLOY THE SMART CONTRACT.

### Compile Insturctions
- sc-meta ve mxpy kütüphanelerin kurulması 
- Kurulum sonrasında sözleşmenin yazılması
- Yazılan sözleşmenin build edilmesi.
### Deploy Insturctions
- Önce cüzdan bağlantısının gerçekleştirilmesi.
- Sözleşmeyi istenilen ağa bağlanılması (devnet,testnet,mainnet)

## A DESCRIPTION OF THE FUNCTIONS AND FEATURES OF THE SMART CONTRACT 

### Functions:
- Stake : Kullanıcı EGLD token'larını stake eder. Stake edilen miktar, kullanıcının mevcut stake miktarına eklenir.
- Unstake : Kullanıcı stake ettiği tokenları geri çekebilir.
- Claim_rewards: Kullanıcı, stake ettikleri tokenlar üzerinden kazandıkları ödülleri talep edebilir.
- Calculate_rewards : Kullanıcının stake ettiği miktara göre ödülleri hesaplar.
- Staked_addresses : Tüm stake yapmış kullanıcıların adreslerini döndürür.
- Staking_position : Kullanıcıların staking pozisyonlarını döndürür.
- Apy :Yıllık getiri oranını (APY) tutar.

### Features
- Stake Tokens: Kullanıcılar EGLD token'larını kontrata stake edebilir. Stake edilen tokenlar, belirli bir süre boyunca kontratta tutulur ve bu süreç boyunca kullanıcılar, stake ettikleri miktara göre ödül kazanır.
- Unstake Tokens: Kullanıcılar, stake ettikleri tokenları geri çekebilir. Stake edilen miktar geri çekilebilirken, ödüller de kullanıcıya aktarılır. Eğer kullanıcı tüm stake miktarını geri çeker ve hiçbir token bırakmazsa, staking pozisyonu sıfırlanır.
- Claim Rewards : Kullanıcılar stake ettikleri tokenlar üzerinden kazandıkları ödülleri talep edebilirler. Ödüller, staking süresi ve miktarına göre hesaplanır ve kullanıcıya gönderilir.
- Reward Calculation: Kontrat, kullanıcıların stake ettikleri miktar üzerinden kazandıkları ödülleri hesaplar. Ödüller, yıllık getiri oranı (APY) ve stake süresi dikkate alınarak hesaplanır.

## IMAGES OF THE USER INTERFACE
![image_alt](https://github.com/user-attachments/assets/e35201ad-ff51-41aa-9066-774810c34a04)
![image_alt](https://github.com/user-attachments/assets/fd1efbe3-2ded-4c2e-8544-d9b42f2dbe18)
![image_alt](https://github.com/user-attachments/assets/6e4c64af-6e68-439e-a94b-e1d68232e2eb)
![image_alt](https://github.com/user-attachments/assets/8e5b605b-b591-4f14-95d3-5c4a09971106)
![image_alt](https://github.com/user-attachments/assets/c8588618-d056-4ab1-bbc3-ba080087542c)

