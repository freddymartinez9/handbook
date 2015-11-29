Secure Messaging
================

SMS are short messages sent between mobile phones. The text message is sent without encryption and can be read and stored by mobile phone providers and other parties with access to the network infrastructure to which you're connected. To protect your messages from interception you need to use end-to-end encryption on your text messages.  WhisperSystems provide an SMS encryption system called Signal, based on public key cryptography which ensures that messages are encrypted on the wire, however to ensure encryption on the wire, both parties must be using the application. It is [Open Source](https://github.com/WhisperSystems) and free to use. 

The encryption technology behind it (named //axolotl//) extends the OTR protocol so that messages can be encrypted and send even if not all of the communicating parties are online.


Android  - Installing Signal
---------------------------

To encrypt messages sent to others, you can use Signal for Android. (Previously it was named TextSecure). It provides end-to-end encryption with support for group messaging, emojis, and even support for unencrypted messaging. Supporting both SMS and MMS messaging, Signal is a drop in replacement for your stock messaging application on Android. Signal can also stores all of your messages in an encrypted database. Furthermore, Signal will transparently use end-to-end encryption for any other Signal user, without need to share keys before hand (although you should verify public keys as much as possible). Again, Signal requires the use of the Google Play framework. 

iOS - Signal
---------------------------


To encrypt messages sent to others, you can use Signal for iOS devices that use iOS 8 and higher as the operating system. Signal provides end-to-end encryption with an easy to use interface (it was designed to resemble iMessage). Unlike Androdi, Signal does not stores your messages in seperate encrypted database, although your iPhone should use full disk encryption by default. Furthermore, Signal will transparently use end-to-end encryption for any other Signal user, without need to share keys before hand (although you should verify public keys as much as possible). 
-------

