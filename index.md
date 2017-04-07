<link rel="shortcut icon" href="/images/favicon.ico">
<center>
   <p>
      <img alt="silkenpy logo" src="/images/silkenpy.svg"/>
      <br/>
   </p>
   <p>
      <i>
      Simplicity is the Best
      </i>
      <br/>
   </p>
   <pre> <font size="5"> <a href="/"> Home </a><a href="/photos.md"> Photos </a><a href="/archives.md"> Archives </a><a href="/contact.md"> Contact </a> <a href="/feed.xml"><img src="/images/feed-icon.png" alt="Subscribe to What's New"></a>
</font></pre>
   <br/>
</center>
## dstat
Sunday, 02. April 2017 11:28PM 

dstat is the best or one of the best command line tools that helps you monitor your system as simple as possible.

```shell
ali@silken:/tmp$ dstat -tams
----system---- ----total-cpu-usage---- -dsk/total- -net/total- ---paging-- ---system-- ------memory-usage----- ----swap---
     time     |usr sys idl wai hiq siq| read  writ| recv  send|  in   out | int   csw | used  buff  cach  free| used  free
02-04 18:28:41|  6   2  92   1   0   0|  38k   48k|   0     0 |   0     0 | 255  1210 |1523M  161M 1726M  396M|   0   999M
02-04 18:28:42|  6   2  92   0   0   0|   0     0 | 126B  228B|   0     0 | 473  3241 |1523M  161M 1722M  400M|   0   999M
02-04 18:28:43|  7   2  91   0   0   0|   0     0 | 126B    0 |   0     0 | 431  3133 |1523M  161M 1722M  400M|   0   999M
02-04 18:28:44|  5   3  92   0   0   0|   0     0 |   0     0 |   0     0 | 450  3191 |1523M  161M 1722M  400M|   0   999M
02-04 18:28:45|  5   3  92   0   0   0|   0     0 |   0     0 |   0     0 | 486  3264 |1523M  161M 1722M  400M|   0   999M
02-04 18:28:46|  6   3  91   0   0   0|   0     0 |   0   231B|   0     0 | 475  3220 |1523M  161M 1722M  400M|   0   999M
02-04 18:28:47|  5   4  91   0   0   0|   0     0 | 168B  231B|   0     0 | 542  3390 |1520M  161M 1722M  404M|   0   999M
02-04 18:28:48|  7   3  91   0   0   0|   0     0 | 756B  231B|   0     0 | 565  3531 |1521M  161M 1722M  403M|   0   999M
02-04 18:28:49|  6   2  92   0   0   0|   0     0 | 966B  231B|   0     0 | 499  3219 |1521M  161M 1722M  402M|   0   999M^C
ali@silken:/tmp$ 

```
