```fortran
C THERE ARE VARIATIONS OF THIS BLOCK THAT USES DIFFERENT VARIABLE
C NAMES FOR:
C     SDET
C     SZDET

      COMMON /DETWFN/ WSTATE(MXRT),SPINS(MXRT),CRIT,PRTTOL,SDET,SZDET,
     *                GRPDET,STSYM,GLIST,DWPARM,
     *                NFLGDM(MXRT),IWTS(MXRT),NCORSV,NCOR,NACT,NORBDT,
     *                NADET,NBDET,KDET,KSTDET,IROOT,IPURES,MAXW1,NITDET,
     *                MAXP,NCIDET,IGPDET,KSTSYM,NFTGCI,IDWEIGH,
     *                FSTATE(MXRT),IFTS(MXRT)

      DOUBLE PRECISION WSTATE,SPINS,CRIT,PRTTOL,SDET,SZDET
      DOUBLE PRECISION GRPDET,STSYM,GLIST,DWPARM
      INTEGER NFLGDM,IWTS,NCORSV,NCOR,NACT,NORBDT
      INTEGER NADET,NBDET,KDET,KSTDET,IROOT,IPURES,MAXW1,NITDET
      INTEGER MAXP,NCIDET,IGPDET,KSTSYM,NFTGCI,IDWEIGH
      DOUBLE PRECISION FSTATE
      INTEGER IFTS

```