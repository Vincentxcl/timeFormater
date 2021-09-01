y:year
MM:month
d:day
h:hour
m:minutes
s:second
q:quarter
S：Millisecond

forexample:
var tt = new Date();
console.log(tt);
Wed Sep 01 2021 14:40:38 GMT+0800 (China Standard Time)

console.log(tt.Format("yyyy-MM-dddd-h-m-s-q-S"));
2021-09-01-14-40-38-3-928
