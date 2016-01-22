# ibmi_fisheye
For those who index their IBM i source using Atlassian Fisheye, these syntax files will add highlighting. File types currently supported:

*RPG
*CL
*DDS
*Service program binder source

# Installation
Place the *.def files in the syntax subdirectory of your Crucible installation. You will then need to edit filename.map to add the following lines:

"**/*.rpgle" rpgle.def "RPGLE"
"**/*.sqlrpgle" rpgle.def "SQLRPGLE"
"**/*.clp" cl.def "CLP"
"**/*.clle" cl.def "CLLE"
"**/*.cmd" cl.def "CMD"
"**/*.pf" dds.def "PF"
"**/*.lf" dds.def "LF"
"**/*.prtf" dds.def "PRTF"
"**/*.dspf" dds.def "DSPF"
"**/*.bnd" bnd.def "SRVSRC"
