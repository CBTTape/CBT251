# CBT251
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 251 IS FROM PAUL DAVIS OF EDS IN LOUISVILLE, COLORADO     *   FILE 251
//*           AND CONTAINS AN ENTIRELY NEW COLLECTION OF HIS        *   FILE 251
//*           EDIT MACROS, TO GO ALONG WITH HIS OTHER COLLECTION    *   FILE 251
//*           OF EDIT MACROS THAT IS ON FILE 095.                   *   FILE 251
//*                                                                 *   FILE 251
//*      Paul Davis passed away on July 19, 2000.                   *   FILE 251
//*                                                                 *   FILE 251
//*           THERE'S A LOT OF GOOD STUFF IN HERE, FOLKS.  ALSO     *   FILE 251
//*           LOOK IN FILE 095.                                     *   FILE 251
//*                                                                 *   FILE 251
//*      $$$DOC    DESCRIPTION OF MEMBERS IN THIS PDS               *   FILE 251
//*                                                                 *   FILE 251
//*      ADDAFTR   ADD A LINE OF DATA AFTER EACH LINE               *   FILE 251
//*                                                                 *   FILE 251
//*      BUPMEM    BACKUP PARMLIB MEMBER                            *   FILE 251
//*                                                                 *   FILE 251
//*      CHGID     PANEL USED BY SALTER                             *   FILE 251
//*                                                                 *   FILE 251
//*      CHGSTS    PANEL USED BY SALTER                             *   FILE 251
//*                                                                 *   FILE 251
//*      CLISTDOC  DOCUMENT A CLIST                                 *   FILE 251
//*                                                                 *   FILE 251
//*      CMODEL    COPY A CLIST MODEL INTO CURRENT EDIT SESSION     *   FILE 251
//*                                                                 *   FILE 251
//*      CUTCOL#   CUT COLUMNS HELP PANEL                           *   FILE 251
//*                                                                 *   FILE 251
//*      CUTCOLS   CUT COLUMNS OF DATA                              *   FILE 251
//*                                                                 *   FILE 251
//*      DELMARK   DEL MEMBERS OF PDS MARKED BY THE MARK MACRO      *   FILE 251
//*                                                                 *   FILE 251
//*      DOCMAC    DOCUMENT AN EDIT MACRO                           *   FILE 251
//*                                                                 *   FILE 251
//*      FINDPROC  FIND A PROC IN JES2 PROC CONCATENATION **        *   FILE 251
//*                MUST BE MODIFIED                                 *   FILE 251
//*                                                                 *   FILE 251
//*      FPROCBLD  BUILD FINDPROC MACRO ** MUST BE MODIFIED         *   FILE 251
//*                                                                 *   FILE 251
//*      FPROCBOT  COPY CODE FOR FPROCBLD                           *   FILE 251
//*                                                                 *   FILE 251
//*      FPROCTOP  COPY CODE FOR FPROCBLD                           *   FILE 251
//*                                                                 *   FILE 251
//*      INSERTM   INSERTM LINES MULTIPLE TIMES IN A DATASET        *   FILE 251
//*                AFTER X LINES                                    *   FILE 251
//*                                                                 *   FILE 251
//*      ISPYP1    MODIFIED PANEL TO WORK WITH VPANEL               *   FILE 251
//*                                                                 *   FILE 251
//*      LINEGRP   PICK LINES OF DATA TO BE USED LATER.  GROUPS     *   FILE 251
//*                THEM AT TOP OF DATA                              *   FILE 251
//*                                                                 *   FILE 251
//*      MACDOC    DOCUMENT A EDIT MACRO                            *   FILE 251
//*                                                                 *   FILE 251
//*      MACPEEK   FIND EDIT MACRO OR CLIST IN SYSPROC              *   FILE 251
//*                CONCATENATION EDIT MAC                           *   FILE 251
//*                                                                 *   FILE 251
//*      MACVIEW   FIND EDIT MACRO OR CLIST IN SYSPROC              *   FILE 251
//*                CONCATENATION TSO CLIST                          *   FILE 251
//*                                                                 *   FILE 251
//*      MARK      MARK MEMBER FOR DELETION                         *   FILE 251
//*                                                                 *   FILE 251
//*      MARKCLR   CLEAR MARKS CREATED BY MARK MACRO                *   FILE 251
//*                                                                 *   FILE 251
//*      MEMDEL    CREATE  A LIST OF MEMBERS AND SELECT SOME        *   FILE 251
//*                FOR DELETION                                     *   FILE 251
//*                                                                 *   FILE 251
//*      MEMLSTX   CALLED BY MEMDEL TO DELETE MEMBERS SELECTED      *   FILE 251
//*                FOR DELETION                                     *   FILE 251
//*                                                                 *   FILE 251
//*      MOVECOL#  MOVECOLS HELP PANEL                              *   FILE 251
//*                                                                 *   FILE 251
//*      MOVECOLS  MOVE COLUMNS OF DATA                             *   FILE 251
//*                                                                 *   FILE 251
//*      MOVFIELD  MOVE DATA FIELDS                                 *   FILE 251
//*                                                                 *   FILE 251
//*      MOVFIEL#  MOVFIELD HELP PANEL                              *   FILE 251
//*                                                                 *   FILE 251
//*      MPAST     CALLED BY INSERTM MACRO TO DO THE DIRTY WORK     *   FILE 251
//*                                                                 *   FILE 251
//*      MSGMAKE   MAKE A ISR MESSAGE IN CLIST                      *   FILE 251
//*                                                                 *   FILE 251
//*      PANPEEK   FIND PANEL IN ISPPLIB CONCATENATION EDIT MACRO   *   FILE 251
//*                                                                 *   FILE 251
//*      PANVIEW   FIND PANEL IN ISPPLIB CONCATENATION TSO CLIST    *   FILE 251
//*                                                                 *   FILE 251
//*      SALTER    CHANGE MEMBER STATS                              *   FILE 251
//*                                                                 *   FILE 251
//*      SKELPEEK  FIND SKELETON IN ISPSLIB CONCATENATION           *   FILE 251
//*                EDIT MACRO                                       *   FILE 251
//*                                                                 *   FILE 251
//*      SKELVIEW  FIND SKELETON IN ISPSLIB CONCATENATION           *   FILE 251
//*                TSO CLIST                                        *   FILE 251
//*                                                                 *   FILE 251
//*      SYA$DOC   SAVE YOUR ASSETS BACKUP DOC                      *   FILE 251
//*                                                                 *   FILE 251
//*      SYACATC   SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYACLNUP  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYACOPYI  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYACOPYO  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYAGENER  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYAGENRI  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYAGENRO  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYAJBALL  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYAPDS    SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYARENAM  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYAUDCAT  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      SYAUNCAT  SYA MACRO SEE SYS$DOC                            *   FILE 251
//*                                                                 *   FILE 251
//*      VOID      RESET PF10 KEY AFTER INSERTM ABORT               *   FILE 251
//*                                                                 *   FILE 251
//*      VPANEL    REFRESH CHANGED PANEL  ** REQUIRES               *   FILE 251
//*                ISPYP1 PANEL MOD                                 *   FILE 251
//*                                                                 *   FILE 251
//*      VTZAPBLD  BUILD A VTOC ZAP FROM IEHLIST LISTING            *   FILE 251
//*                                                                 *   FILE 251
//*      WCUT      WINDOW CUT.  CUT PORTIONS OF LINES FOR TO        *   FILE 251
//*                PASTE W WPASTE FOR THOSE OF US WITHOUT PC'S      *   FILE 251
//*                GIVE THIS A TRY                                  *   FILE 251
//*                                                                 *   FILE 251
//*      WCUT2     CALLED BY WCUT                                   *   FILE 251
//*                                                                 *   FILE 251
//*      WPASTE    PASTE DATA CUT BY WCUT                           *   FILE 251
//*                                                                 *   FILE 251
```
