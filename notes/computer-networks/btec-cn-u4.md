
# 4 Be able to make networked systems secure

  - Securing a system: 
    - Methods:
      - Passwords, Authorization permissions and Access Control Lists 
        - Most Commonly Used Password
          - 123456
          - 123456789
          - qwerty
          - 12345678
          - 111111
          - 1234567890
          - 1234567
          - password
        - Passwords Cracking Techniques
          - Brute force
            - A brute-force attack consists of an attacker trying many passwords or passphrases with the hope of eventually guessing correctly. The attacker systematically checks all possible passwords and passphrases until the correct one is found.
            - Just as a criminal might break into, or "crack" a safe by trying many possible combinations, a brute force cracking application proceeds through all possible combinations of legal characters in sequence. Brute force is considered to be an infallible, although time-consuming, approach.
            - Brute force attacks work by calculating every possible combination that could make up a password and testing it to see if it is the correct password. As the password’s length increases, the amount of time, on average, to find the correct password increases exponentially. This means short passwords can usually be discovered quite quickly, but longer passwords may take decades.
          - Dictionary Attack
            - A dictionary attack is based on trying all the strings in a pre-arranged listing, typically derived from a list of words such as in a dictionary (hence the phrase dictionary attack).
            - In contrast to a brute force attack, where a large proportion of the key space is searched systematically, a dictionary attack tries only those possibilities which are deemed most likely to succeed.
            - Dictionary attacks often succeed because many people have a tendency to choose short passwords that are ordinary words or common passwords, or simple variants obtained, for example, by appending a digit or punctuation character.
            - Dictionary attacks are relatively easy to defeat, e.g. by using a passphrase or otherwise choosing a password that is not a simple variant of a word found in any dictionary or listing of commonly used passwords.
          - Rainbow Table Attack
            - A rainbow table is a precomputed table for reversing cryptographic hash functions, usually for cracking password hashes.
            - Tables are usually used in recovering a plaintext password up to a certain length consisting of a limited set of characters.
            - It is a practical example of a space/time trade-off, using less computer processing time and more storage than a brute-force attack which calculates a hash on every attempt, but more processing time and less storage than a simple lookup table with one entry per hash.
          - Phishing
            - Phishing is the attempt to obtain sensitive information such as usernames, passwords, and credit card details (and, indirectly, money), often for malicious reasons, by disguising as a trustworthy entity in an electronic communication.
            - Phishing is typically carried out by email spoofing or instant messaging, and it often directs users to enter personal information at a fake website, the look and feel of which are almost identical to the legitimate one.
            - Communications purporting to be from social web sites, auction sites, banks, online payment processors or IT administrators are often used to lure victims.
            - Phishing emails may contain links to websites that are infected with malware.
          - Social Engineering
            - Social engineering, in the context of information security, refers to psychological manipulation of people into performing actions or divulging confidential information.
            - The attacks used in social engineering can be used to steal employees' confidential information. 
            - The most common type of social engineering happens over the phone.
            - One example of social engineering is an individual who walks into a building and posts an official-looking announcement to the company bulletin that says the number for the help desk has changed. So, when employees call for help the individual asks them for their passwords and IDs thereby gaining the ability to access the company's private information.
            - Another example of social engineering would be that the hacker contacts the target on a social networking site and starts a conversation with the target. Slowly and gradually, the hacker gains trust of the target and then uses it to get access to sensitive information like password or bank account details.
            - Other examples of social engineering attacks are criminals posing as exterminators, fire marshals and technicians to go unnoticed as they steal company secrets.
      - Backing up
        - Having data backed up is the cornerstone of any disaster recovery plan. Without backups, a simple hard drive failure can set your company back days or even weeks. In fact, without backups, your company’s very existence is in jeopardy. For schools this is a legality and three backups are necessary, nightly, weekly and off site copy. 
        - The main goal of backups is simple:Keep a spare copy of your network’s critical data so that, no matter what happens, you never lose more than one day’s work. The easiest way to do this is to make a copy of your files every day. If that’s not possible, techniques are available to ensure that every file on the network has a backup copy that’s no more than one day old.
        - The goal of disaster planning is to make sure that your company can resume operations shortly after a disaster occurs, such as a fire, earthquake, or any other imaginable calamity. Backups are a key component of any disaster recovery plan, but disaster planning entails much more.
        - The most common media for making backup copies of network data is tape. Depending on the make and model of the tape drive, you can copy as much as 80GB of data onto a single tape cartridge.
        - All versions of Windows come with a built-in backup program. In addition, most tape drives come with backup programs that are often faster or more flexible than the standard Windows backup. You can also purchase sophisticated backup programs that are specially designed for large networks.
        - Back-Up Types
          - Normal backups
            - A normal backup, also called a full backup, is the most basic type of backup. In a normal backup, all files in the backup selection are backed up — regardless of whether the archive bit has been set. As each file is backed up, its archive bit is reset, so backups that select files based on the archive bit setting won’t back up the files.
          - Copy backups
            - A copy backup is similar to a normal backup, except that the archive bit is not reset as each file is copied. As a result, copy backups don’t disrupt the cycle of normal and incremental or differential backups.
          - Daily backups
            - A daily backup backs up just those files that have been changed the same day that the backup is performed. A daily backup examines the modification date for each file to determine whether a file should be backed up. Daily backups don’t reset the archive bit. 
          - Incremental backups
            - An incremental backup backs up only those files that you’ve modified since the last time you did a backup. Incremental backups are a lot faster than full backups because your network users probably modify only a small portion of the files on the server in any given day. As a result, if a full backup takes three tapes, you can probably fit an entire week’s worth of incremental backups on a single tape.
          - Differential backups
            - A differential backup is similar to an incremental backup, except that it doesn’t reset the archive bit as files are backed up. As a result, each differential backup represents the difference between the last normal backup and the current state of the hard drive. To do a full restore from a differential backup, you first restore the last normal backup, and then you restore the most recent differential backup.
      - Restoring
        - If you simply copy your files as a form of backing up, then restoring those files is no problem. You can overwrite current files with the backups, or you can copy files to a new hard disk, for example. If you use a backup program to create backups, you need to restore the backup to get your files back in working order. You cannot simply copy the backups to a new hard disk; you must run a restore.
        - You should test your backups periodically to make sure that they’re going to work. You don’t want to take the time and trouble to back up, only to find that the backup is worthless when you really need it. 
        - Guidelines for restoring backups.
          - Before you start to restore your backups, write-protect the media so that you don’t accidentally overwrite it. Write-protect means to disable the tape or disc from recording new data over the old. Different media use different write-protect methods; see the instructions that come with the media.
          - If you have a hard disk failure, you need to reinstall the operating system and your applications on a new hard disk. Then you need to install the backup software before you restore your backup of files.
          - Always restore your last full backup first. Then restore incremental or differential backups in order, from the earliest to the latest.
          - After you restore your data, hold on to the backup media for a few days to make sure that everything is working, just in case you need to go back to the backup. 
      - Encrypting
        - Encryption refers to the process of translating plain text information(or data) into a secret code so that unauthorized users can’t read the data.
        - Encryption is especially useful in environments where the data can’t be physically secured.If a thief can steal the server computer (or just its hard drive), he or she may be able to crack through the Windows security features and gain access to the data on the hard drive by using low-level disk diagnostic tools. If the files are stored in encrypted form, however, the thief’s efforts will be wasted because the files will be unreadable.
        - All forms of encryption use some sort of key to encrypt and decrypt the data.
        - The most basic type of data encryption, called synchronous data encryption, uses numeric keys that are used to apply complex mathematical operations to the source data in order to translate the data into encrypted form. These operations are reversible, so if you know the key, you can reverse the process and decrypt the data.
          - For example, suppose that the encryption technique is as simple as shifting every letter of the alphabet up by the value of the key. Thus, if the key is 3, then A becomes D, B becomes E, etc. The message “Elementary, my dear Watson” becomes “Hohphqwdub, pb ghdu Zdwvrq.” This message is incomprehensible, unless you know the key. Then, reconstructing the original message is easy.
        -  The actual keys and algorithms used for cryptography are much more complicated. Keys are typically binary numbers of 40 or 128 bits, and the actual calculations used to render the data in encrypted form are complicated. 
        - The classic dilemma of cryptography is this: How can I securely send the key to the person with whom I want to exchange messages? The answer is you can’t. You can’t encrypt the key, because the other person would need to know the key in order to decrypt it. That’s where public key encryption comes into play.
        - Public key encryption is a technique in which two keys are used: a private key and a public key. The keys are related to each other mathematically. Either of the keys can be used to encrypt the data, but the encryption process isn’t completely reversible: You have to have the private key in order to decrypt the data. 
        - Other Methods include:
          - Transposition - characters switched around
          - Substitution - characters replaced by other characters
        - Cryptography serves 3 purposes:
          - Helps to identify authentic users
          - Prevents alteration of the message
          - Prevents unauthorised users from reading the message 
      - Biometrics
        - Biometric verification is any means by which a person can be uniquely identified by evaluating one or more distinguishing biological traits. Unique identifiers include fingerprints, hand geometry, earlobe geometry, retina and iris patterns, voice waves, DNA, and signatures.The oldest form of biometric verification is fingerprinting. 
        - Types
          - Fingerprint identification
            - Fingerprint ridges are like a picture on the surface of a balloon. As the person ages, the fingers get do get larger. However, the relationship between the ridges stays the same, just like the picture on a balloon is still recognizable as the balloon is inflated.
          - Retina scan
            - A retina scan provides an analysis of the capillary blood vessels located in the back of the eye; the pattern remains the same throughout life. A scan uses a low-intensity light to take an image of the pattern formed by the blood vessels.
          - Face recognition
            - Facial characteristics (the size and shape of facial characteristics, and their relationship to each other). Typically, this method uses relative distances between common landmarks on the face to generate a unique "faceprint."
          - Voice analysis
            - The analysis of the pitch, tone, cadence(rythm/tempo) and frequency of a person's voice.
      - Firewalls
        -  A firewall is a security-conscious router that sits between the Internet and your network with a single purpose: preventing external attacks.
        - The firewall acts as a security guard between the Internet and your Network.
        - All network traffic into and out of the system must pass through the firewall, which prevents unauthorised access to the network.
        - Some type of firewall is a must- have if your network has a connection to the Internet, whether that connection is broadband, T1, or some other high-speed connection.
        - Without it, sooner or later a hacker will discover and breach your unprotected network. 
        - You can set up a firewall using two basic ways.
          - The easiest way is to purchase a firewall program, which is basically a self-contained router with built-in firewall features like one Alarm or Sophos. Most firewall appliances include a Web-based interface that enables you to connect to the firewall from any computer on your network using a browser. You can then customise the firewall settings to suit your needs.
          - Alternatively, you can set up a server computer to function as a firewall computer (SSL). The server can run just about any network operating system, but most dedicated firewall systems run Linux.
        - Whether you use a firewall appliance or a firewall computer, the firewall must be located between your network and the Internet. Usually, one end of the firewall is connected to a network hub, which is, in turn, connected to the other computers on the network. The other end of the firewall is connected to the Internet. As a result, all traffic from the LAN to the Internet and vice versa must travel through the firewall.
      - Physical security:
        - CCTV
          - It is common to have these on buildings but companies also have them in the network room, the corridors, reception and wherever there is data/money stored. Some have motion sensors so they record as soon as there is movement.
        - Locks
          - Standard locks on doors are usual, in most buildings staff rooms have locks. Network rooms particularly have locks, all entrances and exits. But network server cupboards and racks have locks, laptop cabinets, filing cabinets and keys allocated only to those who have rights. These locks can be keys or numbered.
      - Antivirus
        - Anti-virus software is a program or set of programs that are designed to prevent, search for, detect, and remove software viruses, and other malicious software like worms, trojans, adware, and more.
        - These tools are critical for users to have installed and up-to-date because a computer without anti-virus software installed will be infected within minutes of connecting to the internet. The bombardment is constant, with anti-virus companies update their detection tools constantly to deal with the more than 60,000 new pieces of malware created daily.
        - There are several different companies that build and offer anti-virus software and what each offers can vary but all perform some basic functions:
          - Scan specific files or directories for any malware or known malicious patterns
          - Allow you to schedule scans to automatically run for you
          - Allow you to initiate a scan of a specific file or of your computer, or of a CD or flash drive at any time.
          - Remove any malicious code detected –sometimes you will be notified of an infection and asked if you want to clean the file, other programs will automatically do this behind the scenes.
          - Show you the ‘health’ of your computer
      - Intrusion detection systems (IDS)
        - An intrusion detection system (IDS) is a device or software application that monitors a network or systems for malicious activity or policy violations.
        - Any detected activity or violation is typically reported either to an administrator or collected centrally using a Security Information and Event management (SIEM) system.
        - A SIEM system combines outputs from multiple sources, and uses alarm filtering techniques to distinguish malicious activity from false alarms.
        - There is a wide spectrum of IDS, varying from antivirus software to hierarchical systems that monitor the traffic of an entire backbone network.
        - Types of IDS
          - Network intrusion detection systems (NIDS)
          - Host-based intrusion detection systems (HIDS)
        - Comparison with firewalls
          - Though they both relate to network security, an IDS differs from a firewall in that a firewall looks outwardly for intrusions in order to stop them from happening.
          - Firewalls limit access between networks to prevent intrusion and do not signal an attack from inside the network.
          - An IDS evaluates a suspected intrusion once it has taken place and signals an alarm.
          - An IDS also watches for attacks that originate from within a system. This is traditionally achieved by examining network communications, identifying heuristics and patterns (often known as signatures) of common computer attacks, and taking action to alert operators.
          - A system that terminates connections is called an intrusion prevention system, and is another form of an application layer firewall.
  - Business risks:
    - Loss of Service
    - Loss of Business
      - Through loss of customer records
      - Increased costs
      - Loss of confidentiality
      - Compromised data integrity
      - Security issues
        - eg malware (hostile, intrusive, or annoying software or program code), 
        - viruses, 
        - Trojans, 
        - worms,
        - spyware,
        - adware
    - Before computers were networked, when a machine went down, that was one computer. It took time to repair it but business went on. With networks, the same happens but the user can move and business goes on. But when a network goes down through physical or software reasons, this can bring every machine down. “Network down time” can seriously impact on companies. For a school down time can mean some classes may be cancelled or find an alternative method, but for companies like Amazon, Play, E-bay etc, this can have a serious financial impact on the company. 
    -  Business confidence is one of the more integral parts of modern business and the loss of information, security breaches, down time, theft or hacking can have a serious impact on the confidence of customers. The more down time a company has, the less confidence customers have. Down time can cause a delay in the delivery of goods which is vital for Play so they might go to other service provider instead.