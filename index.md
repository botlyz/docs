# 🚀 Guide Complet Débutant : De la Carte Bancaire à Lighter DEX

> **Pour qui ?** Les personnes qui découvrent la crypto ou qui n'ont jamais utilisé de DEX
> **Objectif** : Comprendre et déposer 100 USDC + 5$ d'ETH sur Lighter DEX pour trader avec Botlyz
> **Budget** : ~105$ · **Durée** : 30-60 min

---

## 📚 Table des matières

1. [Comprendre les bases](#-partie-1--comprendre-les-bases-avant-de-commencer)
   - [CEX vs DEX : quelle différence ?](#cex-vs-dex--quelle-différence-)
   - [Qu'est-ce qu'un wallet crypto ?](#quest-ce-quun-wallet-crypto-)
   - [La seed phrase : ta clé de propriété](#la-seed-phrase--ta-clé-de-propriété)
   - [Qu'est-ce qu'un smart contract ?](#quest-ce-quun-smart-contract-)
   - [Pourquoi Phantom ?](#pourquoi-phantom-)
   - [Qu'est-ce que le réseau Base ?](#quest-ce-que-le-réseau-base-)
2. [Avant de commencer : Quel est ton cas ?](#-partie-2--avant-de-commencer)
3. [Étape 1 : Installer Phantom Wallet](#étape-1--installer-phantom-wallet)
4. [Étape 2 : Approvisionner ton wallet](#étape-2--approvisionner-ton-wallet)
5. [Étape 3 : Se connecter à Lighter DEX](#étape-3--se-connecter-à-lighter-dex)
6. [Étape 4 : Authentifier son compte](#étape-4--authentifier-son-compte-lighter)
7. [Étape 5 : Déposer tes USDC](#étape-5--déposer-tes-usdc-sur-lighter)
8. [Étape 6 : Lier ton téléphone](#étape-6--lier-ton-téléphone-optionnel)
9. [Checklist finale](#-checklist-finale)
10. [Dépannage](#-dépannage)
11. [Glossaire](#-glossaire)

---

## 🎁 Lien d'inscription Lighter (obligatoire pour le bonus)

Utilise ce lien de parrainage pour créer ton compte Lighter :

### 👉 [app.lighter.xyz/?referral=7122767G](https://app.lighter.xyz/?referral=7122767G)

> **Bonus** : En utilisant ce lien, tu bénéficies de **20$ de crédit Botlyz** utilisable sur un cycle de facturation. Pour le réclamer, contacte le support : **@botlyz_manager**

---

# 📖 Partie 1 : Comprendre les bases avant de commencer

> **Pourquoi cette partie ?** Si tu viens d'un exchange classique (Binance, Bybit, XT.com...), tu vas découvrir un monde différent. Prends 5 minutes pour comprendre ces concepts — ça t'évitera des erreurs coûteuses et tu sauras exactement ce que tu fais.

---

## CEX vs DEX : quelle différence ?

### 🏦 CEX (Centralized Exchange) — Ce que tu connais peut-être

**Exemples** : Binance, Bybit, XT.com, Coinbase, Kraken...

Un CEX fonctionne comme une **banque traditionnelle** :

| Aspect | Comment ça marche |
|--------|-------------------|
| **Inscription** | Tu crées un compte avec email + mot de passe |
| **Vérification** | Tu passes un KYC (pièce d'identité) |
| **Tes fonds** | Tu déposes ton argent **chez eux** |
| **Propriété** | L'exchange **détient** tes crypto pour toi |
| **Trading** | Tu trades sur leur plateforme |
| **Retrait** | Tu dois leur **demander** de te rendre tes fonds |

**Avantages** : Simple, interface familière, support client
**Inconvénients** : Tu ne possèdes pas vraiment tes crypto

> ⚠️ **Le problème** : Quand tes crypto sont sur un CEX, tu as une **promesse** qu'ils te les rendront. Mais si l'exchange fait faillite (FTX en 2022), se fait hacker, ou décide de geler ton compte... tu peux tout perdre.

**L'expression célèbre** : *"Not your keys, not your coins"* (Pas tes clés, pas tes crypto)

---

### 🌐 DEX (Decentralized Exchange) — Ce que tu vas utiliser

**Exemples** : Lighter, dYdX, GMX, Uniswap...

Un DEX fonctionne de manière **complètement différente** :

| Aspect | Comment ça marche |
|--------|-------------------|
| **Inscription** | Aucune ! Tu te connectes avec ton wallet |
| **Vérification** | Aucun KYC requis |
| **Tes fonds** | Ils restent dans **ton wallet** jusqu'au dépôt |
| **Propriété** | **Toi seul** contrôles tes crypto via ta seed phrase |
| **Trading** | Les trades sont exécutés par des **smart contracts** |
| **Retrait** | Tu retires **quand tu veux**, sans demander à personne |

**Avantages** : Propriété réelle, pas de KYC, résistant à la censure
**Inconvénients** : Responsabilité totale (si tu perds ta seed phrase, personne ne peut t'aider)

---

### 📊 Comparaison visuelle

```
         CEX (Binance, Bybit...)              DEX (Lighter, dYdX...)
         ========================              ======================

    Toi                                   Toi
     │                                     │
     ▼                                     ▼
┌─────────────┐                      ┌─────────────┐
│  Exchange   │                      │ Ton Wallet  │ ◄── Tu possèdes les clés
│   détient   │                      │  (Phantom)  │
│  tes fonds  │                      └──────┬──────┘
└─────────────┘                             │
     │                                      ▼
     │                              ┌───────────────┐
     ▼                              │Smart Contract │ ◄── Code automatique
┌─────────────┐                     │   (Lighter)   │     et transparent
│ Tu espères  │                     └───────────────┘
│ qu'ils te   │                             │
│ les rendent │                             ▼
└─────────────┘                     ┌───────────────┐
                                    │ Tes fonds     │
                                    │ toujours à    │
                                    │ toi           │
                                    └───────────────┘
```

---

### 🎯 Ce que ça change concrètement pour toi

| Sur un CEX | Sur un DEX (Lighter) |
|------------|---------------------|
| L'exchange peut geler ton compte | Impossible — tu contrôles tes fonds |
| L'exchange peut faire faillite | Le smart contract continue de fonctionner |
| Tu dois faire confiance à l'exchange | Tu fais confiance au code (vérifiable) |
| Support client disponible | Pas de support pour récupérer ta seed phrase |
| Mot de passe oublié ? → Reset par email | Seed phrase perdue ? → Fonds perdus à jamais |

---

## Qu'est-ce qu'un wallet crypto ?

### 🎒 L'analogie du portefeuille

Imagine un **portefeuille physique** :
- Il contient tes billets et cartes
- Toi seul peux l'ouvrir
- Si tu le perds, tu perds ce qu'il y a dedans

Un **wallet crypto** fonctionne de façon similaire, mais avec une différence importante :

> 💡 **Un wallet crypto ne "contient" pas vraiment tes crypto.**
> Il contient les **clés** qui prouvent que tu possèdes ces crypto sur la blockchain.

### 🔑 Comment ça marche vraiment

```
La blockchain (registre public)
================================
│ Adresse 0x123... possède 100 USDC │
│ Adresse 0x456... possède 50 ETH   │
│ Adresse 0x789... possède 200 USDC │
└───────────────────────────────────┘
            ▲
            │ Ton wallet prouve
            │ que tu contrôles
            │ l'adresse 0x123...
            │
    ┌───────────────┐
    │   Phantom     │
    │ (ton wallet)  │
    │               │
    │ Clé privée: ● │ ◄── Cette clé te permet de signer
    │ Clé publique  │     des transactions
    │  = 0x123...   │ ◄── C'est ton "adresse" publique
    └───────────────┘
```

### 📍 Les deux types de clés

| Type | C'est quoi ? | À qui la donner ? |
|------|-------------|-------------------|
| **Clé publique** (adresse) | Commence par `0x...` | **Tout le monde** — c'est comme ton IBAN |
| **Clé privée** | Générée par ta seed phrase | **PERSONNE** — c'est comme le code de ta carte |

---

## La seed phrase : ta clé de propriété

### 🌱 Qu'est-ce que c'est ?

Quand tu crées un wallet, il génère une **seed phrase** (ou phrase de récupération) :

```
exemple mountain laptop ocean carpet
desk chair window forest river
bridge castle garden sunset dream
```

C'est une suite de **12 ou 24 mots** en anglais, dans un ordre précis.

### 🔐 Pourquoi c'est si important ?

Cette seed phrase est **mathématiquement liée** à toutes tes clés privées. Elle permet de :

1. **Recréer ton wallet** sur n'importe quel appareil
2. **Accéder à tous tes fonds** sur toutes les blockchains
3. **Prouver** que tu es le propriétaire légitime

### ⚠️ C'est là que la crypto diffère d'une banque

| Situation | À la banque | Avec ta seed phrase |
|-----------|-------------|---------------------|
| Tu oublies ton mot de passe | Reset par email/SMS | — |
| Tu perds ton téléphone | Tu appelles la banque | Tu réinstalles le wallet avec ta seed phrase |
| Quelqu'un vole tes identifiants | La banque peut bloquer, rembourser | **Tes fonds sont volés définitivement** |
| Tu perds ta seed phrase | — | **Tes fonds sont perdus définitivement** |

### 📝 Comment bien sécuriser ta seed phrase

**✅ À FAIRE :**
- Écrire sur papier (2-3 copies)
- Stocker dans des endroits sûrs et séparés (coffre, chez un proche de confiance...)
- Utiliser une plaque en métal (résiste au feu/eau) pour les gros montants

**❌ À NE JAMAIS FAIRE :**
- Prendre en photo
- Stocker dans le cloud (Google Drive, iCloud...)
- Envoyer par email ou messagerie
- Entrer sur un site web (sauf le wallet officiel)
- Donner à quelqu'un (même le "support technique")

> 🚨 **PERSONNE de légitime ne te demandera jamais ta seed phrase.**
> Ni Phantom, ni Lighter, ni Botlyz, ni aucun support officiel.
> Si quelqu'un te la demande = **ARNAQUE 100%**

---

## Qu'est-ce qu'un smart contract ?

### 🤖 Le concept simple

Un smart contract est un **programme informatique** qui s'exécute automatiquement sur la blockchain.

**Analogie** : Imagine un distributeur automatique
- Tu mets une pièce → Tu appuies sur un bouton → Tu reçois une canette
- Le distributeur suit des règles programmées, sans intervention humaine
- Il ne peut pas "décider" de garder ta pièce et ne rien te donner

Un smart contract fonctionne pareil :
- Tu envoies des crypto → Le code s'exécute → Tu reçois le résultat
- Les règles sont **publiques et vérifiables**
- Il ne peut pas "tricher" — il fait exactement ce qui est programmé

### 🔍 Pourquoi c'est important pour Lighter ?

Quand tu déposes tes USDC sur Lighter :

```
1. Tu approuves le smart contract Lighter
   │
   ▼
2. Tu envoies tes USDC au smart contract
   │
   ▼
3. Le smart contract te crédite sur Lighter
   │
   ▼
4. Tu peux trader (le smart contract gère les ordres)
   │
   ▼
5. Tu peux retirer QUAND TU VEUX
   Le smart contract te renvoie tes fonds
```

**La différence avec un CEX** :
- CEX : Tu envoies à une **entreprise** qui peut décider quoi faire
- DEX : Tu envoies à un **programme** qui ne peut pas dévier de ses règles

### 🛡️ La sécurité "escape hatch" de Lighter

Lighter a une protection spéciale : même si leur interface (site web) tombe en panne, **le smart contract continue de fonctionner**. Tu peux toujours retirer tes fonds directement depuis la blockchain.

---

## Pourquoi Phantom ?

### 👻 Qu'est-ce que Phantom ?

Phantom est un **wallet crypto** sous forme d'extension de navigateur (comme un AdBlock, mais pour la crypto).

### 🌟 Pourquoi on l'utilise pour Lighter ?

| Critère | Phantom | MetaMask | Autres |
|---------|---------|----------|--------|
| Support du réseau Base | ✅ Natif | ✅ | Variable |
| Interface | Simple et claire | Plus technique | Variable |
| Sécurité | Excellente | Excellente | Variable |
| Compatibilité Lighter | ✅ Parfaite | ✅ | Non testée |
| Support multi-chaînes | Solana, Ethereum, Base... | Ethereum uniquement | Variable |

### 📱 Phantom vs l'app d'un exchange

| | App Binance/Bybit | Phantom |
|--|-------------------|---------|
| Qui contrôle tes fonds ? | L'exchange | **Toi** |
| Besoin de KYC ? | Oui | Non |
| Peut être gelé ? | Oui | Non |
| Tu as la seed phrase ? | Non | **Oui** |

---

## Qu'est-ce que le réseau Base ?

### 🔗 Les blockchains, c'est quoi ?

Une blockchain est un **registre numérique partagé** où sont enregistrées toutes les transactions. Il en existe plusieurs :

| Blockchain | Créateur | Cas d'usage | Symbole |
|------------|----------|-------------|---------|
| Bitcoin | Satoshi Nakamoto | Réserve de valeur | BTC |
| Ethereum | Vitalik Buterin | Smart contracts | ETH |
| Solana | Solana Labs | Transactions rapides | SOL |
| **Base** | Coinbase | Transactions pas chères | ETH (sur Base) |

### ⬛ Base : l'essentiel

Base est une **"Layer 2"** d'Ethereum. Concrètement :
- Même sécurité qu'Ethereum
- Transactions **100x moins chères** (~0.001$ au lieu de ~5-15$)
- Même adresse que sur Ethereum (commence par `0x`)
- Logo : carré noir ⬛

### 💡 Pourquoi on utilise Base pour Lighter ?

1. **Frais quasi-nuls** : déposer/retirer coûte ~0.01$ au lieu de 5-15$ sur Ethereum
2. **Rapidité** : transactions confirmées en 2-10 secondes
3. **Simplicité** : même adresse `0x` que tu utilises déjà

> ⚠️ **ATTENTION** : Quand tu envoies des crypto, tu dois **toujours sélectionner le bon réseau**. Envoyer des USDC via Ethereum au lieu de Base = frais 100x plus élevés. Envoyer via un mauvais réseau = **fonds perdus définitivement**.

---

# 🚀 Partie 2 : Avant de commencer

## Quel est ton cas ?

| | Cas 1 | Cas 2 |
|--|-------|-------|
| **Situation** | Tu as déjà de la crypto sur un exchange (Bybit, Binance, XT.com…) ou tu sais acheter dessus | Tu n'as jamais acheté de crypto, tu pars de zéro |
| **Méthode** | Acheter sur l'exchange → Retirer vers Phantom | Acheter directement dans Phantom par carte bancaire |
| **Commence à** | [Étape 1](#étape-1--installer-phantom-wallet) puis [Étape 2 — Cas 1](#cas-1--transfert-depuis-un-exchange) | [Étape 1](#étape-1--installer-phantom-wallet) puis [Étape 2 — Cas 2](#cas-2--achat-par-carte-bancaire-via-phantom) |

---

## Ce dont tu as besoin

Pour trader sur Lighter avec Botlyz, tu dois avoir dans ton wallet Phantom **sur le réseau Base** :

| Quoi | Pourquoi | Montant minimum |
|------|----------|-----------------|
| **USDC** | C'est ta monnaie de trading (stablecoin = 1 USDC ≈ 1$) | 100$ recommandé |
| **ETH** | Pour payer les frais de transaction (appelés "gas") | ~5$ (largement suffisant) |

---

# Étape 1 — Installer Phantom Wallet

> 💻 **Important** : Fais cette étape sur **ordinateur** avec **Google Chrome**. La première connexion à Lighter doit se faire sur PC.

## 1.1 Télécharger Phantom

1. Ouvre **Google Chrome** sur ton ordinateur
2. Va sur le site officiel : **[https://phantom.app/download](https://phantom.app/download)**

   > ⚠️ **ATTENTION AUX ARNAQUES** :
   > - Ne tape JAMAIS "phantom wallet" dans Google et ne clique pas sur les liens sponsorisés
   > - L'URL officielle est **phantom.app** (pas phantom-wallet.com, phantomwallet.io, etc.)
   > - En cas de doute, tape l'URL manuellement

3. Clique sur **"Download for Chrome"**
4. Tu es redirigé vers le **Chrome Web Store** officiel de Google
5. Vérifie que c'est bien l'extension officielle :
   - Éditeur : "Phantom Technologies Incorporated"
   - Des millions d'utilisateurs
6. Clique sur **"Ajouter à Chrome"** → **"Ajouter l'extension"**
7. L'icône Phantom 👻 apparaît dans ta barre d'extensions (en haut à droite)

## 1.2 Créer ton wallet

1. Clique sur l'icône Phantom 👻
2. Clique sur **"Créer un nouveau wallet"** (ou "Create a new wallet")

### Option A : Connexion rapide (Google/Apple)

- Plus simple pour débuter
- Tu devras quand même définir un mot de passe
- Ta seed phrase est générée mais sauvegardée de manière chiffrée

### Option B : Seed Phrase manuelle (recommandé pour les gros montants)

1. Phantom affiche **12 mots** dans un ordre précis
2. **ÉCRIS-LES SUR PAPIER** immédiatement

   ```
   ┌─────────────────────────────────────────┐
   │  1. ______    2. ______    3. ______    │
   │  4. ______    5. ______    6. ______    │
   │  7. ______    8. ______    9. ______    │
   │ 10. ______   11. ______   12. ______    │
   └─────────────────────────────────────────┘
   ```

3. **Vérifie** en relisant à voix haute chaque mot
4. **Range** ce papier dans un endroit sûr
5. Phantom te demande de confirmer certains mots (pour vérifier que tu les as bien notés)

> 🔒 **RAPPEL SÉCURITÉ** : Cette seed phrase = accès TOTAL à tous tes fonds, pour toujours.
> - Ne la photographie JAMAIS
> - Ne la stocke JAMAIS numériquement
> - Ne la donne JAMAIS à personne

### Définir ton mot de passe

1. Crée un mot de passe fort (min. 8 caractères, idéalement 12+)
2. Ce mot de passe protège l'accès **sur cet appareil uniquement**
3. Si quelqu'un a ta seed phrase, ce mot de passe ne le bloquera pas

### Finaliser

1. Choisis un nom d'utilisateur (ou garde celui par défaut)
2. Clique **"Get Started"** ou **"Continuer"**
3. Ton wallet est créé ✅

## 1.3 Activer le réseau Base

Par défaut, Phantom est configuré sur Solana. Il faut activer Base :

1. Clique sur ton **avatar/icône** (en haut à gauche dans Phantom)
2. Va dans **"Settings"** (Paramètres) → **"Active Networks"**
3. Trouve **"Base"** dans la liste
4. Active le toggle (il devient bleu) ✅
5. Retourne à l'écran principal

## 1.4 Passer sur le réseau Base et copier ton adresse

1. Sur l'écran principal de Phantom, clique sur le **nom du réseau** en haut
   - (Il affiche peut-être "Solana" ou "Ethereum")
2. Sélectionne **"Base"** dans la liste (logo ⬛ carré noir)
3. Ton adresse Base s'affiche en haut, sous ton nom
   - Elle commence par `0x` et fait 42 caractères
   - Exemple : `0x1234...abcd`
4. Clique dessus → **"Copy Address"**
5. **Garde cette adresse** — c'est là que tu vas recevoir tes USDC et ETH

> 💡 **Note** : Ton adresse est la même sur Ethereum et Base (les deux commencent par `0x`). C'est normal, Base est une extension d'Ethereum.

---

# Étape 2 — Approvisionner ton wallet

Tu as besoin de **2 choses** sur le réseau Base dans ton Phantom :
- **100 USDC** (ou le montant que tu veux investir)
- **~5$ d'ETH** (pour payer les frais de transaction)

**Choisis ton cas** :

---

## Cas 1 — Transfert depuis un exchange

> Pour ceux qui ont déjà un compte **Bybit, Binance, XT.com** ou autre exchange.

### A. Vérifier que tes fonds sont sur le wallet Spot

> ⚠️ **Important** : Sur les exchanges, tes fonds peuvent être dans différents "portefeuilles" :
> - **Funding** : Où les dépôts arrivent
> - **Spot** : Pour acheter/vendre
> - **Futures/Dérivés** : Pour le trading avec levier
> - **Earn** : Pour le staking/épargne

**Les retraits se font UNIQUEMENT depuis le wallet Spot.**

Si tes fonds sont ailleurs, fais d'abord un **transfert interne** :

**Sur Bybit** :
1. Va dans **Assets** → **Spot**
2. Si le solde est à 0, clique sur **"Transfer"**
3. Sélectionne : De **Funding** → Vers **Spot**
4. Entre le montant → Confirme

**Sur Binance** :
1. Va dans **Portefeuille** → **Vue d'ensemble**
2. Clique sur **"Transférer"**
3. Sélectionne : De **Funding** → Vers **Spot**

**Sur XT.com** :
1. Va dans **Assets** → **Transfer**
2. Sélectionne : De **Funding** → Vers **Spot**

### B. Acheter USDC et ETH (si pas déjà fait)

1. Va dans **"Acheter des crypto"** / **"Buy Crypto"**
2. Achète **100 USDC** par carte bancaire ou virement
3. Achète **~5$ d'ETH** de la même manière
4. Attends que les fonds arrivent sur ton wallet **Spot**

### C. Retirer les USDC vers Phantom

1. Va dans **"Retrait"** / **"Withdraw"**
2. Sélectionne **USDC**
3. Colle ton **adresse Phantom Base** (le `0x...` copié à l'Étape 1)

4. **⚠️ CHOIX DU RÉSEAU — ÉTAPE CRITIQUE ⚠️**

   Sélectionne le réseau **"Base"** :

   | Ce que tu vois | Ce qu'il faut faire |
   |----------------|---------------------|
   | Base (logo ⬛ carré noir) | ✅ **SÉLECTIONNER** |
   | ERC-20 / Ethereum | ❌ NE PAS sélectionner (frais 5-15$) |
   | TRC-20 / Tron | ❌ NE PAS sélectionner (fonds perdus) |
   | BEP-20 / BSC | ❌ NE PAS sélectionner (fonds perdus) |
   | Autre réseau | ❌ NE PAS sélectionner (fonds perdus) |

   > 🚨 **ATTENTION** : Si tu choisis le mauvais réseau, tes fonds seront **perdus définitivement**. Il n'y a aucun moyen de les récupérer. Vérifie 3 fois avant de confirmer.

5. Entre le montant : **100 USDC**
6. Confirme le retrait (code email/SMS/2FA)

### D. Retirer l'ETH vers Phantom

1. Même processus : **"Retrait"** → **ETH**
2. Colle la **même adresse Phantom** (`0x...`)
3. **⚠️ Sélectionne le réseau "Base"** (⬛)
4. Entre : **~5$ d'ETH** (environ 0.002 ETH)
5. Confirme le retrait

### E. Attendre la réception

- **Délai typique** : 5-30 minutes
- Tu peux suivre le statut dans **l'historique des retraits** de l'exchange
- Les fonds apparaîtront dans Phantom automatiquement

**➡️ Une fois reçus, passe à l'[Étape 3](#étape-3--se-connecter-à-lighter-dex)**

---

## Cas 2 — Achat par carte bancaire via Phantom

> Pour ceux qui n'ont **jamais acheté de crypto**.

### A. Acheter 100 USDC sur Base

1. Ouvre Phantom → vérifie que tu es sur le **réseau Base** (⬛)
2. Clique sur **"Buy"** (Acheter)
3. Dans la recherche, tape **"USDC"**
4. **Important** : Sélectionne l'USDC avec le **logo Base** (⬛ carré noir)
   - Ne sélectionne PAS l'USDC Ethereum, Solana ou autre
5. Entre le montant : **100$**

6. Phantom affiche les offres de plusieurs fournisseurs :

   | Fournisseur | Frais | Tu reçois | Recommandation |
   |-------------|-------|-----------|----------------|
   | **Coinbase Pay** | ~0% | ~100 USDC | ✅ Meilleur choix |
   | **Transak** | ~1% | ~99 USDC | ✅ Bon choix |
   | **MoonPay** | ~4.5% | ~95.50 USDC | ⚠️ Frais élevés |

7. Sélectionne le fournisseur avec le **meilleur taux affiché**

8. **Premier achat = Vérification d'identité (KYC)**

   Le fournisseur te demandera :
   - Ta pièce d'identité (passeport, CNI ou permis de conduire)
   - Ton numéro de téléphone
   - Parfois un selfie

   > 💡 C'est une exigence légale pour les achats par carte bancaire. Cette vérification est faite par le fournisseur (Transak, MoonPay...), pas par Phantom ni par Lighter.

   Durée : environ 5-10 minutes

9. Entre les informations de ta carte bancaire → Confirme le paiement

10. **Délai de réception** : 5-60 minutes selon le fournisseur

### B. Acheter ~5$ d'ETH sur Base

1. Clique sur **"Buy"** dans Phantom
2. Cherche **"ETH"** → sélectionne celui avec le **logo Base** (⬛)
3. Entre **5$**
4. Choisis un fournisseur → Paye par carte
5. L'ETH arrive en quelques minutes

> 💡 **Pourquoi 5$ d'ETH suffit largement** :
> Sur le réseau Base, une transaction coûte environ **0.001$ à 0.005$**.
> Avec 5$ d'ETH, tu peux faire **plus de 1000 transactions** !

**➡️ Une fois reçus, passe à l'[Étape 3](#étape-3--se-connecter-à-lighter-dex)**

---

# Étape 3 — Se connecter à Lighter DEX

> 💻 **Cette étape doit se faire sur ordinateur**, pas sur téléphone.

## 3.1 Accéder à Lighter

1. Ouvre **Google Chrome** (avec Phantom installé)
2. Va sur le lien de parrainage Botlyz :

   ### 👉 **[app.lighter.xyz/?referral=7122767G](https://app.lighter.xyz/?referral=7122767G)**

   > ⚠️ Vérifie bien l'URL : **app.lighter.xyz** (pas lighter.com, lighterxyz.io, etc.)

## 3.2 Connecter ton wallet

1. Clique sur **"Connect Wallet"** (en haut à droite)
2. Une liste de wallets apparaît

3. **Sélectionne "Phantom"** dans la liste

   > 💡 **Si tu ne vois que "MetaMask"** : Clique dessus quand même. Phantom interceptera automatiquement la connexion car il est compatible avec les connexions MetaMask.

4. Un popup Phantom s'ouvre :
   - Vérifie que le site est bien `lighter.xyz`
   - Clique sur **"Connect"**

5. Ton adresse `0x...` apparaît en haut à droite de l'interface Lighter ✅

## 3.3 Ce qui se passe techniquement

Quand tu connectes ton wallet :
- Tu **autorises** Lighter à voir ton adresse publique
- Tu ne donnes **PAS** accès à tes fonds
- Tu ne donnes **PAS** ta clé privée
- Lighter peut maintenant te proposer de signer des transactions

> 💡 Connecter un wallet à un DEX, c'est comme montrer ta carte d'identité : tu prouves qui tu es, mais tu ne donnes pas accès à ton compte bancaire.

---

# Étape 4 — Authentifier son compte Lighter

Après la connexion, Lighter affiche un écran d'authentification :

```
┌──────────────────────────────────────┐
│           Authenticate               │
│      Access Lighter account          │
│                                      │
│  Sign the messages in order to       │
│  authenticate.                       │
│                                      │
│  [ ] I'll use a multi-sig/smart     │
│      wallet                          │
│                                      │
│  [✓] Remember Me                     │
│                                      │
│        [ Authenticate ]              │
└──────────────────────────────────────┘
```

## Ce qu'il faut faire

1. **❌ NE COCHE PAS** "I'll use a multi-sig/smart wallet"
   - Cette option est pour les utilisateurs avancés avec des wallets multi-signatures
   - Si tu coches par erreur, déconnecte-toi et recommence

2. **✅ COCHE** "Remember Me"
   - Ça évite de devoir re-signer à chaque visite

3. Clique sur **"Authenticate"**

4. Phantom ouvre un popup te demandant de **signer un message**

   > 💡 **C'est quoi une signature de message ?**
   > C'est comme signer un document. Tu prouves que tu contrôles cette adresse.
   > - Ce n'est **PAS** une transaction
   > - Ça ne coûte **AUCUN frais** (pas de gas)
   > - Ça ne déplace **AUCUN** de tes fonds

5. Clique sur **"Sign"** dans Phantom

6. Ton compte Lighter est maintenant actif ✅

---

# Étape 5 — Déposer tes USDC sur Lighter

Maintenant que tu es connecté et authentifié, il faut déposer tes USDC pour pouvoir trader.

## 5.1 Choisir la méthode de dépôt

Sur Lighter, tu verras deux options :

```
┌─────────────────────────────────────────────────────┐
│  ○ Deposit from connected wallet                    │
│    Use MetaMask, WalletConnect, or another          │
│    provider to deposit funds from your crypto       │
│    wallet                                           │
│                                                     │
│  ○ Deposit from external account                    │
│    Transfer funds from Binance or other exchanges,  │
│    chains like Solana, and other wallets            │
└─────────────────────────────────────────────────────┘
```

### ✅ Sélectionne **"Deposit from connected wallet"**

C'est la bonne option car tes USDC sont déjà dans ton Phantom connecté.

> 💡 L'autre option ("Deposit from external account") est utile si tu veux envoyer directement depuis un exchange, mais c'est plus complexe et risqué pour les débutants.

## 5.2 Configurer le dépôt

1. **Select Token** → Sélectionne **"USDC (Perps)"**

   > 💡 "Perps" = Perpetuals = c'est le token utilisé pour le trading de contrats perpétuels sur Lighter

2. **Deposit From** → Sélectionne **"Base"** (⬛ carré noir)

3. Tu verras ton **Available Balance** (solde disponible)
   - C'est le montant d'USDC dans ton Phantom sur Base
   - Si ça affiche 0, vérifie que tu es bien sur le réseau Base dans Phantom

4. Entre le montant : **100 USDC** (ou le montant souhaité)
   - Minimum : 5 USDC

## 5.3 Confirmer le dépôt

1. Clique sur **"Deposit"**

2. Phantom ouvre un popup avec les détails :

   ```
   ┌─────────────────────────────────┐
   │  Transaction Request            │
   │                                 │
   │  Dépôt USDC vers Lighter        │
   │  Montant : 100 USDC             │
   │                                 │
   │  Estimated fee: ~$0.005         │
   │  Network: Base                  │
   │                                 │
   │  [ Reject ]    [ Confirm ]      │
   └─────────────────────────────────┘
   ```

3. Vérifie les détails :
   - Le montant est correct
   - Les frais sont minimes (~0.01$ sur Base)
   - Le réseau est bien Base

4. Clique sur **"Confirm"**

## 5.4 Attendre la confirmation

- La transaction est envoyée sur la blockchain Base
- **Délai** : 2-10 secondes généralement
- Tu peux voir le statut dans Phantom (activité récente)
- Une fois confirmée, ton solde apparaît sur Lighter

## 5.5 Ce qui se passe techniquement

Quand tu déposes sur Lighter :

```
Ton Phantom                   Smart Contract               Lighter
    │                             Lighter                      │
    │                                │                         │
    │  1. Tu envoies 100 USDC  ────►│                         │
    │     au smart contract          │                         │
    │                                │                         │
    │                                │  2. Le contrat vérifie  │
    │                                │     et enregistre       │
    │                                │                         │
    │                                │  3. Crédit sur Lighter ─┼───► Tu vois 100$
    │                                │                         │     sur l'interface
```

> 💡 **Important** : Tes fonds sont maintenant dans le smart contract Lighter, pas dans ton Phantom. Mais tu peux les retirer **à tout moment** sans avoir besoin de l'autorisation de qui que ce soit.

---

# 🎉 C'est terminé !

Tu es maintenant prêt à trader avec Botlyz sur Lighter DEX.

> 💬 **N'oublie pas** : Contacte **@botlyz_manager** pour réclamer tes **20$ de crédit Botlyz** (si tu as utilisé le lien de parrainage).

---

# Étape 6 — Lier ton téléphone (optionnel)

L'application mobile Lighter existe et te permet de suivre tes positions depuis ton téléphone.

> ⚠️ **Rappel** : La **première connexion** doit se faire sur **ordinateur**. Tu ne peux pas créer ton compte depuis l'app mobile directement.

## 6.1 Sur ton ordinateur

1. Connecte-toi à Lighter (si pas déjà fait)
2. Clique sur ton **profil/icône** en haut à droite
3. Sélectionne **"Link Mobile Device"**
4. Un **QR code** s'affiche à l'écran

## 6.2 Sur ton téléphone

1. Télécharge l'app **Lighter** (App Store / Google Play)
2. Ouvre l'app
3. Sélectionne l'option pour **scanner un QR code** ou **lier un appareil**
4. Scanne le QR code affiché sur ton ordinateur

## 6.3 C'est fait !

Ton téléphone est maintenant lié à ton compte Lighter. Tu peux :
- Voir tes positions en temps réel
- Suivre tes PnL
- Recevoir des notifications

> 💡 L'app mobile est en lecture seule par défaut. Pour des raisons de sécurité, certaines actions (comme les retraits importants) peuvent nécessiter une confirmation sur ordinateur.

---

# 📋 Checklist Finale

Coche chaque étape une fois complétée :

**Installation**
- [ ] Phantom installé sur **Chrome** depuis [phantom.app/download](https://phantom.app/download)
- [ ] Wallet créé
- [ ] Seed phrase notée sur papier et rangée en lieu sûr
- [ ] Réseau **Base** activé dans Phantom

**Approvisionnement**
- [ ] **100 USDC** (ou plus) reçus sur Base dans Phantom
- [ ] **~5$ d'ETH** reçus sur Base dans Phantom

**Connexion Lighter**
- [ ] Connecté à Lighter via le [lien parrainage](https://app.lighter.xyz/?referral=7122767G) (sur ordinateur)
- [ ] Authentifié avec :
  - [ ] "Remember Me" ✅ coché
  - [ ] "multi-sig/smart wallet" ❌ NON coché
- [ ] Dépôt effectué : USDC (Perps) depuis Base

**Bonus**
- [ ] Crédit Botlyz de 20$ réclamé auprès de **@botlyz_manager**
- [ ] (Optionnel) Téléphone lié via "Link Mobile Device"

---

# 🔧 Dépannage

## Problèmes fréquents et solutions

| Problème | Cause probable | Solution |
|----------|---------------|----------|
| **Transaction échouée au dépôt** | Pas assez d'ETH pour les frais | Ajoute de l'ETH **sur Base** (pas Ethereum mainnet) |
| **"Available Balance" affiche 0** | USDC sur le mauvais réseau | Vérifie que tes USDC sont sur **Base** dans Phantom |
| **Phantom ne se connecte pas** | Conflit d'extensions | Désactive les autres wallets (MetaMask...), vide le cache |
| **USDC non reçus** | Transaction en cours | Attends jusqu'à 60 min. Vérifie sur [basescan.org](https://basescan.org) |
| **Retrait de l'exchange bloqué** | Vérification en cours | Vérifie le statut dans l'historique de l'exchange |
| **Fonds sur Funding au lieu de Spot** | Mauvais portefeuille | Transfère de Funding → Spot avant de retirer |
| **"multi-sig" coché par erreur** | Mauvaise option | Déconnecte le wallet, rafraîchis la page, recommence |
| **Dépôt confirmé mais pas de solde sur Lighter** | Délai de traitement | Attends quelques minutes, rafraîchis la page |

## Comment vérifier une transaction

1. Va sur [basescan.org](https://basescan.org)
2. Colle ton adresse `0x...` ou le hash de transaction
3. Tu verras :
   - Le statut (Success / Pending / Failed)
   - Les détails de la transaction
   - Le montant transféré

## Besoin d'aide ?

- **Support Botlyz** : [@botlyz_manager](https://t.me/botlyz_manager) sur Telegram
- **Documentation Lighter** : [docs.lighter.xyz](https://docs.lighter.xyz)

---

# 💰 Récapitulatif des coûts

| Étape | Cas 1 (Exchange) | Cas 2 (Carte via Phantom) |
|-------|------------------|---------------------------|
| Installer Phantom | Gratuit | Gratuit |
| Acheter 100 USDC | Frais exchange (~0.1-1%) | 0-4.50$ de frais |
| Acheter 5$ ETH | Frais exchange (~0.1-1%) | 0-0.25$ de frais |
| Retrait vers Phantom | Frais retrait (~0.1-1 USDC) | — (déjà dans Phantom) |
| Dépôt sur Lighter | ~0.01$ gas | ~0.01$ gas |
| **Total estimé** | **~106-108$** | **~105-110$** |

---

# 📚 Glossaire

| Terme | Définition simple |
|-------|-------------------|
| **Blockchain** | Registre numérique partagé où toutes les transactions sont enregistrées de façon permanente |
| **CEX** | Centralized Exchange — Plateforme d'échange gérée par une entreprise (ex: Binance, Bybit) |
| **DEX** | Decentralized Exchange — Plateforme d'échange gérée par des smart contracts (ex: Lighter) |
| **ETH** | Ether — La crypto native d'Ethereum, utilisée pour payer les frais de transaction |
| **Gas** | Frais payés pour exécuter une transaction sur la blockchain |
| **KYC** | Know Your Customer — Vérification d'identité obligatoire sur les plateformes régulées |
| **Layer 2 (L2)** | Réseau construit au-dessus d'Ethereum pour des transactions plus rapides et moins chères |
| **Perps** | Perpetuals — Contrats dérivés sans date d'expiration, permettant le trading avec levier |
| **Seed Phrase** | Suite de 12-24 mots permettant de restaurer un wallet — NE JAMAIS PARTAGER |
| **Smart Contract** | Programme automatique sur la blockchain qui exécute des règles prédéfinies |
| **Stablecoin** | Crypto dont la valeur est stable (1 USDC ≈ 1$) |
| **USDC** | USD Coin — Stablecoin émis par Circle, adossé au dollar américain |
| **Wallet** | Portefeuille crypto qui stocke les clés permettant d'accéder à tes fonds |

---

# ℹ️ Informations Lighter DEX

| Caractéristique | Détail |
|-----------------|--------|
| **Type** | DEX perpétuel (carnet d'ordres on-chain, ZK-rollup) |
| **Frais de trading** | 0% maker / 0% taker (compte standard) |
| **Levier maximum** | Jusqu'à 50x sur BTC/ETH |
| **KYC requis** | Non |
| **Sécurité** | Non-custodial + escape hatch |
| **App mobile** | Disponible (iOS/Android), mais première connexion sur PC obligatoire |

### Qu'est-ce que l'escape hatch ?

C'est une fonction de sécurité unique : même si l'interface de Lighter (le site web) tombe en panne ou est censuré, tu peux toujours retirer tes fonds directement depuis la blockchain en interagissant avec le smart contract. Tes fonds ne sont jamais "bloqués".

---

> 📩 **Support Botlyz** : [@botlyz_manager](https://t.me/botlyz_manager)
> 🔗 **Lien parrainage** : [app.lighter.xyz/?referral=7122767G](https://app.lighter.xyz/?referral=7122767G)
