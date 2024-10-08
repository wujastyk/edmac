# EDMAC
[![DOI](https://zenodo.org/badge/90817944.svg)](https://zenodo.org/badge/latestdoi/90817944)

The venerable EDMAC macros for formatting critical editions with Plain TeX.

This is version 3.17, from June 1996.  This was the final release of the EDMAC package.

It was authored by John Lavagnino and Dominik Wujastyk, with help from many friends.  After a long period of testing and refinement, it is now frozen and no longer maintained.  But it still works well :-)

EDMAC is a set of Plain TeX macros providing the ability to format critical editions of texts in the traditional way, i.e., similar to the Oxford Classical Texts, Teubner, Arden Shakespeare and other series. The principal functions that are added are marginal line numbering and multiple series of footnotes and endnotes keyed to line numbers. While EDMAC's inner workings are necessarily esoteric, it provides relatively simple macros to enable you to control the exact format of your edition, taking into account the need to vary the
format for different sorts of texts.  There are some examples of EDMAC output in the `examples` directory above, like this one:

![image](https://user-images.githubusercontent.com/762246/121459610-ce4f0900-c968-11eb-8cf4-dd052c8f48a6.png)

EDMAC 3.17 still works just fine, and is the only choice for anyone who works with Plain TeX.

## Later history 

EDMAC 3.16 was forked in 1994 by Peter Wilson so that it could be conveniently loaded as a LaTeX package and take advantage of LaTeX features. This package was called LEDMAC (original version [at Github](https://github.com/wujastyk/ledmac); successor available on [CTAN](https://www.ctan.org/pkg/ledmac)).

Later still, [Maïeul Rouquette](https://github.com/maieul) worked on LEDMAC and produced an extended, updated LaTeX package called eLEDMAC ([CTAN](https://www.ctan.org/pkg/eledmac)).  After much development, eLEDMAC was frozen and its successor became reLEDMAC ([CTAN](https://www.ctan.org/pkg/reledmac), [GitHub](https://github.com/maieul/ledmac)), currently the most evolved and powerful version of this family of macro packages.

A bibliography of some of the editions produced with EDMAC, LEDMAC and reLEDMAC [is publicly available](https://www.zotero.org/groups/209265/critical_editions_typeset_with_edmac_ledmac_eledmac_and_reledmac/library). There are over 75 volumes in the bibliography (mid-2021).

## The published manual

In 1996, the [UK TeX Users Group](http://uk.tug.org/) and the (international) [TeX Users Group](http://tug.org) jointly published the EDMAC manual and code as a physical book ([Worldcat entry](http://www.worldcat.org/oclc/38058109)). John and I are grateful to the late Sebastian Rahtz for the work he did in bringing this about and in formatting the book nicely for print. The preface to this published manual is included in the files above as well as the full book.  A copy, with the examples, has been made available [at Archive.org](http://n2t.net/ark:/13960/t10p7ch0w).

Appendix A of the EDMAC documentation and the published manual included the code for half a dozen examples.  The ouputs for these examples are available as PDFs in the directory `../examples` in this repo.

EDMAC is hosted here at GitHub, and also at the TeX Users Group, at http://tug.org/edmac.
