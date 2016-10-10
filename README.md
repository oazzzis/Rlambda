
<pre>

@module.zker

{

  (\a \b \c (c b) c a)          \starling
  (\a \b a)                     \kestrel
  (\a \b \c b c a)              \yellowbird
  (\a \b \c (c b) a)            \cardinal

} \Combinators

( <> (\cont <> 'test' print
            <timeBeforeCont> getTime
            <> cont
            <timeAfterCont> getTime
            <> [timeAfterCont - timeBeforeCont] Math | print
            <> 'chapter 2' print
            <> cat | addPlusToEachLine | [ awk { print $2 } ] Bash
     ) callcc
  <> 'yes' print
  <> 'destroy universe one day' print

) \testArrow

</pre>

