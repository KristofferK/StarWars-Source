
     _    _  _                  _                                    
    | |  | || |                | |                                   
    | |__| || |_ _ __       ___| |_ __ _ _ ____      ____ _ _ __ ___            _   __  
    | '_ \__   _| '_ \     / __| __/ _` | '__\ \ /\ / / _` | '__/ __|      __ _/ | /  \ 
    | |_) | | | | |_) |    \__ \ || (_| | |   \ V  V / (_| | |  \__ \      \ V / || () |
    |_.__/  |_| | .__/     |___/\__\__,_|_|    \_/\_/ \__,_|_|  |___/       \_/|_(_)__/  
                | |                                               
                |_|                                               

    ... a CS:S mod
    
    Version 1.0

    this code was written by me, b4p.
    
    this is a server-side mod that will only run on dedicated servers.
    
    this mod should stick to the original CS:S gameplay as much as possible.  <-- read that twice
    
    please do not do any of the following:    
        do not distribute modified versions of this code
        do not drastically alter this code for use on public (non-passworded) servers
        do not distribute the materials, models, or sounds without README.txt and es_b4p_starwars.txt
    

    important notes for admins: 
        
        say "swadmin" in game to access the admin menu
        
        i added classic mode so that only 2 models are needed.
        server admins need to use sv_downloadurl so that clients can download the models quickly.
        if you do no use sv_downloadurl it is likely that very few people will want to play on your server.
        if you're using sv_downloadurl look into using bzip2.
        sv_downloadurl requires a webhost.  if you dont know what that is, just try using classic mode.
        links for sv_downloadurl and bzip2:
            http://forums.mattie.info/cs/forums/viewtopic.php?t=516
            http://forums.srcds.com/showthread.php?tid=1077
            http://www.mani-admin-plugin.com/oldsite/forums/viewtopic.php?t=8549


    notes:  

        other than bug fixes please do not modify this code (unless your server is passworded)
        
        changing default values for things is ok.
        now, having said that...
        please do not modify this code to contain any leveling systems, or experience-based systems.
        this mod was never intended to include such things.  there are already plenty of great
        mods that include that functionality.  

        this mod should stick to the original CS:S gameplay as much as possible.  <-- read that twice

        please try out classic mode on your servers.  
        it's really cool seeing a whole team of stormtroopers coming at you.
        
        in classic mode, if your server is configured properly, there will be only 2 models to download.
        this makes it much easier for people to join.
            
    
    basic features:
    
        - 12 starwars models
            - boba fett
            - c3po
            - chewbacca
            - imperial officer
            - jawa
            - rebel soldier
            - rodian (aka greedo)
            - snow trooper
            - storm trooper
            - tusken raider
            - vader
            - yoda            
        - menu for selecting models (if not in classic mode)
        - admin menu
        - weapon lasers
            - laser sounds for weapons
            - ability to adjust laser
                - style
                - origin
                - team colors
                - start/end width
        - light saber sound effects for knife
        - boba fett has a working jetpack with sounds
        - jedi have force lightning

    
    required plugins (these may change in the future!):
    
        eventscripts v2.1.1.366+:
            http://forums.eventscripts.com/viewtopic.php?f=128&t=40765
    
    
    credits:
 
        almost all meshes, textures, and sounds created by raven software (http://www.ravensoft.com/)
        for "Jedi Knight 3: Jedi Academy".

        many models originated here (basemodels.zip):
        http://jediknight2.filefront.com/file/Raven_Animation_and_Model_Source_Files_Part_2;26625

        vader came from here (vadervm2.2.zip):
        http://jediknight2.filefront.com/file/Darth_Vader;41054
        credits for vader: Mars Marshall "NeoMarz1"

        animations came from Counter-Strike Source
        
        skeletons were heavily modified versions of the CS:S rig provided in the HL2 SDK
        all modifications to this rig were made by b4p
        
        all character models were manually converted to CS:S by b4p
        
        all code below was written by b4p
        but broke after orangebox-engine-update (Summer 2010)
        fixed by thecheetah afterwards
        
        special thanks to:
            SoftImage for making SoftImage|XSI (www.softimage.com)
            mattie and awuh0 over at forums.mattie.info/cs/forums
        
        
