
########################################################################

1. File to be Modified is "dtaConfig.mk"

2. By default release package is configured to build for PN557/PN81T
   with ANDROID - P.

3. Refer to the below table for furhter details.

4. How to read the table: Check Android Version, set the flags based on
   the CHIP (PN81T / PN80T)
########################################################################

________________________________________________________________________
Configuration is as explained below:

     1. To Build DTA for Android P & NCI v2.0
            ANDROID_VER := P
            NCI_VER     := 2_0

     2. To Build DTA for Android P & NCI v1.0
            ANDROID_VER := P
            NCI_VER     := 1_0

     3. To Build DTA for Android O & NCI v2.0
            ANDROID_VER := O
            NCI_VER     := 2_0

     4. To Build DTA for Android O & NCI v1.0
            ANDROID_VER := O
            NCI_VER     := 1_0

     5. To Build DTA for Android L/M/N & NCI v1.0
            ANDROID_VER := L or M or N
            NCI_VER     := 1_0
________________________________________________________________________
