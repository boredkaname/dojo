<div align="center">

# 道場 Dojo

**Apprendre le japonais (JLPT N5 → N3) et l'anglais (B2 → C2), en français, avec un coach IA qui tourne sur ton PC.**

[**Télécharger pour Windows**](https://github.com/boredkaname/dojo/releases/latest) · Windows 10 / 11 · gratuit · mises à jour automatiques

</div>

---

## Ce que tu peux faire

### Japonais
- **Kana** : tableaux hiragana / katakana, lecture, QCM dans les deux sens (kana → rōmaji ou l'inverse), dictée, écriture à la souris, sur des kana seuls, des suites, de vrais mots ou des phrases.
- **Kanji** : les 612 kanji du N5 au N3 classés **par thème** (nombres, famille, se déplacer, émotions…), avec leur sens en français, leurs lectures on'yomi / kun'yomi et des mots d'exemple. Recherche par sens, lecture ou rōmaji, quiz de sens, de lecture et d'écriture.
- **Vocabulaire** : une trentaine de fiches thématiques (nombres et compteurs, heure, famille, nourriture, transports, travail, keigo, onomatopées…) avec exemples et lectures exactes.
- **Grammaire** : tous les points du N5 au N3 expliqués en français, avec exemples et exercices. Tu suis le manuel *Minna no Nihongo* ? Un filtre range les points leçon par leçon.
- **Listes JLPT** et **affichage au choix** : kanji, kanji avec furigana, ou kana seuls selon ton niveau.

### Anglais
- Fiches thématiques B2 → C2 avec phonétique, grammaire avancée, phrasal verbs, idiomes, connecteurs, collocations, faux amis.
- **Oral** : prise de parole chronométrée, shadowing, conversation avec Sensei, dictée vocale.

### Sensei, ton coach IA
Il répond à tes questions, corrige tes phrases, discute avec toi, invente des quiz et corrige tes traductions. Il tourne **entièrement sur ton PC** grâce à [Ollama](https://ollama.com) : rien n'est envoyé sur internet. Tu peux aussi le masquer complètement.

### Et aussi
- **Voix japonaises de style anime** (personnages VOICEVOX) à télécharger au choix, ou la voix de Windows.
- **Réponses à la voix** dans les QCM.
- **Multijoueur** : comptes, salons entre amis, quiz en coopération et scènes d'anime doublées à traduire en équipe.
- **Progression** : XP et ceintures, séries de jours, succès, révisions espacées (boîtes de Leitner).
- 12 thèmes de couleurs et plusieurs polices.

## Installer

1. Télécharge `Dojo-Installeur-vX.Y.Z.exe` depuis la [dernière version](https://github.com/boredkaname/dojo/releases/latest) et lance-le.
2. Windows peut afficher « Windows a protégé votre ordinateur » (l'installeur n'est pas signé) : **Informations complémentaires → Exécuter quand même**.
3. C'est tout : Dojo vérifie les nouvelles versions à chaque lancement et propose de se mettre à jour.

### Activer Sensei (facultatif)
1. Installe [Ollama](https://ollama.com/download).
2. Dans un terminal : `ollama pull gemma4:12b` (plusieurs Go à télécharger ; un PC avec 16 Go de mémoire est conseillé).
3. Relance Dojo : Sensei est prêt. Un autre modèle se choisit dans **Profil → Sensei**.

## Tes données

Ta progression est enregistrée **sur ton PC**. Pour la retrouver sur un autre ordinateur :
- **Profil → Données → Sauvegarder dans mon compte**, puis **Récupérer sur cet appareil** sur l'autre PC (compte Dojo nécessaire, le même que pour le multijoueur) ;
- ou **Exporter** un fichier de sauvegarde et l'**Importer** ailleurs.

Le compte ne sert qu'au multijoueur et à cette sauvegarde : un pseudo et un mot de passe, aucune adresse e-mail.

## Crédits

- Voix : [VOICEVOX](https://voicevox.hiroshiba.jp/) (VOICEVOX Core, modèles de voix ; chaque personnage est crédité dans l'app sous la forme « VOICEVOX:nom »).
- Kanji : [davidluzgouveia/kanji-data](https://github.com/davidluzgouveia/kanji-data) (MIT) ; sens en français écrits pour Dojo.
- Listes JLPT : [elzup/jlpt-word-list](https://github.com/elzup/jlpt-word-list) (MIT).
- Analyse du japonais : [kuromoji.js](https://github.com/takuyaa/kuromoji.js) ; polices : [Fontsource](https://fontsource.org).
- Explications, fiches et exercices : écrits pour Dojo.

Ce dépôt ne contient que les versions publiées de l'application.
