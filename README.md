This is from https://ctan.org/pkg/javatex

The files there (on CTAN) are dated 1998-October-05.

To quote the author, Timothy Murphy:

> javatex – A Java implementation of TEX
>
> At root, this is a ‘small’ TEX (memmax=64K), but a larger version may be built.
> 
> The implementation was in essence an experiment, and performance proved so poor that the author considers it unusable in practice.

But a review there (by HeikoTheissen, dated 2017-01-27) says:

> I have adapted the package in three places and find the result perfectly usable:  
> Fixed an error in mlist_to_hlist  
> Fixed an error that prevented hyphenation  
> Enlarged javaTEX.memoryword.maxHalfword= 1073741823 and built a `big' TEX with memmax = 10000000



