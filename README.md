jbosh
=====

A Android friendly fork of jbosh (git://kenai.com/jbosh~origin).  

The major fixes/changes are:
 * The base implementation has some regex issues on the DalvikVM.  This version replaces regex matching with proper XML parsing.
 * Applying the jbosh patches from the asmack project.
 * Fixing the asmack patches to work with the threading model within jbosh.