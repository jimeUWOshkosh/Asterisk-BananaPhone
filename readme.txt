Upon closing down this project.

I wanted to test Alex Ruiz's 'Banana Phone' system rather
than the Bill Bishop's funky OBITRUNK1 definition in
sip.conf.

Now that I have gain some knowledge of Asterisk and
the Obihai-110 & Obihai 212, I want to challenge
myself one more time.

And try to figure out if the 'once and a while'
receiving 'no orginating phone number' but the trunk name,
OBITRUNK1, is a bug in the B.B.'s Asterisk configuration
or just the phone companies being schmucks!

I'll be documenting :
   0) A.R.'s setup of the Obihai-110.
   1) I moved stuff to the custom files for asterisk
         sip_custom.conf
         extensions_custom.conf
      Note: FreePBX's Asterisk configuration files has
            'include'-s for these files.uly-2022
raspbx-11-11-2019, Asterisk 16.6.1 & FreePBX 15.0.16.22

InTRANET only. If you hook this to the inTERnet, you're
asking for TROUBLE!!!


On Sunday 24-July-2022 was able to test the Banana Phone
setup. I will not be able to do a long run of like
two months to see if I hit the 'no orginating phone number'
issue.

Also I did not declare my VoIP phones in this trial.
phones 1000 and 3000, even though they're mentioned
in extensions_custom.conf

Directory

├── allow.pl                          Sample perl program to filter incoming calls
                                        Used DATA section rather than a DB
                                        Show how to filter by businesses who
                                          have a bank of phone numbers, by
                                          Caller ID
├── asterisk.verbose.phonecall.txt    asterisk -rvvv output of a phone call
├── extensions_custom.conf            Example /etc/asterisk/extensions_custom.conf
├── initial-config-sip-error.txt      A change I had to make to my SIP def
├── OBi110.note.from.BillB.txt        A note from Bill Bishop
├── OBi110.setup.txt                  The Banana Phone OBi100 setup
├── readme.txt
├── sip_custom.conf                   Example /etc/asterisk/sip_custom.conf
├── sip-show-peers-output.txt         Output from 'sip show peers' during asterisk -rvvv
├── voicemail.conf                    Example /etc/asterisk/voicemail.conf?
└── webpareges                        Alex's webpages before he removed them from the web
    └── *There are 5 webpages stored here*
    └── Order.txt                        Order of the html web pages




