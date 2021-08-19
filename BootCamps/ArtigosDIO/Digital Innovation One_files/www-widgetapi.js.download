(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var n;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function r(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
r("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
r("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function fa(a){if(!(a instanceof Array)){a=u(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
var ha="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ia;
if("function"==typeof Object.setPrototypeOf)ia=Object.setPrototypeOf;else{var ja;a:{var ka={a:!0},la={};try{la.__proto__=ka;ja=la.a;break a}catch(a){}ja=!1}ia=ja?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ma=ia;
function oa(a,b){a.prototype=ha(b.prototype);a.prototype.constructor=a;if(ma)ma(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.G=b.prototype}
function pa(){this.s=!1;this.l=null;this.i=void 0;this.h=1;this.m=this.o=0;this.B=this.j=null}
function qa(a){if(a.s)throw new TypeError("Generator is already running");a.s=!0}
pa.prototype.u=function(a){this.i=a};
function ra(a,b){a.j={la:b,oa:!0};a.h=a.o||a.m}
pa.prototype.return=function(a){this.j={return:a};this.h=this.m};
function w(a,b,c){a.h=c;return{value:b}}
pa.prototype.v=function(a){this.h=a};
function sa(a,b,c){a.o=b;void 0!=c&&(a.m=c)}
function ta(a){a.o=0;var b=a.j.la;a.j=null;return b}
function ua(a){a.B=[a.j];a.o=0;a.m=0}
function va(a){var b=a.B.splice(0)[0];(b=a.j=a.j||b)?b.oa?a.h=a.o||a.m:void 0!=b.v&&a.m<b.v?(a.h=b.v,a.j=null):a.h=a.m:a.h=0}
function wa(a){this.h=new pa;this.i=a}
function xa(a,b){qa(a.h);var c=a.h.l;if(c)return ya(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return za(a)}
function ya(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.s=!1,e;var f=e.value}catch(g){return a.h.l=null,ra(a.h,g),za(a)}a.h.l=null;d.call(a.h,f);return za(a)}
function za(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.s=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ra(a.h,c)}a.h.s=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.oa)throw b.la;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Aa(a){this.next=function(b){qa(a.h);a.h.l?b=ya(a,a.h.l.next,b,a.h.u):(a.h.u(b),b=za(a));return b};
this.throw=function(b){qa(a.h);a.h.l?b=ya(a,a.h.l["throw"],b,a.h.u):(ra(a.h,b),b=za(a));return b};
this.return=function(b){return xa(a,b)};
this[Symbol.iterator]=function(){return this}}
function y(a,b){b=new Aa(new wa(b));ma&&a.prototype&&ma(b,a.prototype);return b}
r("Reflect.setPrototypeOf",function(a){return a?a:ma?function(b,c){try{return ma(b,c),!0}catch(d){return!1}}:null});
function Ba(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
r("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Ba(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(2!=m.get(k)||3!=m.get(l))return!1;m.delete(k);m.set(l,4);return!m.has(k)&&4==m.get(l)}catch(q){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Ba(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Ba(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Ba(k,g)&&Ba(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Ba(k,g)&&Ba(k[g],this.h)?delete k[g][this.h]:!1};
return b});
r("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return ea(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h.data_[l];if(m&&Ba(h.data_,l))for(h=0;h<m.length;h++){var q=m[h];if(k!==k&&q.key!==q.key||k===q.key)return{id:l,list:m,index:h,A:q}}return{id:l,list:m,index:-1,A:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||"s"!=m.value[1])return!1;m=l.next();return m.done||4!=m.value[0].x||"t"!=m.value[1]||!l.next().done?!1:!0}catch(q){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.data_[l.id]=[]);l.A?l.A.value=k:(l.A={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.A),this.h.previous.next=l.A,this.h.previous=l.A,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.A&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.A.previous.next=h.A.next,h.A.next.previous=h.A.previous,h.A.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).A};
e.prototype.get=function(h){return(h=d(this,h).A)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ca(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
r("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ca(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
r("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
r("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ca(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
r("Object.setPrototypeOf",function(a){return a||ma});
var Da="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Ba(d,e)&&(a[e]=d[e])}return a};
r("Object.assign",function(a){return a||Da});
r("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.s=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.va),reject:g(this.m)}};
b.prototype.va=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.xa(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.ca(g):this.o(g)}};
b.prototype.ca=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ya(h,g):this.o(g)};
b.prototype.m=function(g){this.u(2,g)};
b.prototype.o=function(g){this.u(1,g)};
b.prototype.u=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.wa();this.B()};
b.prototype.wa=function(){var g=this;e(function(){if(g.N()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.N=function(){if(this.s)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.B=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.xa=function(g){var h=this.l();g.W(h.resolve,h.reject)};
b.prototype.ya=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(t,p){return"function"==typeof t?function(x){try{l(t(x))}catch(A){m(A)}}:p}
var l,m,q=new b(function(t,p){l=t;m=p});
this.W(k(g,l),k(h,m));return q};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.W=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.s=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),m=l.next();!m.done;m=l.next())d(m.value).W(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,m){function q(x){return function(A){t[x]=A;p--;0==p&&l(t)}}
var t=[],p=0;do t.push(void 0),p++,d(k.value).W(q(t.length-1),m),k=h.next();while(!k.done)})};
return b});
function Ea(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
r("Array.prototype.entries",function(a){return a?a:function(){return Ea(this,function(b,c){return[b,c]})}});
r("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Ba(b,d)&&c.push([d,b[d]]);return c}});
r("Array.prototype.keys",function(a){return a?a:function(){return Ea(this,function(b){return b})}});
r("Array.prototype.values",function(a){return a?a:function(){return Ea(this,function(b,c){return c})}});
r("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
r("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
r("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
r("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
r("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
r("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ca(this,b,"includes").indexOf(b,c||0)}});
r("Set",function(a){function b(c){this.h=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
var z=this||self;function B(a,b){a=a.split(".");b=b||z;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Fa(){}
function Ga(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ha(a){var b=Ga(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function C(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ia(a){return Object.prototype.hasOwnProperty.call(a,Ja)&&a[Ja]||(a[Ja]=++Ka)}
var Ja="closure_uid_"+(1E9*Math.random()>>>0),Ka=0;function La(a,b,c){return a.call.apply(a.bind,arguments)}
function Ma(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Na(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Na=La:Na=Ma;return Na.apply(null,arguments)}
function E(a,b){a=a.split(".");var c=z;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function F(a,b){function c(){}
c.prototype=b.prototype;a.G=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.gb=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Oa(a){return a}
;function Pa(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Pa);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.Ba=b)}
F(Pa,Error);Pa.prototype.name="CustomError";function Qa(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function Ra(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var Sa=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},G=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Ta=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
G(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Ua(a,b){b=Sa(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function Va(a){return Array.prototype.concat.apply([],arguments)}
function Wa(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function Xa(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ha(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Ya(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function Za(a){var b=$a,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function ab(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function bb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=bb(a[c]);return b}
var cb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function db(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<cb.length;f++)c=cb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var eb;function fb(a,b){this.h=a===gb&&b||""}
fb.prototype.S=!0;fb.prototype.R=function(){return this.h};
function hb(a){return new fb(gb,a)}
var gb={};hb("");var ib=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function jb(a,b){if(b)a=a.replace(kb,"&amp;").replace(lb,"&lt;").replace(mb,"&gt;").replace(nb,"&quot;").replace(ob,"&#39;").replace(pb,"&#0;");else{if(!qb.test(a))return a;-1!=a.indexOf("&")&&(a=a.replace(kb,"&amp;"));-1!=a.indexOf("<")&&(a=a.replace(lb,"&lt;"));-1!=a.indexOf(">")&&(a=a.replace(mb,"&gt;"));-1!=a.indexOf('"')&&(a=a.replace(nb,"&quot;"));-1!=a.indexOf("'")&&(a=a.replace(ob,"&#39;"));-1!=a.indexOf("\x00")&&(a=a.replace(pb,"&#0;"))}return a}
var kb=/&/g,lb=/</g,mb=/>/g,nb=/"/g,ob=/'/g,pb=/\x00/g,qb=/[\x00&<>"']/;function rb(a,b){this.h=b===sb?a:""}
n=rb.prototype;n.S=!0;n.R=function(){return this.h.toString()};
n.na=!0;n.ma=function(){return 1};
n.toString=function(){return this.h.toString()};
var tb=RegExp('^(?:audio/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font/\\w+|image/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\\w+=(?:\\w+|"[\\w;,= ]+"))*$',"i"),ub=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,vb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,sb={},wb=new rb("about:invalid#zClosurez",sb);var xb;a:{var yb=z.navigator;if(yb){var zb=yb.userAgent;if(zb){xb=zb;break a}}xb=""}function H(a){return-1!=xb.indexOf(a)}
;var Ab={};function Bb(a,b,c){this.h=c===Ab?a:"";this.i=b;this.S=this.na=!0}
Bb.prototype.ma=function(){return this.i};
Bb.prototype.R=function(){return this.h.toString()};
Bb.prototype.toString=function(){return this.h.toString()};
function Cb(a,b){if(void 0===eb){var c=null;var d=z.trustedTypes;if(d&&d.createPolicy){try{c=d.createPolicy("goog#html",{createHTML:Oa,createScript:Oa,createScriptURL:Oa})}catch(e){z.console&&z.console.error(e.message)}eb=c}else eb=c}a=(c=eb)?c.createHTML(a):a;return new Bb(a,b,Ab)}
;var Db=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function Eb(a){return a?decodeURI(a):a}
function Fb(a){return Eb(a.match(Db)[3]||null)}
function Gb(a){var b=a.match(Db);a=b[1];var c=b[2],d=b[3];b=b[4];var e="";a&&(e+=a+":");d&&(e+="//",c&&(e+=c+"@"),e+=d,b&&(e+=":"+b));return e}
function Hb(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Hb(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function Ib(a){var b=[],c;for(c in a)Hb(c,a[c],b);return b.join("&")}
var Jb=/#|$/;function Kb(a,b){var c=a.search(Jb);a:{var d=0;for(var e=b.length;0<=(d=a.indexOf(b,d))&&d<c;){var f=a.charCodeAt(d-1);if(38==f||63==f)if(f=a.charCodeAt(d+e),!f||61==f||38==f||35==f)break a;d+=e+1}d=-1}if(0>d)return null;e=a.indexOf("&",d);if(0>e||e>c)e=c;d+=b.length+1;return decodeURIComponent(a.substr(d,e-d).replace(/\+/g," "))}
;function I(a,b){var c=void 0;return new (c||(c=Promise))(function(d,e){function f(k){try{h(b.next(k))}catch(l){e(l)}}
function g(k){try{h(b["throw"](k))}catch(l){e(l)}}
function h(k){k.done?d(k.value):(new c(function(l){l(k.value)})).then(f,g)}
h((b=b.apply(a,void 0)).next())})}
;function Lb(){return H("iPhone")&&!H("iPod")&&!H("iPad")}
;function Mb(a){Mb[" "](a);return a}
Mb[" "]=Fa;var Nb=H("Opera"),Ob=H("Trident")||H("MSIE"),Pb=H("Edge"),Qb=H("Gecko")&&!(-1!=xb.toLowerCase().indexOf("webkit")&&!H("Edge"))&&!(H("Trident")||H("MSIE"))&&!H("Edge"),Rb=-1!=xb.toLowerCase().indexOf("webkit")&&!H("Edge");function Sb(){var a=z.document;return a?a.documentMode:void 0}
var Tb;a:{var Ub="",Vb=function(){var a=xb;if(Qb)return/rv:([^\);]+)(\)|;)/.exec(a);if(Pb)return/Edge\/([\d\.]+)/.exec(a);if(Ob)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Rb)return/WebKit\/(\S+)/.exec(a);if(Nb)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Vb&&(Ub=Vb?Vb[1]:"");if(Ob){var Wb=Sb();if(null!=Wb&&Wb>parseFloat(Ub)){Tb=String(Wb);break a}}Tb=Ub}var Xb=Tb,Yb;if(z.document&&Ob){var Zb=Sb();Yb=Zb?Zb:parseInt(Xb,10)||void 0}else Yb=void 0;var $b=Yb;var ac=Lb()||H("iPod"),bc=H("iPad"),cc=H("Safari")&&!((H("Chrome")||H("CriOS"))&&!H("Edge")||H("Coast")||H("Opera")||H("Edge")||H("Edg/")||H("OPR")||H("Firefox")||H("FxiOS")||H("Silk")||H("Android"))&&!(Lb()||H("iPad")||H("iPod"));var dc={},ec=null;var fc={ib:{value:!0,configurable:!0}};var gc=Object,hc=gc.freeze,ic=[];Array.isArray(ic)&&!Object.isFrozen(ic)&&Object.defineProperties(ic,fc);hc.call(gc,ic);var J=window;hb("csi.gstatic.com");hb("googleads.g.doubleclick.net");hb("pagead2.googlesyndication.com");hb("partner.googleadservices.com");hb("pubads.g.doubleclick.net");hb("securepubads.g.doubleclick.net");hb("tpc.googlesyndication.com");function jc(a,b){this.width=a;this.height=b}
n=jc.prototype;n.clone=function(){return new jc(this.width,this.height)};
n.aspectRatio=function(){return this.width/this.height};
n.isEmpty=function(){return!(this.width*this.height)};
n.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
n.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
n.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function kc(a,b){Ya(b,function(c,d){c&&"object"==typeof c&&c.S&&(c=c.R());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:lc.hasOwnProperty(d)?a.setAttribute(lc[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var lc={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};function mc(a,b,c){var d=arguments,e=document,f=d[1],g=nc(e,String(d[0]));f&&("string"===typeof f?g.className=f:Array.isArray(f)?g.className=f.join(" "):kc(g,f));2<d.length&&oc(e,g,d);return g}
function oc(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!Ha(f)||C(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(C(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}G(g?Wa(f):f,d)}}}
function nc(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function pc(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function qc(a){var b=rc;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function sc(){var a=[];qc(function(b){a.push(b)});
return a}
var rc={Sa:"allow-forms",Ta:"allow-modals",Ua:"allow-orientation-lock",Va:"allow-pointer-lock",Wa:"allow-popups",Xa:"allow-popups-to-escape-sandbox",Ya:"allow-presentation",Za:"allow-same-origin",ab:"allow-scripts",bb:"allow-top-navigation",cb:"allow-top-navigation-by-user-activation"},tc=Ra(function(){return sc()});
function uc(){var a=nc(document,"IFRAME"),b={};G(tc(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
;var vc=(new Date).getTime();function wc(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==
c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function xc(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(q){for(var t=g,p=0;64>p;p+=4)t[p/4]=q[p]<<24|q[p+1]<<16|q[p+2]<<8|q[p+3];for(p=16;80>p;p++)q=t[p-3]^t[p-8]^t[p-14]^t[p-16],t[p]=(q<<1|q>>>31)&4294967295;q=e[0];var x=e[1],A=e[2],v=e[3],K=e[4];for(p=0;80>p;p++){if(40>p)if(20>p){var P=v^x&(A^v);var D=1518500249}else P=x^A^v,D=1859775393;else 60>p?(P=x&A|v&(x|A),D=2400959708):(P=x^A^v,D=3395469782);P=((q<<5|q>>>27)&4294967295)+P+K+D+t[p]&4294967295;K=v;v=A;A=(x<<30|x>>>2)&4294967295;x=q;q=P}e[0]=e[0]+q&4294967295;e[1]=e[1]+x&4294967295;e[2]=
e[2]+A&4294967295;e[3]=e[3]+v&4294967295;e[4]=e[4]+K&4294967295}
function c(q,t){if("string"===typeof q){q=unescape(encodeURIComponent(q));for(var p=[],x=0,A=q.length;x<A;++x)p.push(q.charCodeAt(x));q=p}t||(t=q.length);p=0;if(0==l)for(;p+64<t;)b(q.slice(p,p+64)),p+=64,m+=64;for(;p<t;)if(f[l++]=q[p++],m++,64==l)for(l=0,b(f);p+64<t;)b(q.slice(p,p+64)),p+=64,m+=64}
function d(){var q=[],t=8*m;56>l?c(h,56-l):c(h,64-(l-56));for(var p=63;56<=p;p--)f[p]=t&255,t>>>=8;b(f);for(p=t=0;5>p;p++)for(var x=24;0<=x;x-=8)q[t++]=e[p]>>x&255;return q}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,Ca:function(){for(var q=d(),t="",p=0;p<q.length;p++)t+="0123456789ABCDEF".charAt(Math.floor(q[p]/16))+"0123456789ABCDEF".charAt(q[p]%16);return t}}}
;function yc(a,b,c){var d=String(z.location.href);return d&&a&&b?[b,zc(wc(d),a,c||null)].join(" "):null}
function zc(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],G(d,function(h){e.push(h)}),Ac(e.join(" "));
var f=[],g=[];G(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];G(d,function(h){e.push(h)});
a=Ac(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Ac(a){var b=xc();b.update(a);return b.Ca().toLowerCase()}
;var Bc={};function Cc(a){this.h=a||{cookie:""}}
n=Cc.prototype;n.isEnabled=function(){if(!z.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{ea:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
n.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.lb;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.ea}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);this.h.cookie=a+"="+b+(f?";domain="+f:"")+(g?";path="+g:"")+(0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString())+(d?";secure":"")+(null!=e?";samesite="+e:"")};
n.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=ib(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
n.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{ea:0,path:b,domain:c});return d};
n.isEmpty=function(){return!this.h.cookie};
n.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=ib(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Dc=new Cc("undefined"==typeof document?null:document);function Ec(a){return!!Bc.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Fc(a,b,c,d){(a=z[a])||(a=(new Cc(document)).get(b));return a?yc(a,c,d):null}
function Gc(a){var b=void 0===b?!1:b;var c=wc(String(z.location.href)),d=[];var e=b;e=void 0===e?!1:e;var f=z.__SAPISID||z.__APISID||z.__3PSAPISID||z.__OVERRIDE_SID;Ec(e)&&(f=f||z.__1PSAPISID);if(f)e=!0;else{var g=new Cc(document);f=g.get("SAPISID")||g.get("APISID")||g.get("__Secure-3PAPISID")||g.get("SID");Ec(e)&&(f=f||g.get("__Secure-1PAPISID"));e=!!f}e&&(e=(c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:"))?z.__SAPISID:z.__APISID,e||(e=new Cc(document),
e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID")),(e=e?yc(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e),c&&Ec(b)&&((b=Fc("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Fc("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a)));return 0==d.length?null:d.join(" ")}
;function Hc(){this.data_=[];this.h=-1}
Hc.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.data_[a]!=b&&(this.data_[a]=b,this.h=-1)};
Hc.prototype.get=function(a){return!!this.data_[a]};
function Ic(a){-1==a.h&&(a.h=Ta(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function Jc(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Jc.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Kc(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var Lc;
function Mc(){var a=z.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!H("Presto")&&(a=function(){var e=nc(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Na(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!H("Trident")&&!H("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.ja;c.ja=null;e()}};
return function(e){d.next={ja:e};d=d.next;b.port2.postMessage(0)}}return function(e){z.setTimeout(e,0)}}
;function Nc(a){z.setTimeout(function(){throw a;},0)}
;function Oc(){this.i=this.h=null}
Oc.prototype.add=function(a,b){var c=Pc.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Oc.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Pc=new Jc(function(){return new Qc},function(a){return a.reset()});
function Qc(){this.next=this.scope=this.h=null}
Qc.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Qc.prototype.reset=function(){this.next=this.scope=this.h=null};function Rc(a,b){Sc||Tc();Uc||(Sc(),Uc=!0);Vc.add(a,b)}
var Sc;function Tc(){if(z.Promise&&z.Promise.resolve){var a=z.Promise.resolve(void 0);Sc=function(){a.then(Wc)}}else Sc=function(){var b=Wc;
"function"!==typeof z.setImmediate||z.Window&&z.Window.prototype&&!H("Edge")&&z.Window.prototype.setImmediate==z.setImmediate?(Lc||(Lc=Mc()),Lc(b)):z.setImmediate(b)}}
var Uc=!1,Vc=new Oc;function Wc(){for(var a;a=Vc.remove();){try{a.h.call(a.scope)}catch(b){Nc(b)}Kc(Pc,a)}Uc=!1}
;function Xc(a,b){this.i=a[z.Symbol.iterator]();this.j=b;this.l=0}
Xc.prototype[Symbol.iterator]=function(){return this};
Xc.prototype.next=function(){var a=this.i.next();return{value:a.done?void 0:this.j.call(void 0,a.value,this.l++),done:a.done}};
function Yc(a,b){return new Xc(a,b)}
;function Zc(){this.blockSize=-1}
;function $c(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.o=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
F($c,Zc);$c.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function ad(a,b,c){c||(c=0);var d=a.o;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
$c.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)ad(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){ad(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){ad(this,e);f=0;break}}this.i=f;this.l+=b}};
$c.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;ad(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function bd(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||z.$googDebugFname||b}catch(g){e="Not available",c=!0}b=cd(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,dd[c])c=dd[c];else{c=String(c);if(!dd[c]){var f=/function\s+([^\(]+)/m.exec(c);dd[c]=f?f[1]:"[Anonymous]"}c=dd[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function cd(a,b){b||(b={});b[ed(a)]=!0;var c=a.stack||"";(a=a.Ba)&&!b[ed(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=cd(a,b));return c}
function ed(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var dd={};function fd(){this.j=this.j;this.m=this.m}
fd.prototype.j=!1;fd.prototype.dispose=function(){this.j||(this.j=!0,this.P())};
fd.prototype.P=function(){if(this.m)for(;this.m.length;)this.m.shift()()};var gd="StopIteration"in z?z.StopIteration:{message:"StopIteration",stack:""};function hd(){}
hd.prototype.next=function(){return hd.prototype.h.call(this)};
hd.prototype.h=function(){throw gd;};
hd.prototype.C=function(){return this};function id(a){if(a instanceof jd||a instanceof kd||a instanceof ld)return a;if("function"==typeof a.next)return new jd(function(){return md(a)});
if("function"==typeof a[Symbol.iterator])return new jd(function(){return a[Symbol.iterator]()});
if("function"==typeof a.C)return new jd(function(){return md(a.C())});
throw Error("Not an iterator or iterable.");}
function md(a){if(!(a instanceof hd))return a;var b=!1;return{next:function(){for(var c;!b;)try{c=a.h();break}catch(d){if(d!==gd)throw d;b=!0}return{value:c,done:b}}}}
function jd(a){this.j=a}
jd.prototype.C=function(){return new kd(this.j())};
jd.prototype[Symbol.iterator]=function(){return new ld(this.j())};
jd.prototype.i=function(){return new ld(this.j())};
function kd(a){this.j=a}
oa(kd,hd);kd.prototype.h=function(){var a=this.j.next();if(a.done)throw gd;return a.value};
kd.prototype.next=function(){return kd.prototype.h.call(this)};
kd.prototype[Symbol.iterator]=function(){return new ld(this.j)};
kd.prototype.i=function(){return new ld(this.j)};
function ld(a){jd.call(this,function(){return a});
this.l=a}
oa(ld,jd);ld.prototype.next=function(){return this.l.next()};function nd(a,b){this.i={};this.h=[];this.j=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof nd)for(c=od(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function od(a){pd(a);return a.h.concat()}
n=nd.prototype;n.has=function(a){return qd(this.i,a)};
n.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||rd;pd(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function rd(a,b){return a===b}
n.isEmpty=function(){return 0==this.size};
n.clear=function(){this.i={};this.j=this.size=this.h.length=0};
n.remove=function(a){return this.delete(a)};
n.delete=function(a){return qd(this.i,a)?(delete this.i[a],--this.size,this.j++,this.h.length>2*this.size&&pd(this),!0):!1};
function pd(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];qd(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],qd(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
n.get=function(a,b){return qd(this.i,a)?this.i[a]:b};
n.set=function(a,b){qd(this.i,a)||(this.size+=1,this.h.push(a),this.j++);this.i[a]=b};
n.forEach=function(a,b){for(var c=od(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
n.clone=function(){return new nd(this)};
n.keys=function(){return id(this.C(!0)).i()};
n.values=function(){return id(this.C(!1)).i()};
n.entries=function(){var a=this;return Yc(this.keys(),function(b){return[b,a.get(b)]})};
n.C=function(a){pd(this);var b=0,c=this.j,d=this,e=new hd;e.h=function(){if(c!=d.j)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)throw gd;var f=d.h[b++];return a?f:d.i[f]};
e.next=e.h.bind(e);return e};
function qd(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function sd(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
sd.prototype.stopPropagation=function(){this.j=!0};
sd.prototype.preventDefault=function(){this.defaultPrevented=!0};var td=function(){if(!z.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{z.addEventListener("test",Fa,b),z.removeEventListener("test",Fa,b)}catch(c){}return a}();function ud(a,b){sd.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
F(ud,sd);var vd={2:"touch",3:"pen",4:"mouse"};
ud.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Qb){a:{try{Mb(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:vd[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&ud.G.preventDefault.call(this)};
ud.prototype.stopPropagation=function(){ud.G.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
ud.prototype.preventDefault=function(){ud.G.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var wd="closure_listenable_"+(1E6*Math.random()|0);var xd=0;function yd(a,b,c,d,e){this.listener=a;this.h=null;this.src=b;this.type=c;this.capture=!!d;this.Y=e;this.key=++xd;this.T=this.V=!1}
function zd(a){a.T=!0;a.listener=null;a.h=null;a.src=null;a.Y=null}
;function Ad(a){this.src=a;this.listeners={};this.h=0}
Ad.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Bd(a,b,d,e);-1<g?(b=a[g],c||(b.V=!1)):(b=new yd(b,this.src,f,!!d,e),b.V=c,a.push(b));return b};
Ad.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Bd(e,b,c,d);return-1<b?(zd(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Cd(a,b){var c=b.type;c in a.listeners&&Ua(a.listeners[c],b)&&(zd(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Bd(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.T&&f.listener==b&&f.capture==!!c&&f.Y==d)return e}return-1}
;var Dd="closure_lm_"+(1E6*Math.random()|0),Ed={},Fd=0;function Gd(a,b,c,d,e){if(d&&d.once)Hd(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Gd(a,b[f],c,d,e);else c=Id(c),a&&a[wd]?a.Z(b,c,C(d)?!!d.capture:!!d,e):Jd(a,b,c,!1,d,e)}
function Jd(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=C(e)?!!e.capture:!!e,h=Kd(a);h||(a[Dd]=h=new Ad(a));c=h.add(b,c,d,g,f);if(!c.h){d=Ld();c.h=d;d.src=a;d.listener=c;if(a.addEventListener)td||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Md(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Fd++}}
function Ld(){function a(c){return b.call(a.src,a.listener,c)}
var b=Nd;return a}
function Hd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Hd(a,b[f],c,d,e);else c=Id(c),a&&a[wd]?a.h.add(String(b),c,!0,C(d)?!!d.capture:!!d,e):Jd(a,b,c,!0,d,e)}
function Od(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Od(a,b[f],c,d,e);else(d=C(d)?!!d.capture:!!d,c=Id(c),a&&a[wd])?a.h.remove(String(b),c,d,e):a&&(a=Kd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Bd(b,c,d,e)),(c=-1<a?b[a]:null)&&Pd(c))}
function Pd(a){if("number"!==typeof a&&a&&!a.T){var b=a.src;if(b&&b[wd])Cd(b.h,a);else{var c=a.type,d=a.h;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Md(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Fd--;(c=Kd(b))?(Cd(c,a),0==c.h&&(c.src=null,b[Dd]=null)):zd(a)}}}
function Md(a){return a in Ed?Ed[a]:Ed[a]="on"+a}
function Nd(a,b){if(a.T)a=!0;else{b=new ud(b,this);var c=a.listener,d=a.Y||a.src;a.V&&Pd(a);a=c.call(d,b)}return a}
function Kd(a){a=a[Dd];return a instanceof Ad?a:null}
var Qd="__closure_events_fn_"+(1E9*Math.random()>>>0);function Id(a){if("function"===typeof a)return a;a[Qd]||(a[Qd]=function(b){return a.handleEvent(b)});
return a[Qd]}
;function L(){fd.call(this);this.h=new Ad(this);this.ca=this;this.s=null}
F(L,fd);L.prototype[wd]=!0;L.prototype.addEventListener=function(a,b,c,d){Gd(this,a,b,c,d)};
L.prototype.removeEventListener=function(a,b,c,d){Od(this,a,b,c,d)};
function Rd(a,b){var c=a.s;if(c){var d=[];for(var e=1;c;c=c.s)d.push(c),++e}a=a.ca;c=b.type||b;"string"===typeof b?b=new sd(b,a):b instanceof sd?b.target=b.target||a:(e=b,b=new sd(c,a),db(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=Sd(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Sd(g,c,!0,b)&&e,b.j||(e=Sd(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Sd(g,c,!1,b)&&e}
L.prototype.P=function(){L.G.P.call(this);if(this.h){var a=this.h,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,zd(d[e]);delete a.listeners[c];a.h--}}this.s=null};
L.prototype.Z=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
function Sd(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.T&&g.capture==c){var h=g.listener,k=g.Y||g.src;g.V&&Cd(a.h,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;var Td=z.JSON.stringify;function Ud(a){this.h=0;this.s=void 0;this.l=this.i=this.j=null;this.m=this.o=!1;if(a!=Fa)try{var b=this;a.call(void 0,function(c){Vd(b,2,c)},function(c){Vd(b,3,c)})}catch(c){Vd(this,3,c)}}
function Wd(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
Wd.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var Xd=new Jc(function(){return new Wd},function(a){a.reset()});
function Yd(a,b,c){var d=Xd.get();d.i=a;d.onRejected=b;d.context=c;return d}
Ud.prototype.then=function(a,b,c){return Zd(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Ud.prototype.$goog_Thenable=!0;Ud.prototype.cancel=function(a){if(0==this.h){var b=new $d(a);Rc(function(){ae(this,b)},this)}};
function ae(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?ae(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):be(c),ce(c,e,3,b)))}a.j=null}else Vd(a,3,b)}
function de(a,b){a.i||2!=a.h&&3!=a.h||ee(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Zd(a,b,c,d){var e=Yd(null,null,null);e.h=new Ud(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof $d?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;de(a,e);return e.h}
Ud.prototype.B=function(a){this.h=0;Vd(this,2,a)};
Ud.prototype.N=function(a){this.h=0;Vd(this,3,a)};
function Vd(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.B,f=a.N;if(d instanceof Ud){de(d,Yd(e||Fa,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(C(d))try{var k=d.then;if("function"===typeof k){fe(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.s=c,a.h=b,a.j=null,ee(a),3!=b||c instanceof $d||ge(a,c))}}
function fe(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function ee(a){a.o||(a.o=!0,Rc(a.u,a))}
function be(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
Ud.prototype.u=function(){for(var a;a=be(this);)ce(this,a,this.h,this.s);this.o=!1};
function ce(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.m;a=a.j)a.m=!1;if(b.h)b.h.j=null,he(b,c,d);else try{b.j?b.i.call(b.context):he(b,c,d)}catch(e){ie.call(null,e)}Kc(Xd,b)}
function he(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function ge(a,b){a.m=!0;Rc(function(){a.m&&ie.call(null,b)})}
var ie=Nc;function $d(a){Pa.call(this,a)}
F($d,Pa);$d.prototype.name="cancel";function M(a){fd.call(this);this.s=1;this.l=[];this.o=0;this.h=[];this.i={};this.u=!!a}
F(M,fd);n=M.prototype;n.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.s;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.s=e+3;d.push(e);return e};
function je(a,b,c){var d=ke;if(a=d.i[a]){var e=d.h;(a=a.find(function(f){return e[f+1]==b&&e[f+2]==c}))&&d.U(a)}}
n.U=function(a){var b=this.h[a];if(b){var c=this.i[b];0!=this.o?(this.l.push(a),this.h[a+1]=Fa):(c&&Ua(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
n.O=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.u)for(e=0;e<c.length;e++){var g=c[e];le(this.h[g+1],this.h[g+2],d)}else{this.o++;try{for(e=0,f=c.length;e<f&&!this.j;e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.o--,0<this.l.length&&0==this.o)for(;c=this.l.pop();)this.U(c)}}return 0!=e}return!1};
function le(a,b,c){Rc(function(){a.apply(b,c)})}
n.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.U,this),delete this.i[a])}else this.h.length=0,this.i={}};
n.P=function(){M.G.P.call(this);this.clear();this.l.length=0};function me(a){this.h=a}
me.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,Td(b))};
me.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
me.prototype.remove=function(a){this.h.remove(a)};function ne(a){this.h=a}
F(ne,me);function oe(a){this.data=a}
function pe(a){return void 0===a||a instanceof oe?a:new oe(a)}
ne.prototype.set=function(a,b){ne.G.set.call(this,a,pe(b))};
ne.prototype.i=function(a){a=ne.G.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
ne.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function qe(a){this.h=a}
F(qe,ne);qe.prototype.set=function(a,b,c){if(b=pe(b)){if(c){if(c<Date.now()){qe.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}qe.G.set.call(this,a,b)};
qe.prototype.i=function(a){var b=qe.G.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())qe.prototype.remove.call(this,a);else return b}};function re(){}
;function se(){}
F(se,re);se.prototype[Symbol.iterator]=function(){return id(this.C(!0)).i()};
se.prototype.clear=function(){var a=Array.from(this);a=u(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function te(a){this.h=a}
F(te,se);n=te.prototype;n.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
n.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
n.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.h.removeItem(a)};
n.C=function(a){var b=0,c=this.h,d=new hd;d.h=function(){if(b>=c.length)throw gd;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
d.next=d.h.bind(d);return d};
n.clear=function(){this.h.clear()};
n.key=function(a){return this.h.key(a)};function ue(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
F(ue,te);function ve(a,b){this.i=a;this.h=null;var c;if(c=Ob)c=!(9<=Number($b));if(c){we||(we=new nd);this.h=we.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),we.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
F(ve,se);var xe={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},we=null;function ye(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return xe[b]})}
n=ve.prototype;n.isAvailable=function(){return!!this.h};
n.set=function(a,b){this.h.setAttribute(ye(a),b);ze(this)};
n.get=function(a){a=this.h.getAttribute(ye(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.h.removeAttribute(ye(a));ze(this)};
n.C=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new hd;d.h=function(){if(b>=c.length)throw gd;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
d.next=d.h.bind(d);return d};
n.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);ze(this)};
function ze(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Ae(a,b){this.i=a;this.h=b+"::"}
F(Ae,se);Ae.prototype.set=function(a,b){this.i.set(this.h+a,b)};
Ae.prototype.get=function(a){return this.i.get(this.h+a)};
Ae.prototype.remove=function(a){this.i.remove(this.h+a)};
Ae.prototype.C=function(a){var b=this.i.C(!0),c=this,d=new hd;d.h=function(){for(var e=b.h();e.substr(0,c.h.length)!=c.h;)e=b.h();return a?e.substr(c.h.length):c.i.get(e)};
d.next=d.h.bind(d);return d};var Be,Ce,De=z.window,Ee=(null===(Be=null===De||void 0===De?void 0:De.yt)||void 0===Be?void 0:Be.config_)||(null===(Ce=null===De||void 0===De?void 0:De.ytcfg)||void 0===Ce?void 0:Ce.data_)||{};E("yt.config_",Ee);function Fe(a){for(var b=0;b<arguments.length;++b);b=arguments;1<b.length?Ee[b[0]]=b[1]:1===b.length&&Object.assign(Ee,b[0])}
function N(a,b){return a in Ee?Ee[a]:b}
;var Ge=[];function He(a){Ge.forEach(function(b){return b(a)})}
function Ie(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Je(b)}}:a}
function Je(a){var b=B("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0):(b=N("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0]),Fe("ERRORS",b));He(a)}
function Ke(a){var b=B("yt.logging.errors.log");b?b(a,"WARNING",void 0,void 0,void 0):(b=N("ERRORS",[]),b.push([a,"WARNING",void 0,void 0,void 0]),Fe("ERRORS",b))}
;var Le=0;E("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++Le});var Me={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Ne(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Me||(this[b]=a[b]);this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;if(d)try{d=d.nodeName?
d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey}}catch(e){}}
Ne.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Ne.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Ne.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var $a=z.ytEventsEventsListeners||{};E("ytEventsEventsListeners",$a);var Oe=z.ytEventsEventsCounter||{count:0};E("ytEventsEventsCounter",Oe);
function Pe(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return Za(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=C(e[4])&&C(d)&&ab(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function Qe(a){a&&("string"==typeof a&&(a=[a]),G(a,function(b){if(b in $a){var c=$a[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Re()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete $a[b]}}))}
var Re=Ra(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Se(a,b,c){var d=void 0===d?{}:d;if(a&&(a.addEventListener||a.attachEvent)){var e=Pe(a,b,c,d);if(!e){e=++Oe.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Ne(h);if(!pc(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Ne(h);
h.currentTarget=a;return c.call(a,h)};
g=Ie(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Re()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);$a[e]=[a,b,c,g,d]}}}
;function Te(a,b){"function"===typeof a&&(a=Ie(a));return window.setTimeout(a,b)}
function Ue(a){"function"===typeof a&&(a=Ie(a));return window.setInterval(a,250)}
;var Ve=/^[\w.]*$/,We={q:!0,search_query:!0};function Xe(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Ye(f[0]||""),h=Ye(f[1]||"");g in c?Array.isArray(c[g])?Xa(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(q){var k=q,l=f[0],m=String(Xe);k.args=[{key:l,value:f[1],query:a,method:Ze==m?"unchanged":m}];We.hasOwnProperty(l)||Ke(k)}}return c}
var Ze=String(Xe);function $e(a){var b=[];Ya(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];G(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function af(a){"?"==a.charAt(0)&&(a=a.substr(1));return Xe(a,"&")}
function bf(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=af(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);b=a;a=Ib(e);a?(c=b.indexOf("#"),0>c&&(c=b.length),f=b.indexOf("?"),0>f||f>c?(f=c,e=""):e=b.substring(f+1,c),b=[b.substr(0,f),e,b.substr(c)],c=b[1],b[1]=a?c?c+"&"+a:a:c,a=b[0]+(b[1]?"?"+b[1]:"")+b[2]):a=b;return a+d}
function cf(a){if(!b)var b=window.location.href;var c=a.match(Db)[1]||null,d=Fb(a);c&&d?(a=a.match(Db),b=b.match(Db),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?Fb(b)==d&&(Number(b.match(Db)[4]||null)||null)==(Number(a.match(Db)[4]||null)||null):!0;return a}
function Ye(a){return a&&a.match(Ve)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Q(a){a=df(a);return"string"===typeof a&&"false"===a?!1:!!a}
function ef(a,b){a=df(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function df(a){var b=N("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:N("EXPERIMENT_FLAGS",{})[a]}
;function ff(){}
function gf(a,b){return hf(a,0,b)}
function jf(a,b){return hf(a,1,b)}
;function kf(){ff.apply(this,arguments)}
oa(kf,ff);function hf(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Te(a,c||0)}
function lf(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}}
kf.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};kf.h||(kf.h=new kf);function mf(a){var b=nf;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=vc;e.flash="0";a:{try{var f=b.h.top.location.href}catch(na){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?J:g;try{var h=g.history.length}catch(na){h=0}e.u_his=h;e.u_java=!!J.navigator&&"unknown"!==typeof J.navigator.javaEnabled&&!!J.navigator.javaEnabled&&J.navigator.javaEnabled();J.screen&&(e.u_h=J.screen.height,e.u_w=J.screen.width,
e.u_ah=J.screen.availHeight,e.u_aw=J.screen.availWidth,e.u_cd=J.screen.colorDepth);J.navigator&&J.navigator.plugins&&(e.u_nplug=J.navigator.plugins.length);J.navigator&&J.navigator.mimeTypes&&(e.u_nmime=J.navigator.mimeTypes.length)}catch(na){}h=b.h;try{var k=h.screenX;var l=h.screenY}catch(na){}try{var m=h.outerWidth;var q=h.outerHeight}catch(na){}try{var t=h.innerWidth;var p=h.innerHeight}catch(na){}try{var x=h.screenLeft;var A=h.screenTop}catch(na){}try{t=h.innerWidth,p=h.innerHeight}catch(na){}try{var v=
h.screen.availWidth;var K=h.screen.availTop}catch(na){}k=[x,A,k,l,v,K,m,q,t,p];l=b.h.top;try{var P=(l||window).document,D="CSS1Compat"==P.compatMode?P.documentElement:P.body;var O=(new jc(D.clientWidth,D.clientHeight)).round()}catch(na){O=new jc(-12245933,-12245933)}P=O;O={};D=new Hc;z.SVGElement&&z.document.createElementNS&&D.set(0);l=uc();l["allow-top-navigation-by-user-activation"]&&D.set(1);l["allow-popups-to-escape-sandbox"]&&D.set(2);z.crypto&&z.crypto.subtle&&D.set(3);z.TextDecoder&&z.TextEncoder&&
D.set(4);D=Ic(D);O.bc=D;O.bih=P.height;O.biw=P.width;O.brdim=k.join();b=b.i;b=(O.vis={visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,O.wgl=!!J.WebGLRenderingContext,O);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var nf=new function(){var a=window.document;this.h=window;this.i=a};
E("yt.ads_.signals_.getAdSignalsString",function(a){return $e(mf(a))});var of="XMLHttpRequest"in z?function(){return new XMLHttpRequest}:null;
function pf(){if(!of)return null;var a=of();return"open"in a?a:null}
;var qf={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL",
"X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},rf="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(fa("client_dev_mss_url client_dev_regex_map client_dev_root_url expflag jsfeat jsmode client_rollout_override".split(" "))),sf=!1;
function tf(a,b){b=void 0===b?{}:b;var c=cf(a),d=Q("web_ajax_ignore_global_headers_if_set"),e;for(e in qf){var f=N(qf[e]);!f||!c&&Fb(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!Fb(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!Fb(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!Fb(a))b["X-YouTube-Ad-Signals"]=$e(mf(void 0));return b}
function uf(a){var b=window.location.search,c=Fb(a);Q("debug_handle_relative_url_for_query_forward_killswitch")||c||!cf(a)||(c=document.location.hostname);var d=Eb(a.match(Db)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=af(b),f={};G(rf,function(g){e[g]&&(f[g]=e[g])});
return bf(a,f||{},!1)}
function vf(a,b){var c=b.format||"JSON";a=wf(a,b);var d=xf(a,b),e=!1,f=yf(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);a:switch(k&&"status"in k?k.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:var l=!0;break a;default:l=!1}var m=null,q=400<=k.status&&500>k.status,t=500<=k.status&&600>k.status;if(l||q||t)m=zf(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(m&&m.return_code,10);break a;case "RAW":l=!0;break a}l=
!!m}m=m||{};q=b.context||z;l?b.onSuccess&&b.onSuccess.call(q,k,m):b.onError&&b.onError.call(q,k,m);b.onFinish&&b.onFinish.call(q,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=Te(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||z,f))},b.timeout)}}
function wf(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=N("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=bf(a,b||{},!0);return a}
function xf(a,b){var c=N("XSRF_FIELD_NAME",void 0),d=N("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=N("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||Fb(a)&&!b.withCredentials&&Fb(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=af(e),db(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):Ib(e));if(!(a=e)&&(a=f)){a:{for(var k in f){f=
!1;break a}f=!0}a=!f}!sf&&a&&"POST"!=b.method&&(sf=!0,Je(Error("AJAX request with postData should use POST")));return e}
function zf(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Ke(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Af(a):null)e={},G(a.getElementsByTagName("*"),function(g){e[g.tagName]=Bf(g)})}d&&Cf(e);
return e}
function Cf(a){if(C(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;hb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=Cb(a[b],null);a[c]=d}else Cf(a[b])}}
function Af(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Bf(a){var b="";G(a.childNodes,function(c){b+=c.nodeValue});
return b}
function yf(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Ie(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=pf();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;Q("debug_forward_web_query_parameters")&&(a=uf(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=tf(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Df=ac||bc;function Ef(a){var b=xb;return b?0<=b.toLowerCase().indexOf(a):!1}
;var Ff={},Gf=0;
function Hf(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!Ef("cobalt"))a&&(a instanceof rb||(a="object"==typeof a&&a.S?a.R():String(a),vb.test(a)?a=new rb(a,sb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(ub))&&tb.test(b[1])?new rb(a,sb):null)),a=a||wb,a instanceof rb&&a.constructor===rb?a=a.h:(Ga(a),a="type_error:SafeUrl"),"about:invalid#zClosurez"===a||a.startsWith("data")?a="":(a instanceof Bb||(b="object"==typeof a,c=null,b&&a.na&&(c=a.ma()),a=Cb(jb(b&&a.S?a.R():String(a)),c)),a instanceof
Bb&&a.constructor===Bb?a=a.h:(Ga(a),a="type_error:SafeHtml"),a=encodeURIComponent(String(Td(a.toString())))),/^[\s\xa0]*$/.test(a)||(a=mc("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a)));else if(e)yf(a,b,"POST",e,d);else if(N("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)yf(a,b,"GET","",d);else{b:{try{var f=new Qa({url:a});if(f.j&&f.i||f.l){var g=Eb(a.match(Db)[5]||null);var h=!(!g||!g.endsWith("/aclk")||
"1"!==Kb(a,"ri"));break b}}catch(k){}h=!1}h?If(a)?(b&&b(),c=!0):c=!1:c=!1;c||Jf(a,b)}}
function Kf(a,b,c){c=void 0===c?"":c;If(a,c)?b&&b():Hf(a,b,void 0,void 0,c)}
function If(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function Jf(a,b){var c=new Image,d=""+Gf++;Ff[d]=c;c.onload=c.onerror=function(){b&&Ff[d]&&b();delete Ff[d]};
c.src=a}
;var Lf=z.ytPubsubPubsubInstance||new M,Mf=z.ytPubsubPubsubSubscribedKeys||{},Nf=z.ytPubsubPubsubTopicToKeys||{},Of=z.ytPubsubPubsubIsSynchronous||{};M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.U;M.prototype.publish=M.prototype.O;M.prototype.clear=M.prototype.clear;E("ytPubsubPubsubInstance",Lf);E("ytPubsubPubsubTopicToKeys",Nf);E("ytPubsubPubsubIsSynchronous",Of);E("ytPubsubPubsubSubscribedKeys",Mf);var Pf=window,R=Pf.ytcsi&&Pf.ytcsi.now?Pf.ytcsi.now:Pf.performance&&Pf.performance.timing&&Pf.performance.now&&Pf.performance.timing.navigationStart?function(){return Pf.performance.timing.navigationStart+Pf.performance.now()}:function(){return(new Date).getTime()};var Qf=ef("initial_gel_batch_timeout",2E3),Rf=Math.pow(2,16)-1,Sf=null,Tf=0,Uf=void 0,Vf=0,Wf=0,Xf=0,Yf=!0,Zf=z.ytLoggingTransportGELQueue_||new Map;E("ytLoggingTransportGELQueue_",Zf);var $f=z.ytLoggingTransportTokensToCttTargetIds_||{};E("ytLoggingTransportTokensToCttTargetIds_",$f);
function ag(a,b){if("log_event"===a.endpoint){var c="";a.X?c="visitorOnlyApprovedKey":a.H&&($f[a.H.token]=bg(a.H),c=a.H.token);var d=Zf.get(c)||[];Zf.set(c,d);d.push(a.payload);b&&(Uf=new b);a=ef("tvhtml5_logging_max_batch")||ef("web_logging_max_batch")||100;b=R();d.length>=a?cg({writeThenSend:!0}):10<=b-Xf&&(dg(),Xf=b)}}
function eg(a,b){if("log_event"===a.endpoint){var c="";a.X?c="visitorOnlyApprovedKey":a.H&&($f[a.H.token]=bg(a.H),c=a.H.token);var d=new Map;d.set(c,[a.payload]);b&&(Uf=new b);return new Ud(function(e){Uf&&Uf.isReady()?fg(d,e,{bypassNetworkless:!0}):e()})}}
function cg(a){a=void 0===a?{}:a;new Ud(function(b){window.clearTimeout(Vf);window.clearTimeout(Wf);Wf=0;Uf&&Uf.isReady()?(fg(Zf,b,a),Zf.clear()):(dg(),b())})}
function dg(){Q("web_gel_timeout_cap")&&!Wf&&(Wf=Te(function(){cg({writeThenSend:!0})},6E4));
window.clearTimeout(Vf);var a=N("LOGGING_BATCH_TIMEOUT",ef("web_gel_debounce_ms",1E4));Q("shorten_initial_gel_batch_timeout")&&Yf&&(a=Qf);Vf=Te(function(){cg({writeThenSend:!0})},a)}
function fg(a,b,c){var d=Uf;c=void 0===c?{}:c;var e=Math.round(R()),f=a.size;a=u(a);for(var g=a.next();!g.done;g=a.next()){var h=u(g.value);g=h.next().value;var k=h=h.next().value;h=bb({context:gg(d.config_||hg())});h.events=k;(k=$f[g])&&ig(h,g,k);delete $f[g];g="visitorOnlyApprovedKey"===g;jg(h,e,g);Q("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&Kf("/generate_204");kg(d,"log_event",h,{retry:!0,onSuccess:function(){f--;f||b();Tf=Math.round(R()-e)},
onError:function(){f--;f||b()},
qa:c,X:g});Yf=!1}}
function jg(a,b,c){a.requestTimeMs=String(b);Q("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=N("EVENT_ID",void 0))&&((c=N("BATCH_CLIENT_COUNTER",void 0)||0)||(c=Math.floor(Math.random()*Rf/2)),c++,c>Rf&&(c=1),Fe("BATCH_CLIENT_COUNTER",c),b={serializedEventId:b,clientCounter:String(c)},a.serializedClientEventId=b,Sf&&Tf&&Q("log_gel_rtt_web")&&(a.previousBatchInfo={serializedClientEventId:Sf,roundtripMs:String(Tf)}),Sf=b,Tf=0)}
function ig(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function bg(a){var b={};a.videoId?b.videoId=a.videoId:a.playlistId&&(b.playlistId=a.playlistId);return b}
;var lg=z.ytLoggingGelSequenceIdObj_||{};E("ytLoggingGelSequenceIdObj_",lg);function mg(){if(!z.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return z.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":z.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":z.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":z.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;E("ytglobal.prefsUserPrefsPrefs_",B("ytglobal.prefsUserPrefsPrefs_")||{});var ng={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},og={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function pg(){var a=z.navigator;return a?a.connection:void 0}
;function qg(){return"INNERTUBE_API_KEY"in Ee&&"INNERTUBE_API_VERSION"in Ee}
function hg(){return{innertubeApiKey:N("INNERTUBE_API_KEY",void 0),innertubeApiVersion:N("INNERTUBE_API_VERSION",void 0),Fa:N("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Ga:N("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:N("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Ia:N("INNERTUBE_CONTEXT_HL",void 0),Ha:N("INNERTUBE_CONTEXT_GL",void 0),Ja:N("INNERTUBE_HOST_OVERRIDE",void 0)||"",La:!!N("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Ka:!!N("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:N("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function gg(a){var b={client:{hl:a.Ia,gl:a.Ha,clientName:a.Ga,clientVersion:a.innertubeContextClientVersion,configInfo:a.Fa}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=z.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=N("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=[];var d=N("EXPERIMENTS_FORCED_FLAGS",{});for(e in d)c.push({key:e,value:String(d[e])});var e=N("EXPERIMENT_FLAGS",{});for(var f in e)f.startsWith("force_")&&void 0===
d[f]&&c.push({key:f,value:String(e[f])});0<c.length&&(b.request={internalExperimentFlags:c});f=b.client.clientName;if("WEB"===f||"MWEB"===f||1===f||2===f){if(!Q("web_include_display_mode_killswitch")){var g;b.client.mainAppWebInfo=null!=(g=b.client.mainAppWebInfo)?g:{};b.client.mainAppWebInfo.webDisplayMode=mg()}}else if(g=b.client.clientName,("WEB_REMIX"===g||76===g)&&!Q("music_web_display_mode_killswitch")){var h;b.client.pa=null!=(h=b.client.pa)?h:{};b.client.pa.webDisplayMode=mg()}a.appInstallData&&
(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);N("DELEGATED_SESSION_ID")&&!Q("pageid_as_header_web")&&(b.user={onBehalfOfUser:N("DELEGATED_SESSION_ID")});a:{if(h=pg()){a=ng[h.type||"unknown"]||"CONN_UNKNOWN";h=ng[h.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===a&&"CONN_UNKNOWN"!==h&&(a=h);if("CONN_UNKNOWN"!==a)break a;if("CONN_UNKNOWN"!==h){a=h;break a}}a=void 0}a&&(b.client.connectionType=a);Q("web_log_effective_connection_type")&&
(a=pg(),a=null!==a&&void 0!==a&&a.effectiveType?og.hasOwnProperty(a.effectiveType)?og[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,a&&(b.client.effectiveConnectionType=a));a=Object;h=a.assign;g=b.client;f={};e=u(Object.entries(af(N("DEVICE",""))));for(c=e.next();!c.done;c=e.next())d=u(c.value),c=d.next().value,d=d.next().value,"cbrand"===c?f.deviceMake=d:"cmodel"===c?f.deviceModel=d:"cbr"===c?f.browserName=d:"cbrver"===c?f.browserVersion=d:"cos"===c?f.osName=d:"cosver"===c?f.osVersion=
d:"cplatform"===c&&(f.platform=d);b.client=h.call(a,g,f);return b}
function rg(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||N("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.fb||N("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().eb:b=Gc([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=N("SESSION_INDEX",0),Q("pageid_as_header_web")&&(d["X-Goog-PageId"]=N("DELEGATED_SESSION_ID")));return d}
;function sg(a){a=Object.assign({},a);delete a.Authorization;var b=Gc();if(b){var c=new $c;c.update(N("INNERTUBE_API_KEY",void 0));c.update(b);b=c.digest();c=3;Ha(b);void 0===c&&(c=0);if(!ec){ec={};for(var d="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),e=["+/=","+/","-_=","-_.","-_"],f=0;5>f;f++){var g=d.concat(e[f].split(""));dc[f]=g;for(var h=0;h<g.length;h++){var k=g[h];void 0===ec[k]&&(ec[k]=h)}}}c=dc[c];d=Array(Math.floor(b.length/3));e=c[64]||"";for(f=g=0;g<b.length-
2;g+=3){var l=b[g],m=b[g+1];k=b[g+2];h=c[l>>2];l=c[(l&3)<<4|m>>4];m=c[(m&15)<<2|k>>6];k=c[k&63];d[f++]=""+h+l+m+k}h=0;k=e;switch(b.length-g){case 2:h=b[g+1],k=c[(h&15)<<2]||e;case 1:b=b[g],d[f]=""+c[b>>2]+c[(b&3)<<4|h>>4]+k+e}a.hash=d.join("")}return a}
;function tg(a){var b=new ue;(b=b.isAvailable()?a?new Ae(b,a):b:null)||(a=new ve(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new qe(a):null;this.i=document.domain||window.location.hostname}
tg.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Td(b))}catch(f){return}else e=escape(b);b=this.i;Dc.set(""+a,e,{ea:c,path:"/",domain:void 0===b?"youtube.com":b,secure:!1})};
tg.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Dc.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
tg.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;Dc.remove(""+a,"/",void 0===b?"youtube.com":b)};var ug;function vg(){ug||(ug=new tg("yt.innertube"));return ug}
function wg(a,b,c,d){if(d)return null;d=vg().get("nextId",!0)||1;var e=vg().get("requests",!0)||{};e[d]={method:a,request:b,authState:sg(c),requestTime:Math.round(R())};vg().set("nextId",d+1,86400,!0);vg().set("requests",e,86400,!0);return d}
function xg(a){var b=vg().get("requests",!0)||{};delete b[a];vg().set("requests",b,86400,!0)}
function yg(a){var b=vg().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(R())-d.requestTime)){var e=d.authState,f=sg(rg(!1));ab(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(R())),kg(a,d.method,e,{}));delete b[c]}}vg().set("requests",b,86400,!0)}}
;var zg=B("ytPubsub2Pubsub2Instance")||new M;M.prototype.subscribe=M.prototype.subscribe;M.prototype.unsubscribeByKey=M.prototype.U;M.prototype.publish=M.prototype.O;M.prototype.clear=M.prototype.clear;E("ytPubsub2Pubsub2Instance",zg);E("ytPubsub2Pubsub2SubscribedKeys",B("ytPubsub2Pubsub2SubscribedKeys")||{});E("ytPubsub2Pubsub2TopicToKeys",B("ytPubsub2Pubsub2TopicToKeys")||{});E("ytPubsub2Pubsub2IsAsync",B("ytPubsub2Pubsub2IsAsync")||{});E("ytPubsub2Pubsub2SkipSubKey",null);var Ag=function(){var a;return function(){a||(a=new tg("ytidb"));return a}}();
function Bg(){var a;return null===(a=Ag())||void 0===a?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
function Cg(a){this.h=void 0===a?!1:a;(a=Bg())||(a={hasSucceededOnce:this.h});this.i=a;var b,c;null!==(b=Ag())&&void 0!==b&&b.h&&(b={hasSucceededOnce:this.i.hasSucceededOnce||this.h},null===(c=Ag())||void 0===c?void 0:c.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0))}
Cg.prototype.isSupported=function(){return this.h};var Dg=[],Eg=!1;function Fg(a){Eg||(Dg.push({type:"ERROR",payload:a}),10<Dg.length&&Dg.shift())}
function Gg(a,b){Eg||(Dg.push({type:"EVENT",eventType:a,payload:b}),10<Dg.length&&Dg.shift())}
;function Hg(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.args=[].concat(fa(c))}
oa(Hg,Error);function Ig(){if(void 0!==N("DATASYNC_ID",void 0))return N("DATASYNC_ID",void 0);throw new Hg("Datasync ID not set","unknown");}
;function Jg(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Kg(a){return a.substr(0,a.indexOf(":"))||a}
;var S={},Lg=(S.AUTH_INVALID="No user identifier specified.",S.EXPLICIT_ABORT="Transaction was explicitly aborted.",S.IDB_NOT_SUPPORTED="IndexedDB is not supported.",S.MISSING_INDEX="Index not created.",S.MISSING_OBJECT_STORE="Object store not created.",S.DB_DELETED_BY_MISSING_OBJECT_STORE="Database is deleted because an expected object store was not created.",S.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",S.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",S.QUOTA_MAYBE_EXCEEDED=
"The current transaction may have failed because of exceeding quota limitations.",S.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",S.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",S),T={},Mg=(T.AUTH_INVALID="ERROR",T.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",T.EXPLICIT_ABORT="IGNORED",T.IDB_NOT_SUPPORTED="ERROR",T.MISSING_INDEX="WARNING",T.MISSING_OBJECT_STORE="ERROR",T.DB_DELETED_BY_MISSING_OBJECT_STORE="WARNING",T.QUOTA_EXCEEDED=
"WARNING",T.QUOTA_MAYBE_EXCEEDED="WARNING",T.UNKNOWN_ABORT="WARNING",T.INCOMPATIBLE_DB_VERSION="WARNING",T),U={},Ng=(U.AUTH_INVALID=!1,U.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,U.EXPLICIT_ABORT=!1,U.IDB_NOT_SUPPORTED=!1,U.MISSING_INDEX=!1,U.MISSING_OBJECT_STORE=!1,U.DB_DELETED_BY_MISSING_OBJECT_STORE=!1,U.QUOTA_EXCEEDED=!1,U.QUOTA_MAYBE_EXCEEDED=!0,U.UNKNOWN_ABORT=!0,U.INCOMPATIBLE_DB_VERSION=!1,U);
function V(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Lg[a]:c;d=void 0===d?Mg[a]:d;e=void 0===e?Ng[a]:e;Hg.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,V.prototype)}
oa(V,Hg);function Og(a){V.call(this,"MISSING_OBJECT_STORE",{Na:a},Lg.MISSING_OBJECT_STORE);Object.setPrototypeOf(this,Og.prototype)}
oa(Og,V);function Pg(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Pg.prototype)}
oa(Pg,Error);var Qg=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Rg(a,b,c,d){b=Kg(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof V)return e;if("QuotaExceededError"===e.name)return new V("QUOTA_EXCEEDED",{objectStoreNames:c,dbName:b});if(cc&&"UnknownError"===e.name)return new V("QUOTA_MAYBE_EXCEEDED",{objectStoreNames:c,dbName:b});if(e instanceof Pg)return new V("MISSING_INDEX",{dbName:b,dbVersion:d,objectStore:e.objectStore,index:e.index});if("InvalidStateError"===e.name&&Qg.some(function(f){return e.message.includes(f)}))return new V("EXECUTE_TRANSACTION_ON_CLOSED_DB",
{objectStoreNames:c,
dbName:b});if("AbortError"===e.name)return new V("UNKNOWN_ABORT",{objectStoreNames:c,dbName:b},e.message);e.args=[{name:"IdbError",kb:e.name,dbName:b,objectStoreNames:c}];e.level="WARNING";return e}
function Sg(a,b,c){return new V("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c}})}
;function Tg(a){if(!a)throw Error();throw a;}
function Ug(a){return a}
function Vg(a){this.h=a}
function W(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=u(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=u(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.onRejected=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
W.all=function(a){return new W(new Vg(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={M:0};f.M<a.length;f={M:f.M},++f.M)Wg(W.resolve(a[f.M]).then(function(g){return function(h){d[g.M]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
W.resolve=function(a){return new W(new Vg(function(b,c){a instanceof W?a.then(b,c):b(a)}))};
W.reject=function(a){return new W(new Vg(function(b,c){c(a)}))};
W.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:Ug,e=null!==b&&void 0!==b?b:Tg;return new W(new Vg(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){Xg(c,c,d,f,g)}),c.onRejected.push(function(){Yg(c,c,e,f,g)})):"FULFILLED"===c.state.status?Xg(c,c,d,f,g):"REJECTED"===c.state.status&&Yg(c,c,e,f,g)}))};
function Wg(a,b){a.then(void 0,b)}
function Xg(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof W?Zg(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Yg(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof W?Zg(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Zg(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof W?Zg(a,b,f,d,e):d(f)},function(f){e(f)})}
;function $g(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function ah(a){return new Promise(function(b,c){$g(a,b,c)})}
function X(a){return new W(new Vg(function(b,c){$g(a,b,c)}))}
;function bh(a,b){return new W(new Vg(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function ch(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(R());this.i=!1}
n=ch.prototype;n.add=function(a,b,c){return dh(this,[a],{mode:"readwrite",D:!0},function(d){return d.objectStore(a).add(b,c)})};
n.clear=function(a){return dh(this,[a],{mode:"readwrite",D:!0},function(b){return b.objectStore(a).clear()})};
n.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
n.count=function(a,b){return dh(this,[a],{mode:"readonly",D:!0},function(c){return c.objectStore(a).count(b)})};
n.delete=function(a,b){return dh(this,[a],{mode:"readwrite",D:!0},function(c){return c.objectStore(a).delete(b)})};
n.get=function(a,b){return dh(this,[a],{mode:"readonly",D:!0},function(c){return c.objectStore(a).get(b)})};
function eh(a,b){return dh(a,["LogsRequestsStore"],{mode:"readwrite",D:!0},function(c){c=c.objectStore("LogsRequestsStore");return X(c.h.put(b,void 0))})}
n.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function dh(a,b,c,d){return I(a,function f(){var g=this,h,k,l,m,q,t,p,x,A,v,K,P;return y(f,function(D){switch(D.h){case 1:var O={mode:"readonly",D:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?O.mode=c:Object.assign(O,c);h=O;g.transactionCount++;k=h.D?3:1;l=0;case 2:if(m){D.v(3);break}l++;q=Math.round(R());sa(D,4);t=g.h.transaction(b,h.mode);O=new fh(t);O=gh(O,d);return w(D,O,6);case 6:return p=D.i,x=Math.round(R()),hh(g,q,x,l,void 0,b.join(),h),D.return(p);case 4:A=ta(D);v=Math.round(R());
K=Rg(A,g.h.name,b.join(),g.h.version);if((P=K instanceof V&&!K.h)||l>=k)hh(g,q,v,l,K,b.join(),h),m=K;D.v(2);break;case 3:return D.return(Promise.reject(m))}})})}
function hh(a,b,c,d,e,f,g){b=c-b;e?(e instanceof V&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&Gg("QUOTA_EXCEEDED",{dbName:Kg(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof V&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),Gg("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),ih(a,!1,d,f,b,g.tag),Fg(e)):ih(a,!0,d,f,b,g.tag)}
function ih(a,b,c,d,e,f){Gg("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
n.getName=function(){return this.h.name};
function jh(a){this.h=a}
n=jh.prototype;n.add=function(a,b){return X(this.h.add(a,b))};
n.autoIncrement=function(){return this.h.autoIncrement};
n.clear=function(){return X(this.h.clear()).then(function(){})};
n.count=function(a){return X(this.h.count(a))};
function kh(a,b){return lh(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
n.delete=function(a){return a instanceof IDBKeyRange?kh(this,a):X(this.h.delete(a))};
n.get=function(a){return X(this.h.get(a))};
n.index=function(a){try{return new mh(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Pg(a,this.h.name);throw b;}};
n.getName=function(){return this.h.name};
n.keyPath=function(){return this.h.keyPath};
function lh(a,b,c){a=a.h.openCursor(b.query,b.direction);return nh(a).then(function(d){return bh(d,c)})}
function fh(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=V;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function gh(a,b){var c=new Promise(function(d,e){try{Wg(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return u(d).next().value})}
fh.prototype.abort=function(){this.h.abort();this.i=!0;throw new V("EXPLICIT_ABORT");};
fh.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new jh(a),this.j.set(a,b));return b};
function mh(a){this.h=a}
n=mh.prototype;n.count=function(a){return X(this.h.count(a))};
n.delete=function(a){return oh(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
n.get=function(a){return X(this.h.get(a))};
n.getKey=function(a){return X(this.h.getKey(a))};
n.keyPath=function(){return this.h.keyPath};
n.unique=function(){return this.h.unique};
function oh(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return nh(a).then(function(d){return bh(d,c)})}
function ph(a,b){this.request=a;this.cursor=b}
function nh(a){return X(a).then(function(b){return b?new ph(a,b):null})}
n=ph.prototype;n.advance=function(a){this.cursor.advance(a);return nh(this.request)};
n.continue=function(a){this.cursor.continue(a);return nh(this.request)};
n.delete=function(){return X(this.cursor.delete()).then(function(){})};
n.getKey=function(){return this.cursor.key};
n.update=function(a){return X(this.cursor.update(a))};function qh(a,b,c){return new Promise(function(d,e){function f(){t||(t=new ch(g.result,{closed:q}));return t}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.Qa,m=c.upgrade,q=c.closed,t;g.addEventListener("upgradeneeded",function(p){try{if(null===p.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");p.dataLoss&&"none"!==p.dataLoss&&Gg("IDB_DATA_CORRUPTED",{reason:p.dataLossMessage||"unknown reason",dbName:Kg(a)});var x=f(),A=new fh(g.transaction);
m&&m(x,function(v){return p.oldVersion<v&&p.newVersion>=v},A);
A.done.catch(function(v){e(v)})}catch(v){e(v)}});
g.addEventListener("success",function(){var p=g.result;k&&p.addEventListener("versionchange",function(){k(f())});
p.addEventListener("close",function(){Gg("IDB_UNEXPECTEDLY_CLOSED",{dbName:Kg(a),dbVersion:p.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function rh(a,b,c){c=void 0===c?{}:c;return qh(a,b,c)}
function sh(a,b){b=void 0===b?{}:b;return I(this,function d(){var e,f,g;return y(d,function(h){e=self.indexedDB.deleteDatabase(a);f=b;(g=f.blocked)&&e.addEventListener("blocked",function(){g()});
return w(h,ah(e),0)})})}
;function th(a,b){this.name=a;this.options=b;this.l=!0;this.j=!1}
th.prototype.i=function(a,b,c){c=void 0===c?{}:c;return rh(a,b,c)};
th.prototype.delete=function(a){a=void 0===a?{}:a;return sh(this.name,a)};
function uh(a,b){return new V("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
th.prototype.open=function(){function a(){return I(c,function g(){var h=this,k,l,m,q,t;return y(g,function(p){switch(p.h){case 1:return sa(p,2),w(p,h.i(h.name,h.options.version,e),4);case 4:k=p.i;a:{var x=h.options;for(var A=u(Object.keys(x.ga)),v=A.next();!v.done;v=A.next()){v=v.value;var K=x.ga[v],P=void 0===K.Pa?Number.MAX_VALUE:K.Pa;if(k.h.version>=K.ia&&!(k.h.version>=P)&&!k.h.objectStoreNames.contains(v)){x=v;break a}}x=void 0}l=x;if(void 0===l){p.v(5);break}if(h.j){p.v(6);break}h.j=!0;return w(p,
h.delete(),7);case 7:return Fg(new V("DB_DELETED_BY_MISSING_OBJECT_STORE",{dbName:h.name,Na:l})),p.return(a());case 6:throw new Og(l);case 5:return p.return(k);case 2:m=ta(p);if(m instanceof DOMException?"VersionError"!==m.name:"DOMError"in self&&m instanceof DOMError?"VersionError"!==m.name:!(m instanceof Object&&"message"in m)||"An attempt was made to open a database using a lower version than the existing version."!==m.message){p.v(8);break}return w(p,h.i(h.name,void 0,Object.assign(Object.assign({},
e),{upgrade:void 0})),9);case 9:q=p.i;t=q.h.version;if(void 0!==h.options.version&&t>h.options.version+1)throw q.close(),h.l=!1,uh(h,t);return p.return(q);case 8:throw b(),m;}})})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.l)throw uh(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Qa:b,upgrade:this.options.upgrade};return this.h=d=a()};var vh=new th("YtIdbMeta",{ga:{databases:{ia:1}},upgrade:function(a,b){b(1)&&a.h.createObjectStore("databases",{keyPath:"actualName"})}});
function wh(a){return I(this,function c(){var d;return y(c,function(e){if(1==e.h)return w(e,vh.open(),2);d=e.i;return e.return(dh(d,["databases"],{D:!0,mode:"readwrite"},function(f){var g=f.objectStore("databases");return g.get(a.actualName).then(function(h){if(h?a.actualName!==h.actualName||a.publicName!==h.publicName||a.userIdentifier!==h.userIdentifier:1)return X(g.h.put(a,void 0)).then(function(){})})}))})})}
function xh(a){return I(this,function c(){var d;return y(c,function(e){if(1==e.h)return a?w(e,vh.open(),2):e.return();d=e.i;return e.return(d.delete("databases",a))})})}
;var yh,zh=new function(){}(new function(){});
function Ah(){return I(this,function b(){var c,d,e;return y(b,function(f){switch(f.h){case 1:c=Bg();if(null===c||void 0===c?0:c.hasSucceededOnce)return f.return(new Cg(!0));var g;if(g=Df)g=/WebKit\/([0-9]+)/.exec(xb),g=!!(g&&600<=parseInt(g[1],10));g&&(g=/WebKit\/([0-9]+)/.exec(xb),g=!(g&&602<=parseInt(g[1],10)));if(g||Pb)return f.return(new Cg(!1));try{if(d=self,!(d.indexedDB&&d.IDBIndex&&d.IDBKeyRange&&d.IDBObjectStore))return f.return(new Cg(!1))}catch(h){return f.return(new Cg(!1))}if(!("IDBTransaction"in
self&&"objectStoreNames"in IDBTransaction.prototype))return f.return(new Cg(!1));sa(f,2);e={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(f,wh(e),4);case 4:return w(f,xh("yt-idb-test-do-not-use"),5);case 5:return f.return(new Cg(!0));case 2:return ta(f),f.return(new Cg(!1))}})})}
function Bh(){if(void 0!==yh)return yh;Eg=!0;return yh=Ah().then(function(a){Eg=!1;return a.isSupported()})}
function Ch(){return Bh().then(function(a){return a?zh:void 0})}
;new function(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})};function Dh(a){try{Ig();var b=!0}catch(c){b=!1}if(!b)throw a=new V("AUTH_INVALID",{dbName:a}),Fg(a),a;b=Ig();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Eh(a,b,c,d){return I(this,function f(){var g,h,k,l;return y(f,function(m){switch(m.h){case 1:return w(m,Ch(),2);case 2:g=m.i;if(!g)throw h=Sg("openDbImpl",a,b),Fg(h),h;Jg(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Dh(a);sa(m,3);return w(m,wh(k),5);case 5:return w(m,rh(k.actualName,b,d),6);case 6:return m.return(m.i);case 3:return l=ta(m),sa(m,7),w(m,xh(k.actualName),9);case 9:m.h=8;m.o=0;break;case 7:ta(m);case 8:throw l;}})})}
function Fh(a,b,c){c=void 0===c?{}:c;return Eh(a,b,!1,c)}
function Gh(a,b,c){c=void 0===c?{}:c;return Eh(a,b,!0,c)}
function Hh(a,b){b=void 0===b?{}:b;return I(this,function d(){var e,f;return y(d,function(g){if(1==g.h)return w(g,Ch(),2);if(3!=g.h){e=g.i;if(!e)return g.return();Jg(a);f=Dh(a);return w(g,sh(f.actualName,b),3)}return w(g,xh(f.actualName),0)})})}
function Ih(a,b){b=void 0===b?{}:b;return I(this,function d(){var e;return y(d,function(f){if(1==f.h)return w(f,Ch(),2);if(3!=f.h){e=f.i;if(!e)return f.return();Jg(a);return w(f,sh(a,b),3)}return w(f,xh(a),0)})})}
;function Jh(a,b){th.call(this,a,b);this.options=b;Jg(a)}
oa(Jh,th);function Kh(a){var b;return function(){b||(b=new Jh("LogsDatabaseV2",a));return b}}
Jh.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.ta?Gh:Fh)(a,b,Object.assign({},c))};
Jh.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.ta?Ih:Hh)(this.name,a)};var Lh;
function Mh(){if(Lh)return Lh();var a={};Lh=Kh({ga:(a.LogsRequestsStore={ia:2},a),ta:!1,upgrade:function(b,c,d){c(2)&&b.h.createObjectStore("LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Lh()}
;function Nh(a){return I(this,function c(){var d,e,f,g;return y(c,function(h){if(1==h.h)return d={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(h,Mh().open(),2);if(3!=h.h)return e=h.i,f=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),interface:N("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(h,eh(e,f),3);g=h.i;d.Ra=R();Oh(d);return h.return(g)})})}
function Ph(){return I(this,function b(){var c,d,e,f,g,h,k;return y(b,function(l){if(1==l.h)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(l,Mh().open(),2);if(3!=l.h)return d=l.i,e=N("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=["NEW",e,0],g=["NEW",e,R()],h=IDBKeyRange.bound(f,g),k=void 0,w(l,dh(d,["LogsRequestsStore"],{mode:"readwrite",D:!0},function(m){return oh(m.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(q){q.cursor.value&&(k=
q.cursor.value,k.status="QUEUED",q.update(k))})}),3);
c.Ra=R();Oh(c);return l.return(k)})})}
function Qh(a){return I(this,function c(){var d;return y(c,function(e){if(1==e.h)return w(e,Mh().open(),2);d=e.i;return e.return(dh(d,["LogsRequestsStore"],{mode:"readwrite",D:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){if(h)return h.status="QUEUED",X(g.h.put(h,void 0)).then(function(){return h})})}))})})}
function Rh(a){return I(this,function c(){var d;return y(c,function(e){if(1==e.h)return w(e,Mh().open(),2);d=e.i;return e.return(dh(d,["LogsRequestsStore"],{mode:"readwrite",D:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",h.sendCount+=1,X(g.h.put(h,void 0)).then(function(){return h})):W.resolve(void 0)})}))})})}
function Sh(a){return I(this,function c(){var d;return y(c,function(e){if(1==e.h)return w(e,Mh().open(),2);d=e.i;return e.return(d.delete("LogsRequestsStore",a))})})}
function Oh(a){if(!Q("nwl_csi_killswitch")&&.01>=Math.random()){var b=B("ytPubsub2Pubsub2Instance");b&&b.publish.call(b,"nwl_transaction_latency_payload".toString(),"nwl_transaction_latency_payload",a)}}
;var Th;function Uh(){Th||(Th=new tg("yt.offline"));return Th}
function Vh(a){if(Q("offline_error_handling")){var b=Uh().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Uh().set("errors",b,2592E3,!0)}}
;var Wh=ef("network_polling_interval",3E4);function Y(){L.call(this);this.B=0;this.N=this.l=!1;this.i=this.da();Xh(this);Yh(this)}
oa(Y,L);function Zh(){if(!Y.h){var a=B("yt.networkStatusManager.instance")||new Y;E("yt.networkStatusManager.instance",a);Y.h=a}return Y.h}
n=Y.prototype;n.J=function(){return this.i};
n.Oa=function(a){this.l=!0;if(void 0===a?0:a)this.B||$h(this)};
n.da=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
n.Da=function(){this.N=!0};
n.Z=function(a,b){return L.prototype.Z.call(this,a,b)};
function Yh(a){window.addEventListener("online",function(){return I(a,function c(){var d=this;return y(c,function(e){if(1==e.h)return w(e,d.L(),2);if(d.N&&Q("offline_error_handling")){var f=Uh().get("errors",!0);if(f){for(var g in f)if(f[g]){var h=new Hg(g,"sent via offline_errors");h.name=f[g].name;h.stack=f[g].stack;h.level=f[g].level;Je(h)}Uh().set("errors",{},2592E3,!0)}}e.h=0})})})}
function Xh(a){window.addEventListener("offline",function(){return I(a,function c(){var d=this;return y(c,function(e){return w(e,d.L(),0)})})})}
function $h(a){a.B=gf(function(){return I(a,function c(){var d=this;return y(c,function(e){if(1==e.h)return d.i?d.da()||!d.l?e.v(3):w(e,d.L(),3):w(e,d.L(),3);$h(d);e.h=0})})},Wh)}
n.L=function(a){var b=this;return this.o?this.o:this.o=new Promise(function(c){return I(b,function e(){var f,g,h,k=this;return y(e,function(l){switch(l.h){case 1:return f=window.AbortController?new window.AbortController:void 0,g=null===f||void 0===f?void 0:f.signal,h=!1,sa(l,2,3),f&&(k.u=jf(function(){f.abort()},a||2E4)),w(l,fetch("/generate_204",{method:"HEAD",
signal:g}),5);case 5:h=!0;case 3:ua(l);k.o=void 0;k.u&&lf(k.u);h!==k.i&&(k.i=h,k.i&&k.l?Rd(k,"ytnetworkstatus-online"):k.l&&Rd(k,"ytnetworkstatus-offline"));c(h);va(l);break;case 2:ta(l),h=!1,l.v(3)}})})})};
Y.prototype.sendNetworkCheckRequest=Y.prototype.L;Y.prototype.listen=Y.prototype.Z;Y.prototype.enableErrorFlushing=Y.prototype.Da;Y.prototype.getWindowStatus=Y.prototype.da;Y.prototype.monitorNetworkStatusChange=Y.prototype.Oa;Y.prototype.isNetworkAvailable=Y.prototype.J;Y.getInstance=Zh;function ai(a){a=void 0===a?{}:a;L.call(this);var b=this;this.l=this.u=0;this.i=Zh();var c=B("yt.networkStatusManager.instance.monitorNetworkStatusChange").bind(this.i);c&&c(a.Ea);a.Ma&&(c=B("yt.networkStatusManager.instance.enableErrorFlushing").bind(this.i))&&c();if(c=B("yt.networkStatusManager.instance.listen").bind(this.i))a.ba?(this.ba=a.ba,c("ytnetworkstatus-online",function(){bi(b,"publicytnetworkstatus-online")}),c("ytnetworkstatus-offline",function(){bi(b,"publicytnetworkstatus-offline")})):
(c("ytnetworkstatus-online",function(){Rd(b,"publicytnetworkstatus-online")}),c("ytnetworkstatus-offline",function(){Rd(b,"publicytnetworkstatus-offline")}))}
oa(ai,L);ai.prototype.J=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable").bind(this.i);return a?a():!0};
ai.prototype.L=function(a){return I(this,function c(){var d=this,e;return y(c,function(f){return(e=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(d.i))?f.return(e(a)):f.return(!0)})})};
function bi(a,b){a.ba?a.l?(lf(a.u),a.u=jf(function(){a.o!==b&&(Rd(a,b),a.o=b,a.l=R())},a.ba-(R()-a.l))):(Rd(a,b),a.o=b,a.l=R()):Rd(a,b)}
;var ci=0,di=0,ei,fi=z.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:!1,databaseToken:void 0,potentialEsfErrorCounter:di,isIdbSupported:!1};E("ytNetworklessLoggingInitializationOptions",fi);function gi(a,b){function c(d){var e=hi().J();if(!ii()||!d||e&&Q("vss_networkless_bypass_write"))ji(a,b);else{var f={url:a,options:b,timestamp:R(),status:"NEW",sendCount:0};Nh(f).then(function(g){f.id=g;hi().J()&&ki(f)}).catch(function(g){ki(f);
hi().J()?Je(g):Vh(g)})}}
b=void 0===b?{}:b;Q("skip_is_supported_killswitch")?Ch().then(function(d){c(d)}):c(li())}
function mi(a,b){function c(d){if(ii()&&d){var e={url:a,options:b,timestamp:R(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(h,k){void 0!==e.id?Sh(e.id):f=!0;g(h,k)};
ji(e.url,e.options);Nh(e).then(function(h){e.id=h;f&&Sh(e.id)}).catch(function(h){hi().J()?Je(h):Vh(h)})}else ji(a,b)}
b=void 0===b?{}:b;Q("skip_is_supported_killswitch")?Ch().then(function(d){c(d)}):c(li())}
function ni(){var a=this;if(!li())throw Sg("throttleSend");ci||(ci=jf(function(){return I(a,function c(){var d;return y(c,function(e){if(1==e.h)return w(e,Ph(),2);if(3!=e.h)return d=e.i,d?w(e,ki(d),3):(lf(ci),ci=0,e.return());ci&&(ci=0,ni());e.h=0})})},100))}
function ki(a){return I(this,function c(){var d,e,f;return y(c,function(g){switch(g.h){case 1:d=li();if(!d)throw e=Sg("immediateSend"),e;if(void 0===a.id){g.v(2);break}return w(g,Qh(a.id),3);case 3:(f=g.i)?a=f:Ke(Error("The request cannot be found in the database."));case 2:var h=a.timestamp;if(!(2592E6<=R()-h)){g.v(4);break}Ke(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){g.v(5);break}return w(g,Sh(a.id),5);case 5:return g.return();case 4:a.skipRetry||(a=
oi(a));h=a;var k,l;if(null===(l=null===(k=null===h||void 0===h?void 0:h.options)||void 0===k?void 0:k.postParams)||void 0===l?0:l.requestTimeMs)h.options.postParams.requestTimeMs=Math.round(R());a=h;if(!a){g.v(0);break}if(!a.skipRetry||void 0===a.id){g.v(8);break}return w(g,Sh(a.id),8);case 8:ji(a.url,a.options,!!a.skipRetry),g.h=0}})})}
function oi(a){var b=this;if(!li())throw Sg("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){return I(b,function h(){return y(h,function(k){switch(k.h){case 1:if(!((B("ytNetworklessLoggingInitializationOptions")?fi.potentialEsfErrorCounter:di)<=ef("potential_esf_error_limit",10))){k.v(2);break}return w(k,hi().L(),3);case 3:if(hi().J())B("ytNetworklessLoggingInitializationOptions")&&fi.potentialEsfErrorCounter++,di++;else return c(e,f),k.return();case 2:if(void 0===(null===a||void 0===a?void 0:a.id)){k.v(4);break}return 1>a.sendCount?w(k,Rh(a.id),8):w(k,Sh(a.id),
4);case 8:jf(function(){hi().J()&&ni()},5E3);
case 4:c(e,f),k.h=0}})})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){return I(b,function h(){return y(h,function(k){if(1==k.h)return void 0===(null===a||void 0===a?void 0:a.id)?k.v(2):w(k,Sh(a.id),2);d(e,f);k.h=0})})};
return a}
function hi(){ei||(ei=new ai({Ma:!0,Ea:!0}));return ei}
function ji(a,b,c){if(Q("networkless_with_beacon")){var d=["method","postBody"];if(Object.keys(b).length>d.length)c=!0;else{c=0;d=u(d);for(var e=d.next();!e.done;e=d.next())b.hasOwnProperty(e.value)&&c++;c=Object.keys(b).length!==c}c?vf(a,b):Kf(a,void 0,b.postBody)}else c&&0===Object.keys(b).length?Hf(a):vf(a,b)}
function ii(){return B("ytNetworklessLoggingInitializationOptions")?fi.isNwlInitialized:!1}
function li(){return B("ytNetworklessLoggingInitializationOptions")?fi.databaseToken:void 0}
;function pi(a){var b=this;this.config_=null;a?this.config_=a:qg()&&(this.config_=hg());gf(function(){yg(b)},5E3)}
pi.prototype.isReady=function(){!this.config_&&qg()&&(this.config_=hg());return!!this.config_};
function kg(a,b,c,d){function e(t){t=void 0===t?!1:t;var p;if(d.retry&&"www.youtube-nocookie.com"!=h&&(t||(p=wg(b,c,l,k)),p)){var x=g.onSuccess,A=g.onFetchSuccess;g.onSuccess=function(v,K){xg(p);x(v,K)};
c.onFetchSuccess=function(v,K){xg(p);A(v,K)}}try{t&&d.retry&&!d.qa.bypassNetworkless?(g.method="POST",d.qa.writeThenSend?gi(q,g):mi(q,g)):(g.method="POST",g.postParams||(g.postParams={}),vf(q,g))}catch(v){if("InvalidAccessError"==v.name)p&&(xg(p),p=0),Ke(Error("An extension is blocking network request."));
else throw v;}p&&gf(function(){yg(a)},5E3)}
!N("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Ke(new Hg("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new Hg("innertube xhrclient not ready",b,c,d);Je(f);throw f;}var g={headers:{"Content-Type":"application/json"},method:"POST",postParams:c,postBodyFormat:"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(t,p){if(d.onSuccess)d.onSuccess(p)},
onFetchSuccess:function(t){if(d.onSuccess)d.onSuccess(t)},
onError:function(t,p){if(d.onError)d.onError(p)},
onFetchError:function(t){if(d.onError)d.onError(t)},
timeout:d.timeout,withCredentials:!0},h="";(f=a.config_.Ja)&&(h=f);var k=a.config_.La||!1,l=rg(k,h,d);Object.assign(g.headers,l);g.headers.Authorization&&!h&&(g.headers["x-origin"]=window.location.origin);f="/youtubei/"+a.config_.innertubeApiVersion+"/"+b;var m={alt:"json"};a.config_.Ka&&g.headers.Authorization||(m.key=a.config_.innertubeApiKey);var q=bf(""+h+f,m||{},!0);ii()?Bh().then(function(t){e(t)}):e(!1)}
;function qi(a,b){var c=void 0===c?{}:c;var d=pi;N("ytLoggingEventsDefaultDisabled",!1)&&pi==pi&&(d=null);c=void 0===c?{}:c;var e={},f=Math.round(c.timestamp||R());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=B("_lact",window);a=null==a?-1:Math.max(Date.now()-a,0);e.context={lastActivityMs:String(c.timestamp||!isFinite(a)?-1:a)};Q("log_sequence_info_on_gel_web")&&c.sa&&(a=e.context,b=c.sa,lg[b]=b in lg?lg[b]+1:0,a.sequence={index:lg[b],groupKey:b},c.hb&&delete lg[c.sa]);(c.mb?eg:ag)({endpoint:"log_event",
payload:e,H:c.H,X:c.X},d)}
;var ri=[{fa:function(a){return"Cannot read property '"+a.key+"'"},
aa:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{fa:function(a){return"Cannot call '"+a.key+"'"},
aa:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{fa:function(a){return a.key+" is not defined"},
aa:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var ti={K:[],I:[{Aa:si,weight:500}]};function si(a){a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function ui(){this.I=[];this.K=[]}
var vi;function wi(){if(!vi){var a=vi=new ui;a.K.length=0;a.I.length=0;ti.K&&a.K.push.apply(a.K,ti.K);ti.I&&a.I.push.apply(a.I,ti.I)}return vi}
;var xi=new M;function yi(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=zi(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=zi(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=zi(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function zi(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Ai(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Bi(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=yi(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Bi(e+".ve",f,g,h):0;d+=g;d+=Bi(e,a[e],b,c);if(500<d)break}}else c[b]=Ci(a),d+=c[b].length;else c[b]=Ci(a),d+=c[b].length;return d}
function Bi(a,b,c,d){c+="."+a;a=Ci(b);d[c]=a;return c.length+a.length}
function Ci(a){return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}
;var Di=new Set,Ei=0,Fi=0,Gi=0,Hi=[],Ii=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];var Ji={};function Ki(a){return Ji[a]||(Ji[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Li={},Mi=[],ke=new M,Ni={};function Oi(){for(var a=u(Mi),b=a.next();!b.done;b=a.next())b=b.value,b()}
function Pi(a,b){var c;"yt:"===a.tagName.toLowerCase().substr(0,3)?c=a.getAttribute(b):c=a?a.dataset?a.dataset[Ki(b)]:a.getAttribute("data-"+b):null;return c}
function Qi(a,b){for(var c=1;c<arguments.length;++c);ke.O.apply(ke,arguments)}
;function Ri(a){this.h=a||{};a=[this.h,window.YTConfig||{}];for(var b=0;b<a.length;b++)a[b].host&&(a[b].host=a[b].host.toString().replace("http://","https://"))}
function Z(a,b){a=[a.h,window.YTConfig||{}];for(var c=0;c<a.length;c++){var d=a[c][b];if(void 0!==d)return d}return null}
function Si(a,b,c){Ti||(Ti={},Se(window,"message",function(d){a:{if(d.origin===Z(a,"host")){try{var e=JSON.parse(d.data)}catch(f){e=void 0;break a}if(d=Ti[e.id])d.s=!0,d.s&&(G(d.o,d.sendMessage,d),d.o.length=0),d.ha(e)}e=void 0}return e}));
Ti[c]=b}
var Ti=null;function Ui(a,b,c){this.m=this.h=this.i=null;this.j=0;this.s=!1;this.o=[];this.l=null;this.B={};if(!a)throw Error("YouTube player element ID required.");this.id=Ia(this);this.u=c;this.setup(a,b)}
n=Ui.prototype;n.setSize=function(a,b){this.h.width=a.toString();this.h.height=b.toString();return this};
n.za=function(){return this.h};
n.ha=function(a){Vi(this,a.event,a)};
n.addEventListener=function(a,b){var c=b;"string"===typeof b&&(c=function(){window[b].apply(window,arguments)});
if(!c)return this;this.l.subscribe(a,c);Wi(this,a);return this};
function Xi(a,b){b=b.split(".");if(2===b.length){var c=b[1];a.u===b[0]&&Wi(a,c)}}
n.destroy=function(){this.h&&this.h.id&&(Li[this.h.id]=null);var a=this.l;a&&"function"==typeof a.dispose&&a.dispose();if(this.m){a=this.h;var b=a.parentNode;b&&b.replaceChild(this.m,a)}else(a=this.h)&&a.parentNode&&a.parentNode.removeChild(a);Ti&&(Ti[this.id]=null);this.i=null;a=this.h;for(var c in $a)$a[c][0]==a&&Qe(c);this.m=this.h=null};
n.ka=function(){return{}};
function Yi(a,b,c){c=c||[];c=Array.prototype.slice.call(c);b={event:"command",func:b,args:c};a.s?a.sendMessage(b):a.o.push(b)}
function Vi(a,b,c){a.l.j||(c={target:a,data:c},a.l.O(b,c),Qi(a.u+"."+b,c))}
function Zi(a,b){var c=document.createElement("iframe");b=b.attributes;for(var d=0,e=b.length;d<e;d++){var f=b[d].value;null!=f&&""!==f&&"null"!==f&&c.setAttribute(b[d].name,f)}c.setAttribute("frameBorder","0");c.setAttribute("allowfullscreen","1");c.setAttribute("allow","accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture");c.setAttribute("title","YouTube "+Z(a.i,"title"));(b=Z(a.i,"width"))&&c.setAttribute("width",b.toString());(b=Z(a.i,"height"))&&c.setAttribute("height",
b.toString());var g=a.ka();g.enablejsapi=window.postMessage?1:0;window.location.host&&(g.origin=window.location.protocol+"//"+window.location.host);g.widgetid=a.id;window.location.href&&G(["debugjs","debugcss"],function(h){var k=Kb(window.location.href,h);null!==k&&(g[h]=k)});
window.yt_embedsTokenValue&&(g.embedsTokenValue=encodeURIComponent(window.yt_embedsTokenValue),delete window.yt_embedsTokenValue);c.src=Z(a.i,"host")+("/embed/"+Z(a.i,"videoId"))+"?"+Ib(g);return c}
n.ra=function(){this.h&&this.h.contentWindow?this.sendMessage({event:"listening"}):window.clearInterval(this.j)};
function $i(a){Si(a.i,a,a.id);a.j=Ue(a.ra.bind(a));Se(a.h,"load",function(){window.clearInterval(a.j);a.j=Ue(a.ra.bind(a))})}
n.setup=function(a,b){var c=document;if(a="string"===typeof a?c.getElementById(a):a)if(c="iframe"===a.tagName.toLowerCase(),b.host||(b.host=c?Gb(a.src):"https://www.youtube.com"),this.i=new Ri(b),c||(b=Zi(this,a),this.m=a,(c=a.parentNode)&&c.replaceChild(b,a),a=b),this.h=a,this.h.id||(this.h.id="widget"+Ia(this.h)),Li[this.h.id]=this,window.postMessage){this.l=new M;$i(this);b=Z(this.i,"events");for(var d in b)b.hasOwnProperty(d)&&this.addEventListener(d,b[d]);for(var e in Ni)Ni.hasOwnProperty(e)&&
Xi(this,e)}};
function Wi(a,b){a.B[b]||(a.B[b]=!0,Yi(a,"addEventListener",[b]))}
n.sendMessage=function(a){a.id=this.id;a.channel="widget";a=Td(a);var b=[Gb(this.h.src||"").replace("http:","https:")];if(this.h.contentWindow)for(var c=0;c<b.length;c++)try{this.h.contentWindow.postMessage(a,b[c])}catch(v){if(v.name&&"SyntaxError"===v.name){if(!(v.message&&0<v.message.indexOf("target origin ''"))){var d=void 0,e=v;d=void 0===d?{}:d;d.name=N("INNERTUBE_CONTEXT_CLIENT_NAME",1);d.version=N("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);var f=d||{};d="WARNING";d=void 0===d?"ERROR":d;if(e){e.hasOwnProperty("level")&&
e.level&&(d=e.level);if(Q("console_log_js_exceptions")){var g=e,h=[];h.push("Name: "+g.name);h.push("Message: "+g.message);g.hasOwnProperty("params")&&h.push("Error Params: "+JSON.stringify(g.params));g.hasOwnProperty("args")&&h.push("Error args: "+JSON.stringify(g.args));h.push("File name: "+g.fileName);h.push("Stacktrace: "+g.stack);window.console.log(h.join("\n"),g)}if(!(5<=Ei)){g=void 0;var k=f,l=bd(e);f=l.message||"Unknown Error";h=l.name||"UnknownError";var m=l.stack||e.i||"Not available";if(m.startsWith(h+
": "+f)){var q=m.split("\n");q.shift();m=q.join("\n")}q=l.lineNumber||"Not available";l=l.fileName||"Not available";var t=0;if(e.hasOwnProperty("args")&&e.args&&e.args.length)for(g=0;g<e.args.length&&!(t=Ai(e.args[g],"params."+g,k,t),500<=t);g++);else if(e.hasOwnProperty("params")&&e.params){var p=e.params;if("object"===typeof e.params)for(g in p){if(p[g]){var x="params."+g,A=Ci(p[g]);k[x]=A;t+=x.length+A.length;if(500<t)break}}else k.params=Ci(p)}if(Hi.length)for(g=0;g<Hi.length&&!(t=Ai(Hi[g],"params.context."+
g,k,t),500<=t);g++);navigator.vendor&&!k.hasOwnProperty("vendor")&&(k["device.vendor"]=navigator.vendor);g={message:f,name:h,lineNumber:q,fileName:l,stack:m,params:k,sampleWeight:1};f=Number(e.columnNumber);isNaN(f)||(g.lineNumber=g.lineNumber+":"+f);if("IGNORED"===e.level)e=0;else a:{e=wi();f=u(e.K);for(h=f.next();!h.done;h=f.next())if(h=h.value,g.message&&g.message.match(h.jb)){e=h.weight;break a}e=u(e.I);for(f=e.next();!f.done;f=e.next())if(f=f.value,f.Aa(g)){e=f.weight;break a}e=1}g.sampleWeight=
e;e=g;g=u(ri);for(f=g.next();!f.done;f=g.next())if(f=f.value,f.aa[e.name])for(q=u(f.aa[e.name]),h=q.next();!h.done;h=q.next())if(l=h.value,h=e.message.match(l.regexp)){e.params["params.error.original"]=h[0];q=l.groups;l={};for(m=0;m<q.length;m++)l[q[m]]=h[m+1],e.params["params.error."+q[m]]=h[m+1];e.message=f.fa(l);break}e.params||(e.params={});g=wi();e.params["params.errorServiceSignature"]="msg="+g.K.length+"&cb="+g.I.length;e.params["params.serviceWorker"]="false";z.document&&z.document.querySelectorAll&&
(e.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));hb("sample").constructor!==fb&&(e.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(e);if(0!==e.sampleWeight&&!Di.has(e.message)){"ERROR"===d?(xi.O("handleError",e),Q("record_app_crashed_web")&&0===Gi&&1===e.sampleWeight&&(Gi++,qi("appCrashed",{appCrashType:"APP_CRASH_TYPE_BREAKPAD"})),Fi++):"WARNING"===d&&xi.O("handleWarning",e);if(Q("kevlar_gel_error_routing")){g=
d;l=e;b:{f=u(Ii);for(h=f.next();!h.done;h=f.next())if(Ef(h.value.toLowerCase())){f=!0;break b}f=!1}if(f)f=void 0;else{h={stackTrace:l.stack};l.fileName&&(h.filename=l.fileName);f=l.lineNumber&&l.lineNumber.split?l.lineNumber.split(":"):[];0!==f.length&&(1!==f.length||isNaN(Number(f[0]))?2!==f.length||isNaN(Number(f[0]))||isNaN(Number(f[1]))||(h.lineNumber=Number(f[0]),h.columnNumber=Number(f[1])):h.lineNumber=Number(f[0]));f={level:"ERROR_LEVEL_UNKNOWN",message:l.message,errorClassName:l.name,sampleWeight:l.sampleWeight};
"ERROR"===g?f.level="ERROR_LEVEL_ERROR":"WARNING"===g&&(f.level="ERROR_LEVEL_WARNNING");h={isObfuscated:!0,browserStackInfo:h};q={pageUrl:window.location.href,kvPairs:[]};N("FEXP_EXPERIMENTS")&&(q.experimentIds=N("FEXP_EXPERIMENTS"));if(l=l.params)for(m=u(Object.keys(l)),k=m.next();!k.done;k=m.next())k=k.value,q.kvPairs.push({key:"client."+k,value:String(l[k])});l=N("SERVER_NAME",void 0);m=N("SERVER_VERSION",void 0);l&&m&&(q.kvPairs.push({key:"server.name",value:l}),q.kvPairs.push({key:"server.version",
value:m}));f={errorMetadata:q,stackTrace:h,logMessage:f}}f&&(qi("clientError",f),("ERROR"===g||Q("errors_flush_gel_always_killswitch"))&&cg())}if(!Q("suppress_error_204_logging")){f=e;g=f.params||{};d={urlParams:{a:"logerror",t:"jserror",type:f.name,msg:f.message.substr(0,250),line:f.lineNumber,level:d,"client.name":g.name},postParams:{url:N("PAGE_NAME",window.location.href),file:f.fileName},method:"POST"};g.version&&(d["client.version"]=g.version);if(d.postParams){f.stack&&(d.postParams.stack=f.stack);
f=u(Object.keys(g));for(h=f.next();!h.done;h=f.next())h=h.value,d.postParams["client."+h]=g[h];if(g=N("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(f=u(Object.keys(g)),h=f.next();!h.done;h=f.next())h=h.value,d.postParams[h]=g[h];g=N("SERVER_NAME",void 0);f=N("SERVER_VERSION",void 0);g&&f&&(d.postParams["server.name"]=g,d.postParams["server.version"]=f)}vf(N("ECATCHER_REPORT_HOST","")+"/error_204",d)}Di.add(e.message);Ei++}}}}}else throw v;}else console&&console.warn&&console.warn("The YouTube player is not attached to the DOM. API calls should be made after the onReady event. See more: https://developers.google.com/youtube/iframe_api_reference#Events")};function aj(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function bj(a){return 0===a.search("get")||0===a.search("is")}
;function cj(a,b){Ui.call(this,a,Object.assign({title:"video player",videoId:"",width:640,height:360},b||{}),"player");this.F={};this.playerInfo={}}
oa(cj,Ui);n=cj.prototype;n.ka=function(){var a=Z(this.i,"playerVars");if(a){var b={},c;for(c in a)b[c]=a[c];a=b}else a={};window!==window.top&&document.referrer&&(a.widget_referrer=document.referrer.substring(0,256));if(c=Z(this.i,"embedConfig")){if(C(c))try{c=JSON.stringify(c)}catch(d){console.error("Invalid embed config JSON",d)}a.embed_config=c}return a};
n.ha=function(a){var b=a.event;a=a.info;switch(b){case "apiInfoDelivery":if(C(a))for(var c in a)a.hasOwnProperty(c)&&(this.F[c]=a[c]);break;case "infoDelivery":dj(this,a);break;case "initialDelivery":C(a)&&(window.clearInterval(this.j),this.playerInfo={},this.F={},ej(this,a.apiInterface),dj(this,a));break;default:Vi(this,b,a)}};
function dj(a,b){if(C(b))for(var c in b)b.hasOwnProperty(c)&&(a.playerInfo[c]=b[c])}
function ej(a,b){G(b,function(c){this[c]||("getCurrentTime"===c?this[c]=function(){var d=this.playerInfo.currentTime;if(1===this.playerInfo.playerState){var e=(Date.now()/1E3-this.playerInfo.currentTimeLastUpdated_)*this.playerInfo.playbackRate;0<e&&(d+=Math.min(e,1))}return d}:aj(c)?this[c]=function(){this.playerInfo={};
this.F={};Yi(this,c,arguments);return this}:bj(c)?this[c]=function(){var d=0;
0===c.search("get")?d=3:0===c.search("is")&&(d=2);return this.playerInfo[c.charAt(d).toLowerCase()+c.substr(d+1)]}:this[c]=function(){Yi(this,c,arguments);
return this})},a)}
n.getVideoEmbedCode=function(){var a=Z(this.i,"host")+("/embed/"+Z(this.i,"videoId")),b=Number(Z(this.i,"width")),c=Number(Z(this.i,"height"));if(isNaN(b)||isNaN(c))throw Error("Invalid width or height property");b=Math.floor(b);c=Math.floor(c);a=jb(a,void 0);return'<iframe width="'+b+'" height="'+c+'" src="'+a+'" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'};
n.getOptions=function(a){return this.F.namespaces?a?this.F[a]?this.F[a].options||[]:[]:this.F.namespaces||[]:[]};
n.getOption=function(a,b){if(this.F.namespaces&&a&&b&&this.F[a])return this.F[a][b]};
function fj(a){if("iframe"!==a.tagName.toLowerCase()){var b=Pi(a,"videoid");b&&(b={videoId:b,width:Pi(a,"width"),height:Pi(a,"height")},new cj(a,b))}}
;E("YT.PlayerState.UNSTARTED",-1);E("YT.PlayerState.ENDED",0);E("YT.PlayerState.PLAYING",1);E("YT.PlayerState.PAUSED",2);E("YT.PlayerState.BUFFERING",3);E("YT.PlayerState.CUED",5);E("YT.get",function(a){return Li[a]});
E("YT.scan",Oi);E("YT.subscribe",function(a,b,c){ke.subscribe(a,b,c);Ni[a]=!0;for(var d in Li)Li.hasOwnProperty(d)&&Xi(Li[d],a)});
E("YT.unsubscribe",function(a,b,c){je(a,b,c)});
E("YT.Player",cj);Ui.prototype.destroy=Ui.prototype.destroy;Ui.prototype.setSize=Ui.prototype.setSize;Ui.prototype.getIframe=Ui.prototype.za;Ui.prototype.addEventListener=Ui.prototype.addEventListener;cj.prototype.getVideoEmbedCode=cj.prototype.getVideoEmbedCode;cj.prototype.getOptions=cj.prototype.getOptions;cj.prototype.getOption=cj.prototype.getOption;
Mi.push(function(a){var b=a;b||(b=document);a=Wa(b.getElementsByTagName("yt:player"));var c=b||document;if(c.querySelectorAll&&c.querySelector)b=c.querySelectorAll(".yt-player");else{var d;c=document;b=b||c;if(b.querySelectorAll&&b.querySelector)b=b.querySelectorAll(".yt-player");else if(b.getElementsByClassName){var e=b.getElementsByClassName("yt-player");b=e}else{e=b.getElementsByTagName("*");var f={};for(c=d=0;b=e[c];c++){var g=b.className,h;if(h="function"==typeof g.split)h=0<=Sa(g.split(/\s+/),
"yt-player");h&&(f[d++]=b)}f.length=d;b=f}}b=Wa(b);G(Va(a,b),fj)});
"undefined"!=typeof YTConfig&&YTConfig.parsetags&&"onload"!=YTConfig.parsetags||Oi();var gj=z.onYTReady;gj&&gj();var hj=z.onYouTubeIframeAPIReady;hj&&hj();var ij=z.onYouTubePlayerAPIReady;ij&&ij();}).call(this);
