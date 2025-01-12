# M1_INFO_cryptography
## 1. Introduction
### 1.1 Enjeux et définitions
### 1.2 Histoire et évolution de techniques
### 1.3 Perspectives actuelles

## 2. Chiffrements symétriques
2.1 Masque jetable
2.2 Notions d'entropie et d'aléa
2.3 Chiffrement de flux
2.4 Chiffrement par bloc
2.4.1 Réseau de substitution-permutation (AES)
2.4.2 Réseau de Feistel (DES)
2.4.3 Modes d'opération (ECB, CBC, CTR, CFB, OFB)

3. Sécurité des chiffrements
3.1 Indistinguabilité calculatoire, adversaire, challenger, oracle, avantage, malléabilité
3.2 Attaque sur texte chiffré seul
3.3 Attaque à texte clair connu
3.4 Attaque à texte clair choisi
3.5 Attaque à texte chiffré choisi

4. Chiffrements asymétriques
4.1. Notions mathématiques
4.1.1 Propriétés des nombres premiers
4.1.2 Arithmétique modulaire et structures algébriques (groupe, corps fini)
4.2. Cryptographie asymétrique
4.2.1 Chiffrement RSA
4.2.2 Echange de clé Diffie-Hellman
4.2.3 Cryptographie sur courbes elliptiques

5. Intégrité des données
5.1 Rappels : fonction de hachage, détection d'erreurs (CRC, checksum)
5.2 Fonctions de hachages cryptographiques
5.2.1 Construction de Merkle-Damgård (MD2, MD5, SHA-1, SHA-2, RIPEMD)
5.2.2 Construction de l’éponge (SHA-3)
5.3 Retour sur les chiffrements symétriques : ChaCha20

6. Authentification
6.1 Signature numérique
6.1.1 DSA
6.1.2 Certificat de clé publique
6.1.3 Horodatage certifié
6.2 Code d'authentification de message (HMAC, CBC-MAC, GMAC)
6.3 Chiffrement authentifié (GCM, CCM, Poly1305)
6.4 Authentification défi-réponse
6.5 Authentification sans mot de passe
6.6 Authentification mutuelle : Kerberos

7. Protocole SSH (secure shell)
Application de toutes les primitives cryptographiques abordées précédemment
