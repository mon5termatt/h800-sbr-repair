# h800-sbr-repair

## what is this anyways??

This is the method I used to REPAIR my SBR on my H800 Raid Card after "Bricking" it.

I accidently wiped the SBR off my Dell H800 Card when trying to flash my H310. Dont do what I did.

## Compatability
This script should work with any pc running BIOS (I did not test UEFI)

### Step 1
Make a bootable USB using Rufus.ie and Load Freedos.

### Step 2
Add the files from this repo to the root of your USB

### Step 3
Attach the corrupted H800 card and boot your computer from said USB
# DO NOT HAVE ANY OTHER CARDS ATTACHED TO THE PC. THIS IS HOW I MESSED UP!!!!

### Step 4
Run the command `MegaRec.exe -writesbr 0 H800.bin`

### Step 5
If it says success, Reboot! You are all set. 

























##### References
https://techmattr.wordpress.com/2016/04/11/updated-sas-hba-crossflashing-or-flashing-to-it-mode-dell-perc-h200-and-h310/
