google is not provided
========================

Text for a JS bookmarklet that replaces all instances of a word (Google) and replaces it with another (not provided)

Drag this link onto your browser toolbar and you're all set.

<a href="javascript:function%20htmlreplace(a,b,element){if(!element)element=document.body;var%20nodes=element.childNodes;for(var%20n=0;n<nodes.length;n++){if(nodes[n].nodeType==Node.TEXT_NODE){nodes[n].textContent=nodes[n].textContent.replace(new%20RegExp(a,'gi'),b);}else{htmlreplace(a,b,nodes[n]);}}}htmlreplace('Google','(not%20provided)');">(not provided) Google</a>