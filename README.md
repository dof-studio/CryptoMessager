![CryptoMessager logo p3](https://github.com/user-attachments/assets/a79a1f6b-77b8-4adc-941c-823668e3d607)

# 00. Special Notification
This software is licensed under the `Apache License, Version 2.0 with Non-Military Use Restriction` since version 0.0.1.3. 
See the `LICENSE` file for details.

# 01. Introduction
This software `CryptoMessager` Version 0.0.1.3 (built 2024H4, stable version), with its GUI frontend `CryptoMessager_GUI` included, is a user-friendly toolkit for conducting encrypted communication and online meeting that are protected by DOF-Studio-developed, patented Hybrid-Minus Algorithm set. With automatic encryption and decryption mechanism enabled, you can communicate confidently with registered users on any insecure Internet platform - because a robust encryption system will always protect your privacy from ciphertext intrusion. 

This software is extremely easy to use - the encryption and decryption for texts or any file structures only requires you to use the shortcut keys `Ctrl + C` and `Ctrl + V`, and will be automatically executed during your copying and pasting process imperceptibly. 

For more features and functionality, scroll down to see more. For how to use this software, see folder "DOCS" and "EXAMPLES". 

Special warning here! DO NOT transmit any SMS Code in a plain text form on the Internet! It represents your whole identity.

# 02. Features
### Basic Features
- `A Hybrid Encryption-decryption System and Methods of Multi-step Layered Encryption` - By using the self-developed, patented encryption algorithm, the system can perform a multi-secure encryption without increasing time consumption. In particular, the algorithm set we now use, called `Hybrid-Minus`, generally has a less than 4x time consumption than AES-256, but can achieve more than 16x security boost, safeguarding your privacy with our utmost determination.
- `One-Click File Structure Encryption` - You can now encrypt and decrypt any single file, any files, or folders (not only texts) into/from a decrypted `.denc.bin` format by using the identical shortcut keys `Ctrl + C` and `Ctrl + V`. The backend monitoring system will be automatically invoked and functioned, while it may take some time (when the light turns to yellow) to complete the encrypting/decrypting process when files are too big.
- `Partial Ciphertext` - Don't you just want to encrypt a part of your text instead of every single character? We can now officially assert that we can do it! By using a `*<...>*` notation in your plaintest, where the `...` represents the part that you are intending to transform into cipertexts, you can copy and paste the whole plain-cipher mixed passage, but only encrypt/decrypt the part that you want to.
- `Encrypt Text To A File` - Is your plaintext too long to be sent on an online platform? You can encrypt your text into a file by adding a `====!!!!` notation at the very beginning or the end of the whole text to encrypt it into a copiable file, instead of encrypting it into a copiable ciphertext. Let's try to encrypt a long article into a file automatically!
- `User Friendly Using Method` - Instead of having to type, click, wait and paste once you encrypt a message, your copied plaintext/ciphertext is automatically encrypted/decrypted imperceptibly during your copying and pasting process by simply holding down the shortcut keys `Ctrl + C` and `Ctrl + V`. Feel free to protect your privacy with robust algorithms, while saving your precious time simultaneously!
- `Full Unicode Support` - Welcome, the world! The entire processes of encryption and decryption completely support Unicode, which means that regardless of the language of plaintext you are using, it will stay with an identical form after encryption and decryption, instead of outputting a string of garbled code when languages other than English are used.
- `Visual Encoded Ciphertext Output` - Our self-developed visual coding scheme can output encrypted messages in visual form, meaning that regardless of the platform you are using, your message will not fail to be sent due to coding issues after encryption. Note that this will be much more efficient than a typical BASE-64.​
- `Forever Free` - Free Is Our Greatest Justice! We use the conditional 'Apache-2.0' license, which protects our rights and interests in the developed software while allowing you to use the software unrestricted, free, and permanent. Our ultimate target is to provide free services that help everyone's daily life!
- `...`

### New Updated Features
- `Dynamic SMS Code` - Each time you invoke your request to get a SMS Code, it will be an unique one (while every single one represents your identity). It may be helpful to track the leakage of a SMS Code.
- `SMS Code Telepathy` - Remotely transmit your SMS Code to an trusted counterparty securely (using TCP/IP, so the server party should have a PUBLIC IPV6 address, but will not require this restriction in later versions)! Elliptic Curve Cryptography implemented by DOF Studio is involved to protect your SMS Code secure even in a network environment!
- `Shortcut Controls` - Using shortcut keys to do complex tasks! Yes, we have created a series of shortcut keys that help you to activate your command without any click! Please refer to the documents or the HELP component built-in the GUI program to see the usage of shortcut keys.
- `Interactive Command Line System` - Are you bored with clicking buttons? A new command line system has been equipped within the GUI frontend, where you can use your keyboard to do everything, even including something that buttons are not able to do! Get start by entering a `Help` and clicking the enter key to see a variety of commands and syntax.
- `Entrypoint Verification` - We use complicated mechanism including cryptographic hash and digital signature to check the integrety of the program and its dependence, preventing any mal-modification to impair your network security.
- `Standalone HintLight` - Are you bored with our dull, outmoded GUI form? Let's control all daily tasks by using a floating, movable rectangle (while it may still be kind of dull). More details of how to use the Standalone HintLight can be found in our document.
- `Multi-Thread Encryption` - Having a Core i9 14900K? We can now utilize at most 20 threads (with AVX-2 supported) to conduct multi-thread encryption or decryption that boosts your using experience. Let's become faaaaaaster!
- `...`

### Upcoming Futures
- `We Require a Custom Password` - In order to protect the security of your CryptoMessager encryption, starting from version 0.0.1.4, we require you to enter a custom password when you first start CryptoMessager. This password will help generate your SMS Code and will help you protect the data security of your local database. Because your database is protected by a password, even if your computer is attacked and the local database is leaked, the data you encrypt with CryptoMessager will not be at risk. This will be a mandatory requirement starting from version 0.0.1.4.
- `The 3rd Generation SMS Code and DEL Code` - We are continuously researching and developping the most efficient and secure way to generate and transmit your SMS Code. The 3rd generation SMS and DEL Code will be incorporated and the replacement of the current version from version 0.0.1.4 (not compatible to previous versions but is expected to last for a long time) along with the new `XORE Primitive` encryption set. New SMS Code will allow you to select the counterparty who is the only one that parse your SMS Code, as well as a `deadline` which indicates an expiration time of one SMS Code. Also, `SMS Code Telepathy` will support the new version as it did in the 0.0.1.3 version.
- `Archivable Encryption` - Don't you want to archive your files with encryption and redundance protection? We have FREE solutions (so abandon RAR from now) with customizable Hybrid-Minus Algorithms, redundance code, and splited archives! You may be required to customize your original key and archives will be encrypted by an enhanced one (automatically conducted). This will start to be available from version 0.0.1.4 in the future.
- `Better SMS Code Telepathy` - User experience will improve in the future versions, which includes logic, GUI, and speed. More details can be found at the introduction page of version 0.0.1.4.
- `Automated APIs in C#` - We are going to provide a series of APIs that can partially control the local CryptoMessager system to do some automatic tasks (e.g. automatic on and off, automatic encrypting and decrypting, ...) when the user permit automatic proxy function in the main GUI interface.
- `XORE Primitive` - A light-weight encryption algorithm series that is fast, reliable, and super secure (AES-256 upper level). It will be incorporated into the Hybrid-Minus Algorithms and will be available by version 0.0.1.5 in the future. (Research is hard at this period...)
- `Multilanguage Support` - We first support Japanese, Koeran, Chinese, French, Russian, as well as the native English in the GUI interface starting from the version 0.0.1.5 in the future.
- `Online Chatroom and Online Meeting` - Surprise! We offer an online chatroom with (text messages, file transmission, and) Full-HD Vision plus Lossless Audio enabled online P2N meeting which supports up to 10 people at the same time. It is completely anonomous and secure (we use TCP/IP protocol, Hybird Minus Encryption, and NO-SERVER technique, so NOTHING will be stored by the thirdparty). This may be available from version 0.0.1.5 or later (Developping...)
- `...`



# 03. Hybrid-Minus Algorithms Supported
### Comparable Algorithms
- `AES 256 Native` - Security *---- Complexity *---- Short Text Extension *---- Long Text Extension **--- Parallel ---
- `AES 512 IEEE  ` - Security **--- Complexity ***-- Short Text Extension *---- Long Text Extension **--- Parallel ---

### Algorithms That We Support
- `Mimoji` - [0.0.1.1] Security **--- Complexity ***-- Short Text Extension *---- Long Text Extension ***-- Parallel ---
- `Leaf  ` - [0.0.1.2] Security ***-- Complexity **--- Short Text Extension ***-- Long Text Extension **--- Parallel ***
- `Aoba  ` - [0.0.1.5] Security ****- Complexity ****- Short Text Extension ***-- Long Text Extension **--- ??? Future
- `Kaze  ` - [0.0.1.5] Security ***-- Complexity *---- Short Text Extension **--- Long Text Extension *---- ??? Future
- `Konoha` - [0.0.1.5] Security **--- Complexity ----- Short Text Extension **--- Long Text Extension *---- ??? Future
- `Inoha ` - [0.0.1.5] Security **--- Complexity ----- Short Text Extension **--- Long Text Extension *---- ??? For stream only.
- `...`

Note, from version 0.0.1.4, `Mimoji` and `Leaf` will be reconstructed and enhanced to provide extra security but with less operating time complexity (SIMD optimization).


# 04. Basic Introduction
### One Graph To Show How To Use It
The `graph` below briefly shows the basic ideas to encrypt and decrypt texts and files by shortcut keys `Ctrl + C` and `Ctrl + V` with our CryptoMessager system.

![CryptoMessager_BasicUsage_Zl_0 0 1 2](https://github.com/dof-studio/CryptoMessager/assets/144514436/8816ca20-c675-4dd9-80cc-ab871f450c3d)

More functions are now supported, including `Partial Ciphertext`, `Encrypt Text To A File`, and `Directly`. You can refer to our `User Tutorial` to see more specific usages in the subfolders of the "DOCS" (highly recommended to have a read).

### GUI Usage
The `graph` below briefly shows some basic usage of the buttons, signals, input bars, and consoles in the GUI system.

![CryptoMessager_GUI_Display_EN_0 0 1 2](https://github.com/dof-studio/CryptoMessager/assets/144514436/a550fca7-f932-4827-bc94-ca12b14862d7)

Please note that the English version of this illustration is not the only version provided, some translated versions of it are also available in the "DOCS" directory. Moreover, a specific, `User Tutorial`, including directions of installation and further usage can also be found in the subfolders of the "DOCS" (highly recommended to have a read).

### Command Line Usage
The `graph` below briefly shows a majority of supported commands that can be used in the interactive command line console.

![CryptoMessager_Commands](https://github.com/dof-studio/CryptoMessager/assets/144514436/92338cb9-edf7-4e2a-b056-9b1c0cbd3855)

Please note that you can use a `HELP;` command in the command line to get a similar copy of this usage. Moreover, you can use a `HELP [Arg];` command with 1 arg in the command line console to get a specific description of how to use a certain command, for example `HELP HELP;` In this version, both Upper-case commands or Lower-case commands are supported.



# 05. Future Updates
### Prospected
- `More Diversified Algorithms Supported` - Multiple Hybird-Minus encryption algorithms will be available, and you will then be able to choose which one you like best for your encryption and decryption. It should be noted that the responsibility of multiple time-performance trade-off should be bear. Basically, the more time you spend on the encryption process, the safer your ciphertext will be.
- `Restricted SMS Code` - In order to ensure that your SMS Code is not maliciously used or forwarded, we will further improve the SMS Code generation mechanism and add a time limited verification mechanism to ensure that your SMS Code is only valid for a few minutes, so that you can ensure that your customers will not forward your SMS Code to other unrecognized and untrustworthy recipients.
- `Rich-Text and HTML Encryption` - You can encrypt formated Microsoft Word/Powerpoint/Excel contents.
- `Console with Color Annotations` - Input and output will be more clear, line a code-editor.
- `Integrated minichatter` - Where you can conduct secure P2P communication and even exchange your SMS Codes with encryption, and remotely!
- `Beautify Our GUI Form` - Will it come soon, or, be put off forever?
- `...`

### Already Known Bugs
- `Security Warning` - Our implementation of encryption algothrim has been found a key-related bug, which may indicate insecurity factors. But after being researched and testes, our secueity engineering team has cliamed that it is only a `potential defect` and has almost no impact of the current cipher generated by the current version of CryptoMessager. It will be fixed in the next version 0.0.1.4.
- `Automatic Update Error` - We have built an automatic updating system capale for checking, installing, and updating all available updates. But it seems not working well. We will fix it in the next version 0.0.1.4.
- `Partial Text Decryption May Fail` - We have found that under some circumstances, CryptoMessager may fail to detect the partial cipher text and fail to decrypt it. This will be solved in the next version 0.0.1.4.
- `...`



# 06. Versions and Support Periods
### Definitions
- `Unstable Trail` - Only a trail update for experimental purpose. We do not ensure the stability of the software and any related code.
- `Standard Support` - Stable versions. For versions with Standard Support, we only provide one Release, which means that you need to update to the next version to resolve performance issues and bugs that may exist in the current version.
- `Long-period Support` - Stable versions. For versions with Long-period Support, we will provide Revision support for up to two years, which means that if you do not update to the next version (which may face protocol changes and incompatibilities, such as `Version 0.0.1.4` and `Version 0.0.1.3`), although you cannot enjoy the updated features, we will still maintain Revision every six months to solve the bugs of the current version.

### A List of Versions
- `Version 0.0.1` - Unstable Trail.
- `Version 0.0.1.1` - Unstable Trail. Released in Oct 2023.
- `Version 0.0.1.2` - Unstable Trail. Released in Nov 2023.
- `Version 0.0.1.3` - Long-period Support. Released in Oct 2024.
- `Version 0.0.1.4` - Standard Support. Project to be released in Feb 2025.
- `Version 0.0.1.5` - Unstable Trail. Project to be released in Aug 2025.
- `Version 0.0.1.6` - Long-period Support. Project to be released in Feb 2026.



# 07. Notifications
### Non-military Apache Version 2.0 License
Please read the following terms carefully and check whether you, or your entity, satisfy the requirement of using this software `CryptoMessager`.
Our team DOF Studio is a non-profitable organization which aims at pursuing a world without War, Discrimination, Unequity, and Anti-democracy.
This software is licensed under the `Apache License, Version 2.0 with Conditional Use Restriction`, which allows any non-military entity to use, commercially use, redistribute, or modify EXCEPT:
- 1. The user is, or belongs to a military related organization.
- 2. The user is, or belongs to an organization whose targets offend DOF Studio's basic aims.
- 3. The user is, or belongs to an organization that is regarded as an explicit prohibitive user we listed below.

If you satisfy ANY ONE of those prohibitive terms listed above, this software is PROHIBITED for you to use. Otherwise, your rights and obligations are under stipulations from the standard `Apache License Version 2.0`.

### Using Experience
- `Most Important` - In the current version, DO NOT use the internet to transmit any plaintext `SMS Code`. It is because whoever receives, or just steals it, they will then be able to effortlessly decrypt whatever you encrypted. Use `SMS Code Telepathy` function available from version 0.0.1.3 instead.
- `Most Important` - Please turn the main button `OFF` when you are `NOT USING` the automatic encrypting and decrypting system. It is because whatever you copy, although you are not intending to encrypt, it will be recognized as a plaintext without false distinction and then encrypted.
- `Helpful` - Please use the command `CLC` or `CLRCLIP` to refresh your clipboard before recopying something when your `Ctrl + C` fails to detect a change of the data intended to be encrypted/decrypted.
- `Helpful` - Encrypted file `*.denc.bin` will be around 1.75 ~ 2.00 times in size (if your original files are not compressable) compared to the original total size with the default Hybrid-Minus encrypting algorithm `Leaf`.
- `...`


DOF Studio, 2024.
