# visio-doc
Visio is a group of projects related to opensource videoconference tools (plugin, addons, .. for jitsi, BBB, ...), 
this project is for general documentation about this group

# Where are documents
Most of office document (text, slide, ...) are in an Osmose community 
https://osmose.numerique.gouv.fr/jcms/p_4701387/fr/communautes-des-equipes-projets-bbb-jitsi-du-secteur-public

# Who is participate
* DINUM
* MTECT
* MENJ
* RENATER
* FUN
* ARAWA
* MEFSIN
* SNAPCOM

# Main Goal
*	Proposer des outils performants pour les agents
*	Eco responsabilité
*	Souveraineté : maitriser le code logiciel libre / RGPD / Cloud / DevOps
* Projets interministériels sur visioconférence
*	Partage des chantiers
*	Identifier les synergies sans bloquer les avancées en propre

# Existing project
*	MTE/WCE
    * JITSI Meet Metrics : analyse durant les conférences ; publié GitHub du MTE 
    *	Ajout des appels téléphoniques sur WCE avec Voxify ; trunk SIP dédié DINUM ; 700 canaux disponibles
    *	Multi-Cloud : NUBO (interministériel)/MTE/OVH(public) ; PTR (plateforme Temps-Réel entre les différents ponts), OVH; 
      pour avoir une transparent utilisateurs avec des gains sur la performance
*	RENATER
    *	Vidéo GW SIP/JITSI
    *	JitsiMeetTestBrowserTool :
        *	Interface de Test Navigateur de Rendez-Vous en mode autonome.
    * Jitsi-SAML2JWT : brique autonome authentification
*	MEFSIN /SNAPCOM
    *	JITSIBOX
        *	Equipement d’une salle avec intelligence pour rejoindre une conférence JITSI
    *	JITSIBOX Manager
        *	Besoin MDM, manager un parc (MAJ, déploiement…)
    *	Bouton Outlook ; générer des invitations / planification
        * Rejoint le confmapper de RENATER 
*	FUN
    *	JITSI/MARSHA
        * Transcription et sous titrage multilingue
        * Captation dans l’outil de webinaire de FUN (VOD+live)
    *	BBB, Ajout à scalelite de la gestion de compte Multi-tenant – échange ARAWA
    * BBB	Transcription et sous titrage multilingue ; live et post conférence sur enregistrement
    * BBB	Ajout streaming RTMP
    * BBB	Interconnexion équipement SIP
    * BBB	Pas de selftest
*	MENJ/ARAWA
    *	DiVim’s : scaling, open sourcé https://gitlab.com/arawa/DiViM-S
    *	Permettre les présentations de NextCLoud depuis la conférence
    *	Popup sur les enregistrements de conférences : rappel des règles à la connexion, information au démarrage de l’enregistrement
    *	Breakout rooms : 
        * remonter en salle principale ce qui est partagé en groupe
        * informer des bascules entre les groupes pour finaliser
    * tableau blanc, remplacement par pldraw
    * permettre l’export des présentations en PDF pour les animateurs
    * Warning de fin de meeting
    * UX/UI : 
        *	locker le chat et agir sur les post anormaux (ex : suppression), modération groupée
        *	prendre une liste de participants / présence
        * layout évolués – pas uniquement mode présentation 
        * zip de contenus en fin de session pour le modérateur
        * question/réponse séparé du chat

