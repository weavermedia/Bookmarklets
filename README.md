# Bookmarklets
### Because I don't love searching for these things everytime I try a new browser.

- Instapaper - <a href="javascript:function iprl5(){var d=document,z=d.createElement('scr'+'ipt'),b=d.body,l=d.location;try{if(!b)throw(0);d.title='(Saving...) '+d.title;z.setAttribute('src',l.protocol+'//www.instapaper.com/j/QwJwyv9gaM8W?u='+encodeURIComponent(l.href)+'&t='+(new Date().getTime()));b.appendChild(z);}catch(e){alert('Please wait until the page has loaded.');}}iprl5();void(0)" title="Read Later">Read Later</a>
- Pinboard - <a class="bookmarklet" href="javascript:if(document.getSelection){s=document.getSelection();}else{s='';};document.location='https://pinboard.in/add?next=same&url='+encodeURIComponent(location.href)+'&description='+encodeURIComponent(s)+'&title='+encodeURIComponent(document.title)">Pin This</a> (same page) - <a class="bookmarklet" href="javascript:q=location.href;if(document.getSelection){d=document.getSelection();}else{d='';};p=document.title;void(open('https://pinboard.in/add?url='+encodeURIComponent(q)+'&description='+encodeURIComponent(d)+'&title='+encodeURIComponent(p),'Pinboard','toolbar=no,width=700,height=350'));">Pin This</a> (popup)
- <a href="javascript:(function(){document.body.appendChild(document.createElement('script')).src='http://bstro.github.com/kern.js/kern.js';})();">Kern.js</a>
- <a class="bookmarklet" href="javascript:%20(function%20()%20{var%20jsCode%20=%20document.createElement(%27script%27);jsCode.setAttribute(%27src%27,%20%27http://sparkbox.github.com/mediaQueryBookmarklet/bookmarklet-js/mediaQueryBookmarklet.js%27);document.body.appendChild(jsCode);}());" id="mediaQueryBookmarklet">mediaQuery</a>
- [Item](http://smallersoftware.net)
- [Hello World][1]

[1]:javascript:alert('Hello World')