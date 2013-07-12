# Bookmarklets
### Because I don't love searching for these things everytime I try a new browser.

- Instapaper - Read Later <pre>javascript:function iprl5(){var d=document,z=d.createElement('scr'+'ipt'),b=d.body,l=d.location;try{if(!b)throw(0);d.title='(Saving...) '+d.title;z.setAttribute('src',l.protocol+'//www.instapaper.com/j/QwJwyv9gaM8W?u='+encodeURIComponent(l.href)+'&t='+(new Date().getTime()));b.appendChild(z);}catch(e){alert('Please wait until the page has loaded.');}}iprl5();void(0)</pre>
- Pinboard - Pin This <pre>javascript:if(document.getSelection){s=document.getSelection();}else{s='';};document.location='https://pinboard.in/add?next=same&url='+encodeURIComponent(location.href)+'&description='+encodeURIComponent(s)+'&title='+encodeURIComponent(document.title)</pre>
- Kern.js <pre>javascript:(function(){document.body.appendChild(document.createElement('script')).src='http://bstro.github.com/kern.js/kern.js';})();</pre>
- mediaQuery <pre>javascript:%20(function%20()%20{var%20jsCode%20=%20document.createElement(%27script%27);jsCode.setAttribute(%27src%27,%20%27http://sparkbox.github.com/mediaQueryBookmarklet/bookmarklet-js/mediaQueryBookmarklet.js%27);document.body.appendChild(jsCode);}());</pre>

