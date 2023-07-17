I touched some code builded on rollup which is only downstream, so now I read more infomation of rollup to learn how is build javascript explicitly in my mind.

besides, the whole with babel building pipeline what them were happened.

[update] : it is hard to execrise for this, 
they supported less usage scene eaxmple to explain their principle.
till now I read code at tsup, to find the scene what rollup usual put on.

## experience 
1. I got the principle they want all in ES6 include cjs code. 
so if can it run at old version, I do not know.
that I know is if complie at defualt to .js, the code will include mjs `import from` and if directly run on nodejs will caught error at tip with no cjs.
so it should set the attribute named "type" to "module". I do not know what module mean.

2. and the config params are hard to align and fine. 
in the course I got, even I add jsDos using @type but never had get a good experience to know immeditely what will happen.

## Ans from ai;
1. thought ai says, two points I think are good to me.  
one, it explain if I want run lower nodejs code, I should complie to old version code (I think it could be other good way but not).
2. using the "type":"module", and no more explain of "module".  
it seem just for point it to ES6 and no more anything else.